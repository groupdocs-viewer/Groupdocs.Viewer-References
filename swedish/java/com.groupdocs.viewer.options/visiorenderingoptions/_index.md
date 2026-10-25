---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Innehåller alternativ för rendering av Visio-dokument."
type: docs
weight: 36
url: /sv/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Innehåller alternativ för rendering av Visio-dokument.


Klassen VisioRenderingOptions tillhandahåller alternativ för bearbetning och rendering av Visio-filer
i GroupDocs.Viewer-komponenten. Den kapslar in inställningar och parametrar som kan användas
för att kontrollera renderingsprocessen och utdataformatet för Visio-dokument.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


Exempel på användning:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | Initierar en ny instans av |
VisioRenderingOptions
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Rendera endast Visio-figurer, exklusive diagrammet. |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Ställer in flaggan för att rendera endast Visio-figurer, exklusive diagrammet. |
|
|  | [getFigureWidth()](#getFigureWidth--) | Hämtar figurens bredd. |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Ställer in figurens bredd. |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Initierar en ny instans av
VisioRenderingOptions
klassen.


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Rendera endast Visio-figurer, exklusive diagrammet.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Returns:**
boolean -  true  om endast Visio-figurer ska renderas,  false  annars.

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Ställer in flaggan för att rendera endast Visio-figurer, exklusive diagrammet.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  för att rendera endast Visio-figurer,  false  för att inkludera diagrammet. |
|

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
|  | figureWidth | int | Figurens bredd. |
|

