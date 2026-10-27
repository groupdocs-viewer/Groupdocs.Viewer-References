---
title: "for_pdf_view 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个 ViewInfoOptions 实例，以在渲染为 PDF 时检索视图信息。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/
is_root: false
weight: 1050
---


## for_pdf_view

初始化一个 ViewInfoOptions 实例，以在渲染为 PDF 时检索视图信息。

```python
def for_pdf_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 示例

```python
    from groupdocs.viewer.options import ViewInfoOptions

    # 为 PDF 格式创建视图信息选项
    view_info_options_pdf = ViewInfoOptions.for_pdf_view()
    ```

### 另见
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
