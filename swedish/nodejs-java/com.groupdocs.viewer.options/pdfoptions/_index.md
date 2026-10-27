---
title: "PdfOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av PDF-dokument."
type: docs
weight: 22
url: /sv/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Tillhandahåller alternativ för rendering av PDF-dokument.

PdfOptions-klassen kapslar in olika inställningar och parametrar som kan användas för att styra rendering av PDF-dokument i GroupDocs.Viewer-komponenten. För detaljer, se [documentation][].

Exempel på användning:

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initierar en ny instans av PdfOptions-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | Stänger av skydd mot kopiering av innehåll vid rendering till HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Stänger av skydd mot kopiering av innehåll vid rendering till HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Bestämmer om texten från källan renderas som en bild i HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Ställer in om texten från källan renderas som en bild i HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Kontrollerar om teckengruppning är inaktiverad för att behålla maximal precision vid teckenpositionering när sidan renderas. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Ställer in alternativet att inaktivera teckengruppning, vilket säkerställer maximal precision vid teckenpositionering när sidan renderas. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Kontrollerar om rendering av text och grafik ska följa z-ordningen i det ursprungliga PDF-dokumentet vid rendering till HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Aktiverar eller inaktiverar rendering av text och grafik enligt z-ordningen i det ursprungliga PDF-dokumentet vid rendering till HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Bestämmer om teckenhintning är aktiverad. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Aktiverar teckenhintning. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Aktiverar rendering av sidor med samma storlek i pixlar som sidstorleken i käll-PDF-dokumentet. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Aktiverar rendering av sidor med samma storlek i pixlar som sidstorleken i käll-PDF-dokumentet. |
| [getImageQuality()](#getImageQuality--) | Hämtar bildkvaliteten för bildresurser vid rendering till HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Ställer in bildkvaliteten för bildresurser vid rendering till HTML. |
| [isFixedLayout()](#isFixedLayout--) | PDF är ett fast format så alla element har en specifik plats på en sida. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF är ett fast format så alla element har en specifik plats på en sida. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Aktivera detta alternativ för att omsluta varje bild i utdata-HTML-dokumentet i en SVG-tagg för att förbättra kvaliteten. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Aktivera detta alternativ för att omsluta varje bild i utdata-HTML-dokumentet i en SVG-tagg för att förbättra kvaliteten. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Försöker åtgärda problemet när hela HTML-sidans innehåll är en länk. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Försöker åtgärda problemet när hela HTML-sidans innehåll är en länk. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Ställ in flaggan för att inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initierar en ny instans av PdfOptions-klassen.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Stänger av skydd mot kopiering av innehåll vid rendering till HTML.

När PDF-filer renderas med skydd mot kopiering av text och bilder till HTML, lägger GroupDocs.Viewer till ett 'inert' HTML-attribut på HTML BODY-taggen. Standardvärdet för detta alternativ är false.

För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Stänger av skydd mot kopiering av innehåll vid rendering till HTML.

När PDF-filer renderas med skydd mot kopiering av text och bilder till HTML, lägger GroupDocs.Viewer till ett 'inert' HTML-attribut på HTML BODY-taggen. Standardvärdet för detta alternativ är false.

För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Bestämmer om texten från källan renderas som en bild i HTML.

När detta alternativ är satt till true renderas texten som en bild i den genererade HTML:n. Aktivera detta alternativ för att göra texten omarkerbar eller för att korrigera teckengenerering och få HTML att se ut som PDF. Detta alternativ stöds vid rendering till HTML.

***Note:** The default value is  false .*

**Returns:**
boolean - true om texten renderas som en bild i HTML, false annars.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Ställer in om texten från källan renderas som en bild i HTML.

När detta alternativ är satt till true renderas texten som en bild i den genererade HTML:n. Aktivera detta alternativ för att göra texten omarkerbar eller för att korrigera teckengenerering och få HTML att se ut som PDF. Detta alternativ stöds vid rendering till HTML.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderTextAsImage | boolean | true för att rendera texten som en bild i HTML, false annars. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Kontrollerar om teckengruppning är inaktiverad för att bibehålla maximal precision vid teckenpositionering när sidan renderas. När detta alternativ är aktiverat renderas tecknen utan någon gruppering, vilket säkerställer maximal precision.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean - true om teckengruppning är inaktiverad, false annars.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Ställer in alternativet för att inaktivera teckengruppning, vilket säkerställer maximal precision vid teckenpositionering när sidan renderas. När detta alternativ aktiveras genom att sätta värdet till true, är teckengruppning inaktiverad, vilket säkerställer maximal precision.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true för att inaktivera teckengruppning, false för att aktivera den. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Kontrollerar om rendering av text och grafik ska följa z-ordningen i det ursprungliga PDF-dokumentet när det renderas till HTML. När detta alternativ aktiveras genom att returnera true, renderas text och grafik enligt deras z-ordning i det ursprungliga PDF-dokumentet.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean - true om lagerbaserad rendering är aktiverad, false annars.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Aktiverar eller inaktiverar rendering av text och grafik enligt z-ordningen i det ursprungliga PDF-dokumentet vid rendering till HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true för att aktivera lagerbaserad rendering, false för att inaktivera den. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Bestämmer om teckensnittshintning är aktiverad. Teckensnittshintning justerar visningen av ett konturteckensnitt. Detta alternativ stöds endast för TrueType (TTF)-teckensnitt när de används i källdokumentet.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean - true om teckensnittshintning är aktiverad, false annars.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Aktiverar teckensnittshintning. Teckensnittshintning justerar visningen av ett konturteckensnitt och stöds endast för TrueType (TTF)-teckensnitt när de används i källdokumentet.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true för att aktivera teckensnittshintning, false för att inaktivera den. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Aktiverar rendering av sidor med samma storlek i pixlar som sidstorleken i käll-PDF-dokumentet.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean - true om alternativet är aktiverat, false annars.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Aktiverar rendering av sidor med samma storlek i pixlar som sidstorleken i käll-PDF-dokumentet.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true för att aktivera rendering med original sidstorlek, false annars. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Hämtar bildkvaliteten för bildresurser vid rendering till HTML. Standardvärdet är Low.

När detta alternativ är satt till true renderar GroupDocs.Viewer text som en bild i HTML-utdata. Detta gör texten omarkerbar och förbättrar teckengenerering, vilket säkerställer ett PDF-liknande utseende i HTML. Standardvärdet är false. Detta alternativ är tillgängligt för rendering till HTML. För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Ställer in bildkvaliteten för bildresurser vid rendering till HTML. Standardvärdet är Low.

När detta alternativ är satt till true renderar GroupDocs.Viewer text som en bild i HTML-utdata. Detta gör texten omarkerbar och förbättrar teckengenerering, vilket säkerställer ett PDF-liknande utseende i HTML. Standardvärdet är false. Detta alternativ är tillgängligt för rendering till HTML. För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Utdata bildkvalitet för bildresurser vid rendering till HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF är ett fast format så alla element har en specifik plats på en sida. För att säkerställa att den genererade HTML:n ser likadan ut som käll-PDF:en renderas dokumenten till HTML med en fast layout som standard. När rendering sker med fast layout har den genererade HTML:n en fast storlek så att elementen förblir på samma plats oavsett fönsterstorlek. För att rendera till HTML med flytande layout, sätt denna egenskap till false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - true om det är fast layout
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF är ett fast format så alla element har en specifik plats på en sida. För att säkerställa att den genererade HTML:n ser likadan ut som käll-PDF:en renderas dokumenten till HTML med en fast layout som standard. När rendering sker med fast layout har den genererade HTML:n en fast storlek så att elementen förblir på samma plats oavsett fönsterstorlek. För att rendera till HTML med flytande layout, sätt denna egenskap till false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixedLayout | boolean | true om det är fast layout |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Aktivera detta alternativ för att omsluta varje bild i utdata-HTML-dokumentet i en SVG-tagg för att förbättra kvaliteten.

Detta alternativ stöds när du renderar [PDF och Page Layout-filformat][] till HTML med inbäddade och externa resurser.

Som standard, när du renderar till PDF- och Page Layout-filer, renderas alla bilder som en enda PNG-bild. Den renderade PNG-bilden används som bakgrund för den genererade HTML-dokumentet.

Läs mer:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean -  true  om bilder är inbäddade i SVG,  false  annars.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Aktivera detta alternativ för att omsluta varje bild i utdata-HTML-dokumentet i en SVG-tagg för att förbättra kvaliteten.

Detta alternativ stöds när du renderar [PDF och Page Layout-filformat][] till HTML med inbäddade och externa resurser.

Som standard, när du renderar till PDF- och Page Layout-filer, renderas alla bilder som en enda PNG-bild. Den renderade PNG-bilden används som bakgrund för den genererade HTML-dokumentet.

Läs mer:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true  om bilder ska inbäddas i SVG,  false  annars. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Försöker åtgärda problemet när hela HTML-sidans innehåll är en länk. Fungerar endast när indataformatet är PDF och utdataformatet är HTML (med inbäddade eller externa resurser). Som standard är det inaktiverat (false). Aktivera det endast när du vet vad du gör och varför. Att slå på detta alternativ ökar dokumentets bearbetningstid.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Försöker åtgärda problemet när hela HTML-sidans innehåll är en länk. Fungerar endast när indataformatet är PDF och utdataformatet är HTML (med inbäddade eller externa resurser). Som standard är det inaktiverat (false). Aktivera det endast när du vet vad du gör och varför. Att slå på detta alternativ ökar dokumentets bearbetningstid.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fixLinkIssue | boolean | true om problemet ska åtgärdas, false annars. |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas.

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| analyzeFonts | boolean | true om teckensnitten ska visas, false annars. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet.

Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av teckensnittets licens. Till exempel kan vissa teckensnitt inte bäddas in i ett PDF-dokument om licensreglerna förbjuder inbäddning för detta teckensnitt. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens-/lagöverträdelser på egen hand. Så de gör det på egen risk. Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter mot upphovsrättslagen. Som standard false. För kodexempel, se [dokumentation][].

Exempel på användning:

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


Ställ in flaggan för att inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet.

Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av teckensnittets licens. Till exempel kan vissa teckensnitt inte bäddas in i ett PDF-dokument om licensreglerna förbjuder inbäddning för detta teckensnitt. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens-/lagöverträdelser på egen hand. Så de gör det på egen risk. Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter mot upphovsrättslagen. Som standard false. För kodexempel, se [dokumentation][].

Exempel på användning:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

