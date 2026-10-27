---
title: "Rgb24Color 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "각 채널당 8비트(빨강, 초록, 파랑)를 갖는 24비트 RGB 색상을 나타내며, 투명성을 지원하지 않습니다."
type: docs
url: /ko/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

각 채널당 8비트(빨강, 초록, 파랑)를 갖는 24비트 RGB 색상을 나타내며, 투명성을 지원하지 않습니다.

이 형식은 CSS 작업에 유용하도록 설계되었지만 이에 국한되지 않습니다. 자세히 보기: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Rgb24Color 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | 이 색상이 지정된 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)와 같은지 여부를 결정합니다. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | 이 색상이 지정된 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 색상과 같은지 확인합니다. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | 이 색상을 지정된 캐스팅되지 않은 색상과 비교합니다. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | 지정된 빨강, 초록, 파랑 채널 값으로 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 값을 생성합니다. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | 이 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 인스턴스에 대한 색조‑채도‑명도(HSL) 명도/밝기를 반환합니다. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | 현재 색상을 정의하는 해시 코드를 반환합니다. `System.Drawing.Color.GetHashCode`와 호환되지 않습니다. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | 색상의 색조 구성 요소를 HSL 색공간에서 도 단위로 반환합니다. 색상이 회색조(R == G == B)인 경우 색조는 정의되지 않으며 메서드는 0을 반환합니다. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | 이 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 인스턴스에 대한 색조‑채도‑명도(HSL) 채도를 반환합니다. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | 이 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 인스턴스의 ARGB 값을 반환합니다. `System.Drawing.Color`와 호환됩니다. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | 이 색상을 16진수 문자열 형태로 반환합니다. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | 이 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 인스턴스를 'rgb' CSS 함수 표기법으로 직렬화합니다. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | 이 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 인스턴스를 'rgb(r, g, b)' 형식으로 직렬화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | 색상의 파랑 구성 요소를 8비트 부호 없는 정수 [0..255]로 나타냅니다. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | 색상의 녹색 구성 요소를 0..255 범위의 8비트 부호 없는 정수로 나타냅니다. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | 이 [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) 인스턴스가 기본값(검정)인지 여부를 나타내는 속성이며, 세 채널 모두 0으로 설정됩니다. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | 색상의 빨간색 구성 요소를 0..255 범위의 8비트 부호 없는 정수로 나타냅니다. |

### 참고
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
