---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή HTML."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων σε μορφή HTML.

Η κλάση HtmlViewOptions περιλαμβάνει πρόσθετες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης εγγράφων σε μορφή HTML στο στοιχείο GroupDocs.Viewer.

Για λεπτομέρειες, δείτε το [topic][] και τα υποστοιχεία του.

Παράδειγμα χρήσης:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```


[topic]: https://docs.groupdocs.com/viewer/java/rendering-to-html/
## Fields

| Field | Περιγραφή |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isRenderResponsive()](#isRenderResponsive--) | Καθορίζει εάν η ανταποκρινόμενη απόδοση είναι ενεργοποιημένη. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Ορίζει εάν η ανταποκρινόμενη απόδοση είναι ενεργοποιημένη. |
| [isMinify()](#isMinify--) | Ελέγχει αν η ελαχιστοποίηση του περιεχομένου HTML και των πόρων HTML είναι ενεργοποιημένη. |
| [setMinify(boolean value)](#setMinify-boolean-) | Ορίζει εάν η ελαχιστοποίηση του περιεχομένου HTML και των πόρων HTML είναι ενεργοποιημένη. |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Ενεργοποιεί την απόδοση ολόκληρου του εγγράφου σε ένα αρχείο HTML. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Ενεργοποιεί την απόδοση ολόκληρου του εγγράφου σε ένα αρχείο HTML. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Επιστρέφει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Λαμβάνει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία. |
| [getImageWidth()](#getImageWidth--) | Λαμβάνει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία. |
| [getImageHeight()](#getImageHeight--) | Λαμβάνει το ύψος της εικόνας εξόδου σε εικονοστοιχεία κατά τη μετατροπή μιας μόνο εικόνας σε HTML. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία κατά τη μετατροπή μιας μόνο εικόνας σε HTML. |
| [isForPrinting()](#isForPrinting--) | Ελέγχει αν το HTML εξόδου πρέπει να βελτιστοποιηθεί για εκτύπωση. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Ορίζει αν το HTML εξόδου πρέπει να βελτιστοποιηθεί για εκτύπωση. |
| [isExcludeFonts()](#isExcludeFonts--) | Καθορίζει αν θα εξαλειφθούν οι γραμματοσειρές από το έγγραφο HTML. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Ορίζει αν θα εξαλειφθούν οι γραμματοσειρές από το έγγραφο HTML. |
| [getFontsToExclude()](#getFontsToExclude--) | Ανακτά τη λίστα των ονομάτων γραμματοσειρών που θα εξαλειφθούν από το έγγραφο HTML. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Ορίζει τη λίστα των ονομάτων γραμματοσειρών που θα εξαλειφθούν από το έγγραφο HTML. |
| [isRemoveJavaScript()](#isRemoveJavaScript--) | Επιτρέπει την αφαίρεση του κώδικα πηγαίου JavaScript από τους συνδέσμους στα παραγόμενα έγγραφα HTML, κατά την απόδοση εγγράφων εισόδου που περιέχουν τα σενάρια. |
| [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Ορίζει την άδεια για αφαίρεση του κώδικα πηγαίου JavaScript από τους συνδέσμους στα παραγόμενα έγγραφα HTML, κατά την απόδοση εγγράφων εισόδου που περιέχουν τα σενάρια. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ανακτά την κλήση επιστροφής που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ορίζει την κλήση επιστροφής που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με ενσωματωμένους πόρους. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με ενσωματωμένους πόρους. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με ενσωματωμένους πόρους. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions . |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions . |
| [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions . |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με εξωτερικούς πόρους. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με εξωτερικούς πόρους. |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με εξωτερικούς πόρους. |
| [forExternalResources()](#forExternalResources--) | Αρχικοποιεί νέο στιγμιότυπο της κλάσης  HtmlViewOptions . |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions . |
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Καθορίζει αν η ανταποκρινόμενη απόδοση είναι ενεργοποιημένη. Οι ανταποκρινόμενες ιστοσελίδες αποδίδουν καλά σε συσκευές με διαφορετικά μεγέθη οθόνης.

Ο ανταποκρινόμενος σχεδιασμός στοχεύει στο να κάνει τις ιστοσελίδες να αποδίδουν καλά σε μια ποικιλία συσκευών. Για απόδοση με ανταποκρινόμενη διάταξη, ορίστε αυτήν την ιδιότητα σε true. Για παράδειγμα κώδικα, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Returns:**
boolean -  true  εάν η ανταποκρινόμενη απόδοση είναι ενεργοποιημένη,  false  διαφορετικά.
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Ορίζει αν η ανταποκρινόμενη απόδοση είναι ενεργοποιημένη. Οι ανταποκρινόμενες ιστοσελίδες αποδίδουν καλά σε συσκευές με διαφορετικά μεγέθη οθόνης.

Ο ανταποκρινόμενος σχεδιασμός στοχεύει στο να κάνει τις ιστοσελίδες να αποδίδουν καλά σε μια ποικιλία συσκευών. Για απόδοση με ανταποκρινόμενη διάταξη, ορίστε αυτήν την ιδιότητα σε true. Για παράδειγμα κώδικα, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση της ανταποκρινόμενης απόδοσης,  false  για απενεργοποίησή της. |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Ελέγχει αν η ελαχιστοποίηση του περιεχομένου HTML και των πόρων HTML είναι ενεργοποιημένη.

Η συμπίεση του περιεχομένου εξόδου (HTML, CSS και SVG) είναι ένας από τους τρόπους βελτιστοποίησης του αρχείου HTML. Για να το κάνετε αυτό, ορίστε αυτήν την ιδιότητα σε true. Για παράδειγμα κώδικα, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Returns:**
boolean -  true  εάν η ελαχιστοποίηση είναι ενεργοποιημένη,  false  διαφορετικά.
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Ορίζει εάν η ελαχιστοποίηση του περιεχομένου HTML και των πόρων HTML είναι ενεργοποιημένη.

Η συμπίεση του περιεχομένου εξόδου (HTML, CSS και SVG) είναι ένας από τους τρόπους βελτιστοποίησης του αρχείου HTML. Για να το κάνετε αυτό, ορίστε αυτήν την ιδιότητα σε true. Για παράδειγμα κώδικα, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση της ελαχιστοποίησης,  false  για απενεργοποίηση. |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Ενεργοποιεί την απόδοση ολόκληρου του εγγράφου σε ένα αρχείο HTML.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Ενεργοποιεί την απόδοση ολόκληρου του εγγράφου σε ένα αρχείο HTML.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Επιστρέφει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - το μέγιστο πλάτος μιας εικόνας εξόδου.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου σε εικονοστοιχεία.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageMaxWidth | int | Το μέγιστο πλάτος μιας εικόνας εξόδου. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Λαμβάνει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - το μέγιστο ύψος μιας εικόνας εξόδου.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου σε εικονοστοιχεία.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageMaxHeight | int | Το μέγιστο ύψος μιας εικόνας εξόδου. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Λαμβάνει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - το πλάτος της εικόνας εξόδου.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Ορίζει το πλάτος της εικόνας εξόδου σε εικονοστοιχεία.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageWidth | int | Το πλάτος της εικόνας εξόδου. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Λαμβάνει το ύψος της εικόνας εξόδου σε εικονοστοιχεία κατά τη μετατροπή μιας μόνο εικόνας σε HTML.

Για λεπτομέρειες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - το ύψος της εικόνας εξόδου σε εικονοστοιχεία.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Ορίζει το ύψος της εικόνας εξόδου σε εικονοστοιχεία κατά τη μετατροπή μιας μόνο εικόνας σε HTML.

Για λεπτομέρειες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageHeight | int | Το ύψος της εικόνας εξόδου σε εικονοστοιχεία. |

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Ελέγχει αν το HTML εξόδου πρέπει να βελτιστοποιηθεί για εκτύπωση.

Ενεργοποιήστε αυτήν την επιλογή για να μετατρέψετε τις σελίδες HTML εξόδου σε διανυσματική μορφή SVG. Για λεπτομέρειες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Returns:**
boolean -  true  εάν το HTML εξόδου πρέπει να βελτιστοποιηθεί για εκτύπωση,  false  διαφορετικά.
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Ορίζει αν το HTML εξόδου πρέπει να βελτιστοποιηθεί για εκτύπωση.

Ενεργοποιήστε αυτήν την επιλογή για να μετατρέψετε τις σελίδες HTML εξόδου σε διανυσματική μορφή SVG. Για λεπτομέρειες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για βελτιστοποίηση του HTML εξόδου για εκτύπωση,  false  διαφορετικά. |

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Καθορίζει αν θα εξαλειφθούν οι γραμματοσειρές από το έγγραφο HTML.

Από προεπιλογή, το GroupDocs.Viewer ενσωματώνει τις γραμματοσειρές που χρησιμοποιούνται στο έγγραφο στο HTML. Για να το αποτρέψετε, ορίστε αυτήν την ιδιότητα σε true. Για λεπτομέρειες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
boolean -  true  εάν οι γραμματοσειρές πρέπει να εξαιρεθούν,  false  διαφορετικά.
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Ορίζει αν θα εξαλειφθούν οι γραμματοσειρές από το έγγραφο HTML.

Από προεπιλογή, το GroupDocs.Viewer ενσωματώνει τις γραμματοσειρές που χρησιμοποιούνται στο έγγραφο στο HTML. Για να το αποτρέψετε, ορίστε αυτήν την ιδιότητα σε true. Για λεπτομέρειες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για εξαίρεση γραμματοσειρών,  false  διαφορετικά. |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Ανακτά τη λίστα των ονομάτων γραμματοσειρών που θα εξαλειφθούν από το έγγραφο HTML.

Αυτή η επιλογή υποστηρίζεται μόνο για παρουσιάσεις. Η ένταξη γραμματοσειρών στο έγγραφο HTML βελτιώνει τη σταθερότητα της προβολής εξόδου, αλλά αυξάνει το μέγεθος του αποτελέσματος απόδοσης. Χρησιμοποιήστε αυτήν την επιλογή για να βρείτε ένα συμβιβασμό μεταξύ σταθερότητας και μεγέθους εξόδου. Συμπεριλάβετε ονόματα γραμματοσειρών που είναι δημοφιλή και εγκατεστημένα στα περισσότερα συστήματα.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
java.util.List<java.lang.String> - η λίστα με τα ονόματα γραμματοσειρών που θα εξαλειφθούν από το έγγραφο HTML.
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Ορίζει τη λίστα των ονομάτων γραμματοσειρών που θα εξαλειφθούν από το έγγραφο HTML.

Αυτή η επιλογή υποστηρίζεται μόνο για παρουσιάσεις. Η ένταξη γραμματοσειρών στο έγγραφο HTML βελτιώνει τη σταθερότητα της προβολής εξόδου, αλλά αυξάνει το μέγεθος του αποτελέσματος απόδοσης. Χρησιμοποιήστε αυτήν την επιλογή για να βρείτε ένα συμβιβασμό μεταξύ σταθερότητας και μεγέθους εξόδου. Συμπεριλάβετε ονόματα γραμματοσειρών που είναι δημοφιλή και εγκατεστημένα στα περισσότερα συστήματα.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | Η λίστα με τα ονόματα γραμματοσειρών που θα εξαλειφθούν από το έγγραφο HTML. |

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Επιτρέπει την αφαίρεση του κώδικα πηγαίου JavaScript από τους συνδέσμους στα παραγόμενα έγγραφα HTML, κατά την απόδοση των εισερχόμενων εγγράφων που περιέχουν τα σενάρια. Από προεπιλογή είναι ενεργοποιημένο (true).

Για λεπτομέρειες σχετικά με την αφαίρεση του JavaScript, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Ορίζει την άδεια για αφαίρεση του κώδικα πηγαίου JavaScript από τους συνδέσμους στα παραγόμενα έγγραφα HTML, κατά την απόδοση των εισερχόμενων εγγράφων που περιέχουν τα σενάρια. Από προεπιλογή είναι ενεργοποιημένο (true).

Για λεπτομέρειες σχετικά με την αφαίρεση του JavaScript, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ανακτά την κλήση επιστροφής που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - η κλήση επιστροφής (callback) που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης του εγγράφου.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Ορίζει την κλήση επιστροφής που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης ενός εγγράφου Words ή Email.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Η κλήση επιστροφής (callback) που χρησιμοποιείται για την εκτίμηση της προόδου αποθήκευσης του εγγράφου. |

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με ενσωματωμένους πόρους.

***Note:** The method takes a  CreatePageStream  parameter, which is a method used to instantiate a stream for writing output page data.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με ενσωματωμένους πόρους.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που έχει ανατεθεί στην παράμετρο createPageStream. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με ενσωματωμένους πόρους.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Η factory που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής εξόδου σελίδας. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου, π.χ., 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Η μορφή διαδρομής αρχείου, π.χ., 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με εξωτερικούς πόρους.

***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Η μέθοδος που δημιουργεί το URL για τον πόρο HTML. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με εξωτερικούς πόρους.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου πόρου HTML. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Η μέθοδος που δημιουργεί το URL για τον πόρο HTML. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createResourceStream. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions  για απόδοση σε HTML με εξωτερικούς πόρους.

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Η factory που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής εξόδου σελίδας. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Η factory που υλοποιεί μεθόδους για τη δημιουργία URL πόρων και τη δημιουργία/απελευθέρωση της ροής εξόδου πόρου HTML. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Αρχικοποιεί νέο στιγμιότυπο της κλάσης  HtmlViewOptions .

 *  \- with "p\_\{0\}.html" as file path format for the output HTML files;
 *  \- with "p\_\{0\}\_\{1\}" as file path format for the output HTML-resource files;
 *  \- with "p\_\{0\}\_\{1\}" as URL format for HTML-resources;

Τα αρχεία εξόδου θα τοποθετηθούν στον τρέχοντα κατάλογο εργασίας της εφαρμογής. Για το παράδειγμα κώδικα, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  HtmlViewOptions .

Για το παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου, π.χ., 'page\_\{0\}.html'. |
| resourceFilePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου πόρου, π.χ., 'page\_\{0\}/resource\_\{1\}'. |
| resourceUrlFormat | java.lang.String | Η μορφή URL πόρου, π.χ., 'page\_\{0\}/resource\_\{1\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
