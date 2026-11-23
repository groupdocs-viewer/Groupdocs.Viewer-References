---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "OutlookViewInfo の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) のインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

新しい OutlookViewInfo インスタンスを初期化します。

```python
def __init__(self, file_type, pages, folders):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_type | `FileType` | ファイルの種類です。 |
| pages | `List[Page]` | 表示するページのリストです。 |
| folders | `List[str]` | Outlook データファイルに含まれるフォルダーの一覧です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `folders` が None の場合にスローされます。 |

### 参照
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
