---
title: "view 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "문서의 모든 페이지에 대한 뷰를 생성합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

문서의 모든 페이지에 대한 뷰를 생성합니다.

자세히 보기

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | `ViewOptions` | 뷰 옵션. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | 옵션이 `None`인 경우. |
| `PasswordRequiredException` | 문서를 열기 위해 비밀번호가 필요한 경우. |
| `IncorrectPasswordException` | 지정된 비밀번호가 올바르지 않을 때. |
| `GroupDocsViewerException` | 첨부 파일을 찾을 수 없을 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

특정 문서 페이지에 대한 뷰를 생성합니다.

자세히 보기

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | `ViewOptions` | 뷰 옵션. |
| page_numbers | `list[int]` | 볼 페이지 번호. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `page_numbers`가 비어 있을 때. |
| `PasswordRequiredException` | 문서를 열기 위해 비밀번호가 필요할 때. |
| `IncorrectPasswordException` | 지정된 비밀번호가 올바르지 않을 때. |
| `GroupDocsViewerException` | 첨부 파일을 찾을 수 없을 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

특정 문서 페이지에 대한 뷰를 생성합니다.

자세히 보기:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | `ViewOptions` | 뷰 옵션. |
| cancellation_token | `CancellationToken` | 처리를 취소하기 위한 취소 토큰. |
| page_numbers | `list[int]` | 볼 페이지 번호. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `page_numbers`가 비어 있을 때. |
| `PasswordRequiredException` | 문서를 열기 위해 비밀번호가 필요할 때. |
| `IncorrectPasswordException` | 지정된 비밀번호가 올바르지 않을 때. |
| `GroupDocsViewerException` | 첨부 파일을 찾을 수 없을 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### 참고
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
