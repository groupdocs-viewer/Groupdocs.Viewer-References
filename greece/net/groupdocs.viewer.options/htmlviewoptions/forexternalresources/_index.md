---
title: ForExternalResources
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Αρχικοποιεί νέα παρουσία τουHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions κλάση για απόδοση σε HTML με εξωτερικούς πόρους.
type: docs
weight: 20
url: /el/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| createResourceStream | CreateResourceStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από*createPageStream* μέθοδος. |
| createResourceUrl | CreateResourceUrl | Η μέθοδος που δημιουργεί τη διεύθυνση URL για τον πόρο HTML. |

### Επιστρεφόμενη Αξία

Νέο παράδειγμα του[`HtmlViewOptions`](../../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*createPageStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*createResourceStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*createResourceUrl* είναι μηδενικό. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../htmlviewoptions)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| createResourceStream | CreateResourceStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων πόρων HTML εξόδου. |
| createResourceUrl | CreateResourceUrl | Η μέθοδος που δημιουργεί τη διεύθυνση URL για τον πόρο HTML. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε με τη μέθοδο που έχει εκχωρηθεί για την ανάθεση της ροής στη*createPageStream* παράμετρος. |
| releaseResourceStream | ReleaseResourceStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε με τη μέθοδο που έχει εκχωρηθεί για την ανάθεση της ροής στη*createResourceStream* παράμετρος. |

### Επιστρεφόμενη Αξία

Νέο παράδειγμα του[`HtmlViewOptions`](../../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*createPageStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*createResourceStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*createResourceUrl* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*releasePageStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*releaseResourceStream* είναι μηδενικό. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../htmlviewoptions)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Το εργοστάσιο που εφαρμόζει μεθόδους για τη δημιουργία και την απελευθέρωση ροής σελίδας εξόδου. |
| resourceStreamFactory | IResourceStreamFactory | Το εργοστάσιο που εφαρμόζει μεθόδους που απαιτούνται για τη δημιουργία διεύθυνσης URL πόρων, τη δημιουργία και την απελευθέρωση ροής πόρων HTML εξόδου. |

### Επιστρεφόμενη Αξία

Νέο παράδειγμα του[`HtmlViewOptions`](../../htmlviewoptions) κλάση για απόδοση σε HTML με εξωτερικούς πόρους.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*pageStreamFactory* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*resourceStreamFactory* είναι μηδενικό. |

### Δείτε επίσης

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../htmlviewoptions)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../../htmlviewoptions) τάξη.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Παρατηρήσεις

Αυτός ο κατασκευαστής αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../../htmlviewoptions) - με "p_{0}.html" ως μορφή διαδρομής αρχείου για τα αρχεία HTML εξόδου; - με "p_{0}_{1}" ως μορφή διαδρομής αρχείου για τα αρχεία πόρων HTML εξόδου; - με " p_{0}_{1}" ως μορφή URL για πόρους HTML; Τα αρχεία εξόδου θα τοποθετηθούν στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

### Δείτε επίσης

* class [HtmlViewOptions](../../htmlviewoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../htmlviewoptions)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Αρχικοποιεί νέα παρουσία του[`HtmlViewOptions`](../../htmlviewoptions) τάξη.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. "page_{0}.html". |
| resourceFilePathFormat | String | Η μορφή διαδρομής του αρχείου πόρων π.χ. "page_{0}/resource_{1}". |
| resourceUrlFormat | String | Η μορφή διεύθυνσης URL του πόρου, π.χ. "page_{0}/resource_{1}". |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Ρίχτηκε όταν*filePathFormat* είναι μηδενικό ή κενό. |
| ArgumentException | Ρίχτηκε όταν*resourceFilePathFormat* είναι μηδενικό ή κενό. |
| ArgumentException | Ρίχτηκε όταν*resourceUrlFormat* είναι μηδενικό ή κενό. |

### Δείτε επίσης

* class [HtmlViewOptions](../../htmlviewoptions)
* χώρος ονομάτων [GroupDocs.Viewer.Options](../../htmlviewoptions)
* συνέλευση [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
