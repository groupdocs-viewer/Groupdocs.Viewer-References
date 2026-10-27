---
title: "PdfOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van PDF-documenten."
type: docs
weight: 22
url: /nl/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Biedt opties voor het renderen van PDF-documenten.

De PdfOptions-klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt om de weergave van PDF-documenten in de GroupDocs.Viewer-component te regelen. Voor details, zie de [documentation][].

Voorbeeldgebruik:

```

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initialiseert een nieuw exemplaar van de PdfOptions-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | Schakelt de bescherming tegen kopiëren van inhoud uit bij het renderen naar HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Schakelt de bescherming tegen kopiëren van inhoud uit bij het renderen naar HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Bepaalt of de tekst van de bron wordt weergegeven als een afbeelding in HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Stelt in of de tekst van de bron wordt weergegeven als een afbeelding in HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Controleert of tekengroepering is uitgeschakeld om maximale precisie te behouden tijdens de positionering van tekens bij het renderen van de pagina. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Stelt de optie in om tekengroepering uit te schakelen, waardoor maximale precisie wordt gegarandeerd tijdens de positionering van tekens bij het renderen van de pagina. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Controleert of de weergave van tekst en grafische elementen de z-volgorde in het oorspronkelijke PDF-document moet volgen bij het renderen naar HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Schakelt de weergave van tekst en grafische elementen in of uit volgens de z-volgorde in het oorspronkelijke PDF-document bij het renderen naar HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Bepaalt of font-hinting is ingeschakeld. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Schakelt font-hinting in. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Schakelt de weergave van pagina's in met dezelfde afmeting in pixels als de paginagrootte in het bron-PDF-document. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Schakelt de weergave van pagina's in met dezelfde afmeting in pixels als de paginagrootte in het bron-PDF-document. |
| [getImageQuality()](#getImageQuality--) | Haalt de uitvoerbeeldkwaliteit op voor afbeeldingsbronnen bij het renderen naar HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Stelt de uitvoerbeeldkwaliteit in voor afbeeldingsbronnen bij het renderen naar HTML. |
| [isFixedLayout()](#isFixedLayout--) | PDF is een vast formaat, zodat alle elementen een specifieke plaats op een pagina hebben. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF is een vast formaat, zodat alle elementen een specifieke plaats op een pagina hebben. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Schakel deze optie in om elke afbeelding in het uitvoer-HTML-document te omhullen met een SVG-tag om de uitvoerkwaliteit te verbeteren. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Schakel deze optie in om elke afbeelding in het uitvoer-HTML-document te omhullen met een SVG-tag om de uitvoerkwaliteit te verbeteren. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Probeert het probleem op te lossen wanneer de volledige HTML-paginainhoud een link is. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Probeert het probleem op te lossen wanneer de volledige HTML-paginainhoud een link is. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Vervangt lettertypen indien nodig om ervoor te zorgen dat alle tekens in de tekst kunnen worden weergegeven. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Vervangt lettertypen indien nodig om ervoor te zorgen dat alle tekens in de tekst kunnen worden weergegeven. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Schakel eventuele licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS-document uit. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Stel de vlag in om alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS-document uit te schakelen. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initialiseert een nieuw exemplaar van de PdfOptions-klasse.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Schakelt de bescherming tegen kopiëren van inhoud uit bij het renderen naar HTML.

Bij het renderen van PDF‑bestanden met bescherming tegen het kopiëren van tekst en afbeeldingen naar HTML, voegt GroupDocs.Viewer een 'inert' HTML‑attribuut toe aan de HTML BODY‑tag. De standaardwaarde van deze optie is false.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Schakelt de bescherming tegen kopiëren van inhoud uit bij het renderen naar HTML.

Bij het renderen van PDF‑bestanden met bescherming tegen het kopiëren van tekst en afbeeldingen naar HTML, voegt GroupDocs.Viewer een 'inert' HTML‑attribuut toe aan de HTML BODY‑tag. De standaardwaarde van deze optie is false.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Bepaalt of de tekst van de bron wordt weergegeven als een afbeelding in HTML.

Wanneer deze optie is ingesteld op true, wordt de tekst als een afbeelding gerenderd in de uitvoer‑HTML. Schakel deze optie in om de tekst niet‑selecteerbaar te maken of om de weergave van tekens te corrigeren en de HTML eruit te laten zien als PDF. Deze optie wordt ondersteund bij het renderen naar HTML.

***Note:** The default value is  false .*

**Returns:**
boolean - true als de tekst als een afbeelding in HTML wordt gerenderd, false anders.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Stelt in of de tekst van de bron wordt weergegeven als een afbeelding in HTML.

Wanneer deze optie is ingesteld op true, wordt de tekst als een afbeelding gerenderd in de uitvoer‑HTML. Schakel deze optie in om de tekst niet‑selecteerbaar te maken of om de weergave van tekens te corrigeren en de HTML eruit te laten zien als PDF. Deze optie wordt ondersteund bij het renderen naar HTML.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderTextAsImage | boolean | true om de tekst als een afbeelding in HTML te renderen, false anders. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Controleert of teken‑groepering is uitgeschakeld om maximale precisie te behouden tijdens de positionering van tekens bij het renderen van de pagina. Wanneer deze optie is ingeschakeld, worden de tekens zonder enige groepering gerenderd, wat maximale precisie garandeert.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean - true als teken‑groepering is uitgeschakeld, false anders.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Stelt de optie in om teken‑groepering uit te schakelen, waardoor maximale precisie tijdens de positionering van tekens bij het renderen van de pagina wordt gegarandeerd. Wanneer deze optie wordt ingeschakeld door de waarde op true te zetten, is teken‑groepering uitgeschakeld, wat maximale precisie verzekert.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true om teken‑groepering uit te schakelen, false om deze in te schakelen. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Controleert of het renderen van tekst en grafische elementen de z-volgorde in het oorspronkelijke PDF‑document moet volgen bij het renderen naar HTML. Wanneer deze optie wordt ingeschakeld door true te retourneren, worden tekst en grafische elementen gerenderd volgens hun z-volgorde in het oorspronkelijke PDF‑document.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean - true als gelaagd renderen is ingeschakeld, false anders.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Schakelt de weergave van tekst en grafische elementen in of uit volgens de z-volgorde in het oorspronkelijke PDF-document bij het renderen naar HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true om gelaagd renderen in te schakelen, false om dit uit te schakelen. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Bepaalt of font‑hinting is ingeschakeld. Font‑hinting past de weergave van een outline‑lettertype aan. Deze optie wordt alleen ondersteund voor TrueType (TTF)-lettertypen wanneer ze in het bron‑document worden gebruikt.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean - true als font‑hinting is ingeschakeld, false anders.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Schakelt font‑hinting in. Font‑hinting past de weergave van een outline‑lettertype aan en wordt alleen ondersteund voor TrueType (TTF)-lettertypen wanneer ze in het bron‑document worden gebruikt.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true om font‑hinting in te schakelen, false om dit uit te schakelen. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Schakelt de weergave van pagina's in met dezelfde afmeting in pixels als de paginagrootte in het bron-PDF-document.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean - true als de optie is ingeschakeld, false anders.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Schakelt de weergave van pagina's in met dezelfde afmeting in pixels als de paginagrootte in het bron-PDF-document.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true om renderen met de oorspronkelijke paginagrootte in te schakelen, false anders. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Haalt de uitvoer‑afbeeldingskwaliteit op voor afbeeldingsbronnen bij het renderen naar HTML. De standaardwaarde is Low.

Wanneer deze optie is ingesteld op true, rendert GroupDocs.Viewer tekst als een afbeelding in de HTML‑output. Hierdoor wordt de tekst niet‑selecteerbaar en verbetert de weergave van tekens, waardoor een PDF‑achtige weergave in HTML wordt gegarandeerd. De standaardwaarde is false. Deze optie is beschikbaar voor renderen naar HTML. Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Stelt de uitvoer‑afbeeldingskwaliteit in voor afbeeldingsbronnen bij het renderen naar HTML. De standaardwaarde is Low.

Wanneer deze optie is ingesteld op true, rendert GroupDocs.Viewer tekst als een afbeelding in de HTML‑output. Hierdoor wordt de tekst niet‑selecteerbaar en verbetert de weergave van tekens, waardoor een PDF‑achtige weergave in HTML wordt gegarandeerd. De standaardwaarde is false. Deze optie is beschikbaar voor renderen naar HTML. Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | De uitvoerbeeldkwaliteit voor afbeeldingsbronnen bij het renderen naar HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF is een vast formaat, dus alle elementen hebben een specifieke plaats op een pagina. Om ervoor te zorgen dat de uitvoer-HTML er hetzelfde uitziet als de bron-PDF, worden de documenten standaard naar HTML gerenderd met een vaste lay-out. Bij het renderen met een vaste lay-out heeft de uitvoer-HTML een vaste grootte, zodat de elementen op dezelfde plaats blijven, ongeacht de venstergrootte. Om naar HTML te renderen met een vloeiende lay-out, stel deze eigenschap in op false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - true als het een vaste lay-out is
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF is een vast formaat, dus alle elementen hebben een specifieke plaats op een pagina. Om ervoor te zorgen dat de uitvoer-HTML er hetzelfde uitziet als de bron-PDF, worden de documenten standaard naar HTML gerenderd met een vaste lay-out. Bij het renderen met een vaste lay-out heeft de uitvoer-HTML een vaste grootte, zodat de elementen op dezelfde plaats blijven, ongeacht de venstergrootte. Om naar HTML te renderen met een vloeiende lay-out, stel deze eigenschap in op false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fixedLayout | boolean | true als het een vaste lay-out is |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Schakel deze optie in om elke afbeelding in het uitvoer-HTML-document te omhullen met een SVG-tag om de uitvoerkwaliteit te verbeteren.

Deze optie wordt ondersteund bij het renderen van [PDF and Page Layout file formats][] naar HTML met ingesloten en externe bronnen.

Standaard, bij het renderen naar PDF- en Page Layout-bestanden, worden alle afbeeldingen gerenderd als één PNG-afbeelding. De gerenderde PNG-afbeelding wordt gebruikt als achtergrond voor het uitvoer-HTML-document.

Meer informatie:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean -  true  als afbeeldingen zijn ingepakt in SVG,  false  anders.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Schakel deze optie in om elke afbeelding in het uitvoer-HTML-document te omhullen met een SVG-tag om de uitvoerkwaliteit te verbeteren.

Deze optie wordt ondersteund bij het renderen van [PDF and Page Layout file formats][] naar HTML met ingesloten en externe bronnen.

Standaard, bij het renderen naar PDF- en Page Layout-bestanden, worden alle afbeeldingen gerenderd als één PNG-afbeelding. De gerenderde PNG-afbeelding wordt gebruikt als achtergrond voor het uitvoer-HTML-document.

Meer informatie:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true  als afbeeldingen moeten worden ingepakt in SVG,  false  anders. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Probeert het probleem op te lossen wanneer de volledige HTML-paginainhoud een link is. Werkt alleen wanneer het invoerformaat PDF is en het uitvoerformaat HTML (met ingesloten of externe bronnen). Standaard is uitgeschakeld (false). Schakel het alleen in wanneer u weet wat en waarom u dit doet. Het inschakelen van deze optie verhoogt de verwerkingstijd van het document.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Probeert het probleem op te lossen wanneer de volledige HTML-paginainhoud een link is. Werkt alleen wanneer het invoerformaat PDF is en het uitvoerformaat HTML (met ingesloten of externe bronnen). Standaard is uitgeschakeld (false). Schakel het alleen in wanneer u weet wat en waarom u dit doet. Het inschakelen van deze optie verhoogt de verwerkingstijd van het document.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fixLinkIssue | boolean | true als het probleem moet worden opgelost, false anders. |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Vervangt lettertypen indien nodig om ervoor te zorgen dat alle tekens in de tekst kunnen worden weergegeven.

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Vervangt lettertypen indien nodig om ervoor te zorgen dat alle tekens in de tekst kunnen worden weergegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| analyzeFonts | boolean | true als de lettertypen moeten worden weergegeven, false anders. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Schakel eventuele licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS-document uit.

Veel bewerkingen met lettertypen kunnen niet worden uitgevoerd als deze bewerkingen verboden zijn door de licentie van het lettertype. Bijvoorbeeld, sommige lettertypen kunnen niet in een PDF-document worden ingesloten als de licentieregels het insluiten voor dit lettertype uitschakelen. Wees voorzichtig bij het gebruik van deze vlag. Wanneer deze is ingesteld, betekent dit dat de persoon die deze vlag instelt alle verantwoordelijkheid voor mogelijke licentie-/wetsovertredingen op zich neemt. Ze doen dit dus op eigen risico. Het wordt sterk aanbevolen deze vlag alleen te gebruiken wanneer u er volledig van overtuigd bent dat u geen auteursrechten schendt. Standaard false. Voor een codevoorbeeld, zie de [documentation][].

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Stel de vlag in om alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS-document uit te schakelen.

Veel bewerkingen met lettertypen kunnen niet worden uitgevoerd als deze bewerkingen verboden zijn door de licentie van het lettertype. Bijvoorbeeld, sommige lettertypen kunnen niet in een PDF-document worden ingesloten als de licentieregels het insluiten voor dit lettertype uitschakelen. Wees voorzichtig bij het gebruik van deze vlag. Wanneer deze is ingesteld, betekent dit dat de persoon die deze vlag instelt alle verantwoordelijkheid voor mogelijke licentie-/wetsovertredingen op zich neemt. Ze doen dit dus op eigen risico. Het wordt sterk aanbevolen deze vlag alleen te gebruiken wanneer u er volledig van overtuigd bent dat u geen auteursrechten schendt. Standaard false. Voor een codevoorbeeld, zie de [documentation][].

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

