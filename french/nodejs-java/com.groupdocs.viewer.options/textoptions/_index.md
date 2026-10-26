---
title: "TextOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Options de division des fichiers texte en pages."
type: docs
weight: 32
url: /fr/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Options de division des fichiers texte en pages.

La classe TextOptions fournit des options pour diviser les fichiers texte en pages dans le composant GroupDocs.Viewer. Elle vous permet de contrôler la façon dont les fichiers texte sont découpés en pages individuelles pour le rendu et la visualisation.

Exemple d'utilisation :

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextOptions()](#TextOptions--) | Initialise une nouvelle instance de la classe  TextOptions  . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Obtient le nombre maximal de caractères par ligne sur une page. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Définit le nombre maximal de caractères par ligne sur une page. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Obtient le nombre maximal de lignes par page. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Définit le nombre maximal de lignes par page. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Initialise une nouvelle instance de la classe  TextOptions  .

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Obtient le nombre maximal de caractères par ligne sur une page.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - le nombre maximal de caractères par ligne sur une page.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Définit le nombre maximal de caractères par ligne sur une page.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxCharsPerRow | int | Le nombre maximal de caractères par ligne sur une page. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Obtient le nombre maximal de lignes par page.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - le nombre maximal de lignes.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Définit le nombre maximal de lignes par page.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxRowsPerPage | int | Le nombre maximal de lignes. |

