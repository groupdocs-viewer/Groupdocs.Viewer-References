---
title: "Rgb24Color sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Her kanal (Kırmızı, Yeşil, Mavi) için 8 bit olmak üzere 24-bit RGB rengi temsil eder ve şeffaflık içermez."
type: docs
url: /tr/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Her kanal (Kırmızı, Yeşil, Mavi) için 8 bit olmak üzere 24-bit RGB rengi temsil eder ve şeffaflık içermez.

Bu tür, (ancak yalnızca CSS işlemleriyle sınırlı olmamak üzere) CSS işlemleri için faydalı olacak şekilde tasarlanmıştır. Daha fazla bilgi: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

The Rgb24Color türü aşağıdaki üyeleri içerir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Bu rengin belirtilen [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ile eşit olup olmadığını belirler. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Bu rengin belirtilen [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) rengiyle eşitliğini kontrol eder. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Bu rengi belirtilen dönüştürülmemiş renge karşı kontrol eder. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Belirtilen kırmızı, yeşil ve mavi kanal değerlerinden bir [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) değeri oluşturur. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Bu [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) örneği için Hue‑Saturation‑Lightness (HSL) ışıklık/parlaklığını döndürür. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Geçerli rengi tanımlayan bir karma kodu döndürür. `System.Drawing.Color.GetHashCode` ile uyumlu değildir. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Renk ton bileşenini HSL renk uzayında derece cinsinden döndürür. Renk gri tonlamalıysa (R == G == B), ton tanımsızdır ve yöntem 0 döndürür. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | Bu [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) örneği için Hue‑Saturation‑Lightness (HSL) doygunluğu. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Bu [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) örneğinin ARGB değerini döndürür, `System.Drawing.Color` ile uyumludur. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Bu rengi onaltılık dize temsili olarak döndürür. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Bu [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) örneğini 'rgb' CSS fonksiyon gösterimine serileştirir. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Bu [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) örneğini 'rgb(r, g, b)' biçimine serileştirir. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | Rengin mavi bileşeni 8-bit işaretsiz tamsayı olarak [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | Renk yeşil bileşeni, 0..255 aralığındaki 8 bit işaretsiz tam sayı olarak. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | Bu [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) örneğinin varsayılan (Siyah) olup olmadığını gösteren özellik – üç kanal da 0 olarak ayarlanmıştır. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | Renk kırmızı bileşeni, 0..255 aralığındaki 8 bit işaretsiz tam sayı olarak. |

### Ayrıca Bakınız
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
