---
title: "kelas Rgb24Color"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili warna RGB 24-bit dengan 8 bit per saluran (Merah, Hijau, Biru) dan tanpa transparansi."
type: docs
url: /id/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Mewakili warna RGB 24-bit dengan 8 bit per saluran (Merah, Hijau, Biru) dan tanpa transparansi.

Tipe ini dirancang untuk berguna dalam operasi CSS (meskipun tidak terbatas pada itu). Lihat selengkapnya: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Tipe Rgb24Color mengekspos anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Menentukan apakah warna ini sama dengan [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) yang ditentukan. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Memeriksa warna ini dengan warna [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) yang ditentukan untuk kesetaraan. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Memeriksa warna ini terhadap warna yang belum di‑cast yang ditentukan. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Membuat nilai [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) dari nilai saluran merah, hijau, dan biru yang ditentukan. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Mengembalikan kecerahan (lightness) Hue‑Saturation‑Lightness (HSL) untuk instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) ini. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Mengembalikan kode hash yang mendefinisikan warna saat ini. Tidak kompatibel dengan `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Mengembalikan komponen hue dari warna dalam ruang warna HSL, dinyatakan dalam derajat. Jika warna adalah skala abu‑abu (R == G == B), hue tidak terdefinisi dan metode mengembalikan 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | Saturasi Hue‑Saturation‑Lightness (HSL) untuk instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) ini. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Mengembalikan nilai ARGB dari instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) ini, kompatibel dengan `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Mengembalikan warna ini dalam representasi string heksadesimal. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Menyerialisasi instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) ini ke notasi fungsi CSS 'rgb'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Menyerialisasi instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) ini ke format 'rgb(r, g, b)'. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | Komponen biru dari warna sebagai integer tak bertanda 8-bit [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | Komponen hijau dari warna sebagai bilangan bulat tak bertanda 8-bit dalam rentang 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | Properti ini menunjukkan apakah instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) ini adalah default (Hitam) – ketiga saluran diatur ke 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | Komponen merah dari warna sebagai bilangan bulat tak bertanda 8-bit (0..255). |

### Lihat Juga
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
