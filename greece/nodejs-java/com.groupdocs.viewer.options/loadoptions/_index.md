---
title: "LoadOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές που χρησιμοποιούνται για το άνοιγμα ενός αρχείου."
type: docs
weight: 18
url: /el/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Παρέχει επιλογές που χρησιμοποιούνται για το άνοιγμα ενός αρχείου.

Η κλάση LoadOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για να καθορίσουν πώς πρέπει να ανοίγεται και να φορτώνεται ένα αρχείο στο στοιχείο GroupDocs.Viewer. Για λεπτομέρειες, δείτε αυτή τη [σελίδα][] και τα υποστοιχεία της.

Παράδειγμα χρήσης:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/loading/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  LoadOptions . |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  LoadOptions . |
## Fields

| Field | Περιγραφή |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | Όταν είναι ενεργοποιημένο, το GroupDocs.Viewer προσπαθεί να επισκευάσει δομική αλλοίωση σε έγγραφα PDF. |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Όταν είναι ενεργοποιημένο, το GroupDocs.Viewer προσπαθεί να επισκευάσει δομική αλλοίωση σε έγγραφα PDF. |
| [getFileType()](#getFileType--) | Λαμβάνει τον τύπο του αρχείου που θα ανοίξει. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Ορίζει τον τύπο του αρχείου που θα ανοίξει. |
| [getPassword()](#getPassword--) | Λαμβάνει τον κωδικό πρόσβασης για το άνοιγμα κρυπτογραφημένου αρχείου. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ορίζει τον κωδικό πρόσβασης για το άνοιγμα κρυπτογραφημένου αρχείου. |
| [getCharset()](#getCharset--) | Το charset που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου ή μηνυμάτων ηλεκτρονικού ταχυδρομείου όπως [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) και [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Το charset που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου ή μηνυμάτων ηλεκτρονικού ταχυδρομείου όπως [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) και [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG). |
| [isDetectCharset()](#isDetectCharset--) | Αυτή η επιλογή ενεργοποιεί την ανίχνευση charset για αρχεία [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) και [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Αυτή η επιλογή ενεργοποιεί την ανίχνευση charset για αρχεία [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) και [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Λαμβάνει το χρονικό όριο για τη φόρτωση εξωτερικών πόρων. |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Ορίζει το χρονικό όριο για τη φόρτωση εξωτερικών πόρων, όπως γραφικά. |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Λαμβάνει το χρονικό όριο σύνδεσης για τη δημιουργία ενός [Viewer](../../com.groupdocs.viewer/viewer) χρησιμοποιώντας java.net.URL για τη φόρτωση ενός εγγράφου. |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Ορίζει το χρονικό όριο σύνδεσης για τη δημιουργία ενός [Viewer](../../com.groupdocs.viewer/viewer) χρησιμοποιώντας java.net.URL για τη φόρτωση ενός εγγράφου. |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | Λαμβάνει το χρονικό όριο ανάγνωσης για τη δημιουργία ενός [Viewer](../../com.groupdocs.viewer/viewer) χρησιμοποιώντας java.net.URL για τη φόρτωση ενός εγγράφου. |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Ορίζει το χρονικό όριο ανάγνωσης για τη δημιουργία ενός [Viewer](../../com.groupdocs.viewer/viewer) χρησιμοποιώντας java.net.URL για τη φόρτωση ενός εγγράφου. |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Λαμβάνει τις επιλογές ασφαλείας για τον έλεγχο της διαδικασίας εξαγωγής αρχείων. |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Ορίζει τις επιλογές ασφαλείας για τον έλεγχο της διαδικασίας εξαγωγής αρχείων. |
| [isSkipExternalResources()](#isSkipExternalResources--) | Όταν οριστεί σε true, όλοι οι εξωτερικοί πόροι όπως οι εικόνες δεν θα φορτωθούν εκτός από \#getWhitelistedResources().getWhitelistedResources(). |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Όταν οριστεί σε true, όλοι οι εξωτερικοί πόροι όπως οι εικόνες δεν θα φορτωθούν εκτός από \#getWhitelistedResources().getWhitelistedResources(). |
| [getWhitelistedResources()](#getWhitelistedResources--) | Η λίστα των τμημάτων URL που αντιστοιχούν σε εξωτερικούς πόρους που πρέπει να φορτωθούν όταν \#isSkipExternalResources().isSkipExternalResources() ορίζεται σε `true`. |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | Ορίζει τη λίστα των τμημάτων URL που αντιστοιχούν σε εξωτερικούς πόρους που πρέπει να φορτωθούν όταν \#isSkipExternalResources().isSkipExternalResources() ορίζεται σε `true`. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  LoadOptions .

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  LoadOptions .

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου προς άνοιγμα. |

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### _tryRepair {#-tryRepair}
```
public boolean _tryRepair
```


### isTryRepair() {#isTryRepair--}
```
public boolean isTryRepair()
```


Όταν είναι ενεργοποιημένο, το GroupDocs.Viewer προσπαθεί να επισκευάσει τη δομική διαφθορά σε έγγραφα PDF. Η προεπιλεγμένη τιμή είναι false.

Αυτή η δυνατότητα αντιμετωπίζει τα ακόλουθα προβλήματα σε ένα έγγραφο PDF:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Όταν είναι ενεργοποιημένο, το GroupDocs.Viewer προσπαθεί να επισκευάσει τη δομική διαφθορά σε έγγραφα PDF. Η προεπιλεγμένη τιμή είναι false.

Αυτή η δυνατότητα αντιμετωπίζει τα ακόλουθα προβλήματα σε ένα έγγραφο PDF:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Λαμβάνει τον τύπο του αρχείου που θα ανοίξει.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Ορίζει τον τύπο του αρχείου που θα ανοίξει.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Λαμβάνει τον κωδικό πρόσβασης για το άνοιγμα κρυπτογραφημένου αρχείου.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String - ο κωδικός πρόσβασης για το άνοιγμα του αρχείου.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ορίζει τον κωδικό πρόσβασης για το άνοιγμα κρυπτογραφημένου αρχείου.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα του αρχείου. |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Το charset που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου ή μηνυμάτων ηλεκτρονικού ταχυδρομείου όπως [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) και [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

Η προεπιλεγμένη τιμή είναι java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


Το charset που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου ή μηνυμάτων ηλεκτρονικού ταχυδρομείου όπως [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) και [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG).

Η προεπιλεγμένη τιμή είναι java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Αυτή η επιλογή ενεργοποιεί την ανίχνευση κωδικοσελίδας αρχείων [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) και [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). Σε περίπτωση που η κωδικοσελίδα δεν μπορεί να ανιχνευθεί, χρησιμοποιείται η προεπιλεγμένη [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--).

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Αν η κωδικοποίηση δεν μπορεί να ανιχνευθεί, χρησιμοποιείται η προεπιλεγμένη. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Αυτή η επιλογή ενεργοποιεί την ανίχνευση κωδικοσελίδας αρχείων [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) και [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV). Σε περίπτωση που η κωδικοσελίδα δεν μπορεί να ανιχνευθεί, χρησιμοποιείται η προεπιλεγμένη [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--).

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Αν η κωδικοποίηση δεν μπορεί να ανιχνευθεί, χρησιμοποιείται η προεπιλεγμένη. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Λαμβάνει το χρονικό όριο για τη φόρτωση εξωτερικών πόρων.

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

Η προεπιλεγμένη τιμή είναι 30 δευτερόλεπτα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setResourceLoadingTimeout(5000); // Set resource loading timeout to 5 seconds

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Ορίζει το χρονικό όριο για τη φόρτωση εξωτερικών πόρων, όπως γραφικά.

***Note:** The default value is 30 seconds.*

Αυτή η επιλογή υποστηρίζεται για έγγραφα επεξεργασίας κειμένου που περιέχουν εξωτερικούς πόρους. Η προεπιλεγμένη τιμή είναι 30 δευτερόλεπτα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceLoadingTimeout | int | Το χρονικό όριο φόρτωσης, χιλιοστά του δευτερολέπτου. |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Λαμβάνει το χρονικό όριο σύνδεσης για τη δημιουργία ενός [Viewer](../../com.groupdocs.viewer/viewer) χρησιμοποιώντας java.net.URL για τη φόρτωση ενός εγγράφου.

***Note:** The default value is 5 seconds.*

**Returns:**
int - το χρονικό όριο σύνδεσης.
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Ορίζει το χρονικό όριο σύνδεσης για τη δημιουργία ενός [Viewer](../../com.groupdocs.viewer/viewer) χρησιμοποιώντας java.net.URL για τη φόρτωση ενός εγγράφου.

***Note:** The default value is 5 seconds.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| urlConnectTimeout | int | Το χρονικό όριο σύνδεσης. |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Λαμβάνει το χρονικό όριο ανάγνωσης για τη δημιουργία ενός [Viewer](../../com.groupdocs.viewer/viewer) χρησιμοποιώντας java.net.URL για τη φόρτωση ενός εγγράφου.

***Note:** The default value is 30 seconds.*

**Returns:**
int - το χρονικό όριο ανάγνωσης.
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Ορίζει το χρονικό όριο ανάγνωσης για τη δημιουργία ενός [Viewer](../../com.groupdocs.viewer/viewer) χρησιμοποιώντας java.net.URL για τη φόρτωση ενός εγγράφου.

***Note:** The default value is 30 seconds.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| urlReadTimeout | int | Το χρονικό όριο ανάγνωσης. |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Λαμβάνει τις επιλογές ασφαλείας για τον έλεγχο της διαδικασίας εξαγωγής αρχείων.

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - το αντικείμενο επιλογών για τη διαμόρφωση της διαδικασίας εξαγωγής αρχείων.
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Ορίζει τις επιλογές ασφαλείας για τον έλεγχο της διαδικασίας εξαγωγής αρχείων.

***Note:** Not each archive type supports all options.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Το αντικείμενο επιλογών για τη διαμόρφωση της διαδικασίας εξαγωγής αρχείων. |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Όταν οριστεί σε true, όλοι οι εξωτερικοί πόροι όπως οι εικόνες δεν θα φορτωθούν εκτός από \#getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Όταν οριστεί σε true, όλοι οι εξωτερικοί πόροι όπως οι εικόνες δεν θα φορτωθούν εκτός από \#getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| skipExternalResources | boolean | Η σημαία για την ενεργοποίηση ή απενεργοποίηση της φόρτωσης εξωτερικών πόρων. |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


Η λίστα των τμημάτων URL που αντιστοιχούν σε εξωτερικούς πόρους που πρέπει να φορτωθούν όταν \#isSkipExternalResources().isSkipExternalResources() ορίζεται σε `true`.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


Ορίζει τη λίστα των τμημάτων URL που αντιστοιχούν σε εξωτερικούς πόρους που πρέπει να φορτωθούν όταν \#isSkipExternalResources().isSkipExternalResources() ορίζεται σε `true`.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | Η λίστα των τμημάτων URL που αντιστοιχούν σε εξωτερικούς πόρους που πρέπει να φορτωθούν. |

