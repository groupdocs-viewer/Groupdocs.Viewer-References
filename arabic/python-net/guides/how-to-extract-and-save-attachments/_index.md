---
title: "حفظ المرفقات"
linkTitle: "Save attachments"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "استرجاع وحفظ المرفقات من رسائل البريد الإلكتروني، ملفات Outlook، الأرشيفات، وملفات PDF."
type: docs
url: /ar/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


للحصول على المرفقات وحفظها، اتبع الخطوات التالية:

1. إنشاء كائن [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/). حدد ملفًا يحتوي على مرفقات.
2. استدعاء طريقة [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods). تُعيد مجموعة المرفقات.
3. التكرار عبر المجموعة. لحفظ مرفق، استدعِ طريقة [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

يظهر المقتطف البرمجي التالي كيفية الحصول على جميع المرفقات وحفظها من ملف MSG:

ملاحظة: المقتطف البرمجي المقدم يناسب جميع عائلات الصيغ التي تدعم المرفقات: رسائل البريد الإلكتروني، ملفات بيانات Outlook، الأرشيفات، ومستندات PDF.

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # تحميل مستند مع مرفقات
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # حفظ المرفق على القرص
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) لتنزيله.

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
