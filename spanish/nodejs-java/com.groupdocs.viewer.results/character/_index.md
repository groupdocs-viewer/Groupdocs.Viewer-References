---
title: "Carácter"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa un rectángulo posicionado relativamente que contiene un solo carácter."
type: docs
weight: 14
url: /es/nodejs-java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

Representa un rectángulo posicionado relativamente que contiene un solo carácter.

La interfaz Character define el contrato para acceder y manipular un carácter representado por un rectángulo en el componente GroupDocs.Viewer. Proporciona métodos para obtener información como el propio carácter, la posición y el tamaño del rectángulo.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
```

***Note:** The default implementation of this interface is CharacterImpl.*
