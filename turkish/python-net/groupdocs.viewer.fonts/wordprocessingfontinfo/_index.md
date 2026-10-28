---
title: "WordProcessingFontInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir Viewer örneğine yüklenen WordProcessing belgesinden bir yazı tipinin meta bilgisini ve ikili verisini kapsüller."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Bir WordProcessing belgesinden yüklenen bir yazı tipinin meta bilgilerini ve ikili verilerini bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneğinde kapsüller.

Değiştirilemez yapı.

Örnekleri, [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) genel API'si tarafından üretilir ve döndürülür ve normalde kullanıcı tarafından oluşturulmamalıdır.

Ayrıntılar için belgeleri inceleyin: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingFontInfo türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Yazı tipi bilgisini bir @font-face at-kuralı olarak serileştirir ve belirtilen metin yazarına yazar. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Bu yazı tipi verisi hakkında hata ayıklama bilgisini şu şablonla döndürür: "ad stil, gömülü/sistem, format". |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | Yazı tipinin alternatif aile adı. Eksikse, boş bir dize döner. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | Bu yazı tipinin karakter kümesi. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | Bu yazı tipinin içeriği bayt dizisi olarak. Yalnızca bu yazı tipi hakkında meta bilgi mevcut ve ikili içerik bulunmuyorsa, özellik None döndürür. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | Yazı tipinin aile adı, stil olmadan; asla None veya boş dize değildir. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Bu yazı tipinin biçimi. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | Bu özellik, yazı tipinin belge içinde gömülü olup olmadığını, [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneğine yüklendiğini (`True`) ya da sistem yazı tipi olduğunu (`False`) gösterir. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | Yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir. |

### Ayrıca Bakınız
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
