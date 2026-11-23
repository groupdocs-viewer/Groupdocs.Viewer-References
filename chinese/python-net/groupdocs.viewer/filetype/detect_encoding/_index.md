---
title: "detect_encoding 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "通过路径检测文本 TXT、TSV 和 CSV 文件的编码。"
type: docs
url: /zh/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

通过路径检测文本 TXT、TSV 和 CSV 文件的编码。

```python
def detect_encoding(cls, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 文件名或文件路径。 |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### 示例

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

尝试从流中检测文本文件（TXT、TSV、CSV）的编码。

```python
def detect_encoding(cls, stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### 示例

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### 另见
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
