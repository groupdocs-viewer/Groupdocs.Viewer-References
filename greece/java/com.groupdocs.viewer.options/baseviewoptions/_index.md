---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Περιέχει τις βασικές επιλογές απόδοσης."
type: docs
weight: 12
url: /el/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Περιέχει τις βασικές επιλογές απόδοσης.


Το
BaseViewOptions
Η κλάση χρησιμεύει ως η βάση για τις επιλογές απόδοσης στο GroupDocs.Viewer.
Σας επιτρέπει να προσαρμόσετε τη συμπεριφορά απόδοσης των εξαγόμενων αρχείων HTML, PDF, PNG και JPEG κατά την απόδοση
συγκεκριμένες μορφές εγγράφων.


***Note:** For internal usage.*

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Ανακτά τις επιλογές για τη διαίρεση αρχείων κειμένου σε σελίδες. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Ορίζει τις επιλογές για τη διαίρεση αρχείων κειμένου σε σελίδες. |
|
|  | [isRenderComments()](#isRenderComments--) | Ενεργοποιεί την απόδοση σχολίων. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Ενεργοποιεί την απόδοση σχολίων. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Απενεργοποιεί την απόδοση σχολίων όταν ορίζεται σε true. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Απενεργοποιεί την απόδοση σχολίων όταν ορίζεται σε true. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Ενεργοποιεί την απόδοση σημειώσεων. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Ενεργοποιεί την απόδοση σημειώσεων. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Ενεργοποιεί την απόδοση κρυφών σελίδων. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Προεπιλεγμένη γραμματοσειρά που θα χρησιμοποιηθεί όταν δεν μπορεί να βρεθεί μια συγκεκριμένη γραμματοσειρά στο έγγραφο. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Προεπιλεγμένη γραμματοσειρά που θα χρησιμοποιηθεί όταν δεν μπορεί να βρεθεί μια συγκεκριμένη γραμματοσειρά στο έγγραφο. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Ανακτά τις επιλογές προβολής αρχείων αρχειοθέτησης. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Ορίζει τις επιλογές προβολής αρχείων αρχειοθέτησης. |
|
|  | [getCadOptions()](#getCadOptions--) | Ανακτά τις επιλογές προβολής σχεδίων CAD. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Ορίζει τις επιλογές προβολής σχεδίων CAD. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | Ανακτά τις επιλογές προβολής μηνυμάτων ηλεκτρονικού ταχυδρομείου. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Ορίζει τις επιλογές προβολής μηνυμάτων ηλεκτρονικού ταχυδρομείου. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | Ανακτά τις επιλογές προβολής αρχείων δεδομένων MS Outlook. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Ορίζει τις επιλογές προβολής αρχείων δεδομένων MS Outlook. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Ανακτά τις επιλογές προβολής εγγράφων PDF. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Ανακτά τις επιλογές προβολής εγγράφων PDF. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Ανακτά τις επιλογές προβολής αρχείων αποθήκευσης Lotus Notes. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Ορίζει τις επιλογές προβολής αρχείων αποθήκευσης Lotus Notes. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Ανακτά τις επιλογές προβολής αρχείων διαχείρισης έργου. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Ορίζει τις επιλογές προβολής αρχείων διαχείρισης έργου. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Ανακτά τις επιλογές προβολής των αρχείων λογιστικού φύλλου. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Ορίζει τις επιλογές προβολής των αρχείων λογιστικού φύλλου. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Οι επιλογές προβολής των αρχείων επεξεργασίας κειμένου. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Οι επιλογές προβολής των αρχείων επεξεργασίας κειμένου. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Ανακτά τις επιλογές απόδοσης για την επεξεργασία αρχείων Visio κατά την προβολή εγγράφων. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Ορίζει τις επιλογές απόδοσης για την επεξεργασία αρχείων Visio κατά την προβολή εγγράφων. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Ανακτά τις επιλογές προβολής για την επεξεργασία εγγράφων παρουσίασης. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Ορίζει τις επιλογές προβολής για την επεξεργασία εγγράφων παρουσίασης. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Λαμβάνει τις επιλογές απόδοσης που επιτρέπουν την προσαρμογή της εμφάνισης της εξόδου HTML/PDF/PNG/JPEG |
κατά την απόδοση εγγράφων Web.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Ορίζει τις επιλογές απόδοσης που επιτρέπουν την προσαρμογή της εμφάνισης της εξόδου HTML/PDF/PNG/JPEG |
κατά την απόδοση εγγράφων Web.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Ανακτά τις επιλογές για τη διαίρεση αρχείων κειμένου σε σελίδες.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Ορίζει τις επιλογές για τη διαίρεση αρχείων κειμένου σε σελίδες.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Οι επιλογές διαίρεσης αρχείων κειμένου. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Ενεργοποιεί την απόδοση σχολίων.


Από προεπιλογή, το GroupDocs.Viewer δεν αποδίδει σχόλια. Για να το κάνετε αυτό, ορίστε αυτήν την ιδιότητα σε true.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
boolean -  true  εάν πρέπει να αποδοθούν σχόλια,  false  διαφορετικά.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Ενεργοποιεί την απόδοση σχολίων.


Από προεπιλογή, το GroupDocs.Viewer δεν αποδίδει σχόλια. Για να το κάνετε αυτό, ορίστε αυτήν την ιδιότητα σε true.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  εάν πρέπει να αποδοθούν σχόλια,  false  διαφορετικά. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Απενεργοποιεί την απόδοση σχολίων όταν οριστεί σε true. Από προεπιλογή είναι false \\u2014 όλα τα σχόλια εμφανίζονται.


Ορισμένες μορφές εγγράφων όπως PDF και WordProcessing μπορεί να περιέχουν σχόλια. Από προεπιλογή το GroupDocs.Viewer τα αποδίδει. Με αυτήν την επιλογή ορισμένη σε true, τα σχόλια μπορεί να εξαιρεθούν από το τελικό έγγραφο.
Αυτή η επιλογή αντικαθιστά την παρωχημένη ιδιότητα 'RenderComments'.


**Returns:**
boolean -  true  εάν πρέπει να αποδοθούν σχόλια,  false  διαφορετικά.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Απενεργοποιεί την απόδοση σχολίων όταν οριστεί σε true. Από προεπιλογή είναι false \\u2014 όλα τα σχόλια εμφανίζονται.


Ορισμένες μορφές εγγράφων όπως PDF και WordProcessing μπορεί να περιέχουν σχόλια. Από προεπιλογή το GroupDocs.Viewer τα αποδίδει. Με αυτήν την επιλογή ορισμένη σε true, τα σχόλια μπορεί να εξαιρεθούν από το τελικό έγγραφο.
Αυτή η επιλογή αντικαθιστά την παρωχημένη ιδιότητα 'RenderComments'.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  εάν πρέπει να αποδοθούν σχόλια,  false  διαφορετικά. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Ενεργοποιεί την απόδοση σημειώσεων.


Ορισμένα αρχεία, όπως παρουσιάσεις ή αρχεία Microsoft Project, μπορεί να περιέχουν σημειώσεις. Από προεπιλογή, το GroupDocs.Viewer δεν αποδίδει σημειώσεις. Για να το κάνετε αυτό, ορίστε αυτήν την ιδιότητα σε true.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
boolean -  true  εάν πρέπει να αποδοθούν σημειώσεις,  false  διαφορετικά.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Ενεργοποιεί την απόδοση σημειώσεων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  εάν πρέπει να αποδοθούν σημειώσεις,  false  διαφορετικά. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Ενεργοποιεί την απόδοση κρυφών σελίδων.


Ορισμένα αρχεία, όπως παρουσιάσεις ή λογιστικά φύλλα, μπορεί να περιέχουν κρυφές σελίδες. Από προεπιλογή, το GroupDocs.Viewer δεν αποδίδει αυτές τις σελίδες. Για να το κάνετε αυτό, ορίστε αυτήν την ιδιότητα σε true.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
boolean -  true  αν οι κρυφές σελίδες πρέπει να αποδοθούν,  false  διαφορετικά.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Ενεργοποιεί την απόδοση κρυφών σελίδων.


Ορισμένα αρχεία, όπως παρουσιάσεις ή λογιστικά φύλλα, μπορεί να περιέχουν κρυφές σελίδες. Από προεπιλογή, το GroupDocs.Viewer δεν αποδίδει αυτές τις σελίδες. Για να το κάνετε αυτό, ορίστε αυτήν την ιδιότητα σε true.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  αν οι κρυφές σελίδες πρέπει να αποδοθούν,  false  διαφορετικά. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Προεπιλεγμένη γραμματοσειρά που θα χρησιμοποιηθεί όταν δεν μπορεί να βρεθεί μια συγκεκριμένη γραμματοσειρά στο έγγραφο.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο. Το GroupDocs.Viewer χρησιμοποιεί αυτή τη γραμματοσειρά κατά την απόδοση αντί για οποιεσδήποτε μη εγκατεστημένες γραμματοσειρές.
Για παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - το όνομα της προεπιλεγμένης γραμματοσειράς.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Προεπιλεγμένη γραμματοσειρά που θα χρησιμοποιηθεί όταν δεν μπορεί να βρεθεί μια συγκεκριμένη γραμματοσειρά στο έγγραφο.


Χρησιμοποιήστε αυτήν την ιδιότητα για να ορίσετε τη προεπιλεγμένη γραμματοσειρά για ένα έγγραφο. Το GroupDocs.Viewer χρησιμοποιεί αυτή τη γραμματοσειρά κατά την απόδοση αντί για οποιεσδήποτε μη εγκατεστημένες γραμματοσειρές.
Για παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το όνομα της προεπιλεγμένης γραμματοσειράς. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Ανακτά τις επιλογές προβολής αρχείων αρχειοθέτησης.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Ορίζει τις επιλογές προβολής αρχείων αρχειοθέτησης.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Οι επιλογές προβολής αρχείων αρχειοθέτησης. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Ανακτά τις επιλογές προβολής σχεδίων CAD.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε το [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) και το [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Ορίζει τις επιλογές προβολής σχεδίων CAD.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε το [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) και το [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | Οι επιλογές προβολής σχεδίου CAD. |
|

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


Ανακτά τις επιλογές προβολής μηνυμάτων ηλεκτρονικού ταχυδρομείου.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Ορίζει τις επιλογές προβολής μηνυμάτων ηλεκτρονικού ταχυδρομείου.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Οι επιλογές προβολής μηνυμάτων ηλεκτρονικού ταχυδρομείου. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Ανακτά τις επιλογές προβολής αρχείων δεδομένων MS Outlook.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Ορίζει τις επιλογές προβολής αρχείων δεδομένων MS Outlook.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Οι επιλογές προβολής αρχείων δεδομένων MS Outlook προς ρύθμιση. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Ανακτά τις επιλογές προβολής εγγράφων PDF.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Ανακτά τις επιλογές προβολής εγγράφων PDF.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | Οι επιλογές προβολής εγγράφων PDF. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Ανακτά τις επιλογές προβολής αρχείων αποθήκευσης Lotus Notes.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Ορίζει τις επιλογές προβολής αρχείων αποθήκευσης Lotus Notes.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Οι επιλογές προβολής αρχείων αποθήκευσης Lotus Notes. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Ανακτά τις επιλογές προβολής αρχείων διαχείρισης έργου.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Ορίζει τις επιλογές προβολής αρχείων διαχείρισης έργου.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Οι επιλογές προβολής αρχείων διαχείρισης έργου προς ρύθμιση. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Ανακτά τις επιλογές προβολής των αρχείων λογιστικού φύλλου.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε το [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), το [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), και το [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Ορίζει τις επιλογές προβολής των αρχείων λογιστικού φύλλου.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε το [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), το [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), και το [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Οι επιλογές προβολής αρχείων λογιστικού φύλλου. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Οι επιλογές προβολής των αρχείων επεξεργασίας κειμένου.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Οι επιλογές προβολής των αρχείων επεξεργασίας κειμένου.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Οι επιλογές επεξεργασίας κειμένου για την απόδοση εγγράφων Word. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Ανακτά τις επιλογές απόδοσης για την επεξεργασία αρχείων Visio κατά την προβολή εγγράφων.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Ορίζει τις επιλογές απόδοσης για την επεξεργασία αρχείων Visio κατά την προβολή εγγράφων.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Οι επιλογές απόδοσης Visio για την επεξεργασία αρχείων Visio. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Ανακτά τις επιλογές προβολής για την επεξεργασία εγγράφων παρουσίασης.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - οι επιλογές προβολής παρουσίασης για την επεξεργασία εγγράφων παρουσίασης.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Ορίζει τις επιλογές προβολής για την επεξεργασία εγγράφων παρουσίασης.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Οι επιλογές προβολής παρουσίασης για την επεξεργασία εγγράφων παρουσίασης. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Λαμβάνει τις επιλογές απόδοσης που επιτρέπουν την προσαρμογή της εμφάνισης της εξόδου HTML/PDF/PNG/JPEG
κατά την απόδοση εγγράφων Web.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - Το αντικείμενο WebDocumentOptions για την προσαρμογή των επιλογών απόδοσης.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Ορίζει τις επιλογές απόδοσης που επιτρέπουν την προσαρμογή της εμφάνισης της εξόδου HTML/PDF/PNG/JPEG
κατά την απόδοση εγγράφων Web.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | Το αντικείμενο WebDocumentOptions για την προσαρμογή των επιλογών απόδοσης. |
|

