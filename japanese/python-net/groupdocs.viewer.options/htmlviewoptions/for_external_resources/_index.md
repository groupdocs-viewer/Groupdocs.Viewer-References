---
title: "for_external_resources メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "外部リソースで HTML にレンダリングするための HtmlViewOptions クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

外部リソースで HTML にレンダリングするための [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) クラスのインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| create_resource_stream | `CreateResourceStream` | `create_page_stream` メソッドで作成されたストリームを解放するメソッド。 |
| create_resource_url | `CreateResourceUrl` | HTML リソースの URL を作成するメソッド。 |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `create_resource_url` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

外部リソースで HTML にレンダリングするための HtmlViewOptions クラスのインスタンスを初期化します。

追加の使用例については、GroupDocs Viewer のドキュメントをご覧ください。

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| create_resource_stream | `CreateResourceStream` | 出力 HTML リソースデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| create_resource_url | `CreateResourceUrl` | HTML リソースの URL を作成するメソッド。 |
| release_page_stream | `ReleasePageStream` | `create_page_stream` に渡されたデリゲートが作成したストリームを解放するメソッド。 |
| release_resource_stream | `ReleaseResourceStream` | `create_resource_stream` に渡されたデリゲートが作成したストリームを解放するメソッド。 |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `release_resource_stream` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Excel スプレッドシートを読み込む
    with Viewer("invoice.xlsx") as viewer:
        # スプレッドシートを外部リソース付きの HTML に変換する。
        # {0} と {1} はそれぞれ現在のページ番号とリソース名に置き換えられます。
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

外部リソースで HTML にレンダリングするための HtmlViewOptions インスタンスを初期化します。

詳細については、オンラインドキュメントをご覧ください。

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 出力ページストリームを作成および解放するメソッドを実装するファクトリです。 |
| resource_stream_factory | `IResourceStreamFactory` | リソースURLの作成、インスタンス化、および出力HTMLリソースストリームの解放に必要なメソッドを実装するファクトリです。 |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `resource_stream_factory` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # 各ページごとにHTMLファイルを作成し、外部リソースを別々に保存します。
    # {0} と {1} はそれぞれ現在のページ番号とリソース名に置き換えられます。
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

外部リソース付きの HTML ファイルを生成するように構成された HtmlViewOptions インスタンスを初期化します。

インスタンスは提供されたフォーマット文字列を使用します：
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

[`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) クラスのインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path_format | `str` | ファイルパスのフォーマット、例: `'page_{0}.html'`。 |
| resource_file_path_format | `str` | リソースファイルパスのフォーマット、例: `'page_{0}/resource_{1}'`。 |
| resource_url_format | `str` | リソースURLのフォーマット、例: `'page_{0}/resource_{1}'`。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `resource_url_format` が None または空の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # ドキュメントを読み込み、各ページを外部リソース付きのHTMLファイルにレンダリングします。
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### 参照
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
