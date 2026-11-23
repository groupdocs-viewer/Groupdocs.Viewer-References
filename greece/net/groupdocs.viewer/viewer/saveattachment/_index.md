---
title: "SaveAttachment"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αποθηκεύει το αρχείο συνημμένου στη ροή προορισμού."
type: docs
weight: 70
url: /el/net/groupdocs.viewer/viewer/saveattachment/
---

## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

Αποθηκεύει το αρχείο συνημμένου στη ροή *προορισμού*.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| συνημμένο | Attachment | Το συνημμένο. |
| προορισμός | Stream | Η εγγράψιμη ροή. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *attachment* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *destination* είναι null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Εγείρεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Εγείρεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Εκτοπίζεται όταν δεν βρέθηκε το συνημμένο. |

### Παρατηρήσεις

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Δείτε επίσης

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SaveAttachment(Attachment, Stream) {#saveattachment}

Αποθηκεύει το αρχείο συνημμένου στη ροή *προορισμού*.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| συνημμένο | Attachment | Το συνημμένο. |
| προορισμός | Stream | Η εγγράψιμη ροή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *attachment* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *destination* είναι null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Εγείρεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Εγείρεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Εκτοπίζεται όταν δεν βρέθηκε το συνημμένο. |

### Παρατηρήσεις

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Δείτε επίσης

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
