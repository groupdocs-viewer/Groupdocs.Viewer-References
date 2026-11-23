---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ som används för att hämta information om vyn."
type: docs
weight: 34
url: /sv/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Tillhandahåller alternativ som används för att hämta information om vyn.


Klassen ViewInfoOptions kapslar in ytterligare inställningar och parametrar som
kan användas för att hämta information om en vy i GroupDocs.Viewer-komponenten.


Exempel på användning:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | Indikerar om textutdragning är aktiverad. |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | Ställer in flaggan som indikerar om textutdragning är aktiverad. |
|
|  | [getMaxWidth()](#getMaxWidth--) | Returnerar den maximala bredden på utdata bilden för rendering till PNG/JPG. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Ställer in den maximala bredden på en utdata bild (i pixlar, endast för rendering till PNG/JPG). |
|
|  | [getMaxHeight()](#getMaxHeight--) | Returnerar den maximala höjden på utdata bilden för rendering till PNG/JPG. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Ställer in den maximala höjden på en utdata bild (i pixlar, endast för rendering till PNG/JPG). |
|
|  | [getWidth()](#getWidth--) | Bredden på utdata bilden (i pixlar, endast för rendering till PNG/JPG). |
|
|  | [setWidth(int width)](#setWidth-int-) | Bredden på utdata bilden (i pixlar, endast för rendering till PNG/JPG). |
|
|  | [getHeight()](#getHeight--) | Höjden på utdata bilden (i pixlar, endast för rendering till PNG/JPG). |
|
|  | [setHeight(int height)](#setHeight-int-) | Höjden på utdata bilden (i pixlar, endast för rendering till PNG/JPG). |
|
|  | [forHtmlView()](#forHtmlView--) | Initierar en ny instans av |
ViewInfoOptions
klass för att hämta information om vyn vid rendering till HTML.
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Initierar en ny instans av |
ViewInfoOptions
klass för att hämta information om vyn vid rendering till HTML.
|
|  | [forJpgView()](#forJpgView--) | Initierar en ny instans av |
ViewInfoOptions
klass för att hämta information om vyn vid rendering till JPG.
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | Initierar en ny instans av |
ViewInfoOptions
klass för att hämta information om vyn vid rendering till JPG.
|
|  | [forPngView()](#forPngView--) | Initierar en ny instans av |
ViewInfoOptions
klass för att hämta information om vyn vid rendering till PNG.
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | Initierar en ny instans av |
ViewInfoOptions
klass för att hämta information om vyn vid rendering till PNG.
|
|  | [forPdfView()](#forPdfView--) | Initierar en ny instans av klassen ViewInfoOptions för att hämta information om vyn vid rendering till PDF. |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Initierar en ny instans av |
ViewInfoOptions
klass baserad på objektet [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Initierar en ny instans av |
ViewInfoOptions
klass baserad på objektet [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Initierar en ny instans av |
ViewInfoOptions
klass baserad på objektet [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Initierar en ny instans av klassen [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) baserad på ett PdfViewOptions-objekt. |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Indikerar om textutdragning är aktiverad.
Använd den här egenskapen för att hämta texten som finns i ett källdokument och dess koordinater. Därefter kan du använda dessa data för att lägga till markerbar text över bilden eller för att implementera en textsökning i bildbaserad rendering. För kodexempel, se [dokumentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Returns:**
boolean - Sant om textutdragning är aktiverad, falskt annars.

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Ställer in flaggan som indikerar om textutdragning är aktiverad.
Använd den här egenskapen för att hämta texten som finns i ett källdokument och dess koordinater. Därefter kan du använda dessa data för att lägga till markerbar text över bilden eller för att implementera en textsökning i bildbaserad rendering. För kodexempel, se [dokumentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | extractText | boolean | Sant för att aktivera textutdragning, falskt för att inaktivera. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Returnerar den maximala bredden på utdata bilden för rendering till PNG/JPG.
Använd den här egenskapen för att ange den maximala bredden på utdata bilden (i pixlar). För kodexempel, se [dokumentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Om du anger egenskapen ignoreras denna egenskap.


**Returns:**
int - den maximala bredden på utdatabilden.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Ställer in den maximala bredden på en utdata bild (i pixlar, endast för rendering till PNG/JPG).
Använd den här egenskapen för att ange den maximala bredden på utdata bilden (i pixlar). För kodexempel, se [dokumentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Om du anger egenskapen ignoreras denna egenskap.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxWidth | int | Den maximala bredden på utdatabilden. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Returnerar den maximala höjden på utdata bilden för rendering till PNG/JPG.
Använd den här egenskapen för att ange den maximala höjden på utdata bilden (i pixlar). För kodexempel, se [dokumentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Om du anger egenskapen ignoreras denna egenskap.


**Returns:**
int - den maximala höjden på utdatabilden.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Ställer in den maximala höjden på en utdata bild (i pixlar, endast för rendering till PNG/JPG).
Använd den här egenskapen för att ange den maximala höjden på utdata bilden (i pixlar). För kodexempel, se [dokumentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Om du anger egenskapen ignoreras denna egenskap.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxHeight | int | Den maximala höjden på utdatabilden. |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


Bredden på utdata bilden (i pixlar, endast för rendering till PNG/JPG).
Använd den här egenskapen för att ange bredden på utdata bilden (i pixlar). För kodexempel, se [dokumentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Om du anger denna egenskap ignoreras egenskapen.


**Returns:**
int - bildens bredd.

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Bredden på utdata bilden (i pixlar, endast för rendering till PNG/JPG).
Använd den här egenskapen för att ange bredden på utdata bilden (i pixlar). För kodexempel, se [dokumentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Om du anger denna egenskap ignoreras egenskapen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | width | int | Bredden på bilden. |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


Höjden på utdata bilden (i pixlar, endast för rendering till PNG/JPG).
Använd den här egenskapen för att ange bildens utdatahöjd (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Om du anger den här egenskapen ignoreras egenskapen.


**Returns:**
int – bildens höjd.

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Höjden på utdata bilden (i pixlar, endast för rendering till PNG/JPG).
Använd den här egenskapen för att ange bildens utdatahöjd (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Om du anger den här egenskapen ignoreras egenskapen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | höjd | int | Bildens höjd. |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Initierar en ny instans av
ViewInfoOptions
klass för att hämta information om vyn vid rendering till HTML.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Initierar en ny instans av
ViewInfoOptions
klass för att hämta information om vyn vid rendering till HTML.


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | renderSinglePage | boolean | Gör det möjligt att rendera HTML‑innehåll på en enda sida. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Initierar en ny instans av
ViewInfoOptions
klass för att hämta information om vyn vid rendering till JPG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Initierar en ny instans av
ViewInfoOptions
klass för att hämta information om vyn vid rendering till JPG.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | extractText | boolean | Gör det möjligt att extrahera text. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Initierar en ny instans av
ViewInfoOptions
klass för att hämta information om vyn vid rendering till PNG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Initierar en ny instans av
ViewInfoOptions
klass för att hämta information om vyn vid rendering till PNG.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | extractText | boolean | Gör det möjligt att extrahera text. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Initierar en ny instans av klassen ViewInfoOptions för att hämta information om vyn vid rendering till PDF.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Initierar en ny instans av
ViewInfoOptions
klass baserad på objektet [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML‑visningsalternativen. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Initierar en ny instans av
ViewInfoOptions
klass baserad på objektet [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG‑visningsalternativen. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Initierar en ny instans av
ViewInfoOptions
klass baserad på objektet [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG‑visningsalternativen. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Initierar en ny instans av klassen [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) baserad på ett PdfViewOptions-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF‑visningsalternativen. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

