---
title: "Word"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta un rettangolo posizionato relativamente che contiene una singola parola."
type: docs
weight: 26
url: /it/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Rappresenta un rettangolo posizionato relativamente che contiene una singola parola.

L'interfaccia Word rappresenta una parola all'interno di un rettangolo posizionato relativamente nel componente GroupDocs.Viewer. Estende l'interfaccia TextElement e fornisce metodi aggiuntivi per accedere e manipolare il contenuto della parola.

Esempio di utilizzo:

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
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCharacters()](#getCharacters--) | Recupera i caratteri contenuti nella parola. |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Imposta i caratteri contenuti nella parola. |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Recupera i caratteri contenuti nella parola.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - l'elenco dei caratteri.
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Imposta i caratteri contenuti nella parola.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| caratteri | java.util.List<com.groupdocs.viewer.results.Character> | l'elenco dei caratteri da impostare. |

