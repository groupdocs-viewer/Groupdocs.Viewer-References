---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου."
type: docs
weight: 38
url: /el/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου.

Η κλάση WordProcessingOptions παρέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου στο στοιχείο GroupDocs.Viewer. Συγκεντρώνει ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της διαδικασίας απόδοσης και της μορφής εξόδου για αρχεία επεξεργασίας κειμένου. Για λεπτομέρειες, δείτε την [documentation][].

Παράδειγμα χρήσης:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | Αρχικοποιεί μια νέα παρουσία της  WordProcessingOptions  κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPageSize()](#getPageSize--) | Ανακτά το μέγεθος σελίδας για την απόδοση αρχείων HTM και HTML. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Ορίζει το μέγεθος σελίδας για την απόδοση αρχείων HTM και HTML. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Δείχνει αν η απόδοση παρακολουθούμενων αλλαγών (αναθεωρήσεων) είναι ενεργοποιημένη. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Ορίζει αν η απόδοση παρακολουθούμενων αλλαγών (αναθεωρήσεων) είναι ενεργοποιημένη. |
| [getLeftMargin()](#getLeftMargin--) | Ανακτά το αριστερό περιθώριο σελίδας για την απόδοση HTML. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Ορίζει το αριστερό περιθώριο σελίδας για την απόδοση HTML. |
| [getRightMargin()](#getRightMargin--) | Ανακτά το δεξί περιθώριο σελίδας για την απόδοση HTML. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Ορίζει το δεξί περιθώριο σελίδας για την απόδοση HTML. |
| [getTopMargin()](#getTopMargin--) | Ανακτά το επάνω περιθώριο σελίδας για την απόδοση HTML. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Ορίζει το επάνω περιθώριο σελίδας για την απόδοση HTML. |
| [getBottomMargin()](#getBottomMargin--) | Κάτω περιθώριο σελίδας (μόνο για απόδοση HTML) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Ορίζει το κάτω περιθώριο σελίδας για την απόδοση HTML. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Αυτή η επιλογή ενεργοποιεί το κερνίδωμα και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών γραφών, λατινικών ή κυριλλικών γραφών. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Αυτή η επιλογή ενεργοποιεί το κερνίδωμα και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών γραφών, λατινικών ή κυριλλικών γραφών. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Δείχνει εάν η πλοήγηση στον πίνακα περιεχομένων πρέπει να απενεργοποιηθεί κατά την απόδοση σε HTML ή PDF. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Ορίζει εάν η πλοήγηση στον πίνακα περιεχομένων πρέπει να απενεργοποιηθεί κατά την απόδοση σε HTML ή PDF. |
| [isUpdateFields()](#isUpdateFields--) | Λαμβάνει μια τιμή που καθορίζει εάν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισερχόμενου εγγράφου WordProcessing σε μορφές εξόδου HTML, PDF, PNG ή JPEG. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Ορίζει μια τιμή που καθορίζει εάν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισερχόμενου εγγράφου WordProcessing σε μορφές εξόδου HTML, PDF, PNG ή JPEG. |
| [equals(Object o)](#equals-java.lang.Object-) | Ελέγξτε εάν οι επιλογές έχουν αλλάξει. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης WordProcessingOptions. Περιέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Ανακτά το μέγεθος σελίδας για την απόδοση αρχείων HTM και HTML.

Κατά τη χρήση του προεπιλεγμένου μεγέθους σελίδας, ορισμένο περιεχόμενο μπορεί να μην χωράει στο πλαίσιο της σελίδας. Για να ταιριάξουν τα περιεχόμενα, μπορείτε να ορίσετε μεγαλύτερο μέγεθος σελίδας, όπως το A3, χρησιμοποιώντας το [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Ορίζει το μέγεθος σελίδας για την απόδοση αρχείων HTM και HTML.

Κατά τη χρήση του προεπιλεγμένου μεγέθους σελίδας, ορισμένο περιεχόμενο μπορεί να μην χωράει στο πλαίσιο της σελίδας. Για να ταιριάξουν τα περιεχόμενα, μπορείτε να ορίσετε μεγαλύτερο μέγεθος σελίδας, όπως το A3, χρησιμοποιώντας το [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Το μέγεθος της σελίδας εξόδου. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Δείχνει αν η απόδοση παρακολουθούμενων αλλαγών (αναθεωρήσεων) είναι ενεργοποιημένη.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean -  true  εάν η απόδοση των παρακολουθούμενων αλλαγών είναι ενεργοποιημένη,  false  διαφορετικά.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Ορίζει αν η απόδοση παρακολουθούμενων αλλαγών (αναθεωρήσεων) είναι ενεργοποιημένη.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση της απόδοσης παρακολουθούμενων αλλαγών,  false  για απενεργοποίησή της. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Ανακτά το αριστερό περιθώριο σελίδας για την απόδοση HTML.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - η τιμή του αριστερού περιθωρίου σελίδας.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Ορίζει το αριστερό περιθώριο σελίδας για την απόδοση HTML.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| leftMargin | java.lang.Double | Η τιμή του αριστερού περιθωρίου σελίδας που θα οριστεί. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Ανακτά το δεξί περιθώριο σελίδας για την απόδοση HTML.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - η τιμή του δεξιού περιθωρίου σελίδας.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Ορίζει το δεξί περιθώριο σελίδας για την απόδοση HTML.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rightMargin | java.lang.Double | Η τιμή του δεξιού περιθωρίου σελίδας που θα οριστεί. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Ανακτά το επάνω περιθώριο σελίδας για την απόδοση HTML.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - το επάνω περιθώριο σελίδας.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Ορίζει το επάνω περιθώριο σελίδας για την απόδοση HTML.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| topMargin | java.lang.Double | Το επάνω περιθώριο σελίδας που θα οριστεί. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Κάτω περιθώριο σελίδας (μόνο για απόδοση HTML)

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - το κάτω περιθώριο σελίδας.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Ορίζει το κάτω περιθώριο σελίδας για την απόδοση HTML.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bottomMargin | java.lang.Double | Το κάτω περιθώριο σελίδας που θα οριστεί. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Αυτή η επιλογή ενεργοποιεί το κερνίδωμα και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών γραφών, λατινικών ή κυριλλικών γραφών.

**Returns:**
boolean - True εάν οι λειτουργίες OpenType είναι ενεργοποιημένες, false διαφορετικά.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Αυτή η επιλογή ενεργοποιεί το κερνίδωμα και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών γραφών, λατινικών ή κυριλλικών γραφών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | Αληθές για ενεργοποίηση των χαρακτηριστικών OpenType, ψευδές διαφορετικά. |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Δείχνει αν η πλοήγηση του πίνακα περιεχομένων πρέπει να απενεργοποιηθεί κατά την απόδοση σε HTML ή PDF. Όταν αυτή η επιλογή οριστεί σε αληθές, για απόδοση HTML, οι σχετικοί σύνδεσμοι από τον πίνακα περιεχομένων θα αντικατασταθούν με ετικέτες span, αφαιρώντας τη λειτουργικότητα αλλά διατηρώντας την οπτική εμφάνιση. Για απόδοση PDF, ο πίνακας περιεχομένων θα αποδοθεί ως απλό κείμενο χωρίς συνδέσμους.

**Returns:**
boolean - Αληθές εάν η πλοήγηση του πίνακα περιεχομένων είναι απενεργοποιημένη· διαφορετικά, ψευδές.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Ορίζει αν η πλοήγηση του πίνακα περιεχομένων πρέπει να απενεργοποιηθεί κατά την απόδοση σε HTML ή PDF. Όταν αυτή η επιλογή οριστεί σε αληθές, για απόδοση HTML, οι σχετικοί σύνδεσμοι από τον πίνακα περιεχομένων θα αντικατασταθούν με ετικέτες span, αφαιρώντας τη λειτουργικότητα αλλά διατηρώντας την οπτική εμφάνιση. Για απόδοση PDF, ο πίνακας περιεχομένων θα αποδοθεί ως απλό κείμενο χωρίς συνδέσμους.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unlinkTableOfContents | boolean | Δείχνει αν η πλοήγηση του πίνακα περιεχομένων πρέπει να απενεργοποιηθεί. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Λαμβάνει μια τιμή που καθορίζει αν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισερχόμενου εγγράφου WordProcessing στα μορφότυπα εξόδου HTML, PDF, PNG ή JPEG. Η προεπιλεγμένη τιμή για αυτήν την ιδιότητα είναι αληθής \u2014 τα πεδία θα ενημερωθούν πριν από την αποθήκευση.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Ορίζει μια τιμή που καθορίζει αν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισερχόμενου εγγράφου WordProcessing στα μορφότυπα εξόδου HTML, PDF, PNG ή JPEG. Η προεπιλεγμένη τιμή για αυτήν την ιδιότητα είναι αληθής \u2014 τα πεδία θα ενημερωθούν πριν από την αποθήκευση.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Ελέγξτε εάν οι επιλογές έχουν αλλάξει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| o | java.lang.Object | Το αντικείμενο για σύγκριση ισότητας. |

**Returns:**
boolean -  αληθές  εάν οι επιλογές είναι ίσες με το καθορισμένο αντικείμενο,  ψευδές  διαφορετικά.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Υπολογίζει την τιμή του κώδικα κατακερματισμού για αυτό το αντικείμενο. Ο κώδικας κατακερματισμού βασίζεται στην εσωτερική κατάσταση του αντικειμένου και χρησιμοποιείται σε δομές δεδομένων βάσει κατακερματισμού όπως οι hash maps και τα hash sets.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - η τιμή του κώδικα κατακερματισμού για αυτό το αντικείμενο.
