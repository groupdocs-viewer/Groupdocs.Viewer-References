---
title: "Layer"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει ένα στρώμα που περιέχεται σε σχέδιο CAD."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Αντιπροσωπεύει ένα στρώμα που περιέχεται σε σχέδιο CAD.

Η διεπαφή Layer ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση ενός στρώματος μέσα σε ένα σχέδιο CAD στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών όπως το όνομα του στρώματος, η ορατότητα και άλλες ιδιότητες.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayerImpl.*
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Ανακτά το όνομα του στρώματος. |
| [setName(String name)](#setName-java.lang.String-) | Ορίζει το όνομα του στρώματος. |
| [isVisible()](#isVisible--) | Ελέγχει την ορατότητα του στρώματος. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | Ορίζει την ορατότητα του στρώματος. |
| [equals(Object other)](#equals-java.lang.Object-) | Ελέγχει αν αυτό το αντικείμενο είναι ίσο με το παρεχόμενο αντικείμενο. |
### getName() {#getName--}
```
public abstract String getName()
```


Ανακτά το όνομα του στρώματος.

**Note:** Layer names are case sensitive.

**Returns:**
java.lang.String - το όνομα του στρώματος.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Ορίζει το όνομα του στρώματος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Το νέο όνομα για το στρώμα. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Ελέγχει την ορατότητα του στρώματος.

Τα στρώματα σχεδίου CAD που είναι απενεργοποιημένα ή παγωμένα είναι αόρατα. Για την απόδοση των αόρατων στρωμάτων, χρησιμοποιήστε την επιλογή [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-).

**Returns:**
boolean -  true  εάν το στρώμα είναι ορατό,  false  διαφορετικά.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Ορίζει την ορατότητα του στρώματος.

Εάν  true , το στρώμα θα είναι ορατό· εάν  false , θα είναι κρυφό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | Εάν το στρώμα πρέπει να είναι ορατό ή όχι. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Ελέγχει αν αυτό το αντικείμενο είναι ίσο με το παρεχόμενο αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| άλλο | java.lang.Object | Το αντικείμενο προς σύγκριση. |

**Returns:**
boolean -  true  εάν τα αντικείμενα είναι ίσα,  false  διαφορετικά.
