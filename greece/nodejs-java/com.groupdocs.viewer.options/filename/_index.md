---
title: "FileName"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει το όνομα ενός αρχείου σε μια αρχειοθήκη."
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Αντιπροσωπεύει το όνομα ενός αρχείου σε μια αρχειοθήκη.

Η κλάση FileName περιλαμβάνει το όνομα ενός αρχείου χωρίς καμία πληροφορία διαδρομής ή καταλόγου. Παρέχει μεθόδους για τη διαχείριση και την ανάκτηση πληροφοριών σχετικά με το όνομα του αρχείου.

Παράδειγμα χρήσης:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της  FileName  κλάσης. |
## Fields

| Field | Περιγραφή |
| --- | --- |
| [EMPTY](#EMPTY) | Αντιπροσωπεύει ένα κενό όνομα αρχείου. |
| [SOURCE](#SOURCE) | Αντιπροσωπεύει το όνομα του αρχείου προέλευσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | Επιστρέφει μια αναπαράσταση σε συμβολοσειρά του τρέχοντος αντικειμένου. |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της  FileName  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το όνομα του αρχείου. |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Αντιπροσωπεύει ένα κενό όνομα αρχείου.

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Αντιπροσωπεύει το όνομα του αρχείου προέλευσης.

### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναπαράσταση σε συμβολοσειρά του τρέχοντος αντικειμένου.

**Returns:**
java.lang.String - μια αναπαράσταση σε συμβολοσειρά του τρέχοντος αντικειμένου.
