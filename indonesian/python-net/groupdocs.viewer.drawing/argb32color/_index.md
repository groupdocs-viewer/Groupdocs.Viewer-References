---
title: "kelas Argb32Color"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili warna 32-bit dalam format ARGB, dengan 8 bit per setiap saluran (Alpha, Merah, Hijau, Biru)."
type: docs
url: /id/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Mewakili warna 32-bit dalam format ARGB, dengan 8 bit per setiap saluran (Alpha, Merah, Hijau, Biru). Mendukung transparansi.

Tipe ini dirancang untuk berguna dalam operasi CSS (meskipun tidak terbatas pada itu). Lihat selengkapnya: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Tipe Argb32Color menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Memeriksa apakah warna ini sama dengan [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) yang ditentukan. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Menentukan apakah warna ini sama dengan [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) yang ditentukan. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Memeriksa apakah warna ini sama dengan warna yang belum dikastakan yang ditentukan. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Membuat instance Argb32Color dari nilai ARGB 32-bit, kompatibel dengan nilai yang dihasilkan oleh `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Membuat instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) baru dari instance yang ditentukan, tetapi dengan nilai alpha (opasitas) yang didefinisikan ulang. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Membuat instance Argb32Color baru dari Rgb24Color yang ditentukan, tetapi dengan nilai alpha (opasitas) yang ditentukan. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Membuat nilai Argb32Color dari saluran Merah, Hijau, Biru yang ditentukan, dengan saluran Alpha diatur menjadi sepenuhnya opak. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Membuat nilai [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) dari nilai saluran merah, hijau, biru, dan alpha yang ditentukan. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Membuat warna sepenuhnya opak (A=255) dari satu nilai byte yang diterapkan ke semua saluran. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Mengembalikan kecerahan Hue‑Saturation‑Lightness (HSL) untuk instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Mengembalikan kode hash yang mendefinisikan warna saat ini; tidak kompatibel dengan `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Mengembalikan nilai hue Hue‑Saturation‑Lightness (HSL), dalam derajat, untuk instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini; jika R == G == B, hue tidak bermakna dan metode mengembalikan 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Mengembalikan saturasi Hue‑Saturation‑Lightness (HSL) dari instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Mengembalikan nilai ARGB dari instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini, kompatibel dengan metode `System.Drawing.Color.ToArgb()`. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Menyerialisasikan instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini ke notasi heksadesimal `##RRGGBB` sebagai string tanpa kanal alfa. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Menyerialisasikan instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini ke notasi heksadesimal `##RRGGBBAA` sebagai string dengan kanal alfa. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Menyerialisasikan instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini ke notasi fungsi CSS `rgb`, menghilangkan kanal alfa. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Menyerialisasikan instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini ke notasi fungsi CSS 'rgba'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Menyerialisasikan instance Argb32Color ke notasi fungsi CSS yang paling tepat tergantung pada tingkat transparansi. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Komponen alfa dari warna sebagai bilangan bulat tak bertanda 8-bit dalam rentang 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Komponen alfa dari warna sebagai bilangan pecahan dalam rentang 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Komponen biru dari warna sebagai bilangan bulat tak bertanda 8-bit dalam rentang 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Komponen hijau dari warna sebagai bilangan bulat tak bertanda 8-bit dalam rentang 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | Properti ini menunjukkan apakah instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini adalah default (transparan), yang berarti keempat kanal diatur ke 0; ini setara dengan [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | Properti ini menunjukkan apakah instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini belum diinisialisasi (keempat kanal diatur ke 0). Ini setara dengan warna default atau transparan dan cocok dengan [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | Properti ini menunjukkan apakah instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini sepenuhnya tidak tembus, tanpa transparansi (kanal Alfa-nya memiliki nilai maksimum). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | Properti ini menunjukkan apakah instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini sepenuhnya transparan—kanal Alfa-nya memiliki nilai minimum (0), sehingga kanal R, G, dan B tidak memberikan efek yang terlihat. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | Properti ini menunjukkan apakah instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ini tembus (tidak sepenuhnya transparan, namun juga tidak sepenuhnya tidak tembus). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Komponen merah dari warna sebagai bilangan bulat tak bertanda 8-bit (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | Representasi bilangan bulat bertanda 32-bit dari warna. |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Mengembalikan warna kosong, yang tidak memiliki informasi kanal dan sepenuhnya transparan. Sama dengan ''. Nilai default. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Warna kosong yang sepenuhnya transparan. Sama dengan nilai warna default ''. |

### Contoh

```python
from groupdocs.viewer.drawing import Argb32Color

# Buat warna kuning yang sepenuhnya tidak tembus (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Lihat Juga
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
