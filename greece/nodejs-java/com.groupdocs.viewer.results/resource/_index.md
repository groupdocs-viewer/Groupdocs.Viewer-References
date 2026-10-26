---
title: "Resource"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει πόρο HTML όπως γραμματοσειρά, στυλ, εικόνα ή γραφικά."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Αντιπροσωπεύει πόρο HTML όπως γραμματοσειρά, στυλ, εικόνα ή γραφικά.

Η κλάση Resource αντιπροσωπεύει έναν πόρο που χρησιμοποιείται στην απόδοση HTML στο στοιχείο GroupDocs.Viewer. Μπορεί να αντιπροσωπεύει διάφορους τύπους πόρων, όπως γραμματοσειρές, στυλ, εικόνες ή γραφικά, που περιλαμβάνονται ή αναφέρονται στην παραγόμενη έξοδο HTML κατά τη διαδικασία απόδοσης.

Παράδειγμα χρήσης:

```

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης Resource. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFileName()](#getFileName--) | Επιστρέφει το όνομα αρχείου του πόρου. |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | Ορίζει το όνομα αρχείου του πόρου. |
| [isNested()](#isNested--) | Επιστρέφει αν ο πόρος βρίσκεται μέσα σε άλλο πόρο, π.χ. ένας πόρος γραμματοσειράς που βρίσκεται σε πόρο CSS ή SVG. |
| [setNested(boolean nested)](#setNested-boolean-) | Ορίζει αν ο πόρος βρίσκεται μέσα σε άλλο πόρο. |
| [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης Resource.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το όνομα αρχείου του πόρου. |
| ενσωματωμένο | boolean | Δείχνει αν ο πόρος βρίσκεται μέσα σε άλλο πόρο, π.χ., ένας πόρος γραμματοσειράς που βρίσκεται σε πόρο CSS ή SVG. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Επιστρέφει το όνομα αρχείου του πόρου.

**Returns:**
java.lang.String - το όνομα αρχείου του πόρου.
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Ορίζει το όνομα αρχείου του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το νέο όνομα αρχείου για τον πόρο. |

### isNested() {#isNested--}
```
public final boolean isNested()
```


Επιστρέφει αν ο πόρος βρίσκεται μέσα σε άλλο πόρο, π.χ. ένας πόρος γραμματοσειράς που βρίσκεται σε πόρο CSS ή SVG.

**Returns:**
boolean - Αν ο πόρος βρίσκεται μέσα σε άλλο πόρο.
### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Ορίζει αν ο πόρος βρίσκεται μέσα σε άλλο πόρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ενσωματωμένο | boolean | Αν ο πόρος πρέπει να οριστεί ως ενσωματωμένος. |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.

**Returns:**
java.lang.String - η αναπαράσταση συμβολοσειράς του τρέχοντος αντικειμένου.
