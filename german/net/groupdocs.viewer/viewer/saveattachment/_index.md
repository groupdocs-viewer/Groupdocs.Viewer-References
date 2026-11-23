---
title: "SaveAttachment"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Speichert die Anhangdatei im Zielstream."
type: docs
weight: 70
url: /de/net/groupdocs.viewer/viewer/saveattachment/
---

## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

Speichert die Anhangsdatei in den *Ziel*-Stream.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Anhang | Attachment | Der Anhang. |
| Ziel | Stream | Der beschreibbare Stream. |
| cancellationToken | CancellationToken | Abbruch‑Token. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *attachment* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *destination* null ist. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Passwort inkorrekt ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn der Anhang nicht gefunden werden konnte. |

### Bemerkungen

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Siehe auch

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SaveAttachment(Attachment, Stream) {#saveattachment}

Speichert die Anhangsdatei in den *Ziel*-Stream.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Anhang | Attachment | Der Anhang. |
| Ziel | Stream | Der beschreibbare Stream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *attachment* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *destination* null ist. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Passwort inkorrekt ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn der Anhang nicht gefunden werden konnte. |

### Bemerkungen

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Siehe auch

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
