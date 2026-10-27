---
title: "Word"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa un rectángulo posicionado relativamente que contiene una sola palabra."
type: docs
weight: 26
url: /es/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Representa un rectángulo posicionado relativamente que contiene una sola palabra.

La interfaz Word representa una palabra dentro de un rectángulo posicionado relativamente en el componente GroupDocs.Viewer. Extiende la interfaz TextElement y proporciona métodos adicionales para acceder y manipular el contenido de la palabra.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is WordImpl.*
## Métodos

| Método | Descripción |
| --- | --- |
| [getCharacters()](#getCharacters--) | Obtiene los caracteres contenidos por la palabra. |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Establece los caracteres contenidos por la palabra. |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Obtiene los caracteres contenidos por la palabra.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - la lista de caracteres.
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Establece los caracteres contenidos por la palabra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| caracteres | java.util.List<com.groupdocs.viewer.results.Character> | la lista de caracteres a establecer. |

