---
title: "max_items 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "要渲染的消息或项目的最大数量。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/mailstorageoptions/max_items/
is_root: false
weight: 2020
---


## max_items property

要渲染的消息或项目的最大数量。

邮件存储数据文件可能很大，检索所有消息可能需要相当长的时间。此属性限制渲染的消息或项目的最大数量。默认值为 0 —— 渲染所有消息。

有关代码示例，请参阅文档。

### Definition:
```python
@property
def max_items(self):
    ...
@max_items.setter
def max_items(self, value):
    ...
```

### 另见
* class [`MailStorageOptions`](/viewer/python-net/groupdocs.viewer.options/mailstorageoptions/)
