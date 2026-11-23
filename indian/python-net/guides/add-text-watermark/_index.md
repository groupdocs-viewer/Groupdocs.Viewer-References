---
title: "टेक्स्ट वॉटरमार्क जोड़ें"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "अपने Python एप्लिकेशन में GroupDocs.Viewer का उपयोग करके रेंडर किए गए दस्तावेज़ों में टेक्स्ट वॉटरमार्क जोड़ें।"
type: docs
url: /hi/python-net/guides/add-text-watermark/
is_root: false
weight: 80
---


HTML/JPG/PNG/PDF आउटपुट में वॉटरमार्क जोड़ने के लिए, इन चरणों का पालन करें:

1. [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) क्लास (या [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), या [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), या [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)) का एक इंस्टेंस बनाएं;
2. एक [Watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/watermark/) ऑब्जेक्ट बनाएं और उसकी प्रॉपर्टीज़ को भरें;
3. [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (या [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), या [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), या [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)) क्लास की [watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/viewoptions/#properties) मेथड को कॉल करें और चरण 2 में बनाए गए ऑब्जेक्ट को निर्दिष्ट करें;
4. [Viewer.view()](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) मेथड को कॉल करें।

निम्नलिखित कोड स्निपेट दिखाता है कि आउटपुट पृष्ठों पर वॉटरमार्क कैसे लागू किया जाए।

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # दस्तावेज़ लोड करें
    with Viewer("sample.docx") as viewer:
        # एक HTML फ़ाइल बनाएं।
        viewOptions = HtmlViewOptions.for_embedded_resources("add_text_watermark/output-watermark.html")
        # वॉटरमार्क जोड़ें।
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/add-text-watermark/sample.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"output-watermark.html\" >}}
```text
<!DOCTYPE html><html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><meta name="generator" content="Aspose.Words for .NET 26.4.0" /><title>Sample Document ver.1</title><style type="text/css">@font-face { font-family:'Calibri'; font-style:normal; font-weight:normal; src:local('☺'), url('data:application/x-font-woff;base64,d09GRgABAAAAAGlIAA0AAAAA09gAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABPUy8yAAABMAAAAGAAAABgncM96GNtYXAAAAGQAAACswAABrCp8yKHY3Z0IAAABEQAAAKEAAAFvLlw2DVmcGdtAAAGy
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/add-text-watermark/add_text_watermark/output-watermark.html)
{{< /tab >}}
{{< /tabs >}}
