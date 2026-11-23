---
title: "Page"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt een enkele pagina voor die kan worden bekeken."
type: docs
weight: 23
url: /nl/java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Stelt een enkele pagina voor die kan worden bekeken.


De Page-interface definieert het contract voor het benaderen en manipuleren van een enkele pagina
die kan worden bekeken in de GroupDocs.Viewer-component. Het biedt methoden om op te halen
informatie zoals het paginanummer, de grootte en andere eigenschappen.


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is PageImpl.*

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Haalt de naam van het werkblad of de pagina op. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Stelt de naam van het werkblad of de pagina in. |
|
|  | [getNumber()](#getNumber--) | Haalt het paginanummer op. |
|
|  | [setNumber(int number)](#setNumber-int-) | Stelt het paginanummer in. |
|
|  | [isVisible()](#isVisible--) | Haalt de paginazichtindicator op. |
|
|  | [setVisible(boolean visible)](#setVisible-boolean-) | Stelt de paginazichtindicator in. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van de pagina in pixels op bij weergave als JPG of PNG. |
|
|  | [setWidth(int width)](#setWidth-int-) | Stelt de breedte van de pagina in pixels in bij weergave als JPG of PNG. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van de pagina in pixels op bij weergave als JPG of PNG. |
|
|  | [setHeight(int height)](#setHeight-int-) | Stelt de hoogte van de pagina in pixels in bij weergave als JPG of PNG. |
|
|  | [getLines()](#getLines--) | Haalt de lijnen op die in de pagina staan bij weergave als JPG of PNG met ingeschakelde Tekstextractie. |
|
|  | [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Stelt de lijnen in die in de pagina staan bij weergave als JPG of PNG met ingeschakelde Tekstextractie. |
|
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
|  | name | java.lang.String | de naam die moet worden ingesteld voor het werkblad of de pagina. |
|

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
|  | number | int | het paginanummer dat moet worden ingesteld. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Haalt de paginazichtindicator op.


**Returns:**
boolean - de paginazichtindicator.

### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Stelt de paginazichtindicator in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | zichtbaar | boolean | true als de pagina zichtbaar is, anders false. |
|

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
|  | width | int | de breedte die moet worden ingesteld voor de pagina. |
|

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
|  | hoogte | int | de hoogte die moet worden ingesteld voor de pagina. |
|

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Haalt de lijnen op die in de pagina staan bij weergave als JPG of PNG met ingeschakelde Tekstextractie.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - de lijnen die in de pagina staan.

### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Stelt de lijnen in die in de pagina staan bij weergave als JPG of PNG met ingeschakelde Tekstextractie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | regels | java.util.List<com.groupdocs.viewer.results.Line> | de lijst met lijnen die moet worden ingesteld voor de pagina. |
|

