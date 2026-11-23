---
title: "PdfOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση εγγράφων PDF."
type: docs
weight: 22
url: /el/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων PDF.


Η κλάση PdfOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν
για τον έλεγχο της απόδοσης εγγράφων PDF στο στοιχείο GroupDocs.Viewer.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Παράδειγμα χρήσης:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Αρχικοποιεί μια νέα παρουσία του |
PdfOptions
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Καθορίζει εάν το κείμενο από την πηγή αποδίδεται ως εικόνα σε HTML. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Ορίζει εάν το κείμενο από την πηγή αποδίδεται ως εικόνα σε HTML. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Ελέγχει εάν η ομαδοποίηση χαρακτήρων είναι απενεργοποιημένη για τη διατήρηση μέγιστης ακρίβειας κατά την τοποθέτηση χαρακτήρων όταν αποδίδεται η σελίδα. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Ορίζει την επιλογή για απενεργοποίηση της ομαδοποίησης χαρακτήρων, εξασφαλίζοντας μέγιστη ακρίβεια κατά την τοποθέτηση χαρακτήρων όταν αποδίδεται η σελίδα. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Ελέγχει εάν η απόδοση κειμένου και γραφικών πρέπει να ακολουθεί τη σειρά z στο αρχικό έγγραφο PDF όταν αποδίδεται σε HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Ενεργοποιεί ή απενεργοποιεί την απόδοση κειμένου και γραφικών σύμφωνα με τη σειρά z-order στο αρχικό έγγραφο PDF κατά την απόδοση σε HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Καθορίζει εάν η υποδείξη γραμματοσειράς είναι ενεργοποιημένη. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Ενεργοποιεί την υποδείξη γραμματοσειράς. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Ενεργοποιεί την απόδοση σελίδων με το ίδιο μέγεθος σε εικονοστοιχεία (pixels) όπως το μέγεθος της σελίδας στο πηγαίο έγγραφο PDF. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Ενεργοποιεί την απόδοση σελίδων με το ίδιο μέγεθος σε εικονοστοιχεία (pixels) όπως το μέγεθος της σελίδας στο πηγαίο έγγραφο PDF. |
|
|  | [getImageQuality()](#getImageQuality--) | Ανακτά την ποιότητα εξόδου εικόνας για πόρους εικόνας κατά την απόδοση σε HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Ορίζει την ποιότητα εξόδου εικόνας για πόρους εικόνας κατά την απόδοση σε HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | Το PDF είναι σταθερή μορφή, έτσι όλα τα στοιχεία έχουν συγκεκριμένη θέση σε μια σελίδα. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | Το PDF είναι σταθερή μορφή, έτσι όλα τα στοιχεία έχουν συγκεκριμένη θέση σε μια σελίδα. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Ενεργοποιήστε αυτήν την επιλογή για να τυλίξετε κάθε εικόνα στο τελικό έγγραφο HTML σε ετικέτα SVG ώστε να βελτιώσετε την ποιότητα εξόδου. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Ενεργοποιήστε αυτήν την επιλογή για να τυλίξετε κάθε εικόνα στο τελικό έγγραφο HTML σε ετικέτα SVG ώστε να βελτιώσετε την ποιότητα εξόδου. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Αντικαθιστά τις γραμματοσειρές όπως απαιτείται για να διασφαλιστεί ότι όλοι οι χαρακτήρες στο κείμενο μπορούν να εμφανιστούν. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Αντικαθιστά τις γραμματοσειρές όπως απαιτείται για να διασφαλιστεί ότι όλοι οι χαρακτήρες στο κείμενο μπορούν να εμφανιστούν. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Απενεργοποιεί τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Ορίστε τη σημαία για να απενεργοποιήσετε τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Αρχικοποιεί μια νέα παρουσία του
PdfOptions
κλάσης.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML.


Κατά την απόδοση αρχείων PDF με προστασία κατά της αντιγραφής κειμένου και εικόνων σε HTML, το GroupDocs.Viewer προσθέτει ένα 'inert' χαρακτηριστικό HTML στην ετικέτα BODY του HTML.
Η προεπιλεγμένη τιμή αυτής της επιλογής είναι
false
.


Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML.


Κατά την απόδοση αρχείων PDF με προστασία κατά της αντιγραφής κειμένου και εικόνων σε HTML, το GroupDocs.Viewer προσθέτει ένα 'inert' χαρακτηριστικό HTML στην ετικέτα BODY του HTML.
Η προεπιλεγμένη τιμή αυτής της επιλογής είναι
false
.


Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Καθορίζει εάν το κείμενο από την πηγή αποδίδεται ως εικόνα σε HTML.


Όταν αυτή η επιλογή οριστεί σε
true
, το κείμενο αποδίδεται ως εικόνα στο τελικό HTML.
Ενεργοποιήστε αυτήν την επιλογή για να κάνετε το κείμενο μη επιλέξιμο ή για να διορθώσετε την απόδοση χαρακτήρων και να κάνετε το HTML να μοιάζει με PDF.
Αυτή η επιλογή υποστηρίζεται κατά την απόδοση σε HTML.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  εάν το κείμενο αποδίδεται ως εικόνα σε HTML,  false  διαφορετικά.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Ορίζει εάν το κείμενο από την πηγή αποδίδεται ως εικόνα σε HTML.


Όταν αυτή η επιλογή οριστεί σε
true
, το κείμενο αποδίδεται ως εικόνα στο τελικό HTML.
Ενεργοποιήστε αυτήν την επιλογή για να κάνετε το κείμενο μη επιλέξιμο ή για να διορθώσετε την απόδοση χαρακτήρων και να κάνετε το HTML να μοιάζει με PDF.
Αυτή η επιλογή υποστηρίζεται κατά την απόδοση σε HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  για απόδοση του κειμένου ως εικόνα σε HTML,  false  διαφορετικά. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Ελέγχει εάν η ομαδοποίηση χαρακτήρων είναι απενεργοποιημένη για τη διατήρηση μέγιστης ακρίβειας κατά την τοποθέτηση χαρακτήρων όταν αποδίδεται η σελίδα.
Όταν αυτή η επιλογή είναι ενεργοποιημένη, οι χαρακτήρες αποδίδονται χωρίς καμία ομαδοποίηση, κάτι που εξασφαλίζει μέγιστη ακρίβεια.


***Note:** By default, character grouping is enabled.*
Κατά τη μετατροπή αρχείων PDF, το GroupDocs.Viewer ομαδοποιεί μεμονωμένους χαρακτήρες σε λέξεις για βελτιωμένη απόδοση. Εάν το έγγραφό σας περιλαμβάνει ιερογλυφικά ή ειδικά σύμβολα, ίσως θέλετε να απαγορεύσετε την ομαδοποίηση χαρακτήρων ώστε να εξασφαλίσετε πιο ακριβή διάταξη. Η προεπιλεγμένη τιμή είναι false.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean -  true  εάν η ομαδοποίηση χαρακτήρων είναι απενεργοποιημένη,  false  διαφορετικά.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Ορίζει την επιλογή για απενεργοποίηση της ομαδοποίησης χαρακτήρων, εξασφαλίζοντας μέγιστη ακρίβεια κατά την τοποθέτηση χαρακτήρων όταν αποδίδεται η σελίδα.
Όταν αυτή η επιλογή ενεργοποιείται ορίζοντας την τιμή σε
true
, η ομαδοποίηση χαρακτήρων είναι απενεργοποιημένη, κάτι που εξασφαλίζει μέγιστη ακρίβεια.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
Κατά τη μετατροπή αρχείων PDF, το GroupDocs.Viewer ομαδοποιεί μεμονωμένους χαρακτήρες σε λέξεις για βελτιωμένη απόδοση. Εάν το έγγραφό σας περιλαμβάνει ιερογλυφικά ή ειδικά σύμβολα, ίσως θέλετε να απαγορεύσετε την ομαδοποίηση χαρακτήρων ώστε να εξασφαλίσετε πιο ακριβή διάταξη. Η προεπιλεγμένη τιμή είναι false.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  για απενεργοποίηση της ομαδοποίησης χαρακτήρων,  false  για ενεργοποίησή της. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Ελέγχει εάν η απόδοση κειμένου και γραφικών πρέπει να ακολουθεί τη σειρά z στο αρχικό έγγραφο PDF όταν αποδίδεται σε HTML.
Όταν αυτή η επιλογή ενεργοποιείται επιστρέφοντας
true
, το κείμενο και τα γραφικά αποδίδονται σύμφωνα με τη σειρά z τους στο αρχικό έγγραφο PDF.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Από προεπιλογή, το GroupDocs.Veiewer αποδίδει το κείμενο και τα γραφικά ως ένα ενιαίο στρώμα σε HTML. Αυτή η επιλογή σας επιτρέπει να διατάξετε τα αντικείμενα στην ίδια σειρά με το αρχείο προέλευσης. Η προεπιλεγμένη τιμή είναι false.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean -  true  εάν η πολυεπίπεδη απόδοση είναι ενεργοποιημένη,  false  διαφορετικά.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Ενεργοποιεί ή απενεργοποιεί την απόδοση κειμένου και γραφικών σύμφωνα με τη σειρά z-order στο αρχικό έγγραφο PDF κατά την απόδοση σε HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Από προεπιλογή, το GroupDocs.Veiewer αποδίδει το κείμενο και τα γραφικά ως ένα ενιαίο στρώμα σε HTML. Αυτή η επιλογή σας επιτρέπει να διατάξετε τα αντικείμενα στην ίδια σειρά με το αρχείο προέλευσης. Η προεπιλεγμένη τιμή είναι false.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  για ενεργοποίηση της πολυεπίπεδης απόδοσης,  false  για απενεργοποίησή της. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Καθορίζει αν η υποδείξη γραμματοσειράς είναι ενεργοποιημένη. Η υποδείξη γραμματοσειράς προσαρμόζει την εμφάνιση μιας γραμματοσειράς περιγράμματος.
Αυτή η επιλογή υποστηρίζεται μόνο για γραμματοσειρές TrueType (TTF) όταν χρησιμοποιείται στο έγγραφο προέλευσης.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Η υποδείξη γραμματοσειράς προσαρμόζει τον τρόπο εμφάνισης μιας γραμματοσειράς περιγράμματος. Ισχύει μόνο για γραμματοσειρές TTF που χρησιμοποιούνται στο έγγραφο προέλευσης. Αυτή η επιλογή είναι διαθέσιμη για απόδοση σε μορφές PNG ή JPG. Η προεπιλεγμένη τιμή είναι false.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean -  true  εάν η υποδείξη γραμματοσειράς είναι ενεργοποιημένη,  false  διαφορετικά.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Ενεργοποιεί την υποδείξη γραμματοσειράς. Η υποδείξη γραμματοσειράς προσαρμόζει την εμφάνιση μιας γραμματοσειράς περιγράμματος και υποστηρίζεται μόνο για γραμματοσειρές TrueType (TTF) όταν χρησιμοποιείται στο έγγραφο προέλευσης.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Η υποδείξη γραμματοσειράς προσαρμόζει τον τρόπο εμφάνισης μιας γραμματοσειράς περιγράμματος. Ισχύει μόνο για γραμματοσειρές TTF που χρησιμοποιούνται στο έγγραφο προέλευσης. Αυτή η επιλογή είναι διαθέσιμη για απόδοση σε μορφές PNG ή JPG. Η προεπιλεγμένη τιμή είναι false.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  για ενεργοποίηση της υποδείξης γραμματοσειράς,  false  για απενεργοποίησή της. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Ενεργοποιεί την απόδοση σελίδων με το ίδιο μέγεθος σε εικονοστοιχεία (pixels) όπως το μέγεθος της σελίδας στο πηγαίο έγγραφο PDF.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Από προεπιλογή, το GroupDocs.Viewer υπολογίζει το μέγεθος σελίδας της εξόδου εικόνας για καλύτερη ποιότητα απόδοσης. Ενεργοποιήστε αυτήν την επιλογή για να διασφαλίσετε ότι οι σελίδες εξόδου έχουν το ίδιο μέγεθος με το μέγεθος σελίδας του πηγαίου εγγράφου PDF (σε εικονοστοιχεία). Η προεπιλεγμένη τιμή είναι false.
Αυτή η επιλογή είναι διαθέσιμη για απόδοση σε μορφές PNG ή JPG.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean -  true  εάν η επιλογή είναι ενεργοποιημένη,  false  διαφορετικά.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Ενεργοποιεί την απόδοση σελίδων με το ίδιο μέγεθος σε εικονοστοιχεία (pixels) όπως το μέγεθος της σελίδας στο πηγαίο έγγραφο PDF.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Από προεπιλογή, το GroupDocs.Viewer υπολογίζει το μέγεθος σελίδας της εξόδου εικόνας για καλύτερη ποιότητα απόδοσης. Ενεργοποιήστε αυτήν την επιλογή για να διασφαλίσετε ότι οι σελίδες εξόδου έχουν το ίδιο μέγεθος με το μέγεθος σελίδας του πηγαίου εγγράφου PDF (σε εικονοστοιχεία). Η προεπιλεγμένη τιμή είναι false.
Αυτή η επιλογή είναι διαθέσιμη για απόδοση σε μορφές PNG ή JPG.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  για να ενεργοποιήσετε την απόδοση με το αρχικό μέγεθος σελίδας,  false  αλλιώς. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Ανακτά την ποιότητα εικόνας εξόδου για πόρους εικόνας κατά την απόδοση σε HTML. Η προεπιλεγμένη τιμή είναι Low.


Όταν αυτή η επιλογή οριστεί σε true, το GroupDocs.Viewer αποδίδει το κείμενο ως εικόνα στην έξοδο HTML. Αυτό καθιστά το κείμενο μη επιλέξιμο και βελτιώνει την απόδοση των χαρακτήρων, εξασφαλίζοντας εμφάνιση παρόμοια με PDF στο HTML. Η προεπιλεγμένη τιμή είναι false.
Αυτή η επιλογή είναι διαθέσιμη για απόδοση σε HTML.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Ορίζει την ποιότητα εικόνας εξόδου για πόρους εικόνας κατά την απόδοση σε HTML. Η προεπιλεγμένη τιμή είναι Low.


Όταν αυτή η επιλογή οριστεί σε true, το GroupDocs.Viewer αποδίδει το κείμενο ως εικόνα στην έξοδο HTML. Αυτό καθιστά το κείμενο μη επιλέξιμο και βελτιώνει την απόδοση των χαρακτήρων, εξασφαλίζοντας εμφάνιση παρόμοια με PDF στο HTML. Η προεπιλεγμένη τιμή είναι false.
Αυτή η επιλογή είναι διαθέσιμη για απόδοση σε HTML.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Η ποιότητα εικόνας εξόδου για πόρους εικόνας κατά την απόδοση σε HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


Το PDF είναι σταθερή μορφή, έτσι όλα τα στοιχεία έχουν συγκεκριμένη θέση σε μια σελίδα.
Για να διασφαλιστεί ότι το παραγόμενο HTML φαίνεται το ίδιο με το αρχικό PDF, τα έγγραφα αποδίδονται σε HTML με στατική διάταξη από προεπιλογή.
Κατά την απόδοση με στατική διάταξη, το παραγόμενο HTML έχει στατικό μέγεθος ώστε τα στοιχεία να παραμένουν στην ίδια θέση ανεξάρτητα από το μέγεθος του παραθύρου.
Για απόδοση σε HTML με ρευστή διάταξη, ορίστε αυτήν την ιδιότητα σε false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
Τα έγγραφα PDF και EPUB αρχικά αποδίδονται σε HTML με στατική διάταξη για να διατηρηθεί η εμφάνιση του αρχικού εγγράφου. Αυτή η στατική διάταξη σημαίνει ότι όλα τα στοιχεία HTML έχουν ακριβείς θέσεις μέσα σε ένα κοντέινερ με καθορισμένο μέγεθος. Η αλλαγή μεγέθους του παραθύρου του προγράμματος περιήγησης δεν επηρεάζει τη θέση και το μέγεθος των στοιχείων στο έγγραφο.
Αυτή η επιλογή είναι διαθέσιμη μόνο κατά την απόδοση σε HTML. Η προεπιλεγμένη τιμή είναι true. Για απόδοση με ρευστή διάταξη, ορίστε αυτήν την ιδιότητα σε false.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - true εάν είναι στατική διάταξη

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


Το PDF είναι σταθερή μορφή, έτσι όλα τα στοιχεία έχουν συγκεκριμένη θέση σε μια σελίδα.
Για να διασφαλιστεί ότι το παραγόμενο HTML φαίνεται το ίδιο με το αρχικό PDF, τα έγγραφα αποδίδονται σε HTML με στατική διάταξη από προεπιλογή.
Κατά την απόδοση με στατική διάταξη, το παραγόμενο HTML έχει στατικό μέγεθος ώστε τα στοιχεία να παραμένουν στην ίδια θέση ανεξάρτητα από το μέγεθος του παραθύρου.
Για απόδοση σε HTML με ρευστή διάταξη, ορίστε αυτήν την ιδιότητα σε false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
Τα έγγραφα PDF και EPUB αρχικά αποδίδονται σε HTML με στατική διάταξη για να διατηρηθεί η εμφάνιση του αρχικού εγγράφου. Αυτή η στατική διάταξη σημαίνει ότι όλα τα στοιχεία HTML έχουν ακριβείς θέσεις μέσα σε ένα κοντέινερ με καθορισμένο μέγεθος. Η αλλαγή μεγέθους του παραθύρου του προγράμματος περιήγησης δεν επηρεάζει τη θέση και το μέγεθος των στοιχείων στο έγγραφο.
Αυτή η επιλογή είναι διαθέσιμη μόνο κατά την απόδοση σε HTML. Η προεπιλεγμένη τιμή είναι true. Για απόδοση με ρευστή διάταξη, ορίστε αυτήν την ιδιότητα σε false.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fixedLayout | boolean | true εάν είναι στατική διάταξη |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Ενεργοποιήστε αυτήν την επιλογή για να τυλίξετε κάθε εικόνα στο τελικό έγγραφο HTML σε ετικέτα SVG ώστε να βελτιώσετε την ποιότητα εξόδου.


Αυτή η επιλογή υποστηρίζεται όταν αποδίδεται [PDF and Page Layout file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) σε HTML με ενσωματωμένους και εξωτερικούς πόρους.


Από προεπιλογή, όταν αποδίδεται σε αρχεία PDF και Page Layout, όλες οι εικόνες αποδίδονται ως μία εικόνα PNG. Η παραγόμενη εικόνα PNG χρησιμοποιείται ως φόντο για το έγγραφο HTML εξόδου.


Μάθετε περισσότερα:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  true  εάν οι εικόνες είναι τυλιγμένες σε SVG,  false  αλλιώς.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Ενεργοποιήστε αυτήν την επιλογή για να τυλίξετε κάθε εικόνα στο τελικό έγγραφο HTML σε ετικέτα SVG ώστε να βελτιώσετε την ποιότητα εξόδου.


Αυτή η επιλογή υποστηρίζεται όταν αποδίδεται [PDF and Page Layout file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) σε HTML με ενσωματωμένους και εξωτερικούς πόρους.


Από προεπιλογή, όταν αποδίδεται σε αρχεία PDF και Page Layout, όλες οι εικόνες αποδίδονται ως μία εικόνα PNG. Η παραγόμενη εικόνα PNG χρησιμοποιείται ως φόντο για το έγγραφο HTML εξόδου.


Μάθετε περισσότερα:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  εάν οι εικόνες πρέπει να τυλιχθούν σε SVG,  false  αλλιώς. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Αντικαθιστά τις γραμματοσειρές όπως απαιτείται για να διασφαλιστεί ότι όλοι οι χαρακτήρες στο κείμενο μπορούν να εμφανιστούν.


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Αντικαθιστά τις γραμματοσειρές όπως απαιτείται για να διασφαλιστεί ότι όλοι οι χαρακτήρες στο κείμενο μπορούν να εμφανιστούν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | analyzeFonts | boolean | true εάν οι γραμματοσειρές πρέπει να εμφανιστούν, false αλλιώς |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Απενεργοποιεί τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS.


Πολλές λειτουργίες με τη γραμματοσειρά δεν μπορούν να εκτελεστούν εάν αυτές οι λειτουργίες απαγορεύονται από την άδεια αυτής της γραμματοσειράς.
Για παράδειγμα, ορισμένες γραμματοσειρές δεν μπορούν να ενσωματωθούν σε ένα έγγραφο PDF εάν οι κανόνες άδειας απενεργοποιούν την ενσωμάτωση για αυτή τη γραμματοσειρά.
Να είστε προσεκτικοί όταν χρησιμοποιείτε αυτή τη σημαία. Όταν ορίζεται, σημαίνει ότι το άτομο που τη θέτει αναλαμβάνει όλη την ευθύνη
για πιθανές παραβιάσεις άδειας/νόμου από τον εαυτό τους. Έτσι το αναλαμβάνουν με δικό τους ρίσκο. Συνιστάται έντονα να χρησιμοποιείτε
αυτή τη σημαία μόνο όταν είστε πλήρως βέβαιοι ότι δεν παραβιάζετε το νόμο περί πνευματικών δικαιωμάτων. Από προεπιλογή είναι ψευδής.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Ορίστε τη σημαία για να απενεργοποιήσετε τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS.


Πολλές λειτουργίες με τη γραμματοσειρά δεν μπορούν να εκτελεστούν εάν αυτές οι λειτουργίες απαγορεύονται από την άδεια αυτής της γραμματοσειράς.
Για παράδειγμα, ορισμένες γραμματοσειρές δεν μπορούν να ενσωματωθούν σε ένα έγγραφο PDF εάν οι κανόνες άδειας απενεργοποιούν την ενσωμάτωση για αυτή τη γραμματοσειρά.
Να είστε προσεκτικοί όταν χρησιμοποιείτε αυτή τη σημαία. Όταν ορίζεται, σημαίνει ότι το άτομο που τη θέτει αναλαμβάνει όλη την ευθύνη
για πιθανές παραβιάσεις άδειας/νόμου από τον εαυτό τους. Έτσι το αναλαμβάνουν με δικό τους ρίσκο. Συνιστάται έντονα να χρησιμοποιείτε
αυτή τη σημαία μόνο όταν είστε πλήρως βέβαιοι ότι δεν παραβιάζετε το νόμο περί πνευματικών δικαιωμάτων. Από προεπιλογή είναι ψευδής.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

