---
title: "свойство remove_comments"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство отключает рендеринг комментариев, когда установлено в True."
type: docs
url: /ru/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

Свойство отключает отображение комментариев, когда установлено в True. По умолчанию оно False, поэтому все комментарии отображаются.

Некоторые форматы документов, такие как PDF и WordProcessing, могут содержать комментарии. По умолчанию GroupDocs.Viewer их рендерит. При установке этой опции в True комментарии могут быть исключены из результирующего документа.

Эта опция заменяет устаревшее свойство `RenderComments`.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### См. также
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
