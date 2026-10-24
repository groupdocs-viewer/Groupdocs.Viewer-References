---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αυτή η εξαίρεση προκαλείται όταν δεν βρεθεί ένα αρχείο ή κατάλογος."
type: docs
weight: 11
url: /el/java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Αυτή η εξαίρεση ρίχνεται όταν δεν βρεθεί ένα αρχείο ή κατάλογος. Υποδεικνύει ότι το καθορισμένο αρχείο ή κατάλογος δεν υπάρχει ή δεν είναι προσβάσιμο.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Δημιουργεί ένα αντικείμενο της κλάσης FileNotFoundException με το καθορισμένο μήνυμα. |
|
|  | [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης FileNotFoundException με μια καθορισμένη διαδρομή αρχείου. |
|
|  | [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Δημιουργεί ένα νέο αντικείμενο της κλάσης FileNotFoundException με ένα καθορισμένο μήνυμα σφάλματος. |
|
|  | [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Δημιουργεί ένα νέο αντικείμενο της κλάσης FileNotFoundException. |
|
|  | [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης FileNotFoundException με ένα καθορισμένο μήνυμα σφάλματος. |
|
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Δημιουργεί ένα αντικείμενο της κλάσης FileNotFoundException με το καθορισμένο μήνυμα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα που περιγράφει το σφάλμα. |
|

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης FileNotFoundException με μια καθορισμένη διαδρομή αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | διαδρομή | java.nio.file.Path | Η διαδρομή του αρχείου που δεν υπάρχει. |
|

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Δημιουργεί ένα νέο αντικείμενο της κλάσης FileNotFoundException με ένα καθορισμένο μήνυμα σφάλματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | messageTemplate | java.lang.String | Το μήνυμα που περιγράφει το σφάλμα. |
|
|  | παράμετροι | java.lang.Object[] | Οι παράμετροι που θα οριστούν στο μήνυμα σφάλματος. |
|

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Δημιουργεί ένα νέο αντικείμενο της κλάσης FileNotFoundException.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αίτιο | java.lang.Throwable | Η αιτία της εξαίρεσης. |
|

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης FileNotFoundException με ένα καθορισμένο μήνυμα σφάλματος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα που περιγράφει το σφάλμα. |
|
|  | throwable | java.lang.Throwable | Το throwable που προκάλεσε την εξαίρεση. |
|

