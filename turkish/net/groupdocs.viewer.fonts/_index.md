---
title: "GroupDocs.Viewer.Fonts"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Ad alanı, renderleme sürecinde kullanılan yazı tiplerini yönetmek için sınıflar ve enumlar sağlar."
type: docs
weight: 50
url: /tr/net/groupdocs.viewer.fonts/
---

Ad alanı, renderleme sürecinde kullanılan yazı tiplerini yönetmek için sınıflar ve enumlar sağlar.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [FolderFontSource](./folderfontsource) | TrueType yazı tiplerini içeren klasörü temsil eder. |
| [FontSettings](./fontsettings) | TrueType yazı tiplerini aramak için kaynaklarla çalışmaya yönelik yöntemler sağlar. |
## Structures

| Yapı | Açıklama |
| --- | --- |
| [FontStyles](./fontstyles) | Belgede kullanılan yazı tipinin 4 olası stilini temsil eder: Regular, Bold, Italic, or Bold Italic |
| [PdfFontInfo](./pdffontinfo) | PDF belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini, [`Viewer`](../groupdocs.viewer/viewer) örneğine yüklenmiş şekilde kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belgenin içinde gömülü olarak bulunur veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulu olur. |
| [PresentationFontInfo](./presentationfontinfo) | Sunum belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini, [`Viewer`](../groupdocs.viewer/viewer) örneğine yüklenmiş şekilde kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belgenin içinde gömülü olarak bulunur veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulu olur. |
| [SpreadsheetFontInfo](./spreadsheetfontinfo) | Elektronik tablo belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini, [`Viewer`](../groupdocs.viewer/viewer) örneğine yüklenmiş şekilde kapsüller. Elektronik tablo belgelerinde gömülü yazı tipleri bulunamaz, bu nedenle bu belirli yazı tipi, eğer [`GetAllFonts`](../groupdocs.viewer/viewer/getallfonts) yöntemi tarafından döndürülmüşse, GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulur. |
| [WordProcessingFontInfo](./wordprocessingfontinfo) | WordProcessing belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini, [`Viewer`](../groupdocs.viewer/viewer) örneğine yüklenmiş şekilde kapsüller. Bu yazı tipi belge içeriğinde kullanılır ve belgenin içinde gömülü olarak bulunur veya GroupDocs.Viewer'ın çalıştığı işletim sistemine kurulu olur. |
| [WordProcessingSubstitutedFontInfo](./wordprocessingsubstitutedfontinfo) | WordProcessing belgesinden bir yazı tipinin meta bilgisini ve ikili verilerini kapsüller; bu yazı tipi, [`Viewer`](../groupdocs.viewer/viewer) örneğine yüklenen belgede aslında kullanılmaz, ancak hedef makinede bulunamayanlar için bir yedek yazı tipi olarak hizmet eder. Yedek yazı tipleri yalnızca WordProcessing formatları ailesi için mevcuttur. |
## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [IFontInfo](./ifontinfo) | Tüm yazı tipleri için ortak arayüz, PDF, WordProcessing, Spreadsheet ve Presentation gibi desteklenen tüm belge formatı ailelerinden çıkarılabilir. |
| [IFontSource](./ifontsource) | Yazı tipi kaynakları için işaretleyici arayüz. |
## Numaralandırma

| Numaralandırma | Açıklama |
| --- | --- |
| [FontFormat](./fontformat) | [`IFontInfo`](../groupdocs.viewer.fonts/ifontinfo) türevlerinde bulunabilecek tüm yazı tipi formatlarını temsil eder. |
| [SearchOption](./searchoption) | Geçerli klasörü, ya da geçerli klasörü ve tüm alt klasörleri arayıp aramayacağını belirtir. |

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
