---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Viewer クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` クラスの新しいインスタンスを初期化します。

詳しく見る

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 読み取り可能なストリームを返すメソッド。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `get_file_stream` が None のときに発生します。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` の新しいインスタンスを初期化します。

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 読み取り可能なストリームを返すメソッド。 |
| get_load_options | `Func[LoadOptions]` | ドキュメントのロードオプションを返すメソッド。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `get_load_options` が None のときにスローされます。 |
| `Remarks` | - GroupDocs.Viewer がサポートするファイルタイプの詳細: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - .NET 用 GroupDocs.Viewer の機能の詳細: https://docs.groupdocs.com/display/viewernet/Developer+Guide - .NET 用 GroupDocs.Viewer で暗号化ドキュメントをロードし、サードパーティ ストレージからファイルを表示する方法の詳細: https://docs.groupdocs.com/display/viewernet/Loading |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

新しい [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスを初期化します。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 読み取り可能なストリームを返すメソッド。 |
| settings | `ViewerSettings` | Viewer の設定。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `settings` が None のとき。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

新しい Viewer インスタンスを初期化します。

詳細情報：

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 読み取り可能なストリームを返す Callable。 |
| get_load_options | `Func[LoadOptions]` | ドキュメントのロードオプションを返す Callable。 |
| settings | `ViewerSettings` | Viewer の設定。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `settings` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` クラスの新しいインスタンスを初期化します。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `stream` が None のときに発生します。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

新しい Viewer インスタンスを初期化します。

詳しく読む:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| leave_open | `bool` | Viewer オブジェクトが破棄された後にストリームを開いたままにする場合は True、そうでない場合は False。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | もし `stream` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` の新しいインスタンスを初期化します。

詳しく読む:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| load_options | `LoadOptions` | ドキュメントのロード オプション。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `load_options` が None のとき。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

新しい Viewer インスタンスを初期化します。

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| load_options | `LoadOptions` | ドキュメントのロード オプション。 |
| leave_open | `bool` | Viewer オブジェクトが破棄された後にストリームを開いたままにする場合は True、そうでない場合は False。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `load_options` が None のとき。 |
| `Remarks` | - GroupDocs.Viewer がサポートするファイルタイプの詳細: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - .NET 用 GroupDocs.Viewer の機能の詳細: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - .NET 用 GroupDocs.Viewer で暗号化ドキュメントを読み込み、サードパーティ ストレージからファイルを表示する方法の詳細: <https://docs.groupdocs.com/display/viewernet/Loading> |

### 例

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

新しい Viewer インスタンスを初期化します。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| settings | `ViewerSettings` | Viewer の設定。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `settings` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

新しい Viewer インスタンスを初期化します。

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| settings | `ViewerSettings` | Viewer の設定。 |
| leave_open | `bool` | Viewer オブジェクトが破棄された後にストリームを開いたままにする場合は True、そうでない場合は False。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `settings` が None のとき。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

新しい Viewer インスタンスを初期化します。

コンストラクタはファイルストリーム (`io.RawIOBase`) を必要とし、オプションでドキュメントのロード オプションと Viewer 設定を受け取ります。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| load_options | `LoadOptions` | ドキュメントのロード オプション。 |
| settings | `ViewerSettings` | Viewer の設定。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `stream`、`load_options`、または `settings` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer

# ファイルをバイナリ ストリームとして開き、Viewer を作成します。
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # viewer を使用します。例: HTML にレンダリングする
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` の新しいインスタンスを初期化します。

詳しく読む:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| load_options | `LoadOptions` | ドキュメントのロード オプション。 |
| settings | `ViewerSettings` | Viewer の設定。 |
| leave_open | `bool` | Viewer オブジェクトが破棄された後にストリームを開いたままにする場合は True、そうでない場合は False。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `settings` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` クラスの新しいインスタンスを初期化します。

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | レンダリングするファイルへのパス。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_path` が `None` または空の場合。 |

### 例

```python
from groupdocs.viewer import Viewer

# ドキュメントパスで viewer を初期化します。
with Viewer("./sample.docx") as viewer:
    # viewer がドキュメントのレンダリングの準備ができました。
    pass
```

## __init__ {#file_path-settings}

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` クラスの新しいインスタンスを初期化します。

詳しく読む:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | レンダリングするファイルへのパス。 |
| settings | `ViewerSettings` | Viewer の設定。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `settings` が null の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` の新しいインスタンスを初期化します。

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | レンダリングするファイルへのパス。 |
| load_options | `LoadOptions` | ファイルを開く際に使用されるオプション。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `load_options` が None の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

新しい Viewer インスタンスを初期化します。

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | レンダリングするファイルへのパス。 |
| load_options | `LoadOptions` | ファイルを開く際に使用されるオプション。 |
| settings | `ViewerSettings` | Viewer の設定。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `settings` が None の場合。 |

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
