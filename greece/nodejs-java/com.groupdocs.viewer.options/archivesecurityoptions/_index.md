---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Κλάση που μπορεί να χρησιμοποιηθεί για τον περιορισμό της διαδικασίας εξαγωγής των αρχειοθηκών."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Κλάση που μπορεί να χρησιμοποιηθεί για τον περιορισμό της διαδικασίας εξαγωγής των αρχειοθηκών.

Η κλάση ArchiveSecurityOptions παρέχει έναν τρόπο περιορισμού της εξαγωγής αρχείων και επιβολής ορισμένων περιορισμών.

Παράδειγμα χρήσης:

```

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
 
```

***Note:** Not each archive type supports all options.*
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Αυτή η επιλογή καθορίζει το μέγιστο μήκος που μπορεί να έχει το όνομα μιας καταχώρησης αρχείου. |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Ορίζει το μέγιστο επιτρεπόμενο μήκος για τα ονόματα των καταχωρήσεων αρχείων. |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Ανακτά το μέγιστο επιτρεπόμενο μέγεθος για τις καταχωρήσεις αρχείων. |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Ορίζει το μέγιστο επιτρεπόμενο μέγεθος για τις καταχωρήσεις αρχείων. |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Ανακτά το μέγιστο επιτρεπόμενο πλήθος καταχωρήσεων σε ένα αρχείο. |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Ορίζει το μέγιστο επιτρεπόμενο πλήθος καταχωρήσεων σε ένα αρχείο. |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Καθορίζει το μέγιστο επιτρεπόμενο λόγο συμπίεσης για την εξαγωγή καταχωρήσεων αρχείων. |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Καθορίζει το μέγιστο επιτρεπόμενο λόγο συμπίεσης για την εξαγωγή καταχωρήσεων αρχείων. |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Αυτή η επιλογή καθορίζει το μέγιστο μήκος που μπορεί να έχει το όνομα μιας καταχώρησης αρχείου. Εάν ένα όνομα καταχώρησης υπερβεί αυτό το όριο, θα προκαλέσει σφάλμα.

***Note:** The default value for this option is 255.*

**Returns:**
int - το μέγιστο επιτρεπόμενο μήκος για τα ονόματα των καταχωρήσεων αρχείων.
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Ορίζει το μέγιστο επιτρεπτό μήκος για τα ονόματα των καταχωρίσεων του αρχείου. Το μέγιστο επιτρεπτό μήκος καθορίζει το όριο για το μήκος ενός ονόματος καταχώρισης αρχείου. Εάν το μήκος ενός ονόματος καταχώρισης υπερβεί αυτό το όριο, θα προκληθεί σφάλμα.

***Note:** The default value for the maximum allowed entry name length is 255.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | Το μέγιστο μήκος ονόματος καταχώρισης αρχείου που θα οριστεί. |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Ανακτά το μέγιστο επιτρεπτό μέγεθος για τις καταχωρίσεις του αρχείου. Το μέγιστο επιτρεπτό μέγεθος καταχώρισης καθορίζει το όριο για το μέγεθος μιας καταχώρισης αρχείου. Εάν το μέγεθος μιας καταχώρισης υπερβεί αυτό το όριο, θα προκύψει σφάλμα.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Returns:**
long - το μέγιστο μέγεθος καταχώρισης αρχείου.
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Ορίζει το μέγιστο επιτρεπτό μέγεθος για τις καταχωρίσεις του αρχείου. Το μέγιστο επιτρεπτό μέγεθος καταχώρισης καθορίζει το όριο για το μέγεθος μιας καταχώρισης αρχείου. Εάν το μέγεθος μιας καταχώρισης υπερβεί αυτό το όριο, θα προκύψει σφάλμα.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxAllowedEntrySize | long | Το μέγιστο μέγεθος καταχώρισης αρχείου. |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Ανακτά το μέγιστο επιτρεπτό πλήθος καταχωρίσεων σε ένα αρχείο. Το μέγιστο επιτρεπτό πλήθος καταχωρίσεων καθορίζει το όριο για τον αριθμό των καταχωρίσεων που μπορεί να περιέχει ένα αρχείο. Εάν ένα αρχείο περιέχει περισσότερες καταχωρίσεις από αυτό το όριο, δεν μπορεί να εξαχθεί.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Returns:**
long - το μέγιστο πλήθος καταχωρίσεων σε ένα αρχείο.
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Ορίζει το μέγιστο επιτρεπτό πλήθος καταχωρίσεων σε ένα αρχείο. Το μέγιστο επιτρεπτό πλήθος καταχωρίσεων καθορίζει το όριο για τον αριθμό των καταχωρίσεων που μπορεί να περιέχει ένα αρχείο. Εάν ένα αρχείο περιέχει περισσότερες καταχωρίσεις από αυτό το όριο, δεν μπορεί να εξαχθεί.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxAllowedEntriesCount | long | Το μέγιστο πλήθος καταχωρίσεων σε ένα αρχείο. |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Καθορίζει το μέγιστο επιτρεπόμενο λόγο συμπίεσης για την εξαγωγή καταχωρήσεων αρχείων.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Returns:**
double - ο μέγιστος επιτρεπτός λόγος συμπίεσης για τις καταχωρίσεις του αρχείου.
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Καθορίζει το μέγιστο επιτρεπόμενο λόγο συμπίεσης για την εξαγωγή καταχωρήσεων αρχείων.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | Ο μέγιστος επιτρεπτός λόγος συμπίεσης για τις καταχωρίσεις του αρχείου. |

