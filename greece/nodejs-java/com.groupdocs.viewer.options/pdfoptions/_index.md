---
title: "PdfOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση εγγράφων PDF."
type: docs
weight: 22
url: /el/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Παρέχει επιλογές για την απόδοση εγγράφων PDF.

Η κλάση PdfOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης εγγράφων PDF στο στοιχείο GroupDocs.Viewer. Για λεπτομέρειες, δείτε την [documentation][].

Παράδειγμα χρήσης:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PdfOptions. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Καθορίζει εάν το κείμενο από την πηγή αποδίδεται ως εικόνα στο HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Ορίζει εάν το κείμενο από την πηγή αποδίδεται ως εικόνα στο HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Ελέγχει αν η ομαδοποίηση χαρακτήρων είναι απενεργοποιημένη για τη διατήρηση μέγιστης ακρίβειας κατά την τοποθέτηση χαρακτήρων όταν αποδίδεται η σελίδα. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Ορίζει την επιλογή για απενεργοποίηση της ομαδοποίησης χαρακτήρων, εξασφαλίζοντας μέγιστη ακρίβεια κατά την τοποθέτηση χαρακτήρων όταν αποδίδεται η σελίδα. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Ελέγχει εάν η απόδοση κειμένου και γραφικών πρέπει να ακολουθεί τη σειρά z στο αρχικό έγγραφο PDF κατά την απόδοση σε HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Ενεργοποιεί ή απενεργοποιεί την απόδοση κειμένου και γραφικών σύμφωνα με τη σειρά z στο αρχικό έγγραφο PDF κατά την απόδοση σε HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Καθορίζει εάν η υποδείξη γραμματοσειράς είναι ενεργοποιημένη. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Ενεργοποιεί την υποδείξη γραμματοσειράς. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Ενεργοποιεί την απόδοση σελίδων με το ίδιο μέγεθος σε εικονοστοιχεία όπως το μέγεθος σελίδας στο πηγαίο έγγραφο PDF. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Ενεργοποιεί την απόδοση σελίδων με το ίδιο μέγεθος σε εικονοστοιχεία όπως το μέγεθος σελίδας στο πηγαίο έγγραφο PDF. |
| [getImageQuality()](#getImageQuality--) | Ανακτά την ποιότητα εξόδου εικόνας για πόρους εικόνας κατά την απόδοση σε HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Ορίζει την ποιότητα εξόδου εικόνας για πόρους εικόνας κατά την απόδοση σε HTML. |
| [isFixedLayout()](#isFixedLayout--) | Το PDF είναι σταθερή μορφή, έτσι όλα τα στοιχεία έχουν συγκεκριμένη θέση σε μια σελίδα. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | Το PDF είναι σταθερή μορφή, έτσι όλα τα στοιχεία έχουν συγκεκριμένη θέση σε μια σελίδα. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Ενεργοποιήστε αυτήν την επιλογή για να τυλίξετε κάθε εικόνα στο έγγραφο HTML εξόδου με ετικέτα SVG ώστε να βελτιώσετε την ποιότητα εξόδου. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Ενεργοποιήστε αυτήν την επιλογή για να τυλίξετε κάθε εικόνα στο έγγραφο HTML εξόδου με ετικέτα SVG ώστε να βελτιώσετε την ποιότητα εξόδου. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Προσπαθεί να διορθώσει το πρόβλημα όταν όλο το περιεχόμενο της σελίδας HTML είναι ένας σύνδεσμος. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Προσπαθεί να διορθώσει το πρόβλημα όταν όλο το περιεχόμενο της σελίδας HTML είναι ένας σύνδεσμος. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Αντικαθιστά τις γραμματοσειρές όπως απαιτείται για να διασφαλιστεί ότι όλοι οι χαρακτήρες στο κείμενο μπορούν να εμφανιστούν. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Αντικαθιστά τις γραμματοσειρές όπως απαιτείται για να διασφαλιστεί ότι όλοι οι χαρακτήρες στο κείμενο μπορούν να εμφανιστούν. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Απενεργοποιήστε τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Ορίστε τη σημαία για να απενεργοποιήσετε τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PdfOptions.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML.

Κατά την απόδοση αρχείων PDF με προστασία κατά της αντιγραφής κειμένου και εικόνων σε HTML, το GroupDocs.Viewer προσθέτει ένα χαρακτηριστικό HTML 'inert' στην ετικέτα HTML BODY. Η προεπιλεγμένη τιμή αυτής της επιλογής είναι  false .

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML.

Κατά την απόδοση αρχείων PDF με προστασία κατά της αντιγραφής κειμένου και εικόνων σε HTML, το GroupDocs.Viewer προσθέτει ένα χαρακτηριστικό HTML 'inert' στην ετικέτα HTML BODY. Η προεπιλεγμένη τιμή αυτής της επιλογής είναι  false .

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Καθορίζει εάν το κείμενο από την πηγή αποδίδεται ως εικόνα στο HTML.

Όταν αυτή η επιλογή οριστεί σε  true , το κείμενο αποδίδεται ως εικόνα στο παραγόμενο HTML. Ενεργοποιήστε αυτή την επιλογή για να κάνετε το κείμενο μη επιλέξιμο ή για να διορθώσετε την απόδοση χαρακτήρων και να κάνετε το HTML να μοιάζει με PDF. Αυτή η επιλογή υποστηρίζεται κατά την απόδοση σε HTML.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  εάν το κείμενο αποδίδεται ως εικόνα σε HTML,  false  διαφορετικά.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Ορίζει εάν το κείμενο από την πηγή αποδίδεται ως εικόνα στο HTML.

Όταν αυτή η επιλογή οριστεί σε  true , το κείμενο αποδίδεται ως εικόνα στο παραγόμενο HTML. Ενεργοποιήστε αυτή την επιλογή για να κάνετε το κείμενο μη επιλέξιμο ή για να διορθώσετε την απόδοση χαρακτήρων και να κάνετε το HTML να μοιάζει με PDF. Αυτή η επιλογή υποστηρίζεται κατά την απόδοση σε HTML.

***Note:** The default value is  false .*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderTextAsImage | boolean | true  για απόδοση του κειμένου ως εικόνα σε HTML,  false  διαφορετικά. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Ελέγχει εάν η ομαδοποίηση χαρακτήρων είναι απενεργοποιημένη για να διατηρηθεί η μέγιστη ακρίβεια κατά την τοποθέτηση χαρακτήρων κατά την απόδοση της σελίδας. Όταν αυτή η επιλογή είναι ενεργοποιημένη, οι χαρακτήρες αποδίδονται χωρίς καμία ομαδοποίηση, εξασφαλίζοντας τη μέγιστη ακρίβεια.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean -  true  εάν η ομαδοποίηση χαρακτήρων είναι απενεργοποιημένη,  false  διαφορετικά.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Ορίζει την επιλογή για απενεργοποίηση της ομαδοποίησης χαρακτήρων, εξασφαλίζοντας τη μέγιστη ακρίβεια κατά την τοποθέτηση χαρακτήρων κατά την απόδοση της σελίδας. Όταν αυτή η επιλογή ενεργοποιηθεί ορίζοντας την τιμή σε  true , η ομαδοποίηση χαρακτήρων απενεργοποιείται, εξασφαλίζοντας τη μέγιστη ακρίβεια.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για απενεργοποίηση της ομαδοποίησης χαρακτήρων,  false  για ενεργοποίησή της. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Ελέγχει εάν η απόδοση κειμένου και γραφικών πρέπει να ακολουθεί τη σειρά z στο αρχικό έγγραφο PDF κατά την απόδοση σε HTML. Όταν αυτή η επιλογή ενεργοποιηθεί επιστρέφοντας  true , το κείμενο και τα γραφικά αποδίδονται σύμφωνα με τη σειρά z στο αρχικό έγγραφο PDF.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean -  true  εάν η πολυεπίπεδη απόδοση είναι ενεργοποιημένη,  false  διαφορετικά.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Ενεργοποιεί ή απενεργοποιεί την απόδοση κειμένου και γραφικών σύμφωνα με τη σειρά z στο αρχικό έγγραφο PDF κατά την απόδοση σε HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση της πολυεπίπεδης απόδοσης,  false  για απενεργοποίησή της. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Καθορίζει εάν είναι ενεργοποιημένο το font hinting. Το font hinting προσαρμόζει την εμφάνιση μιας γραμματοσειράς outline. Αυτή η επιλογή υποστηρίζεται μόνο για γραμματοσειρές TrueType (TTF) όταν χρησιμοποιείται στο πηγαίο έγγραφο.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean -  true  εάν το font hinting είναι ενεργοποιημένο,  false  διαφορετικά.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Ενεργοποιεί το font hinting. Το font hinting προσαρμόζει την εμφάνιση μιας γραμματοσειράς outline και υποστηρίζεται μόνο για γραμματοσειρές TrueType (TTF) όταν χρησιμοποιείται στο πηγαίο έγγραφο.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση του font hinting,  false  για απενεργοποίησή του. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Ενεργοποιεί την απόδοση σελίδων με το ίδιο μέγεθος σε εικονοστοιχεία όπως το μέγεθος σελίδας στο πηγαίο έγγραφο PDF.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean -  true  εάν η επιλογή είναι ενεργοποιημένη,  false  διαφορετικά.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Ενεργοποιεί την απόδοση σελίδων με το ίδιο μέγεθος σε εικονοστοιχεία όπως το μέγεθος σελίδας στο πηγαίο έγγραφο PDF.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true  για ενεργοποίηση απόδοσης με το αρχικό μέγεθος σελίδας,  false  διαφορετικά. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Ανακτά την ποιότητα εξόδου εικόνας για πόρους εικόνας κατά την απόδοση σε HTML. Η προεπιλεγμένη τιμή είναι Low.

Όταν αυτή η επιλογή οριστεί σε true, το GroupDocs.Viewer αποδίδει το κείμενο ως εικόνα στην έξοδο HTML. Αυτό κάνει το κείμενο μη επιλέξιμο και βελτιώνει την απόδοση χαρακτήρων, εξασφαλίζοντας εμφάνιση παρόμοια με PDF στο HTML. Η προεπιλεγμένη τιμή είναι false. Αυτή η επιλογή είναι διαθέσιμη για απόδοση σε HTML. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Ορίζει την ποιότητα εξόδου εικόνας για πόρους εικόνας κατά την απόδοση σε HTML. Η προεπιλεγμένη τιμή είναι Low.

Όταν αυτή η επιλογή οριστεί σε true, το GroupDocs.Viewer αποδίδει το κείμενο ως εικόνα στην έξοδο HTML. Αυτό κάνει το κείμενο μη επιλέξιμο και βελτιώνει την απόδοση χαρακτήρων, εξασφαλίζοντας εμφάνιση παρόμοια με PDF στο HTML. Η προεπιλεγμένη τιμή είναι false. Αυτή η επιλογή είναι διαθέσιμη για απόδοση σε HTML. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Η ποιότητα της εξόδου εικόνας για πόρους εικόνας κατά τη μετατροπή σε HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


Το PDF είναι σταθερή μορφή, έτσι όλα τα στοιχεία έχουν συγκεκριμένη θέση σε μια σελίδα. Για να διασφαλιστεί ότι το παραγόμενο HTML φαίνεται το ίδιο με το αρχικό PDF, τα έγγραφα μετατρέπονται σε HTML με σταθερή διάταξη από προεπιλογή. Όταν γίνεται μετατροπή με σταθερή διάταξη, το παραγόμενο HTML έχει σταθερό μέγεθος, ώστε τα στοιχεία να παραμένουν στην ίδια θέση ανεξάρτητα από το μέγεθος του παραθύρου. Για να μετατρέψετε σε HTML με ρευστή διάταξη, ορίστε αυτήν την ιδιότητα σε false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - true εάν είναι σταθερή διάταξη
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


Το PDF είναι σταθερή μορφή, έτσι όλα τα στοιχεία έχουν συγκεκριμένη θέση σε μια σελίδα. Για να διασφαλιστεί ότι το παραγόμενο HTML φαίνεται το ίδιο με το αρχικό PDF, τα έγγραφα μετατρέπονται σε HTML με σταθερή διάταξη από προεπιλογή. Όταν γίνεται μετατροπή με σταθερή διάταξη, το παραγόμενο HTML έχει σταθερό μέγεθος, ώστε τα στοιχεία να παραμένουν στην ίδια θέση ανεξάρτητα από το μέγεθος του παραθύρου. Για να μετατρέψετε σε HTML με ρευστή διάταξη, ορίστε αυτήν την ιδιότητα σε false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fixedLayout | boolean | true εάν είναι σταθερή διάταξη |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Ενεργοποιήστε αυτήν την επιλογή για να τυλίξετε κάθε εικόνα στο έγγραφο HTML εξόδου με ετικέτα SVG ώστε να βελτιώσετε την ποιότητα εξόδου.

Αυτή η επιλογή υποστηρίζεται κατά τη μετατροπή των [PDF and Page Layout file formats][] σε HTML με ενσωματωμένους και εξωτερικούς πόρους.

Από προεπιλογή, όταν γίνεται μετατροπή σε αρχεία PDF και Page Layout, όλες οι εικόνες μετατρέπονται σε μία εικόνα PNG. Η παραγόμενη εικόνα PNG χρησιμοποιείται ως φόντο για το παραγόμενο έγγραφο HTML.

Μάθετε περισσότερα:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean -  true  εάν οι εικόνες είναι τυλιγμένες σε SVG,  false  διαφορετικά.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Ενεργοποιήστε αυτήν την επιλογή για να τυλίξετε κάθε εικόνα στο έγγραφο HTML εξόδου με ετικέτα SVG ώστε να βελτιώσετε την ποιότητα εξόδου.

Αυτή η επιλογή υποστηρίζεται κατά τη μετατροπή των [PDF and Page Layout file formats][] σε HTML με ενσωματωμένους και εξωτερικούς πόρους.

Από προεπιλογή, όταν γίνεται μετατροπή σε αρχεία PDF και Page Layout, όλες οι εικόνες μετατρέπονται σε μία εικόνα PNG. Η παραγόμενη εικόνα PNG χρησιμοποιείται ως φόντο για το παραγόμενο έγγραφο HTML.

Μάθετε περισσότερα:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true  εάν οι εικόνες πρέπει να τυλιχθούν σε SVG,  false  διαφορετικά. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Προσπαθεί να διορθώσει το πρόβλημα όταν ολόκληρο το περιεχόμενο της σελίδας HTML είναι ένας σύνδεσμος. Λειτουργεί μόνο όταν η μορφή εισόδου είναι PDF και η μορφή εξόδου είναι HTML (με ενσωματωμένους ή εξωτερικούς πόρους). Από προεπιλογή είναι απενεργοποιημένο (false). Ενεργοποιήστε το μόνο όταν γνωρίζετε τι και γιατί το κάνετε. Η ενεργοποίηση αυτής της επιλογής αυξάνει το χρόνο επεξεργασίας του εγγράφου.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Προσπαθεί να διορθώσει το πρόβλημα όταν ολόκληρο το περιεχόμενο της σελίδας HTML είναι ένας σύνδεσμος. Λειτουργεί μόνο όταν η μορφή εισόδου είναι PDF και η μορφή εξόδου είναι HTML (με ενσωματωμένους ή εξωτερικούς πόρους). Από προεπιλογή είναι απενεργοποιημένο (false). Ενεργοποιήστε το μόνο όταν γνωρίζετε τι και γιατί το κάνετε. Η ενεργοποίηση αυτής της επιλογής αυξάνει το χρόνο επεξεργασίας του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fixLinkIssue | boolean | true εάν το πρόβλημα πρέπει να διορθωθεί, false διαφορετικά. |

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
| analyzeFonts | boolean | true εάν οι γραμματοσειρές πρέπει να εμφανιστούν, false διαφορετικά. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Απενεργοποιήστε τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS.

Πολλές λειτουργίες με γραμματοσειρές δεν μπορούν να εκτελεστούν εάν αυτές οι λειτουργίες απαγορεύονται από την άδεια της γραμματοσειράς. Για παράδειγμα, ορισμένες γραμματοσειρές δεν μπορούν να ενσωματωθούν σε έγγραφο PDF εάν οι κανόνες άδειας απενεργοποιούν την ενσωμάτωση για αυτή τη γραμματοσειρά. Να είστε προσεκτικοί όταν χρησιμοποιείτε αυτή τη σημαία. Όταν ορίζεται, σημαίνει ότι το άτομο που τη θέτει αναλαμβάνει πλήρη ευθύνη για τυχόν παραβιάσεις άδειας/νόμου. Έτσι το αναλαμβάνει με δικό του ρίσκο. Συνιστάται έντονα να χρησιμοποιείτε αυτή τη σημαία μόνο όταν είστε πλήρως βέβαιοι ότι δεν παραβιάζετε το νόμο περί πνευματικών δικαιωμάτων. Από προεπιλογή false. Για παράδειγμα κώδικα, δείτε την [documentation][].

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Ορίστε τη σημαία για να απενεργοποιήσετε τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS.

Πολλές λειτουργίες με γραμματοσειρές δεν μπορούν να εκτελεστούν εάν αυτές οι λειτουργίες απαγορεύονται από την άδεια της γραμματοσειράς. Για παράδειγμα, ορισμένες γραμματοσειρές δεν μπορούν να ενσωματωθούν σε έγγραφο PDF εάν οι κανόνες άδειας απενεργοποιούν την ενσωμάτωση για αυτή τη γραμματοσειρά. Να είστε προσεκτικοί όταν χρησιμοποιείτε αυτή τη σημαία. Όταν ορίζεται, σημαίνει ότι το άτομο που τη θέτει αναλαμβάνει πλήρη ευθύνη για τυχόν παραβιάσεις άδειας/νόμου. Έτσι το αναλαμβάνει με δικό του ρίσκο. Συνιστάται έντονα να χρησιμοποιείτε αυτή τη σημαία μόνο όταν είστε πλήρως βέβαιοι ότι δεν παραβιάζετε το νόμο περί πνευματικών δικαιωμάτων. Από προεπιλογή false. Για παράδειγμα κώδικα, δείτε την [documentation][].

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

