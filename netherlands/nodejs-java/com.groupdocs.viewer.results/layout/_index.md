---
title: "Layout"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt een lay-out voor die is opgenomen in een CAD-tekening."
type: docs
weight: 17
url: /nl/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Stelt een lay-out voor die is opgenomen in een CAD-tekening.

De Layout-interface definieert het contract voor het benaderen en manipuleren van een lay-out binnen een CAD-tekening in de GroupDocs.Viewer-component. Het biedt methoden om informatie op te halen, zoals de naam van de lay-out, afmetingen en andere eigenschappen.

Voorbeeldgebruik:

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

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Haalt de naam van de lay-out op. |
| [setName(String name)](#setName-java.lang.String-) | Stelt de naam van de lay-out in. |
| [getWidth()](#getWidth--) | Haalt de breedte van de lay-out op. |
| [setWidth(double width)](#setWidth-double-) | Stelt de breedte van de lay-out in. |
| [getHeight()](#getHeight--) | Haalt de hoogte van de lay-out op. |
| [setHeight(double height)](#setHeight-double-) | Stelt de hoogte van de lay-out in. |
| [equals(Object other)](#equals-java.lang.Object-) | Controleert of dit object gelijk is aan het opgegeven object. |
### getName() {#getName--}
```
public abstract String getName()
```


Haalt de naam van de lay-out op.

**Returns:**
java.lang.String - de naam van de lay-out.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Stelt de naam van de lay-out in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam die voor de lay-out moet worden ingesteld. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Haalt de breedte van de lay-out op.

**Returns:**
double - de breedte van de lay-out.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Stelt de breedte van de lay-out in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | double | De breedte die voor de lay-out moet worden ingesteld. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Haalt de hoogte van de lay-out op.

**Returns:**
double - de hoogte van de lay-out.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Stelt de hoogte van de lay-out in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| height | double | De hoogte die voor de lay-out moet worden ingesteld. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Controleert of dit object gelijk is aan het opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| anders | java.lang.Object | Het object om te vergelijken. |

**Returns:**
boolean -  true  als de objecten gelijk zijn,  false  anders.
