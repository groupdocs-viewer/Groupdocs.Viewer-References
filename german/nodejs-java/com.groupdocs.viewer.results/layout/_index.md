---
title: "Layout"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt ein Layout dar, das in einer CAD‑Zeichnung enthalten ist."
type: docs
weight: 17
url: /de/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Stellt ein Layout dar, das in einer CAD‑Zeichnung enthalten ist.

Das Layout-Interface definiert den Vertrag für den Zugriff auf und die Manipulation eines Layouts innerhalb einer CAD‑Zeichnung in der GroupDocs.Viewer‑Komponente. Es bietet Methoden zum Abrufen von Informationen wie dem Layoutnamen, den Abmessungen und anderen Eigenschaften.

Beispielhafte Verwendung:

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
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Ruft den Namen des Layouts ab. |
| [setName(String name)](#setName-java.lang.String-) | Setzt den Namen des Layouts. |
| [getWidth()](#getWidth--) | Ruft die Breite des Layouts ab. |
| [setWidth(double width)](#setWidth-double-) | Setzt die Breite des Layouts. |
| [getHeight()](#getHeight--) | Ruft die Höhe des Layouts ab. |
| [setHeight(double height)](#setHeight-double-) | Setzt die Höhe des Layouts. |
| [equals(Object other)](#equals-java.lang.Object-) | Prüft, ob dieses Objekt dem bereitgestellten Objekt gleich ist. |
### getName() {#getName--}
```
public abstract String getName()
```


Ruft den Namen des Layouts ab.

**Returns:**
java.lang.String - der Name des Layouts.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Setzt den Namen des Layouts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Der Name, der für das Layout festzulegen ist. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Ruft die Breite des Layouts ab.

**Returns:**
double - die Breite des Layouts.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Setzt die Breite des Layouts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | double | Die Breite, die für das Layout festzulegen ist. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Ruft die Höhe des Layouts ab.

**Returns:**
double - die Höhe des Layouts.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Setzt die Höhe des Layouts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| height | double | Die Höhe, die für das Layout festzulegen ist. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Prüft, ob dieses Objekt dem bereitgestellten Objekt gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| andere | java.lang.Object | Das zu vergleichende Objekt. |

**Returns:**
boolean -  true  wenn die Objekte gleich sind,  false  sonst.
