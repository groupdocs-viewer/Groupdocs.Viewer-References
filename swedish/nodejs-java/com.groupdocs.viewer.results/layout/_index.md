---
title: "Layout"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar en layout som finns i en CAD-ritning."
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Representerar en layout som finns i en CAD-ritning.

Layout‑gränssnittet definierar kontraktet för åtkomst och manipulering av en layout i en CAD‑ritning i GroupDocs.Viewer‑komponenten. Det tillhandahåller metoder för att hämta information såsom layoutens namn, dimensioner och andra egenskaper.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayoutImpl.*
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Hämtar layoutens namn. |
| [setName(String name)](#setName-java.lang.String-) | Ställer in layoutens namn. |
| [getWidth()](#getWidth--) | Hämtar layoutens bredd. |
| [setWidth(double width)](#setWidth-double-) | Ställer in layoutens bredd. |
| [getHeight()](#getHeight--) | Hämtar layoutens höjd. |
| [setHeight(double height)](#setHeight-double-) | Ställer in layoutens höjd. |
| [equals(Object other)](#equals-java.lang.Object-) | Kontrollerar om detta objekt är lika med det angivna objektet. |
### getName() {#getName--}
```
public abstract String getName()
```


Hämtar layoutens namn.

**Returns:**
java.lang.String - layoutens namn.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Ställer in layoutens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namnet att ställa in för layouten. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Hämtar layoutens bredd.

**Returns:**
double - layoutens bredd.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Ställer in layoutens bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | double | Bredden att ställa in för layouten. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Hämtar layoutens höjd.

**Returns:**
double - layoutens höjd.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Ställer in layoutens höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| height | double | Höjden att ställa in för layouten. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Kontrollerar om detta objekt är lika med det angivna objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annat | java.lang.Object | Objektet att jämföra. |

**Returns:**
boolean -  true  om objekten är lika,  false  annars.
