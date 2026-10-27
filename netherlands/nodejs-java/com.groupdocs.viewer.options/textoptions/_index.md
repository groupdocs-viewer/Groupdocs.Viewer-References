---
title: "TextOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Opties voor het splitsen van tekstbestanden naar pagina's."
type: docs
weight: 32
url: /nl/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Opties voor het splitsen van tekstbestanden naar pagina's.

De TextOptions-klasse biedt opties voor het splitsen van tekstbestanden in pagina's in de GroupDocs.Viewer-component. Het stelt u in staat om te regelen hoe tekstbestanden worden verdeeld over afzonderlijke pagina's voor weergave- en weergavedoeleinden.

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextOptions()](#TextOptions--) | Initialiseert een nieuw exemplaar van de TextOptions-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Haalt het maximale aantal tekens per rij op een pagina op. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Stelt het maximale aantal tekens per rij op een pagina in. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Haalt het maximale aantal rijen per pagina op. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Stelt het maximale aantal rijen per pagina in. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Initialiseert een nieuw exemplaar van de TextOptions-klasse.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Haalt het maximale aantal tekens per rij op een pagina op.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - het maximale aantal tekens per rij op een pagina.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Stelt het maximale aantal tekens per rij op een pagina in.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxCharsPerRow | int | Het maximale aantal tekens per rij op een pagina. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Haalt het maximale aantal rijen per pagina op.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - het maximale aantal rijen.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Stelt het maximale aantal rijen per pagina in.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxRowsPerPage | int | Het maximale aantal rijen. |

