---
title: "ViewOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Enthält die Rendering‑Optionen."
type: docs
weight: 35
url: /de/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Enthält die Rendering‑Optionen.

Die Klasse ViewOptions erweitert die Klasse BaseViewOptions und dient als Basisklasse für Rendering-Optionen in der GroupDocs.Viewer-Komponente. Sie fasst gemeinsame Einstellungen und Parameter zusammen, die zum Rendern verschiedener Dokumenttypen in unterschiedliche Formate verwendet werden können.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWatermark()](#getWatermark--) | Liefert das auf jeder Seite angewendete Textwasserzeichen. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Setzt das Textwasserzeichen, das auf jeder Seite angewendet werden soll. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Wendet eine Drehung im Uhrzeigersinn auf die angegebene Seite an. |
| [getPageRotations()](#getPageRotations--) | Ruft die Seitendrehungen ab. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Um das Erstellen der Instanz nur zum Prüfen, ob sie leer ist, zu verhindern |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Liefert das auf jeder Seite angewendete Textwasserzeichen.

Falls sowohl \#setWatermark(Watermark).setWatermark(Watermark) als auch \#getPageRotations().getPageRotations() angegeben sind, wird das Wasserzeichen auf die rotierten Seiten angewendet. Weitere Details finden Sie in der [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Setzt das Textwasserzeichen, das auf jeder Seite angewendet werden soll.

Falls sowohl  ViewOptions.Watermark  als auch \#getPageRotations().getPageRotations() angegeben sind, wird das Wasserzeichen auf die rotierten Seiten angewendet. Weitere Details finden Sie in der [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Das Textwasserzeichen, das festgelegt werden soll. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Wendet eine Drehung im Uhrzeigersinn auf die angegebene Seite an.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | int | Die Seitenzahl muss strikt größer als 0 sein. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Der Rotationswert. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Ruft die Seitendrehungen ab.

Wenn sowohl [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) als auch  getPageRotations()  angegeben sind, wird das Wasserzeichen auf die gedrehten Seiten angewendet. Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - eine Map, die die Seitenzahlen als Schlüssel und die entsprechenden Rotationen als Werte enthält.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Um das Erstellen der Instanz nur zum Prüfen, ob sie leer ist, zu verhindern

**Returns:**
boolean
