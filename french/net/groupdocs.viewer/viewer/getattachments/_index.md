---
title: "GetAttachments"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Renvoie les pièces jointes contenues dans le document."
type: docs
weight: 40
url: /fr/net/groupdocs.viewer/viewer/getattachments/
---

## GetAttachments() {#getattachments}

Renvoie les pièces jointes contenues dans le document.

```csharp
public IList<Attachment> GetAttachments()
```

### Valeur de retour

Pièces jointes contenues dans le document.

### Exceptions

| exception | condition |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |

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

## GetAttachments(CancellationToken) {#getattachments_1}

Renvoie les pièces jointes contenues dans le document.

```csharp
public IList<Attachment> GetAttachments(CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Pièces jointes contenues dans le document.

### Exceptions

| exception | condition |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |

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
