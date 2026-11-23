---
title: "添加文本水印"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "在您的 Python 应用程序中使用 GroupDocs.Viewer 为渲染的文档添加文本水印。"
type: docs
url: /zh/python-net/guides/add-text-watermark/
is_root: false
weight: 80
---


要向 HTML/JPG/PNG/PDF 输出添加水印，请按照以下步骤操作：

1. 创建 [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 类的实例（或 [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)、[JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)、[PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) 的实例）；
2. 创建一个 [Watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/watermark/) 对象并填充其属性；
3. 调用 [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 类的 [watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/viewoptions/#properties) 方法（或 [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)、[JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) 或 [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)），并指定在第 2 步创建的对象；
4. 调用 [Viewer.view()](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) 方法。

以下代码片段展示了如何将水印应用于输出页面。

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # 加载文档
    with Viewer("sample.docx") as viewer:
        # 创建 HTML 文件。
        viewOptions = HtmlViewOptions.for_embedded_resources("add_text_watermark/output-watermark.html")
        # 添加水印。
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例使用的示例文件。点击 [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/add-text-watermark/sample.docx) 下载它。

{{< /tab >}}
{{< tab \"output-watermark.html\" >}}
```text
<!DOCTYPE html><html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><meta name="generator" content="Aspose.Words for .NET 26.4.0" /><title>Sample Document ver.1</title><style type="text/css">@font-face { font-family:'Calibri'; font-style:normal; font-weight:normal; src:local('☺'), url('data:application/x-font-woff;base64,d09GRgABAAAAAGlIAA0AAAAA09gAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABPUy8yAAABMAAAAGAAAABgncM96GNtYXAAAAGQAAACswAABrCp8yKHY3Z0IAAABEQAAAKEAAAFvLlw2DVmcGdtAAAGy
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/add-text-watermark/add_text_watermark/output-watermark.html)
{{< /tab >}}
{{< /tabs >}}
