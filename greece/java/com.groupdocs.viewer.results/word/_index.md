---
title: "Word"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει ένα σχετικό ορθογώνιο που περιέχει μία μόνο λέξη."
type: docs
weight: 28
url: /el/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Αντιπροσωπεύει ένα σχετικό ορθογώνιο που περιέχει μία μόνο λέξη.


Η διεπαφή Word αντιπροσωπεύει μια λέξη μέσα σε ένα σχετικώς τοποθετημένο ορθογώνιο στο στοιχείο GroupDocs.Viewer.
Επεκτείνει τη διεπαφή TextElement και παρέχει πρόσθετες μεθόδους για την πρόσβαση και τη διαχείριση του περιεχομένου της λέξης.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is WordImpl.*

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | Ανακτά τους χαρακτήρες που περιέχονται στη λέξη. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Ορίζει τους χαρακτήρες που περιέχονται στη λέξη. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Ανακτά τους χαρακτήρες που περιέχονται στη λέξη.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - η λίστα των χαρακτήρων.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Ορίζει τους χαρακτήρες που περιέχονται στη λέξη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | χαρακτήρες | java.util.List<com.groupdocs.viewer.results.Character> | η λίστα των χαρακτήρων προς ορισμό. |
|

