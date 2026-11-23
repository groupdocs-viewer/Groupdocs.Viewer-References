---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει πληροφορίες προβολής για ένα αρχείο δεδομένων Outlook."
type: docs
weight: 22
url: /el/java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Αντιπροσωπεύει πληροφορίες προβολής για ένα αρχείο δεδομένων Outlook.


Η διεπαφή OutlookViewInfo ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση των πληροφοριών προβολής
για ένα αρχείο δεδομένων Outlook στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών
όπως μια λίστα φακέλων και άλλες ιδιότητες.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is OutlookViewInfoImpl.*

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFolders()](#getFolders--) | Ανακτά τη λίστα των φακέλων που περιέχονται στο αρχείο δεδομένων Outlook. |
|
|  | [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Ορίζει τη λίστα των φακέλων που περιέχονται στο αρχείο δεδομένων Outlook. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Ανακτά τη λίστα των φακέλων που περιέχονται στο αρχείο δεδομένων Outlook.


**Returns:**
java.util.List<java.lang.String> - η λίστα των φακέλων.

### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Ορίζει τη λίστα των φακέλων που περιέχονται στο αρχείο δεδομένων Outlook.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | λίστα | java.util.List<java.lang.String> | η λίστα των φακέλων. |
|

