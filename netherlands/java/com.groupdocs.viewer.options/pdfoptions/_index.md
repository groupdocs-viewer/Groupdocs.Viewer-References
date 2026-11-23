---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties voor het renderen van PDF‑documenten."
type: docs
weight: 22
url: /nl/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Biedt opties voor het renderen van PDF‑documenten.


De PdfOptions‑klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt
om de rendering van PDF‑documenten in de GroupDocs.Viewer‑component te regelen.
Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Initialiseert een nieuw exemplaar van |
PdfOptions
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Schakelt kopieerbeveiliging van inhoud uit bij het renderen naar HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Schakelt kopieerbeveiliging van inhoud uit bij het renderen naar HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Bepaalt of de tekst van de bron als afbeelding in HTML wordt gerenderd. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Stelt in of de tekst van de bron als afbeelding in HTML wordt gerenderd. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Controleert of karaktergroepering is uitgeschakeld om maximale precisie te behouden tijdens de positionering van tekens bij het renderen van de pagina. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Stelt de optie in om karaktergroepering uit te schakelen, waardoor maximale precisie wordt gegarandeerd tijdens de positionering van tekens bij het renderen van de pagina. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Controleert of de weergave van tekst en grafische elementen de z-volgorde in het oorspronkelijke PDF‑document moet volgen bij het renderen naar HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Schakelt het renderen van tekst en grafische elementen in of uit volgens de z-volgorde in het oorspronkelijke PDF‑document bij het renderen naar HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Bepaalt of lettertype‑hinting is ingeschakeld. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Schakelt lettertype‑hinting in. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Schakelt het renderen van pagina's in met dezelfde afmeting in pixels als de paginagrootte in het bron‑PDF‑document. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Schakelt het renderen van pagina's in met dezelfde afmeting in pixels als de paginagrootte in het bron‑PDF‑document. |
|
|  | [getImageQuality()](#getImageQuality--) | Haalt de uitvoer‑afbeeldingskwaliteit op voor afbeeldingsbronnen bij het renderen naar HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Stelt de uitvoer‑afbeeldingskwaliteit in voor afbeeldingsbronnen bij het renderen naar HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF is een vast formaat, zodat alle elementen een specifieke plaats op een pagina hebben. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF is een vast formaat, zodat alle elementen een specifieke plaats op een pagina hebben. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Schakel deze optie in om elke afbeelding in het uitvoer‑HTML‑document in een SVG‑tag te plaatsen om de uitvoerkwaliteit te verbeteren. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Schakel deze optie in om elke afbeelding in het uitvoer‑HTML‑document in een SVG‑tag te plaatsen om de uitvoerkwaliteit te verbeteren. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Vervangt lettertypen indien nodig om ervoor te zorgen dat alle tekens in de tekst kunnen worden weergegeven. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Vervangt lettertypen indien nodig om ervoor te zorgen dat alle tekens in de tekst kunnen worden weergegeven. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Schakel alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS‑document uit. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Stel de vlag in om alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS‑document uit te schakelen. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initialiseert een nieuw exemplaar van
PdfOptions
klasse.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Schakelt kopieerbeveiliging van inhoud uit bij het renderen naar HTML.


Bij het renderen van PDF‑bestanden met bescherming tegen het kopiëren van tekst en afbeeldingen naar HTML, voegt GroupDocs.Viewer een 'inert' HTML‑attribuut toe aan de HTML‑BODY‑tag.
De standaardwaarde van deze optie is
false
.


Voor code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Schakelt kopieerbeveiliging van inhoud uit bij het renderen naar HTML.


Bij het renderen van PDF‑bestanden met bescherming tegen het kopiëren van tekst en afbeeldingen naar HTML, voegt GroupDocs.Viewer een 'inert' HTML‑attribuut toe aan de HTML‑BODY‑tag.
De standaardwaarde van deze optie is
false
.


Voor code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Bepaalt of de tekst van de bron als afbeelding in HTML wordt gerenderd.


Wanneer deze optie is ingesteld op
true
, wordt de tekst gerenderd als een afbeelding in de uitvoer‑HTML.
Schakel deze optie in om de tekst niet‑selecteerbaar te maken of om de weergave van tekens te corrigeren en de HTML eruit te laten zien als een PDF.
Deze optie wordt ondersteund bij het renderen naar HTML.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  als de tekst wordt gerenderd als een afbeelding in HTML,  false  anders.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Stelt in of de tekst van de bron als afbeelding in HTML wordt gerenderd.


Wanneer deze optie is ingesteld op
true
, wordt de tekst gerenderd als een afbeelding in de uitvoer‑HTML.
Schakel deze optie in om de tekst niet‑selecteerbaar te maken of om de weergave van tekens te corrigeren en de HTML eruit te laten zien als een PDF.
Deze optie wordt ondersteund bij het renderen naar HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  om de tekst als een afbeelding in HTML weer te geven,  false  anders. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Controleert of karaktergroepering is uitgeschakeld om maximale precisie te behouden tijdens de positionering van tekens bij het renderen van de pagina.
Wanneer deze optie is ingeschakeld, worden de tekens zonder enige groepering weergegeven, wat maximale precisie garandeert.


***Note:** By default, character grouping is enabled.*
Bij het converteren van PDF‑bestanden groepeert GroupDocs.Viewer individuele tekens tot woorden voor verbeterde renderprestaties. Als uw document hiërogliefen of speciale symbolen bevat, wilt u mogelijk het groeperen van tekens verbieden om een nauwkeurigere lay-out te garanderen. De standaardwaarde is false.
Voor een code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean -  true  als tekengroepering is uitgeschakeld,  false  anders.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Stelt de optie in om karaktergroepering uit te schakelen, waardoor maximale precisie wordt gegarandeerd tijdens de positionering van tekens bij het renderen van de pagina.
Wanneer deze optie is ingeschakeld door de waarde in te stellen op
true
, is tekengroepering uitgeschakeld, wat maximale precisie garandeert.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
Bij het converteren van PDF‑bestanden groepeert GroupDocs.Viewer individuele tekens tot woorden voor verbeterde renderprestaties. Als uw document hiërogliefen of speciale symbolen bevat, wilt u mogelijk het groeperen van tekens verbieden om een nauwkeurigere lay-out te garanderen. De standaardwaarde is false.
Voor een code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om tekengroepering uit te schakelen,  false  om deze in te schakelen. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Controleert of de weergave van tekst en grafische elementen de z-volgorde in het oorspronkelijke PDF‑document moet volgen bij het renderen naar HTML.
Wanneer deze optie is ingeschakeld door te retourneren
true
, worden tekst en grafische elementen gerenderd volgens hun z‑volgorde in het oorspronkelijke PDF‑document.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Standaard rendert GroupDocs.Veiewer tekst en grafische elementen als één enkele laag in HTML. Deze optie stelt u in staat objecten in dezelfde volgorde als in het bronbestand te rangschikken. De standaardwaarde is false.
Voor een code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean -  true  als gelaagde rendering is ingeschakeld,  false  anders.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Schakelt het renderen van tekst en grafische elementen in of uit volgens de z-volgorde in het oorspronkelijke PDF‑document bij het renderen naar HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Standaard rendert GroupDocs.Veiewer tekst en grafische elementen als één enkele laag in HTML. Deze optie stelt u in staat objecten in dezelfde volgorde als in het bronbestand te rangschikken. De standaardwaarde is false.
Voor een code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om gelaagde rendering in te schakelen,  false  om deze uit te schakelen. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Bepaalt of lettertype‑hinting is ingeschakeld. Lettertype‑hinting past de weergave van een outline‑lettertype aan.
Deze optie wordt alleen ondersteund voor TrueType (TTF)-lettertypen wanneer ze in het brondocument worden gebruikt.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Lettertype‑hinting past aan hoe een outline‑lettertype wordt weergegeven. Alleen van toepassing op TTF‑lettertypen die in het brondocument worden gebruikt. Deze optie is beschikbaar voor rendering naar PNG‑ of JPG‑formaten. De standaardwaarde is false.
Voor een code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean -  true  als lettertype‑hinting is ingeschakeld,  false  anders.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Schakelt lettertype‑hinting in. Lettertype‑hinting past de weergave van een outline‑lettertype aan en wordt alleen ondersteund voor TrueType (TTF)-lettertypen wanneer ze in het brondocument worden gebruikt.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Lettertype‑hinting past aan hoe een outline‑lettertype wordt weergegeven. Alleen van toepassing op TTF‑lettertypen die in het brondocument worden gebruikt. Deze optie is beschikbaar voor rendering naar PNG‑ of JPG‑formaten. De standaardwaarde is false.
Voor een code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om lettertype‑hinting in te schakelen,  false  om deze uit te schakelen. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Schakelt het renderen van pagina's in met dezelfde afmeting in pixels als de paginagrootte in het bron‑PDF‑document.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Standaard berekent GroupDocs.Viewer de paginagrootte van de uitvoerafbeelding voor een betere renderkwaliteit. Schakel deze optie in om ervoor te zorgen dat de uitvoerpagina's dezelfde grootte hebben als de paginagrootte van het bron‑PDF‑document (in pixels). De standaardwaarde is false.
Deze optie is beschikbaar voor rendering naar PNG‑ of JPG‑formaten.
Voor een code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean -  true  als de optie is ingeschakeld,  false  anders.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Schakelt het renderen van pagina's in met dezelfde afmeting in pixels als de paginagrootte in het bron‑PDF‑document.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Standaard berekent GroupDocs.Viewer de paginagrootte van de uitvoerafbeelding voor een betere renderkwaliteit. Schakel deze optie in om ervoor te zorgen dat de uitvoerpagina's dezelfde grootte hebben als de paginagrootte van het bron‑PDF‑document (in pixels). De standaardwaarde is false.
Deze optie is beschikbaar voor rendering naar PNG‑ of JPG‑formaten.
Voor een code‑voorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  om rendering met de oorspronkelijke paginagrootte in te schakelen,  false  anders. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Haalt de uitvoerbeeldkwaliteit op voor afbeeldingsbronnen bij het renderen naar HTML. De standaardwaarde is Low.


Wanneer deze optie is ingesteld op true, rendert GroupDocs.Viewer tekst als een afbeelding in de HTML-uitvoer. Hierdoor is de tekst niet selecteerbaar en wordt de weergave van tekens verbeterd, waardoor een PDF-achtige weergave in HTML ontstaat. De standaardwaarde is false.
Deze optie is beschikbaar voor het renderen naar HTML.
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Stelt de uitvoerbeeldkwaliteit in voor afbeeldingsbronnen bij het renderen naar HTML. De standaardwaarde is Low.


Wanneer deze optie is ingesteld op true, rendert GroupDocs.Viewer tekst als een afbeelding in de HTML-uitvoer. Hierdoor is de tekst niet selecteerbaar en wordt de weergave van tekens verbeterd, waardoor een PDF-achtige weergave in HTML ontstaat. De standaardwaarde is false.
Deze optie is beschikbaar voor het renderen naar HTML.
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | De uitvoerbeeldkwaliteit voor afbeeldingsbronnen bij het renderen naar HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF is een vast formaat, zodat alle elementen een specifieke plaats op een pagina hebben.
Om ervoor te zorgen dat de uitvoer-HTML er hetzelfde uitziet als de bron-PDF, worden de documenten standaard naar HTML gerenderd met een vaste lay-out.
Bij het renderen met een vaste lay-out heeft de uitvoer-HTML een vaste grootte, zodat de elementen op dezelfde plaats blijven, ongeacht de venstergrootte.
Om naar HTML te renderen met een vloeiende lay-out, stel deze eigenschap in op false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF- en EPUB-documenten worden aanvankelijk naar HTML gerenderd met een vaste lay-out om het uiterlijk van het brondocument te behouden. Deze vaste lay-out betekent dat alle HTML-elementen precieze posities hebben binnen een container met een vaste grootte. Het wijzigen van de grootte van het browservenster heeft geen invloed op de positie en grootte van elementen in het document.
Deze optie is alleen beschikbaar bij het renderen naar HTML. De standaardwaarde is true. Om met een vloeiende lay-out te renderen, stel deze eigenschap in op false.


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - true als het een vaste lay-out is

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF is een vast formaat, zodat alle elementen een specifieke plaats op een pagina hebben.
Om ervoor te zorgen dat de uitvoer-HTML er hetzelfde uitziet als de bron-PDF, worden de documenten standaard naar HTML gerenderd met een vaste lay-out.
Bij het renderen met een vaste lay-out heeft de uitvoer-HTML een vaste grootte, zodat de elementen op dezelfde plaats blijven, ongeacht de venstergrootte.
Om naar HTML te renderen met een vloeiende lay-out, stel deze eigenschap in op false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF- en EPUB-documenten worden aanvankelijk naar HTML gerenderd met een vaste lay-out om het uiterlijk van het brondocument te behouden. Deze vaste lay-out betekent dat alle HTML-elementen precieze posities hebben binnen een container met een vaste grootte. Het wijzigen van de grootte van het browservenster heeft geen invloed op de positie en grootte van elementen in het document.
Deze optie is alleen beschikbaar bij het renderen naar HTML. De standaardwaarde is true. Om met een vloeiende lay-out te renderen, stel deze eigenschap in op false.


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fixedLayout | boolean | true als het een vaste lay-out is |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Schakel deze optie in om elke afbeelding in het uitvoer‑HTML‑document in een SVG‑tag te plaatsen om de uitvoerkwaliteit te verbeteren.


Deze optie wordt ondersteund bij het renderen van [PDF- en Page Layout-bestandsformaten](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) naar HTML met ingebedde en externe bronnen.


Standaard, bij het renderen naar PDF- en Page Layout-bestanden, worden alle afbeeldingen gerenderd als één PNG-afbeelding. De gerenderde PNG-afbeelding wordt gebruikt als achtergrond voor het uitvoer-HTML-document.


Meer informatie:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  true  als afbeeldingen zijn ingepakt in SVG,  false  anders.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Schakel deze optie in om elke afbeelding in het uitvoer‑HTML‑document in een SVG‑tag te plaatsen om de uitvoerkwaliteit te verbeteren.


Deze optie wordt ondersteund bij het renderen van [PDF- en Page Layout-bestandsformaten](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) naar HTML met ingebedde en externe bronnen.


Standaard, bij het renderen naar PDF- en Page Layout-bestanden, worden alle afbeeldingen gerenderd als één PNG-afbeelding. De gerenderde PNG-afbeelding wordt gebruikt als achtergrond voor het uitvoer-HTML-document.


Meer informatie:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  als afbeeldingen moeten worden ingepakt in SVG,  false  anders. |
|

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
|  | analyzeFonts | boolean | true als de lettertypen moeten worden weergegeven, false anders. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Schakel alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS‑document uit.


Veel bewerkingen met lettertype kunnen niet worden uitgevoerd als deze bewerkingen verboden zijn door de licentie van dit lettertype.
Bijvoorbeeld, sommige lettertypen kunnen niet in een PDF-document worden ingebed als de licentieregels het insluiten voor dit lettertype uitschakelen.
Wees voorzichtig bij het gebruik van deze vlag. Wanneer deze is ingesteld, betekent dit dat de persoon die deze vlag instelt alle verantwoordelijkheid neemt
voor mogelijke licentie-/wetsovertredingen op zichzelf. Dus ze nemen het op eigen risico. Het wordt sterk aanbevolen om
deze vlag alleen te gebruiken wanneer u er volledig van overtuigd bent dat u de auteurswet niet schendt. Standaard is false.
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Voorbeeldgebruik:

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


Stel de vlag in om alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS‑document uit te schakelen.


Veel bewerkingen met lettertype kunnen niet worden uitgevoerd als deze bewerkingen verboden zijn door de licentie van dit lettertype.
Bijvoorbeeld, sommige lettertypen kunnen niet in een PDF-document worden ingebed als de licentieregels het insluiten voor dit lettertype uitschakelen.
Wees voorzichtig bij het gebruik van deze vlag. Wanneer deze is ingesteld, betekent dit dat de persoon die deze vlag instelt alle verantwoordelijkheid neemt
voor mogelijke licentie-/wetsovertredingen op zichzelf. Dus ze nemen het op eigen risico. Het wordt sterk aanbevolen om
deze vlag alleen te gebruiken wanneer u er volledig van overtuigd bent dat u de auteurswet niet schendt. Standaard is false.
Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

