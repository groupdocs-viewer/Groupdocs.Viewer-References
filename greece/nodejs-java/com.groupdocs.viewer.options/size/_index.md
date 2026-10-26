---
title: "Size"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Περιέχει το μέγεθος του υδατογραφήματος."
type: docs
weight: 30
url: /el/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Περιέχει το μέγεθος του υδατογραφήματος.

Η κλάση Size αντιπροσωπεύει το μέγεθος ενός υδατογραφήματος στο στοιχείο GroupDocs.Viewer. Παρέχει επιλογές για τον καθορισμό των διαστάσεων του υδατογραφήματος, όπως το πλάτος και το ύψος.

Παράδειγμα χρήσης:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Size . |
## Fields

| Field | Περιγραφή |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | Αντιπροσωπεύει το μέγιστο μέγεθος του κειμένου του υδατογραφήματος που ταιριάζει στη σελίδα. |
| [HALF_SIZE](#HALF-SIZE) | Αντιπροσωπεύει τη μισή του μέγιστου μεγέθους του κειμένου του υδατογραφήματος που ταιριάζει στη σελίδα. |
| [ONE_THIRD](#ONE-THIRD) | Αντιπροσωπεύει το ένα τρίτο του μέγιστου μεγέθους του κειμένου του υδατογραφήματος που ταιριάζει στη σελίδα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | Επιστρέφει το μέγεθος του κειμένου του υδατογραφήματος σε ποσοστά σε σχέση με το πλάτος της σελίδας. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  Size .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| relativeSize | byte | Το μέγεθος σε ποσοστά σε σχέση με το μέγεθος της σελίδας. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Αντιπροσωπεύει το μέγιστο μέγεθος του κειμένου του υδατογραφήματος που ταιριάζει στη σελίδα.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Αντιπροσωπεύει τη μισή του μέγιστου μεγέθους του κειμένου του υδατογραφήματος που ταιριάζει στη σελίδα.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Αντιπροσωπεύει το ένα τρίτο του μέγιστου μεγέθους του κειμένου του υδατογραφήματος που ταιριάζει στη σελίδα.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Επιστρέφει το μέγεθος του κειμένου του υδατογραφήματος σε ποσοστά σε σχέση με το πλάτος της σελίδας.

**Returns:**
byte - το μέγεθος του κειμένου του υδατογραφήματος σε ποσοστά.
