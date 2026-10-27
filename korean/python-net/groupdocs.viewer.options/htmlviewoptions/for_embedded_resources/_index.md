---
title: "for_embedded_resources 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "임베디드 리소스를 사용하여 HTML을 렌더링하기 위해 HtmlViewOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

임베디드 리소스를 사용하여 HTML을 렌더링하기 위해 HtmlViewOptions 인스턴스를 초기화합니다.

자세한 내용은 문서를 참조하십시오.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `create_page_stream`이 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

임베디드 리소스를 사용하여 HTML로 렌더링하기 위해 [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 클래스의 인스턴스를 초기화합니다.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| release_page_stream | `ReleasePageStream` | `create_page_stream` 매개변수에 할당된 메서드가 만든 스트림을 해제하는 메서드입니다. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `release_page_stream`이 `None`인 경우. 코드 예제는 문서를 참조하십시오. |

## for_embedded_resources {#page_stream_factory}

임베디드 리소스를 사용하여 HTML로 렌더링하기 위해 HtmlViewOptions 인스턴스를 초기화합니다.

코드 예제는 https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources 에 있는 문서를 참조하십시오.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 출력 페이지 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리입니다. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | page_stream_factory가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

임베디드 리소스를 사용하여 [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 클래스의 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def for_embedded_resources(cls):
    ...
```

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

임베디드 리소스를 위한 HtmlViewOptions 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path_format | `str` | 파일 경로 형식 예: 'page_{0}.html'. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_path_format`이 None이거나 비어 있는 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### 참고
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
