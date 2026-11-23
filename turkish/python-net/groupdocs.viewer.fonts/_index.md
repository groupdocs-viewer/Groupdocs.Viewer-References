---
title: "groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Yazı tipi yükleme ve ikame yapılandırması."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Yazı tipi yükleme ve ikame yapılandırması.

### Sınıflar
| Sınıf | Açıklama |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | TrueType yazı tiplerini içeren klasörü temsil eder. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | TrueType yazı tiplerini aramak için kaynaklarla çalışmaya yönelik metodlar sağlar. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Belge içinde kullanılan yazı tipinin 4 olası stilini temsil eder: Normal, Kalın, İtalik veya Kalın İtalik. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | PDF, WordProcessing, Spreadsheet ve Presentation gibi desteklenen tüm belge formatı ailelerinden çıkarılabilen tüm yazı tipleri için ortak bir arayüzü temsil eder. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | `[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)` örneğine yüklenen bir PDF yazı tipinin meta verilerini ve ikili verilerini kapsüller; bu yazı tipi belgeye gömülü olabilir veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulmuş olabilir. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Bir Presentation belgesinden yüklenen bir yazı tipinin meta bilgilerini ve ikili verilerini bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneğinde temsil eder. Yazı tipi belge içeriğinde kullanılır ve belgeye gömülü olabilir veya görüntüleyicinin çalıştığı işletim sistemine kurulmuş olabilir. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Bir elektronik tablo belgesinden yüklenen bir yazı tipinin meta bilgilerini ve ikili verilerini bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneğinde kapsüller. Elektronik tablo belgelerinde gömülü yazı tipleri bulunamaz, bu yüzden [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) tarafından döndürülen bir yazı tipi, görüntüleyicinin çalıştığı işletim sistemine kurulur. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Bir WordProcessing belgesinden yüklenen bir yazı tipinin meta bilgilerini ve ikili verilerini bir [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örneğinde kapsüller. |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Yüklenen [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) örnek belgesinde aslında kullanılmayan, ancak hedef makinede bulunamayanlar için bir yedek yazı tipi olarak hizmet veren bir WordProcessing belgesinden bir yazı tipinin meta bilgilerini ve ikili verilerini kapsüller. Yedek yazı tipleri yalnızca WordProcessing formatları ailesi için mevcuttur. |

### Enumlar
| Enum | Açıklama |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Yazı tipi kaynakları için bir işaretçi arayüzünü temsil eder. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
