---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "PdfViewInfo の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

PdfViewInfo の新しいインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

PdfViewInfo の新しいインスタンスを初期化します。

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_type | `FileType` | ファイルの種類です。 |
| pages | `List[Page]` | 表示するページのリストです。 |
| printing_allowed | `bool` | 印刷許可インジケータ。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `pages` が None の場合。 |

### 参照
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
