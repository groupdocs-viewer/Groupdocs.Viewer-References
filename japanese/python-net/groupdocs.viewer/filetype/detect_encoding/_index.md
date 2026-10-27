---
title: "detect_encoding メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "パスでテキスト TXT、TSV、CSV ファイルのエンコーディングを検出します。"
type: docs
url: /ja/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

パスでテキスト TXT、TSV、CSV ファイルのエンコーディングを検出します。

```python
def detect_encoding(cls, file_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_path | `str` | ファイル名またはファイルパスです。 |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### 例

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

ストリームからテキストファイル（TXT、TSV、CSV）のエンコーディングを検出しようとします。

```python
def detect_encoding(cls, stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### 例

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### 参照
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
