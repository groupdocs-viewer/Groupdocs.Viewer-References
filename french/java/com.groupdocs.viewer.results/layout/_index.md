---
title: "Layout"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente une mise en page contenue dans un dessin CAO."
type: docs
weight: 17
url: /fr/java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Représente une mise en page contenue dans un dessin CAO.


L'interface Layout définit le contrat pour accéder et manipuler un layout dans un dessin CAO
dans le composant GroupDocs.Viewer. Il fournit des méthodes pour récupérer des informations telles que le nom du layout,
dimensions, et d'autres propriétés.


Exemple d'utilisation :

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

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Récupère le nom du layout. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Définit le nom du layout. |
|
|  | [getWidth()](#getWidth--) | Récupère la largeur du layout. |
|
|  | [setWidth(double width)](#setWidth-double-) | Définit la largeur du layout. |
|
|  | [getHeight()](#getHeight--) | Récupère la hauteur du layout. |
|
|  | [setHeight(double height)](#setHeight-double-) | Définit la hauteur du layout. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Vérifie si cet objet est égal à l'objet fourni. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Récupère le nom du layout.


**Returns:**
java.lang.String - le nom du layout.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Définit le nom du layout.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | Le nom à définir pour la mise en page. |
|

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Récupère la largeur du layout.


**Returns:**
double - la largeur de la mise en page.

### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Définit la largeur du layout.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | width | double | La largeur à définir pour la mise en page. |
|

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Récupère la hauteur du layout.


**Returns:**
double - la hauteur de la mise en page.

### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Définit la hauteur du layout.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | hauteur | double | La hauteur à définir pour la mise en page. |
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

