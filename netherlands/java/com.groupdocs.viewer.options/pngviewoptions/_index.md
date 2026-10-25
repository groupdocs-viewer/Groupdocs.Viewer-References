---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties voor het renderen van documenten naar PNG‑formaat."
type: docs
weight: 25
url: /nl/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Biedt opties voor het renderen van documenten naar PNG‑formaat.


De PngViewOptions-klasse omvat extra instellingen en parameters die kunnen worden gebruikt
om de weergave van documenten in PNG-formaat te regelen in de GroupDocs.Viewer-component.


Voorbeeldgebruik:

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
Voor details, zie deze [pagina](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) en de onderliggende pagina's.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialiseert een nieuw exemplaar van de |
PngViewOptions
klasse.
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialiseert een nieuw exemplaar van de |
PngViewOptions
klasse.
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialiseert een nieuw exemplaar van de |
PngViewOptions
klasse.
|
|  | [PngViewOptions()](#PngViewOptions--) | Initialiseert een nieuw exemplaar van |
PngViewOptions
klasse.
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de |
PngViewOptions
klasse.
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Initialiseert een nieuw exemplaar van de |
PngViewOptions
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Geeft de maximale breedte van een uitvoerafbeelding in pixels terug. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Stelt de maximale breedte van een uitvoerafbeelding in in pixels. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Retourneert de maximale hoogte van een uitvoerafbeelding in pixels. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Stelt de maximale hoogte van een uitvoerafbeelding in in pixels. |
|
|  | [isExtractText()](#isExtractText--) | Bepaalt of tekstextractie is ingeschakeld. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Schakelt tekstextractie in of uit. |
|
|  | [getWidth()](#getWidth--) | Retourneert de breedte van de uitvoerafbeelding in pixels. |
|
|  | [setWidth(int value)](#setWidth-int-) | Stelt de breedte van de uitvoerafbeelding in pixels in. |
|
|  | [getHeight()](#getHeight--) | Retourneert de hoogte van de uitvoerafbeelding in pixels. |
|
|  | [setHeight(int value)](#setHeight-int-) | Stelt de hoogte van de uitvoerafbeelding in pixels in. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Haalt de callback op voor het schatten van de opslaanvoortgang van een document. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Stelt de callback in voor het schatten van de opslaanvoortgang van een document. |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de
PngViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | De methode die de stream instantieert die wordt gebruikt om de uitvoerpagina-gegevens te schrijven. |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van de
PngViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | De methode die de stream instantieert die wordt gebruikt om de uitvoerpagina-gegevens te schrijven. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | De methode die de stream vrijgeeft die is aangemaakt door de methode die is toegewezen aan de createPageStream-parameter. |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Initialiseert een nieuw exemplaar van de
PngViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoerpagina-stream. |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Initialiseert een nieuw exemplaar van
PngViewOptions
klasse.


Deze constructor initialiseert een nieuw exemplaar van
PngViewOptions

met "p_{0}.png" als bestandsnaamformaat voor de uitvoerbestanden.
De uitvoerbestanden worden geplaatst in de huidige werkmap van de applicatie.
Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Initialiseert een nieuw exemplaar van de
PngViewOptions
klasse.


Bijvoorbeeld, als het bestandsnaamformaat 'page_{0}.png' is, zullen de uitvoerbestanden
genoemd worden als 'page_1.png', 'page_2.png', enzovoort, gebaseerd op het paginanummer.


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Het bestandsnaamformaat, bijv., 'page_{0}.png'. |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Initialiseert een nieuw exemplaar van de
PngViewOptions
klasse.


Bijvoorbeeld, als het bestandsnaamformaat 'page_{0}.png' is, zullen de uitvoerbestanden
genoemd worden als 'page_1.png', 'page_2.png', enzovoort, gebaseerd op het paginanummer.
Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Het bestandsnaamformaat, bijv., 'page_{0}.png'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Geeft de maximale breedte van een uitvoerafbeelding in pixels terug.


Gebruik deze eigenschap om de maximale breedte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Als je de eigenschap instelt, wordt deze eigenschap genegeerd.


**Returns:**
int - de maximale breedte van de uitvoerafbeelding.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Stelt de maximale breedte van een uitvoerafbeelding in in pixels.


Gebruik deze eigenschap om de maximale breedte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Als je de eigenschap instelt, wordt deze eigenschap genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | maxWidth | int | De maximale breedte van de uitvoerafbeelding. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Retourneert de maximale hoogte van een uitvoerafbeelding in pixels.


Gebruik deze eigenschap om de maximale hoogte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Als je de eigenschap instelt, wordt deze eigenschap genegeerd.


**Returns:**
int - de maximale hoogte van de uitvoerafbeelding.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Stelt de maximale hoogte van een uitvoerafbeelding in in pixels.


Gebruik deze eigenschap om de maximale hoogte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Als je de eigenschap instelt, wordt deze eigenschap genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | maxHeight | int | De maximale hoogte van de uitvoerafbeelding. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Bepaalt of tekstextractie is ingeschakeld.


Deze optie kan nuttig zijn wanneer u een selecteerbare tekstlaag over de afbeelding wilt toevoegen.
Gebruik deze eigenschap om de tekst in een brondocument en de coördinaten ervan op te halen. Vervolgens kunt u deze gegevens gebruiken om een selecteerbare tekst over de afbeelding toe te voegen of om een tekstzoekopdracht te implementeren bij afbeeldingsgebaseerde weergave.
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  als teksteXtractie is ingeschakeld,  false  anders.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Schakelt tekstextractie in of uit.


Deze optie kan nuttig zijn wanneer u een selecteerbare tekstlaag over de afbeelding wilt toevoegen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om teksteXtractie in te schakelen,  false  om het uit te schakelen. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Retourneert de breedte van de uitvoerafbeelding in pixels.


Gebruik deze eigenschap om de breedte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Als u deze eigenschap instelt, wordt de eigenschap genegeerd.


**Returns:**
int - de breedte van de uitvoerafbeelding.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de breedte van de uitvoerafbeelding in pixels in.


Gebruik deze eigenschap om de breedte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Als u deze eigenschap instelt, wordt de eigenschap genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De breedte van de uitvoerafbeelding. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Retourneert de hoogte van de uitvoerafbeelding in pixels.


Gebruik deze eigenschap om de hoogte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Als u deze eigenschap instelt, wordt de eigenschap genegeerd.


**Returns:**
int - de hoogte van de uitvoerafbeelding.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de hoogte van de uitvoerafbeelding in pixels in.


Gebruik deze eigenschap om de hoogte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Als u deze eigenschap instelt, wordt de eigenschap genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De hoogte van de uitvoerafbeelding. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Haalt de callback op voor het schatten van de opslaanvoortgang van een document.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - de callback om de voortgang van het opslaan van het document te schatten.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Stelt de callback in voor het schatten van de opslaanvoortgang van een document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | De callback om de voortgang van het opslaan van het document te schatten. |
|

