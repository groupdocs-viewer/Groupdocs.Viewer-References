---
title: "try_repair プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは、GroupDocs.Viewer が PDF ドキュメントの構造的破損の修復を試みることを可能にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

このプロパティは、GroupDocs.Viewer が PDF ドキュメントの構造的破損の修復を試みることを可能にします。デフォルトは False です。

この機能は、PDF ドキュメントの次の問題に対処します：

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### 参照
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
