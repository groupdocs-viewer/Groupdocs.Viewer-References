---
title: "ArchiveOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "アーカイブファイルのレンダリングオプションを含みます。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

アーカイブファイルのレンダリングオプションを含みます。

ArchiveOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) クラスのインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | 表示されるアーカイブファイル名。 |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | レンダリング対象のフォルダー。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
