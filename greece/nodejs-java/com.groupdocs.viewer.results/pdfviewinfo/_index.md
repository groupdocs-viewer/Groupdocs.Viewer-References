---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει πληροφορίες προβολής για ένα έγγραφο PDF."
type: docs
weight: 22
url: /el/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Αντιπροσωπεύει πληροφορίες προβολής για ένα έγγραφο PDF.

Η διεπαφή PdfViewInfo ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση πληροφοριών προβολής για ένα έγγραφο PDF στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για ανάκτηση πληροφοριών όπως η δυνατότητα εκτύπωσης και άλλες ιδιότητες.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | Ελέγχει αν επιτρέπεται η εκτύπωση του εγγράφου. |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Ορίζει αν επιτρέπεται η εκτύπωση του εγγράφου. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Ελέγχει αν επιτρέπεται η εκτύπωση του εγγράφου.

**Returns:**
boolean -  true  αν επιτρέπεται η εκτύπωση,  false  διαφορετικά.
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Ορίζει αν επιτρέπεται η εκτύπωση του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| allowPrinting | boolean | true  για να επιτρέψετε την εκτύπωση,  false  διαφορετικά. |

