---
title: "Argb32Color sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "ARGB formatında, her kanal (Alfa, Kırmızı, Yeşil, Mavi) için 8 bit olmak üzere 32 bit rengi temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

ARGB formatında, her kanal (Alfa, Kırmızı, Yeşil, Mavi) için 8 bit olmak üzere 32-bit rengi temsil eder. Şeffaflığı destekler.

Bu tür, (ancak yalnızca CSS işlemleriyle sınırlı olmamak üzere) CSS işlemleri için faydalı olacak şekilde tasarlanmıştır. Daha fazla bilgi: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Argb32Color türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Bu rengin belirtilen [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ile eşit olup olmadığını denetler. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Bu rengin belirtilen [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) ile eşit olup olmadığını belirler. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Bu rengin belirtilen dönüştürülmemiş renkle eşit olup olmadığını denetler. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Bir 32-bit ARGB değerinden, `System.Drawing.Color.ToArgb()` tarafından üretilen değerlerle uyumlu bir Argb32Color örneği oluşturur. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Belirtilen örnekten yeni bir [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneği oluşturur, ancak yeniden tanımlanmış alfa (opaklık) değeriyle. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Belirtilen bir Rgb24Color'dan yeni bir Argb32Color örneği oluşturur, ancak belirtilen alfa (opaklık) değeriyle. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Belirtilen Kırmızı, Yeşil, Mavi kanallardan bir Argb32Color değeri oluşturur ve Alfa kanalını tamamen opak olarak ayarlar. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Belirtilen kırmızı, yeşil, mavi ve alfa kanal değerlerinden bir [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) değeri oluşturur. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Tüm kanallara uygulanan tek bir bayt değerinden tamamen opak (A=255) bir renk oluşturur. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneği için Hue‑Saturation‑Lightness (HSL) aydınlık/değerini döndürür. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Geçerli rengi tanımlayan bir hash kodu döndürür; `System.Drawing.Color.GetHashCode` ile uyumlu değildir. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneği için derece cinsinden Hue‑Saturation‑Lightness (HSL) ton değerini döndürür; eğer R == G == B ise ton anlamsızdır ve yöntem 0 döndürür. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğinin Hue‑Saturation‑Lightness (HSL) doygunluğunu döndürür. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğinin ARGB değerini döndürür; `System.Drawing.Color.ToArgb()` yöntemiyle uyumludur. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğini alfa kanalı olmadan bir dize olarak `##RRGGBB` onaltılık gösterimine serileştirir. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğini alfa kanalıyla bir dize olarak `##RRGGBBAA` onaltılık gösterimine serileştirir. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğini alfa kanalını atlayarak `rgb` CSS fonksiyon gösterimine serileştirir. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğini 'rgba' CSS fonksiyon gösterimine serileştirir. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Argb32Color örneğini saydamlığa bağlı olarak en uygun CSS fonksiyon gösterimine serileştirir. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Renk alfa bileşeni, 0..255 aralığındaki 8 bit işaretsiz tam sayı olarak. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Renk alfa bileşeni, 0..1 aralığındaki kayan nokta sayı olarak. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Renk mavi bileşeni, 0..255 aralığındaki 8 bit işaretsiz tam sayı olarak. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Renk yeşil bileşeni, 0..255 aralığındaki 8 bit işaretsiz tam sayı olarak. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | Bu özellik, bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğinin varsayılan (şeffaf) olup olmadığını gösterir; yani dört kanalın da 0 olarak ayarlandığı anlamına gelir; [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) ile eşdeğerdir. |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | Bu özellik, bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğinin başlatılmamış (dört kanalın da 0 olarak ayarlandığı) olup olmadığını gösterir. Varsayılan veya şeffaf renkle eşdeğer olup, [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) ile eşleşir. |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | Bu özellik, bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğinin tamamen opak, şeffaflık içermediğini (Alfa kanalının maksimum değerde olduğunu) gösterir. |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | Bu özellik, bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğinin tamamen şeffaf olup olmadığını gösterir—Alfa kanalı minimum (0) değere sahiptir, bu yüzden R, G ve B kanalları görünür bir etki yapmaz. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | Bu özellik, bu [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) örneğinin yarı saydam (tamamen şeffaf değil, aynı zamanda tamamen opak da değil) olup olmadığını gösterir. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Renk kırmızı bileşeni, 0..255 aralığındaki 8 bit işaretsiz tam sayı olarak. |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | Rengin 32 bit işaretli tam sayı temsili. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Kanal bilgisi olmayan ve tamamen şeffaf bir boş renk döndürür. '' ile aynı. Varsayılan değer. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Tamamen şeffaf boş renk. Varsayılan '' renk değeriyle aynı. |

### Örnek

```python
from groupdocs.viewer.drawing import Argb32Color

# Tamamen opak sarı bir renk oluşturun (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
