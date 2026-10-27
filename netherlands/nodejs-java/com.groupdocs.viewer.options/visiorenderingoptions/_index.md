---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Bevat opties voor het renderen van Visio-documenten."
type: docs
weight: 36
url: /nl/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Bevat opties voor het renderen van Visio-documenten.

De VisioRenderingOptions-klasse biedt opties voor het verwerken en renderen van Visio-bestanden in de GroupDocs.Viewer-component. Het omvat instellingen en parameters die kunnen worden gebruikt om het renderproces en het uitvoerformaat voor Visio-documenten te beheersen. Voor details, zie de [documentation][].

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Initialiseert een nieuw exemplaar van de  VisioRenderingOptions  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Render alleen Visio-figuren, exclusief het diagram. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Stelt de vlag in om alleen Visio-figuren te renderen, exclusief het diagram. |
| [getFigureWidth()](#getFigureWidth--) | Haalt de breedte van de figuur op. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Stelt de breedte van de figuur in. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Initialiseert een nieuw exemplaar van de  VisioRenderingOptions  klasse.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Render alleen Visio-figuren, exclusief het diagram.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  als alleen Visio-figuren moeten worden gerenderd,  false  anders.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Stelt de vlag in om alleen Visio-figuren te renderen, exclusief het diagram.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  om alleen Visio-figuren te renderen,  false  om het diagram op te nemen. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Haalt de breedte van de figuur op. De hoogte wordt automatisch berekend.

**Returns:**
int - de breedte van de figuur.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Stelt de breedte van de figuur in. De hoogte wordt automatisch berekend.

***Note:** Default value is 100.*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| figureWidth | int | De breedte van de figuur. |

