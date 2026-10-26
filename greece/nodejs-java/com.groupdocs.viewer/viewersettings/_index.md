---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του στοιχείου Viewer."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του στοιχείου Viewer.

Η κλάση ViewerSettings παρέχει επιλογές και ιδιότητες για την προσαρμογή της συμπεριφοράς του στοιχείου GroupDocs.Viewer κατά τη διαδικασία απόδοσης του εγγράφου. Μπορείτε να χρησιμοποιήσετε αυτήν την κλάση για να καθορίσετε διάφορες ρυθμίσεις, όπως καταγραφέα, προσαρμοσμένη υλοποίηση cache και άλλα.

Παράδειγμα χρήσης:

```

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης ViewerSettings. |
| [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης ViewerSettings. |
| [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης ViewerSettings. |
| [ViewerSettings()](#ViewerSettings--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης ViewerSettings. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLogger()](#getLogger--) | Λαμβάνει την υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Errors, Warnings, Traces). |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ορίζει την υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Errors, Warnings, Traces). |
| [getCache()](#getCache--) | Λαμβάνει την υλοποίηση του cache που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων απόδοσης. |
| [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Ορίζει την υλοποίηση του cache που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων απόδοσης. |
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης ViewerSettings.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Το cache. |
| logger | com.groupdocs.foundation.logging.ILogger | Ο καταγραφέας. |

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης ViewerSettings.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | Ο καταγραφέας. |

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης ViewerSettings.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Το cache. |

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης ViewerSettings.

### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Λαμβάνει την υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή (Errors, Warnings, Traces).

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
| logger | com.groupdocs.foundation.logging.ILogger | Η υλοποίηση του καταγραφέα προς ορισμό. |

### getCache() {#getCache--}
```
public final Cache getCache()
```


Λαμβάνει την υλοποίηση του cache που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων απόδοσης.

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
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Η υλοποίηση του cache. |

