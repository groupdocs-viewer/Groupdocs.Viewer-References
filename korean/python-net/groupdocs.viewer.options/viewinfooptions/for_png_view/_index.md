---
title: "for_png_view 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "PNG로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

PNG로 렌더링할 때 보기 정보를 검색하기 위해 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 클래스의 인스턴스를 초기화합니다.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# PNG 형식용 보기 정보 옵션 만들기
view_info_options_png = ViewInfoOptions.for_png_view()

# 문서를 로드하고 PNG에 대한 보기 정보를 가져옵니다
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

PNG로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 클래스의 인스턴스를 초기화합니다.

```python
def for_png_view(cls, extract_text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extract_text | `bool` | 텍스트 추출을 활성화합니다. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 예시

```python
from groupdocs.viewer.options import ViewInfoOptions

# 텍스트 추출이 활성화된 PNG 형식용 보기 정보 옵션 만들기
options = ViewInfoOptions.for_png_view(extractText=True)
```

### 참고
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
