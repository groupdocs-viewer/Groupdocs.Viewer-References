---
title: "Line"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει ένα σχετικό ορθογώνιο που περιέχει μία μόνο γραμμή."
type: docs
weight: 18
url: /el/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Αντιπροσωπεύει ένα σχετικό ορθογώνιο που περιέχει μία μόνο γραμμή.

Η Line interface ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση μιας γραμμής που αναπαρίσταται από ένα ορθογώνιο στο component GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών όπως το κείμενο της γραμμής, η θέση και το μέγεθος του ορθογωνίου.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LineImpl.*
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWords()](#getWords--) | Ανακτά τις λέξεις που περιέχονται στη line. |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Ορίζει τις λέξεις που περιέχονται στη line. |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Ανακτά τις λέξεις που περιέχονται στη line.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - οι λέξεις που περιέχονται στη line.
### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Ορίζει τις λέξεις που περιέχονται στη line.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | οι λέξεις που περιέχονται στη line. |

