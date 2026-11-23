---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt opties voor het renderen van presentaties."
type: docs
weight: 26
url: /nl/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Biedt opties voor het renderen van presentaties.


Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Schakelt een nieuwe HTML-rendermodus in voor Presentatiedocumenten. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Schakelt een nieuwe HTML-rendermodus in voor Presentatiedocumenten. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Schakelt het renderen van tijdelijke aanduidingen in de kop- en voettekst van een dia in. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Schakelt het renderen van tijdelijke aanduidingen in de kop- en voettekst van een dia in. |
|
|  | [getResolution()](#getResolution--) | Resolutie voor afbeeldingen binnen een presentatie (alleen voor HTML/PDF-rendering). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Resolutie voor afbeeldingen binnen een presentatie (alleen voor HTML/PDF-rendering). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Schakelt een nieuwe HTML-rendermodus in voor Presentatiedocumenten.


In deze modus worden de Presentatiebestanden gerenderd naar pure HTML/CSS-markup, zonder SVG-afbeeldingen.
Standaard is deze functie uitgeschakeld (false). De bestaande SVG-gebaseerde HTML-renderer wordt gebruikt als deze optie niet is ingeschakeld.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Schakelt een nieuwe HTML-rendermodus in voor Presentatiedocumenten.


In deze modus worden de Presentatiebestanden gerenderd naar pure HTML/CSS-markup, zonder SVG-afbeeldingen.
Standaard is deze functie uitgeschakeld (false). De bestaande SVG-gebaseerde HTML-renderer wordt gebruikt als deze optie niet is ingeschakeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Schakelt het renderen van tijdelijke aanduidingen in de kop- en voettekst van een dia in. Standaard uitgeschakeld (false). Deze optie is van toepassing op alle 4 rendermodi van presentaties: HTML, PDF, PNG en JPEG. Niet van toepassing bij het renderen van een presentatie naar pure HTML/CSS-markup met .


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Schakelt het renderen van tijdelijke aanduidingen in de kop- en voettekst van een dia in. Standaard uitgeschakeld (false). Deze optie is van toepassing op alle 4 rendermodi van presentaties: HTML, PDF, PNG en JPEG. Niet van toepassing bij het renderen van een presentatie naar pure HTML/CSS-markup met .


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Resolutie voor afbeeldingen binnen een presentatie (alleen voor HTML/PDF-rendering).


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Resolutie voor afbeeldingen binnen een presentatie (alleen voor HTML/PDF-rendering).


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resolutie | com.groupdocs.viewer.options.Resolution |  |

