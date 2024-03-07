---
title: Character
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents a relatively positioned rectangle that contains a single character.
type: docs
weight: 14
url: /nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Represents a relatively positioned rectangle that contains a single character.

The Character interface defines the contract for accessing and manipulating a character represented by a rectangle in the GroupDocs.Viewer component. It provides methods to retrieve information such as the character itself, position, and size of the rectangle.

Example usage:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
