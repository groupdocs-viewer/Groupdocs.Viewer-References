---
title: "SaveAttachment"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Ek dosyasını hedef akışa kaydeder."
type: docs
weight: 70
url: /tr/net/groupdocs.viewer/viewer/saveattachment/
---

## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

Ek dosyasını *destination* akışına kaydeder.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| ek | Attachment | Ek. |
| hedef | Akış | Yazılabilir akış. |
| cancellationToken | CancellationToken | İptal belirteci. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *attachment* null olduğunda fırlatılır. |
| ArgumentNullException | *destination* null olduğunda fırlatılır. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ek bulunamadığında fırlatılır. |

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

## SaveAttachment(Attachment, Stream) {#saveattachment}

Ek dosyasını *destination* akışına kaydeder.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| ek | Attachment | Ek. |
| hedef | Akış | Yazılabilir akış. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *attachment* null olduğunda fırlatılır. |
| ArgumentNullException | *destination* null olduğunda fırlatılır. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Belgeyi açmak için şifre gerektiğinde atılır. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Belirtilen şifre yanlış olduğunda atılır. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ek bulunamadığında fırlatılır. |

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
