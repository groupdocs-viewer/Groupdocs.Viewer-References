---
title: "for_embedded_resources メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "埋め込みリソースで HTML をレンダリングするための HtmlViewOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

埋め込みリソースで HTML をレンダリングするための HtmlViewOptions インスタンスを初期化します。

詳細については、ドキュメントをご覧ください。

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `create_page_stream` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

埋め込みリソースで HTML にレンダリングするための [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) クラスのインスタンスを初期化します。

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| release_page_stream | `ReleasePageStream` | `create_page_stream` パラメータに割り当てられたメソッドが作成したストリームを解放するメソッドです。 |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `release_page_stream` が `None` の場合。コード例については、ドキュメントをご覧ください。 |

## for_embedded_resources {#page_stream_factory}

埋め込みリソースで HTML にレンダリングするための HtmlViewOptions インスタンスを初期化します。

コード例については、https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources のドキュメントをご覧ください。

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 出力ページストリームの作成と解放のメソッドを実装するファクトリです。 |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | page_stream_factory が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

埋め込みリソース付きの [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) クラスのインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def for_embedded_resources(cls):
    ...
```

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

埋め込みリソース用の HtmlViewOptions インスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path_format | `str` | ファイルパス形式（例: 'page_{0}.html'）です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_path_format` が None または空の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### 参照
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
