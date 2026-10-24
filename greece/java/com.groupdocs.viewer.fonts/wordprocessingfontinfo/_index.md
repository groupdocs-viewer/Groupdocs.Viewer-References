---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο WordProcessing που φορτώθηκε στην παρουσία Viewer."
type: docs
weight: 17
url: /el/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο WordProcessing, που φορτώθηκε στην παρουσία Viewer. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι ενσωματωμένη μέσα στο ίδιο το έγγραφο ή είναι εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer.

Αμετάβλητη κλάση. Οι στιγμές της παράγονται και επιστρέφονται από το GroupDocs.Viewer.
δημόσιο API και κανονικά δεν πρέπει να δημιουργείται από τον χρήστη.
Για λεπτομέρειες, δείτε την τεκμηρίωση:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ μη μηδενικό ή κενό. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | Εναλλακτικό όνομα οικογένειας της γραμματοσειράς. |
|
|  | [getStyle()](#getStyle--) | Στυλ της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Δείχνει αν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο (true) ή είναι γραμματοσειρά συστήματος (false). |
|
|  | [getFormat()](#getFormat--) | Μορφή αυτής της γραμματοσειράς. |
|
|  | [getContent()](#getContent--) | Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte, ή null εάν δεν είναι διαθέσιμο. |
|
|  | [getCharset()](#getCharset--) | Σύνολο χαρακτήρων αυτής της γραμματοσειράς. |
|
|  | [toString()](#toString--) | Επιστρέφει πληροφορίες αποσφαλμάτωσης για αυτή τη γραμματοσειρά στο ακόλουθο πρότυπο: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Σειριοποιεί τις πληροφορίες αυτής της γραμματοσειράς ως κανόνα CSS @font-face και τις γράφει στον καθορισμένο writer. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ μη μηδενικό ή κενό.


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Εναλλακτικό όνομα οικογένειας της γραμματοσειράς. Εάν λείπει, επιστρέφει κενή συμβολοσειρά.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Στυλ της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Δείχνει αν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο (true) ή είναι γραμματοσειρά συστήματος (false).


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Μορφή αυτής της γραμματοσειράς. Εάν υπάρχουν μόνο μεταπληροφορίες και λείπουν τα δυαδικά δεδομένα, μπορεί να επιστρέψει FontFormat.UNKNOWN.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte, ή null εάν δεν είναι διαθέσιμο.


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Σύνολο χαρακτήρων αυτής της γραμματοσειράς.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει πληροφορίες αποσφαλμάτωσης για αυτή τη γραμματοσειρά στο ακόλουθο πρότυπο: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Σειριοποιεί τις πληροφορίες αυτής της γραμματοσειράς ως κανόνα CSS @font-face και τις γράφει στον καθορισμένο writer.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | output | java.io.Writer | Writer για τη λήψη του σειριοποιημένου CSS. |
|

