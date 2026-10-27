---
title: "حماية مستند PDF"
linkTitle: "Protect PDF document"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "أمّن مخرجات PDF باستخدام كلمات مرور وأذونات عند عرض المستندات باستخدام GroupDocs.Viewer."
type: docs
url: /ar/python-net/guides/protect-pdf-document/
is_root: false
weight: 90
---


يمكنك حماية مستند PDF عن طريق تعيين المعلمات التالية:

* permissions
* password to open document
* password to change permissions

لحماية مستند PDF، اتبع الخطوات التالية:

1. أنشئ مثيلًا من فئة [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). حدّد مسار المستند المصدر كمعامل للمنشئ.
2. إنشاء كائن [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security).
3. لتحديد كلمة مرور لفتح المستند، اضبط خاصية [DocumentOpenPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
4. لتحديد كلمة مرور لتغيير القيود، اضبط خاصية [PermissionsPassword](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/security/#properties).
5. لتحديد أذونات المستند، اضبط خاصية [Permissions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/permissions).
6. إنشاء كائن [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions). حدد تنسيق مسار الحفظ للمستند المُعالج.
7. تهيئة خاصية [Security](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/#properties) لكائن [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) باستخدام الكائن الذي تم إنشاؤه في الخطوات 2-5.
8. استدعاء طريقة [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) لكائن [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). حدد كائن [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) كمعامل.

المقتطف البرمجي التالي يوضح كيفية حماية مستند PDF الناتج:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

def protect_pdf_document():
    # تحميل المستند
    with Viewer("sample.docx") as viewer:
        # حدد إعدادات الأمان.
        security = Security()
        security.document_open_password = "o123"
        security.permissions_password = "p123"
        security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

        # إنشاء ملف PDF.
        pdf_options = PdfViewOptions("protect_pdf_document/protected_document.pdf")

        # تطبيق إعدادات الأمان
        pdf_options.security = security
        viewer.view(pdf_options)

if __name__ == "__main__":
    protect_pdf_document()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` هو الملف النموذجي المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/sample.docx) لتنزيله.

{{< /tab >}}
{{< tab \"protected_document.pdf\" >}}
```text
Binary file (PDF, 238 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/protect-pdf-document/protect_pdf_document/protected_document.pdf)
{{< /tab >}}
{{< /tabs >}}
