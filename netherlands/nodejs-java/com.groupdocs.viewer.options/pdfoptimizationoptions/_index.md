---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Gebruik deze klasse om PDF-optimalisatieopties op te geven die op het uitvoer‑PDF‑bestand moeten worden toegepast."
type: docs
weight: 21
url: /nl/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Gebruik deze klasse om PDF-optimalisatieopties op te geven die op het uitvoer‑PDF‑bestand moeten worden toegepast.

Deze optimalisatie‑opties worden ondersteund voor alle invoerbestandsformaten die ondersteund worden voor export naar PDF. Voor details en code‑voorbeelden, zie deze [page][] en de onderliggende pagina's.

Voorbeeldgebruik:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Stelt de standaardwaarden in voor de MaxResolution‑optie op 300 en de ImageQuality‑optie op 100. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isLinearize()](#isLinearize--) | Schakelt optimalisatie van het uitvoer‑PDF‑bestand in voor weergave online met een webbrowser. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Duidt of het uitvoer‑PDF moet worden geoptimaliseerd voor online browsen met een webbrowser. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Annotaties kunnen worden verwijderd wanneer ze overbodig zijn. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Bepaalt of overbodige annotaties uit de PDF worden verwijderd. |
| [isRemoveFormFields()](#isRemoveFormFields--) | Als het PDF‑document AcroForms bevat, kunnen we proberen de bestandsgrootte te verkleinen door de formulier‑velden plat te maken. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Bepaalt of formulier‑velden uit de PDF worden verwijderd. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | Een PDF‑bestand bestaat uit Tekst, Afbeelding, Bijlage, Annotaties, Grafieken en andere objecten. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Bepaalt of de PDF naar grijstinten wordt geconverteerd. |
| [isSubsetFonts()](#isSubsetFonts--) | Elk lettertype dat wordt gebruikt om tekst op de pagina weer te geven, bevat een reeks glyphs voor de lettertekens. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Bepaalt of de lettertypen in de PDF worden onderverdeeld. |
| [isCompressImages()](#isCompressImages--) | Als het bron‑PDF‑bestand afbeeldingen bevat, overweeg dan de afbeeldingen te comprimeren en hun kwaliteit in te stellen. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Bepaalt of de afbeeldingen in de PDF worden gecomprimeerd. |
| [getImageQuality()](#getImageQuality--) | Als het bron‑PDF‑bestand afbeeldingen bevat, overweeg dan de afbeeldingen te comprimeren en hun kwaliteit in te stellen. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | Stelt de afbeeldingskwaliteit in voor het comprimeren van de afbeeldingen in de PDF. |
| [isResizeImages()](#isResizeImages--) | Kan worden gebruikt met de optie CompressImages om de afbeeldingen te verkleinen tot een lagere resolutie. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Bepaalt of de afbeeldingen in de PDF worden verkleind. |
| [getMaxResolution()](#getMaxResolution--) | Kan worden gebruikt met de optie CompressImages om de afbeeldingen te verkleinen tot een lagere resolutie. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Stelt de maximale resolutie in voor het verkleinen van de afbeeldingen in de PDF. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimaliseer de randlijnen en lettertypen van Excel‑werkbladen voor een kleinere uitvoer‑bestandsgrootte. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Bepaalt of de werkbladen in de PDF worden geoptimaliseerd. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Verwijder privé‑informatie (pagina‑stuk‑info) indien ingesteld op waar. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Bepaalt of privé‑informatie uit de PDF wordt verwijderd. |
| [isUnembedFonts()](#isUnembedFonts--) | Als het document ingesloten lettertypen gebruikt, betekent dit dat alle lettertype‑gegevens in het document zijn opgenomen. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Bepaalt of de ingesloten lettertypen uit de PDF worden verwijderd. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Soms bevat een document meerdere identieke resource‑streams (bijvoorbeeld afbeeldingen). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Bepaalt of dubbele streams in de PDF worden gekoppeld. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | Als deze eigenschap is ingesteld op waar, wordt de paginainhoud hergebruikt bij het optimaliseren van het document voor identieke pagina's. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Stelt in of het hergebruiken van paginainhoud in de PDF is toegestaan. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Soms bevat een document ongebruikte resource‑streams. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Stelt in of ongebruikte streams uit de PDF moeten worden verwijderd. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Een PDF‑document bevat soms de PDF‑objecten die niet door een ander object in het document worden gerefereerd. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Stelt in of ongebruikte objecten uit de PDF moeten worden verwijderd. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Stelt de standaardwaarden in voor de MaxResolution‑optie op 300 en de ImageQuality‑optie op 100.

Voor details en code‑voorbeelden, zie deze [page][] en de onderliggende pagina’s.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Schakelt optimalisatie van het uitvoer‑PDF‑bestand in voor weergave online met een webbrowser.

Voor een code‑voorbeeld, zie deze [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  als de uitvoer‑PDF is geoptimaliseerd voor online browsen,  false  anders.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Duidt of het uitvoer‑PDF moet worden geoptimaliseerd voor online browsen met een webbrowser.

Voor een code‑voorbeeld, zie deze [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| linearize | boolean | true  om de uitvoer‑PDF te optimaliseren voor online browsen,  false  anders. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Annotaties kunnen worden verwijderd wanneer ze overbodig zijn. Wanneer ze nodig zijn maar geen extra bewerking vereisen, kunnen ze worden geflatteerd. Dit zal de bestandsgrootte verkleinen.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  als annotaties worden verwijderd,  false  anders.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Bepaalt of overbodige annotaties uit de PDF worden verwijderd.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| removeAnnotations | boolean | true  om overbodige annotaties te verwijderen,  false  anders. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Als het PDF‑document AcroForms bevat, kunnen we proberen de bestandsgrootte te verkleinen door de formulier‑velden plat te maken.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  als formuliervelden worden verwijderd,  false  anders.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Bepaalt of formulier‑velden uit de PDF worden verwijderd.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| removeFormFields | boolean | true  om formuliervelden te verwijderen,  false  anders. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


Een PDF‑bestand bestaat uit Tekst, Afbeelding, Bijlage, Annotaties, Grafieken en andere objecten. Het kan voorkomen dat u een PDF moet converteren van RGB‑kleurruimte naar grijswaarden zodat het sneller afgedrukt kan worden. Ook wordt de bestandsgrootte verkleind wanneer het bestand naar grijswaarden wordt geconverteerd, maar hierdoor kan de kwaliteit van het document afnemen. Momenteel wordt deze functionaliteit ondersteund door de Pre‑Flight‑functie van Adobe Acrobat.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  als de PDF wordt geconverteerd naar grijswaarden,  false  anders.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Bepaalt of de PDF naar grijstinten wordt geconverteerd.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertToGrayScale | boolean | true  om de PDF naar grijswaarden te converteren,  false  anders. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Elke lettertype die wordt gebruikt om tekst op de pagina weer te geven, bevat een set glyphs voor de tekens. De PDF‑specificatie ondersteunt \"font subset\", d.w.z. een lettertype met alleen de gebruikte glyphs. Dit kan problemen veroorzaken wanneer tekst moet worden bijgewerkt (omdat de benodigde glyphs mogelijk ontbreken in het lettertype), maar voor een document dat niet wordt gewijzigd, maakt dit verkleining van de bestandsgrootte mogelijk.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  als lettertypen zijn gesubset,  false  anders.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Bepaalt of de lettertypen in de PDF worden onderverdeeld.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subsetFonts | boolean | true  om de lettertypen te subsetten,  false  anders. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Als het bron‑PDF‑bestand afbeeldingen bevat, overweeg dan de afbeeldingen te comprimeren en hun kwaliteit in te stellen. Om beeldcompressie in te schakelen, zet deze optie op true. Alle afbeeldingen in een document worden opnieuw gecomprimeerd. De compressie wordt gedefinieerd door de ImageQuality‑eigenschap, die de kwaliteitswaarde in procenten aangeeft. 100 % is ongewijzigde kwaliteit. Om de beeldkwaliteit te verlagen, zet de ImageQuality‑eigenschap op minder dan 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean - true als afbeeldingen zijn gecomprimeerd, false anders.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Bepaalt of de afbeeldingen in de PDF worden gecomprimeerd.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| compressImages | boolean | true om de afbeeldingen te comprimeren, false anders. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Als het bron‑PDF‑bestand afbeeldingen bevat, overweeg dan de afbeeldingen te comprimeren en hun kwaliteit in te stellen. Om beeldcompressie in te schakelen, zet de CompressImages‑optie op true. Alle afbeeldingen in een document worden opnieuw gecomprimeerd. De compressie wordt gedefinieerd door de ImageQuality‑eigenschap, die de kwaliteitswaarde in procenten aangeeft. 100 % is ongewijzigde kwaliteit. Om de beeldkwaliteit te verlagen, zet de CompressImages‑optie op true en de ImageQuality‑eigenschap op minder dan 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - de beeldkwaliteit (waarde tussen 1 en 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Stelt de afbeeldingskwaliteit in voor het comprimeren van de afbeeldingen in de PDF.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageQuality | int | de beeldkwaliteit (waarde tussen 1 en 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Kan worden gebruikt met de CompressImages‑optie om de afbeeldingen te verkleinen met een lagere resolutie. In dit geval moeten we CompressImage op true zetten, ResizeImages op true en MaxResolution op de juiste waarde.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean - true als afbeeldingen zijn verkleind, false anders.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Bepaalt of de afbeeldingen in de PDF worden verkleind.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resizeImages | boolean | true om de afbeeldingen te verkleinen, false anders. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Kan worden gebruikt met de CompressImages‑optie om de afbeeldingen te verkleinen met een lagere resolutie. In dit geval moeten we CompressImage op true zetten, ResizeImages op true en MaxResolution op de juiste waarde.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - de maximale resolutie voor de afbeeldingen.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Stelt de maximale resolutie in voor het verkleinen van de afbeeldingen in de PDF.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxResolution | int | de maximale resolutie voor de afbeeldingen. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimaliseer de randlijnen en lettertypen van Excel‑werkbladen voor een kleinere uitvoer‑bestandsgrootte.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean - true als spreadsheets zijn geoptimaliseerd, false anders.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Bepaalt of de werkbladen in de PDF worden geoptimaliseerd.

Voor een code‑voorbeeld, zie deze [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true om de spreadsheets te optimaliseren, false anders. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Verwijder privé‑informatie (pagina‑stuk‑info) indien ingesteld op waar.

***Note:** The default value is  false .*

**Returns:**
boolean - true als privé‑informatie wordt verwijderd, false anders.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Bepaalt of privé‑informatie uit de PDF wordt verwijderd.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| removePrivateInfo | boolean | true om privé‑informatie te verwijderen, false anders. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Als het document ingesloten lettertypen gebruikt, betekent dit dat alle lettertype‑gegevens in het document zijn opgenomen. Het voordeel is dat het document kan worden bekeken, ongeacht of het lettertype op de computer van de gebruiker is geïnstalleerd. Maar het insluiten van lettertypen maakt het document groter. De unembed fonts‑methode verwijdert alle ingesloten lettertypen. Dit verkleint de documentgrootte, maar het document kan onleesbaar worden als het juiste lettertype niet is geïnstalleerd.

***Note:** The default value is  false .*

**Returns:**
boolean - true als ingesloten lettertypen zijn verwijderd, false anders.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Bepaalt of de ingesloten lettertypen uit de PDF worden verwijderd.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| unembedFonts | boolean | true om de ingesloten lettertypen te verwijderen, false anders. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Soms bevat een document meerdere identieke resource‑streams (bijvoorbeeld afbeeldingen). Dit kan bijvoorbeeld gebeuren wanneer een document met zichzelf wordt samengevoegd. Het uitvoerdocument bevat twee onafhankelijke kopieën van dezelfde resource‑stream. We analyseren alle resource‑streams en vergelijken ze. Als streams gedupliceerd zijn, worden ze samengevoegd, zodat er slechts één kopie overblijft, referenties worden dienovereenkomstig aangepast en kopieën van het object worden verwijderd. Soms verkleint dit de documentgrootte.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  als duplicate streams zijn gekoppeld,  false  anders.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Bepaalt of dubbele streams in de PDF worden gekoppeld.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  om duplicate streams te koppelen,  false  anders. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Als deze eigenschap is ingesteld op waar, wordt de paginainhoud hergebruikt bij het optimaliseren van het document voor identieke pagina's.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  als paginainhoud wordt hergebruikt,  false  anders.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Stelt in of het hergebruiken van paginainhoud in de PDF is toegestaan.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| allowReusePageContent | boolean | true  om het hergebruiken van paginainhoud toe te staan,  false  anders. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Soms bevat een document ongebruikte resource‑streams. Deze streams zijn geen \u201cunused objects\u201d omdat ze worden verwezen vanuit het resource‑woordenboek van een pagina\u2019s. Dit kan gebeuren wanneer een afbeelding van de pagina is verwijderd maar niet uit de paginabronnen. Ook komt deze situatie vaak voor wanneer pagina's uit het document worden geëxtraheerd en documentpagina's \u201ccommon\u201d resources hebben, namelijk hetzelfde Resources‑object. Paginainhoud wordt geanalyseerd om te bepalen of een resource‑stream wordt gebruikt of niet. Ongebruikte streams worden verwijderd. Soms verkleint dit de documentgrootte.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  als ongebruikte streams worden verwijderd,  false  anders.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Stelt in of ongebruikte streams uit de PDF moeten worden verwijderd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  om ongebruikte streams te verwijderen,  false  anders. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Een PDF‑document bevat soms PDF‑objecten die niet vanuit een ander object in het document worden verwezen. Dit kan bijvoorbeeld gebeuren wanneer een pagina uit de document‑paginaire boom wordt verwijderd, maar het paginapunt zelf isn\u2019t verwijderd. Het verwijderen van deze objecten maakt het document niet ongeldig, maar verkleint het wel.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  als ongebruikte objecten worden verwijderd,  false  anders.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Stelt in of ongebruikte objecten uit de PDF moeten worden verwijderd.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  om ongebruikte objecten te verwijderen,  false  anders. |

