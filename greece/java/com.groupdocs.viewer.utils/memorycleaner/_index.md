---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Καθαρίζει διάφορους πόρους για να ελευθερώσει μνήμη."
type: docs
weight: 12
url: /el/java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Καθαρίζει διάφορους πόρους για να ελευθερώσει μνήμη.


Αυτή η κλάση παρέχει μεθόδους για τον καθαρισμό της μνήμης heap, τη διαγραφή προσωρινών αρχείων και τον καθαρισμό των πληροφοριών καταχώρησης γραμματοσειρών.
Περιλαμβάνει επίσης μια μέθοδο για τον ασφαλή καθαρισμό των τοπικών προς νήμα αντικειμένων για το τρέχον νήμα.


Παράδειγμα χρήσης:

````

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
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία. |
|
|  | [clear()](#clear--) | Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | Καθαρίζει τα προσωρινά αρχεία που δημιουργήθηκαν από το GroupDocs.Viewer στον σύστημα προσωρινό φάκελο. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | Καθαρίζει τις πληροφορίες καταχώρησης γραμματοσειρών από τη μνήμη heap. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Καθαρίζει με ασφάλεια τη μνήμη heap από τοπικές προς νήμα περιπτώσεις για το τρέχον νήμα. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία.
Αυτή η μέθοδος δεν επηρεάζει τις ρυθμίσεις γραμματοσειρών.


### clear() {#clear--}
```
public static void clear()
```


Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις (static και threadLocal) και διαγράφει όλα τα προσωρινά αρχεία.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Καθαρίζει τη μνήμη heap από στατικές PDF περιπτώσεις.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Καθαρίζει τα προσωρινά αρχεία που δημιουργήθηκαν από το GroupDocs.Viewer στον σύστημα προσωρινό φάκελο.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Καθαρίζει τις πληροφορίες καταχώρησης γραμματοσειρών από τη μνήμη heap.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Καθαρίζει με ασφάλεια τη μνήμη heap από τοπικές προς νήμα περιπτώσεις για το τρέχον νήμα.


