---
title: "Layer"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt een laag voor die is opgenomen in een CAD-tekening."
type: docs
weight: 16
url: /nl/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Stelt een laag voor die is opgenomen in een CAD-tekening.

De Layer-interface definieert het contract voor het benaderen en manipuleren van een laag binnen een CAD-tekening in de GroupDocs.Viewer-component. Het biedt methoden om informatie op te halen, zoals de laagnaam, zichtbaarheid en andere eigenschappen.

Voorbeeldgebruik:

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

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Haal de naam van de laag op. |
| [setName(String name)](#setName-java.lang.String-) | Stel de naam van de laag in. |
| [isVisible()](#isVisible--) | Controleert de zichtbaarheid van de laag. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | Stelt de zichtbaarheid van de laag in. |
| [equals(Object other)](#equals-java.lang.Object-) | Controleert of dit object gelijk is aan het opgegeven object. |
### getName() {#getName--}
```
public abstract String getName()
```


Haal de naam van de laag op.

**Note:** Layer names are case sensitive.

**Returns:**
java.lang.String - de naam van de laag.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Stel de naam van de laag in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De nieuwe naam voor de laag. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Controleert de zichtbaarheid van de laag.

De CAD-tekenlagen die zijn uitgeschakeld of bevroren, zijn onzichtbaar. Om onzichtbare lagen weer te geven, gebruik de [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-) optie.

**Returns:**
boolean -  true  als de laag zichtbaar is,  false  anders.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Stelt de zichtbaarheid van de laag in.

Als  true , is de laag zichtbaar; als  false , wordt deze verborgen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| isVisible | boolean | Of de laag zichtbaar moet zijn of niet. |

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
