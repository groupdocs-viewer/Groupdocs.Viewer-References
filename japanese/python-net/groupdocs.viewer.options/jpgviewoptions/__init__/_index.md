---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "JpgViewOptions クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

JpgViewOptions クラスのインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def __init__(self, create_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `create_page_stream` が None のとき。 |

## __init__ {#create_page_stream-release_page_stream}

JpgViewOptions クラスのインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 出力ページデータの書き込みに使用されるストリームを生成する Callable。 |
| release_page_stream | `ReleasePageStream` | `create_page_stream` に渡されたデリゲートに割り当てられたメソッドによって作成されたストリームを解放する Callable。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `release_page_stream` が None の場合。 |

## __init__ {#page_stream_factory}

[`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) クラスのインスタンスを初期化します。

コード例については、https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg のドキュメントを参照してください。

```python
def __init__(self, page_stream_factory):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 出力ページストリームの作成と解放のメソッドを実装するファクトリです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `page_stream_factory` が None のとき。 |

## __init__

JpgViewOptions インスタンスを初期化します。

このコンストラクタは、[`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) のインスタンスを初期化し、出力ファイルのファイルパス形式として `"p_{0}.jpg"` を使用します。出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

[`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) の新しいインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def __init__(self, file_path_format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path_format | `str` | ファイルパス形式、例: `'page_{0}.jpg'`。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_path_format` が None または空の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # ドキュメントを読み込む（例: Excel ファイル）
    with Viewer("invoice.xlsx") as viewer:
        # ファイル名パターンで JPEG ビューオプションを作成します。
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### 参照
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
