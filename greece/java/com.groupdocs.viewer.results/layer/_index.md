---
title: "Layer"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει ένα επίπεδο που περιέχεται σε ένα σχέδιο CAD."
type: docs
weight: 16
url: /el/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Αντιπροσωπεύει ένα επίπεδο που περιέχεται σε ένα σχέδιο CAD.


Η διεπαφή Layer ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση ενός επιπέδου μέσα σε ένα σχέδιο CAD
στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών όπως το όνομα του επιπέδου,
ορατότητα και άλλες ιδιότητες.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Ανακτά το όνομα του επιπέδου. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Ορίζει το όνομα του επιπέδου. |
|
|  | [isVisible()](#isVisible--) | Ελέγχει την ορατότητα του επιπέδου. |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | Ορίζει την ορατότητα του επιπέδου. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Ελέγχει αν αυτό το αντικείμενο είναι ίσο με το παρεχόμενο αντικείμενο. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Ανακτά το όνομα του επιπέδου.


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - το όνομα του επιπέδου.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Ορίζει το όνομα του επιπέδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το νέο όνομα για το επίπεδο. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Ελέγχει την ορατότητα του επιπέδου.


Τα επίπεδα σχεδίασης CAD που είναι απενεργοποιημένα ή παγωμένα είναι αόρατα.
Για την απόδοση επιπέδων που είναι αόρατα, χρησιμοποιήστε την επιλογή [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-).


**Returns:**
boolean -  true  αν το επίπεδο είναι ορατό,  false  διαφορετικά.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Ορίζει την ορατότητα του επιπέδου.


Αν
true
, το επίπεδο θα είναι ορατό· αν
false
, θα είναι κρυφό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | isVisible | boolean | Αν το επίπεδο πρέπει να είναι ορατό ή όχι. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Ελέγχει αν αυτό το αντικείμενο είναι ίσο με το παρεχόμενο αντικείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | άλλο | java.lang.Object | Το αντικείμενο για σύγκριση. |
|

**Returns:**
boolean -  true  εάν τα αντικείμενα είναι ίσα,  false  διαφορετικά.

