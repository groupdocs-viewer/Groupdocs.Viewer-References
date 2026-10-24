---
title: "Character"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente un rectangle positionné relativement qui contient un seul caractère."
type: docs
weight: 14
url: /fr/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Représente un rectangle positionné relativement qui contient un seul caractère.


L'interface Character définit le contrat pour accéder et manipuler un caractère représenté par un rectangle
dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour récupérer des informations telles que le caractère lui‑même,
position et taille du rectangle.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

