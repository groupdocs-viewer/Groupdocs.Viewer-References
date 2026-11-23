---
title: "Σελίδα"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει μια μοναδική σελίδα που μπορεί να προβληθεί."
type: docs
weight: 21
url: /el/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Αντιπροσωπεύει μια μοναδική σελίδα που μπορεί να προβληθεί.

Το interface Page ορίζει τη σύμβαση για πρόσβαση και διαχείριση μιας μοναδικής σελίδας που μπορεί να προβληθεί στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για ανάκτηση πληροφοριών όπως ο αριθμός σελίδας, το μέγεθος και άλλες ιδιότητες.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Ανακτά το όνομα του φύλλου εργασίας ή της σελίδας. |
| [setName(String name)](#setName-java.lang.String-) | Ορίζει το όνομα του φύλλου εργασίας ή της σελίδας. |
| [getNumber()](#getNumber--) | Ανακτά τον αριθμό σελίδας. |
| [setNumber(int number)](#setNumber-int-) | Ορίζει τον αριθμό σελίδας. |
| [isVisible()](#isVisible--) | Ανακτά τον δείκτη ορατότητας της σελίδας. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Ορίζει τον δείκτη ορατότητας της σελίδας. |
| [getWidth()](#getWidth--) | Ανακτά το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| [setWidth(int width)](#setWidth-int-) | Ορίζει το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| [getHeight()](#getHeight--) | Ανακτά το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| [setHeight(int height)](#setHeight-int-) | Ορίζει το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| [getLines()](#getLines--) | Ανακτά τις γραμμές που περιέχονται στη σελίδα όταν προβάλλεται ως JPG ή PNG με ενεργοποιημένη εξαγωγή κειμένου. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Ορίζει τις γραμμές που περιέχονται στη σελίδα όταν προβάλλεται ως JPG ή PNG με ενεργοποιημένη εξαγωγή κειμένου. |
### getName() {#getName--}
```
public abstract String getName()
```


Ανακτά το όνομα του φύλλου εργασίας ή της σελίδας.

**Returns:**
java.lang.String - το όνομα του φύλλου εργασίας ή της σελίδας.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Ορίζει το όνομα του φύλλου εργασίας ή της σελίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String | το όνομα που θα οριστεί για το φύλλο εργασίας ή τη σελίδα. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Ανακτά τον αριθμό σελίδας.

**Returns:**
int - ο αριθμός σελίδας.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Ορίζει τον αριθμό σελίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριθμός | int | ο αριθμός σελίδας που θα οριστεί. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Ανακτά τον δείκτη ορατότητας της σελίδας.

**Returns:**
boolean - ο δείκτης ορατότητας της σελίδας.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Ορίζει τον δείκτη ορατότητας της σελίδας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ορατό | boolean | true εάν η σελίδα είναι ορατή, false διαφορετικά. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Ανακτά το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG.

**Returns:**
int - το πλάτος της σελίδας.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Ορίζει το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | int | το πλάτος που θα οριστεί για τη σελίδα. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Ανακτά το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG.

**Returns:**
int - το ύψος της σελίδας.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Ορίζει το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| height | int | το ύψος που θα οριστεί για τη σελίδα. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Ανακτά τις γραμμές που περιέχονται στη σελίδα όταν προβάλλεται ως JPG ή PNG με ενεργοποιημένη εξαγωγή κειμένου.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - οι γραμμές που περιέχονται στη σελίδα.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Ορίζει τις γραμμές που περιέχονται στη σελίδα όταν προβάλλεται ως JPG ή PNG με ενεργοποιημένη εξαγωγή κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γραμμές | java.util.List<com.groupdocs.viewer.results.Line> | η λίστα των γραμμών που θα οριστεί για τη σελίδα. |

