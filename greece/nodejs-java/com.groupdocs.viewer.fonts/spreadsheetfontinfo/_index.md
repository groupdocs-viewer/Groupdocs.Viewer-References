---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο Spreadsheet που φορτώθηκε στην παρουσία Viewer."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από το έγγραφο Spreadsheet, που φορτώθηκε στην παρουσία Viewer. Τα έγγραφα Spreadsheet δεν μπορούν να περιέχουν ενσωματωμένες γραμματοσειρές, έτσι αυτή η συγκεκριμένη γραμματοσειρά, εάν επιστραφεί από τη μέθοδο Viewer.getAllFonts(), είναι εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ μη μηδενικό ή κενό. |
| [getStyle()](#getStyle--) | Στυλ αυτής της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή BoldItalic. |
| [isStrikeout()](#isStrikeout--) | Δείχνει εάν η γραμματοσειρά έχει μία ενιαία διαγράμμιση. |
| [isUnderline()](#isUnderline--) | Δείχνει εάν η γραμματοσειρά έχει υπογράμμιση. |
| [getColor()](#getColor--) | Χρώμα αυτής της γραμματοσειράς. |
| [getCharset()](#getCharset--) | Σύνολο χαρακτήρων αυτής της γραμματοσειράς. |
| [getContent()](#getContent--) | Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte. |
| [getFormat()](#getFormat--) | Μορφή αυτής της γραμματοσειράς. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα @font-face και τις γράφει στον καθορισμένο συγγραφέα. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ μη μηδενικό ή κενό.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Στυλ αυτής της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Δείχνει εάν η γραμματοσειρά έχει μία ενιαία διαγράμμιση.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Δείχνει εάν η γραμματοσειρά έχει υπογράμμιση.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Χρώμα αυτής της γραμματοσειράς.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


Σύνολο χαρακτήρων αυτής της γραμματοσειράς.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte. Μπορεί να είναι null εάν διατίθενται μόνο μεταπληροφορίες.

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Μορφή αυτής της γραμματοσειράς.

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως κανόνα @font-face και τις γράφει στον καθορισμένο συγγραφέα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έξοδος | java.io.Writer | Συσκευή για εγγραφή σειριοποιημένων δεδομένων κειμένου. |

