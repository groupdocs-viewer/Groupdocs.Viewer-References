---
title: "Ebene"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt eine Ebene dar, die in einer CAD‑Zeichnung enthalten ist."
type: docs
weight: 16
url: /de/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Stellt eine Ebene dar, die in einer CAD‑Zeichnung enthalten ist.


Das Layer-Interface definiert den Vertrag für den Zugriff auf und die Manipulation einer Ebene innerhalb einer CAD-Zeichnung
im GroupDocs.Viewer-Komponente. Sie bietet Methoden zum Abrufen von Informationen wie dem Ebenennamen,
Sichtbarkeit und weitere Eigenschaften.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Ruft den Namen der Ebene ab. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Legt den Namen der Ebene fest. |
|
|  | [isVisible()](#isVisible--) | Prüft die Sichtbarkeit der Ebene. |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | Legt die Sichtbarkeit der Ebene fest. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Prüft, ob dieses Objekt dem bereitgestellten Objekt gleich ist. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Ruft den Namen der Ebene ab.


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - der Name der Ebene.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Legt den Namen der Ebene fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Der neue Name für die Ebene. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Prüft die Sichtbarkeit der Ebene.


Die CAD-Zeichnungsebenen, die ausgeschaltet oder eingefroren sind, sind unsichtbar.
Um unsichtbare Ebenen zu rendern, verwenden Sie die Option [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-).


**Returns:**
boolean -  true  wenn die Ebene sichtbar ist,  false  sonst.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Legt die Sichtbarkeit der Ebene fest.


Wenn
true
, ist die Ebene sichtbar; wenn
false
, wird sie ausgeblendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | isVisible | boolesch | Ob die Ebene sichtbar sein soll oder nicht. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Prüft, ob dieses Objekt dem bereitgestellten Objekt gleich ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | andere | java.lang.Object | Das Objekt zum Vergleichen. |
|

**Returns:**
boolean -  true  wenn die Objekte gleich sind,  false  sonst.

