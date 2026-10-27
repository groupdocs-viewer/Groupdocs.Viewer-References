---
title: "for_rendering_by_width_and_height 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "너비와 높이 기준으로 렌더링하기 위해 CadOptions 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/
is_root: false
weight: 1040
---


## for_rendering_by_width_and_height {#width-height}

너비와 높이 기준으로 렌더링하기 위해 CadOptions 클래스의 인스턴스를 초기화합니다.

코드 예제는 문서를 참조하십시오.

```python
def for_rendering_by_width_and_height(cls, width, height):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| width | `int` | 출력 결과의 너비(픽셀 단위). |
| height | `int` | 출력 결과의 높이(픽셀 단위)입니다. |

**Returns:** CadOptions: New instance of CadOptions class for rendering by width and height.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `height`가 0 이하인 경우. |

### 참고
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
