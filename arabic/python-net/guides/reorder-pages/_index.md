---
title: "إعادة ترتيب الصفحات"
linkTitle: "Reorder pages"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "إعادة ترتيب صفحات PDF أثناء العرض باستخدام GroupDocs.Viewer للبايثون عبر .NET. التحكم في تسلسل الصفحات الناتجة."
type: docs
url: /ar/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


يحافظ GroupDocs.Viewer على ترتيب الصفحات في المستند الأصلي. بدلاً من ذلك، يمكنك إعادة ترتيب الصفحات في مستند PDF الناتج.

لإعادة ترتيب الصفحات، اتبع الخطوات التالية:

1. أنشئ كائن [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer).
2. أنشئ كائن [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions).
3. استدعِ طريقة [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) لكائن [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). حدّد ترتيب الصفحات الجديد في المعلمات الأخيرة.

المقتطف البرمجي التالي يوضح كيفية إعادة ترتيب الصفحات:

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # تحميل المستند
    with Viewer("sample.docx") as viewer:
        # أنشئ خيارات العرض.
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # مرّر أرقام الصفحات بالترتيب الذي تريد عرضها به.
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` هو الملف النموذجي المستخدم في هذا المثال. اضغط [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) لتنزيله.

{{< /tab >}}
{{< tab "reordered_pages.pdf" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
