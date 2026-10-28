---
title: "IFontInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "PDF, WordProcessing, Spreadsheet ve Presentation gibi desteklenen tüm belge formatı ailelerinden çıkarılabilen tüm yazı tipleri için ortak bir arayüzü temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

PDF, WordProcessing, Spreadsheet ve Presentation gibi desteklenen tüm belge formatı ailelerinden çıkarılabilen tüm yazı tipleri için ortak bir arayüzü temsil eder.

The IFontInfo türü aşağıdaki üyeleri içerir:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Bu yazı tipi bilgisini bir @font-face at-kuralı olarak serileştirir ve belirtilen metin yazarına yazar. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | Yazı tipinin ikili içeriği, mevcutsa bayt dizisi olarak, yoksa None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | Yazı tipinin aile adı bir dize olarak. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Bu yazı tipinin biçimi bir enum olarak — TrueType, TrueType Collection, OpenType, Embedded OpenType veya `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | Yazı tipinin stili bir enum olarak (Regular, Bold, Italic veya Bold Italic); bazı belge formatları yalnızca [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) destekleyebilir. |

### Ayrıca Bakınız
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
