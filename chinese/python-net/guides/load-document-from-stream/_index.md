---
title: "从流加载文档"
linkTitle: "Load from stream"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "使用基于 .NET 的 GroupDocs.Viewer for Python，直接从类文件对象（如打开的文件句柄、BytesIO 或任何流）加载文档。"
type: docs
url: /zh/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


您可以从流加载文档，而无需将其保存为磁盘上的文件。此功能可用于从不同来源（如 URL、FTP 等）加载文档。

要从流加载文档，请按照以下步骤操作：

1. 实现一个获取文档流的方法。
2. 调用 [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) 类构造函数。指定在上一步实现的方法。

以下代码片段展示了如何从流加载文档：

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # 打开文档流
    stream = open("sample.docx", "rb")

    # 从流渲染文档。
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) 下载。

{{< /tab >}}
{{< tab \"load-document-from-stream-outputs.zip\" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

另请参阅 [Load document from URL]()，了解将文档下载到 `BytesIO` 流并在不写入磁盘的情况下渲染的具体示例。
