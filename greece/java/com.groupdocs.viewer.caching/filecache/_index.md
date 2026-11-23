---
title: "FileCache"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει μια τοπική κρυφή μνήμη στο δίσκο."
type: docs
weight: 11
url: /el/java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Αντιπροσωπεύει μια τοπική κρυφή μνήμη στο δίσκο.


Η κλάση FileCache αντιπροσωπεύει μια τοπική κρυφή μνήμη στο δίσκο στο στοιχείο GroupDocs.Viewer.
Παρέχει λειτουργικότητα για αποθήκευση και ανάκτηση δεδομένων στην κρυφή μνήμη του δίσκου για αποδοτική απόδοση εγγράφων.


Παράδειγμα χρήσης:

````

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
````


Για να χρησιμοποιήσετε το FileCache, πρέπει να δημιουργήσετε μια παρουσία αυτής της κλάσης και να τη μεταβιβάσετε στο αντικείμενο ViewerSettings.
Το αντικείμενο Viewer θα χρησιμοποιεί τότε το FileCache για σκοπούς κρυφής μνήμης κατά την απόδοση εγγράφων.


***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer.
Μπορείτε επίσης να υλοποιήσετε τη δική σας προσαρμοσμένη κρυφή μνήμη υλοποιώντας τη διεπαφή Cache.*

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Δημιουργεί μια νέα παρουσία της |
FileCache
κλάσης.
|
|  | [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Δημιουργεί μια νέα παρουσία της |
FileCache
κλάσης.
|
|  | [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Δημιουργεί μια νέα παρουσία της |
FileCache
κλάσης.
|
|  | [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Δημιουργεί μια νέα παρουσία της |
FileCache
κλάσης.
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCachePath()](#getCachePath--) | Λαμβάνει τη σχετική ή απόλυτη διαδρομή προς το φάκελο κρυφής μνήμης. |
|
|  | [getCacheSubFolder()](#getCacheSubFolder--) | Ο υπο-φάκελος που θα προσαρτηθεί στη διαδρομή κρυφής μνήμης. |
|
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Σειριοποιεί δεδομένα στον τοπικό δίσκο. |
|
|  | [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Αποσειριοποιεί δεδομένα που σχετίζονται με αυτό το κλειδί εάν υπάρχουν. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Επιστρέφει όλα τα ονόματα αρχείων που περιέχουν το φίλτρο στο όνομα αρχείου. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Δημιουργεί μια νέα παρουσία της
FileCache
κλάσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cachePath | java.lang.String | Η σχετική ή απόλυτη διαδρομή όπου θα αποθηκευτεί η κρυφή μνήμη εγγράφου. |
|

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Δημιουργεί μια νέα παρουσία της
FileCache
κλάσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | Η σχετική ή απόλυτη διαδρομή όπου θα αποθηκευτεί η κρυφή μνήμη εγγράφου. |
|

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Δημιουργεί μια νέα παρουσία της
FileCache
κλάσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cachePath | java.lang.String | Η σχετική ή απόλυτη διαδρομή όπου θα αποθηκευτεί η κρυφή μνήμη εγγράφου. |
|
|  | cacheSubFolder | java.lang.String | Ο υποφάκελος που θα προσαρτηθεί στο  cachePath . |
|

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Δημιουργεί μια νέα παρουσία της
FileCache
κλάσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | Η σχετική ή απόλυτη διαδρομή όπου θα αποθηκευτεί η κρυφή μνήμη εγγράφου. |
|
|  | cacheSubFolder | java.lang.String | Ο υποφάκελος που θα προσαρτηθεί στο  cachePath . |
|

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Λαμβάνει τη σχετική ή απόλυτη διαδρομή προς το φάκελο κρυφής μνήμης.


**Returns:**
java.lang.String - Διαδρομή προς το φάκελο cache.

### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


Ο υπο-φάκελος που θα προσαρτηθεί στη διαδρομή κρυφής μνήμης.


**Returns:**
java.lang.String - ο υποφάκελος που θα προσαρτηθεί.

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Σειριοποιεί δεδομένα στον τοπικό δίσκο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κλειδί | java.lang.String | Το μοναδικό αναγνωριστικό για την καταχώρηση cache. |
|
|  | τιμή | java.lang.Object | Το αντικείμενο για σειριοποίηση. |
|

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Αποσειριοποιεί δεδομένα που σχετίζονται με αυτό το κλειδί εάν υπάρχουν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κλειδί | java.lang.String | Ένα κλειδί που προσδιορίζει την ζητούμενη καταχώρηση. |
|
|  | clazz | java.lang.Class<T> | Η κλάση της αναμενόμενης τιμής. |
|

**Returns:**
T - η εντοπισμένη τιμή ή null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Επιστρέφει όλα τα ονόματα αρχείων που περιέχουν το φίλτρο στο όνομα αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | φίλτρο | java.lang.String | Το φίλτρο προς χρήση. |
|

**Returns:**
java.util.List<java.lang.String> - Ονόματα αρχείων που περιέχουν το φίλτρο στο όνομα αρχείου.

