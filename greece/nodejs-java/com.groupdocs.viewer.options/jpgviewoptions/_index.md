---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή JPG."
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή JPG.

Η κλάση JpgViewOptions περιλαμβάνει πρόσθετες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης εγγράφων σε μορφή JPG στο στοιχείο GroupDocs.Viewer.

Παράδειγμα χρήσης:

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions . |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions . |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions . |
| [JpgViewOptions()](#JpgViewOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της  JpgViewOptions  με "p\_\{0\}.jpg" ως μορφή διαδρομής αρχείου για τα αρχεία εξόδου. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions . |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Λαμβάνει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [getMaxHeight()](#getMaxHeight--) | Λαμβάνει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [getQuality()](#getQuality--) | Λαμβάνει την ποιότητα της εικόνας εξόδου. |
| [setQuality(byte value)](#setQuality-byte-) | Ορίζει την ποιότητα της εικόνας εξόδου. |
| [isExtractText()](#isExtractText--) | Επιτρέπει την εξαγωγή κειμένου. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Ενεργοποιεί ή απενεργοποιεί την εξαγωγή κειμένου. |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
| [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |
| [setHeight(int value)](#setHeight-int-) | Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Λαμβάνει το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής σελίδας εξόδου. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Λαμβάνει την κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ορίζει την κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email. |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που έχει ανατεθεί στον αντιπρόσωπο που περάστηκε στην παράμετρο  createPageStream . |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Η factory που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής εξόδου σελίδας. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της  JpgViewOptions  με "p\_\{0\}.jpg" ως μορφή διαδρομής αρχείου για τα αρχεία εξόδου. Τα αρχεία εξόδου θα τοποθετηθούν στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου, π.χ., 'page\_\{0\}.jpg'. |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  JpgViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Η μορφή διαδρομής αρχείου, π.χ., 'page\_\{0\}.jpg'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Λαμβάνει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][]. Εάν ορίσετε την ιδιότητα \#setWidth(int).setWidth(int), αυτή η ιδιότητα θα αγνοηθεί.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - το μέγιστο πλάτος μιας εικόνας εξόδου.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][]. Εάν ορίσετε την ιδιότητα \#setWidth(int).setWidth(int), αυτή η ιδιότητα θα αγνοηθεί.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxWidth | int | Το μέγιστο πλάτος μιας εικόνας εξόδου. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Λαμβάνει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εξαγόμενης εικόνας (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε την ιδιότητα \#setHeight(int).setHeight(int), αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - το μέγιστο ύψος μιας εικόνας εξόδου.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εξαγόμενης εικόνας (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε την ιδιότητα \#setHeight(int).setHeight(int), αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxHeight | int | Το μέγιστο ύψος μιας εικόνας εξόδου. |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Λαμβάνει την ποιότητα της εικόνας εξόδου.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - η ποιότητα της εξαγόμενης εικόνας.
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Ορίζει την ποιότητα της εικόνας εξόδου.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte | Η ποιότητα της εξαγόμενης εικόνας. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Επιτρέπει την εξαγωγή κειμένου.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  εάν η εξαγωγή κειμένου είναι ενεργοποιημένη,  false  διαφορετικά.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Ενεργοποιεί ή απενεργοποιεί την εξαγωγή κειμένου.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση της εξαγωγής κειμένου,  false  για απενεργοποίησή του. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εξαγόμενης εικόνας (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα \#setMaxWidth(int).setMaxWidth(int) αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - το πλάτος της εικόνας εξόδου.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εξαγόμενης εικόνας (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα \#setMaxWidth(int).setMaxWidth(int) αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | Το πλάτος της εικόνας εξόδου. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος της εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εξαγόμενης εικόνας (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα \#setMaxHeight(int).setMaxHeight(int) αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - το ύψος της εικόνας εξόδου.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εξαγόμενης εικόνας (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα \#setMaxHeight(int).setMaxHeight(int) αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | Το ύψος της εικόνας εξόδου. |

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
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Η κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης του εγγράφου. |

