---
title: "Character"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет относительно позиционированный прямоугольник, содержащий один символ."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Представляет относительно позиционированный прямоугольник, содержащий один символ.

Интерфейс Character определяет контракт для доступа и манипулирования символом, представленным прямоугольником, в компоненте GroupDocs.Viewer. Он предоставляет методы для получения информации, такой как сам символ, позиция и размер прямоугольника.

Пример использования:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
