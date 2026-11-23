---
title: "PresentationFontInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Viewer örneğine yüklenen bir Presentation belgesinden bir yazı tipinin meta bilgisi ve ikili verilerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Bir Presentation belgesinden yüklenen bir yazı tipinin meta bilgilerini ve ikili verilerini bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneğinde temsil eder. Yazı tipi belge içeriğinde kullanılır ve belgeye gömülü olabilir veya görüntüleyicinin çalıştığı işletim sistemine kurulmuş olabilir.

PresentationFontInfo türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Bu yazı tipi bilgisini bir @font-face at-kuralı olarak serileştirir ve belirtilen metin yazarına yazar. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | Bu yazı tipinin içeriği bir bayt dizisi olarak. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | Yazı tipinin aile adı, stil olmadan; asla None veya boş dize değildir. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | Bu yazı tipinin biçimi. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | Bu özellik, yazı tipinin belge içinde gömülü olup [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneğine (`True`) yüklendiğini ya da sistem yazı tipi (`False`) olduğunu gösterir. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | Yazı tipinin stili — Regular, Bold, Italic veya Bold Italic olabilir. |

### Ayrıca Bakınız
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
