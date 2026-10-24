---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του στοιχείου Viewer."
type: docs
weight: 13
url: /el/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του στοιχείου Viewer.


Η κλάση ViewerSettings παρέχει επιλογές και ιδιότητες για την προσαρμογή της συμπεριφοράς του στοιχείου GroupDocs.Viewer κατά τη διαδικασία απόδοσης του εγγράφου.
Μπορείτε να χρησιμοποιήσετε αυτήν την κλάση για να καθορίσετε διάφορες ρυθμίσεις, όπως καταγραφέα, προσαρμοσμένη υλοποίηση cache και άλλα.


Παράδειγμα χρήσης:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Αρχικοποιεί μια νέα παρουσία του |
ViewerSettings
κλάσης.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Αρχικοποιεί μια νέα παρουσία του |
ViewerSettings
κλάσης.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Αρχικοποιεί μια νέα παρουσία του |
ViewerSettings
κλάσης.
|
|  | [ViewerSettings()](#ViewerSettings--) | Αρχικοποιεί μια νέα παρουσία του |
ViewerSettings
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getLogger()](#getLogger--) | Αποκτά την υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Errors, Warnings, Traces). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ορίζει την υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Errors, Warnings, Traces). |
|
|  | [getCache()](#getCache--) | Αποκτά την υλοποίηση του cache που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων απόδοσης. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Ορίζει την υλοποίηση του cache που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων απόδοσης. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Αρχικοποιεί μια νέα παρουσία του
ViewerSettings
κλάσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Το cache. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Ο καταγραφέας. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Αρχικοποιεί μια νέα παρουσία του
ViewerSettings
κλάσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Ο καταγραφέας. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Αρχικοποιεί μια νέα παρουσία του
ViewerSettings
κλάσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Το cache. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Αρχικοποιεί μια νέα παρουσία του
ViewerSettings
κλάσης.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Αποκτά την υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Errors, Warnings, Traces).


**Returns:**
com.groupdocs.foundation.logging.ILogger - η υλοποίηση του καταγραφέα.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Ορίζει την υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Errors, Warnings, Traces).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Η υλοποίηση του καταγραφέα προς ορισμό. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


Αποκτά την υλοποίηση του cache που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων απόδοσης.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Ορίζει την υλοποίηση του cache που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων απόδοσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Η υλοποίηση της κρυφής μνήμης. |
|

