---
title: "Layout"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt een lay‑out voor die is opgenomen in een CAD‑tekening."
type: docs
weight: 17
url: /nl/java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Stelt een lay‑out voor die is opgenomen in een CAD‑tekening.


De Layout interface definieert het contract voor het benaderen en manipuleren van een layout binnen een CAD-tekening
in de GroupDocs.Viewer component. Het biedt methoden om informatie op te halen zoals de layoutnaam,
afmetingen, en andere eigenschappen.


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayoutImpl.*

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Haalt de naam van de layout op. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Stelt de naam van de layout in. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van de layout op. |
|
|  | [setWidth(double width)](#setWidth-double-) | Stelt de breedte van de layout in. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van de layout op. |
|
|  | [setHeight(double height)](#setHeight-double-) | Stelt de hoogte van de layout in. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Controleert of dit object gelijk is aan het opgegeven object. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Haalt de naam van de layout op.


**Returns:**
java.lang.String - de naam van de layout.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Stelt de naam van de layout in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | De naam die moet worden ingesteld voor de lay-out. |
|

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Haalt de breedte van de layout op.


**Returns:**
double - de breedte van de lay-out.

### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Stelt de breedte van de layout in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | width | double | De breedte die moet worden ingesteld voor de lay-out. |
|

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Haalt de hoogte van de layout op.


**Returns:**
double - de hoogte van de lay-out.

### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Stelt de hoogte van de layout in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | hoogte | double | De hoogte die moet worden ingesteld voor de lay-out. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Controleert of dit object gelijk is aan het opgegeven object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | anders | java.lang.Object | Het object om te vergelijken. |
|

**Returns:**
boolean -  true  als de objecten gelijk zijn,  false  anders.

