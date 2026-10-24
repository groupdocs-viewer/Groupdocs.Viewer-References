---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου."
type: docs
weight: 38
url: /el/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου.


Η κλάση WordProcessingOptions παρέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου
στο στοιχείο GroupDocs.Viewer. Περιλαμβάνει ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν
για να ελέγχει τη διαδικασία απόδοσης και τη μορφή εξόδου για αρχεία επεξεργασίας κειμένου.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


Παράδειγμα χρήσης:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Αρχικοποιεί μια νέα παρουσία του |
WordProcessingOptions
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Ανακτά το μέγεθος σελίδας για την απόδοση αρχείων HTM και HTML. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Ορίζει το μέγεθος σελίδας για την απόδοση αρχείων HTM και HTML. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Δείχνει αν η απόδοση παρακολουθούμενων αλλαγών (αναθεωρήσεων) είναι ενεργοποιημένη. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Ορίζει αν η απόδοση παρακολουθούμενων αλλαγών (αναθεωρήσεων) είναι ενεργοποιημένη. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Ανακτά το αριστερό περιθώριο σελίδας για την απόδοση HTML. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Ορίζει το αριστερό περιθώριο σελίδας για την απόδοση HTML. |
|
|  | [getRightMargin()](#getRightMargin--) | Ανακτά το δεξί περιθώριο σελίδας για την απόδοση HTML. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Ορίζει το δεξί περιθώριο σελίδας για την απόδοση HTML. |
|
|  | [getTopMargin()](#getTopMargin--) | Ανακτά το επάνω περιθώριο σελίδας για την απόδοση HTML. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Ορίζει το επάνω περιθώριο σελίδας για την απόδοση HTML. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Κάτω περιθώριο σελίδας (μόνο για απόδοση HTML) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Ορίζει το κάτω περιθώριο σελίδας για την απόδοση HTML. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Αυτή η επιλογή ενεργοποιεί το kerning και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών γραφών, λατινικών ή κυριλλικών γραφών. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Αυτή η επιλογή ενεργοποιεί το kerning και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών γραφών, λατινικών ή κυριλλικών γραφών. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Δείχνει αν η πλοήγηση στον πίνακα περιεχομένων πρέπει να απενεργοποιηθεί κατά την απόδοση σε HTML ή PDF. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Ορίζει αν η πλοήγηση στον πίνακα περιεχομένων πρέπει να απενεργοποιηθεί κατά την απόδοση σε HTML ή PDF. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Ανακτά μια τιμή που καθορίζει αν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισαγόμενου εγγράφου WordProcessing σε μορφές εξόδου HTML, PDF, PNG ή JPEG. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Ορίζει μια τιμή που καθορίζει αν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισαγόμενου εγγράφου WordProcessing σε μορφές εξόδου HTML, PDF, PNG ή JPEG. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Ανακτά την οριζόντια ανάλυση για τις παραγόμενες εικόνες σε κουκκίδες ανά ίντσα. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Ορίζει την οριζόντια ανάλυση για τις παραγόμενες εικόνες σε κουκκίδες ανά ίντσα. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Ανακτά την κάθετη ανάλυση για τις παραγόμενες εικόνες σε κουκκίδες ανά ίντσα. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Ορίζει την κάθετη ανάλυση για τις παραγόμενες εικόνες σε κουκκίδες ανά ίντσα. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Επιτρέπει την εξαναγκαστική εφαρμογή αρίθμησης σελίδων για το φορτωμένο έγγραφο WordProcessing. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Επιτρέπει την εξαναγκαστική εφαρμογή αρίθμησης σελίδων για το φορτωμένο έγγραφο WordProcessing. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Ελέγξτε αν οι επιλογές έχουν αλλάξει. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Αρχικοποιεί μια νέα παρουσία του
WordProcessingOptions
κλάσης.
Περιέχει επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου. Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Ανακτά το μέγεθος σελίδας για την απόδοση αρχείων HTM και HTML.


Κατά τη χρήση του προεπιλεγμένου μεγέθους σελίδας, ορισμένο περιεχόμενο μπορεί να μην χωράει στο πλαίσιο της σελίδας.
Για να χωρέσει το περιεχόμενο, μπορείτε να ορίσετε μεγαλύτερο μέγεθος σελίδας, όπως το A3, χρησιμοποιώντας το [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Ορίζει το μέγεθος σελίδας για την απόδοση αρχείων HTM και HTML.


Κατά τη χρήση του προεπιλεγμένου μεγέθους σελίδας, ορισμένο περιεχόμενο μπορεί να μην χωράει στο πλαίσιο της σελίδας.
Για να χωρέσει το περιεχόμενο, μπορείτε να ορίσετε μεγαλύτερο μέγεθος σελίδας, όπως το A3, χρησιμοποιώντας το [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Το μέγεθος της εξόδου σελίδας. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Δείχνει αν η απόδοση παρακολουθούμενων αλλαγών (αναθεωρήσεων) είναι ενεργοποιημένη.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
boolean -  true  αν η απόδοση παρακολουθούμενων αλλαγών είναι ενεργοποιημένη,  false  διαφορετικά.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Ορίζει αν η απόδοση παρακολουθούμενων αλλαγών (αναθεωρήσεων) είναι ενεργοποιημένη.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  για ενεργοποίηση της απόδοσης παρακολουθούμενων αλλαγών,  false  για απενεργοποίησή της. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Ανακτά το αριστερό περιθώριο σελίδας για την απόδοση HTML.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - η τιμή του αριστερού περιθωρίου σελίδας.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Ορίζει το αριστερό περιθώριο σελίδας για την απόδοση HTML.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | Η τιμή του αριστερού περιθωρίου σελίδας προς ορισμό. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Ανακτά το δεξί περιθώριο σελίδας για την απόδοση HTML.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - η τιμή του δεξιού περιθωρίου σελίδας.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Ορίζει το δεξί περιθώριο σελίδας για την απόδοση HTML.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | Η τιμή του δεξιού περιθωρίου σελίδας για ορισμό. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Ανακτά το επάνω περιθώριο σελίδας για την απόδοση HTML.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - το επάνω περιθώριο σελίδας.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Ορίζει το επάνω περιθώριο σελίδας για την απόδοση HTML.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | topMargin | java.lang.Double | Το επάνω περιθώριο σελίδας για ορισμό. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Κάτω περιθώριο σελίδας (μόνο για απόδοση HTML)
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - το κάτω περιθώριο σελίδας.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Ορίζει το κάτω περιθώριο σελίδας για την απόδοση HTML.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | Το κάτω περιθώριο σελίδας για ορισμό. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Αυτή η επιλογή ενεργοποιεί το kerning και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών γραφών, λατινικών ή κυριλλικών γραφών.


**Returns:**
boolean - Αληθές εάν οι δυνατότητες OpenType είναι ενεργοποιημένες, ψευδές διαφορετικά.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Αυτή η επιλογή ενεργοποιεί το kerning και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, ινδικών γραφών, λατινικών ή κυριλλικών γραφών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | Αληθές για ενεργοποίηση των δυνατότητων OpenType, ψευδές διαφορετικά. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Υποδεικνύει εάν η πλοήγηση του πίνακα περιεχομένων πρέπει να απενεργοποιηθεί κατά την απόδοση σε HTML ή PDF. Όταν αυτή η επιλογή οριστεί σε true, για απόδοση HTML, οι σχετικοί σύνδεσμοι από τον πίνακα περιεχομένων θα αντικατασταθούν με ετικέτες span, αφαιρώντας τη λειτουργικότητα αλλά διατηρώντας την οπτική εμφάνιση. Για απόδοση PDF, ο πίνακας περιεχομένων θα αποδοθεί ως απλό κείμενο χωρίς συνδέσμους.


**Returns:**
boolean - Αληθές εάν η πλοήγηση του πίνακα περιεχομένων είναι απενεργοποιημένη· διαφορετικά, ψευδές.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Ορίζει εάν η πλοήγηση του πίνακα περιεχομένων πρέπει να απενεργοποιηθεί κατά την απόδοση σε HTML ή PDF. Όταν αυτή η επιλογή οριστεί σε true, για απόδοση HTML, οι σχετικοί σύνδεσμοι από τον πίνακα περιεχομένων θα αντικατασταθούν με ετικέτες span, αφαιρώντας τη λειτουργικότητα αλλά διατηρώντας την οπτική εμφάνιση. Για απόδοση PDF, ο πίνακας περιεχομένων θα αποδοθεί ως απλό κείμενο χωρίς συνδέσμους.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | Υποδεικνύει εάν η πλοήγηση του πίνακα περιεχομένων πρέπει να απενεργοποιηθεί. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Λαμβάνει μια τιμή που καθορίζει εάν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισερχόμενου εγγράφου WordProcessing σε μορφές εξόδου HTML, PDF, PNG ή JPEG. Η προεπιλεγμένη τιμή για αυτήν την ιδιότητα είναι true \\u2014 τα πεδία θα ενημερωθούν πριν από την αποθήκευση.


Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Ορίζει μια τιμή που καθορίζει εάν τα πεδία ορισμένων τύπων πρέπει να ενημερωθούν πριν από την αποθήκευση του εισερχόμενου εγγράφου WordProcessing σε μορφές εξόδου HTML, PDF, PNG ή JPEG. Η προεπιλεγμένη τιμή για αυτήν την ιδιότητα είναι true \\u2014 τα πεδία θα ενημερωθούν πριν από την αποθήκευση.


Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Λαμβάνει την οριζόντια ανάλυση για τις παραγόμενες εικόνες σε κουκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση εγγράφων WordProcessing σε μορφές PNG ή JPEG.


Η προεπιλεγμένη τιμή είναι 96 DPI. Η ελάχιστη δυνατή τιμή - 72 DPI, η μέγιστη δυνατή τιμή - 600 DPI.
Εάν η τιμή που καθορίστηκε από τον χρήστη είναι εκτός αυτών των ορίων, θα εφαρμοστεί η ελάχιστη ή η μέγιστη δυνατή τιμή.


**Returns:**
int - η οριζόντια ανάλυση σε DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Ορίζει την οριζόντια ανάλυση για τις παραγόμενες εικόνες σε κουκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση εγγράφων WordProcessing σε μορφές PNG ή JPEG.


Η προεπιλεγμένη τιμή είναι 96 DPI. Η ελάχιστη δυνατή τιμή - 72 DPI, η μέγιστη δυνατή τιμή - 600 DPI.
Εάν η τιμή που καθορίστηκε από τον χρήστη είναι εκτός αυτών των ορίων, θα εφαρμοστεί η ελάχιστη ή η μέγιστη δυνατή τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | horizontalResolution | int | η οριζόντια ανάλυση σε DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Λαμβάνει την κάθετη ανάλυση για τις παραγόμενες εικόνες σε κουκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση εγγράφων WordProcessing σε μορφές PNG ή JPEG.


Η προεπιλεγμένη τιμή είναι 96 DPI. Η ελάχιστη δυνατή τιμή - 72 DPI, η μέγιστη δυνατή τιμή - 600 DPI.
Εάν η τιμή που καθορίστηκε από τον χρήστη είναι εκτός αυτών των ορίων, θα εφαρμοστεί η ελάχιστη ή η μέγιστη δυνατή τιμή.


**Returns:**
int - η κάθετη ανάλυση σε DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Ορίζει την κάθετη ανάλυση για τις παραγόμενες εικόνες σε κουκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση εγγράφων WordProcessing σε μορφές PNG ή JPEG.


Η προεπιλεγμένη τιμή είναι 96 DPI. Η ελάχιστη δυνατή τιμή - 72 DPI, η μέγιστη δυνατή τιμή - 600 DPI.
Εάν η τιμή που καθορίστηκε από τον χρήστη είναι εκτός αυτών των ορίων, θα εφαρμοστεί η ελάχιστη ή η μέγιστη δυνατή τιμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | verticalResolution | int | η κάθετη ανάλυση σε DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Επιτρέπει την εξαναγκαστική εφαρμογή αρίθμησης σελίδων για το φορτωμένο έγγραφο WordProcessing. Από προεπιλογή είναι [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 το έγγραφο παραμένει αμετάβλητο.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Επιτρέπει την εξαναγκαστική εφαρμογή αρίθμησης σελίδων για το φορτωμένο έγγραφο WordProcessing. Από προεπιλογή είναι [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 το έγγραφο παραμένει αμετάβλητο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | η θέση αριθμού σελίδας. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Ελέγξτε αν οι επιλογές έχουν αλλάξει.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | o | java.lang.Object | Το αντικείμενο για σύγκριση ισότητας. |
|

**Returns:**
boolean -  true  εάν οι επιλογές είναι ίσες με το καθορισμένο αντικείμενο,  false  διαφορετικά.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Υπολογίζει την τιμή του κώδικα κατακερματισμού για αυτό το αντικείμενο. Ο κώδικας κατακερματισμού βασίζεται σε
την εσωτερική κατάσταση του αντικειμένου και χρησιμοποιείται σε δομές δεδομένων βασισμένες σε κατακερματισμό
όπως οι hash maps και τα hash sets.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - η τιμή του κώδικα κατακερματισμού για αυτό το αντικείμενο.

