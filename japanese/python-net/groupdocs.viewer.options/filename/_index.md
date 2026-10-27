---
title: "FileName クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイル名。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

ファイル名。

FileName 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) クラスのインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | 現在のオブジェクトを表す文字列を返します。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | 空のファイル名。 |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | ソースファイルの名前。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
