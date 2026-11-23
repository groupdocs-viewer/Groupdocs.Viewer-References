---
title: "SaveAttachment"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Enregistre le fichier de pièce jointe dans le flux de destination."
type: docs
weight: 70
url: /fr/net/groupdocs.viewer/viewer/saveattachment/
---

## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

Enregistre le fichier de pièce jointe dans le flux *destination*.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pièce jointe | Attachment | La pièce jointe. |
| destination | Flux | Le flux inscriptible. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *attachment* est null. |
| ArgumentNullException | Levée lorsque *destination* est null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Levée lorsque la pièce jointe n'a pas pu être trouvée. |

### Remarques

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Voir aussi

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SaveAttachment(Attachment, Stream) {#saveattachment}

Enregistre le fichier de pièce jointe dans le flux *destination*.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pièce jointe | Attachment | La pièce jointe. |
| destination | Flux | Le flux inscriptible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *attachment* est null. |
| ArgumentNullException | Levée lorsque *destination* est null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Levée lorsque la pièce jointe n'a pas pu être trouvée. |

### Remarques

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Voir aussi

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
