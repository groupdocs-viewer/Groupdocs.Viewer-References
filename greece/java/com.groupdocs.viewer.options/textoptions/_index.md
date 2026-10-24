---
title: "TextOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Επιλογές διαίρεσης αρχείων κειμένου σε σελίδες."
type: docs
weight: 32
url: /el/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Επιλογές διαίρεσης αρχείων κειμένου σε σελίδες.


Η κλάση TextOptions παρέχει επιλογές για τη διαίρεση αρχείων κειμένου σε σελίδες στο στοιχείο GroupDocs.Viewer.
Σας επιτρέπει να ελέγχετε πώς τα αρχεία κειμένου διαχωρίζονται σε μεμονωμένες σελίδες για σκοπούς απόδοσης και προβολής.


Παράδειγμα χρήσης:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | Αρχικοποιεί μια νέα παρουσία του |
TextOptions
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Ανακτά τον μέγιστο αριθμό χαρακτήρων ανά γραμμή σε μια σελίδα. |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Ορίζει τον μέγιστο αριθμό χαρακτήρων ανά γραμμή σε μια σελίδα. |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Ανακτά τον μέγιστο αριθμό γραμμών ανά σελίδα. |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Ορίζει τον μέγιστο αριθμό γραμμών ανά σελίδα. |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Αρχικοποιεί μια νέα παρουσία του
TextOptions
κλάσης.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Ανακτά τον μέγιστο αριθμό χαρακτήρων ανά γραμμή σε μια σελίδα.


***Note:** The default value is 85.*
Η προεπιλεγμένη τιμή είναι 85. Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - ο μέγιστος αριθμός χαρακτήρων ανά γραμμή σε μια σελίδα.

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Ορίζει τον μέγιστο αριθμό χαρακτήρων ανά γραμμή σε μια σελίδα.


***Note:** The default value is 85.*
Η προεπιλεγμένη τιμή είναι 85. Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxCharsPerRow | int | Ο μέγιστος αριθμός χαρακτήρων ανά γραμμή σε μια σελίδα. |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Ανακτά τον μέγιστο αριθμό γραμμών ανά σελίδα.


***Note:** The default value is 55.*
Η προεπιλεγμένη τιμή είναι 55. Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - ο μέγιστος αριθμός γραμμών.

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Ορίζει τον μέγιστο αριθμό γραμμών ανά σελίδα.


***Note:** The default value is 55.*
Η προεπιλεγμένη τιμή είναι 55. Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxRowsPerPage | int | Ο μέγιστος αριθμός γραμμών. |
|

