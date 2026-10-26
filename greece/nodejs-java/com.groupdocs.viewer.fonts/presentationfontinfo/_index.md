---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Περιλαμβάνει μεταδεδομένα και δυαδικά δεδομένα μιας γραμματοσειράς που χρησιμοποιείται σε έγγραφο Presentation που φορτώθηκε στην παρουσίαση Viewer."
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Περιλαμβάνει μεταδεδομένα και δυαδικά δεδομένα μιας γραμματοσειράς που χρησιμοποιείται σε έγγραφο Presentation, φορτωμένο στην παρουσίαση Viewer. Αυτή η γραμματοσειρά χρησιμοποιείται στο περιεχόμενο του εγγράφου και μπορεί να είναι ενσωματωμένη μέσα στο ίδιο το έγγραφο ή εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Λαμβάνει το όνομα οικογένειας της γραμματοσειράς (ποτέ μη μηδενικό ή κενό). |
| [getStyle()](#getStyle--) | Λαμβάνει το στυλ της γραμματοσειράς: Regular, Bold, Italic ή BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Δείχνει εάν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο που φορτώθηκε στην παρουσίαση Viewer. |
| [getFormat()](#getFormat--) | Λαμβάνει τη μορφή της γραμματοσειράς (TrueType, OpenType κ.λπ.). |
| [getContent()](#getContent--) | Λαμβάνει το δυαδικό περιεχόμενο της γραμματοσειράς, ή null εάν τα δεδομένα της γραμματοσειράς δεν είναι διαθέσιμα. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς σε κανόνα CSS @font-face χρησιμοποιώντας τον καθορισμένο writer. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Λαμβάνει το όνομα οικογένειας της γραμματοσειράς (ποτέ μη μηδενικό ή κενό).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Λαμβάνει το στυλ της γραμματοσειράς: Regular, Bold, Italic ή BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Δείχνει εάν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο που φορτώθηκε στην παρουσίαση Viewer. Σημείωση: Τα έγγραφα Spreadsheet δεν μπορούν να περιέχουν ενσωματωμένες γραμματοσειρές, επομένως για αυτά πάντα επιστρέφει false.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Λαμβάνει τη μορφή της γραμματοσειράς (TrueType, OpenType κ.λπ.). Εάν διατίθενται μόνο μεταδεδομένα, επιστρέφει FontFormat.Unknown.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Λαμβάνει το δυαδικό περιεχόμενο της γραμματοσειράς, ή null εάν τα δεδομένα της γραμματοσειράς δεν είναι διαθέσιμα.

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς σε κανόνα CSS @font-face χρησιμοποιώντας τον καθορισμένο writer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έξοδος | java.io.Writer | συγγραφέας για εγγραφή CSS (δεν πρέπει να είναι null) |

