---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση αρχείων αρχειοθήκης."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Παρέχει επιλογές για την απόδοση αρχείων αρχειοθήκης.

Η κλάση  ArchiveOptions  αντιπροσωπεύει ένα σύνολο επιλογών που μπορούν να χρησιμοποιηθούν για τη διαμόρφωση της απόδοσης αρχείων αρχειοθήκης στη μονάδα προβολής. Σας επιτρέπει να προσαρμόσετε διάφορες πτυχές της διαδικασίας απόδοσης, όπως ο αριθμός των στοιχείων ανά σελίδα κ.λπ.

Παράδειγμα χρήσης:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης ArchiveOptions με προεπιλεγμένες ρυθμίσεις. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFolder()](#getFolder--) | Λαμβάνει το φάκελο μέσα στην αρχειοθήκη που θα χρησιμοποιηθεί για την απόδοση. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Ορίζει το φάκελο μέσα στο αρχείο που θα χρησιμοποιηθεί για την απόδοση. |
| [getFileName()](#getFileName--) | Λαμβάνει το όνομα αρχείου που θα εμφανίζεται στην κεφαλίδα. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Ορίζει το όνομα αρχείου που θα εμφανίζεται στην κεφαλίδα. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης ArchiveOptions με προεπιλεγμένες ρυθμίσεις.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


Λαμβάνει το φάκελο μέσα στην αρχειοθήκη που θα χρησιμοποιηθεί για την απόδοση.

Από προεπιλογή, το GroupDocs.Viewer αποδίδει στοιχεία από όλους τους φακέλους που περιέχονται στο αρχείο. Για να αποδώσετε στοιχεία από συγκεκριμένο φάκελο, ορίστε αυτήν την ιδιότητα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - ο φάκελος που θα αποδοθεί.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Ορίζει το φάκελο μέσα στο αρχείο που θα χρησιμοποιηθεί για την απόδοση.

Από προεπιλογή, το GroupDocs.Viewer αποδίδει στοιχεία από όλους τους φακέλους που περιέχονται στο αρχείο. Για να αποδώσετε στοιχεία από συγκεκριμένο φάκελο, ορίστε αυτήν την ιδιότητα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | Ο φάκελος που θα αποδοθεί. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Λαμβάνει το όνομα αρχείου που θα εμφανίζεται στην κεφαλίδα.

Από προεπιλογή, το GroupDocs.Viewer εμφανίζει το όνομα του αρχείου του αρχείου στην κεφαλίδα κάθε σελίδας. Για να αλλάξετε ή να κρύψετε αυτό το όνομα, ορίστε αυτήν την ιδιότητα. Για περισσότερες πληροφορίες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Ορίζει το όνομα αρχείου που θα εμφανίζεται στην κεφαλίδα.

Από προεπιλογή, το GroupDocs.Viewer εμφανίζει το όνομα του αρχείου του αρχείου στην κεφαλίδα κάθε σελίδας. Για να αλλάξετε ή να κρύψετε αυτό το όνομα, ορίστε αυτήν την ιδιότητα. Για περισσότερες πληροφορίες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Το όνομα αρχείου που θα εμφανίζεται. |

