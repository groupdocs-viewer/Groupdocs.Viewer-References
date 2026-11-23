---
title: "Argb32Color"
second_title: "GroupDocs.Viewer for .NET API 참조"
description: "ARGB 형식으로 8비트씩 알파, 레드, 그린, 블루 채널을 갖는 32비트 색상을 나타냅니다. 투명성을 지원합니다."
type: docs
weight: 950
url: /ko/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

ARGB 형식의 32비트 색상을 나타내며, 각 채널(알파, 레드, 그린, 블루)에 8비트를 사용합니다. 투명성을 지원합니다.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | 색상의 알파 부분을 8비트 부호 없는 정수 [0..255]로 가져옵니다. |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | 색상의 알파 부분을 (0..1) 범위의 백분율로 가져옵니다. |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | 색상의 파란색 부분을 8비트 부호 없는 정수 [0..255]로 가져옵니다. |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | 색상의 녹색 부분을 8비트 부호 없는 정수 [0..255]로 가져옵니다. |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | 이 [`Argb32Color`](../argb32color) 인스턴스가 기본값(투명)인지 여부를 나타냅니다 - 모든 4채널이 0으로 설정됩니다. [`IsEmpty`](./isempty)와 동일합니다. |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | 이 [`Argb32Color`](../argb32color) 색상 인스턴스가 초기화되지 않았는지 여부를 나타냅니다 - 모든 4채널이 0으로 설정됩니다. 기본값 및 투명과 동일합니다. [`IsDefault`](./isdefault)와 동일합니다. |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | 이 [`Argb32Color`](../argb32color) 인스턴스가 완전히 불투명한지 여부를 나타냅니다(투명성 없음, 알파 채널이 최대값을 가짐). |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | 이 [`Argb32Color`](../argb32color) 인스턴스가 완전히 투명한지 여부를 나타냅니다 - 알파 채널이 최소값(0)이며, 따라서 다른 R, G, B 채널은 눈에 보이는 효과가 없습니다. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | 이 [`Argb32Color`](../argb32color) 인스턴스가 반투명인지 여부를 나타냅니다(완전히 투명하지도 않고 완전히 불투명하지도 않음) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | 색상의 빨간 부분을 8비트 부호 없는 정수 [0..255]로 가져옵니다 |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | 색상의 Int32 값을 32비트 부호 있는 정수로 가져옵니다 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | 32비트 구성 요소(알파, 빨강, 초록, 파랑) 값을 사용하여 [`Argb32Color`](../argb32color) 인스턴스를 생성합니다. `System.Drawing.Color.ToArgb()` 메서드가 생성한 값과 호환됩니다. |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | 지정된 값으로 새로운 [`Argb32Color`](../argb32color) 인스턴스를 생성하되, 알파(불투명도) 값을 재정의합니다. |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | 지정된 [`Rgb24Color`](../rgb24color) 로부터 새로운 [`Argb32Color`](../argb32color) 인스턴스를 생성하되, 지정된 알파(불투명도) 값을 사용합니다. |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | 지정된 빨강, 초록, 파랑 채널을 사용하여 하나의 [`Argb32Color`](../argb32color) 값을 생성하고, 알파 채널은 완전히 불투명하게 설정합니다. |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | 지정된 빨강, 초록, 파랑 및 알파 채널을 사용하여 하나의 [`Argb32Color`](../argb32color) 값을 생성합니다. |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | 단일 값을 사용하여 완전히 불투명한(A=255) 색상을 생성하며, 이 값은 모든 채널에 적용됩니다. |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | 이 색상이 지정된 [`Argb32Color`](../argb32color) 색상과 같은지 확인합니다. |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | 이 색상을 지정된 캐스팅되지 않은 색상과 비교합니다. |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | 이 색상이 지정된 [`Rgb24Color`](../rgb24color) 색상과 같은지 확인합니다. |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | 이 [`Argb32Color`](../argb32color) 인스턴스에 대한 색조-채도-명도(HSL) 명도/밝기를 반환합니다. |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | 현재 색상을 정의하는 해시 코드를 반환합니다. GetHashCode와 호환되지 않습니다. |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | 이 [`Argb32Color`](../argb32color) 인스턴스에 대한 색조-채도-명도(HSL) 색상값을 도 단위로 반환합니다. R == G == B인 경우 색상값은 의미가 없으며 반환값은 0입니다. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | 이 [`Argb32Color`](../argb32color) 인스턴스에 대한 색조-채도-명도(HSL) 채도 |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | 이 [`Argb32Color`](../argb32color) 인스턴스의 ARGB 값을 반환합니다. `System.Drawing.Color.ToArgb()` 메서드와 호환됩니다. |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | 이 [`Argb32Color`](../argb32color) 인스턴스를 알파 채널 없이 16진수 표기 `##RRGGBB` 문자열로 직렬화합니다. |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | 이 [`Argb32Color`](../argb32color) 인스턴스를 알파 채널을 포함한 16진수 표기 `##RRGGBBAA` 문자열로 직렬화합니다. |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | 이 [`Argb32Color`](../argb32color) 인스턴스를 'rgb' CSS 함수 표기법으로 직렬화합니다. 직렬화 시 이 색상의 알파 채널은 생략됩니다. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | 이 [`Argb32Color`](../argb32color) 인스턴스를 'rgba' CSS 함수 표기법으로 직렬화합니다. |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | 이 [`Argb32Color`](../argb32color) 인스턴스를 투명도에 따라 가장 적절한 CSS 함수 표기법으로 직렬화합니다. |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | 두 개의 [`Argb32Color`](../argb32color) 색상을 비교하고, 두 색상이 일치하는지 여부를 나타내는 부울 값을 반환합니다. (연산자 2개) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | 32비트 [`Argb32Color`](../argb32color) 를 24비트 [`Rgb24Color`](../rgb24color) 로 명시적으로 캐스팅합니다. 원본 [`Argb32Color`](../argb32color) 의 알파 채널은 투명성을 지원하지 않기 때문에 캐스팅 후 손실됩니다. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | 24비트 [`Rgb24Color`](../rgb24color) 를 32비트 [`Argb32Color`](../argb32color) 로 암시적으로 캐스팅합니다. 출력 [`Argb32Color`](../argb32color) 의 알파 채널은 `255` 로 설정되어 완전히 불투명합니다. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | 두 [`Argb32Color`](../argb32color) 색을 비교하고 두 색이 일치하지 않는지를 나타내는 부울 값을 반환합니다. (2 연산자) |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | 채널 정보가 없고 완전히 투명한 빈 색을 반환합니다. '[`Transparent`](./transparent)'와 동일합니다. 기본값. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | 완전히 투명한 빈 색입니다. 기본 '[`Empty`](./empty)' 색 값과 동일합니다. |

### 비고

이 타입은 (CSS 작업에만 국한되지 않고) 유용하도록 설계되었습니다. 자세히 보기: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### 또 보기

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
