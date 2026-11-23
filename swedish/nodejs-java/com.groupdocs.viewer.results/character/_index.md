---
title: "Tecken"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar en relativt placerad rektangel som innehåller ett enda tecken."
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Representerar en relativt placerad rektangel som innehåller ett enda tecken.

Character‑gränssnittet definierar kontraktet för att komma åt och manipulera ett tecken som representeras av en rektangel i GroupDocs.Viewer‑komponenten. Det tillhandahåller metoder för att hämta information såsom själva tecknet, positionen och rektangelns storlek.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
