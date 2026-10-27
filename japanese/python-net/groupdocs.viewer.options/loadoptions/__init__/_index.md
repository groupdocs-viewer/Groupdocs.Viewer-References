---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "LoadOptions クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) クラスのインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

新しい LoadOptions インスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def __init__(self, file_type):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_type | `FileType` | 開くファイルのタイプ。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_type` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### 参照
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
