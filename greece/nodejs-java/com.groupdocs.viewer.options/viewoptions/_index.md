---
title: "ViewOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Περιέχει τις επιλογές απόδοσης."
type: docs
weight: 35
url: /el/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Περιέχει τις επιλογές απόδοσης.

Η κλάση ViewOptions επεκτείνει την κλάση BaseViewOptions και λειτουργεί ως βασική κλάση για τις επιλογές απόδοσης στο στοιχείο GroupDocs.Viewer. Συγκεντρώνει κοινές ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για την απόδοση διαφόρων τύπων εγγράφων σε διαφορετικές μορφές.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWatermark()](#getWatermark--) | Αποκτά το κείμενο υδατογράφημα που εφαρμόζεται σε κάθε σελίδα. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Ορίζει το κείμενο υδατογράφημα που θα εφαρμόζεται σε κάθε σελίδα. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Εφαρμόζει μια δεξιόστροφη περιστροφή στη συγκεκριμένη σελίδα. |
| [getPageRotations()](#getPageRotations--) | Ανακτά τις περιστροφές των σελίδων. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Για να αποφευχθεί η δημιουργία του στιγμιότυπου μόνο για να ελεγχθεί αν είναι κενό |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Αποκτά το κείμενο υδατογράφημα που εφαρμόζεται σε κάθε σελίδα.

Σε περίπτωση που τόσο το \#setWatermark(Watermark).setWatermark(Watermark) όσο και το \#getPageRotations().getPageRotations() έχουν καθοριστεί, το υδατογράφημα θα εφαρμοστεί στις περιστραμμένες σελίδες. Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Ορίζει το κείμενο υδατογράφημα που θα εφαρμόζεται σε κάθε σελίδα.

Σε περίπτωση που τόσο το ViewOptions.Watermark όσο και το \#getPageRotations().getPageRotations() έχουν καθοριστεί, το υδατογράφημα θα εφαρμοστεί στις περιστραμμένες σελίδες. Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Το κείμενο υδατογράφημα που θα οριστεί. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Εφαρμόζει μια δεξιόστροφη περιστροφή στη συγκεκριμένη σελίδα.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageNumber | int | Ο αριθμός σελίδας πρέπει να είναι αυστηρά μεγαλύτερος από 0. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Η τιμή περιστροφής. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Ανακτά τις περιστροφές των σελίδων.

Εάν τόσο το [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) όσο και  getPageRotations()  καθοριστούν, το υδατογράφημα θα εφαρμοστεί στις περιστρεφόμενες σελίδες. Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - ένας χάρτης που περιέχει τους αριθμούς σελίδων ως κλειδιά και τις αντίστοιχες περιστροφές τους ως τιμές.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Για να αποφευχθεί η δημιουργία του στιγμιότυπου μόνο για να ελεγχθεί αν είναι κενό

**Returns:**
boolean
