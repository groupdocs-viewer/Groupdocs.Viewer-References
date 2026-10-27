---
title: "detect_encoding 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "경로를 통해 텍스트 TXT, TSV 및 CSV 파일의 인코딩을 감지합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

경로를 통해 텍스트 TXT, TSV 및 CSV 파일의 인코딩을 감지합니다.

```python
def detect_encoding(cls, file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 파일 이름 또는 파일 경로입니다. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### 예시

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

스트림에서 텍스트 파일(TXT, TSV, CSV)의 인코딩을 감지하려 시도합니다.

```python
def detect_encoding(cls, stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### 예시

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### 참고
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
