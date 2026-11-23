---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "PdfViewOptions의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

[`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) 인스턴스를 초기화합니다.

코드 예제는 https://docs.groupdocs.com/viewer/net/rendering-to-pdf/ 의 문서를 참조하십시오.

```python
def __init__(self, create_file_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | 출력 파일 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `create_file_stream`이 `None`인 경우. |

## __init__ {#create_file_stream-release_file_stream}

새 PdfViewOptions 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | `io.RawIOBase` 스트림을 반환하는 호출 가능 객체로, 출력 파일 데이터를 쓰는 데 사용됩니다. |
| release_file_stream | `ReleaseFileStream` | `create_file_stream`에 할당된 메서드가 만든 스트림을 해제하는 호출 가능 객체. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `release_file_stream`이 None인 경우. |

## __init__ {#file_stream_factory}

PdfViewOptions 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | 출력 파일 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_stream_factory`가 None일 때 발생합니다. |

## __init__

PdfViewOptions 인스턴스를 초기화합니다.

이 생성자는 출력 파일의 파일 경로 형식으로 `\"output.pdf\"`를 사용하여 PdfViewOptions를 초기화합니다. 출력 파일은 애플리케이션의 현재 작업 디렉터리에 배치됩니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

[`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/) 클래스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def __init__(self, output_file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| output_file_path | `str` | 출력 PDF 파일의 경로입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `output_file_path`가 None이거나 비어 있을 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### 참고
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
