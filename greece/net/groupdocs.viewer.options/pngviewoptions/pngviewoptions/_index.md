---
title: "PngViewOptions"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί μια παρουσία της κλάσης PngViewOptionsgroupdocs.viewer.options/pngviewoptions."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *createPageStream* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει μια ροή που δημιουργήθηκε από μέθοδο που ανατέθηκε σε delegate που περάστηκε στην παράμετρο *createPageStream*. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *createPageStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *releasePageStream* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της εξαγόμενης ροής σελίδας. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *pageStreamFactory* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Δείτε επίσης

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions()
```

### Παρατηρήσεις

Αυτός ο κατασκευαστής αρχικοποιεί μια παρουσία της [`PngViewOptions`](../../pngviewoptions) με "p_{0}.png" ως μορφή διαδρομής αρχείου για τα αρχεία εξόδου. Τα αρχεία εξόδου τοποθετούνται στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Δείτε επίσης

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Αρχικοποιεί μια παρουσία της κλάσης [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(string filePathFormat)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'page_{0}.png'. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *filePathFormat* είναι null ή κενό. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Δείτε επίσης

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
