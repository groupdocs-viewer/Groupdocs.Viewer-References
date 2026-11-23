---
title: "ViewOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Enthält die Rendering‑Optionen."
type: docs
weight: 35
url: /de/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Enthält die Rendering‑Optionen.


Die ViewOptions-Klasse erweitert die BaseViewOptions-Klasse und dient als Basisklasse für Rendering-Optionen
im GroupDocs.Viewer‑Komponente. Sie kapselt gängige Einstellungen und Parameter, die verwendet werden können
zum Rendern verschiedener Dokumenttypen in unterschiedliche Formate.


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Liest das auf jeder Seite angewendete Textwasserzeichen aus. |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Legt das auf jeder Seite anzuwendende Textwasserzeichen fest. |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Wendet eine Drehung im Uhrzeigersinn auf die angegebene Seite an. |
|
|  | [getPageRotations()](#getPageRotations--) | Ruft die Seitenrotationen ab. |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Um das Erstellen der Instanz nur zum Prüfen, ob sie leer ist, zu vermeiden |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Liest das auf jeder Seite angewendete Textwasserzeichen aus.


Falls sowohl #setWatermark(Watermark).setWatermark(Watermark) als auch #getPageRotations().getPageRotations() angegeben sind,
wird das Wasserzeichen auf die gedrehten Seiten angewendet.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Legt das auf jeder Seite anzuwendende Textwasserzeichen fest.


Falls beide
ViewOptions.Watermark
und #getPageRotations().getPageRotations() angegeben sind,
wird das Wasserzeichen auf die gedrehten Seiten angewendet.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Das zu setzende Textwasserzeichen. |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Wendet eine Drehung im Uhrzeigersinn auf die angegebene Seite an.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageNumber | int | Die Seitenzahl muss strikt größer als 0 sein. |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Der Rotationswert. |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Ruft die Seitenrotationen ab.


Falls sowohl [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) als auch
getPageRotations()
angegeben sind,
wird das Wasserzeichen auf die gedrehten Seiten angewendet.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> – eine Map, die die Seitenzahlen als Schlüssel und die jeweiligen Rotationen als Werte enthält.

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Um das Erstellen der Instanz nur zum Prüfen, ob sie leer ist, zu vermeiden


**Returns:**
boolesch
