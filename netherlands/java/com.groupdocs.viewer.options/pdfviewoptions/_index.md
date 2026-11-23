---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties voor het renderen van documenten naar PDF‑formaat."
type: docs
weight: 23
url: /nl/java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Biedt opties voor het renderen van documenten naar PDF‑formaat.


De PdfViewOptions-klasse omvat extra instellingen en parameters
die kan worden gebruikt om de rendering van documenten naar PDF-formaat te regelen in de GroupDocs.Viewer-component.
Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


Voorbeeldgebruik:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Initialiseert een nieuw exemplaar van de |
PdfViewOptions
klasse.
|
|  | [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Initialiseert een nieuw exemplaar van de |
PdfViewOptions
klasse.
|
|  | [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Initialiseert een nieuw exemplaar van de  PdfViewOptions  klasse. |
|
|  | [PdfViewOptions()](#PdfViewOptions--) | Initialiseert een nieuw exemplaar van de  PdfViewOptions  klasse met standaardinstellingen. |
|
|  | [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de |
PdfViewOptions
klasse.
|
|  | [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Initialiseert een nieuw exemplaar van de |
PdfViewOptions
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Verminder de grootte van het uitvoer-PDF-bestand door optimalisatietechnieken toe te passen met verschillende opties. |
|
|  | [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Verminder de grootte van het uitvoer-PDF-bestand door optimalisatietechnieken toe te passen met verschillende opties. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Haalt de maximale breedte van een uitvoerafbeelding op in pixels. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Stelt de maximale breedte van een uitvoerafbeelding in in pixels. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Haalt de maximale hoogte van een uitvoerafbeelding op in pixels. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Stelt de maximale hoogte van een uitvoerafbeelding in in pixels. |
|
|  | [getImageWidth()](#getImageWidth--) | Haalt de breedte van de uitvoerafbeelding op in pixels. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Stelt de breedte van de uitvoerafbeelding in pixels in. |
|
|  | [getImageHeight()](#getImageHeight--) | Haalt de hoogte van de uitvoerafbeelding in pixels op. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Stelt de hoogte van de uitvoerafbeelding in pixels in. |
|
|  | [getSecurity()](#getSecurity--) | Haalt de beveiligingsopties op voor het uitvoer‑PDF‑document. |
|
|  | [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Stelt de beveiligingsopties in voor het uitvoer‑PDF‑document. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Haalt de callback op die wordt gebruikt om de voortgang van het opslaan van een Words‑ of e‑mail‑document te schatten. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Stelt de callback in die wordt gebruikt om de voortgang van het opslaan van een Words‑ of e‑mail‑document te schatten. |
|
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Initialiseert een nieuw exemplaar van de
PdfViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Initialiseert een nieuw exemplaar van de
PdfViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | De methode die wordt gebruikt om de stream te instantieren voor het schrijven van de uitvoerbestandsgegevens. |
|
|  | releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | De methode die wordt gebruikt om de stream vrij te geven die is aangemaakt door de  createFileStream  methode. |
|

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Initialiseert een nieuw exemplaar van de  PdfViewOptions  klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoer‑bestandsstream. |
|

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Initialiseert een nieuw exemplaar van de  PdfViewOptions  klasse met standaardinstellingen.


Deze constructor maakt een nieuwe
PdfViewOptions
object met "output.pdf" als het bestandspadformaat voor het uitvoerbestand.
Het uitvoerbestand wordt geplaatst in de huidige werkmap van de applicatie.
Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Initialiseert een nieuw exemplaar van de
PdfViewOptions
klasse.


Deze constructor maakt een nieuwe
PdfViewOptions
object met de opgegeven
outputFilePath
parameter
dat het pad voor het uitvoer‑PDF‑bestand vertegenwoordigt.
Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputFilePath | java.lang.String | Het pad voor het uitvoer‑PDF‑bestand. |
|

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Initialiseert een nieuw exemplaar van de
PdfViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputFilePath | java.nio.file.Path | Het pad voor het uitvoer‑PDF‑bestand. |
|

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Verminder de grootte van het uitvoer-PDF-bestand door optimalisatietechnieken toe te passen met verschillende opties.


Deze optie wordt ondersteund voor alle invoerbestandsformaten die worden ondersteund voor conversie naar PDF: [Ondersteunde documentformaten](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Voor details en codevoorbeelden, zie deze [pagina](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) en de onderliggende pagina's.


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.

### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Verminder de grootte van het uitvoer-PDF-bestand door optimalisatietechnieken toe te passen met verschillende opties.


Deze optie wordt ondersteund voor alle invoerbestandsformaten die worden ondersteund voor conversie naar PDF: [Ondersteunde documentformaten](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Voor details en codevoorbeelden, zie deze [pagina](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) en de onderliggende pagina's.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions‑object of null. |
|

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Haalt de maximale breedte van een uitvoerafbeelding in pixels op. Deze parameter is alleen van toepassing bij het converteren van één afbeelding naar HTML.


Gebruik deze eigenschap om de maximale breedte van de uitvoerafbeelding (in pixels) in te stellen. GroupDocs.Viewer past deze eigenschap toe bij het renderen van één afbeelding naar PDF. Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Als je de eigenschap instelt, wordt deze eigenschap genegeerd.


**Returns:**
int - de maximale breedte van de uitvoerafbeelding in pixels.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Stelt de maximale breedte van een uitvoerafbeelding in pixels in. Deze parameter is alleen van toepassing bij het converteren van één afbeelding naar HTML.


Gebruik deze eigenschap om de maximale breedte van de uitvoerafbeelding (in pixels) in te stellen. GroupDocs.Viewer past deze eigenschap toe bij het renderen van één afbeelding naar PDF. Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Als je de eigenschap instelt, wordt deze eigenschap genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageMaxWidth | int | De maximale breedte van de uitvoerafbeelding in pixels. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Haalt de maximale hoogte van een uitvoerafbeelding in pixels op. Deze parameter is alleen van toepassing bij het converteren van één afbeelding naar HTML.


Gebruik deze eigenschap om de maximale hoogte van de uitvoerafbeelding (in pixels) in te stellen. GroupDocs.Viewer past deze eigenschap toe bij het renderen van één afbeelding naar PDF. Zie voor details de [documentatie](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Als je de eigenschap instelt, wordt deze eigenschap genegeerd.


**Returns:**
int - de maximale hoogte van de uitvoerafbeelding in pixels.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Stelt de maximale hoogte van een uitvoerafbeelding in pixels in. Deze parameter is alleen van toepassing bij het converteren van één afbeelding naar HTML.


Gebruik deze eigenschap om de maximale hoogte van de uitvoerafbeelding (in pixels) in te stellen. GroupDocs.Viewer past deze eigenschap toe bij het renderen van één afbeelding naar HTML alleen. Zie voor details de [documentatie](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Als je de eigenschap instelt, wordt deze eigenschap genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageMaxHeight | int | De maximale hoogte van de uitvoerafbeelding in pixels. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Haalt de breedte van de uitvoerafbeelding in pixels op. Deze parameter is alleen van toepassing bij het converteren van één afbeelding naar HTML.


Gebruik deze eigenschap om de breedte van de uitvoerafbeelding (in pixels) in te stellen. GroupDocs.Viewer past deze eigenschap toe bij het renderen van één afbeelding naar PDF. Zie voor details de [documentatie](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Als u deze eigenschap instelt, wordt de eigenschap genegeerd.


**Returns:**
int - de breedte van de uitvoerafbeelding in pixels.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Stelt de breedte van de uitvoerafbeelding in pixels in. Deze parameter is alleen van toepassing bij het converteren van één afbeelding naar PDF.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageWidth | int | De breedte van de uitvoerafbeelding in pixels. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Haalt de hoogte van de uitvoerafbeelding in pixels op. Deze parameter is alleen van toepassing bij het converteren van één afbeelding naar HTML.


Gebruik deze eigenschap om de hoogte van de uitvoerafbeelding (in pixels) in te stellen. GroupDocs.Viewer past deze eigenschap toe bij het renderen van één afbeelding naar HTML alleen. Zie voor details de [documentatie](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Als u deze eigenschap instelt, wordt de eigenschap genegeerd.


**Returns:**
int - de hoogte van de uitvoerafbeelding in pixels.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Stelt de hoogte van de uitvoerafbeelding in pixels in. Deze parameter is alleen van toepassing bij het converteren van één afbeelding naar HTML.


Gebruik deze eigenschap om de hoogte van de uitvoerafbeelding (in pixels) in te stellen. GroupDocs.Viewer past deze eigenschap toe bij het renderen van één afbeelding naar HTML alleen. Zie voor details de [documentatie](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
Als u deze eigenschap instelt, wordt de eigenschap genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageHeight | int | De hoogte van de uitvoerafbeelding in pixels. |
|

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Haalt de beveiligingsopties op voor het uitvoer‑PDF‑document.


Zie voor details de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.

### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Stelt de beveiligingsopties in voor het uitvoer‑PDF‑document.


Zie voor details de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Security](../../com.groupdocs.viewer.options/security) | De beveiligingsopties voor het uitvoer‑PDF‑document. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Haalt de callback op die wordt gebruikt om de voortgang van het opslaan van een Words‑ of e‑mail‑document te schatten.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - de callback om de voortgang van het opslaan van het document te schatten.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Stelt de callback in die wordt gebruikt om de voortgang van het opslaan van een Words‑ of e‑mail‑document te schatten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | De callback om de voortgang van het opslaan van het document te schatten. |
|

