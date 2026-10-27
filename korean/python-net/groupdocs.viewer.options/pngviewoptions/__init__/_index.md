---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "새 PngViewOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

새로운 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def __init__(self, create_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `create_page_stream`가 None인 경우. |

## __init__ {#create_page_stream-release_page_stream}

[`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 클래스의 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| release_page_stream | `ReleasePageStream` | `create_page_stream` 매개변수에 전달된 대리자에 할당된 메서드가 만든 스트림을 해제하는 메서드. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `release_page_stream`가 None인 경우. |

## __init__ {#page_stream_factory}

새로운 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 인스턴스를 초기화합니다.

자세한 내용은 문서를 참조하세요.

```python
def __init__(self, page_stream_factory):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 출력 페이지 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `page_stream_factory`가 `None`인 경우. |

## __init__

PngViewOptions 인스턴스를 초기화합니다.

이 생성자는 출력 파일의 기본 파일 경로 형식으로 ``"p_{0}.png"``을 사용하여 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)를 생성합니다. 생성된 PNG 파일은 애플리케이션의 현재 작업 디렉터리에 저장됩니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

새로운 [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def __init__(self, file_path_format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path_format | `str` | 파일 경로 형식, 예: `'page_{0}.png'`. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_path_format`이 None이거나 비어 있는 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### 참고
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
