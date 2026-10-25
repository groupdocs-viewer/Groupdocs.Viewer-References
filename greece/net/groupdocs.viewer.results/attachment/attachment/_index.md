---
title: "Attachment"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί νέα παρουσία της κλάσης Attachmentgroupdocs.viewer.results/attachment."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

Αρχικοποιεί νέα παρουσία της κλάσης [`Attachment`](../../attachment).

```csharp
public Attachment()
```

### Δείτε επίσης

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

Αρχικοποιεί νέα παρουσία της κλάσης [`Attachment`](../../attachment).

```csharp
public Attachment(string fileName, string filePath)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| fileName | String | Όνομα αρχείου Attachment. |
| filePath | String | Σχετική διαδρομή συνημμένου π.χ. folder/file.docx ή όνομα αρχείου όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε μήνυμα ηλεκτρονικού ταχυδρομείου ή αρχείο δεδομένων. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Ρίχνεται όταν *fileName* είναι null ή κενό. |
| ArgumentException | Εκτοπίζεται όταν το *filePath* είναι null ή κενό. |

### Δείτε επίσης

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

Αρχικοποιεί νέα παρουσία της κλάσης [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| id | String | Μοναδικό (στο πλαίσιο ενός μόνο αρχείου) αναγνωριστικό του συνημμένου. |
| fileName | String | Όνομα αρχείου Attachment. |
| filePath | String | Σχετική διαδρομή συνημμένου π.χ. folder/file.docx ή όνομα αρχείου όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε μήνυμα ηλεκτρονικού ταχυδρομείου ή αρχείο δεδομένων. |
| size | Int64 | Μέγεθος αρχείου Attachment σε bytes. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *id* είναι null ή κενό. |
| ArgumentException | Ρίχνεται όταν *fileName* είναι null ή κενό. |
| ArgumentException | Εκτοπίζεται όταν το *filePath* είναι null ή κενό. |

### Δείτε επίσης

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

Αρχικοποιεί νέα παρουσία της κλάσης [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| id | String | Μοναδικό (στο πλαίσιο ενός μόνο αρχείου) αναγνωριστικό του συνημμένου. |
| fileName | String | Όνομα αρχείου Attachment. |
| filePath | String | Σχετική διαδρομή συνημμένου π.χ. folder/file.docx ή όνομα αρχείου όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε μήνυμα ηλεκτρονικού ταχυδρομείου ή αρχείο δεδομένων. |
| fileType | FileType | Τύπος αρχείου Attachment. |
| size | Int64 | Μέγεθος αρχείου Attachment σε bytes. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *id* είναι null ή κενό. |
| ArgumentException | Ρίχνεται όταν *fileName* είναι null ή κενό. |
| ArgumentException | Εκτοπίζεται όταν το *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν το *fileType* είναι null. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
