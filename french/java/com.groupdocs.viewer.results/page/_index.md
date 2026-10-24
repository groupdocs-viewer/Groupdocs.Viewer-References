---
title: "Page"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente une page unique qui peut être affichée."
type: docs
weight: 23
url: /fr/java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Représente une page unique qui peut être affichée.


L'interface Page définit le contrat pour accéder et manipuler une seule page
qui peut être affichée dans le composant GroupDocs.Viewer. Elle fournit des méthodes pour récupérer
des informations telles que le numéro de page, la taille et d'autres propriétés.


Exemple d'utilisation :

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is PageImpl.*

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getName()](#getName--) | Récupère le nom de la feuille de calcul ou de la page. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Définit le nom de la feuille de calcul ou de la page. |
|
|  | [getNumber()](#getNumber--) | Récupère le numéro de page. |
|
|  | [setNumber(int number)](#setNumber-int-) | Définit le numéro de page. |
|
|  | [isVisible()](#isVisible--) | Récupère l'indicateur de visibilité de la page. |
|
|  | [setVisible(boolean visible)](#setVisible-boolean-) | Définit l'indicateur de visibilité de la page. |
|
|  | [getWidth()](#getWidth--) | Récupère la largeur de la page en pixels lors de la visualisation en JPG ou PNG. |
|
|  | [setWidth(int width)](#setWidth-int-) | Définit la largeur de la page en pixels lors de la visualisation en JPG ou PNG. |
|
|  | [getHeight()](#getHeight--) | Récupère la hauteur de la page en pixels lors de la visualisation en JPG ou PNG. |
|
|  | [setHeight(int height)](#setHeight-int-) | Définit la hauteur de la page en pixels lors de la visualisation en JPG ou PNG. |
|
|  | [getLines()](#getLines--) | Récupère les lignes contenues dans la page lors de la visualisation en JPG ou PNG avec extraction de texte activée. |
|
|  | [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Définit les lignes contenues dans la page lors de la visualisation en JPG ou PNG avec extraction de texte activée. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Récupère le nom de la feuille de calcul ou de la page.


**Returns:**
java.lang.String - le nom de la feuille de calcul ou de la page.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Définit le nom de la feuille de calcul ou de la page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nom | java.lang.String | le nom à définir pour la feuille de calcul ou la page. |
|

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Récupère le numéro de page.


**Returns:**
int - le numéro de page.

### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Définit le numéro de page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | nombre | int | le numéro de page à définir. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Récupère l'indicateur de visibilité de la page.


**Returns:**
boolean - l'indicateur de visibilité de la page.

### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Définit l'indicateur de visibilité de la page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | visible | boolean | true si la page est visible, false sinon. |
|

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Récupère la largeur de la page en pixels lors de la visualisation en JPG ou PNG.


**Returns:**
int - la largeur de la page.

### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Définit la largeur de la page en pixels lors de la visualisation en JPG ou PNG.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | width | int | la largeur à définir pour la page. |
|

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Récupère la hauteur de la page en pixels lors de la visualisation en JPG ou PNG.


**Returns:**
int - la hauteur de la page.

### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Définit la hauteur de la page en pixels lors de la visualisation en JPG ou PNG.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | hauteur | int | la hauteur à définir pour la page. |
|

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Récupère les lignes contenues dans la page lors de la visualisation en JPG ou PNG avec extraction de texte activée.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - les lignes contenues dans la page.

### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Définit les lignes contenues dans la page lors de la visualisation en JPG ou PNG avec extraction de texte activée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | lignes | java.util.List<com.groupdocs.viewer.results.Line> | la liste des lignes à définir pour la page. |
|

