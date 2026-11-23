---
title: "Layer"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente une couche contenue dans un dessin CAO."
type: docs
weight: 16
url: /fr/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Représente une couche contenue dans un dessin CAO.

L'interface Layer définit le contrat pour accéder et manipuler une couche dans un dessin CAD du composant GroupDocs.Viewer. Elle fournit des méthodes pour récupérer des informations telles que le nom de la couche, la visibilité et d'autres propriétés.

Exemple d'utilisation :

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
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Récupère le nom de la couche. |
| [setName(String name)](#setName-java.lang.String-) | Définit le nom de la couche. |
| [isVisible()](#isVisible--) | Vérifie la visibilité de la couche. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | Définit la visibilité de la couche. |
| [equals(Object other)](#equals-java.lang.Object-) | Vérifie si cet objet est égal à l'objet fourni. |
### getName() {#getName--}
```
public abstract String getName()
```


Récupère le nom de la couche.

**Note:** Layer names are case sensitive.

**Returns:**
java.lang.String - le nom de la couche.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Définit le nom de la couche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nouveau nom de la couche. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Vérifie la visibilité de la couche.

Les couches du dessin CAD qui sont désactivées ou gelées sont invisibles. Pour rendre visibles les couches qui sont invisibles, utilisez l'option [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-).

**Returns:**
boolean -  true  si la couche est visible,  false  sinon.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Définit la visibilité de la couche.

Si  true , la couche sera visible ; si  false , elle sera cachée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | Indique si la couche doit être visible ou non. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Vérifie si cet objet est égal à l'objet fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autre | java.lang.Object | L'objet à comparer. |

**Returns:**
boolean -  true  si les objets sont égaux,  false  sinon.
