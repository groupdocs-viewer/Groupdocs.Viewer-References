---
title: "从本地磁盘加载文档"
linkTitle: "Load from local disk"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "使用 GroupDocs.Viewer for Python via .NET，通过文件路径从本地磁盘加载文档。"
type: docs
url: /zh/python-net/guides/load-document-from-local-disk/
is_root: false
weight: 50
---


您可以使用文件路径从本地磁盘加载文档。GroupDocs.Viewer 以只读模式打开文件。

以下代码片段展示了如何使用本地路径字符串加载文档：

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_local_disk():
    # 从本地磁盘加载文档
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_embedded_resources("load_document_from_local_disk/document_from_local_disk_{0}.html")
        viewer.view(html_options)

if __name__ == "__main__":
    load_document_from_local_disk()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-local-disk/sample.docx) 下载。

{{< /tab >}}
{{< tab \"load-document-from-local-disk-outputs.zip\" >}}
```text
load_document_from_local_disk/document_from_local_disk_1.html (317 KB)
load_document_from_local_disk/document_from_local_disk_2.html (149 KB)
load_document_from_local_disk/document_from_local_disk_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-local-disk/load_document_from_local_disk/load-document-from-local-disk-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
