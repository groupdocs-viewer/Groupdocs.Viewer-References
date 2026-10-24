---
title: "SearchOption"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Καθορίζει αν θα αναζητηθεί ο τρέχων φάκελος ή ο τρέχων φάκελος και όλοι οι υποφάκελοι."
type: docs
weight: 21
url: /el/java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Καθορίζει αν θα αναζητηθεί ο τρέχων φάκελος ή ο τρέχων φάκελος και όλοι οι υποφάκελοι.


Το enum SearchOption χρησιμοποιείται για τον καθορισμό του πεδίου εφαρμογής της λειτουργίας αναζήτησης γραμματοσειρών στο API του GroupDocs.Viewer.


Παράδειγμα χρήσης:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Περιλαμβάνει μόνο τον τρέχοντα φάκελο σε μια αναζήτηση. |
|
|  | [ALL_FOLDERS](#ALL-FOLDERS) | Περιλαμβάνει τον τρέχοντα φάκελο και όλους τους υποφακέλους σε μια αναζήτηση. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Περιλαμβάνει μόνο τον τρέχοντα φάκελο σε μια αναζήτηση.


### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Περιλαμβάνει τον τρέχοντα φάκελο και όλους τους υποφακέλους σε μια αναζήτηση.


### values() {#values--}
```
public static SearchOption[] values()
```




**Returns:**
com.groupdocs.viewer.fonts.SearchOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SearchOption valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
