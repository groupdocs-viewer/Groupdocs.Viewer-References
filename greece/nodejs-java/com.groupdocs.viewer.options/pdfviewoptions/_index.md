---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή PDF."
type: docs
weight: 23
url: /el/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή PDF.

Η κλάση PdfViewOptions περιλαμβάνει πρόσθετες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης εγγράφων σε μορφή PDF στο στοιχείο GroupDocs.Viewer. Για λεπτομέρειες, δείτε την [documentation][].

Παράδειγμα χρήσης:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions . |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions . |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions . |
| [PdfViewOptions()](#PdfViewOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions  με προεπιλεγμένες ρυθμίσεις. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions . |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Μειώστε το μέγεθος του αρχείου PDF εξόδου εφαρμόζοντας τεχνικές βελτιστοποίησης με διαφορετικές επιλογές. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Μειώστε το μέγεθος του αρχείου PDF εξόδου εφαρμόζοντας τεχνικές βελτιστοποίησης με διαφορετικές επιλογές. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Ανακτά το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Ανακτά το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [getImageWidth()](#getImageWidth--) | Ανακτά το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
| [getImageHeight()](#getImageHeight--) | Ανακτά το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |
| [getSecurity()](#getSecurity--) | Ανακτά τις επιλογές ασφαλείας για το έγγραφο PDF εξόδου. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Ορίζει τις επιλογές ασφαλείας για το έγγραφο PDF εξόδου. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ανακτά την κλήση επιστροφής που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ορίζει την κλήση επιστροφής που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Η μέθοδος που χρησιμοποιείται για τη δημιουργία της ροής για την εγγραφή των δεδομένων του αρχείου εξόδου. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | Η μέθοδος που χρησιμοποιείται για την απελευθέρωση της ροής που δημιουργήθηκε από τη μέθοδο  createFileStream  . |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής αρχείου εξόδου. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions  με προεπιλεγμένες ρυθμίσεις.

Αυτός ο κατασκευαστής δημιουργεί ένα νέο  PdfViewOptions  αντικείμενο με "output.pdf" ως μορφή διαδρομής αρχείου για το αρχείο εξόδου. Το αρχείο εξόδου θα τοποθετηθεί στον τρέχοντα κατάλογο εργασίας της εφαρμογής. Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions .

Αυτός ο κατασκευαστής δημιουργεί ένα νέο  PdfViewOptions  αντικείμενο με την καθορισμένη παράμετρο  outputFilePath  που αντιπροσωπεύει τη διαδρομή για το αρχείο PDF εξόδου. Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputFilePath | java.lang.String | Η διαδρομή για το αρχείο PDF εξόδου. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  PdfViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | Η διαδρομή για το αρχείο PDF εξόδου. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Μειώστε το μέγεθος του αρχείου PDF εξόδου εφαρμόζοντας τεχνικές βελτιστοποίησης με διαφορετικές επιλογές.

Αυτή η επιλογή υποστηρίζεται για οποιεσδήποτε μορφές αρχείων εισόδου που υποστηρίζονται για μετατροπή σε PDF: [Υποστηριζόμενες μορφές εγγράφων][] Για λεπτομέρειες και παραδείγματα κώδικα, δείτε αυτή τη [σελίδα][] και τα υπο-στοιχεία της.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Μειώστε το μέγεθος του αρχείου PDF εξόδου εφαρμόζοντας τεχνικές βελτιστοποίησης με διαφορετικές επιλογές.

Αυτή η επιλογή υποστηρίζεται για οποιεσδήποτε μορφές αρχείων εισόδου που υποστηρίζονται για μετατροπή σε PDF: [Υποστηριζόμενες μορφές εγγράφων][] Για λεπτομέρειες και παραδείγματα κώδικα, δείτε αυτή τη [σελίδα][] και τα υπο-στοιχεία της.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions αντικείμενο ή null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Ανακτά το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. Αυτό το παράμετρο ισχύει μόνο όταν μετατρέπεται μια μοναδική εικόνα σε HTML.

Χρησιμοποιήστε αυτή την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Το GroupDocs.Viewer εφαρμόζει αυτή την ιδιότητα κατά την απόδοση μιας μοναδικής εικόνας σε PDF. Για λεπτομέρειες, δείτε την [τεκμηρίωση][]. Εάν ορίσετε την  property, αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - το μέγιστο πλάτος της εικόνας εξόδου σε εικονοστοιχεία.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. Αυτό το παράμετρο ισχύει μόνο όταν μετατρέπεται μια μοναδική εικόνα σε HTML.

Χρησιμοποιήστε αυτή την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Το GroupDocs.Viewer εφαρμόζει αυτή την ιδιότητα κατά την απόδοση μιας μοναδικής εικόνας σε PDF. Για λεπτομέρειες, δείτε την [τεκμηρίωση][]. Εάν ορίσετε την  property, αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageMaxWidth | int | Το μέγιστο πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Ανακτά το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. Αυτό το παράμετρο ισχύει μόνο όταν μετατρέπεται μια μοναδική εικόνα σε HTML.

Χρησιμοποιήστε αυτή την ιδιότητα για να ορίσετε το μέγιστο ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Το GroupDocs.Viewer εφαρμόζει αυτή την ιδιότητα κατά την απόδοση μιας μοναδικής εικόνας σε PDF. Για λεπτομέρειες, δείτε την [τεκμηρίωση][]. Εάν ορίσετε την  property, αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - το μέγιστο ύψος της εικόνας εξόδου σε εικονοστοιχεία.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. Αυτή η παράμετρος εφαρμόζεται μόνο κατά τη μετατροπή μιας μόνο εικόνας σε HTML.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Το GroupDocs.Viewer εφαρμόζει αυτήν την ιδιότητα μόνο κατά την απόδοση μιας μόνο εικόνας σε HTML. Για λεπτομέρειες, δείτε την [documentation][]. Εάν ορίσετε την  ιδιότητα, αυτή η ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageMaxHeight | int | Το μέγιστο ύψος της εικόνας εξόδου σε εικονοστοιχεία. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Ανακτά το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. Αυτή η παράμετρος εφαρμόζεται μόνο κατά τη μετατροπή μιας μόνο εικόνας σε HTML.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Το GroupDocs.Viewer εφαρμόζει αυτήν την ιδιότητα κατά την απόδοση μιας μόνο εικόνας σε PDF. Για λεπτομέρειες, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η  ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - το πλάτος της εικόνας εξόδου σε εικονοστοιχεία.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. Αυτή η παράμετρος εφαρμόζεται μόνο κατά τη μετατροπή μιας μόνο εικόνας PDF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageWidth | int | Το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Ανακτά το ύψος της εικόνας εξόδου σε εικονοστοιχεία. Αυτή η παράμετρος εφαρμόζεται μόνο κατά τη μετατροπή μιας μόνο εικόνας σε HTML.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Το GroupDocs.Viewer εφαρμόζει αυτήν την ιδιότητα μόνο κατά την απόδοση μιας μόνο εικόνας σε HTML. Για λεπτομέρειες, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η  ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - το ύψος της εικόνας εξόδου σε εικονοστοιχεία.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία. Αυτή η παράμετρος εφαρμόζεται μόνο κατά τη μετατροπή μιας μόνο εικόνας σε HTML.

Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Το GroupDocs.Viewer εφαρμόζει αυτήν την ιδιότητα μόνο κατά την απόδοση μιας μόνο εικόνας σε HTML. Για λεπτομέρειες, δείτε την [documentation][]. Εάν ορίσετε αυτήν την ιδιότητα, η  ιδιότητα αγνοείται.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageHeight | int | Το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Ανακτά τις επιλογές ασφαλείας για το έγγραφο PDF εξόδου.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Ορίζει τις επιλογές ασφαλείας για το έγγραφο PDF εξόδου.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | Οι επιλογές ασφαλείας για το έγγραφο PDF εξόδου. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ανακτά την κλήση επιστροφής που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - η κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης του εγγράφου.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Ορίζει την κλήση επιστροφής που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Η κλήση επιστροφής για την εκτίμηση της προόδου αποθήκευσης του εγγράφου. |

