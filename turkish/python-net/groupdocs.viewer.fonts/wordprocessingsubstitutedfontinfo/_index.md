---
title: "WordProcessingSubstitutedFontInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir WordProcessing belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini kapsüller; bu yazı tipi başlangıçta yüklü Viewer örnek belgesinde kullanılmaz, ancak eksik olanlar için bir ikame yazı tipi olarak hizmet eder…"
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Yüklenen [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örnek belgesinde aslında kullanılmayan, ancak hedef makinede bulunamayanlar için bir yedek yazı tipi olarak hizmet veren bir WordProcessing belgesinden bir yazı tipinin meta bilgilerini ve ikili verilerini kapsüller. Yedek yazı tipleri yalnızca WordProcessing formatları ailesi için mevcuttur.

Değiştirilemez struct. Örnekleri, [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) genel API'si tarafından üretilir ve döndürülür ve normalde kullanıcı tarafından oluşturulmamalıdır. Ayrıntılar için belgeleri inceleyin: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingSubstitutedFontInfo türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Yazı tipi bilgisini bir @font-face at-kuralı olarak serileştirir ve belirtilen metin yazarına yazar. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Yazı tipi bilgilerini "original-name -> substituted-name style, format" biçiminde içeren bir hata ayıklama dizesi döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | İkame edilen yazı tipinin içeriği bayt dizisi olarak. Asla None değildir. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | İkame edilen yazı tipinin aile adı, stil olmadan. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Bu ikame (orijinal olmayan) yazı tipinin biçimi. |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | Hedef makinede bulunamayan orijinal yazı tipinin aile adı, stil olmadan. Asla null veya boş dize değildir. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | Orijinal yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir. |

### Ayrıca Bakınız
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
