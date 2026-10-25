---
title: "Προβολή"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Δημιουργεί προβολή όλων των σελίδων του εγγράφου."
type: docs
weight: 90
url: /el/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Δημιουργεί προβολή όλων των σελίδων του εγγράφου.

```csharp
public void View(ViewOptions options)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| options | ViewOptions | Οι επιλογές προβολής. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *options* είναι null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Εγείρεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Εγείρεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Εκτοπίζεται όταν δεν βρέθηκε το συνημμένο. |

### Παρατηρήσεις

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Δείτε επίσης

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Δημιουργεί προβολή όλων των σελίδων του εγγράφου.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| options | ViewOptions | Οι επιλογές προβολής. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για αποστολή αιτήματος ακύρωσης της τρέχουσας διαδικασίας προβολής. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *options* είναι null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Εγείρεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Εγείρεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Εκτοπίζεται όταν δεν βρέθηκε το συνημμένο. |

### Παρατηρήσεις

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Δείτε επίσης

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Δημιουργεί προβολή συγκεκριμένων σελίδων του εγγράφου.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| options | ViewOptions | Οι επιλογές προβολής. |
| pageNumbers | Int32[] | Οι αριθμοί σελίδων για προβολή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *options* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *pageNumbers* είναι null. |
| ArgumentException | Εκτοπίζεται όταν το *pageNumbers* είναι κενό. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Εγείρεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Εγείρεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Εκτοπίζεται όταν δεν βρέθηκε το συνημμένο. |

### Παρατηρήσεις

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Δείτε επίσης

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Δημιουργεί προβολή συγκεκριμένων σελίδων του εγγράφου.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| options | ViewOptions | Οι επιλογές προβολής. |
| pageNumbers | CancellationToken | Οι αριθμοί σελίδων για προβολή. |
| cancellationToken | Int32[] | Διακριτικό ακύρωσης για την ακύρωση της επεξεργασίας. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *options* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν το *pageNumbers* είναι null. |
| ArgumentException | Εκτοπίζεται όταν το *pageNumbers* είναι κενό. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Εγείρεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Εγείρεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Εκτοπίζεται όταν δεν βρέθηκε το συνημμένο. |

### Παρατηρήσεις

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Δείτε επίσης

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
