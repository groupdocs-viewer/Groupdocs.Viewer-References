---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Enthält Optionen zum Rendern von Visio-Dokumenten."
type: docs
weight: 36
url: /de/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Enthält Optionen zum Rendern von Visio-Dokumenten.

Die VisioRenderingOptions‑Klasse bietet Optionen für die Verarbeitung und das Rendern von Visio‑Dateien in der GroupDocs.Viewer‑Komponente. Sie kapselt Einstellungen und Parameter, die zur Steuerung des Rendering‑Prozesses und des Ausgabeformats für Visio‑Dokumente verwendet werden können. Weitere Details finden Sie in der [Dokumentation][].

Beispielhafte Verwendung:

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Initialisiert eine neue Instanz der VisioRenderingOptions‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Nur Visio‑Figuren rendern, das Diagramm ausschließen. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Setzt das Flag, um nur Visio‑Figuren zu rendern, das Diagramm auszuschließen. |
| [getFigureWidth()](#getFigureWidth--) | Liefert die Breite der Figur. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Setzt die Breite der Figur. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Initialisiert eine neue Instanz der VisioRenderingOptions‑Klasse.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Nur Visio‑Figuren rendern, das Diagramm ausschließen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolescher -  true  wenn nur Visio‑Figuren gerendert werden sollen,  false  sonst.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Setzt das Flag, um nur Visio‑Figuren zu rendern, das Diagramm auszuschließen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  um nur Visio‑Figuren zu rendern,  false  um das Diagramm einzubeziehen. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Ruft die Breite der Figur ab. Die Höhe wird automatisch berechnet.

**Returns:**
int - die Breite der Figur.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Setzt die Breite der Figur. Die Höhe wird automatisch berechnet.

***Note:** Default value is 100.*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figureWidth | int | Die Breite der Figur. |

