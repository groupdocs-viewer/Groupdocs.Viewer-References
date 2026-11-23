---
title: "for_jpg_view 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "JPG로 렌더링할 때 보기 정보를 가져오기 위해 ViewInfoOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

JPG로 렌더링할 때 보기 정보를 검색하기 위해 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 인스턴스를 초기화합니다.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_jpg_view_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_jpg_view())
        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_jpg_view_info()
```

## for_jpg_view {#extract_text}

JPG로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 인스턴스를 초기화합니다.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extract_text | `bool` | 텍스트 추출을 활성화합니다. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 참고
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
