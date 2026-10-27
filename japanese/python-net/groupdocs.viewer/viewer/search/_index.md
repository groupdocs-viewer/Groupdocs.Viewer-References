---
title: "search メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "テキスト検索を実行し、提供されたオプションに従ってロードされたドキュメント内で見つかったテキストをハイライトします。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

テキスト検索を実行し、提供されたオプションに従ってロードされたドキュメント内で見つかったテキストをハイライトします。

```python
def search(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | `SearchHighlightOptions` | 検索およびハイライトオプション（検索するテキストフレーズを含む）。None であってはなりません。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `options` が None の場合。 |

### 参照
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
