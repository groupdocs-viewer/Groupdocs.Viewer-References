---
title: "CacheKeys"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει μεθόδους για την ανάκτηση του μοναδικού αναγνωριστικού μιας καταχώρησης στην κρυφή μνήμη."
type: docs
weight: 10
url: /el/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Παρέχει μεθόδους για την ανάκτηση του μοναδικού αναγνωριστικού μιας καταχώρησης στην κρυφή μνήμη.


Η κλάση σας επιτρέπει να δημιουργείτε κλειδιά cache με βάση διαφορετικές παραμέτρους, όπως η διαδρομή του εγγράφου, οι επιλογές απόδοσης και το όνομα του πόρου.
Αυτά τα κλειδιά cache μπορούν να χρησιμοποιηθούν για την αποθήκευση και ανάκτηση των δεδομένων cache για αποδοτική απόδοση εγγράφων.


Παράδειγμα χρήσης:

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | Επιστρέφει το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει μια συλλογή αντικειμένων [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αρχείο συνημμένου. |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αντικείμενο [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αντικείμενο [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αρχείο. |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αρχείο σελίδας. |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Επιστρέφει ένα μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αντικείμενο [Resource](../../com.groupdocs.viewer.results/resource). |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Επιστρέφει μια συμβολοσειρά φίλτρου για την αναζήτηση καταχωρήσεων cache που αντιπροσωπεύουν αντικείμενα [Resource](../../com.groupdocs.viewer.results/resource). |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Επιστρέφει το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει μια συλλογή αντικειμένων [Attachment](../../com.groupdocs.viewer.results/attachment).


**Returns:**
java.lang.String - το μοναδικό αναγνωριστικό για την καταχώρηση cache των συνημμένων.

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αρχείο συνημμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | attachmentId | java.lang.String | Το μοναδικό αναγνωριστικό του συνημμένου (στο πλαίσιο ενός μόνο αρχείου). |
|

**Returns:**
java.lang.String - το μοναδικό αναγνωριστικό για την καταχώρηση cache του αρχείου συνημμένου.

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αντικείμενο [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String - το μοναδικό αναγνωριστικό για την καταχώρηση cache.

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αντικείμενο [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String - το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αντικείμενο [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αρχείο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extension | java.lang.String | The επίθημα του ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc". |
|

**Returns:**
java.lang.String - το μοναδικό αναγνωριστικό για την καταχώρηση της κρυφής μνήμης που αντιπροσωπεύει ένα αρχείο.

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Ανακτά το μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αρχείο σελίδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageNumber | int | Ο αριθμός της σελίδας. |
|
|  | extension | java.lang.String | The επίθημα του ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc". |
|

**Returns:**
java.lang.String - το μοναδικό αναγνωριστικό για την καταχώρηση της κρυφής μνήμης που αντιπροσωπεύει ένα αρχείο σελίδας.

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Επιστρέφει ένα μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει ένα αντικείμενο [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageNumber | int | Ο αριθμός της σελίδας. |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | Ο πόρος HTML. |
|

**Returns:**
java.lang.String - το μοναδικό αναγνωριστικό για την καταχώρηση cache.

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Επιστρέφει μια συμβολοσειρά φίλτρου για την αναζήτηση καταχωρήσεων cache που αντιπροσωπεύουν αντικείμενα [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pageNumber | int | Ο αριθμός της σελίδας. |
|

**Returns:**
java.lang.String - η συμβολοσειρά φίλτρου για την αναζήτηση καταχωρήσεων κρυφής μνήμης.

