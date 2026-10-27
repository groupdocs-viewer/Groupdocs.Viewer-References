---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "PdfViewOptions のインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

[`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) のインスタンスを初期化します。

コード例については、https://docs.groupdocs.com/viewer/net/rendering-to-pdf/ のドキュメントをご覧ください。

```python
def __init__(self, create_file_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | 出力ファイルデータの書き込みに使用されるストリームを生成するメソッドです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `create_file_stream` が `None` の場合。 |

## __init__ {#create_file_stream-release_file_stream}

新しい PdfViewOptions インスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | `io.RawIOBase` ストリームを返す呼び出し可能オブジェクトで、出力ファイルデータの書き込みに使用されます。 |
| release_file_stream | `ReleaseFileStream` | `create_file_stream` に割り当てられたメソッドが作成したストリームを解放する呼び出し可能オブジェクトです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `release_file_stream` が None の場合。 |

## __init__ {#file_stream_factory}

PdfViewOptions インスタンスを初期化します。

コード例については、ドキュメントをご覧ください: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | 出力ファイルストリームの作成と解放のメソッドを実装するファクトリです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_stream_factory` が None のときに発生します。 |

## __init__

PdfViewOptions インスタンスを初期化します。

このコンストラクタは、出力ファイルのファイルパス形式として `"output.pdf"` を使用して PdfViewOptions を初期化します。出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

[`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) クラスのインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def __init__(self, output_file_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| output_file_path | `str` | 出力 PDF ファイルのパスです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `output_file_path` が None または空の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### 参照
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
