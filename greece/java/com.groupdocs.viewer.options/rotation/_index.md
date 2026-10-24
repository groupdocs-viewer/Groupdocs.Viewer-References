---
title: "Rotation"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Περιέχει περιστροφή σελίδας σε μοίρες δεξιόστροφα."
type: docs
weight: 45
url: /el/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Περιέχει περιστροφή σελίδας σε μοίρες (δεξιόστροφα).


Το enum Rotation αντιπροσωπεύει διαφορετικές γωνίες περιστροφής για μια σελίδα στο στοιχείο GroupDocs.Viewer.
Παρέχει ένα σύνολο προκαθορισμένων επιλογών περιστροφής που μπορούν να χρησιμοποιηθούν για τον καθορισμό της γωνίας περιστροφής
για την απόδοση μιας σελίδας σε διάφορα σενάρια προβολής ή μετατροπής εγγράφων.


Παράδειγμα χρήσης:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | Η περιστροφή σελίδας 90 μοιρών. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | Η περιστροφή σελίδας 180 μοιρών. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | Η περιστροφή σελίδας 270 μοιρών. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


Η περιστροφή σελίδας 90 μοιρών.
Αυτή η περιστροφή αντιπροσωπεύει μια 90 μοίρες δεξιόστροφη περιστροφή της σελίδας.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


Η περιστροφή σελίδας 180 μοιρών.
Αυτή η περιστροφή αντιπροσωπεύει μια 180 μοίρες δεξιόστροφη περιστροφή της σελίδας.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


Η περιστροφή σελίδας 270 μοιρών.
Αυτή η περιστροφή αντιπροσωπεύει μια 270 μοίρες δεξιόστροφη περιστροφή της σελίδας.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
