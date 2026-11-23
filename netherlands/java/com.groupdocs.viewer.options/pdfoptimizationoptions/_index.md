---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Gebruik deze klasse om PDF-optimalisatieopties op te geven die op het uitvoer‑PDF‑bestand moeten worden toegepast."
type: docs
weight: 21
url: /nl/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Gebruik deze klasse om PDF-optimalisatieopties op te geven die op het uitvoer‑PDF‑bestand moeten worden toegepast.


Deze optimalisatie-opties worden ondersteund voor alle invoerbestandsformaten die worden ondersteund voor export naar PDF.
Voor details en codevoorbeelden, zie deze [pagina](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) en de onderliggende pagina's.


Voorbeeldgebruik:

````

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
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Stelt de standaardwaarden van de MaxResolution-optie in op 300 en de ImageQuality-optie op 100. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Schakelt optimalisatie van het uitvoer‑PDF‑bestand in voor online bekijken met een webbrowser. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Stelt in of het uitvoer‑PDF moet worden geoptimaliseerd voor online browsen met een webbrowser. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | Annotaties kunnen worden verwijderd wanneer ze overbodig zijn. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Stelt in of overbodige annotaties uit de PDF moeten worden verwijderd. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | Als het PDF‑document AcroForms bevat, kunnen we proberen de bestandsgrootte te verkleinen door formulier‑velden plat te maken. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Stelt in of formulier‑velden uit de PDF moeten worden verwijderd. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF‑bestand bestaat uit Tekst, Afbeelding, Bijlage, Annotaties, Grafieken en andere objecten. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Stelt in of de PDF moet worden geconverteerd naar grijstinten. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | Elk lettertype dat wordt gebruikt om tekst op de pagina weer te geven, bevat een set glyphs voor lettertype‑tekens. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Stelt in of de lettertypen in de PDF moeten worden onderverdeeld. |
|
|  | [isCompressImages()](#isCompressImages--) | Als het bron‑PDF‑bestand afbeeldingen bevat, overweeg dan de afbeeldingen te comprimeren en hun kwaliteit in te stellen. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Stelt in of de afbeeldingen in de PDF moeten worden gecomprimeerd. |
|
|  | [getImageQuality()](#getImageQuality--) | Als het bron‑PDF‑bestand afbeeldingen bevat, overweeg dan de afbeeldingen te comprimeren en hun kwaliteit in te stellen. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | Stelt de afbeeldingskwaliteit in voor het comprimeren van de afbeeldingen in de PDF. |
|
|  | [isResizeImages()](#isResizeImages--) | Kan worden gebruikt met de CompressImages‑optie om de afbeeldingen te verkleinen tot een lagere resolutie. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Stelt in of de afbeeldingen in de PDF moeten worden verkleind. |
|
|  | [getMaxResolution()](#getMaxResolution--) | Kan worden gebruikt met de CompressImages‑optie om de afbeeldingen te verkleinen tot een lagere resolutie. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Stelt de maximale resolutie in voor het verkleinen van de afbeeldingen in de PDF. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimaliseer de randlijnen en lettertypen van Excel‑spreadsheets voor een kleinere uitvoerbestandsgrootte. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Stelt in of de spreadsheets in de PDF moeten worden geoptimaliseerd. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Verwijder privé‑informatie (pagina‑onderdeel‑info) indien ingesteld op true. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Stelt in of privé‑informatie uit de PDF moet worden verwijderd. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | Als het document ingesloten lettertypen gebruikt, betekent dit dat alle lettertype‑gegevens in het document zijn geplaatst. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Stelt in of de ingesloten lettertypen uit de PDF moeten worden uitgepakt. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Soms bevat een document verschillende identieke resource‑streams (bijvoorbeeld afbeeldingen). |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Stelt in of dubbele streams in de PDF moeten worden gekoppeld. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | Als deze eigenschap is ingesteld op true, wordt de paginainhoud hergebruikt bij het optimaliseren van het document voor identieke pagina's. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Stelt in of het hergebruiken van paginainhoud in de PDF is toegestaan. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Soms bevat een document ongebruikte resource‑streams. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Stelt in of ongebruikte streams uit de PDF moeten worden verwijderd. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Een PDF‑document bevat soms de PDF‑objecten die niet worden gerefereerd |
door enig ander object in het document.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Stelt in of ongebruikte objecten uit de PDF moeten worden verwijderd. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Stelt de standaardwaarden van de MaxResolution-optie in op 300 en de ImageQuality-optie op 100.


Voor details en codevoorbeelden, zie deze [pagina](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) en de onderliggende pagina's.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Schakelt optimalisatie van het uitvoer‑PDF‑bestand in voor online bekijken met een webbrowser.


Voor een code‑voorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Returns:**
boolean -  true  als de uitvoer‑PDF is geoptimaliseerd voor online browsen,  false  anders.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Stelt in of het uitvoer‑PDF moet worden geoptimaliseerd voor online browsen met een webbrowser.


Voor een code‑voorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | linearize | boolean | true  om de uitvoer‑PDF te optimaliseren voor online browsen,  false  anders. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Annotaties kunnen worden verwijderd wanneer ze overbodig zijn. Wanneer ze nodig zijn maar geen extra bewerking vereisen, kunnen ze worden geflatteerd. Dit zal de bestandsgrootte verkleinen.


***Note:** The default value is 
false
.*
Voor een code‑voorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Returns:**
boolean -  true  als annotaties zijn verwijderd,  false  anders.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Stelt in of overbodige annotaties uit de PDF moeten worden verwijderd.


***Note:** The default value is 
false
.*
Voor een code‑voorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  om onnodige annotaties te verwijderen,  false  anders. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Als het PDF‑document AcroForms bevat, kunnen we proberen de bestandsgrootte te verkleinen door formulier‑velden plat te maken.


***Note:** The default value is 
false
.*
Voor een codevoorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
boolean -  true  als formuliervelden zijn verwijderd,  false  anders.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Stelt in of formulier‑velden uit de PDF moeten worden verwijderd.


***Note:** The default value is 
false
.*
Voor een codevoorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | removeFormFields | boolean | true  om formuliervelden te verwijderen,  false  anders. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF‑bestand bestaat uit Tekst, Afbeelding, Bijlage, Annotaties, Grafieken en andere objecten.
U kunt een vereiste tegenkomen om een PDF van RGB-kleurruimte naar grijswaarden te converteren, zodat het sneller gaat bij het afdrukken van die PDF‑bestanden.
Wanneer het bestand naar grijswaarden wordt geconverteerd, wordt de bestandsgrootte ook verkleind, maar door deze wijziging kan de kwaliteit van het document afnemen.
Momenteel wordt deze functie ondersteund door de Pre‑Flight‑functie van Adobe Acrobat.


***Note:** The default value is 
false
.*
Voor een codevoorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
boolean -  true  als de PDF naar grijswaarden is geconverteerd,  false  anders.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Stelt in of de PDF moet worden geconverteerd naar grijstinten.


***Note:** The default value is 
false
.*
Voor een codevoorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  om de PDF naar grijswaarden te converteren,  false  anders. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Elk lettertype dat wordt gebruikt om tekst op de pagina weer te geven, bevat een set glyphs voor lettertype‑tekens.
PDF-specificatie ondersteunt "font subset", d.w.z. een lettertype met alleen die glyphs die worden gebruikt.
Dit kan problemen veroorzaken wanneer tekst moet worden bijgewerkt (aangezien de benodigde glyphs waarschijnlijk ontbreken in het lettertype), maar voor een document dat niet gewijzigd zal worden, maakt dit verkleining mogelijk.


***Note:** The default value is 
false
.*
Als het bestand ingesloten lettertypen gebruikt, bevat het alle lettertype‑gegevens. GroupDocs.Viewer kan ingesloten lettertypen subsetten om de bestandsgrootte te verkleinen. Voor een codevoorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
boolean -  true  als lettertypen zijn gesubset,  false  anders.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Stelt in of de lettertypen in de PDF moeten worden onderverdeeld.


***Note:** The default value is 
false
.*
Als het bestand ingesloten lettertypen gebruikt, bevat het alle lettertype‑gegevens. GroupDocs.Viewer kan ingesloten lettertypen subsetten om de bestandsgrootte te verkleinen. Voor een codevoorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | subsetFonts | boolean | true  om de lettertypen te subsetten,  false  anders. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Als het bron‑PDF‑bestand afbeeldingen bevat, overweeg dan de afbeeldingen te comprimeren en hun kwaliteit in te stellen.
Om beeldcompressie in te schakelen, zet deze optie op true. Alle afbeeldingen in een document worden opnieuw gecomprimeerd.
De compressie wordt bepaald door de ImageQuality‑eigenschap, die de kwaliteitswaarde in procenten aangeeft.
100% is ongewijzigde kwaliteit. Om de beeldkwaliteit te verlagen, stel de ImageQuality‑eigenschap in op minder dan 100.


***Note:** The default value is 
false
.*
Gebruik deze optie om andere compressie‑opties toe te staan: #setImageQuality(int).setImageQuality(int) en . Voor een codevoorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
boolean -  true  als afbeeldingen zijn gecomprimeerd,  false  anders.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Stelt in of de afbeeldingen in de PDF moeten worden gecomprimeerd.


***Note:** The default value is 
false
.*
Gebruik deze optie om andere compressie‑opties toe te staan: #setImageQuality(int).setImageQuality(int) en . Voor een codevoorbeeld, zie deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | compressImages | boolean | true  om de afbeeldingen te comprimeren,  false  anders. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Als het bron‑PDF‑bestand afbeeldingen bevat, overweeg dan de afbeeldingen te comprimeren en hun kwaliteit in te stellen. Om afbeeldingscompressie in te schakelen, stel de optie CompressImages in op true. Alle afbeeldingen in een document worden opnieuw gecomprimeerd. De compressie wordt gedefinieerd door de eigenschap ImageQuality, die de kwaliteitswaarde in procent aangeeft. 100 % is ongewijzigde kwaliteit. Om de beeldkwaliteit te verlagen, stel de optie CompressImages in op true en de eigenschap ImageQuality op minder dan 100.

<br />


***Note:** The default value is 
100
.*
Om de beeldkwaliteit te wijzigen, stel eerst de eigenschap #setCompressImages(boolean).setCompressImages(boolean) in op true. Zie voor een codevoorbeeld deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
int - de beeldkwaliteit (waarde tussen 1 en 100).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Stelt de afbeeldingskwaliteit in voor het comprimeren van de afbeeldingen in de PDF.


***Note:** The default value is 
100
.*
Om de beeldkwaliteit te wijzigen, stel eerst de eigenschap #setCompressImages(boolean).setCompressImages(boolean) in op true. Zie voor een codevoorbeeld deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | imageQuality | int | de beeldkwaliteit (waarde tussen 1 en 100). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Kan worden gebruikt met de CompressImages‑optie om de afbeeldingen te verkleinen tot een lagere resolutie.
In dit geval moeten we CompressImage op true zetten, ResizeImages op true en MaxResolution op de juiste waarde.


***Note:** The default value is 
false
.*
Om deze optie toe te staan, stel de eigenschap in op true. Deze optie maakt het instellen van de eigenschap mogelijk. Zie voor een codevoorbeeld deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
boolean -  true  als afbeeldingen worden aangepast,  false  anders.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Stelt in of de afbeeldingen in de PDF moeten worden verkleind.


***Note:** The default value is 
false
.*
Om deze optie toe te staan, stel de eigenschap in op true. Deze optie maakt het instellen van de eigenschap mogelijk. Zie voor een codevoorbeeld deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | resizeImages | boolean | true  om de afbeeldingen aan te passen,  false  anders. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Kan worden gebruikt met de optie CompressImages om de afbeeldingen met een lagere resolutie aan te passen. In dit geval moeten we CompressImage op true zetten, ResizeImages op true en MaxResolution op de juiste waarde.


***Note:** The default value is 
300
.*
Om deze optie toe te staan, stel de eigenschappen #setCompressImages(boolean).setCompressImages(boolean) en #setMaxResolution(int).setMaxResolution(int) in op true.
Zie voor een codevoorbeeld deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
int - de maximale resolutie voor de afbeeldingen.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Stelt de maximale resolutie in voor het verkleinen van de afbeeldingen in de PDF.


***Note:** The default value is 
300
.*
Om deze optie toe te staan, stel de eigenschappen #setCompressImages(boolean).setCompressImages(boolean) en #setMaxResolution(int).setMaxResolution(int) in op true.
Zie voor een codevoorbeeld deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | maxResolution | int | de maximale resolutie voor de afbeeldingen. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimaliseer de randlijnen en lettertypen van Excel‑spreadsheets voor een kleinere uitvoerbestandsgrootte.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
Zie voor een codevoorbeeld deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Returns:**
boolean -  true  als spreadsheets zijn geoptimaliseerd,  false  anders.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Stelt in of de spreadsheets in de PDF moeten worden geoptimaliseerd.


Zie voor een codevoorbeeld deze [documentatie](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  om de spreadsheets te optimaliseren,  false  anders. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Verwijder privé‑informatie (pagina‑onderdeel‑info) indien ingesteld op true.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  als privé‑informatie wordt verwijderd,  false  anders.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Stelt in of privé‑informatie uit de PDF moet worden verwijderd.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  om privé‑informatie te verwijderen,  false  anders. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Als het document ingesloten lettertypen gebruikt, betekent dit dat alle lettertype‑gegevens in het document zijn geplaatst.
Het voordeel is dat het document bekeken kan worden, ongeacht of het lettertype op de computer van de gebruiker\\u2019s is geïnstalleerd of niet. Maar het insluiten van lettertypen maakt het document groter.
De methode om lettertypen te de‑embedden verwijdert alle ingesloten lettertypen. Dit verkleint de documentgrootte, maar het document kan onleesbaar worden als het juiste lettertype niet is geïnstalleerd.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  als ingesloten lettertypen zijn gedebed,  false  anders.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Stelt in of de ingesloten lettertypen uit de PDF moeten worden uitgepakt.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | unembedFonts | boolean | true  om de ingesloten lettertypen te de‑embedden,  false  anders. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Soms bevat een document verschillende identieke resource‑streams (bijvoorbeeld afbeeldingen).
Dit kan bijvoorbeeld gebeuren wanneer een document met zichzelf wordt samengevoegd.
Het uitvoerdocument bevat twee onafhankelijke kopieën van dezelfde resource‑stroom.
We analyseren alle resource‑stromen en vergelijken ze. Als stromingen gedupliceerd zijn, worden ze samengevoegd, dat wil zeggen, er blijft slechts één kopie over, verwijzingen worden dienovereenkomstig aangepast en kopieën van het object worden verwijderd.
Soms verkleint dit de documentgrootte.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  als gedupliceerde stromingen zijn gekoppeld,  false  anders.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Stelt in of dubbele streams in de PDF moeten worden gekoppeld.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  om gedupliceerde stromingen te koppelen,  false  anders. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Als deze eigenschap is ingesteld op true, wordt de paginainhoud hergebruikt bij het optimaliseren van het document voor identieke pagina's.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  als paginainhoud wordt hergebruikt,  false  anders.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Stelt in of het hergebruiken van paginainhoud in de PDF is toegestaan.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  om het hergebruiken van paginainhoud toe te staan,  false  anders. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Soms bevat een document ongebruikte resource‑streams.
Deze stromingen zijn geen \\u201congebruikte objecten\\u201d omdat ze worden verwezen vanuit een pagina\\u2019s resource‑woordenboek.
Dit kan gebeuren in gevallen waarin een afbeelding van de pagina is verwijderd, maar niet uit de paginabronnen.
Bovendien komt deze situatie vaak voor wanneer pagina's uit het document worden geëxtraheerd en documentpagina's \\u201cgemeenschappelijke\\u201d bronnen hebben,
dat wil zeggen, hetzelfde Resources‑object. Paginainhoud wordt geanalyseerd om te bepalen of een resource‑stroom
wordt gebruikt of niet. Ongebruikte stromingen worden verwijderd. Soms verkleint dit de documentgrootte.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  als ongebruikte stromingen worden verwijderd,  false  anders.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Stelt in of ongebruikte streams uit de PDF moeten worden verwijderd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  om ongebruikte stromingen te verwijderen,  false  anders. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Een PDF‑document bevat soms de PDF‑objecten die niet worden gerefereerd
van elk ander object in het document. Dit kan bijvoorbeeld gebeuren,
wanneer een pagina wordt verwijderd uit de documentpaginaboom, maar het pagina‑object zelf isn\\u2019t verwijderd.
Het verwijderen van deze objecten maakt het document niet ongeldig, maar verkleint het.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  als ongebruikte objecten worden verwijderd,  false  anders.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Stelt in of ongebruikte objecten uit de PDF moeten worden verwijderd.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  om ongebruikte objecten te verwijderen,  false  anders. |
|

