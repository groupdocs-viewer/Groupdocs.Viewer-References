---
title: "метод detect_encoding"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Определяет кодировку текстовых файлов TXT, TSV и CSV по пути."
type: docs
url: /ru/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Определяет кодировку текстовых файлов TXT, TSV и CSV по пути.

```python
def detect_encoding(cls, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Имя файла или путь к файлу. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Пример

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Пытается определить кодировку текстовых файлов (TXT, TSV, CSV) из потока.

```python
def detect_encoding(cls, stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Пример

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### См. также
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
