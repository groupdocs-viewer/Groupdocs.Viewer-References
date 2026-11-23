---
title: "Layout"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει μια διάταξη που περιέχεται σε σχέδιο CAD."
type: docs
weight: 17
url: /el/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Αντιπροσωπεύει μια διάταξη που περιέχεται σε σχέδιο CAD.

Η διεπαφή Layout ορίζει τη σύμβαση για πρόσβαση και διαχείριση μιας διάταξης μέσα σε ένα σχέδιο CAD στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών όπως το όνομα της διάταξης, οι διαστάσεις και άλλες ιδιότητες.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayoutImpl.*
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Ανακτά το όνομα της διάταξης. |
| [setName(String name)](#setName-java.lang.String-) | Ορίζει το όνομα της διάταξης. |
| [getWidth()](#getWidth--) | Ανακτά το πλάτος της διάταξης. |
| [setWidth(double width)](#setWidth-double-) | Ορίζει το πλάτος της διάταξης. |
| [getHeight()](#getHeight--) | Ανακτά το ύψος της διάταξης. |
| [setHeight(double height)](#setHeight-double-) | Ορίζει το ύψος της διάταξης. |
| [equals(Object other)](#equals-java.lang.Object-) | Ελέγχει αν αυτό το αντικείμενο είναι ίσο με το παρεχόμενο αντικείμενο. |
### getName() {#getName--}
```
public abstract String getName()
```


Ανακτά το όνομα της διάταξης.

**Returns:**
java.lang.String - το όνομα της διάταξης.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Ορίζει το όνομα της διάταξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | Το όνομα που θα οριστεί για τη διάταξη. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Ανακτά το πλάτος της διάταξης.

**Returns:**
double - το πλάτος της διάταξης.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Ορίζει το πλάτος της διάταξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | double | Το πλάτος που θα οριστεί για τη διάταξη. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Ανακτά το ύψος της διάταξης.

**Returns:**
double - το ύψος της διάταξης.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Ορίζει το ύψος της διάταξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| height | double | Το ύψος που θα οριστεί για τη διάταξη. |

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
