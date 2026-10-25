---
title: "PdfViewOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί μια παρουσία της κλάσης PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| createFileStream | CreateFileStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου αρχείου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *createFileStream* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Δείτε επίσης

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| createFileStream | CreateFileStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου αρχείου. |
| releaseFileStream | ReleaseFileStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που ανατέθηκε σε delegate που περάστηκε ως παράμετρος *createFileStream*. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *createFileStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *releaseFileStream* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Δείτε επίσης

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | Η εργοστασιακή μονάδα που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση του ρεύματος εξόδου αρχείου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εγείρεται όταν *fileStreamFactory* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Δείτε επίσης

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions()
```

### Παρατηρήσεις

Αυτός ο κατασκευαστής αρχικοποιεί μια παρουσία του [`PdfViewOptions`](../../pdfviewoptions) με το "output.pdf" ως μορφή διαδρομής αρχείου για το αρχείο εξόδου. Το αρχείο εξόδου θα τοποθετηθεί στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Δείτε επίσης

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

Αρχικοποιεί μια παρουσία της κλάσης [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(string outputFilePath)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| outputFilePath | String | Η διαδρομή για το αρχείο PDF εξόδου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται όταν *outputFilePath* είναι null ή κενό. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Δείτε επίσης

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
