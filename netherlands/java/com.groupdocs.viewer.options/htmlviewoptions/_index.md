---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties voor het renderen van documenten naar HTML-indeling."
type: docs
weight: 16
url: /nl/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Biedt opties voor het renderen van documenten naar HTML-indeling.


De HtmlViewOptions-klasse omvat extra instellingen en parameters
die kan worden gebruikt om de weergave van documenten naar HTML-indeling te regelen in de GroupDocs.Viewer-component.


Voor details, zie het [topic](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) en de onderliggende items.


Voorbeeldgebruik:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | Bepaalt of responsieve weergave is ingeschakeld. |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Stelt in of responsieve weergave is ingeschakeld. |
|
|  | [isMinify()](#isMinify--) | Controleert of HTML-inhoud en HTML-resources minificatie is ingeschakeld. |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | Stelt in of HTML-inhoud en HTML-resources minificatie is ingeschakeld. |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | Stelt het mogelijk om een heel document naar één HTML-bestand te renderen. |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Stelt het mogelijk om een heel document naar één HTML-bestand te renderen. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Geeft de maximale breedte van een uitvoerafbeelding in pixels terug. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Stelt de maximale breedte van een uitvoerafbeelding in in pixels. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Haalt de maximale hoogte van een uitvoerafbeelding in pixels op. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Stelt de maximale hoogte van een uitvoerafbeelding in in pixels. |
|
|  | [getImageWidth()](#getImageWidth--) | Haalt de breedte van de uitvoerafbeelding in pixels op. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Stelt de breedte van de uitvoerafbeelding in pixels in. |
|
|  | [getImageHeight()](#getImageHeight--) | Haalt de hoogte van de uitvoerafbeelding in pixels op bij het converteren van een enkele afbeelding naar HTML. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Stelt de hoogte van de uitvoerafbeelding in pixels in bij het converteren van een enkele afbeelding naar HTML. |
|
|  | [isForPrinting()](#isForPrinting--) | Controleert of de uitvoer-HTML geoptimaliseerd moet worden voor afdrukken. |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | Stelt in of de uitvoer-HTML geoptimaliseerd moet worden voor afdrukken. |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | Bepaalt of lettertypen uit het HTML-document moeten worden uitgesloten. |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Stelt in of lettertypen uit het HTML-document moeten worden uitgesloten. |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | Haalt de lijst met lettertype-namen op die uit het HTML-document moeten worden uitgesloten. |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Stelt de lijst met lettertype-namen in die uit het HTML-document moeten worden uitgesloten. |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | Staat toe om de JavaScript-broncode uit de koppelingen in resulterende HTML-documenten te verwijderen bij het renderen van invoerdocumenten die de scripts bevatten. |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Stelt toestemming in om de JavaScript-broncode uit de koppelingen in resulterende HTML-documenten te verwijderen bij het renderen van invoerdocumenten die de scripts bevatten. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Haalt de callback op die wordt gebruikt om de voortgang van het opslaan van een Words- of e-maildocument te schatten. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Stelt de callback in die wordt gebruikt om de voortgang van het opslaan van een Words- of e-maildocument te schatten. |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse voor het renderen naar HTML met ingesloten bronnen.
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse voor het renderen naar HTML met ingesloten bronnen.
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse voor het renderen naar HTML met ingesloten bronnen.
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse.
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse.
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse voor het renderen naar HTML met externe bronnen.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse voor het renderen naar HTML met externe bronnen.
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse voor het renderen naar HTML met externe bronnen.
|
|  | [forExternalResources()](#forExternalResources--) | Initialiseert een nieuw exemplaar van |
HtmlViewOptions
klasse.
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Initialiseert een nieuw exemplaar van de |
HtmlViewOptions
klasse.
|
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Bepaalt of responsieve weergave is ingeschakeld.
Responsieve webpagina's worden goed weergegeven op apparaten met verschillende schermformaten.


Responsief ontwerp heeft als doel webpagina's goed te laten weergeven op verschillende apparaten. Om met een responsieve lay-out te renderen, stel deze eigenschap in op true.
Voor codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Returns:**
boolean -  true  als responsief renderen is ingeschakeld,  false  anders.

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Stelt in of responsieve weergave is ingeschakeld.
Responsieve webpagina's worden goed weergegeven op apparaten met verschillende schermformaten.


Responsief ontwerp heeft als doel webpagina's goed te laten weergeven op verschillende apparaten. Om met een responsieve lay-out te renderen, stel deze eigenschap in op true.
Voor codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om responsief renderen in te schakelen,  false  om het uit te schakelen. |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Controleert of HTML-inhoud en HTML-resources minificatie is ingeschakeld.


Compressie van de uitvoerinhoud (HTML, CSS en SVG) is een van de manieren om het HTML-bestand te optimaliseren. Stel hiervoor deze eigenschap in op true.
Voor codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Returns:**
boolean -  true  als minimalisatie is ingeschakeld,  false  anders.

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Stelt in of HTML-inhoud en HTML-resources minificatie is ingeschakeld.


Compressie van de uitvoerinhoud (HTML, CSS en SVG) is een van de manieren om het HTML-bestand te optimaliseren. Stel hiervoor deze eigenschap in op true.
Voor codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om minimalisatie in te schakelen,  false  om uit te schakelen. |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Stelt het mogelijk om een heel document naar één HTML-bestand te renderen.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Stelt het mogelijk om een heel document naar één HTML-bestand te renderen.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Geeft de maximale breedte van een uitvoerafbeelding in pixels terug.
***Note:** This value is used when converting a single image to HTML.
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - de maximale breedte van een uitvoerafbeelding.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Stelt de maximale breedte van een uitvoerafbeelding in in pixels.
***Note:** This value is used when converting a single image to HTML.
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageMaxWidth | int | De maximale breedte van een uitvoerafbeelding. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Haalt de maximale hoogte van een uitvoerafbeelding in pixels op.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - de maximale hoogte van een uitvoerafbeelding.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Stelt de maximale hoogte van een uitvoerafbeelding in in pixels.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageMaxHeight | int | De maximale hoogte van een uitvoerafbeelding. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Haalt de breedte van de uitvoerafbeelding in pixels op.


***Note:** This value is applicable only when converting a single image to HTML.*
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - de breedte van de uitvoerafbeelding.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Stelt de breedte van de uitvoerafbeelding in pixels in.


***Note:** This value is applicable only when converting a single image to HTML.*
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageWidth | int | De breedte van de uitvoerafbeelding. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Haalt de hoogte van de uitvoerafbeelding in pixels op bij het converteren van een enkele afbeelding naar HTML.


Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - de hoogte van de uitvoerafbeelding in pixels.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Stelt de hoogte van de uitvoerafbeelding in pixels in bij het converteren van een enkele afbeelding naar HTML.


Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageHeight | int | De hoogte van de uitvoerafbeelding in pixels. |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Controleert of de uitvoer-HTML geoptimaliseerd moet worden voor afdrukken.


Schakel deze optie in om de uitvoer‑HTML‑pagina's te converteren naar het vector‑SVG‑formaat.
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Returns:**
boolean -  true  als de uitvoer‑HTML geoptimaliseerd moet worden voor afdrukken,  false  anders.

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Stelt in of de uitvoer-HTML geoptimaliseerd moet worden voor afdrukken.


Schakel deze optie in om de uitvoer‑HTML‑pagina's te converteren naar het vector‑SVG‑formaat.
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om de uitvoer‑HTML te optimaliseren voor afdrukken,  false  anders. |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Bepaalt of lettertypen uit het HTML-document moeten worden uitgesloten.


Standaard embedde GroupDocs.Viewer de lettertypen die in het document worden gebruikt in HTML. Om dit te voorkomen, stel deze eigenschap in op true.
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
boolean -  true  als lettertypen moeten worden uitgesloten,  false  anders.

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Stelt in of lettertypen uit het HTML-document moeten worden uitgesloten.


Standaard embedde GroupDocs.Viewer de lettertypen die in het document worden gebruikt in HTML. Om dit te voorkomen, stel deze eigenschap in op true.
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om lettertypen uit te sluiten,  false  anders. |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Haalt de lijst met lettertype-namen op die uit het HTML-document moeten worden uitgesloten.


Deze optie wordt alleen ondersteund voor presentaties.
Het opnemen van lettertypen in het HTML‑document verbetert de stabiliteit van de uitvoerweergave, maar vergroot de grootte van het renderresultaat.
Gebruik deze optie om een compromis te vinden tussen stabiliteit en uitvoergrootte.
Neem lettertypenamen op die populair zijn en op de meeste systemen geïnstalleerd.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) optie is uitgeschakeld.*
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
java.util.List<java.lang.String> - de lijst met lettertypenamen die uit het HTML‑document moeten worden uitgesloten.

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Stelt de lijst met lettertype-namen in die uit het HTML-document moeten worden uitgesloten.


Deze optie wordt alleen ondersteund voor presentaties.
Het opnemen van lettertypen in het HTML‑document verbetert de stabiliteit van de uitvoerweergave, maar vergroot de grootte van het renderresultaat.
Gebruik deze optie om een compromis te vinden tussen stabiliteit en uitvoergrootte.
Neem lettertypenamen op die populair zijn en op de meeste systemen geïnstalleerd.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) optie is uitgeschakeld.*
Voor details en codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.List<java.lang.String> | De lijst met lettertypenamen die uit het HTML‑document moeten worden uitgesloten. |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Staat toe om de JavaScript-broncode uit de koppelingen in resulterende HTML-documenten te verwijderen bij het renderen van invoerdocumenten die scripts bevatten. Standaard is ingeschakeld (true).


Voor details over het verwijderen van JavaScript, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Stelt de toestemming in om de JavaScript-broncode uit de koppelingen in resulterende HTML-documenten te verwijderen bij het renderen van invoerdocumenten die scripts bevatten. Standaard is ingeschakeld (true).


Voor details over het verwijderen van JavaScript, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Haalt de callback op die wordt gebruikt om de voortgang van het opslaan van een Words- of e-maildocument te schatten.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - de callback die wordt gebruikt om de voortgang van het opslaan van het document te schatten.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Stelt de callback in die wordt gebruikt om de voortgang van het opslaan van een Words- of e-maildocument te schatten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | De callback die wordt gebruikt om de voortgang van het opslaan van het document te schatten. |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse voor het renderen naar HTML met ingesloten bronnen.


***Note:** The method takes a 
CreatePageStream
parameter, die een methode is die wordt gebruikt om een stream te instantieren voor het schrijven van uitvoerpagina-gegevens.*
Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | De methode die een stream instantieert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse voor het renderen naar HTML met ingesloten bronnen.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | De methode die een stream instantieert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | De methode die de stream vrijgeeft die is gemaakt door de methode die is toegewezen aan de  createPageStream  parameter. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse voor het renderen naar HTML met ingesloten bronnen.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoerpagina-stream. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Het bestandspadformaat, bijv. 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Het bestandspadformaat, bijv. 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse voor het renderen naar HTML met externe bronnen.


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | De methode die de stream instantieert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | De methode die de  createPageStream  methode vrijgeeft. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | De methode die de URL voor de HTML-resource maakt. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse voor het renderen naar HTML met externe bronnen.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | De methode die de stream instantieert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | De methode die de stream instantieert die wordt gebruikt om uitvoer-HTML-resource-gegevens te schrijven. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | De methode die de URL voor de HTML-resource maakt. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | De methode die de  createPageStream  methode vrijgeeft. |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | De methode die de stream vrijgeeft die is gemaakt door de  createResourceStream  methode. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse voor het renderen naar HTML met externe bronnen.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | De fabriek die methoden implementeert voor het maken en vrijgeven van de uitvoerpagina-stream. |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | De fabriek die methoden implementeert voor het maken van resource-URL's en het instantieren/vrijgeven van de uitvoer-HTML-resource-stream. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Initialiseert een nieuw exemplaar van
HtmlViewOptions
klasse.


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

De uitvoerbestanden worden geplaatst in de huidige werkmap van de applicatie. Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Initialiseert een nieuw exemplaar van de
HtmlViewOptions
klasse.


Voor het codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Het bestandspadformaat, bijv. 'page_{0}.html'. |
|
|  | resourceFilePathFormat | java.lang.String | Het resource-bestandspadformaat, bijv. 'page_{0}/resource_{1}'. |
|
|  | resourceUrlFormat | java.lang.String | Het resource-URL-formaat, bijv. 'page_{0}/resource_{1}'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
