---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties die worden gebruikt om informatie over de weergave op te halen."
type: docs
weight: 34
url: /nl/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Biedt opties die worden gebruikt om informatie over de weergave op te halen.

De ViewInfoOptions-klasse omvat extra instellingen en parameters die kunnen worden gebruikt om informatie over een weergave op te halen in de GroupDocs.Viewer-component.

Voorbeeldgebruik:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isExtractText()](#isExtractText--) | Geeft aan of teksteextractie is ingeschakeld. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | Stelt de vlag in die aangeeft of teksteextractie is ingeschakeld. |
| [getMaxWidth()](#getMaxWidth--) | Retourneert de maximale breedte van de uitvoerafbeelding voor weergave naar PNG/JPG. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Stelt de maximale breedte van een uitvoerafbeelding in (in pixels, alleen voor weergave naar PNG/JPG). |
| [getMaxHeight()](#getMaxHeight--) | Retourneert de maximale hoogte van de uitvoerafbeelding voor weergave naar PNG/JPG. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Stelt de maximale hoogte van een uitvoerafbeelding in (in pixels, alleen voor weergave naar PNG/JPG). |
| [getWidth()](#getWidth--) | De breedte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG). |
| [setWidth(int width)](#setWidth-int-) | De breedte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG). |
| [getHeight()](#getHeight--) | De hoogte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG). |
| [setHeight(int height)](#setHeight-int-) | De hoogte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG). |
| [forHtmlView()](#forHtmlView--) | Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar HTML. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar HTML. |
| [forJpgView()](#forJpgView--) | Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar JPG. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar JPG. |
| [forPngView()](#forPngView--) | Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar PNG. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar PNG. |
| [forPdfView()](#forPdfView--) | Initialiseert een nieuw exemplaar van de ViewInfoOptions class om informatie over de weergave op te halen bij het renderen naar PDF. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Initialiseert een nieuw exemplaar van de ViewInfoOptions class op basis van het [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) object. |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Initialiseert een nieuw exemplaar van de ViewInfoOptions class op basis van het [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) object. |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Initialiseert een nieuw exemplaar van de ViewInfoOptions class op basis van het [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) object. |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Initialiseert een nieuw exemplaar van de [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class op basis van een PdfViewOptions-object. |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Geeft aan of teksteextractie is ingeschakeld.

Gebruik deze eigenschap om de tekst in een brondocument en de coördinaten ervan op te halen. Vervolgens kunt u deze gegevens gebruiken om selecteerbare tekst over de afbeelding toe te voegen of om een tekstzoekopdracht te implementeren bij afbeeldingsgebaseerde weergave. Zie voor een codevoorbeeld de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
boolean - Waar als tekstextractie is ingeschakeld, onwaar anders.
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Stelt de vlag in die aangeeft of teksteextractie is ingeschakeld.

Gebruik deze eigenschap om de tekst in een brondocument en de coördinaten ervan op te halen. Vervolgens kunt u deze gegevens gebruiken om selecteerbare tekst over de afbeelding toe te voegen of om een tekstzoekopdracht te implementeren bij afbeeldingsgebaseerde weergave. Zie voor een codevoorbeeld de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extractText | boolean | Waar om tekstextractie in te schakelen, onwaar om uit te schakelen. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Retourneert de maximale breedte van de uitvoerafbeelding voor weergave naar PNG/JPG.

Gebruik deze eigenschap om de maximale breedte van de uitvoerafbeelding in te stellen (in pixels). Zie voor het code‑voorbeeld de [documentation][]. Als u de  eigenschap instelt, wordt deze eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - de maximale breedte van de uitvoerafbeelding.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Stelt de maximale breedte van een uitvoerafbeelding in (in pixels, alleen voor weergave naar PNG/JPG).

Gebruik deze eigenschap om de maximale breedte van de uitvoerafbeelding in te stellen (in pixels). Zie voor het code‑voorbeeld de [documentation][]. Als u de  eigenschap instelt, wordt deze eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxWidth | int | De maximale breedte van de uitvoerafbeelding. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Retourneert de maximale hoogte van de uitvoerafbeelding voor weergave naar PNG/JPG.

Gebruik deze eigenschap om de maximale hoogte van de uitvoerafbeelding in te stellen (in pixels). Zie voor het code‑voorbeeld de [documentation][]. Als u de  eigenschap instelt, wordt deze eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - de maximale hoogte van de uitvoerafbeelding.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Stelt de maximale hoogte van een uitvoerafbeelding in (in pixels, alleen voor weergave naar PNG/JPG).

Gebruik deze eigenschap om de maximale hoogte van de uitvoerafbeelding in te stellen (in pixels). Zie voor het code‑voorbeeld de [documentation][]. Als u de  eigenschap instelt, wordt deze eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxHeight | int | De maximale hoogte van de uitvoerafbeelding. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


De breedte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG).

Gebruik deze eigenschap om de breedte van de uitvoerafbeelding in te stellen (in pixels). Zie voor het code‑voorbeeld de [documentation][]. Als u deze eigenschap instelt, wordt de  eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - de breedte van de afbeelding.
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


De breedte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG).

Gebruik deze eigenschap om de breedte van de uitvoerafbeelding in te stellen (in pixels). Zie voor het code‑voorbeeld de [documentation][]. Als u deze eigenschap instelt, wordt de  eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | De breedte van de afbeelding. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


De hoogte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG).

Gebruik deze eigenschap om de hoogte van de uitvoerafbeelding in te stellen (in pixels). Zie voor het code‑voorbeeld de [documentation][]. Als u deze eigenschap instelt, wordt de  eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - de hoogte van de afbeelding.
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


De hoogte van de uitvoerafbeelding (in pixels, alleen voor weergave naar PNG/JPG).

Gebruik deze eigenschap om de hoogte van de uitvoerafbeelding in te stellen (in pixels). Zie voor het code‑voorbeeld de [documentation][]. Als u deze eigenschap instelt, wordt de  eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| height | int | De hoogte van de afbeelding. |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar HTML.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar HTML.

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderSinglePage | boolean | Schakelt in dat HTML-inhoud op één pagina wordt gerenderd. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar JPG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar JPG.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extractText | boolean | Schakelt tekstextractie in. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar PNG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Initialiseert een nieuw exemplaar van de  ViewInfoOptions  klasse om informatie over de weergave op te halen bij weergave naar PNG.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extractText | boolean | Schakelt tekstextractie in. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Initialiseert een nieuw exemplaar van de ViewInfoOptions class om informatie over de weergave op te halen bij het renderen naar PDF.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Initialiseert een nieuw exemplaar van de ViewInfoOptions class op basis van het [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | De HTML-weergaveopties. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Initialiseert een nieuw exemplaar van de ViewInfoOptions class op basis van het [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | De PNG-weergaveopties. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Initialiseert een nieuw exemplaar van de ViewInfoOptions class op basis van het [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | De JPG-weergaveopties. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Initialiseert een nieuw exemplaar van de [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class op basis van een PdfViewOptions-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | De PDF-weergaveopties. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
