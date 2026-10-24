---
title: "Character"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta un rettangolo posizionato relativamente che contiene un singolo carattere."
type: docs
weight: 14
url: /it/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Rappresenta un rettangolo posizionato relativamente che contiene un singolo carattere.


L'interfaccia Character definisce il contratto per accedere e manipolare un carattere rappresentato da un rettangolo
nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni come il carattere stesso,
posizione e dimensione del rettangolo.


Esempio di utilizzo:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

