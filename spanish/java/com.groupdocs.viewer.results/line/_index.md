---
title: "Line"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa un rectángulo posicionado relativamente que contiene una sola línea."
type: docs
weight: 18
url: /es/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Representa un rectángulo posicionado relativamente que contiene una sola línea.


La interfaz Line define el contrato para acceder y manipular una línea representada por un rectángulo
en el componente GroupDocs.Viewer. Proporciona métodos para obtener información como el texto de la línea,
posición y tamaño del rectángulo.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LineImpl.*

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWords()](#getWords--) | Recupera las palabras contenidas en la línea. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Establece las palabras contenidas en la línea. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Recupera las palabras contenidas en la línea.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - las palabras contenidas en la línea.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Establece las palabras contenidas en la línea.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | las palabras contenidas en la línea. |
|

