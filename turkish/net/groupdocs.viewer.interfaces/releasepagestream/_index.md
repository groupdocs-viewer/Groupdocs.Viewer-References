---
title: "ReleasePageStream"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "CreatePageStream./createpagestream temsilcisiyle ilişkili yöntem tarafından oluşturulan akışı serbest bırakır."
type: docs
weight: 710
url: /tr/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

[`CreatePageStream`](../createpagestream) temsilcisiyle ilişkili yöntem tarafından oluşturulan akışı serbest bırakır.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageNumber | Int32 | Sayfanın numarası. |
| pageStream | Stream | [`CreatePageStream`](../createpagestream) temsilcisiyle ilişkili yöntem tarafından oluşturulan akış. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
