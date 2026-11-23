---
title: "Χαρακτήρας"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει ένα σχετικό ορθογώνιο που περιέχει έναν μόνο χαρακτήρα."
type: docs
weight: 14
url: /el/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Αντιπροσωπεύει ένα σχετικό ορθογώνιο που περιέχει έναν μόνο χαρακτήρα.


Η διεπαφή Character ορίζει τη σύμβαση για την πρόσβαση και τη διαχείριση ενός χαρακτήρα που αναπαρίσταται από ένα ορθογώνιο.
στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για την ανάκτηση πληροφοριών όπως ο ίδιος ο χαρακτήρας,
η θέση και το μέγεθος του ορθογωνίου.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

