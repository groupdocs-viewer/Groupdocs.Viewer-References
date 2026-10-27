---
title: "max_items プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "レンダリングするメッセージまたはアイテムの最大数。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/mailstorageoptions/max_items/
is_root: false
weight: 2020
---


## max_items property

レンダリングするメッセージまたはアイテムの最大数。

メールストレージデータファイルはサイズが大きくなることがあり、すべてのメッセージを取得するのにかなりの時間がかかる場合があります。このプロパティは、レンダリングされるメッセージまたはアイテムの最大数を制限します。デフォルト値は 0 で、すべてのメッセージがレンダリングされます。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def max_items(self):
    ...
@max_items.setter
def max_items(self, value):
    ...
```

### 参照
* class [`MailStorageOptions`](/viewer/python-net/groupdocs.viewer.options/mailstorageoptions/)
