---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties voor het renderen van tekstverwerkingsdocumenten."
type: docs
weight: 38
url: /nl/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Biedt opties voor het renderen van tekstverwerkingsdocumenten.


De WordProcessingOptions-klasse biedt opties voor het renderen van tekstverwerkingsdocumenten
in de GroupDocs.Viewer-component. Het omvat instellingen en parameters die kunnen worden gebruikt
om het renderproces en het uitvoerformaat voor tekstverwerkingsbestanden te beheersen.
Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


Voorbeeldgebruik:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Initialiseert een nieuw exemplaar van de |
WordProcessingOptions
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Haalt de paginagrootte op voor het renderen van HTM- en HTML-bestanden. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Stelt de paginagrootte in voor het renderen van HTM- en HTML-bestanden. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Geeft aan of het renderen van tracked changes (revisies) is ingeschakeld. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Stelt in of het renderen van tracked changes (revisies) is ingeschakeld. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Haalt de linkermarge van de pagina op voor HTML-rendering. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Stelt de linkermarge van de pagina in voor HTML-rendering. |
|
|  | [getRightMargin()](#getRightMargin--) | Haalt de rechtermarge van de pagina op voor HTML-rendering. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Stelt de rechter paginamarge in voor HTML-weergave. |
|
|  | [getTopMargin()](#getTopMargin--) | Haalt de bovenste paginamarge op voor HTML-weergave. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Stelt de bovenste paginamarge in voor HTML-weergave. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Onderste paginamarge (alleen voor HTML-weergave) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Stelt de onderste paginamarge in voor HTML-weergave. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Deze optie schakelt kerning en andere OpenType-functies in bij het renderen van Arabische, Hebreeuwse, Indiase, Latijnse of Cyrillische scripts. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Deze optie schakelt kerning en andere OpenType-functies in bij het renderen van Arabische, Hebreeuwse, Indiase, Latijnse of Cyrillische scripts. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Geeft aan of de navigatie van de inhoudsopgave moet worden uitgeschakeld bij het renderen naar HTML of PDF. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Stelt in of de navigatie van de inhoudsopgave moet worden uitgeschakeld bij het renderen naar HTML of PDF. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Haalt een waarde op die bepaalt of velden van bepaalde typen moeten worden bijgewerkt voordat het invoer‑WordProcessing‑document wordt opgeslagen naar de HTML-, PDF-, PNG- of JPEG-uitvoerformaten. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Stelt een waarde in die bepaalt of velden van bepaalde typen moeten worden bijgewerkt voordat het invoer‑WordProcessing‑document wordt opgeslagen naar de HTML-, PDF-, PNG- of JPEG-uitvoerformaten. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Haalt de horizontale resolutie op voor gegenereerde afbeeldingen in dots per inch. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Stelt de horizontale resolutie in voor gegenereerde afbeeldingen in dots per inch. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Haalt de verticale resolutie op voor gegenereerde afbeeldingen in dots per inch. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Stelt de verticale resolutie in voor gegenereerde afbeeldingen in dots per inch. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Staat toe om geforceerd paginanummering toe te passen op het geladen WordProcessing‑document. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Staat toe om geforceerd paginanummering toe te passen op het geladen WordProcessing‑document. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Controleer of de opties zijn gewijzigd. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Initialiseert een nieuw exemplaar van de
WordProcessingOptions
klasse.
Bevat opties voor het renderen van tekstverwerkingsdocumenten. Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Haalt de paginagrootte op voor het renderen van HTM- en HTML-bestanden.


Bij gebruik van de standaard paginagrootte past sommige inhoud mogelijk niet in het paginakader.
Om de inhoud passend te maken, kun je een grotere paginagrootte instellen, zoals A3, met behulp van [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Stelt de paginagrootte in voor het renderen van HTM- en HTML-bestanden.


Bij gebruik van de standaard paginagrootte past sommige inhoud mogelijk niet in het paginakader.
Om de inhoud passend te maken, kun je een grotere paginagrootte instellen, zoals A3, met behulp van [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | De grootte van de uitvoerpagina. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Geeft aan of het renderen van tracked changes (revisies) is ingeschakeld.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
boolean -  true  als renderen van tracked changes is ingeschakeld,  false  anders.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Stelt in of het renderen van tracked changes (revisies) is ingeschakeld.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | boolean | true  om renderen van tracked changes in te schakelen,  false  om het uit te schakelen. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Haalt de linkermarge van de pagina op voor HTML-rendering.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - de waarde van de linker paginamarge.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Stelt de linkermarge van de pagina in voor HTML-rendering.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | De in te stellen waarde van de linker paginamarge. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Haalt de rechtermarge van de pagina op voor HTML-rendering.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - de waarde van de rechter paginamarge.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Stelt de rechter paginamarge in voor HTML-weergave.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | De te instellen waarde van de rechter paginamarge. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Haalt de bovenste paginamarge op voor HTML-weergave.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - de bovenste paginamarge.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Stelt de bovenste paginamarge in voor HTML-weergave.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | topMargin | java.lang.Double | De te instellen bovenste paginamarge. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Onderste paginamarge (alleen voor HTML-weergave)
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - de onderste paginamarge.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Stelt de onderste paginamarge in voor HTML-weergave.
Zie voor details de [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | De te instellen onderste paginamarge. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Deze optie schakelt kerning en andere OpenType-functies in bij het renderen van Arabische, Hebreeuwse, Indiase, Latijnse of Cyrillische scripts.


**Returns:**
boolean - True als OpenType-functies zijn ingeschakeld, anders false.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Deze optie schakelt kerning en andere OpenType-functies in bij het renderen van Arabische, Hebreeuwse, Indiase, Latijnse of Cyrillische scripts.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | True om OpenType-functies in te schakelen, anders false. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Geeft aan of navigatie in de inhoudsopgave moet worden uitgeschakeld bij het renderen naar HTML of PDF. Wanneer deze optie op true is ingesteld, worden bij HTML-rendering de relatieve links uit de inhoudsopgave vervangen door span-tags, waardoor functionaliteit wordt verwijderd maar de visuele weergave behouden blijft. Bij PDF-rendering wordt de inhoudsopgave als platte tekst zonder links weergegeven.


**Returns:**
boolean - True als navigatie in de inhoudsopgave is uitgeschakeld; anders false.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Stelt in of navigatie in de inhoudsopgave moet worden uitgeschakeld bij het renderen naar HTML of PDF. Wanneer deze optie op true is ingesteld, worden bij HTML-rendering de relatieve links uit de inhoudsopgave vervangen door span-tags, waardoor functionaliteit wordt verwijderd maar de visuele weergave behouden blijft. Bij PDF-rendering wordt de inhoudsopgave als platte tekst zonder links weergegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | Geeft aan of navigatie in de inhoudsopgave moet worden uitgeschakeld. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Haalt een waarde op die bepaalt of velden van bepaalde typen moeten worden bijgewerkt voordat het invoer‑WordProcessing‑document wordt opgeslagen naar de HTML-, PDF-, PNG- of JPEG‑uitvoerformaten. Standaardwaarde voor deze eigenschap is true \\u2014 velden worden bijgewerkt vóór het opslaan.


Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Stelt een waarde in die bepaalt of velden van bepaalde typen moeten worden bijgewerkt voordat het invoer‑WordProcessing‑document wordt opgeslagen naar de HTML-, PDF-, PNG- of JPEG‑uitvoerformaten. Standaardwaarde voor deze eigenschap is true \\u2014 velden worden bijgewerkt vóór het opslaan.


Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Haalt de horizontale resolutie op voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van WordProcessing‑documenten naar PNG‑ of JPEG‑formaten.


Standaardwaarde is 96 DPI. Minimum mogelijke waarde - 72 DPI, maximum mogelijke waarde - 600 DPI.
Als de door de gebruiker opgegeven waarde buiten deze limieten valt, wordt de minimum- of maximumwaarde toegepast.


**Returns:**
int - de horizontale resolutie in DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Stelt de horizontale resolutie in voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van WordProcessing‑documenten naar PNG‑ of JPEG‑formaten.


Standaardwaarde is 96 DPI. Minimum mogelijke waarde - 72 DPI, maximum mogelijke waarde - 600 DPI.
Als de door de gebruiker opgegeven waarde buiten deze limieten valt, wordt de minimum- of maximumwaarde toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | horizontalResolution | int | de horizontale resolutie in DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Haalt de verticale resolutie op voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van WordProcessing‑documenten naar PNG‑ of JPEG‑formaten.


Standaardwaarde is 96 DPI. Minimum mogelijke waarde - 72 DPI, maximum mogelijke waarde - 600 DPI.
Als de door de gebruiker opgegeven waarde buiten deze limieten valt, wordt de minimum- of maximumwaarde toegepast.


**Returns:**
int - de verticale resolutie in DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Stelt de verticale resolutie in voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van WordProcessing‑documenten naar PNG‑ of JPEG‑formaten.


Standaardwaarde is 96 DPI. Minimum mogelijke waarde - 72 DPI, maximum mogelijke waarde - 600 DPI.
Als de door de gebruiker opgegeven waarde buiten deze limieten valt, wordt de minimum- of maximumwaarde toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | verticalResolution | int | de verticale resolutie in DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Staat toe om paginanummering geforceerd toe te passen op het geladen WordProcessing‑document. Standaard is [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 document blijft ongewijzigd.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Staat toe om paginanummering geforceerd toe te passen op het geladen WordProcessing‑document. Standaard is [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 document blijft ongewijzigd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | de locatie van het paginanummer. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Controleer of de opties zijn gewijzigd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | o | java.lang.Object | Het object om op gelijkheid te vergelijken. |
|

**Returns:**
boolean -  true  als de opties gelijk zijn aan het opgegeven object,  false  anders.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Berekent de hashcode-waarde voor dit object. De hashcode is gebaseerd op
de interne staat van het object en wordt gebruikt in hash-gebaseerde datastructuren
zoals hash‑maps en hash‑sets.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - de hashcode-waarde voor dit object.

