---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές που χρησιμοποιούνται για την ανάκτηση πληροφοριών σχετικά με την προβολή."
type: docs
weight: 34
url: /el/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Παρέχει επιλογές που χρησιμοποιούνται για την ανάκτηση πληροφοριών σχετικά με την προβολή.


Η κλάση ViewInfoOptions περιλαμβάνει πρόσθετες ρυθμίσεις και παραμέτρους που
μπορούν να χρησιμοποιηθούν για την ανάκτηση πληροφοριών σχετικά με μια προβολή στο στοιχείο GroupDocs.Viewer.


Παράδειγμα χρήσης:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | Δείχνει αν η εξαγωγή κειμένου είναι ενεργοποιημένη. |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | Ορίζει τη σημαία που υποδεικνύει εάν η εξαγωγή κειμένου είναι ενεργοποιημένη. |
|
|  | [getMaxWidth()](#getMaxWidth--) | Επιστρέφει το μέγιστο πλάτος της εικόνας εξόδου για απόδοση σε PNG/JPG. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
|
|  | [getMaxHeight()](#getMaxHeight--) | Επιστρέφει το μέγιστο ύψος της εικόνας εξόδου για απόδοση σε PNG/JPG. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
|
|  | [getWidth()](#getWidth--) | Το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
|
|  | [setWidth(int width)](#setWidth-int-) | Το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
|
|  | [getHeight()](#getHeight--) | Το ύψος της εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
|
|  | [setHeight(int height)](#setHeight-int-) | Το ύψος της εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG). |
|
|  | [forHtmlView()](#forHtmlView--) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε HTML.
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε HTML.
|
|  | [forJpgView()](#forJpgView--) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε JPG.
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε JPG.
|
|  | [forPngView()](#forPngView--) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε PNG.
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε PNG.
|
|  | [forPdfView()](#forPdfView--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ViewInfoOptions για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε PDF. |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση βασισμένη στο αντικείμενο [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση βασισμένη στο αντικείμενο [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Αρχικοποιεί μια νέα παρουσία του |
ViewInfoOptions
κλάση βασισμένη στο αντικείμενο [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) βασισμένο σε αντικείμενο PdfViewOptions. |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Δείχνει αν η εξαγωγή κειμένου είναι ενεργοποιημένη.
Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε το κείμενο που περιέχεται σε ένα έγγραφο προέλευσης και τις συντεταγμένες του. Στη συνέχεια, μπορείτε να χρησιμοποιήσετε αυτά τα δεδομένα για να προσθέσετε επιλέξιμο κείμενο πάνω στην εικόνα ή για να υλοποιήσετε αναζήτηση κειμένου σε απόδοση με βάση την εικόνα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Returns:**
boolean - True εάν η εξαγωγή κειμένου είναι ενεργοποιημένη, false διαφορετικά.

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Ορίζει τη σημαία που υποδεικνύει εάν η εξαγωγή κειμένου είναι ενεργοποιημένη.
Χρησιμοποιήστε αυτήν την ιδιότητα για να λάβετε το κείμενο που περιέχεται σε ένα έγγραφο προέλευσης και τις συντεταγμένες του. Στη συνέχεια, μπορείτε να χρησιμοποιήσετε αυτά τα δεδομένα για να προσθέσετε επιλέξιμο κείμενο πάνω στην εικόνα ή για να υλοποιήσετε αναζήτηση κειμένου σε απόδοση με βάση την εικόνα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extractText | boolean | True για ενεργοποίηση της εξαγωγής κειμένου, false για απενεργοποίηση. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Επιστρέφει το μέγιστο πλάτος της εικόνας εξόδου για απόδοση σε PNG/JPG.
Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Εάν ορίσετε την ιδιότητα, αυτή η ιδιότητα αγνοείται.


**Returns:**
int - το μέγιστο πλάτος της εικόνας εξόδου.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Ορίζει το μέγιστο πλάτος μιας εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG).
Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Εάν ορίσετε την ιδιότητα, αυτή η ιδιότητα αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxWidth | int | Το μέγιστο πλάτος της εικόνας εξόδου. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Επιστρέφει το μέγιστο ύψος της εικόνας εξόδου για απόδοση σε PNG/JPG.
Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Εάν ορίσετε την ιδιότητα, αυτή η ιδιότητα αγνοείται.


**Returns:**
int - το μέγιστο ύψος της εικόνας εξόδου.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Ορίζει το μέγιστο ύψος μιας εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG).
Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το μέγιστο ύψος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Εάν ορίσετε την ιδιότητα, αυτή η ιδιότητα αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxHeight | int | Το μέγιστο ύψος της εικόνας εξόδου. |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


Το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG).
Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα αγνοείται.


**Returns:**
int - το πλάτος της εικόνας.

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG).
Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το πλάτος της εικόνας εξόδου (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | width | int | Το πλάτος της εικόνας. |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


Το ύψος της εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG).
Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εξόδου εικόνας (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα αγνοείται.


**Returns:**
int - το ύψος της εικόνας.

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Το ύψος της εικόνας εξόδου (σε εικονοστοιχεία, μόνο για απόδοση σε PNG/JPG).
Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε το ύψος της εξόδου εικόνας (σε εικονοστοιχεία). Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Εάν ορίσετε αυτήν την ιδιότητα, η ιδιότητα αγνοείται.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ύψος | int | Το ύψος της εικόνας. |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε HTML.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε HTML.


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | renderSinglePage | boolean | Επιτρέπει την απόδοση του περιεχομένου HTML σε μία μόνο σελίδα. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε JPG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε JPG.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extractText | boolean | Επιτρέπει την εξαγωγή κειμένου. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε PNG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε PNG.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extractText | boolean | Επιτρέπει την εξαγωγή κειμένου. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης ViewInfoOptions για την ανάκτηση πληροφοριών σχετικά με την προβολή κατά την απόδοση σε PDF.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση βασισμένη στο αντικείμενο [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | Οι επιλογές προβολής HTML. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση βασισμένη στο αντικείμενο [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | Οι επιλογές προβολής PNG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Αρχικοποιεί μια νέα παρουσία του
ViewInfoOptions
κλάση βασισμένη στο αντικείμενο [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | Οι επιλογές προβολής JPG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) βασισμένο σε αντικείμενο PdfViewOptions.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | Οι επιλογές προβολής PDF. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

