---
title: "Layer"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt eine Ebene dar, die in einer CAD‑Zeichnung enthalten ist."
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Stellt eine Ebene dar, die in einer CAD‑Zeichnung enthalten ist.

Das Layer-Interface definiert den Vertrag für den Zugriff auf und die Manipulation einer Ebene innerhalb einer CAD-Zeichnung in der GroupDocs.Viewer-Komponente. Es bietet Methoden zum Abrufen von Informationen wie dem Ebenennamen, der Sichtbarkeit und anderen Eigenschaften.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayerImpl.*
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Ruft den Namen der Ebene ab. |
| [setName(String name)](#setName-java.lang.String-) | Setzt den Namen der Ebene. |
| [isVisible()](#isVisible--) | Prüft die Sichtbarkeit der Ebene. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | Setzt die Sichtbarkeit der Ebene. |
| [equals(Object other)](#equals-java.lang.Object-) | Prüft, ob dieses Objekt dem bereitgestellten Objekt gleich ist. |
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


Setzt den Namen der Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Der neue Name für die Ebene. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Prüft die Sichtbarkeit der Ebene.

Die CAD-Zeichnungsebenen, die deaktiviert oder eingefroren sind, sind unsichtbar. Um unsichtbare Ebenen zu rendern, verwenden Sie die [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-) Option.

**Returns:**
boolean -  true  wenn die Ebene sichtbar ist,  false  sonst.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Setzt die Sichtbarkeit der Ebene.

Wenn  true , ist die Ebene sichtbar; wenn  false , wird sie ausgeblendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isVisible | boolean | Ob die Ebene sichtbar sein soll oder nicht. |

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
