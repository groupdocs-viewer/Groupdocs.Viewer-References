---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση αρχείων δεδομένων Outlook."
type: docs
weight: 20
url: /el/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Παρέχει επιλογές για την απόδοση αρχείων δεδομένων Outlook.


Η κλάση OutlookOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν
για τον έλεγχο της απόδοσης αρχείων δεδομένων Outlook (όπως αρχεία PST ή OST) στο στοιχείο GroupDocs.Viewer.


Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Παράδειγμα χρήσης:

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFolder()](#getFolder--) | Λαμβάνει το όνομα του φακέλου για απόδοση. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Ορίζει το όνομα του φακέλου για απόδοση. |
|
|  | [getTextFilter()](#getTextFilter--) | Λαμβάνει τις λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων. |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Λαμβάνει τις λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Λαμβάνει τη διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη. |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Ορίζει τη διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη. |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Λαμβάνει τον μέγιστο αριθμό μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο. |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Ορίζει τον μέγιστο αριθμό μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο. |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Λαμβάνει το όνομα του φακέλου για απόδοση.
Το όνομα του φακέλου (π.χ., Inbox, Sent Item ή Deleted Items) για απόδοση.


Κατά την απόδοση ενός αρχείου δεδομένων Outlook, το GroupDocs.Viewer αποδίδει μηνύματα από όλους τους φακέλους που περιέχονται στο αρχείο (συμπεριλαμβανομένων των ένθετων φακέλων). Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε στοιχεία από έναν συγκεκριμένο φάκελο.
Για παράδειγμα κώδικα, δείτε αυτήν τη [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Returns:**
java.lang.String - το όνομα του φακέλου για απόδοση.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Ορίζει το όνομα του φακέλου για απόδοση.
Το όνομα του φακέλου (π.χ., Inbox, Sent Item ή Deleted Items) για απόδοση.


Κατά την απόδοση ενός αρχείου δεδομένων Outlook, το GroupDocs.Viewer αποδίδει μηνύματα από όλους τους φακέλους που περιέχονται στο αρχείο (συμπεριλαμβανομένων των ένθετων φακέλων). Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε στοιχεία από έναν συγκεκριμένο φάκελο.
Για παράδειγμα κώδικα, δείτε αυτήν τη [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το όνομα του φακέλου για απόδοση. |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Λαμβάνει τις λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων.


Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε όλα τα μηνύματα που περιέχουν συγκεκριμένο κείμενο στο θέμα ή στο σώμα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - οι λέξεις-κλειδιά.

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Λαμβάνει τις λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων.


Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε όλα τα μηνύματα που περιέχουν συγκεκριμένο κείμενο στο θέμα ή στο σώμα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Οι λέξεις-κλειδιά. |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Λαμβάνει τη διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη.


Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε όλα τα μηνύματα που περιέχουν συγκεκριμένο κείμενο στη διεύθυνση αποστολέα\\ufffds ή παραλήπτη\\ufffds. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - η διεύθυνση email που χρησιμοποιείται για το φιλτράρισμα των μηνυμάτων.

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Ορίζει τη διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη.


Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε όλα τα μηνύματα που περιέχουν συγκεκριμένο κείμενο στη διεύθυνση αποστολέα\\ufffds ή παραλήπτη\\ufffds. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Η διεύθυνση email που χρησιμοποιείται για το φιλτράρισμα των μηνυμάτων. |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Λαμβάνει τον μέγιστο αριθμό μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο.


Τα αρχεία δεδομένων Outlook μπορεί να είναι μεγάλα και η ανάκτηση όλων των μηνυμάτων μπορεί να διαρκέσει σημαντικό χρόνο.
Αυτή η ρύθμιση περιορίζει τον μέγιστο αριθμό μηνυμάτων ή στοιχείων (όπως επαφές και εργασίες) που αποδίδονται.
Η προεπιλεγμένη τιμή είναι 50. Ορίστε την τιμή σε 0 για να αποδώσετε όλα τα μηνύματα.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Returns:**
int - ο μέγιστος αριθμός μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο.

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Ορίζει τον μέγιστο αριθμό μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο.


Τα αρχεία δεδομένων Outlook μπορεί να είναι μεγάλα και η ανάκτηση όλων των μηνυμάτων μπορεί να διαρκέσει σημαντικό χρόνο.
Αυτή η ρύθμιση περιορίζει τον μέγιστο αριθμό μηνυμάτων ή στοιχείων (όπως επαφές και εργασίες) που αποδίδονται.
Η προεπιλεγμένη τιμή είναι 50. Ορίστε την τιμή σε 0 για να αποδώσετε όλα τα μηνύματα.
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ο μέγιστος αριθμός μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο. |
|

