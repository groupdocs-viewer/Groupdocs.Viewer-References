---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Περιέχει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από ένα PDF έγγραφο που φορτώθηκε στην παρουσία Viewer."
type: docs
weight: 14
url: /el/java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από έγγραφο PDF, που φορτώθηκε στο αντίγραφο Viewer.


Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι είτε:

* embedded inside the PDF document
* or installed in the operating system where GroupDocs.Viewer is running

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Εσωτερικός κατασκευαστής που χρησιμοποιείται από την εξαγωγή γραμματοσειρών PDF. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Λαμβάνει το όνομα οικογένειας γραμματοσειράς. |
|
|  | [getStyle()](#getStyle--) | Λαμβάνει το στυλ αυτής της γραμματοσειράς. |
|
|  | [isEmbedded()](#isEmbedded--) | Επιστρέφει αν η γραμματοσειρά είναι ενσωματωμένη μέσα στο PDF έγγραφο. |
|
|  | [isInstalled()](#isInstalled--) | Επιστρέφει αν η γραμματοσειρά είναι εγκατεστημένη στο λειτουργικό σύστημα. |
|
|  | [getFormat()](#getFormat--) | Επιστρέφει τη μορφή αρχείου της γραμματοσειράς. |
|
|  | [getContent()](#getContent--) | Επιστρέφει το δυαδικό περιεχόμενο της γραμματοσειράς. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Σειριοποιεί αυτή τη γραμματοσειρά ως κανόνα CSS @font-face. |
|
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Εσωτερικός κατασκευαστής που χρησιμοποιείται από την εξαγωγή γραμματοσειρών PDF.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | familyName | java.lang.String | όνομα οικογένειας γραμματοσειράς |
|
|  | στυλ | com.groupdocs.viewer.fonts.FontStyles | στυλ (Regular, Bold, Italic, BoldItalic) |
|
|  | isEmbedded | boolean | αληθές εάν η γραμματοσειρά είναι ενσωματωμένη στο PDF |
|
|  | isInstalled | boolean | αληθές εάν η γραμματοσειρά είναι εγκατεστημένη στο λειτουργικό σύστημα |
|
|  | content | byte[] | δυαδικά δεδομένα γραμματοσειράς (nullable) |
|
|  | μορφή | int | μορφή αρχείου γραμματοσειράς |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Λαμβάνει το όνομα οικογένειας γραμματοσειράς.


**Returns:**
java.lang.String - συμβολοσειρά ονόματος οικογένειας (ποτέ δεν είναι null ή κενή)

### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Λαμβάνει το στυλ αυτής της γραμματοσειράς.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles - το στυλ της γραμματοσειράς

### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Επιστρέφει αν η γραμματοσειρά είναι ενσωματωμένη μέσα στο PDF έγγραφο.


**Returns:**
boolean - αληθές εάν ενσωματωμένο

### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Επιστρέφει αν η γραμματοσειρά είναι εγκατεστημένη στο λειτουργικό σύστημα.


**Returns:**
boolean - αληθές εάν εγκατεστημένο

### getFormat() {#getFormat--}
```
public int getFormat()
```


Επιστρέφει τη μορφή αρχείου της γραμματοσειράς.


**Returns:**
int - η enum μορφής γραμματοσειράς

### getContent() {#getContent--}
```
public byte[] getContent()
```


Επιστρέφει το δυαδικό περιεχόμενο της γραμματοσειράς.


**Returns:**
byte[] - πίνακας byte ή null εάν δεν είναι διαθέσιμο

### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Σειριοποιεί αυτή τη γραμματοσειρά ως κανόνα CSS @font-face.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | output | java.io.Writer | ο writer στον οποίο θα γραφτεί το CSS |
|

