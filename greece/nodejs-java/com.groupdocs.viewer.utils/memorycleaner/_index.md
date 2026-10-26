---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Καθαρίζει διάφορους πόρους για την απελευθέρωση μνήμης."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Καθαρίζει διάφορους πόρους για την απελευθέρωση μνήμης.

Αυτή η κλάση παρέχει μεθόδους για εκκαθάριση της μνήμης heap, διαγραφή προσωρινών αρχείων και εκκαθάριση των πληροφοριών καταχώρησης γραμματοσειρών. Περιλαμβάνει επίσης μια μέθοδο για ασφαλή εκκαθάριση των τοπικών προς νήμα αντικειμένων για το τρέχον νήμα.

Παράδειγμα χρήσης:

```

 // Clean heap memory, keeping font settings
 MemoryCleaner.clearKeepingFontSettings();

 // Clean heap memory and delete temp files
 MemoryCleaner.clear();

 // Clean heap memory from static PDF instances
 MemoryCleaner.clearStaticInstances();

 // Delete all temp files created by PDF in the system temp directory
 MemoryCleaner.clearAllTempFiles();

 // Clear font registry information from heap memory
 MemoryCleaner.clearFontRegistry();

 // Safely clear thread-local instances for the current thread
 MemoryCleaner.clearCurrentThreadLocals();
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Εκκαθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία. |
| [clear()](#clear--) | Εκκαθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία. |
| [clearStaticInstances()](#clearStaticInstances--) | Εκκαθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις. |
| [clearAllTempFiles()](#clearAllTempFiles--) | Διαγράφει τα προσωρινά αρχεία που δημιουργήθηκαν από το GroupDocs.Viewer στον φάκελο προσωρινών αρχείων του συστήματος. |
| [clearFontRegistry()](#clearFontRegistry--) | Εκκαθαρίζει τις πληροφορίες καταχώρησης γραμματοσειρών από τη μνήμη heap. |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Ασφαλώς εκκαθαρίζει τη μνήμη heap από τα thread-local αντικείμενα για το τρέχον νήμα. |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Εκκαθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία. Αυτή η μέθοδος δεν επηρεάζει τις ρυθμίσεις γραμματοσειρών.

### clear() {#clear--}
```
public static void clear()
```


Εκκαθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία.

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Εκκαθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις.

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Διαγράφει τα προσωρινά αρχεία που δημιουργήθηκαν από το GroupDocs.Viewer στον φάκελο προσωρινών αρχείων του συστήματος.

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Εκκαθαρίζει τις πληροφορίες καταχώρησης γραμματοσειρών από τη μνήμη heap.

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Ασφαλώς εκκαθαρίζει τη μνήμη heap από τα thread-local αντικείμενα για το τρέχον νήμα.

