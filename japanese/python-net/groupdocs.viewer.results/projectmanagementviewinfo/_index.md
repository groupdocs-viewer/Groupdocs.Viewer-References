---
title: "ProjectManagementViewInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "MS Project ドキュメントのビュー情報を表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

MS Project ドキュメントのビュー情報を表します。

ProjectManagementViewInfo 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | 新しい [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) のインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | ProjectManagementViewInfo の新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 現在のオブジェクトを表す文字列を返します。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | プロジェクトが完了する日時です。 |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | プロジェクトが開始された日時です。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | ファイルの種類です。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 表示するページのリストです。 ( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### 例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
`ProjectManagementViewInfo` を使用するタスク ガイド:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 参照
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
