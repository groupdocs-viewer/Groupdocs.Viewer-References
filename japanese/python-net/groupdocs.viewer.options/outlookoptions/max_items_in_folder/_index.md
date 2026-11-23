---
title: "max_items_in_folder プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "1つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

1つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数。

Outlook データ ファイルは大きくなることがあり、すべてのメッセージを取得するのにかなりの時間がかかります。このプロパティはレンダリングされるメッセージまたはアイテムの最大数を制限します。デフォルト値は `50` です。すべてのメッセージをレンダリングするには、値を `0` に設定します。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### 参照
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
