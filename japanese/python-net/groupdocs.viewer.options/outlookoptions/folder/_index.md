---
title: "folder プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "フォルダーの名前 (例:"
type: docs
url: /ja/python-net/groupdocs.viewer.options/outlookoptions/folder/
is_root: false
weight: 2020
---


## folder property

レンダリングするフォルダーの名前（例: Inbox、Sent Item、Deleted Items）。

Outlook データ ファイルをレンダリングする際、GroupDocs.Viewer はファイルに含まれるすべてのフォルダー（ネストされたフォルダーを含む）からメッセージをレンダリングします。このプロパティを使用して、特定のフォルダーのアイテムをレンダリングします。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def folder(self):
    ...
@folder.setter
def folder(self, value):
    ...
```

### 参照
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
