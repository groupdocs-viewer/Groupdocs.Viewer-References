---
title: "SpreadsheetFontInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Viewer örneğine yüklenen bir elektronik tablo belgesinden bir yazı tipinin meta bilgisi ve ikili verilerini kapsüller."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Bir elektronik tablo belgesinden yüklenen bir yazı tipinin meta bilgilerini ve ikili verilerini bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneğinde kapsüller. Elektronik tablo belgelerinde gömülü yazı tipleri bulunamaz, bu yüzden [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) tarafından döndürülen bir yazı tipi, görüntüleyicinin çalıştığı işletim sistemine kurulur.

SpreadsheetFontInfo türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Yazı tipi bilgisini bir @font-face at-kuralı olarak serileştirir ve belirtilen metin yazarına yazar. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | Bu yazı tipinin karakter kümesi. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | Bu yazı tipinin rengi. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | Bu yazı tipinin içeriği bir bayt dizisi olarak. Yalnızca bu yazı tipiyle ilgili meta bilgi mevcut ve ikili içeriği bulunmuyorsa, özellik None döndürür. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | Yazı tipinin stil olmadan aile adı, hiçbir zaman null veya boş string değildir. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Bu yazı tipinin biçimi. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | Yazı tipinin tek bir üstü çizili özelliği vardır. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | Yazı tipinin altı çizili özelliği vardır. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | Bu yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir. |

### Ayrıca Bakınız
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
