---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "FileName クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

[`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) クラスのインスタンスを初期化します。

```python
def __init__(self, file_name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_name | `str` | ファイルの名前です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_name` が None の場合。 |

### 例

```python
from groupdocs.viewer.options import FileName

# カスタムアーカイブ名で FileName インスタンスを作成します
custom_name = FileName("Sample Files")
```

### 参照
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
