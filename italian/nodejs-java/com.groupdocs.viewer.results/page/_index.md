---
title: "Pagina"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta una singola pagina visualizzabile."
type: docs
weight: 21
url: /it/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Rappresenta una singola pagina visualizzabile.

L'interfaccia Page definisce il contratto per accedere e manipolare una singola pagina visualizzabile nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni come il numero della pagina, le dimensioni e altre proprietà.

Esempio di utilizzo:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Recupera il nome del foglio di lavoro o della pagina. |
| [setName(String name)](#setName-java.lang.String-) | Imposta il nome del foglio di lavoro o della pagina. |
| [getNumber()](#getNumber--) | Recupera il numero della pagina. |
| [setNumber(int number)](#setNumber-int-) | Imposta il numero della pagina. |
| [isVisible()](#isVisible--) | Recupera l'indicatore di visibilità della pagina. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Imposta l'indicatore di visibilità della pagina. |
| [getWidth()](#getWidth--) | Recupera la larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| [setWidth(int width)](#setWidth-int-) | Imposta la larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| [getHeight()](#getHeight--) | Recupera l'altezza della pagina in pixel quando visualizzata come JPG o PNG. |
| [setHeight(int height)](#setHeight-int-) | Imposta l'altezza della pagina in pixel quando visualizzata come JPG o PNG. |
| [getLines()](#getLines--) | Recupera le linee contenute nella pagina quando visualizzata come JPG o PNG con estrazione del testo abilitata. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Imposta le linee contenute nella pagina quando visualizzata come JPG o PNG con estrazione del testo abilitata. |
### getName() {#getName--}
```
public abstract String getName()
```


Recupera il nome del foglio di lavoro o della pagina.

**Returns:**
java.lang.String - il nome del foglio di lavoro o della pagina.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Imposta il nome del foglio di lavoro o della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | il nome da impostare per il foglio di lavoro o la pagina. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Recupera il numero della pagina.

**Returns:**
int - il numero della pagina.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Imposta il numero della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | il numero della pagina da impostare. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Recupera l'indicatore di visibilità della pagina.

**Returns:**
boolean - l'indicatore di visibilità della pagina.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Imposta l'indicatore di visibilità della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| visibile | boolean | true se la pagina è visibile, false altrimenti. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Recupera la larghezza della pagina in pixel quando visualizzata come JPG o PNG.

**Returns:**
int - la larghezza della pagina.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Imposta la larghezza della pagina in pixel quando visualizzata come JPG o PNG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | int | la larghezza da impostare per la pagina. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Recupera l'altezza della pagina in pixel quando visualizzata come JPG o PNG.

**Returns:**
int - l'altezza della pagina.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Imposta l'altezza della pagina in pixel quando visualizzata come JPG o PNG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| height | int | l'altezza da impostare per la pagina. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Recupera le linee contenute nella pagina quando visualizzata come JPG o PNG con estrazione del testo abilitata.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - le righe contenute nella pagina.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Imposta le linee contenute nella pagina quando visualizzata come JPG o PNG con estrazione del testo abilitata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| linee | java.util.List<com.groupdocs.viewer.results.Line> | l'elenco delle righe da impostare per la pagina. |

