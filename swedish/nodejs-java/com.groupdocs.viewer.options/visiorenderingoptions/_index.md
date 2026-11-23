---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Innehåller alternativ för rendering av Visio-dokument."
type: docs
weight: 36
url: /sv/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Innehåller alternativ för rendering av Visio-dokument.

Klassen VisioRenderingOptions tillhandahåller alternativ för bearbetning och rendering av Visio-filer i GroupDocs.Viewer-komponenten. Den kapslar in inställningar och parametrar som kan användas för att styra renderingsprocessen och utdataformatet för Visio-dokument. För detaljer, se [dokumentation][].

Exempel på användning:

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Initierar en ny instans av klassen VisioRenderingOptions. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Rendera endast Visio-figurer, exklusive diagrammet. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Sätter flaggan för att rendera endast Visio-figurer, exklusive diagrammet. |
| [getFigureWidth()](#getFigureWidth--) | Hämtar figurens bredd. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Sätter figurens bredd. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Initierar en ny instans av klassen VisioRenderingOptions.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Rendera endast Visio-figurer, exklusive diagrammet.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  om endast Visio-figurer ska renderas,  false  annars.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Sätter flaggan för att rendera endast Visio-figurer, exklusive diagrammet.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  för att rendera endast Visio-figurer,  false  för att inkludera diagrammet. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Hämtar figurens bredd. Höjden beräknas automatiskt.

**Returns:**
int - figurens bredd.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Ställer in figurens bredd. Höjden beräknas automatiskt.

***Note:** Default value is 100.*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| figureWidth | int | Figurens bredd. |

