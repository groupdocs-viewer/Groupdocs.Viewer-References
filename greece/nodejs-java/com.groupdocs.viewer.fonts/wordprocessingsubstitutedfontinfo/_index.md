---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Περιλαμβάνει μεταδεδομένα και δυαδικά δεδομένα μιας αντικατεστημένης γραμματοσειράς που χρησιμοποιείται σε έγγραφο Επεξεργασίας Κειμένου μέσω του GroupDocs.Viewer."
type: docs
weight: 18
url: /el/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Περιλαμβάνει μεταδεδομένα και δυαδικά δεδομένα μιας αντικατεστημένης γραμματοσειράς που χρησιμοποιείται σε έγγραφο WordProcessing μέσω GroupDocs.Viewer. Αμετάβλητη κλάση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Κατασκευαστής για την αρχικοποίηση όλων των πεδίων. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Επιστρέφει το όνομα οικογένειας της αντικατεστημένης γραμματοσειράς (ποτέ null). |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | Επιστρέφει το όνομα οικογένειας της αρχικής γραμματοσειράς (ποτέ null). |
| [getStyle()](#getStyle--) | Επιστρέφει το στυλ της αρχικής γραμματοσειράς. |
| [getContent()](#getContent--) | Επιστρέφει το δυαδικό περιεχόμενο της αντικατεστημένης γραμματοσειράς (ποτέ null). |
| [getFormat()](#getFormat--) | Επιστρέφει τη μορφή γραμματοσειράς της αντικατεστημένης γραμματοσειράς. |
| [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που περιγράφει αυτήν την αντικατεστημένη γραμματοσειρά: "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | Ισότητα βάσει αρχικής οικογένειας, αντικατεστημένης οικογένειας και στυλ. |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Σειριοποιήστε αυτήν τη γραμματοσειρά ως κανόνα CSS @font-face χρησιμοποιώντας μια βοηθητική μέθοδο. |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Κατασκευαστής για την αρχικοποίηση όλων των πεδίων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| originalFamilyName | java.lang.String | Το όνομα της αρχικής γραμματοσειράς (δεν βρέθηκε στο σύστημα) |
| substitutedFamilyName | java.lang.String | Το όνομα της αντικατεστημένης γραμματοσειράς (διαθέσιμο) |
| στυλ | com.groupdocs.viewer.fonts.FontStyles | Στυλ γραμματοσειράς (Regular, Bold, Italic, BoldItalic) |
| περιεχόμενο | byte[] | Δυαδικό περιεχόμενο της αντικατεστημένης γραμματοσειράς (ποτέ null) |
| μορφή | int | Μορφή γραμματοσειράς (TrueType, OpenType, κ.λπ.) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Επιστρέφει το όνομα οικογένειας της αντικατεστημένης γραμματοσειράς (ποτέ null).

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Επιστρέφει το όνομα οικογένειας της αρχικής γραμματοσειράς (ποτέ null).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Επιστρέφει το στυλ της αρχικής γραμματοσειράς.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Επιστρέφει το δυαδικό περιεχόμενο της αντικατεστημένης γραμματοσειράς (ποτέ null).

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Επιστρέφει τη μορφή γραμματοσειράς της αντικατεστημένης γραμματοσειράς.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που περιγράφει αυτήν την αντικατεστημένη γραμματοσειρά: "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Ισότητα βάσει αρχικής οικογένειας, αντικατεστημένης οικογένειας και στυλ. Απαιτείται για χρήση σε HashSet ή HashMap όπως C\# IEqualityComparer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Σειριοποιήστε αυτήν τη γραμματοσειρά ως κανόνα CSS @font-face χρησιμοποιώντας μια βοηθητική μέθοδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έξοδος | java.io.Writer |  |

