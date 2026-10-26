---
title: "GetAttachments"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Belge tarafından içerilen ekleri döndürür."
type: docs
weight: 40
url: /tr/net/groupdocs.viewer/viewer/getattachments/
---

## GetAttachments() {#getattachments}

Belge tarafından içerilen ekleri döndürür.

```csharp
public IList<Attachment> GetAttachments()
```

### Dönüş Değeri

Belge tarafından içerilen ekler.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |

### Açıklamalar

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Ayrıca Bakınız

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetAttachments(CancellationToken) {#getattachments_1}

Belge tarafından içerilen ekleri döndürür.

```csharp
public IList<Attachment> GetAttachments(CancellationToken cancellationToken)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| cancellationToken | CancellationToken | İptal belirteci. |

### Dönüş Değeri

Belge tarafından içerilen ekler.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |

### Açıklamalar

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Ayrıca Bakınız

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
