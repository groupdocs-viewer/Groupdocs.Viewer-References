---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ProjectManagementViewInfo の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) のインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

ProjectManagementViewInfo の新しいインスタンスを初期化します。

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_type | `FileType` | ファイルの種類です。 |
| pages | `List[Page]` | 表示するページのリストです。 |
| start_date | `datetime` | プロジェクトが開始された日時です。 |
| end_date | `datetime` | プロジェクトが完了する日時です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | もし `pages` が None の場合。 |

### 参照
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
