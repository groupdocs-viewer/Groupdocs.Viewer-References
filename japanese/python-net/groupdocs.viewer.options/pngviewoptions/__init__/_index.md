---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "新しい PngViewOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

新しい [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) インスタンスを初期化します。

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

[`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) クラスのインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| release_page_stream | `ReleasePageStream` | `create_page_stream` パラメータに渡されたデリゲートに割り当てられたメソッドが作成したストリームを解放するメソッドです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `release_page_stream` が None のとき。 |

## __init__ {#page_stream_factory}

新しい [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) インスタンスを初期化します。

詳細については、ドキュメントをご参照ください。

```python
def __init__(self, page_stream_factory):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 出力ページストリームの作成と解放のメソッドを実装するファクトリです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `page_stream_factory` が `None` の場合。 |

## __init__

PngViewOptions インスタンスを初期化します。

このコンストラクタは、出力ファイルのデフォルトファイルパス形式として ``\"p_{0}.png\"`` を使用した [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) を作成します。生成された PNG ファイルは、アプリケーションの現在の作業ディレクトリに保存されます。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

新しい [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) インスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def __init__(self, file_path_format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path_format | `str` | ファイルパス形式、例: `'page_{0}.png'`。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_path_format` が None または空の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### 参照
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
