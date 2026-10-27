---
title: "Sida"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar en enskild sida som kan visas."
type: docs
weight: 21
url: /sv/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Representerar en enskild sida som kan visas.

Page‑gränssnittet definierar kontraktet för att komma åt och manipulera en enskild sida som kan visas i GroupDocs.Viewer‑komponenten. Det tillhandahåller metoder för att hämta information såsom sidnummer, storlek och andra egenskaper.

Exempel på användning:

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Hämtar namnet på kalkylbladet eller sidan. |
| [setName(String name)](#setName-java.lang.String-) | Ställer in namnet på kalkylbladet eller sidan. |
| [getNumber()](#getNumber--) | Hämtar sidnumret. |
| [setNumber(int number)](#setNumber-int-) | Ställer in sidnumret. |
| [isVisible()](#isVisible--) | Hämtar indikatorn för sidans synlighet. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Ställer in indikatorn för sidans synlighet. |
| [getWidth()](#getWidth--) | Hämtar sidans bredd i pixlar när den visas som JPG eller PNG. |
| [setWidth(int width)](#setWidth-int-) | Ställer in sidans bredd i pixlar när den visas som JPG eller PNG. |
| [getHeight()](#getHeight--) | Hämtar sidans höjd i pixlar när den visas som JPG eller PNG. |
| [setHeight(int height)](#setHeight-int-) | Ställer in sidans höjd i pixlar när den visas som JPG eller PNG. |
| [getLines()](#getLines--) | Hämtar raderna som finns i sidan när den visas som JPG eller PNG med aktiverad textutvinning. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Ställer in raderna som finns i sidan när den visas som JPG eller PNG med aktiverad textutvinning. |
### getName() {#getName--}
```
public abstract String getName()
```


Hämtar namnet på kalkylbladet eller sidan.

**Returns:**
java.lang.String - namnet på kalkylbladet eller sidan.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Ställer in namnet på kalkylbladet eller sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | namnet att sätta för kalkylbladet eller sidan. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Hämtar sidnumret.

**Returns:**
int - sidnumret.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Ställer in sidnumret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | int | sidnumret att sätta. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Hämtar indikatorn för sidans synlighet.

**Returns:**
boolean - indikatorn för sidans synlighet.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Ställer in indikatorn för sidans synlighet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| synlig | boolean | true om sidan är synlig, false annars. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Hämtar sidans bredd i pixlar när den visas som JPG eller PNG.

**Returns:**
int - sidans bredd.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Ställer in sidans bredd i pixlar när den visas som JPG eller PNG.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | bredden att sätta för sidan. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Hämtar sidans höjd i pixlar när den visas som JPG eller PNG.

**Returns:**
int - sidans höjd.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Ställer in sidans höjd i pixlar när den visas som JPG eller PNG.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| height | int | höjden att sätta för sidan. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Hämtar raderna som finns i sidan när den visas som JPG eller PNG med aktiverad textutvinning.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - raderna som finns på sidan.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Ställer in raderna som finns i sidan när den visas som JPG eller PNG med aktiverad textutvinning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rader | java.util.List<com.groupdocs.viewer.results.Line> | listan med rader att sätta för sidan. |

