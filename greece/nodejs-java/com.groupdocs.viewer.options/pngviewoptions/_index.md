---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή PNG."
type: docs
weight: 25
url: /el/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή PNG.

Η κλάση PngViewOptions περιλαμβάνει πρόσθετες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης εγγράφων σε μορφή PNG στο στοιχείο GroupDocs.Viewer.

Παράδειγμα χρήσης:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions. |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions. |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions. |
| [PngViewOptions()](#PngViewOptions--) | Αρχικοποιεί νέο αντικείμενο της κλάσης PngViewOptions. |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions. |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Επιστρέφει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [getMaxHeight()](#getMaxHeight--) | Επιστρέφει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [isExtractText()](#isExtractText--) | Καθορίζει εάν η εξαγωγή κειμένου είναι ενεργοποιημένη. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Ενεργοποιεί ή απενεργοποιεί την εξαγωγή κειμένου. |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
| [setWidth(int value)](#setWidth-int-) | Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |
| [setHeight(int value)](#setHeight-int-) | Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ανακτά τη συνάρτηση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ορίζει τη συνάρτηση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου. |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που έχει ανατεθεί στην παράμετρο createPageStream. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Η factory που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής εξόδου σελίδας. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Αρχικοποιεί νέο αντικείμενο της κλάσης PngViewOptions.

Αυτός ο κατασκευαστής αρχικοποιεί μια νέα παρουσία του PngViewOptions με το "p\_\{0\}.png" ως μορφή διαδρομής αρχείου για τα αρχεία εξόδου. Τα αρχεία εξόδου θα τοποθετηθούν στον τρέχοντα κατάλογο εργασίας της εφαρμογής. Για το παράδειγμα κώδικα, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions.

Για παράδειγμα, εάν η μορφή διαδρομής αρχείου είναι 'page\_\{0\}.png', τα αρχεία εξόδου θα ονομάζονται 'page\_1.png', 'page\_2.png' κ.λπ., ανάλογα με τον αριθμό σελίδας.

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου, π.χ., 'page\_\{0\}.png'. |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PngViewOptions.

Για παράδειγμα, εάν η μορφή διαδρομής αρχείου είναι 'page\_\{0\}.png', τα αρχεία εξόδου θα ονομάζονται 'page\_1.png', 'page\_2.png' κ.λπ., ανάλογα με τον αριθμό σελίδας. Για το παράδειγμα κώδικα, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Η μορφή διαδρομής αρχείου, π.χ., 'page\_\{0\}.png'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Επιστρέφει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε την  ιδιότητα, αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - το μέγιστο πλάτος της εικόνας εξόδου.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε την  ιδιότητα, αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxWidth | int | Το μέγιστο πλάτος της εικόνας εξόδου. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Επιστρέφει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε την  ιδιότητα, αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - το μέγιστο ύψος της εικόνας εξόδου.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε την  ιδιότητα, αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxHeight | int | Το μέγιστο ύψος της εικόνας εξόδου. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Καθορίζει εάν η εξαγωγή κειμένου είναι ενεργοποιημένη.

Αυτή η επιλογή μπορεί να είναι χρήσιμη όταν θέλετε να προσθέσετε ένα επιλεγμένο επίπεδο κειμένου πάνω στην εικόνα. Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε το κείμενο που περιέχεται σε ένα έγγραφο προέλευσης και τις συντεταγμένες του. Στη συνέχεια, μπορείτε να χρησιμοποιήσετε αυτά τα δεδομένα για να προσθέσετε επιλεγμένο κείμενο πάνω στην εικόνα ή για να υλοποιήσετε αναζήτηση κειμένου σε απόδοση βασισμένη στην εικόνα. Για παράδειγμα κώδικα, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  εάν η εξαγωγή κειμένου είναι ενεργοποιημένη,  false  διαφορετικά.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Ενεργοποιεί ή απενεργοποιεί την εξαγωγή κειμένου.

Αυτή η επιλογή μπορεί να είναι χρήσιμη όταν θέλετε να προσθέσετε ένα επιλεγμένο επίπεδο κειμένου πάνω στην εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση της εξαγωγής κειμένου,  false  για απενεργοποίησή του. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Επιστρέφει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η  ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - το πλάτος της εικόνας εξόδου.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η  ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | Το πλάτος της εικόνας εξόδου. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Επιστρέφει το ύψος της εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η  ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - το ύψος της εικόνας εξόδου.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η  ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | Το ύψος της εικόνας εξόδου. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ανακτά τη συνάρτηση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - η κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης του εγγράφου.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Ορίζει τη συνάρτηση επιστροφής για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Η κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης του εγγράφου. |

