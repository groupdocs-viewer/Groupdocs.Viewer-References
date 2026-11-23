---
title: "get_view_info メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ビューおよびドキュメント固有の情報を返します。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

ビューおよびドキュメント固有の情報を返します。

ドキュメントのファイルタイプ、ページ数、その他のフォーマット固有のプロパティの詳細は次のとおりです：
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | `ViewInfoOptions` | ビュー情報オプションです。 |

**Returns:** Information about view and document specific information.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `options` が None の場合。 |
| `PasswordRequiredException` | ドキュメントを開くのにパスワードが必要な場合。 |
| `IncorrectPasswordException` | 指定されたパスワードが正しくない場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### 参照
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
