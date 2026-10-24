---
title: "Line"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει ένα σχετικό ορθογώνιο που περιέχει μία μόνο γραμμή."
type: docs
weight: 18
url: /el/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Αντιπροσωπεύει ένα σχετικό ορθογώνιο που περιέχει μία μόνο γραμμή.


Η διεπαφή Line ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση μιας γραμμής που αντιπροσωπεύεται από ένα ορθογώνιο
στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών όπως το κείμενο της γραμμής,
η θέση και το μέγεθος του ορθογωνίου.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LineImpl.*

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWords()](#getWords--) | Ανακτά τις λέξεις που περιέχονται στη γραμμή. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Ορίζει τις λέξεις που περιέχονται στη γραμμή. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Ανακτά τις λέξεις που περιέχονται στη γραμμή.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - οι λέξεις που περιέχονται στη γραμμή.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Ορίζει τις λέξεις που περιέχονται στη γραμμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | οι λέξεις που περιέχονται στη γραμμή. |
|

