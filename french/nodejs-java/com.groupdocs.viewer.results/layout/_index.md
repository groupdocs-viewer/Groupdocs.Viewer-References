---
title: "Disposition"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Représente une mise en page contenue dans un dessin CAO."
type: docs
weight: 17
url: /fr/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Représente une mise en page contenue dans un dessin CAO.

L'interface Layout définit le contrat pour accéder et manipuler une disposition au sein d'un dessin CAO dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour récupérer des informations telles que le nom de la disposition, les dimensions et d'autres propriétés.

Exemple d'utilisation :

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
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Récupère le nom de la disposition. |
| [setName(String name)](#setName-java.lang.String-) | Définit le nom de la disposition. |
| [getWidth()](#getWidth--) | Récupère la largeur de la disposition. |
| [setWidth(double width)](#setWidth-double-) | Définit la largeur de la disposition. |
| [getHeight()](#getHeight--) | Récupère la hauteur de la disposition. |
| [setHeight(double height)](#setHeight-double-) | Définit la hauteur de la disposition. |
| [equals(Object other)](#equals-java.lang.Object-) | Vérifie si cet objet est égal à l'objet fourni. |
### getName() {#getName--}
```
public abstract String getName()
```


Récupère le nom de la disposition.

**Returns:**
java.lang.String - le nom de la disposition.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Définit le nom de la disposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom à définir pour la disposition. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Récupère la largeur de la disposition.

**Returns:**
double - la largeur de la disposition.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Définit la largeur de la disposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | double | La largeur à définir pour la disposition. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Récupère la hauteur de la disposition.

**Returns:**
double - la hauteur de la disposition.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Définit la hauteur de la disposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| height | double | La hauteur à définir pour la disposition. |

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
