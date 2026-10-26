---
title: "TextOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Επιλογές διαίρεσης αρχείων κειμένου σε σελίδες."
type: docs
weight: 32
url: /el/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Επιλογές διαίρεσης αρχείων κειμένου σε σελίδες.

Η κλάση TextOptions παρέχει επιλογές για τη διαίρεση αρχείων κειμένου σε σελίδες στο στοιχείο GroupDocs.Viewer. Σας επιτρέπει να ελέγχετε πώς τα αρχεία κειμένου διαχωρίζονται σε μεμονωμένες σελίδες για σκοπούς απόδοσης και προβολής.

Παράδειγμα χρήσης:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextOptions()](#TextOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  TextOptions . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Λαμβάνει τον μέγιστο αριθμό χαρακτήρων ανά γραμμή σε μια σελίδα. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Ορίζει τον μέγιστο αριθμό χαρακτήρων ανά γραμμή σε μια σελίδα. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Λαμβάνει τον μέγιστο αριθμό γραμμών ανά σελίδα. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Ορίζει τον μέγιστο αριθμό γραμμών ανά σελίδα. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  TextOptions .

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Λαμβάνει τον μέγιστο αριθμό χαρακτήρων ανά γραμμή σε μια σελίδα.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - ο μέγιστος αριθμός χαρακτήρων ανά γραμμή σε μια σελίδα.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Ορίζει τον μέγιστο αριθμό χαρακτήρων ανά γραμμή σε μια σελίδα.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxCharsPerRow | int | Ο μέγιστος αριθμός χαρακτήρων ανά γραμμή σε μια σελίδα. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Λαμβάνει τον μέγιστο αριθμό γραμμών ανά σελίδα.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - ο μέγιστος αριθμός γραμμών.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Ορίζει τον μέγιστο αριθμό γραμμών ανά σελίδα.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxRowsPerPage | int | Ο μέγιστος αριθμός γραμμών. |

