---
title: "max_items_in_folder 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "可以从单个文件夹呈现的最大消息或项目数量。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

可以从单个文件夹呈现的最大消息或项目数量。

Outlook 数据文件可能很大，检索所有消息可能需要相当长的时间。此属性限制渲染的消息或项目的最大数量。默认值为 `50`。若要渲染所有消息，请将该值设为 `0`。

有关代码示例，请参阅文档。

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### 另见
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
