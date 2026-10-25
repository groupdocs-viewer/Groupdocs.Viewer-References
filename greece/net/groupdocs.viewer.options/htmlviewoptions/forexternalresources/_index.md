---
title: "ForExternalResources"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί μια παρουσία της κλάσης HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions για απόδοση σε HTML με εξωτερικούς πόρους."
type: docs
weight: 20
url: /el/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή (stream) που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου της σελίδας. |
| createResourceStream | CreateResourceStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο *createPageStream*. |
| createResourceUrl | CreateResourceUrl | Η μέθοδος που δημιουργεί URL για τον πόρο HTML. |

### Τιμή Επιστροφής

Νέα παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *createPageStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *createResourceStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *createResourceUrl* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή (stream) που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου της σελίδας. |
| createResourceStream | CreateResourceStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων του εξαγόμενου πόρου HTML. |
| createResourceUrl | CreateResourceUrl | Η μέθοδος που δημιουργεί URL για τον πόρο HTML. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που ανατέθηκε στο delegate που περάστηκε στην παράμετρο *createPageStream*. |
| releaseResourceStream | ReleaseResourceStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που ανατέθηκε στο delegate που περάστηκε στην παράμετρο *createResourceStream*. |

### Τιμή Επιστροφής

Νέα παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *createPageStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *createResourceStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *createResourceUrl* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *releasePageStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *releaseResourceStream* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της εξαγόμενης ροής σελίδας. |
| resourceStreamFactory | IResourceStreamFactory | Το εργοστάσιο που υλοποιεί τις μεθόδους που απαιτούνται για τη δημιουργία URL πόρου, την δημιουργία και την απελευθέρωση της εξαγόμενης ροής πόρου HTML. |

### Τιμή Επιστροφής

Νέα παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions) για απόδοση σε HTML με εξωτερικούς πόρους.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *pageStreamFactory* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *resourceStreamFactory* είναι null. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Δείτε επίσης

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Παρατηρήσεις

Αυτός ο κατασκευαστής αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions)

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

Τα αρχεία εξόδου θα τοποθετηθούν στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Δείτε επίσης

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Αρχικοποιεί μια παρουσία της κλάσης [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'page_{0}.html'. |
| resourceFilePathFormat | String | Η μορφή διαδρομής αρχείου πόρων π.χ. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Η μορφή URL πόρων π.χ. 'page_{0}/resource_{1}'. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *filePathFormat* είναι null ή κενό. |
| ArgumentException | Εκτοπίζεται όταν το *resourceFilePathFormat* είναι null ή κενό. |
| ArgumentException | Εκτοπίζεται όταν το *resourceUrlFormat* είναι null ή κενό. |

### Παρατηρήσεις

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Δείτε επίσης

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
