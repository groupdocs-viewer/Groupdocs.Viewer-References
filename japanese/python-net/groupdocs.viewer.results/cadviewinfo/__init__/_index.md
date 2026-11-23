---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "CadViewInfo の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

CadViewInfo の新しいインスタンスを初期化します。

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_type | `FileType` | ファイルの種類です。 |
| pages | `List[Page]` | 表示するページのリストです。 |
| layers | `List[Layer]` | CAD 図面に含まれるレイヤーの一覧です。 |
| layouts | `List[Layout]` | CAD 図面に含まれるレイヤーの一覧です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `layouts` が None のときにスローされます。 |

### 参照
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
