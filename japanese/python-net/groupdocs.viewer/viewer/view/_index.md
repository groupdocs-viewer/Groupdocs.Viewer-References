---
title: "view メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "すべてのドキュメントページのビューを作成します。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

すべてのドキュメントページのビューを作成します。

詳しく見る

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | `ViewOptions` | ビューオプション。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `options` が None の場合。 |
| `PasswordRequiredException` | ドキュメントを開くのにパスワードが必要な場合。 |
| `IncorrectPasswordException` | 指定されたパスワードが正しくない場合。 |
| `GroupDocsViewerException` | 添付ファイルが見つからなかった場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

特定のドキュメントページのビューを作成します。

詳しく見る

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | `ViewOptions` | ビューオプション。 |
| page_numbers | `list[int]` | 表示するページ番号。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `page_numbers` が空の場合。 |
| `PasswordRequiredException` | ドキュメントを開くのにパスワードが必要な場合。 |
| `IncorrectPasswordException` | 指定されたパスワードが正しくない場合。 |
| `GroupDocsViewerException` | 添付ファイルが見つからない場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

特定のドキュメントページのビューを作成します。

詳しく読む:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | `ViewOptions` | ビューオプション。 |
| cancellation_token | `CancellationToken` | 処理をキャンセルするためのキャンセルトークン。 |
| page_numbers | `list[int]` | 表示するページ番号。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `page_numbers` が空の場合。 |
| `PasswordRequiredException` | ドキュメントを開くのにパスワードが必要な場合。 |
| `IncorrectPasswordException` | 指定されたパスワードが正しくない場合。 |
| `GroupDocsViewerException` | 添付ファイルが見つからない場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### 参照
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
