---
title: "إضافة علامات مائية نصية"
linkTitle: "Add text watermarks"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "إضافة علامات مائية نصية إلى المستندات المُعالجة باستخدام GroupDocs.Viewer في تطبيقات Python الخاصة بك."
type: docs
url: /ar/python-net/guides/add-text-watermark/
is_root: false
weight: 80
---


لإضافة علامة مائية إلى مخرجات HTML/JPG/PNG/PDF، اتبع الخطوات التالية:

1. أنشئ مثيلاً من الفئة [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (أو [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)، أو [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)، أو [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/));
2. أنشئ كائنًا من النوع [Watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/watermark/) واملأ خصائصه؛
3. استدعِ طريقة [watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/viewoptions/#properties) للفئة [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (أو [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)، أو [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)، أو [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)) وحدد الكائن الذي تم إنشاؤه في الخطوة 2؛
4. استدعِ طريقة [Viewer.view()](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

تظهر مقتطف الشيفرة التالي كيفية تطبيق العلامة المائية على صفحات الإخراج.

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # تحميل المستند
    with Viewer("sample.docx") as viewer:
        # إنشاء ملف HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources("add_text_watermark/output-watermark.html")
        # إضافة علامة مائية.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` هو ملف العينة المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/add-text-watermark/sample.docx) لتنزيله.

{{< /tab >}}
{{< tab "output-watermark.html" >}}
```text
<!DOCTYPE html><html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><meta name="generator" content="Aspose.Words for .NET 26.4.0" /><title>Sample Document ver.1</title><style type="text/css">@font-face { font-family:'Calibri'; font-style:normal; font-weight:normal; src:local('☺'), url('data:application/x-font-woff;base64,d09GRgABAAAAAGlIAA0AAAAA09gAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABPUy8yAAABMAAAAGAAAABgncM96GNtYXAAAAGQAAACswAABrCp8yKHY3Z0IAAABEQAAAKEAAAFvLlw2DVmcGdtAAAGy
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/add-text-watermark/add_text_watermark/output-watermark.html)
{{< /tab >}}
{{< /tabs >}}
