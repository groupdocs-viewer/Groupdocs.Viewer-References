---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει πληροφορίες προβολής για ένα έγγραφο MS Project."
type: docs
weight: 25
url: /el/java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Αντιπροσωπεύει πληροφορίες προβολής για ένα έγγραφο MS Project.


Η διεπαφή ProjectManagementViewInfo ορίζει τη σύμβαση για πρόσβαση και διαχείριση πληροφοριών προβολής
για ένα έγγραφο MS Project στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών
όπως οι ημερομηνίες έναρξης και λήξης, καθώς και άλλες ιδιότητες.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getStartDate()](#getStartDate--) | Ανακτά την ημερομηνία και ώρα από την οποία ξεκίνησε το έργο. |
|
|  | [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Ορίζει την ημερομηνία και ώρα έναρξης για το έργο. |
|
|  | [getEndDate()](#getEndDate--) | Ανακτά την ημερομηνία και ώρα ολοκλήρωσης του έργου. |
|
|  | [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Ορίζει την ημερομηνία και ώρα λήξης για το έργο. |
|
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Ανακτά την ημερομηνία και ώρα από την οποία ξεκίνησε το έργο.


**Returns:**
java.util.Date - η ημερομηνία και ώρα έναρξης του έργου.

### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Ορίζει την ημερομηνία και ώρα έναρξης για το έργο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | startDate | java.util.Date | η νέα ημερομηνία και ώρα έναρξης που θα οριστεί. |
|

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Ανακτά την ημερομηνία και ώρα ολοκλήρωσης του έργου.


**Returns:**
java.util.Date - η ημερομηνία και ώρα λήξης του έργου.

### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Ορίζει την ημερομηνία και ώρα λήξης για το έργο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | endDate | java.util.Date | η νέα ημερομηνία και ώρα λήξης που θα οριστεί. |
|

