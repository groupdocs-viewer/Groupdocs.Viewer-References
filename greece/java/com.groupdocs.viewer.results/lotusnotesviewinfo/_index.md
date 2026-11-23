---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει πληροφορίες προβολής για την αποθήκευση βάσης δεδομένων Lotus Notes."
type: docs
weight: 19
url: /el/java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Αντιπροσωπεύει πληροφορίες προβολής για την αποθήκευση βάσης δεδομένων Lotus Notes.


Η διεπαφή LotusNotesViewInfo ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση των πληροφοριών προβολής
για την αποθήκευση βάσης δεδομένων Lotus Notes στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών
όπως ο αριθμός σημειώσεων και άλλες ιδιότητες.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getNotesCount()](#getNotesCount--) | Ανακτά τον αριθμό των σημειώσεων στην αποθήκευση. |
|
|  | [setNotesCount(int count)](#setNotesCount-int-) | Ορίζει τον αριθμό των σημειώσεων στην αποθήκευση. |
|
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Ανακτά τον αριθμό των σημειώσεων στην αποθήκευση.


**Returns:**
int - ο αριθμός των σημειώσεων στην αποθήκευση.

### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Ορίζει τον αριθμό των σημειώσεων στην αποθήκευση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αριθμός | int | ο αριθμός των σημειώσεων στην αποθήκευση. |
|

