---
title: "PageSize"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Το μέγεθος της σελίδας."
type: docs
weight: 42
url: /el/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

Το μέγεθος της σελίδας.

Το enum PageSize αντιπροσωπεύει διαφορετικά μεγέθη σελίδας στο στοιχείο GroupDocs.Viewer. Παρέχει ένα σύνολο προκαθορισμένων μεγεθών σελίδας που μπορούν να χρησιμοποιηθούν για τον καθορισμό των διαστάσεων μιας σελίδας σε διάφορα σενάρια απόδοσης εγγράφων.

Παράδειγμα χρήσης:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Περιγραφή |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Το προεπιλεγμένο, ακαθόριστο μέγεθος σελίδας. |
| [LETTER](#LETTER) | Το μέγεθος της σελίδας Letter σε σημεία είναι 792 x 612. |
| [LEDGER](#LEDGER) | Το μέγεθος της σελίδας A0 σε σημεία είναι 3371 x 2384. |
| [A0](#A0) | Το μέγεθος της σελίδας A1 σε σημεία είναι 2384 x 1685. |
| [A1](#A1) | Το μέγεθος της σελίδας A2 σε σημεία είναι 1684 x 1190. |
| [A2](#A2) | Το μέγεθος της σελίδας A3 σε σημεία είναι 1190 x 842. |
| [A3](#A3) | Το μέγεθος της σελίδας A3 σε σημεία είναι 1190 x 842. |
| [A4](#A4) | Το μέγεθος της σελίδας A4 σε σημεία είναι 842 x 595. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


Το προεπιλεγμένο, ακαθόριστο μέγεθος σελίδας. Αυτό το μέγεθος χρησιμοποιείται όταν δεν έχει καθοριστεί συγκεκριμένο μέγεθος σελίδας.

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Το μέγεθος της σελίδας Letter σε σημεία είναι 792 x 612. Αυτό το μέγεθος σελίδας χρησιμοποιείται συνήθως για επιστολές και έγγραφα στη Βόρεια Αμερική.

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


Το μέγεθος της σελίδας A0 σε σημεία είναι 3371 x 2384. Αυτό το μεγάλο μέγεθος σελίδας αποτελεί μέρος του διεθνούς προτύπου ISO 216.

### A0 {#A0}
```
public static final PageSize A0
```


Το μέγεθος της σελίδας A1 σε σημεία είναι 2384 x 1685. Αυτό το μέγεθος σελίδας αποτελεί μέρος του διεθνούς προτύπου ISO 216.

### A1 {#A1}
```
public static final PageSize A1
```


Το μέγεθος της σελίδας A2 σε σημεία είναι 1684 x 1190. Αυτό το μέγεθος σελίδας αποτελεί μέρος του διεθνούς προτύπου ISO 216.

### A2 {#A2}
```
public static final PageSize A2
```


Το μέγεθος της σελίδας A3 σε σημεία είναι 1190 x 842. Αυτό το μέγεθος σελίδας αποτελεί μέρος του διεθνούς προτύπου ISO 216.

### A3 {#A3}
```
public static final PageSize A3
```


Το μέγεθος της σελίδας A3 σε σημεία είναι 1190 x 842. Αυτό το μέγεθος σελίδας αποτελεί μέρος του διεθνούς προτύπου ISO 216.

### A4 {#A4}
```
public static final PageSize A4
```


Το μέγεθος της σελίδας A4 σε σημεία είναι 842 x 595. Αυτό το μέγεθος σελίδας αποτελεί μέρος του διεθνούς προτύπου ISO 216.

### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
