---
title: "ViewOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Bevat de renderopties."
type: docs
weight: 35
url: /nl/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Bevat de renderopties.

De ViewOptions‑klasse breidt de BaseViewOptions‑klasse uit en dient als basis‑klasse voor renderopties in de GroupDocs.Viewer‑component. Het omvat algemene instellingen en parameters die kunnen worden gebruikt voor het renderen van verschillende soorten documenten naar verschillende formaten.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWatermark()](#getWatermark--) | Haalt het tekstwatermerk op dat op elke pagina wordt toegepast. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Stelt het tekstwatermerk in dat op elke pagina moet worden toegepast. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Past een klokwijzerrotatie toe op de opgegeven pagina. |
| [getPageRotations()](#getPageRotations--) | Haalt de paginarotaties op. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Om te voorkomen dat de instantie wordt gemaakt alleen om te controleren of deze leeg is |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Haalt het tekstwatermerk op dat op elke pagina wordt toegepast.

In het geval dat zowel \#setWatermark(Watermark).setWatermark(Watermark) als \#getPageRotations().getPageRotations() zijn gespecificeerd, wordt het watermerk toegepast op de geroteerde pagina's. Zie voor details de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Stelt het tekstwatermerk in dat op elke pagina moet worden toegepast.

In het geval dat zowel  ViewOptions.Watermark  als \#getPageRotations().getPageRotations() zijn gespecificeerd, wordt het watermerk toegepast op de geroteerde pagina's. Zie voor details de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | De tekstwatermark die moet worden ingesteld. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Past een klokwijzerrotatie toe op de opgegeven pagina.

Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumber | int | Het paginanummer moet strikt groter zijn dan 0. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | De rotatiewaarde. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Haalt de paginarotaties op.

Als zowel [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) als getPageRotations() zijn opgegeven, wordt de watermark toegepast op de geroteerde pagina's. Voor details, zie de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - een map die de paginanummers als sleutels bevat en hun bijbehorende rotaties als waarden.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Om te voorkomen dat de instantie wordt gemaakt alleen om te controleren of deze leeg is

**Returns:**
boolean
