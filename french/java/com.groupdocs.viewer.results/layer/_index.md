---
title: "Layer"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente une couche contenue dans un dessin CAO."
type: docs
weight: 16
url: /fr/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Représente une couche contenue dans un dessin CAO.


L'interface Layer définit le contrat pour accéder et manipuler une couche dans un dessin CAO
dans le composant GroupDocs.Viewer. Il fournit des méthodes pour récupérer des informations telles que le nom du calque,
visibilité, et d'autres propriétés.


Exemple d'utilisation :

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

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Récupère le nom du calque. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Définit le nom du calque. |
|
|  | [isVisible()](#isVisible--) | Vérifie la visibilité du calque. |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | Définit la visibilité du calque. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Vérifie si cet objet est égal à l'objet fourni. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Récupère le nom du calque.


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - le nom du calque.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Définit le nom du calque.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Le nouveau nom du calque. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Vérifie la visibilité du calque.


Les calques de dessin CAD qui sont désactivés ou gelés sont invisibles.
Pour rendre les calques invisibles, utilisez l'option [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-).


**Returns:**
boolean -  true  si le calque est visible,  false  sinon.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Définit la visibilité du calque.


Si
true
, le calque sera visible ; si
false
, il sera caché.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | isVisible | boolean | Si le calque doit être visible ou non. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Vérifie si cet objet est égal à l'objet fourni.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | autre | java.lang.Object | L'objet à comparer. |
|

**Returns:**
booléen -  true  si les objets sont égaux,  false  sinon.

