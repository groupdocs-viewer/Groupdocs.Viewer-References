---
title: "ArchiveViewInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "アーカイブファイルのビュー情報を表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

アーカイブファイルのビュー情報を表します。

ArchiveViewInfo 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | 新しい [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/) インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | 新しい ArchiveViewInfo インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 現在のオブジェクトを表す文字列を返します。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | アーカイブファイルに含まれるフォルダーです。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | ファイルの種類です。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 表示するページのリストです。 ( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### 例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
`ArchiveViewInfo` を使用するタスクガイド：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 参照
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
