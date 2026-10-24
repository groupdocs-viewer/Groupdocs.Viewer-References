---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει πληροφορίες προβολής για ένα έγγραφο PDF."
type: docs
weight: 24
url: /el/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Αντιπροσωπεύει πληροφορίες προβολής για ένα έγγραφο PDF.


Η διεπαφή PdfViewInfo ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση των πληροφοριών προβολής
για ένα έγγραφο PDF στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών
όπως η δυνατότητα εκτύπωσης και άλλες ιδιότητες.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | Ελέγχει αν η εκτύπωση του εγγράφου επιτρέπεται. |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Ορίζει αν η εκτύπωση του εγγράφου επιτρέπεται. |
|
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Ελέγχει αν η εκτύπωση του εγγράφου επιτρέπεται.


**Returns:**
boolean -  true  εάν η εκτύπωση επιτρέπεται,  false  διαφορετικά.

### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Ορίζει αν η εκτύπωση του εγγράφου επιτρέπεται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | allowPrinting | boolean | true  για να επιτραπεί η εκτύπωση,  false  διαφορετικά. |
|

