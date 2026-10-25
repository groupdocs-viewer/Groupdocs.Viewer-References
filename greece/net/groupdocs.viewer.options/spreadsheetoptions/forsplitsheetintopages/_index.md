---
title: "ForSplitSheetIntoPages"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αρχικοποιεί μια παρουσία της κλάσης SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions για απόδοση φύλλου σε σελίδες."
type: docs
weight: 50
url: /el/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

Αρχικοποιεί μια παρουσία της κλάσης [`SpreadsheetOptions`](../../spreadsheetoptions) για απόδοση φύλλου σε σελίδες.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| countRowsPerPage | Int32 | Αριθμός γραμμών που θα συμπεριληφθούν σε κάθε σελίδα. |

### Τιμή Επιστροφής

Νέα παρουσία της [`SpreadsheetOptions`](../../spreadsheetoptions) για απόδοση φύλλου σε σελίδες.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *countRowsPerPage* είναι ίσο ή μικρότερο του μηδενός. |

### Παρατηρήσεις

Για λεπτομέρειες, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).

### Δείτε επίσης

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

Αρχικοποιεί μια παρουσία της κλάσης [`SpreadsheetOptions`](../../spreadsheetoptions) για απόδοση φύλλου σε σελίδες.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| countRowsPerPage | Int32 | Αριθμός γραμμών που θα συμπεριληφθούν σε κάθε σελίδα. |
| countColumnsPerPage | Int32 | Αριθμός στηλών που θα συμπεριληφθούν σε κάθε σελίδα. |

### Τιμή Επιστροφής

Νέα παρουσία της [`SpreadsheetOptions`](../../spreadsheetoptions) για απόδοση φύλλου σε σελίδες.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *countRowsPerPage* είναι ίσο ή μικρότερο του μηδενός. |
| ArgumentException | Εκτοπίζεται όταν το *countColumnsPerPage* είναι ίσο ή μικρότερο του μηδενός. |

### Παρατηρήσεις

Για λεπτομέρειες, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).

### Δείτε επίσης

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
