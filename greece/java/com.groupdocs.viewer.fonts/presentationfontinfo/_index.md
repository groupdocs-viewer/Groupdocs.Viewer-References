---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Περιλαμβάνει μεταδεδομένα και δυαδικά δεδομένα μιας γραμματοσειράς που χρησιμοποιείται σε έγγραφο Presentation που φορτώνεται στην παρουσία Viewer."
type: docs
weight: 15
url: /el/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Περιλαμβάνει μεταδεδομένα και δυαδικά δεδομένα μιας γραμματοσειράς που χρησιμοποιείται σε έγγραφο Presentation, φορτωμένο στην παρουσία Viewer. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και μπορεί να είναι ενσωματωμένη μέσα στο ίδιο το έγγραφο ή εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Αποκτά το όνομα οικογένειας της γραμματοσειράς (ποτέ μη μηδενικό ή κενό). |
|
|  | [getStyle()](#getStyle--) | Αποκτά το στυλ της γραμματοσειράς: Regular, Bold, Italic ή BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Δείχνει αν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο που φορτώνεται στην παρουσία Viewer. |
|
|  | [getFormat()](#getFormat--) | Αποκτά τη μορφή της γραμματοσειράς (TrueType, OpenType κ.λπ.). |
|
|  | [getContent()](#getContent--) | Αποκτά το δυαδικό περιεχόμενο της γραμματοσειράς, ή null εάν τα δεδομένα της γραμματοσειράς δεν είναι διαθέσιμα. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Σειριοποιεί τις πληροφορίες αυτής της γραμματοσειράς σε κανόνα CSS @font-face χρησιμοποιώντας τον καθορισμένο writer. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Αποκτά το όνομα οικογένειας της γραμματοσειράς (ποτέ μη μηδενικό ή κενό).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Αποκτά το στυλ της γραμματοσειράς: Regular, Bold, Italic ή BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Δείχνει αν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο που φορτώνεται στην παρουσία Viewer. Σημείωση: Τα έγγραφα Spreadsheet δεν μπορούν να περιέχουν ενσωματωμένες γραμματοσειρές, έτσι για αυτά πάντα επιστρέφει false.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Αποκτά τη μορφή της γραμματοσειράς (TrueType, OpenType κ.λπ.). Εάν είναι διαθέσιμα μόνο μεταδεδομένα, επιστρέφει FontFormat.Unknown.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Αποκτά το δυαδικό περιεχόμενο της γραμματοσειράς, ή null εάν τα δεδομένα της γραμματοσειράς δεν είναι διαθέσιμα.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Σειριοποιεί τις πληροφορίες αυτής της γραμματοσειράς σε κανόνα CSS @font-face χρησιμοποιώντας τον καθορισμένο writer.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | output | java.io.Writer | writer για τη γραφή του CSS (δεν πρέπει να είναι null) |
|

