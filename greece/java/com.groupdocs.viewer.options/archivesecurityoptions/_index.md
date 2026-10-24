---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Κλάση που μπορεί να χρησιμοποιηθεί για τον περιορισμό της διαδικασίας εξαγωγής των αρχείων."
type: docs
weight: 11
url: /el/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Κλάση που μπορεί να χρησιμοποιηθεί για τον περιορισμό της διαδικασίας εξαγωγής των αρχείων.

Η κλάση ArchiveSecurityOptions παρέχει έναν τρόπο περιορισμού της εξαγωγής αρχείων και επιβολής ορισμένων περιορισμών.

Παράδειγμα χρήσης:

````

 ArchiveSecurityOptions securityOptions = new ArchiveSecurityOptions();
 securityOptions.setMaxAllowedEntryNameLength(255);
 securityOptions.setMaxAllowedEntrySize(10737418240L);
 securityOptions.setMaxAllowedEntriesCount(1000);
 securityOptions.setMaxAllowedEntryCompressionRatio(100);

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setArchiveSecurityOptions(securityOptions);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** Not each archive type supports all options.*

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Αυτή η επιλογή καθορίζει το μέγιστο μήκος που μπορεί να έχει το όνομα μιας καταχώρησης αρχείου. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Ορίζει το μέγιστο επιτρεπόμενο μήκος για τα ονόματα των καταχωρήσεων αρχείου. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Ανακτά το μέγιστο επιτρεπόμενο μέγεθος για τις καταχωρήσεις αρχείου. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Ορίζει το μέγιστο επιτρεπόμενο μέγεθος για τις καταχωρήσεις αρχείου. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Ανακτά το μέγιστο επιτρεπόμενο πλήθος καταχωρήσεων σε ένα αρχείο. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Ορίζει το μέγιστο επιτρεπόμενο πλήθος καταχωρήσεων σε ένα αρχείο. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Καθορίζει το μέγιστο λόγο συμπίεσης που επιτρέπεται για την εξαγωγή καταχωρήσεων αρχείου. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Καθορίζει το μέγιστο λόγο συμπίεσης που επιτρέπεται για την εξαγωγή καταχωρήσεων αρχείου. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Αυτή η επιλογή καθορίζει το μέγιστο μήκος που μπορεί να έχει το όνομα μιας καταχώρησης αρχείου.
Εάν το όνομα μιας καταχώρησης υπερβεί αυτό το όριο, θα προκαλέσει σφάλμα.


***Note:** The default value for this option is 255.*


**Returns:**
int - το μέγιστο επιτρεπόμενο μήκος για τα ονόματα των καταχωρήσεων αρχείου.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Ορίζει το μέγιστο επιτρεπόμενο μήκος για τα ονόματα των καταχωρήσεων αρχείου.
Το μέγιστο επιτρεπόμενο μήκος καθορίζει το όριο για το μήκος ενός ονόματος καταχώρησης αρχείου.
Εάν το μήκος ενός ονόματος καταχώρησης υπερβεί αυτό το όριο, θα προκαλέσει σφάλμα.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | Το μέγιστο μήκος ονόματος καταχώρησης αρχείου που θα οριστεί. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Ανακτά το μέγιστο επιτρεπόμενο μέγεθος για τις καταχωρήσεις αρχείου.
Το μέγιστο επιτρεπόμενο μέγεθος καταχώρησης καθορίζει το όριο για το μέγεθος μιας καταχώρησης αρχείου.
Εάν το μέγεθος μιας καταχώρησης υπερβεί αυτό το όριο, θα οδηγήσει σε σφάλμα.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - το μέγιστο μέγεθος καταχώρησης αρχείου.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Ορίζει το μέγιστο επιτρεπόμενο μέγεθος για τις καταχωρήσεις αρχείου.
Το μέγιστο επιτρεπόμενο μέγεθος καταχώρησης καθορίζει το όριο για το μέγεθος μιας καταχώρησης αρχείου.
Εάν το μέγεθος μιας καταχώρησης υπερβεί αυτό το όριο, θα οδηγήσει σε σφάλμα.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | Το μέγιστο μέγεθος καταχώρησης αρχείου. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Ανακτά το μέγιστο επιτρεπόμενο πλήθος καταχωρήσεων σε ένα αρχείο.
Ο μέγιστος επιτρεπτός αριθμός καταχωρήσεων καθορίζει το όριο για τον αριθμό των καταχωρήσεων που μπορεί να περιέχει ένα αρχείο.
Εάν ένα αρχείο περιέχει περισσότερες καταχωρήσεις από αυτό το όριο, δεν μπορεί να εξαχθεί.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - ο μέγιστος αριθμός καταχωρήσεων σε ένα αρχείο.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Ορίζει το μέγιστο επιτρεπόμενο πλήθος καταχωρήσεων σε ένα αρχείο.
Ο μέγιστος επιτρεπτός αριθμός καταχωρήσεων καθορίζει το όριο για τον αριθμό των καταχωρήσεων που μπορεί να περιέχει ένα αρχείο.
Εάν ένα αρχείο περιέχει περισσότερες καταχωρήσεις από αυτό το όριο, δεν μπορεί να εξαχθεί.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | Ο μέγιστος αριθμός καταχωρήσεων σε ένα αρχείο. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Καθορίζει το μέγιστο λόγο συμπίεσης που επιτρέπεται για την εξαγωγή καταχωρήσεων αρχείου.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - ο μέγιστος επιτρεπτός λόγος συμπίεσης για τις καταχωρήσεις του αρχείου.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Καθορίζει το μέγιστο λόγο συμπίεσης που επιτρέπεται για την εξαγωγή καταχωρήσεων αρχείου.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | Ο μέγιστος επιτρεπτός λόγος συμπίεσης για τις καταχωρήσεις του αρχείου. |
|

