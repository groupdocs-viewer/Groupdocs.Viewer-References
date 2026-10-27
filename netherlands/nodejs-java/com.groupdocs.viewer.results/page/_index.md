---
title: "Pagina"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt een enkele pagina voor die kan worden bekeken."
type: docs
weight: 21
url: /nl/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Stelt een enkele pagina voor die kan worden bekeken.

De Page-interface definieert het contract voor het benaderen en manipuleren van een enkele pagina die kan worden bekeken in de GroupDocs.Viewer-component. Het biedt methoden om informatie op te halen, zoals het paginanummer, de grootte en andere eigenschappen.

Voorbeeldgebruik:

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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Haalt de naam van het werkblad of de pagina op. |
| [setName(String name)](#setName-java.lang.String-) | Stelt de naam van het werkblad of de pagina in. |
| [getNumber()](#getNumber--) | Haalt het paginanummer op. |
| [setNumber(int number)](#setNumber-int-) | Stelt het paginanummer in. |
| [isVisible()](#isVisible--) | Haalt de zichtbaarheidindicator van de pagina op. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Stelt de zichtbaarheidindicator van de pagina in. |
| [getWidth()](#getWidth--) | Haalt de breedte van de pagina in pixels op bij weergave als JPG of PNG. |
| [setWidth(int width)](#setWidth-int-) | Stelt de breedte van de pagina in pixels in bij weergave als JPG of PNG. |
| [getHeight()](#getHeight--) | Haalt de hoogte van de pagina in pixels op bij weergave als JPG of PNG. |
| [setHeight(int height)](#setHeight-int-) | Stelt de hoogte van de pagina in pixels in bij weergave als JPG of PNG. |
| [getLines()](#getLines--) | Haalt de regels op die in de pagina staan bij weergave als JPG of PNG met ingeschakelde tekstelextractie. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Stelt de regels in die in de pagina staan bij weergave als JPG of PNG met ingeschakelde tekstelextractie. |
### getName() {#getName--}
```
public abstract String getName()
```


Haalt de naam van het werkblad of de pagina op.

**Returns:**
java.lang.String - de naam van het werkblad of de pagina.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Stelt de naam van het werkblad of de pagina in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | de naam die moet worden ingesteld voor het werkblad of de pagina. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Haalt het paginanummer op.

**Returns:**
int - het paginanummer.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Stelt het paginanummer in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | het paginanummer dat moet worden ingesteld. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Haalt de zichtbaarheidindicator van de pagina op.

**Returns:**
boolean - de zichtbaarheidindicator van de pagina.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Stelt de zichtbaarheidindicator van de pagina in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| zichtbaar | boolean | true als de pagina zichtbaar is, false anders. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Haalt de breedte van de pagina in pixels op bij weergave als JPG of PNG.

**Returns:**
int - de breedte van de pagina.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Stelt de breedte van de pagina in pixels in bij weergave als JPG of PNG.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | de breedte die voor de pagina moet worden ingesteld. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Haalt de hoogte van de pagina in pixels op bij weergave als JPG of PNG.

**Returns:**
int - de hoogte van de pagina.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Stelt de hoogte van de pagina in pixels in bij weergave als JPG of PNG.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| height | int | de hoogte die voor de pagina moet worden ingesteld. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Haalt de regels op die in de pagina staan bij weergave als JPG of PNG met ingeschakelde tekstelextractie.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - de regels die op de pagina staan.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Stelt de regels in die in de pagina staan bij weergave als JPG of PNG met ingeschakelde tekstelextractie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | de lijst met regels die voor de pagina moeten worden ingesteld. |

