---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση αρχείων αρχειοθήκης."
type: docs
weight: 10
url: /el/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Παρέχει επιλογές για την απόδοση αρχείων αρχειοθήκης.


Το
ArchiveOptions
Η κλάση αντιπροσωπεύει ένα σύνολο επιλογών που μπορούν να χρησιμοποιηθούν για τη διαμόρφωση της απόδοσης αρχείων αρχειοθήκης στη μονάδα προβολής.
Σας επιτρέπει να προσαρμόσετε διάφορες πτυχές της διαδικασίας απόδοσης, όπως ο αριθμός των αντικειμένων σε κάθε σελίδα κ.λπ.


Παράδειγμα χρήσης:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
Η κλάση παρέχει μια σειρά επιλογών προσαρμογής για την απόδοση αρχείων αρχειοθήκης.
Μπορείτε να διαμορφώσετε αυτές τις επιλογές βάσει των συγκεκριμένων απαιτήσεών σας για να πετύχετε το επιθυμητό αποτέλεσμα.*

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | Δημιουργεί ένα νέο αντίτυπο της κλάσης ArchiveOptions με προεπιλεγμένες ρυθμίσεις. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFolder()](#getFolder--) | Αποκτά το φάκελο μέσα στην αρχειοθήκη που θα χρησιμοποιηθεί για την απόδοση. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Ορίζει το φάκελο μέσα στην αρχειοθήκη που θα χρησιμοποιηθεί για την απόδοση. |
|
|  | [getFileName()](#getFileName--) | Αποκτά το όνομα αρχείου που θα εμφανίζεται στην κεφαλίδα. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Ορίζει το όνομα αρχείου που θα εμφανίζεται στην κεφαλίδα. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Δημιουργεί ένα νέο αντίτυπο της κλάσης ArchiveOptions με προεπιλεγμένες ρυθμίσεις.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Αποκτά το φάκελο μέσα στην αρχειοθήκη που θα χρησιμοποιηθεί για την απόδοση.


Από προεπιλογή, το GroupDocs.Viewer αποδίδει στοιχεία από όλους τους φακέλους που περιέχονται στην αρχειοθήκη. Για να αποδώσετε στοιχεία από έναν συγκεκριμένο φάκελο, ορίστε αυτήν την ιδιότητα.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder).


**Returns:**
java.lang.String - ο φάκελος που θα αποδοθεί.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Ορίζει το φάκελο μέσα στην αρχειοθήκη που θα χρησιμοποιηθεί για την απόδοση.


Από προεπιλογή, το GroupDocs.Viewer αποδίδει στοιχεία από όλους τους φακέλους που περιέχονται στην αρχειοθήκη. Για να αποδώσετε στοιχεία από έναν συγκεκριμένο φάκελο, ορίστε αυτήν την ιδιότητα.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Ο φάκελος που θα αποδοθεί. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Αποκτά το όνομα αρχείου που θα εμφανίζεται στην κεφαλίδα.


Από προεπιλογή, το GroupDocs.Viewer εμφανίζει το όνομα του αρχείου αρχειοθήκης στην κεφαλίδα κάθε σελίδας. Για να αλλάξετε ή να κρύψετε αυτό το όνομα, ορίστε αυτήν την ιδιότητα.
Για περισσότερες πληροφορίες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Ορίζει το όνομα αρχείου που θα εμφανίζεται στην κεφαλίδα.


Από προεπιλογή, το GroupDocs.Viewer εμφανίζει το όνομα του αρχείου αρχειοθήκης στην κεφαλίδα κάθε σελίδας. Για να αλλάξετε ή να κρύψετε αυτό το όνομα, ορίστε αυτήν την ιδιότητα.
Για περισσότερες πληροφορίες και παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Το όνομα αρχείου που θα εμφανιστεί. |
|

