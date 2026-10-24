---
title: "Layer"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta un livello contenuto in un disegno CAD."
type: docs
weight: 16
url: /it/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Rappresenta un livello contenuto in un disegno CAD.


L'interfaccia Layer definisce il contratto per accedere e manipolare un livello all'interno di un disegno CAD
nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni come il nome del livello,
visibilità e altre proprietà.


Esempio di utilizzo:

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

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getName()](#getName--) | Recupera il nome del livello. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Imposta il nome del livello. |
|
|  | [isVisible()](#isVisible--) | Verifica la visibilità del livello. |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | Imposta la visibilità del livello. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Verifica se questo oggetto è uguale all'oggetto fornito. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Recupera il nome del livello.


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - il nome del livello.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Imposta il nome del livello.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | nome | java.lang.String | Il nuovo nome per il livello. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Verifica la visibilità del livello.


I livelli di disegno CAD che sono disattivati o congelati sono invisibili.
Per renderizzare i livelli invisibili, utilizza l'opzione [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-).


**Returns:**
boolean -  true  se il livello è visibile,  false  altrimenti.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Imposta la visibilità del livello.


Se
true
, il livello sarà visibile; se
false
, sarà nascosto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | isVisible | boolean | Se il livello dovrebbe essere visibile o meno. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Verifica se questo oggetto è uguale all'oggetto fornito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | altro | java.lang.Object | L'oggetto da confrontare. |
|

**Returns:**
boolean -  true  se gli oggetti sono uguali,  false  altrimenti.

