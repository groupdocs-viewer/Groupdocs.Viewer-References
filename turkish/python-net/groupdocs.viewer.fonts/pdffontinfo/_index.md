---
title: "PdfFontInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir Viewer örneğine yüklenen PDF yazı tipinin meta verilerini ve ikili verilerini kapsüller; bu yazı tipi belgeye gömülü olabilir veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulmuş olabilir."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

`[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` örneğine yüklenen bir PDF yazı tipinin meta verilerini ve ikili verilerini kapsüller; bu yazı tipi belgeye gömülü olabilir veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulmuş olabilir.

PdfFontInfo türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Bu yazı tipi bilgisini bir @font-face at-kuralı olarak serileştirir ve belirtilen metin yazarına yazar. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | Bu yazı tipinin içeriği bayt dizisi olarak, yalnızca meta veri mevcutsa ve ikili içerik bulunamıyorsa None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | Yazı tipinin aile adı, stil olmadan; asla None veya boş dize değildir. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Bu yazı tipinin biçimi. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | Bu özellik, yazı tipinin PDF belgesi içinde gömülü olup Viewer örneğine (`True`) yüklendiğini ya da olmadığını gösterir. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | Bu özellik, bu yazı tipinin GroupDocs.Viewer'ın çalıştığı işletim sisteminde mevcut (kurulu) olup olmadığını gösterir. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | Yazı tipinin stili; Regular, Bold, Italic veya Bold Italic olabilir. |

### Ayrıca Bakınız
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
