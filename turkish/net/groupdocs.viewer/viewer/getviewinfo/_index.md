---
title: "GetViewInfo"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Görünüm ve belgeye özgü bilgileri döndürür."
type: docs
weight: 60
url: /tr/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

Görünüm ve belgeye özgü bilgileri döndürür.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| seçenekler | ViewInfoOptions | Görünüm bilgi seçenekleri. |

### Dönüş Değeri

Görünüm ve belgeye özgü bilgiler hakkında bilgi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *options* null olduğunda fırlatılır. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |

### Açıklamalar

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Ayrıca Bakınız

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

Görünüm ve belgeye özgü bilgileri döndürür.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| seçenekler | ViewInfoOptions | Görünüm bilgi seçenekleri. |
| cancellationToken | CancellationToken | İptal belirteci. |

### Dönüş Değeri

Görünüm ve belgeye özgü bilgiler hakkında bilgi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *options* null olduğunda fırlatılır. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |

### Açıklamalar

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Ayrıca Bakınız

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
