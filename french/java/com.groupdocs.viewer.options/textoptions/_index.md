---
title: "TextOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Options de division des fichiers texte en pages."
type: docs
weight: 32
url: /fr/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Options de division des fichiers texte en pages.


La classe TextOptions fournit des options pour diviser les fichiers texte en pages dans le composant GroupDocs.Viewer.
Elle vous permet de contrôler la façon dont les fichiers texte sont divisés en pages individuelles à des fins de rendu et de visualisation.


Exemple d'utilisation :

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | Initialise une nouvelle instance de |
TextOptions
classe.
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Obtient le nombre maximal de caractères par ligne sur une page. |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Définit le nombre maximal de caractères par ligne sur une page. |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Obtient le nombre maximal de lignes par page. |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Définit le nombre maximal de lignes par page. |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Initialise une nouvelle instance de
TextOptions
classe.
Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Obtient le nombre maximal de caractères par ligne sur une page.


***Note:** The default value is 85.*
La valeur par défaut est 85. Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - le nombre maximal de caractères par ligne sur une page.

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Définit le nombre maximal de caractères par ligne sur une page.


***Note:** The default value is 85.*
La valeur par défaut est 85. Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxCharsPerRow | int | Le nombre maximal de caractères par ligne sur une page. |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Obtient le nombre maximal de lignes par page.


***Note:** The default value is 55.*
La valeur par défaut est 55. Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - le nombre maximal de lignes.

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Définit le nombre maximal de lignes par page.


***Note:** The default value is 55.*
La valeur par défaut est 55. Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxRowsPerPage | int | Le nombre maximal de lignes. |
|

