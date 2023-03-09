---
title: View
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Δημιουργεί προβολή όλων των σελίδων του εγγράφου.
type: docs
weight: 70
url: /el/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Δημιουργεί προβολή όλων των σελίδων του εγγράφου.

```csharp
public void View(ViewOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | ViewOptions | Οι επιλογές προβολής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*options* είναι μηδενικό. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Πετάγεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Πετάγεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι εσφαλμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ρίχτηκε όταν δεν ήταν δυνατή η εύρεση του συνημμένου. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τις διαφορετικές επιλογές προβολής ακολουθώντας αυτόν τον οδηγό: [Πώς να προσαρμόσετε την έξοδο προβολής εγγράφων χρησιμοποιώντας το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Δείτε επίσης

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Δημιουργεί προβολή όλων των σελίδων του εγγράφου.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | ViewOptions | Οι επιλογές προβολής. |
| cancellationToken | CancellationToken | Διακριτικό ακύρωσης για να στείλετε ένα αίτημα για ακύρωση της τρέχουσας διαδικασίας προβολής. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*options* είναι μηδενικό. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Πετάγεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Πετάγεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι εσφαλμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ρίχτηκε όταν δεν ήταν δυνατή η εύρεση του συνημμένου. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τις διαφορετικές επιλογές προβολής ακολουθώντας αυτόν τον οδηγό: [Πώς να προσαρμόσετε την έξοδο προβολής εγγράφων χρησιμοποιώντας το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Δείτε επίσης

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Δημιουργεί προβολή συγκεκριμένων σελίδων εγγράφου.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | ViewOptions | Οι επιλογές προβολής. |
| pageNumbers | Int32[] | Οι αριθμοί σελίδων για προβολή. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*options* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*pageNumbers* είναι μηδενικό. |
| ArgumentException | Ρίχτηκε όταν*pageNumbers* είναι άδειο. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Πετάγεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Πετάγεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι εσφαλμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ρίχτηκε όταν δεν ήταν δυνατή η εύρεση του συνημμένου. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τις διαφορετικές επιλογές προβολής ακολουθώντας αυτόν τον οδηγό: [Πώς να προσαρμόσετε την έξοδο προβολής εγγράφων χρησιμοποιώντας το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Δείτε επίσης

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Δημιουργεί προβολή συγκεκριμένων σελίδων εγγράφου.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | ViewOptions | Οι επιλογές προβολής. |
| pageNumbers | CancellationToken | Οι αριθμοί σελίδων για προβολή. |
| cancellationToken | Int32[] | Διακριτικό ακύρωσης για ακύρωση της επεξεργασίας. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*options* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*pageNumbers* είναι μηδενικό. |
| ArgumentException | Ρίχτηκε όταν*pageNumbers* είναι άδειο. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Πετάγεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Πετάγεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι εσφαλμένος. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Ρίχτηκε όταν δεν ήταν δυνατή η εύρεση του συνημμένου. |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Περισσότερα σχετικά με τις διαφορετικές επιλογές προβολής ακολουθώντας αυτόν τον οδηγό: [Πώς να προσαρμόσετε την έξοδο προβολής εγγράφων χρησιμοποιώντας το GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Δείτε επίσης

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* χώρος ονομάτων [GroupDocs.Viewer](../../viewer)
* συνέλευση [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
