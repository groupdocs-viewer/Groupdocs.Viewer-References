---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση αρχείων δεδομένων Mail storage Lotus Notes MBox."
type: docs
weight: 19
url: /el/java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Παρέχει επιλογές για την απόδοση αρχείων δεδομένων αποθήκευσης αλληλογραφίας (Lotus Notes, MBox).


Η κλάση MailStorageOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν
για να ελέγξετε την απόδοση των αρχείων αποθήκευσης αλληλογραφίας (όπως Lotus Notes ή MBox) στο στοιχείο GroupDocs.Viewer.


Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Παράδειγμα χρήσης:

````

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTextFilter()](#getTextFilter--) | Λαμβάνει τις λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων. |
|
|  | [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Ορίζει τις λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Λαμβάνει τη διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη. |
|
|  | [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Ορίζει τη διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη. |
|
|  | [getMaxItems()](#getMaxItems--) | Λαμβάνει τον μέγιστο αριθμό μηνυμάτων ή αντικειμένων προς απόδοση. |
|
|  | [setMaxItems(int maxItems)](#setMaxItems-int-) | Ορίζει τον μέγιστο αριθμό μηνυμάτων ή αντικειμένων προς απόδοση. |
|
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Λαμβάνει τις λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων.


Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε όλα τα μηνύματα που περιέχουν συγκεκριμένο κείμενο στο θέμα ή στο σώμα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Returns:**
java.lang.String - οι λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων.

### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Ορίζει τις λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων.


Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε όλα τα μηνύματα που περιέχουν συγκεκριμένο κείμενο στο θέμα ή στο σώμα. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | textFilter | java.lang.String | Οι λέξεις-κλειδιά που χρησιμοποιούνται για φιλτράρισμα μηνυμάτων. |
|

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Λαμβάνει τη διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη.


Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε όλα τα μηνύματα που περιέχουν συγκεκριμένο κείμενο στη διεύθυνση του αποστολέα ή του παραλήπτη. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Returns:**
java.lang.String - η διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων.

### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Ορίζει τη διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη.


Χρησιμοποιήστε αυτήν την ιδιότητα για να αποδώσετε όλα τα μηνύματα που περιέχουν συγκεκριμένο κείμενο στη διεύθυνση του αποστολέα ή του παραλήπτη. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | addressFilter | java.lang.String | Η διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων. |
|

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Λαμβάνει τον μέγιστο αριθμό μηνυμάτων ή αντικειμένων προς απόδοση.


Τα αρχεία δεδομένων Lotus Notes μπορεί να είναι μεγάλα, και η ανάκτηση όλων των μηνυμάτων μπορεί να διαρκέσει σημαντικό χρόνο.
Αυτή η ρύθμιση περιορίζει τον μέγιστο αριθμό μηνυμάτων ή αντικειμένων που αποδίδονται.


***Note:** The default value is 0, which means all messages will be rendered.*
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).


**Returns:**
int - ο μέγιστος αριθμός μηνυμάτων ή αντικειμένων προς απόδοση.

### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Ορίζει τον μέγιστο αριθμό μηνυμάτων ή αντικειμένων προς απόδοση.


Τα αρχεία δεδομένων Lotus Notes μπορεί να είναι μεγάλα, και η ανάκτηση όλων των μηνυμάτων μπορεί να διαρκέσει σημαντικό χρόνο.
Αυτή η ρύθμιση περιορίζει τον μέγιστο αριθμό μηνυμάτων ή αντικειμένων που αποδίδονται.


***Note:** The default value is 0, which means all messages will be rendered.*
Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxItems | int | Ο μέγιστος αριθμός μηνυμάτων ή αντικειμένων προς απόδοση. |
|

