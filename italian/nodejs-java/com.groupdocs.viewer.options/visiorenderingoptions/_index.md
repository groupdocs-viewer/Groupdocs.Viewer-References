---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Contiene opzioni per il rendering dei documenti Visio."
type: docs
weight: 36
url: /it/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Contiene opzioni per il rendering dei documenti Visio.

La classe VisioRenderingOptions fornisce opzioni per l'elaborazione e il rendering dei file Visio nel componente GroupDocs.Viewer. Incapsula impostazioni e parametri che possono essere usati per controllare il processo di rendering e il formato di output per i documenti Visio. Per i dettagli, vedi la [documentation][].

Esempio di utilizzo:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Inizializza una nuova istanza della classe  VisioRenderingOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Renderizza solo le figure Visio, escludendo il diagramma. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Imposta il flag per renderizzare solo le figure Visio, escludendo il diagramma. |
| [getFigureWidth()](#getFigureWidth--) | Recupera la larghezza della figura. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Imposta la larghezza della figura. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Inizializza una nuova istanza della classe  VisioRenderingOptions.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Renderizza solo le figure Visio, escludendo il diagramma.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  se devono essere renderizzate solo le figure Visio,  false  altrimenti.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Imposta il flag per renderizzare solo le figure Visio, escludendo il diagramma.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  per renderizzare solo le figure Visio,  false  per includere il diagramma. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Recupera la larghezza della figura. L'altezza verrà calcolata automaticamente.

**Returns:**
int - la larghezza della figura.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Imposta la larghezza della figura. L'altezza verrà calcolata automaticamente.

***Note:** Default value is 100.*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| figureWidth | int | La larghezza della figura. |

