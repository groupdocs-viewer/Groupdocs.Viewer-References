---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο WordProcessing που φορτώθηκε στην παρουσία Viewer."
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο WordProcessing, που φορτώθηκε στην παρουσίαση Viewer. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και είναι ενσωματωμένη μέσα στο ίδιο το έγγραφο ή είναι εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer.

Αμετάβλητη κλάση. Τα στιγμιότυπά της παράγονται και επιστρέφονται από το δημόσιο API του GroupDocs.Viewer και κανονικά δεν πρέπει να δημιουργούνται από τον χρήστη. Για λεπτομέρειες, δείτε την τεκμηρίωση: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ μη μηδενικό ή κενό. |
| [getAltFamilyName()](#getAltFamilyName--) | Εναλλακτικό όνομα οικογένειας της γραμματοσειράς. |
| [getStyle()](#getStyle--) | Στυλ της γραμματοσειράς \u2014 μπορεί να είναι Regular, Bold, Italic ή BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Δείχνει εάν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο (true) ή είναι γραμματοσειρά συστήματος (false). |
| [getFormat()](#getFormat--) | Μορφή αυτής της γραμματοσειράς. |
| [getContent()](#getContent--) | Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte, ή null εάν δεν είναι διαθέσιμο. |
| [getCharset()](#getCharset--) | Σύνολο χαρακτήρων αυτής της γραμματοσειράς. |
| [toString()](#toString--) | Επιστρέφει πληροφορίες αποσφαλμάτωσης για αυτή τη γραμματοσειρά στο ακόλουθο πρότυπο: "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα CSS @font-face και τις γράφει στον καθορισμένο writer. |
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


Στυλ της γραμματοσειράς \u2014 μπορεί να είναι Regular, Bold, Italic ή BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Δείχνει εάν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο (true) ή είναι γραμματοσειρά συστήματος (false).

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Μορφή αυτής της γραμματοσειράς. Εάν υπάρχουν μόνο μεταπληροφορίες και λείπει το δυαδικό περιεχόμενο, μπορεί να επιστρέψει FontFormat.UNKNOWN.

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


Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα CSS @font-face και τις γράφει στον καθορισμένο writer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έξοδος | java.io.Writer | Writer για τη λήψη του σειριοποιημένου CSS. |

