---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av presentationer."
type: docs
weight: 26
url: /sv/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Tillhandahåller alternativ för rendering av presentationer.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Aktiverar ett nytt HTML-renderingsläge för Presentation-dokument. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Aktiverar ett nytt HTML-renderingsläge för Presentation-dokument. |
| [getResolution()](#getResolution--) | Upplösning för bilder i presentationen (endast för HTML/PDF-rendering). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Upplösning för bilder i presentationen (endast för HTML/PDF-rendering). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Aktiverar ett nytt HTML-renderingsläge för Presentation-dokument.

I detta läge renderas Presentation-filerna till ren HTML/CSS-markup, utan SVG-bilder. Som standard är den här funktionen inaktiverad (false). Befintlig SVG-baserad HTML-renderare används om detta alternativ inte är aktiverat.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Aktiverar ett nytt HTML-renderingsläge för Presentation-dokument.

I detta läge renderas Presentation-filerna till ren HTML/CSS-markup, utan SVG-bilder. Som standard är den här funktionen inaktiverad (false). Befintlig SVG-baserad HTML-renderare används om detta alternativ inte är aktiverat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Upplösning för bilder i presentationen (endast för HTML/PDF-rendering).

För kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Upplösning för bilder i presentationen (endast för HTML/PDF-rendering).

För kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

