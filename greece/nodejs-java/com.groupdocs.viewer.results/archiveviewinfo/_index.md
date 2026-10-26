---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει πληροφορίες προβολής για ένα αρχείο αρχειοθήκης."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Αντιπροσωπεύει πληροφορίες προβολής για ένα αρχείο αρχειοθήκης.

Το interface ArchiveViewInfo ορίζει τη σύμβαση για την ανάκτηση πληροφοριών προβολής ειδικά για ένα αρχείο αρχείου στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για πρόσβαση σε λεπτομέρειες όπως ο αριθμός σελίδων, οι διαστάσεις και οι επιλογές απόδοσης ειδικά για αρχεία αρχείου.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFolders()](#getFolders--) | Ανακτά τη λίστα των φακέλων που περιέχονται στο αρχείο αρχείου. |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Ορίζει τη λίστα των φακέλων που περιέχονται στο αρχείο αρχείου. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Ανακτά τη λίστα των φακέλων που περιέχονται στο αρχείο αρχείου.

**Returns:**
java.util.List<java.lang.String> - η λίστα των φακέλων.
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Ορίζει τη λίστα των φακέλων που περιέχονται στο αρχείο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| φάκελοι | java.util.List<java.lang.String> | η λίστα των φακέλων. |

