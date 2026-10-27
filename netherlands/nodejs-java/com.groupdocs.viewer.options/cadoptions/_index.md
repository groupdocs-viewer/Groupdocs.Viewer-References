---
title: "CadOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van CAD-tekeningen."
type: docs
weight: 13
url: /nl/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Biedt opties voor het renderen van CAD-tekeningen.

De CadOptions‑klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt om de weergave van CAD-tekeningen in de GroupDocs.Viewer‑component te regelen.

Voor meer informatie en code‑voorbeelden, zie de [Render CAD‑tekeningen en modellen als HTML, PDF en afbeeldingsbestanden][Render CAD drawings and models as HTML_ PDF_ and image files] en [Specificeer renderopties voor CAD‑bestanden][].

Voorbeeldgebruik:

```

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## Velden

| Veld | Beschrijving |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPc3File()](#getPc3File--) | Haalt het PC3‑bestand (Plotter Configuration) op dat aan de plotter is gekoppeld. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Stelt het PC3‑bestand (Plotter Configuration) in dat aan de plotter is gekoppeld. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Initialiseert een nieuw exemplaar van de  CadOptions  klasse voor weergave op schaalfactor. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Initialiseert een nieuw exemplaar van de  CadOptions  klasse voor weergave op breedte. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Initialiseert een nieuw exemplaar van de  CadOptions  klasse voor weergave op hoogte. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Initialiseert een nieuw exemplaar van de  CadOptions  klasse voor weergave op basis van breedte en hoogte. |
| [getScaleFactor()](#getScaleFactor--) | Haalt de schaalfactor op voor weergave. |
| [getWidth()](#getWidth--) | Haalt de breedte van het uitvoerresultaat op in pixels. |
| [getHeight()](#getHeight--) | Haalt de hoogte van het uitvoerresultaat op in pixels. |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt de achtergrondkleur van de afbeelding op. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Haalt de achtergrondkleur van de afbeelding op. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Stelt de achtergrondkleur van de afbeelding in. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Stelt de achtergrondkleur van de afbeelding in. |
| [getTiles()](#getTiles--) | Haalt de te renderen tekengebieden op. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Stelt de te renderen tekengebieden in. |
| [isRenderLayouts()](#isRenderLayouts--) | Geeft aan of lay-outs uit het CAD-document moeten worden gerenderd. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Stelt in of lay-outs uit het CAD-document moeten worden gerenderd. |
| [getLayoutName()](#getLayoutName--) | Haalt de naam op van de specifieke lay-out die moet worden gerenderd. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Stelt de naam in van de specifieke lay-out die moet worden gerenderd. |
| [getLayers()](#getLayers--) | Haalt de CAD-tekenlagen op die moeten worden gerenderd. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Haalt de CAD-tekenlagen op die moeten worden gerenderd. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Het instellen van deze vlag op true schakelt een speciale prestatiegerichte conversiemodus in voor alle formaten binnen de CAD-familie. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Het instellen van deze vlag op true schakelt een speciale prestatiegerichte conversiemodus in voor alle formaten binnen de CAD-familie. |
| [equals(Object o)](#equals-java.lang.Object-) | Controleert of dit CadOptions-object gelijk is aan een ander object. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Haalt het PC3‑bestand (Plotter Configuration) op dat aan de plotter is gekoppeld.

**Returns:**
java.lang.String - het PC3-bestandspad.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Stelt het PC3‑bestand (Plotter Configuration) in dat aan de plotter is gekoppeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pc3File | java.lang.String | Het PC3-bestandspad. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Initialiseert een nieuw exemplaar van de  CadOptions  klasse voor weergave op schaalfactor.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleFactor | double | De schaalfactor voor weergave. Waarden groter dan 1 vergroten het uitvoerresultaat, terwijl waarden tussen 0 en 1 het uitvoerresultaat verkleinen. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Initialiseert een nieuw exemplaar van de  CadOptions  klasse voor weergave op breedte.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | De breedte van het uitvoerresultaat in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Initialiseert een nieuw exemplaar van de  CadOptions  klasse voor weergave op hoogte.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| height | int | De hoogte van het uitvoerresultaat in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Initialiseert een nieuw exemplaar van de  CadOptions  klasse voor weergave op basis van breedte en hoogte.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | De breedte van het uitvoerresultaat in pixels. |
| height | int | De hoogte van het uitvoerresultaat in pixels. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Haalt de schaalfactor op voor weergave. Waarden hoger dan 1 vergroten het uitvoerresultaat, terwijl waarden tussen 0 en 1 het uitvoerresultaat verkleinen.

**Returns:**
double - de schaalfactor voor weergave.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte van het uitvoerresultaat op in pixels.

**Returns:**
int - de breedte van het uitvoerresultaat.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte van het uitvoerresultaat op in pixels.

**Returns:**
int - de hoogte van het uitvoerresultaat.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Haalt de achtergrondkleur van de afbeelding op.

**Returns:**
java.awt.Color - de achtergrondkleur van de afbeelding.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Haalt de achtergrondkleur van de afbeelding op.

**Returns:**
java.lang.String - de achtergrondkleur van de afbeelding in 0xFFFFFF-indeling.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Stelt de achtergrondkleur van de afbeelding in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| backgroundColor | java.awt.Color | De achtergrondkleur van de afbeelding. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Stelt de achtergrondkleur van de afbeelding in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorName | java.lang.String | De naam van de achtergrondkleur van de afbeelding. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Haalt de te renderen tekengebieden op.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - de lijst met tekengebieden om weer te geven.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Stelt de te renderen tekengebieden in.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | De lijst met tekengebieden om weer te geven. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Geeft aan of lay-outs uit het CAD-document moeten worden gerenderd.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  als lay-outs moeten worden gerenderd,  false  anders.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Stelt in of lay-outs uit het CAD-document moeten worden gerenderd.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  om lay-outs te renderen,  false  anders. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Haalt de naam op van de specifieke lay-out om te renderen. De lay-outnaam is hoofdlettergevoelig.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - de naam van de specifieke lay-out om te renderen.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Stelt de naam in van de specifieke lay-out om te renderen. De lay-outnaam is hoofdlettergevoelig.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | De naam van de specifieke lay-out om te renderen. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Haalt de CAD-tekenlagen op die moeten worden gerenderd.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - de CAD-tekenlagen.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Haalt de CAD-tekenlagen op die moeten worden gerenderd.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | De CAD-tekenlagen. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Het instellen van deze vlag op true schakelt een speciale prestatiegerichte conversiemodus in voor alle formaten binnen de CAD-familie. In deze modus is de conversiesnelheid veel hoger, maar de kwaliteit van de resulterende documenten is aanzienlijk slechter. Standaard is deze uitgeschakeld (false). De kwaliteit van de resulterende documenten is zo goed mogelijk ten koste van de prestaties.

**Returns:**
boolean -  true  als de prestatiegerichte conversiemodus is ingeschakeld,  false  anders.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Het instellen van deze vlag op true schakelt een speciale prestatiegerichte conversiemodus in voor alle formaten binnen de CAD-familie. In deze modus is de conversiesnelheid veel hoger, maar de kwaliteit van de resulterende documenten is aanzienlijk slechter. Standaard is deze uitgeschakeld (false). De kwaliteit van de resulterende documenten is zo goed mogelijk ten koste van de prestaties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  om de prestatiegerichte conversiemodus in te schakelen,  false  om deze uit te schakelen. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Controleert of dit CadOptions-object gelijk is aan een ander object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | java.lang.Object | Het object om mee te vergelijken. |

**Returns:**
boolean -  true  als de objecten gelijk zijn,  false  anders.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berekent de hashcode-waarde voor dit object. De hashcode is gebaseerd op de interne staat van het object en wordt gebruikt in hash-gebaseerde datastructuren zoals hash‑maps en hash‑sets.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - de hashcode-waarde voor dit object.
### toString() {#toString--}
```
public String toString()
```


Retourneert een tekenreeksrepresentatie van dit object.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - een tekenreeksrepresentatie van dit object.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Retourneert een tekenreeksrepresentatie van dit object.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stijl | org.apache.commons.lang3.builder.ToStringStyle | De ToStringStyle die gebruikt moet worden voor het genereren van de tekenreeksrepresentatie. |

**Returns:**
java.lang.String - een tekenreeksrepresentatie van dit object met de opgegeven ToStringStyle.
