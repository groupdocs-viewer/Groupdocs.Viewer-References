---
title: "重新排序页面"
linkTitle: "Reorder pages"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "在使用 GroupDocs.Viewer for Python via .NET 渲染时重新排序 PDF 页面。控制输出页面顺序。"
type: docs
url: /zh/python-net/guides/reorder-pages/
is_root: false
weight: 100
---


GroupDocs.Viewer 保持源文档中的页面顺序。相反，您可以在输出 PDF 文档中重新排序页面。

要重新排序页面，请按照以下步骤：

1. 实例化 [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) 对象。
2. 创建 [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) 对象。
3. 调用 [view](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) 方法于 [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer) 对象。 在最后的参数中指定新的页面顺序。

以下代码片段展示了如何重新排序页面：

{{< tabs "example1">}}
{{< tab "Python">}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def reorder_pages():
    # 加载文档
    with Viewer("sample.docx") as viewer:
        # 创建视图选项。
        viewOptions = PdfViewOptions("reorder_pages/reordered_pages.pdf")

        # 按您希望渲染的顺序传递页码。
        viewer.view(viewOptions, [2, 1])

if __name__ == "__main__":
    reorder_pages()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是此示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/sample.docx) 下载。

{{< /tab >}}
{{< tab "reordered_pages.pdf" >}}
```text
Binary file (PDF, 176 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/rendering-to-pdf/reorder-pages/reorder_pages/reordered_pages.pdf)
{{< /tab >}}
{{< /tabs >}}
