---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van presentaties."
type: docs
weight: 26
url: /nl/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Biedt opties voor het renderen van presentaties.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Schakelt een nieuwe HTML-renderingsmodus in voor Presentatiedocumenten. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Schakelt een nieuwe HTML-renderingsmodus in voor Presentatiedocumenten. |
| [getResolution()](#getResolution--) | Resolutie voor afbeeldingen binnen de presentatie (alleen voor HTML/PDF-rendering). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Resolutie voor afbeeldingen binnen de presentatie (alleen voor HTML/PDF-rendering). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Schakelt een nieuwe HTML-renderingsmodus in voor Presentatiedocumenten.

In deze modus worden de Presentatie‑bestanden gerenderd naar pure HTML/CSS‑markup, zonder SVG‑afbeeldingen. Standaard is deze functie uitgeschakeld (false). De bestaande SVG‑gebaseerde HTML‑renderer wordt gebruikt als deze optie niet is ingeschakeld.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Schakelt een nieuwe HTML-renderingsmodus in voor Presentatiedocumenten.

In deze modus worden de Presentatie‑bestanden gerenderd naar pure HTML/CSS‑markup, zonder SVG‑afbeeldingen. Standaard is deze functie uitgeschakeld (false). De bestaande SVG‑gebaseerde HTML‑renderer wordt gebruikt als deze optie niet is ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Resolutie voor afbeeldingen binnen de presentatie (alleen voor HTML/PDF-rendering).

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Resolutie voor afbeeldingen binnen de presentatie (alleen voor HTML/PDF-rendering).

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

