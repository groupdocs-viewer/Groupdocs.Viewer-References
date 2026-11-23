---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för rendering av presentationer."
type: docs
weight: 26
url: /sv/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Tillhandahåller alternativ för rendering av presentationer.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Aktiverar ett nytt HTML-renderingsläge för Presentation-dokument. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Aktiverar ett nytt HTML-renderingsläge för Presentation-dokument. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Aktiverar rendering av platshållare i sidhuvud och sidfot på en bild. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Aktiverar rendering av platshållare i sidhuvud och sidfot på en bild. |
|
|  | [getResolution()](#getResolution--) | Upplösning för bilder i presentationen (endast för rendering till HTML/PDF). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Upplösning för bilder i presentationen (endast för rendering till HTML/PDF). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Aktiverar ett nytt HTML-renderingsläge för Presentation-dokument.


I detta läge renderas Presentation-filerna till ren HTML/CSS-markup, utan SVG-bilder.
Som standard är denna funktion inaktiverad (false). Befintlig SVG-baserad HTML-renderare används om detta alternativ inte är aktiverat.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Aktiverar ett nytt HTML-renderingsläge för Presentation-dokument.


I detta läge renderas Presentation-filerna till ren HTML/CSS-markup, utan SVG-bilder.
Som standard är denna funktion inaktiverad (false). Befintlig SVG-baserad HTML-renderare används om detta alternativ inte är aktiverat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Aktiverar rendering av platshållare i rubrik och sidfot på en bild. Inaktiverad som standard (false). Detta alternativ gäller för alla 4 renderingslägen för presentationer: HTML, PDF, PNG och JPEG. Är inte tillämplig när presentation renderas till ren HTML/CSS markup med .


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Aktiverar rendering av platshållare i rubrik och sidfot på en bild. Inaktiverad som standard (false). Detta alternativ gäller för alla 4 renderingslägen för presentationer: HTML, PDF, PNG och JPEG. Är inte tillämplig när presentation renderas till ren HTML/CSS markup med .


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Upplösning för bilder i presentationen (endast för rendering till HTML/PDF).


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Upplösning för bilder i presentationen (endast för rendering till HTML/PDF).


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

