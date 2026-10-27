---
title: "Argb32Color 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "ARGB 형식의 32비트 색상을 나타내며, 각 채널(알파, 빨강, 초록, 파랑)에 8비트씩 할당됩니다."
type: docs
url: /ko/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

32비트 색상을 ARGB 형식으로 나타내며, 각 채널당 8비트(알파, 빨강, 초록, 파랑)를 사용합니다. 투명성을 지원합니다.

이 형식은 CSS 작업에 유용하도록 설계되었지만 이에 국한되지 않습니다. 자세히 보기: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Argb32Color 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | 이 색상이 지정된 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)과 같은지 확인합니다. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | 이 색상이 지정된 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)과 같은지 판단합니다. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | 이 색상이 지정된 형변환되지 않은 색상과 같은지 확인합니다. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | `System.Drawing.Color.ToArgb()`에서 생성된 값과 호환되는 32비트 ARGB 값으로 Argb32Color 인스턴스를 생성합니다. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | 지정된 인스턴스로부터 새로운 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스를 생성하지만, 알파(불투명도) 값을 재정의합니다. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | 지정된 Rgb24Color로부터 새로운 Argb32Color 인스턴스를 생성하되, 지정된 알파(불투명도) 값을 사용합니다. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | 지정된 빨강, 초록, 파랑 채널로부터 Argb32Color 값을 생성하고, 알파 채널은 완전 불투명으로 설정합니다. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | 지정된 빨강, 초록, 파랑 및 알파 채널 값으로부터 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 값을 생성합니다. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | 단일 바이트 값을 모든 채널에 적용하여 완전 불투명(A=255) 색상을 생성합니다. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스에 대한 색조‑채도‑명도(HSL) 밝기(라이트니스)를 반환합니다. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | 현재 색상을 정의하는 해시 코드를 반환합니다; `System.Drawing.Color.GetHashCode`와 호환되지 않습니다. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스에 대한 색조‑채도‑명도(HSL) 색상값을 도 단위로 반환합니다; R == G == B인 경우 색상값은 의미가 없으며 메서드는 0을 반환합니다. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스에 대한 색조‑채도‑명도(HSL) 채도 값을 반환합니다. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스의 ARGB 값을 반환합니다; `System.Drawing.Color.ToArgb()` 메서드와 호환됩니다. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스를 알파 채널 없이 문자열 형태의 16진수 표기 `##RRGGBB` 로 직렬화합니다. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스를 알파 채널을 포함한 문자열 형태의 16진수 표기 `##RRGGBBAA` 로 직렬화합니다. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스를 알파 채널을 제외한 `rgb` CSS 함수 표기법으로 직렬화합니다. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스를 'rgba' CSS 함수 표기법으로 직렬화합니다. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Argb32Color 인스턴스를 투명도에 따라 가장 적절한 CSS 함수 표기법으로 직렬화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | 색상의 알파 구성 요소를 0..255 범위의 8비트 부호 없는 정수로 나타냅니다. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | 색상의 알파 구성 요소를 0..1 범위의 부동 소수점 값으로 나타냅니다. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | 색상의 파란색 구성 요소를 0..255 범위의 8비트 부호 없는 정수로 나타냅니다. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | 색상의 녹색 구성 요소를 0..255 범위의 8비트 부호 없는 정수로 나타냅니다. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | 이 속성은 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스가 기본값(투명)인지 여부를 나타내며, 네 채널 모두 0으로 설정된 것을 의미합니다; 이는 [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/)와 동일합니다. |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | 이 속성은 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스가 초기화되지 않았는지(네 채널 모두 0으로 설정) 여부를 나타냅니다. 이는 기본값 또는 투명 색과 동일하며 [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/)와 일치합니다. |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | 이 속성은 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스가 완전히 불투명한지, 즉 투명성이 없으며(알파 채널이 최대값) 여부를 나타냅니다. |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | 이 속성은 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스가 완전히 투명한지—알파 채널이 최소값(0)이며, 따라서 R, G, B 채널이 눈에 보이는 영향을 주지 않는지를 나타냅니다. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | 이 속성은 이 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 인스턴스가 반투명인지(완전 투명하지도 않고 완전 불투명하지도 않음) 여부를 나타냅니다. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | 색상의 빨간색 구성 요소를 0..255 범위의 8비트 부호 없는 정수로 나타냅니다. |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | 색상의 32비트 부호 있는 정수 표현입니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | 채널 정보가 없고 완전히 투명한 빈 색을 반환합니다. ''와 동일합니다. 기본값입니다. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | 완전히 투명한 빈 색입니다. 기본 '' 색 값과 동일합니다. |

### 예시

```python
from groupdocs.viewer.drawing import Argb32Color

# 완전히 불투명한 노란색(RGB 255, 255, 0) 색을 생성합니다.
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### 참고
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
