---
title: "Argb32Color"
second_title: "Referensi API GroupDocs.Viewer untuk .NET"
description: "Mewakili warna 32-bit dalam format ARGB dengan 8 bit untuk setiap saluran Alpha Red Green Blue. Mendukung transparansi."
type: docs
weight: 950
url: /id/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Mewakili warna 32-bit dalam format ARGB, dengan 8 bit per setiap saluran (Alpha, Red, Green, Blue). Mendukung transparansi.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Mendapatkan bagian alpha dari warna sebagai bilangan bulat tak bertanda 8-bit [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Mendapatkan bagian alpha dari warna dalam persen pada rentang (0..1). |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Mendapatkan bagian biru dari warna sebagai bilangan bulat tak bertanda 8-bit [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Mendapatkan bagian hijau dari warna sebagai bilangan bulat tak bertanda 8-bit [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Menunjukkan apakah instance [`Argb32Color`](../argb32color) ini adalah default (Transparent) - semua 4 saluran diatur ke 0. Sama dengan [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Menunjukkan apakah instance warna [`Argb32Color`](../argb32color) ini belum diinisialisasi - semua 4 saluran diatur ke 0. Sama dengan Default dan Transparent. Sama dengan [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Menunjukkan apakah instance [`Argb32Color`](../argb32color) ini sepenuhnya opak, tanpa transparansi (saluran Alpha-nya memiliki nilai maksimum) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Menunjukkan apakah instance [`Argb32Color`](../argb32color) ini sepenuhnya transparan - saluran Alpha-nya memiliki nilai minimum (0), sehingga saluran R, G, dan B lainnya tidak memberikan efek yang terlihat. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Menunjukkan apakah instance [`Argb32Color`](../argb32color) ini bersifat translusen (tidak sepenuhnya transparan, tetapi juga tidak sepenuhnya opak) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Mendapatkan bagian merah dari warna sebagai integer tak bertanda 8-bit [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Mendapatkan nilai Int32 dari warna sebagai integer bertanda 32-bit |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Membuat instance [`Argb32Color`](../argb32color) dari nilai komponennya yang 32-bit (alpha, merah, hijau, dan biru), kompatibel dengan nilai yang dihasilkan oleh metode `System.Drawing.Color.ToArgb()`. |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Membuat instance [`Argb32Color`](../argb32color) baru dari nilai yang ditentukan, namun dengan nilai alpha (opasitas) yang didefinisikan ulang. |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Membuat instance [`Argb32Color`](../argb32color) baru dari [`Rgb24Color`](../rgb24color) yang ditentukan, namun dengan nilai alpha (opasitas) yang ditentukan. |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Membuat satu nilai [`Argb32Color`](../argb32color) dari kanal Merah, Hijau, Biru yang ditentukan, sementara kanal Alpha sepenuhnya opak. |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Membuat satu nilai [`Argb32Color`](../argb32color) dari kanal Merah, Hijau, Biru, dan Alpha yang ditentukan. |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Membuat warna yang sepenuhnya opak (A=255) dari satu nilai tunggal, yang akan diterapkan ke semua kanal. |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Memeriksa kesetaraan warna ini dengan warna [`Argb32Color`](../argb32color) yang ditentukan. |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Memeriksa warna ini dengan nilai yang tidak dikast. |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Memeriksa kesetaraan warna ini dengan warna [`Rgb24Color`](../rgb24color) yang ditentukan. |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Mengembalikan kecerahan (lightness) Hue-Saturation-Lightness (HSL) untuk instance [`Argb32Color`](../argb32color) ini. |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Mengembalikan kode hash yang mendefinisikan warna saat ini. Tidak kompatibel dengan GetHashCode. |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Mengembalikan nilai hue Hue-Saturation-Lightness (HSL), dalam derajat, untuk instance [`Argb32Color`](../argb32color) ini. Jika R == G == B, hue tidak memiliki makna, dan nilai yang dikembalikan adalah 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | Saturasi Hue-Saturation-Lightness (HSL) untuk instance [`Argb32Color`](../argb32color) ini. |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Mengembalikan nilai ARGB dari instance [`Argb32Color`](../argb32color) ini, kompatibel dengan metode `System.Drawing.Color.ToArgb()`. |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Menyerialisasi instance [`Argb32Color`](../argb32color) ini ke notasi heksadesimal `##RRGGBB` sebagai string tanpa kanal alpha. |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Menyerialisasi instance [`Argb32Color`](../argb32color) ini ke notasi heksadesimal `##RRGGBBAA` sebagai string dengan kanal alpha. |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Menyerialisasi instance [`Argb32Color`](../argb32color) ini ke notasi fungsi CSS 'rgb'. Kanal alpha warna ini akan diabaikan selama serialisasi. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Menyerialisasi instance [`Argb32Color`](../argb32color) ini ke notasi fungsi CSS 'rgba'. |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Menyerialisasi instance [`Argb32Color`](../argb32color) ini ke notasi fungsi CSS yang paling tepat tergantung pada tingkat tembus. |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Membandingkan dua warna [`Argb32Color`](../argb32color) dan mengembalikan nilai boolean yang menunjukkan apakah keduanya cocok. (2 operator) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Secara eksplisit mengubah tipe 32-bit [`Argb32Color`](../argb32color) menjadi 24-bit [`Rgb24Color`](../rgb24color). Kanal alpha dari sumber [`Argb32Color`](../argb32color) akan hilang setelah casting, karena [`Rgb24Color`](../rgb24color) tidak mendukung transparansi. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Secara implisit mengubah tipe 24-bit [`Rgb24Color`](../rgb24color) menjadi 32-bit [`Argb32Color`](../argb32color). Kanal alpha dari output [`Argb32Color`](../argb32color) akan diatur ke `255` - sepenuhnya opak. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Membandingkan dua warna [`Argb32Color`](../argb32color) dan mengembalikan nilai boolean yang menunjukkan apakah keduanya tidak cocok. (2 operator) |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Mengembalikan warna kosong, yang tidak memiliki informasi kanal dan sepenuhnya transparan. Sama dengan '[`Transparent`](./transparent)'. Nilai default. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Warna kosong yang sepenuhnya transparan. Sama dengan nilai warna default '[`Empty`](./empty)'. |

### Catatan

Tipe ini dirancang agar berguna untuk (tetapi tidak terbatas pada) operasi CSS. Lihat selengkapnya: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Lihat Juga

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
