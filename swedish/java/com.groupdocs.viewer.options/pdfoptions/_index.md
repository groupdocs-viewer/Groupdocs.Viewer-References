---
title: "PdfOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för rendering av PDF-dokument."
type: docs
weight: 22
url: /sv/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Tillhandahåller alternativ för rendering av PDF-dokument.


PdfOptions-klassen kapslar in olika inställningar och parametrar som kan användas
för att styra rendering av PDF-dokument i GroupDocs.Viewer-komponenten.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Exempel på användning:

````

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
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Initierar en ny instans av |
PdfOptions
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Stänger av skydd mot kopiering av innehåll vid rendering till HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Stänger av skydd mot kopiering av innehåll vid rendering till HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Bestämmer om texten från källan renderas som en bild i HTML. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Ställer in om texten från källan renderas som en bild i HTML. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Kontrollerar om teckengruppning är inaktiverad för att bibehålla maximal precision vid teckenplacering när sidan renderas. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Ställer in alternativet att inaktivera teckengruppning, vilket säkerställer maximal precision vid teckenplacering när sidan renderas. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Kontrollerar om rendering av text och grafik ska följa z-ordningen i det ursprungliga PDF-dokumentet vid rendering till HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Aktiverar eller inaktiverar rendering av text och grafik enligt z-ordningen i det ursprungliga PDF-dokumentet när det renderas till HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Bestämmer om teckenhintning är aktiverad. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Aktiverar teckenhintning. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Aktiverar rendering av sidor med samma storlek i pixlar som sidstorleken i källdokumentet PDF. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Aktiverar rendering av sidor med samma storlek i pixlar som sidstorleken i källdokumentet PDF. |
|
|  | [getImageQuality()](#getImageQuality--) | Hämtar bildkvaliteten för bildresurser vid rendering till HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Ställer in bildkvaliteten för bildresurser vid rendering till HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF är ett fast format så alla element har en specifik plats på en sida. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF är ett fast format så alla element har en specifik plats på en sida. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Aktivera detta alternativ för att omsluta varje bild i utdata-HTML-dokumentet i en SVG-tagg för att förbättra kvaliteten. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Aktivera detta alternativ för att omsluta varje bild i utdata-HTML-dokumentet i en SVG-tagg för att förbättra kvaliteten. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Ställ in flaggan för att inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initierar en ny instans av
PdfOptions
klassen.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Stänger av skydd mot kopiering av innehåll vid rendering till HTML.


När PDF-filer renderas med skydd mot kopiering av text och bilder till HTML, lägger GroupDocs.Viewer till ett 'inert' HTML-attribut på HTML BODY-taggen.
Standardvärdet för detta alternativ är
false
.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Stänger av skydd mot kopiering av innehåll vid rendering till HTML.


När PDF-filer renderas med skydd mot kopiering av text och bilder till HTML, lägger GroupDocs.Viewer till ett 'inert' HTML-attribut på HTML BODY-taggen.
Standardvärdet för detta alternativ är
false
.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Bestämmer om texten från källan renderas som en bild i HTML.


När detta alternativ är inställt på
true
, renderas texten som en bild i utdata-HTML.
Aktivera detta alternativ för att göra texten omarkerbar eller för att rätta teckenrendering och få HTML att se ut som PDF.
Detta alternativ stöds vid rendering till HTML.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  om texten renderas som en bild i HTML,  false  annars.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Ställer in om texten från källan renderas som en bild i HTML.


När detta alternativ är inställt på
true
, renderas texten som en bild i utdata-HTML.
Aktivera detta alternativ för att göra texten omarkerbar eller för att rätta teckenrendering och få HTML att se ut som PDF.
Detta alternativ stöds vid rendering till HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  för att rendera texten som en bild i HTML,  false  annars. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Kontrollerar om teckengruppning är inaktiverad för att bibehålla maximal precision vid teckenplacering när sidan renderas.
När detta alternativ är aktiverat renderas tecknen utan någon gruppering, vilket säkerställer maximal precision.


***Note:** By default, character grouping is enabled.*
När PDF-filer konverteras grupperar GroupDocs.Viewer enskilda tecken till ord för förbättrad renderingsprestanda. Om ditt dokument innehåller hieroglyfer eller specialtecken kan du vilja förbjuda teckengruppning för att säkerställa en mer exakt layout. Standardvärdet är false.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean -  true  om teckengruppning är inaktiverad,  false  annars.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Ställer in alternativet att inaktivera teckengruppning, vilket säkerställer maximal precision vid teckenplacering när sidan renderas.
När detta alternativ är aktiverat genom att sätta värdet till
true
, teckengruppning är inaktiverad, vilket säkerställer maximal precision.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
När PDF-filer konverteras grupperar GroupDocs.Viewer enskilda tecken till ord för förbättrad renderingsprestanda. Om ditt dokument innehåller hieroglyfer eller specialtecken kan du vilja förbjuda teckengruppning för att säkerställa en mer exakt layout. Standardvärdet är false.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att inaktivera teckengruppning,  false  för att aktivera den. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Kontrollerar om rendering av text och grafik ska följa z-ordningen i det ursprungliga PDF-dokumentet vid rendering till HTML.
När detta alternativ är aktiverat genom att returnera
true
, renderas text och grafik enligt deras z-ordning i det ursprungliga PDF-dokumentet.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Som standard renderar GroupDocs.Veiewer text och grafik som ett enda lager i HTML. Detta alternativ låter dig ordna objekt i samma ordning som i källfilen. Standardvärdet är false.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean -  true  om lagerrendering är aktiverad,  false  annars.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Aktiverar eller inaktiverar rendering av text och grafik enligt z-ordningen i det ursprungliga PDF-dokumentet när det renderas till HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Som standard renderar GroupDocs.Veiewer text och grafik som ett enda lager i HTML. Detta alternativ låter dig ordna objekt i samma ordning som i källfilen. Standardvärdet är false.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att aktivera lagerrendering,  false  för att inaktivera den. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Bestämmer om typhintning är aktiverad. Typhintning justerar visningen av ett konturfont.
Detta alternativ stöds endast för TrueType (TTF)-fonter när de används i källdokumentet.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Typhintning justerar hur ett konturfont visas. Gäller endast för TTF-fonter som används i källdokumentet. Detta alternativ är tillgängligt för rendering till PNG- eller JPG-format. Standardvärdet är false.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean -  true  om typhintning är aktiverad,  false  annars.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Aktiverar typhintning. Typhintning justerar visningen av ett konturfont och stöds endast för TrueType (TTF)-fonter när de används i källdokumentet.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Typhintning justerar hur ett konturfont visas. Gäller endast för TTF-fonter som används i källdokumentet. Detta alternativ är tillgängligt för rendering till PNG- eller JPG-format. Standardvärdet är false.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att aktivera typhintning,  false  för att inaktivera den. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Aktiverar rendering av sidor med samma storlek i pixlar som sidstorleken i källdokumentet PDF.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Som standard beräknar GroupDocs.Viewer utdata bildsidstorlek för bättre renderingskvalitet. Aktivera detta alternativ för att säkerställa att utdata sidor har samma storlek som käll-PDF-dokumentets sidstorlek (i pixlar). Standardvärdet är false.
Detta alternativ är tillgängligt för rendering till PNG- eller JPG-format.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean -  true  om alternativet är aktiverat,  false  annars.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Aktiverar rendering av sidor med samma storlek i pixlar som sidstorleken i källdokumentet PDF.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Som standard beräknar GroupDocs.Viewer utdata bildsidstorlek för bättre renderingskvalitet. Aktivera detta alternativ för att säkerställa att utdata sidor har samma storlek som käll-PDF-dokumentets sidstorlek (i pixlar). Standardvärdet är false.
Detta alternativ är tillgängligt för rendering till PNG- eller JPG-format.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  för att aktivera rendering med original sidstorlek,  false  annars. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Hämtar bildkvaliteten för bildresurser vid rendering till HTML. Standardvärdet är Low.


När detta alternativ är satt till true renderar GroupDocs.Viewer text som en bild i HTML-utdata. Detta gör texten ovalbar och förbättrar teckengenerering, vilket säkerställer ett PDF-liknande utseende i HTML. Standardvärdet är false.
Detta alternativ är tillgängligt för rendering till HTML.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Ställer in bildkvaliteten för bildresurser vid rendering till HTML. Standardvärdet är Low.


När detta alternativ är satt till true renderar GroupDocs.Viewer text som en bild i HTML-utdata. Detta gör texten ovalbar och förbättrar teckengenerering, vilket säkerställer ett PDF-liknande utseende i HTML. Standardvärdet är false.
Detta alternativ är tillgängligt för rendering till HTML.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Bildkvaliteten för bildresurser vid rendering till HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF är ett fast format så alla element har en specifik plats på en sida.
För att säkerställa att den genererade HTML:n ser likadan ut som käll-PDF:en renderas dokumenten till HTML med en fast layout som standard.
Vid rendering med fast layout har den genererade HTML:n en fast storlek så att elementen förblir på samma plats oavsett fönsterstorlek.
För att rendera till HTML med flytande layout, sätt denna egenskap till false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF- och EPUB-dokument renderas initialt till HTML med en fast layout för att bevara källdokumentets utseende. Denna fasta layout innebär att alla HTML-element har exakta positioner inom en behållare med en bestämd storlek. Att ändra storlek på webbläsarfönstret påverkar inte positionen och storleken på elementen i dokumentet.
Detta alternativ är endast tillgängligt vid rendering till HTML. Standardvärdet är true. För att rendera med en flytande layout, sätt denna egenskap till false.


Exempel på användning:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - true om det är fast layout

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF är ett fast format så alla element har en specifik plats på en sida.
För att säkerställa att den genererade HTML:n ser likadan ut som käll-PDF:en renderas dokumenten till HTML med en fast layout som standard.
Vid rendering med fast layout har den genererade HTML:n en fast storlek så att elementen förblir på samma plats oavsett fönsterstorlek.
För att rendera till HTML med flytande layout, sätt denna egenskap till false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF- och EPUB-dokument renderas initialt till HTML med en fast layout för att bevara källdokumentets utseende. Denna fasta layout innebär att alla HTML-element har exakta positioner inom en behållare med en bestämd storlek. Att ändra storlek på webbläsarfönstret påverkar inte positionen och storleken på elementen i dokumentet.
Detta alternativ är endast tillgängligt vid rendering till HTML. Standardvärdet är true. För att rendera med en flytande layout, sätt denna egenskap till false.


Exempel på användning:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fixedLayout | boolean | true om det är fast layout |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Aktivera detta alternativ för att omsluta varje bild i utdata-HTML-dokumentet i en SVG-tagg för att förbättra kvaliteten.


Detta alternativ stöds när man renderar [PDF- och Page Layout-filformat](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) till HTML med inbäddade och externa resurser.


Som standard, när man renderar till PDF- och Page Layout-filer, renderas alla bilder som en enda PNG-bild. Den renderade PNG-bilden används som bakgrund för den genererade HTML-dokumentet.


Läs mer:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  true  om bilder är inbäddade i SVG,  false  annars.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Aktivera detta alternativ för att omsluta varje bild i utdata-HTML-dokumentet i en SVG-tagg för att förbättra kvaliteten.


Detta alternativ stöds när man renderar [PDF- och Page Layout-filformat](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) till HTML med inbäddade och externa resurser.


Som standard, när man renderar till PDF- och Page Layout-filer, renderas alla bilder som en enda PNG-bild. Den renderade PNG-bilden används som bakgrund för den genererade HTML-dokumentet.


Läs mer:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  om bilder ska inbäddas i SVG,  false  annars. |
|

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
|  | analyzeFonts | boolean | true om teckensnitten ska visas, false annars. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet.


Många operationer med teckensnittet kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt.
Till exempel kan vissa teckensnitt inte bäddas in i ett PDF-dokument om licensreglerna förbjuder inbäddning för detta teckensnitt.
Var försiktig när du använder den här flaggan. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar
för möjliga licens-/lagöverträdelser på sig själva. Så tar de det på egen risk. Det rekommenderas starkt att använda
denna flagga endast när du är helt säker på att du inte bryter mot upphovsrättslagen. Standardvärdet är falskt.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Exempel på användning:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Ställ in flaggan för att inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet.


Många operationer med teckensnittet kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt.
Till exempel kan vissa teckensnitt inte bäddas in i ett PDF-dokument om licensreglerna förbjuder inbäddning för detta teckensnitt.
Var försiktig när du använder den här flaggan. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar
för möjliga licens-/lagöverträdelser på sig själva. Så tar de det på egen risk. Det rekommenderas starkt att använda
denna flagga endast när du är helt säker på att du inte bryter mot upphovsrättslagen. Standardvärdet är falskt.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Exempel på användning:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

