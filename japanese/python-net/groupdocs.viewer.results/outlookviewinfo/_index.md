---
title: "OutlookViewInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Outlook データ ファイルのビュー情報を表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Outlook データ ファイルのビュー情報を表します。

OutlookViewInfo 型は、次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | 新しい [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) のインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | 新しい OutlookViewInfo インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 現在のオブジェクトを表す文字列を返します。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Outlook データ ファイルに含まれるフォルダーの一覧です。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | ファイルの種類です。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 表示するページのリストです。 ( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### 例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
`OutlookViewInfo` を使用するタスク ガイド：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 参照
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
