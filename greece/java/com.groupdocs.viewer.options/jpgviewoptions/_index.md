---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή JPG."
type: docs
weight: 17
url: /el/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή JPG.


Η κλάση JpgViewOptions περιλαμβάνει πρόσθετες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης των εγγράφων
σε μορφή JPG στο στοιχείο GroupDocs.Viewer.


Παράδειγμα χρήσης:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Αρχικοποιεί μια νέα παρουσία του |
JpgViewOptions
κλάσης.
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Αρχικοποιεί μια νέα παρουσία του |
JpgViewOptions
κλάσης.
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Αρχικοποιεί μια νέα παρουσία του |
JpgViewOptions
κλάσης.
|
|  | [JpgViewOptions()](#JpgViewOptions--) | Αρχικοποιεί μια νέα παρουσία του |
JpgViewOptions
με "p_{0}.jpg" ως μορφή διαδρομής αρχείου για τα αρχεία εξόδου.
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία του |
JpgViewOptions
κλάσης.
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Αρχικοποιεί μια νέα παρουσία του |
JpgViewOptions
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Λαμβάνει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Ορίζει το μέγιστο πλάτος μιας εξαγόμενης εικόνας σε εικονοστοιχεία. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Λαμβάνει το μέγιστο ύψος μιας εξόδου εικόνας σε εικονοστοιχεία. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Ορίζει το μέγιστο ύψος μιας εξαγόμενης εικόνας σε εικονοστοιχεία. |
|
|  | [getQuality()](#getQuality--) | Λαμβάνει την ποιότητα της εικόνας εξόδου. |
|
|  | [setQuality(byte value)](#setQuality-byte-) | Ορίζει την ποιότητα της εικόνας εξόδου. |
|
|  | [isExtractText()](#isExtractText--) | Επιτρέπει την εξαγωγή κειμένου. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Ενεργοποιεί ή απενεργοποιεί την εξαγωγή κειμένου. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος της εξόδου εικόνας σε εικονοστοιχεία. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | Λαμβάνει το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής σελίδας εξόδου. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Λαμβάνει την κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ορίζει την κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email. |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Αρχικοποιεί μια νέα παρουσία του
JpgViewOptions
κλάσης.


Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Αρχικοποιεί μια νέα παρουσία του
JpgViewOptions
κλάσης.


Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που εκχωρήθηκε στον αντιπρόσωπο που περάστηκε στην παράμετρο createPageStream. |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Αρχικοποιεί μια νέα παρουσία του
JpgViewOptions
κλάσης.


Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση του ρεύματος εξόδου σελίδας. |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Αρχικοποιεί μια νέα παρουσία του
JpgViewOptions
με "p_{0}.jpg" ως μορφή διαδρομής αρχείου για τα αρχεία εξόδου.
Τα αρχεία εξόδου θα τοποθετηθούν στον τρέχοντα κατάλογο εργασίας της εφαρμογής.


Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Αρχικοποιεί μια νέα παρουσία του
JpgViewOptions
κλάσης.


Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου, π.χ., 'page_{0}.jpg'. |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Αρχικοποιεί μια νέα παρουσία του
JpgViewOptions
κλάσης.


Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Η μορφή διαδρομής αρχείου, π.χ., 'page_{0}.jpg'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Λαμβάνει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Εάν ορίσετε την ιδιότητα #setWidth(int).setWidth(int), αυτή η ιδιότητα αγνοείται.


**Returns:**
int - το μέγιστο πλάτος μιας εικόνας εξόδου.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Ορίζει το μέγιστο πλάτος μιας εξαγόμενης εικόνας σε εικονοστοιχεία.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Εάν ορίσετε την ιδιότητα #setWidth(int).setWidth(int), αυτή η ιδιότητα αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxWidth | int | Το μέγιστο πλάτος μιας εικόνας εξόδου. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Λαμβάνει το μέγιστο ύψος μιας εξόδου εικόνας σε εικονοστοιχεία.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Εάν ορίσετε την ιδιότητα #setHeight(int).setHeight(int), αυτή η ιδιότητα αγνοείται.


**Returns:**
int - το μέγιστο ύψος μιας εικόνας εξόδου.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Ορίζει το μέγιστο ύψος μιας εξαγόμενης εικόνας σε εικονοστοιχεία.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Εάν ορίσετε την ιδιότητα #setHeight(int).setHeight(int), αυτή η ιδιότητα αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxHeight | int | Το μέγιστο ύψος μιας εικόνας εξόδου. |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Λαμβάνει την ποιότητα της εικόνας εξόδου.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Returns:**
byte - η ποιότητα της εικόνας εξόδου.

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Ορίζει την ποιότητα της εικόνας εξόδου.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte | Η ποιότητα της εικόνας εξόδου. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Επιτρέπει την εξαγωγή κειμένου.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  εάν η εξαγωγή κειμένου είναι ενεργοποιημένη,  false  διαφορετικά.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Ενεργοποιεί ή απενεργοποιεί την εξαγωγή κειμένου.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  για ενεργοποίηση της εξαγωγής κειμένου,  false  για απενεργοποίηση. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος της εξόδου εικόνας σε εικονοστοιχεία.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα #setMaxWidth(int).setMaxWidth(int) αγνοείται.


**Returns:**
int - το πλάτος της εικόνας εξόδου.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα #setMaxWidth(int).setMaxWidth(int) αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Το πλάτος της εικόνας εξόδου. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος της εικόνας εξόδου σε εικονοστοιχεία.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα #setMaxHeight(int).setMaxHeight(int) αγνοείται.


**Returns:**
int - το ύψος της εικόνας εξόδου.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα #setMaxHeight(int).setMaxHeight(int) αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Το ύψος της εικόνας εξόδου. |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Λαμβάνει το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής σελίδας εξόδου.


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Λαμβάνει την κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - η κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης του εγγράφου.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Ορίζει την κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Η κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης του εγγράφου. |
|

