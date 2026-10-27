---
title: "from_other_with_alpha 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "지정된 인스턴스로부터 새로운 Argb32Color 인스턴스를 생성하지만, 알파(불투명도) 값을 재정의합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

지정된 인스턴스로부터 새로운 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스를 생성하지만, 알파(불투명도) 값을 재정의합니다.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | `Argb32Color` | 새 인스턴스를 만들기 위한 다른 `Argb32Color` 인스턴스. |
| new_alpha | `int` | 재정의된 알파 채널 값 (255 - 완전히 불투명, 0 - 완전히 투명). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

지정된 Rgb24Color로부터 새로운 Argb32Color 인스턴스를 생성하되, 지정된 알파(불투명도) 값을 사용합니다.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | `Rgb24Color` | 새 인스턴스를 만들기 위한 다른 Rgb24Color 인스턴스. |
| new_alpha | `int` | 알파 채널 값 (255 - 완전히 불투명, 0 - 완전히 투명). |

**Returns:** New Argb32Color instance.

### 참고
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
