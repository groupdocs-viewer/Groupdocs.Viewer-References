---
title: "CadOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av CAD-ritningar."
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Tillhandahåller alternativ för rendering av CAD-ritningar.

Klassen CadOptions kapslar in olika inställningar och parametrar som kan användas för att styra rendering av CAD-ritningar i GroupDocs.Viewer-komponenten.

För mer information och kodexempel, se [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] och [Specify rendering options for CAD files][].

Exempel på användning:

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
## Fält

| Fält | Beskrivning |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPc3File()](#getPc3File--) | Hämtar PC3‑filen (Plotter Configuration) som är associerad med plottern. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Ställer in PC3‑filen (Plotter Configuration) som är associerad med plottern. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Initierar en ny instans av  CadOptions  klassen för rendering efter skalfaktor. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Initierar en ny instans av  CadOptions  klassen för rendering efter bredd. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Initierar en ny instans av  CadOptions  klassen för rendering efter höjd. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Initierar en ny instans av klassen  CadOptions  för rendering efter bredd och höjd. |
| [getScaleFactor()](#getScaleFactor--) | Hämtar skalningsfaktorn för rendering. |
| [getWidth()](#getWidth--) | Hämtar bredden på utdataresultatet i pixlar. |
| [getHeight()](#getHeight--) | Hämtar höjden på utdataresultatet i pixlar. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar bakgrundsfärgen på bilden. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Hämtar bakgrundsfärgen på bilden. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Ställer in bakgrundsfärgen på bilden. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Ställer in bakgrundsfärgen på bilden. |
| [getTiles()](#getTiles--) | Hämtar de ritningsområden som ska renderas. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Ställer in de ritningsområden som ska renderas. |
| [isRenderLayouts()](#isRenderLayouts--) | Anger om layouter från CAD-dokumentet ska renderas. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Ställer in om layouter från CAD-dokumentet ska renderas. |
| [getLayoutName()](#getLayoutName--) | Hämtar namnet på den specifika layouten som ska renderas. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Ställer in namnet på den specifika layouten som ska renderas. |
| [getLayers()](#getLayers--) | Hämtar CAD-ritningslagren som ska renderas. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Hämtar CAD-ritningslagren som ska renderas. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Att sätta denna flagga till true aktiverar ett speciellt prestandaorienterat konverteringsläge för alla format inom CAD-familjen. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Att sätta denna flagga till true aktiverar ett speciellt prestandaorienterat konverteringsläge för alla format inom CAD-familjen. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollerar om detta CadOptions‑objekt är lika med ett annat objekt. |
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


Hämtar PC3‑filen (Plotter Configuration) som är associerad med plottern.

**Returns:**
java.lang.String - PC3‑filens sökväg.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Ställer in PC3‑filen (Plotter Configuration) som är associerad med plottern.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pc3File | java.lang.String | PC3‑filens sökväg. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Initierar en ny instans av  CadOptions  klassen för rendering efter skalfaktor.

För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleFactor | double | Skalningsfaktorn för rendering. Värden större än 1 förstorar utdataresultatet, medan värden mellan 0 och 1 gör utdataresultatet mindre. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Initierar en ny instans av  CadOptions  klassen för rendering efter bredd.

För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Bredden på utdataresultatet i pixlar. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Initierar en ny instans av  CadOptions  klassen för rendering efter höjd.

För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| height | int | Höjden på utdataresultatet i pixlar. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Initierar en ny instans av klassen  CadOptions  för rendering efter bredd och höjd.

För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Bredden på utdataresultatet i pixlar. |
| height | int | Höjden på utdataresultatet i pixlar. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Hämtar skalningsfaktorn för rendering. Värden högre än 1 förstorar utdataresultatet, medan värden mellan 0 och 1 gör utdataresultatet mindre.

**Returns:**
double - skalningsfaktorn för rendering.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på utdataresultatet i pixlar.

**Returns:**
int - bredden på utdataresultatet.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden på utdataresultatet i pixlar.

**Returns:**
int - höjden på utdataresultatet.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar bakgrundsfärgen på bilden.

**Returns:**
java.awt.Color - bakgrundsfärgen på bilden.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Hämtar bakgrundsfärgen på bilden.

**Returns:**
java.lang.String - bakgrundsfärgen på bilden i 0xFFFFFF-format.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Ställer in bakgrundsfärgen på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| backgroundColor | java.awt.Color | Bakgrundsfärgen på bilden. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Ställer in bakgrundsfärgen på bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorName | java.lang.String | Namnet på bildens bakgrundsfärg. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Hämtar de ritningsområden som ska renderas.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - listan med ritområden att rendera.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Ställer in de ritningsområden som ska renderas.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | Listan med ritområden att rendera. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Anger om layouter från CAD-dokumentet ska renderas.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  om layouter ska renderas,  false  annars.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Ställer in om layouter från CAD-dokumentet ska renderas.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att rendera layouter,  false  annars. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Hämtar namnet på den specifika layouten som ska renderas. Layoutnamnet är skiftlägeskänsligt.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - namnet på den specifika layouten som ska renderas.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Ställer in namnet på den specifika layouten som ska renderas. Layoutnamnet är skiftlägeskänsligt.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | Namnet på den specifika layouten som ska renderas. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Hämtar CAD-ritningslagren som ska renderas.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD-ritlagerna.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Hämtar CAD-ritningslagren som ska renderas.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | CAD-ritlagren. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Att sätta detta flagg till true aktiverar ett speciellt prestandaorienterat konverteringsläge för alla format inom CAD-familjen. I detta läge är konverteringshastigheten mycket snabbare, men kvaliteten på de resulterande dokumenten är avsevärt sämre. Som standard är det inaktiverat (false). Kvaliteten på de resulterande dokumenten är så bra som möjligt på bekostnad av prestanda.

**Returns:**
boolean -  true  om prestandaorienterat konverteringsläge är aktiverat,  false  annars.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Att sätta detta flagg till true aktiverar ett speciellt prestandaorienterat konverteringsläge för alla format inom CAD-familjen. I detta läge är konverteringshastigheten mycket snabbare, men kvaliteten på de resulterande dokumenten är avsevärt sämre. Som standard är det inaktiverat (false). Kvaliteten på de resulterande dokumenten är så bra som möjligt på bekostnad av prestanda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  för att aktivera det prestandaorienterade konverteringsläget,  false  för att inaktivera det. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollerar om detta CadOptions‑objekt är lika med ett annat objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Objektet att jämföra med. |

**Returns:**
boolean -  true  om objekten är lika,  false  annars.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Beräknar hashkodsvärdet för detta objekt. Hashkoden baseras på objektets interna tillstånd och används i hashbaserade datastrukturer såsom hash‑mappar och hash‑set.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - hashkodsvärdet för detta objekt.
### toString() {#toString--}
```
public String toString()
```


Returnerar en strängrepresentation av detta objekt.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - en strängrepresentation av detta objekt.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Returnerar en strängrepresentation av detta objekt.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stil | org.apache.commons.lang3.builder.ToStringStyle | Den ToStringStyle som ska användas för att generera strängrepresentationen. |

**Returns:**
java.lang.String - en strängrepresentation av detta objekt med den angivna ToStringStyle.
