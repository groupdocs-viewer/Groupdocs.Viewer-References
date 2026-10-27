---
title: "for_external_resources 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "외부 리소스를 사용하여 HTML로 렌더링하기 위해 HtmlViewOptions 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

외부 리소스를 사용하여 HTML로 렌더링하기 위해 [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 클래스의 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| create_resource_stream | `CreateResourceStream` | `create_page_stream` 메서드에 의해 생성된 스트림을 해제하는 메서드. |
| create_resource_url | `CreateResourceUrl` | HTML 리소스의 URL을 생성하는 메서드. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `create_resource_url` 가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

외부 리소스를 사용하여 HTML로 렌더링하기 위해 HtmlViewOptions 클래스의 인스턴스를 초기화합니다.

추가 사용 예제는 GroupDocs Viewer 문서를 참조하십시오.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| create_resource_stream | `CreateResourceStream` | 출력 HTML 리소스 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| create_resource_url | `CreateResourceUrl` | HTML 리소스의 URL을 생성하는 메서드. |
| release_page_stream | `ReleasePageStream` | `create_page_stream`에 전달된 대리자에 의해 생성된 스트림을 해제하는 메서드. |
| release_resource_stream | `ReleaseResourceStream` | `create_resource_stream`에 전달된 대리자에 의해 생성된 스트림을 해제하는 메서드. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `release_resource_stream` 가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Excel 스프레드시트 로드
    with Viewer("invoice.xlsx") as viewer:
        # 스프레드시트를 외부 리소스와 함께 HTML로 변환합니다.
        # {0}과 {1}은 각각 현재 페이지 번호와 리소스 이름으로 대체됩니다.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

외부 리소스를 사용하여 HTML로 렌더링하기 위해 HtmlViewOptions 인스턴스를 초기화합니다.

자세한 내용은 온라인 문서를 참조하십시오.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | 출력 페이지 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리입니다. |
| resource_stream_factory | `IResourceStreamFactory` | 리소스 URL을 생성하고, 인스턴스화하며, 출력 HTML 리소스 스트림을 해제하는 데 필요한 메서드를 구현하는 팩터리입니다. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `resource_stream_factory`가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # 각 페이지마다 HTML 파일을 생성하고 외부 리소스를 별도로 저장합니다.
    # {0}과 {1}은 각각 현재 페이지 번호와 리소스 이름으로 대체됩니다.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

외부 리소스를 포함한 HTML 파일을 생성하도록 구성된 HtmlViewOptions 인스턴스를 초기화합니다.

인스턴스는 제공된 형식 문자열을 사용합니다:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

출력 파일은 애플리케이션의 현재 작업 디렉터리에 배치됩니다.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

[`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) 클래스의 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path_format | `str` | 파일 경로 형식, 예: `'page_{0}.html'`. |
| resource_file_path_format | `str` | 리소스 파일 경로 형식, 예: `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | 리소스 URL 형식, 예: `'page_{0}/resource_{1}'`. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `resource_url_format`가 None이거나 비어 있는 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # 문서를 로드하고 각 페이지를 외부 리소스가 포함된 HTML 파일로 렌더링합니다.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### 참고
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
