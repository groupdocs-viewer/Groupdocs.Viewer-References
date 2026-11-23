---
title: "Layer"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar ett lager som finns i en CAD-ritning."
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Representerar ett lager som finns i en CAD-ritning.

Layer‑gränssnittet definierar kontraktet för åtkomst och manipulering av ett lager i en CAD‑ritning i GroupDocs.Viewer‑komponenten. Det tillhandahåller metoder för att hämta information såsom lagrets namn, synlighet och andra egenskaper.

Exempel på användning:

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Hämtar lagrets namn. |
| [setName(String name)](#setName-java.lang.String-) | Sätter lagrets namn. |
| [isVisible()](#isVisible--) | Kontrollerar lagrets synlighet. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | Sätter lagrets synlighet. |
| [equals(Object other)](#equals-java.lang.Object-) | Kontrollerar om detta objekt är lika med det angivna objektet. |
### getName() {#getName--}
```
public abstract String getName()
```


Hämtar lagrets namn.

**Note:** Layer names are case sensitive.

**Returns:**
java.lang.String - lagrets namn.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Sätter lagrets namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Det nya namnet för lagret. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Kontrollerar lagrets synlighet.

CAD‑ritningslagren som är avstängda eller frysta är osynliga. För att rendera lager som är osynliga, använd alternativet [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-).

**Returns:**
boolean -  true  om lagret är synligt,  false  annars.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Sätter lagrets synlighet.

Om  true , blir lagret synligt; om  false , blir det dolt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isVisible | boolean | Om lagret ska vara synligt eller inte. |

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
