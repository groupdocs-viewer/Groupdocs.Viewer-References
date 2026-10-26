---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "FolderFontSourcegroupdocs.viewer.fonts/folderfontsource sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---

## FolderFontSource constructor

Yeni bir [`FolderFontSource`](../../folderfontsource) sınıfının örneğini başlatır.

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| folderPath | String | TrueType yazı tiplerini içeren klasörün yolu. |
| searchOption | SearchOption | Geçerli klasörü, ya da geçerli klasörü ve tüm alt klasörleri arayıp aramayacağını belirtir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *folderPath* null olduğunda fırlatılır. |
| DirectoryNotFoundException | *folderPath* içinde belirtilen yol bulunamadığında fırlatılır. |

### Ayrıca Bakınız

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
