---
title: "Teken"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt een relatief gepositioneerde rechthoek voor die één teken bevat."
type: docs
weight: 14
url: /nl/nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Stelt een relatief gepositioneerde rechthoek voor die één teken bevat.

De Character-interface definieert het contract voor het benaderen en manipuleren van een teken dat wordt weergegeven door een rechthoek in de GroupDocs.Viewer-component. Het biedt methoden om informatie op te halen, zoals het teken zelf, de positie en de grootte van de rechthoek.

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
