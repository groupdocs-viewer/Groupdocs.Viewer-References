---
title: "ForEmbeddedResources"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί μια παρουσία της κλάσης HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions για απόδοση σε HTML με ενσωματωμένους πόρους."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή (stream) που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου της σελίδας. |

### Τιμή Επιστροφής

Νέα παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *createPageStream* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή (stream) που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου της σελίδας. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που ανατέθηκε στο delegate που περάστηκε στην παράμετρο *createPageStream*. |

### Τιμή Επιστροφής

Νέα παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *createPageStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *releasePageStream* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της εξαγόμενης ροής σελίδας. |

### Τιμή Επιστροφής

Νέα παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με ενσωματωμένους πόρους.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *pageStreamFactory* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Δείτε επίσης

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Δείτε επίσης

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'page_{0}.html'. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *filePathFormat* είναι null ή κενό. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Δείτε επίσης

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
