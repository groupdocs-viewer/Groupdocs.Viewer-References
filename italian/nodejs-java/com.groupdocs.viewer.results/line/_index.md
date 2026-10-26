---
title: "Line"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta un rettangolo posizionato relativamente che contiene una singola riga."
type: docs
weight: 18
url: /it/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Rappresenta un rettangolo posizionato relativamente che contiene una singola riga.

L'interfaccia Line definisce il contratto per accedere e manipolare una linea rappresentata da un rettangolo nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni come il testo della linea, la posizione e le dimensioni del rettangolo.

Esempio di utilizzo:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LineImpl.*
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWords()](#getWords--) | Recupera le parole contenute nella linea. |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Imposta le parole contenute nella linea. |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Recupera le parole contenute nella linea.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - le parole contenute nella linea.
### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Imposta le parole contenute nella linea.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | le parole contenute nella linea. |

