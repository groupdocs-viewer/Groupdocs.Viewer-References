---
title: "from_jpg_view_options 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "제공된 JpgViewOptions를 기반으로 ViewInfoOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/viewinfooptions/from_jpg_view_options/
is_root: false
weight: 1090
---


## from_jpg_view_options {#options}

제공된 [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)를 기반으로 [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) 인스턴스를 초기화합니다.

```python
def from_jpg_view_options(cls, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | `JpgViewOptions` | JPG 보기 옵션. |

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | 옵션이 `None`인 경우. |

### 참고
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
