---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Χρησιμοποιήστε αυτήν την κλάση για να καθορίσετε επιλογές βελτιστοποίησης PDF που θα εφαρμοστούν στο αρχείο PDF εξόδου."
type: docs
weight: 21
url: /el/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Χρησιμοποιήστε αυτήν την κλάση για να καθορίσετε επιλογές βελτιστοποίησης PDF που θα εφαρμοστούν στο αρχείο PDF εξόδου.

Αυτές οι επιλογές βελτιστοποίησης υποστηρίζονται για οποιεσδήποτε μορφές αρχείων εισόδου που υποστηρίζονται για εξαγωγή σε PDF. Για λεπτομέρειες και παραδείγματα κώδικα, δείτε αυτή τη [page][] και τα υποστοιχεία της.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Ορίζει τις προεπιλεγμένες τιμές της επιλογής MaxResolution σε 300 και της επιλογής ImageQuality σε 100. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isLinearize()](#isLinearize--) | Επιτρέπει τη βελτιστοποίηση του εξαγόμενου αρχείου PDF για προβολή online με έναν web browser. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Ορίζει αν θα βελτιστοποιηθεί το εξαγόμενο PDF για περιήγηση online με έναν web browser. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Οι σημειώσεις μπορούν να διαγραφούν όταν δεν είναι απαραίτητες. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Ορίζει αν θα αφαιρεθούν οι περιττές σημειώσεις από το PDF. |
| [isRemoveFormFields()](#isRemoveFormFields--) | Εάν το έγγραφο PDF περιέχει AcroForms, μπορούμε να προσπαθήσουμε να μειώσουμε το μέγεθος του αρχείου επίπεδοντας τα πεδία φόρμας. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Ορίζει αν θα αφαιρεθούν τα πεδία φόρμας από το PDF. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | Το αρχείο PDF αποτελείται από Κείμενο, Εικόνα, Συνημμένο, Σημειώσεις, Γραφήματα και άλλα αντικείμενα. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Ορίζει αν θα μετατραπεί το PDF σε αποχρώσεις του γκρι. |
| [isSubsetFonts()](#isSubsetFonts--) | Κάθε γραμματοσειρά που χρησιμοποιείται για την εμφάνιση κειμένου στη σελίδα περιέχει σύνολο γλύφων για τους χαρακτήρες της γραμματοσειράς. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Ορίζει αν θα γίνει υποσύνολο των γραμματοσειρών στο PDF. |
| [isCompressImages()](#isCompressImages--) | Εάν το πηγαίο αρχείο PDF περιέχει εικόνες, σκεφτείτε τη συμπίεση των εικόνων και τον καθορισμό της ποιότητάς τους. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Ορίζει αν θα συμπιεστούν οι εικόνες στο PDF. |
| [getImageQuality()](#getImageQuality--) | Εάν το πηγαίο αρχείο PDF περιέχει εικόνες, σκεφτείτε τη συμπίεση των εικόνων και τον καθορισμό της ποιότητάς τους. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | Ορίζει την ποιότητα εικόνας για τη συμπίεση των εικόνων στο PDF. |
| [isResizeImages()](#isResizeImages--) | Μπορεί να χρησιμοποιηθεί με την επιλογή CompressImages για αλλαγή μεγέθους των εικόνων με χαμηλότερη ανάλυση. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Ορίζει αν θα αλλάξει το μέγεθος των εικόνων στο PDF. |
| [getMaxResolution()](#getMaxResolution--) | Μπορεί να χρησιμοποιηθεί με την επιλογή CompressImages για αλλαγή μεγέθους των εικόνων με χαμηλότερη ανάλυση. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Ορίζει τη μέγιστη ανάλυση για την αλλαγή μεγέθους των εικόνων στο PDF. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Βελτιστοποιήστε τις γραμμές περιγράμματος και τις γραμματοσειρές των λογιστικών φύλλων Excel για μικρότερο μέγεθος εξαγόμενου αρχείου. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Ορίζει αν θα βελτιστοποιηθούν τα λογιστικά φύλλα στο PDF. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Αφαιρέστε τις ιδιωτικές πληροφορίες (πληροφορίες τμήματος σελίδας) εάν οριστεί σε true. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Ορίζει αν θα αφαιρεθούν οι ιδιωτικές πληροφορίες από το PDF. |
| [isUnembedFonts()](#isUnembedFonts--) | Εάν το έγγραφο χρησιμοποιεί ενσωματωμένες γραμματοσειρές, σημαίνει ότι όλα τα δεδομένα γραμματοσειράς τοποθετούνται στο έγγραφο. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Ορίζει αν θα αφαιρεθεί η ενσωμάτωση των ενσωματωμένων γραμματοσειρών στο PDF. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Μερικές φορές ένα έγγραφο περιέχει πολλαπλές πανομοιότυπες ροές πόρων (για παράδειγμα εικόνες). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Ορίζει αν θα συνδεθούν οι διπλότυπες ροές στο PDF. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | Εάν αυτή η ιδιότητα οριστεί σε true, το περιεχόμενο της σελίδας θα επαναχρησιμοποιηθεί κατά τη βελτιστοποίηση του εγγράφου για πανομοιότυπες σελίδες. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Ορίζει αν επιτρέπεται η επαναχρησιμοποίηση του περιεχομένου της σελίδας στο PDF. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Μερικές φορές ένα έγγραφο περιέχει αχρησιμοποίητες ροές πόρων. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Ορίζει αν θα αφαιρεθούν οι αχρησιμοποίητες ροές από το PDF. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Ένα έγγραφο PDF μερικές φορές περιέχει αντικείμενα PDF που δεν αναφέρονται από κανένα άλλο αντικείμενο στο έγγραφο. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Ορίζει αν θα αφαιρεθούν τα αχρησιμοποίητα αντικείμενα από το PDF. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Ορίζει τις προεπιλεγμένες τιμές της επιλογής MaxResolution σε 300 και της επιλογής ImageQuality σε 100.

Για λεπτομέρειες και παραδείγματα κώδικα, δείτε αυτή τη [page][] και τα θυγατρικά της.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Επιτρέπει τη βελτιστοποίηση του εξαγόμενου αρχείου PDF για προβολή online με έναν web browser.

Για παράδειγμα κώδικα, δείτε αυτή τη [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  εάν το εξαγόμενο PDF είναι βελτιστοποιημένο για διαδικτυακή περιήγηση,  false  διαφορετικά.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Ορίζει αν θα βελτιστοποιηθεί το εξαγόμενο PDF για περιήγηση online με έναν web browser.

Για παράδειγμα κώδικα, δείτε αυτή τη [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| linearize | boolean | true  για βελτιστοποίηση του εξαγόμενου PDF για διαδικτυακή περιήγηση,  false  διαφορετικά. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Οι σημειώσεις μπορούν να διαγραφούν όταν είναι περιττές. Όταν χρειάζονται αλλά δεν απαιτούν πρόσθετη επεξεργασία, μπορούν να ισοπεδωθούν. Αυτό θα μειώσει το μέγεθος του αρχείου.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  εάν οι σημειώσεις αφαιρεθούν,  false  διαφορετικά.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Ορίζει αν θα αφαιρεθούν οι περιττές σημειώσεις από το PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| removeAnnotations | boolean | true  για αφαίρεση περιττών σημειώσεων,  false  διαφορετικά. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Εάν το έγγραφο PDF περιέχει AcroForms, μπορούμε να προσπαθήσουμε να μειώσουμε το μέγεθος του αρχείου επίπεδοντας τα πεδία φόρμας.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  εάν τα πεδία φόρμας αφαιρεθούν,  false  διαφορετικά.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Ορίζει αν θα αφαιρεθούν τα πεδία φόρμας από το PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| removeFormFields | boolean | true  για αφαίρεση πεδίων φόρμας,  false  διαφορετικά. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


Το αρχείο PDF αποτελείται από Κείμενο, Εικόνα, Συνημμένο, Σημειώσεις, Γραφήματα και άλλα αντικείμενα. Μπορεί να αντιμετωπίσετε την ανάγκη να μετατρέψετε ένα PDF από χρωματικό χώρο RGB σε κλίμακα του γκρι ώστε να είναι πιο γρήγορο κατά την εκτύπωση αυτών των αρχείων PDF. Επίσης, όταν το αρχείο μετατραπεί σε κλίμακα του γκρι, το μέγεθος του εγγράφου μειώνεται, αλλά με αυτήν την αλλαγή η ποιότητα του εγγράφου μπορεί να υποχωρήσει. Προς το παρόν, αυτή η δυνατότητα υποστηρίζεται από τη λειτουργία Pre‑Flight του Adobe Acrobat.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  εάν το PDF μετατραπεί σε κλίμακα του γκρι,  false  διαφορετικά.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Ορίζει αν θα μετατραπεί το PDF σε αποχρώσεις του γκρι.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| convertToGrayScale | boolean | true  για μετατροπή του PDF σε κλίμακα του γκρι,  false  διαφορετικά. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Κάθε γραμματοσειρά που χρησιμοποιείται για την εμφάνιση κειμένου στη σελίδα περιέχει σύνολο γλύφων για τους χαρακτήρες της γραμματοσειράς. Η προδιαγραφή PDF υποστηρίζει το "font subset", δηλαδή γραμματοσειρά μόνο με εκείνους τους γλύφους που χρησιμοποιούνται. Αυτό μπορεί να προκαλέσει προβλήματα όταν το κείμενο πρέπει να ενημερωθεί (εφόσον οι απαιτούμενοι γλύφοι λείπουν από τη γραμματοσειρά), αλλά για το έγγραφο που δεν προγραμματίζεται να αλλάξει, αυτό επιτρέπει τη μείωση του μεγέθους.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  εάν οι γραμματοσειρές είναι υποσύνολο,  false  διαφορετικά.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Ορίζει αν θα γίνει υποσύνολο των γραμματοσειρών στο PDF.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subsetFonts | boolean | true  για υποσύνολο των γραμματοσειρών,  false  διαφορετικά. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Εάν το αρχείο PDF προέλευσης περιέχει εικόνες, σκεφτείτε τη συμπίεση των εικόνων και τον καθορισμό της ποιότητάς τους. Για να ενεργοποιήσετε τη συμπίεση εικόνων, ορίστε αυτήν την επιλογή σε true. Όλες οι εικόνες σε ένα έγγραφο θα ξανασυμπιεστούν. Η συμπίεση ορίζεται από την ιδιότητα ImageQuality, η οποία είναι η τιμή της ποιότητας σε ποσοστό. Το 100% είναι αμετάβλητη ποιότητα. Για να μειώσετε την ποιότητα της εικόνας, ορίστε την ιδιότητα ImageQuality μικρότερη από 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  εάν οι εικόνες είναι συμπιεσμένες,  false  διαφορετικά.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Ορίζει αν θα συμπιεστούν οι εικόνες στο PDF.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| compressImages | boolean | true  για τη συμπίεση των εικόνων,  false  διαφορετικά. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Εάν το αρχείο PDF προέλευσης περιέχει εικόνες, σκεφτείτε τη συμπίεση των εικόνων και τον καθορισμό της ποιότητάς τους. Για να ενεργοποιήσετε τη συμπίεση εικόνων, ορίστε την επιλογή CompressImages σε true. Όλες οι εικόνες σε ένα έγγραφο θα ξανασυμπιεστούν. Η συμπίεση ορίζεται από την ιδιότητα ImageQuality, η οποία είναι η τιμή της ποιότητας σε ποσοστό. Το 100% είναι αμετάβλητη ποιότητα. Για να μειώσετε την ποιότητα της εικόνας, ορίστε την επιλογή CompressImages σε true και την ιδιότητα ImageQuality μικρότερη από 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - η ποιότητα της εικόνας (τιμή μεταξύ 1 και 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Ορίζει την ποιότητα εικόνας για τη συμπίεση των εικόνων στο PDF.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| imageQuality | int | η ποιότητα της εικόνας (τιμή μεταξύ 1 και 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Μπορεί να χρησιμοποιηθεί με την επιλογή CompressImages για αλλαγή μεγέθους των εικόνων με χαμηλότερη ανάλυση. Σε αυτήν την περίπτωση, πρέπει να ορίσουμε CompressImage σε true, ResizeImages σε true και MaxResolution στην κατάλληλη τιμή.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  εάν οι εικόνες έχουν αλλάξει μέγεθος,  false  διαφορετικά.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Ορίζει αν θα αλλάξει το μέγεθος των εικόνων στο PDF.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resizeImages | boolean | true  για αλλαγή μεγέθους των εικόνων,  false  διαφορετικά. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Μπορεί να χρησιμοποιηθεί με την επιλογή CompressImages για αλλαγή μεγέθους των εικόνων με χαμηλότερη ανάλυση. Σε αυτήν την περίπτωση, πρέπει να ορίσουμε CompressImage σε true, ResizeImages σε true και MaxResolution στην κατάλληλη τιμή.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - η μέγιστη ανάλυση για τις εικόνες.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Ορίζει τη μέγιστη ανάλυση για την αλλαγή μεγέθους των εικόνων στο PDF.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxResolution | int | η μέγιστη ανάλυση για τις εικόνες. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Βελτιστοποιήστε τις γραμμές περιγράμματος και τις γραμματοσειρές των λογιστικών φύλλων Excel για μικρότερο μέγεθος εξαγόμενου αρχείου.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  εάν τα φύλλα εργασίας βελτιστοποιούνται,  false  διαφορετικά.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Ορίζει αν θα βελτιστοποιηθούν τα λογιστικά φύλλα στο PDF.

Για παράδειγμα κώδικα, δείτε αυτή τη [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  για βελτιστοποίηση των φύλλων εργασίας,  false  διαφορετικά. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Αφαιρέστε τις ιδιωτικές πληροφορίες (πληροφορίες τμήματος σελίδας) εάν οριστεί σε true.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  εάν αφαιρούνται προσωπικές πληροφορίες,  false  διαφορετικά.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Ορίζει αν θα αφαιρεθούν οι ιδιωτικές πληροφορίες από το PDF.

***Note:** The default value is  false .*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| removePrivateInfo | boolean | true  για αφαίρεση προσωπικών πληροφοριών,  false  διαφορετικά. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Εάν το έγγραφο χρησιμοποιεί ενσωματωμένες γραμματοσειρές, σημαίνει ότι όλα τα δεδομένα γραμματοσειράς τοποθετούνται στο έγγραφο. Το πλεονέκτημα είναι ότι το έγγραφο είναι προβλέψιμο ανεξάρτητα από το αν η γραμματοσειρά είναι εγκατεστημένη στο μηχάνημα του χρήστη\\u2019s ή όχι. Αλλά η ενσωμάτωση γραμματοσειρών κάνει το έγγραφο μεγαλύτερο. Η μέθοδος unembed fonts αφαιρεί όλες τις ενσωματωμένες γραμματοσειρές. Αυτό μειώνει το μέγεθος του εγγράφου, αλλά το έγγραφο μπορεί να γίνει μη αναγνώσιμο εάν η σωστή γραμματοσειρά δεν είναι εγκατεστημένη.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  εάν οι ενσωματωμένες γραμματοσειρές έχουν αφαιρεθεί,  false  διαφορετικά.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Ορίζει αν θα αφαιρεθεί η ενσωμάτωση των ενσωματωμένων γραμματοσειρών στο PDF.

***Note:** The default value is  false .*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| unembedFonts | boolean | true  για αφαίρεση των ενσωματωμένων γραμματοσειρών,  false  διαφορετικά. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Μερικές φορές ένα έγγραφο περιέχει αρκετές πανομοιότυπες ροές πόρων (για παράδειγμα εικόνες). Αυτό μπορεί να συμβεί, για παράδειγμα, όταν ένα έγγραφο συνενώεται με τον εαυτό του. Το έγγραφο εξόδου περιέχει δύο ανεξάρτητα αντίγραφα της ίδιας ροής πόρων. Αναλύουμε όλες τις ροές πόρων και τις συγκρίνουμε. Εάν οι ροές είναι διπλότυπες, συγχωνεύονται, δηλαδή μένει μόνο ένα αντίγραφο, οι αναφορές αλλάζουν αναλόγως και τα αντίγραφα του αντικειμένου αφαιρούνται. Μερικές φορές αυτό μειώνει το μέγεθος του εγγράφου.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  εάν οι διπλότυπες ροές είναι συνδεδεμένες,  false  διαφορετικά.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Ορίζει αν θα συνδεθούν οι διπλότυπες ροές στο PDF.

***Note:** The default value is  false .*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  για σύνδεση διπλότυπων ροών,  false  διαφορετικά. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Εάν αυτή η ιδιότητα οριστεί σε true, το περιεχόμενο της σελίδας θα επαναχρησιμοποιηθεί κατά τη βελτιστοποίηση του εγγράφου για πανομοιότυπες σελίδες.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  εάν το περιεχόμενο της σελίδας επαναχρησιμοποιείται,  false  διαφορετικά.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Ορίζει αν επιτρέπεται η επαναχρησιμοποίηση του περιεχομένου της σελίδας στο PDF.

***Note:** The default value is  false .*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| allowReusePageContent | boolean | true  για να επιτραπεί η επαναχρήση του περιεχομένου της σελίδας,  false  διαφορετικά. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Μερικές φορές ένα έγγραφο περιέχει αχρησιμοποίητες ροές πόρων. Αυτές οι ροές δεν είναι \\u201cαχρησιμοποίητα αντικείμενα\\u201d επειδή αναφέρονται από το λεξικό πόρων μιας σελίδας\\u2019s. Αυτό μπορεί να συμβεί σε περιπτώσεις όπου μια εικόνα έχει αφαιρεθεί από τη σελίδα αλλά όχι από τους πόρους της σελίδας. Επίσης, αυτή η κατάσταση συχνά εμφανίζεται όταν εξάγονται σελίδες από το έγγραφο και οι σελίδες του εγγράφου έχουν \\u201cκοινά\\u201d πόρους, δηλαδή το ίδιο αντικείμενο Resources. Τα περιεχόμενα της σελίδας αναλύονται για να προσδιοριστεί εάν μια ροή πόρων χρησιμοποιείται ή όχι. Οι αχρησιμοποίητες ροές αφαιρούνται. Μερικές φορές αυτό μειώνει το μέγεθος του εγγράφου.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  εάν οι αχρησιμοποίητες ροές αφαιρούνται,  false  διαφορετικά.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Ορίζει αν θα αφαιρεθούν οι αχρησιμοποίητες ροές από το PDF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  για αφαίρεση αχρησιμοποίητων ροών,  false  διαφορετικά. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Μερικές φορές ένα PDF έγγραφο περιέχει PDF αντικείμενα που δεν αναφέρονται από κανένα άλλο αντικείμενο στο έγγραφο. Αυτό μπορεί να συμβεί, για παράδειγμα, όταν μια σελίδα αφαιρείται από το δέντρο σελίδων του εγγράφου αλλά το ίδιο το αντικείμενο σελίδας δεν αφαιρείται. Η αφαίρεση αυτών των αντικειμένων δεν καθιστά το έγγραφο άκυρο, αλλά το μικραίνει.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  εάν τα αχρησιμοποίητα αντικείμενα αφαιρούνται,  false  διαφορετικά.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Ορίζει αν θα αφαιρεθούν τα αχρησιμοποίητα αντικείμενα από το PDF.

***Note:** The default value is  false .*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  για αφαίρεση αχρησιμοποίητων αντικειμένων,  false  διαφορετικά. |

