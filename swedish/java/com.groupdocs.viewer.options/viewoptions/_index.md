---
title: "ViewOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Innehåller renderingsalternativen."
type: docs
weight: 35
url: /sv/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Innehåller renderingsalternativen.


Klassen ViewOptions ärver klassen BaseViewOptions och fungerar som en basklass för renderingsalternativ
i GroupDocs.Viewer-komponenten. Den kapslar in vanliga inställningar och parametrar som kan användas
för att rendera olika typer av dokument till olika format.


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Hämtar textvattenstämpeln som tillämpas på varje sida. |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Ställer in textvattenstämpeln som ska tillämpas på varje sida. |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Tillämpar en medursrotation på den angivna sidan. |
|
|  | [getPageRotations()](#getPageRotations--) | Hämtar sidrotationerna. |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | För att förhindra att skapa instansen bara för att kontrollera att den är tom |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Hämtar textvattenstämpeln som tillämpas på varje sida.


Om både #setWatermark(Watermark).setWatermark(Watermark) och #getPageRotations().getPageRotations() är angivna,
kommer vattenstämpeln att tillämpas på de roterade sidorna.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Ställer in textvattenstämpeln som ska tillämpas på varje sida.


Om båda
ViewOptions.Watermark
och #getPageRotations().getPageRotations() är angivna,
kommer vattenstämpeln att tillämpas på de roterade sidorna.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Textvattenstämpeln som ska sättas. |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Tillämpar en medursrotation på den angivna sidan.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageNumber | int | Sidnumret måste vara strikt större än 0. |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Rotationsvärdet. |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Hämtar sidrotationerna.


Om både [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) och
getPageRotations()
är specificerade,
kommer vattenstämpeln att tillämpas på de roterade sidorna.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - en karta som innehåller sidnumren som nycklar och deras motsvarande rotationer som värden.

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


För att förhindra att skapa instansen bara för att kontrollera att den är tom


**Returns:**
boolean
