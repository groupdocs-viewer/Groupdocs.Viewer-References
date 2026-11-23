---
title: "ImageQuality"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Η ποιότητα των εικόνων στο παραγόμενο HTML που περιέχεται στα έγγραφα PDF."
type: docs
weight: 41
url: /el/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

Η ποιότητα των εικόνων στο παραγόμενο HTML που περιέχεται στα έγγραφα PDF.

Το enum ImageQuality αντιπροσωπεύει την ποιότητα των εικόνων στο παραγόμενο HTML που περιέχεται στα έγγραφα PDF στο στοιχείο GroupDocs.Viewer. Παρέχει διαφορετικά επίπεδα ποιότητας εικόνας που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης και της συμπίεσης των εικόνων στην παραγόμενη έξοδο HTML.

Παράδειγμα χρήσης:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Περιγραφή |
| --- | --- |
| [LOW](#LOW) | Η αποδεκτή ποιότητα και η καλύτερη απόδοση. |
| [MEDIUM](#MEDIUM) | Καλύτερη ποιότητα και πιο αργή απόδοση. |
| [HIGH](#HIGH) | Η καλύτερη ποιότητα αλλά αργή απόδοση. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


Η αποδεκτή ποιότητα και η καλύτερη απόδοση. Αυτή η ρύθμιση δίνει προτεραιότητα στην ταχύτητα απόδοσης σε σχέση με την ποιότητα εικόνας.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Καλύτερη ποιότητα και πιο αργή απόδοση. Αυτή η ρύθμιση παρέχει μια ισορροπία μεταξύ ποιότητας εικόνας και ταχύτητας απόδοσης.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


Η καλύτερη ποιότητα αλλά αργή απόδοση. Αυτή η ρύθμιση δίνει προτεραιότητα στην ποιότητα εικόνας σε σχέση με την ταχύτητα απόδοσης.

### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
