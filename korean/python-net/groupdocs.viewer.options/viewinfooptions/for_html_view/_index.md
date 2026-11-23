---
title: "for_html_view 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "HTML로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

HTML로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 인스턴스를 초기화합니다.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### 예시

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # HTML 형식(단일 페이지)용 보기 정보 옵션 만들기
    options = ViewInfoOptions.for_html_view(True)

    # 문서를 로드하고 보기 정보를 가져옵니다
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

HTML로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 인스턴스를 초기화합니다.

```python
def for_html_view(cls, render_single_page):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| render_single_page | `bool` | HTML 콘텐츠를 단일 페이지로 렌더링하도록 활성화합니다. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# 단일 페이지 HTML에 대한 보기 정보를 검색합니다
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### 참고
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
