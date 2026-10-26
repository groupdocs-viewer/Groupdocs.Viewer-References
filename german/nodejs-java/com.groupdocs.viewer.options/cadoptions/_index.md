---
title: "CadOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen zum Rendern von CAD‑Zeichnungen."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Bietet Optionen zum Rendern von CAD‑Zeichnungen.

Die CadOptions-Klasse fasst verschiedene Einstellungen und Parameter zusammen, die zur Steuerung der Darstellung von CAD-Zeichnungen in der GroupDocs.Viewer-Komponente verwendet werden können.

Weitere Informationen und Codebeispiele finden Sie unter [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] und [Specify rendering options for CAD files][].

Beispielhafte Verwendung:

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
## Felder

| Feld | Beschreibung |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPc3File()](#getPc3File--) | Ruft die mit dem Plotter verbundene PC3‑Datei (Plotter Configuration) ab. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Legt die mit dem Plotter verbundene PC3‑Datei (Plotter Configuration) fest. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Initialisiert eine neue Instanz der  CadOptions  Klasse für die Darstellung nach Skalierungsfaktor. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Initialisiert eine neue Instanz der  CadOptions  Klasse für die Darstellung nach Breite. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Initialisiert eine neue Instanz der  CadOptions  Klasse für die Darstellung nach Höhe. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Initialisiert eine neue Instanz der  CadOptions  Klasse für das Rendern nach Breite und Höhe. |
| [getScaleFactor()](#getScaleFactor--) | Liefert den Skalierungsfaktor für das Rendern. |
| [getWidth()](#getWidth--) | Liefert die Breite des Ausgabeergebnisses in Pixeln. |
| [getHeight()](#getHeight--) | Liefert die Höhe des Ausgabeergebnisses in Pixeln. |
| [getBackgroundColor()](#getBackgroundColor--) | Liefert die Hintergrundfarbe des Bildes. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Liefert die Hintergrundfarbe des Bildes. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Setzt die Hintergrundfarbe des Bildes. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Setzt die Hintergrundfarbe des Bildes. |
| [getTiles()](#getTiles--) | Liefert die zu rendernden Zeichenbereiche. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Setzt die zu rendernden Zeichenbereiche. |
| [isRenderLayouts()](#isRenderLayouts--) | Gibt an, ob Layouts aus dem CAD-Dokument gerendert werden sollen. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Legt fest, ob Layouts aus dem CAD-Dokument gerendert werden sollen. |
| [getLayoutName()](#getLayoutName--) | Liefert den Namen des zu rendernden spezifischen Layouts. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Setzt den Namen des zu rendernden spezifischen Layouts. |
| [getLayers()](#getLayers--) | Liefert die CAD-Zeichnungsebenen zum Rendern. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Liefert die CAD-Zeichnungsebenen zum Rendern. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Das Setzen dieses Flags auf true aktiviert einen speziellen, leistungsorientierten Konvertierungsmodus für alle Formate innerhalb der CAD-Familie. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Das Setzen dieses Flags auf true aktiviert einen speziellen, leistungsorientierten Konvertierungsmodus für alle Formate innerhalb der CAD-Familie. |
| [equals(Object o)](#equals-java.lang.Object-) | Prüft, ob dieses CadOptions-Objekt einem anderen Objekt gleich ist. |
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


Ruft die mit dem Plotter verbundene PC3‑Datei (Plotter Configuration) ab.

**Returns:**
java.lang.String - der PC3-Dateipfad.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Legt die mit dem Plotter verbundene PC3‑Datei (Plotter Configuration) fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pc3File | java.lang.String | Der PC3-Dateipfad. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Initialisiert eine neue Instanz der  CadOptions  Klasse für die Darstellung nach Skalierungsfaktor.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleFactor | double | Der Skalierungsfaktor für das Rendern. Werte größer als 1 vergrößern das Ausgabeergebnis, während Werte zwischen 0 und 1 das Ausgabeergebnis verkleinern. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Initialisiert eine neue Instanz der  CadOptions  Klasse für die Darstellung nach Breite.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Breite des Ausgabeergebnisses in Pixeln. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Initialisiert eine neue Instanz der  CadOptions  Klasse für die Darstellung nach Höhe.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| height | int | Die Höhe des Ausgabeergebnisses in Pixeln. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Initialisiert eine neue Instanz der  CadOptions  Klasse für das Rendern nach Breite und Höhe.

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Breite des Ausgabeergebnisses in Pixeln. |
| height | int | Die Höhe des Ausgabeergebnisses in Pixeln. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Liefert den Skalierungsfaktor für das Rendern. Werte über 1 vergrößern das Ausgabeergebnis, während Werte zwischen 0 und 1 das Ausgabeergebnis verkleinern.

**Returns:**
double - der Skalierungsfaktor für das Rendern.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Liefert die Breite des Ausgabeergebnisses in Pixeln.

**Returns:**
int - die Breite des Ausgaberesultats.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Liefert die Höhe des Ausgabeergebnisses in Pixeln.

**Returns:**
int - die Höhe des Ausgaberesultats.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liefert die Hintergrundfarbe des Bildes.

**Returns:**
java.awt.Color - die Hintergrundfarbe des Bildes.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Liefert die Hintergrundfarbe des Bildes.

**Returns:**
java.lang.String - die Hintergrundfarbe des Bildes im 0xFFFFFF-Format.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Setzt die Hintergrundfarbe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| backgroundColor | java.awt.Color | Die Hintergrundfarbe des Bildes. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Setzt die Hintergrundfarbe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorName | java.lang.String | Der Name der Hintergrundfarbe des Bildes. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Liefert die zu rendernden Zeichenbereiche.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - die Liste der zu rendernden Zeichenregionen.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Setzt die zu rendernden Zeichenbereiche.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | Die Liste der zu rendernden Zeichenregionen. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Gibt an, ob Layouts aus dem CAD-Dokument gerendert werden sollen.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  wenn Layouts gerendert werden sollen,  false  sonst.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Legt fest, ob Layouts aus dem CAD-Dokument gerendert werden sollen.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  zum Rendern von Layouts,  false  sonst. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Liefert den Namen des zu rendernden spezifischen Layouts. Der Layout-Name ist case-sensitive.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - der Name des zu rendernden spezifischen Layouts.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Setzt den Namen des zu rendernden spezifischen Layouts. Der Layout-Name ist case-sensitive.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | Der Name des zu rendernden spezifischen Layouts. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Liefert die CAD-Zeichnungsebenen zum Rendern.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - die CAD-Zeichnungsebenen.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Liefert die CAD-Zeichnungsebenen zum Rendern.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | Die CAD-Zeichnungsebenen. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Wenn dieses Flag auf true gesetzt wird, aktiviert es einen speziellen, leistungsorientierten Konvertierungsmodus für alle Formate der CAD-Familie. In diesem Modus ist die Konvertierungsgeschwindigkeit deutlich höher, jedoch ist die Qualität der resultierenden Dokumente erheblich schlechter. Standardmäßig ist er deaktiviert (false). Die Qualität der resultierenden Dokumente ist bestmöglich, jedoch zulasten der Leistung.

**Returns:**
boolean -  true  wenn der leistungsorientierte Konvertierungsmodus aktiviert ist,  false  sonst.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Wenn dieses Flag auf true gesetzt wird, aktiviert es einen speziellen, leistungsorientierten Konvertierungsmodus für alle Formate der CAD-Familie. In diesem Modus ist die Konvertierungsgeschwindigkeit deutlich höher, jedoch ist die Qualität der resultierenden Dokumente erheblich schlechter. Standardmäßig ist er deaktiviert (false). Die Qualität der resultierenden Dokumente ist bestmöglich, jedoch zulasten der Leistung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  zum Aktivieren des leistungsorientierten Konvertierungsmodus,  false  zum Deaktivieren. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Prüft, ob dieses CadOptions-Objekt einem anderen Objekt gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das Objekt, mit dem verglichen wird. |

**Returns:**
boolean -  true  wenn die Objekte gleich sind,  false  sonst.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berechnet den Hashcode-Wert für dieses Objekt. Der Hashcode basiert auf dem internen Zustand des Objekts und wird in hashbasierten Datenstrukturen wie Hash-Maps und Hash-Sets verwendet.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - der Hashcode-Wert für dieses Objekt.
### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkettenrepräsentation dieses Objekts zurück.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - eine Zeichenkettenrepräsentation dieses Objekts.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Gibt eine Zeichenkettenrepräsentation dieses Objekts zurück.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stil | org.apache.commons.lang3.builder.ToStringStyle | Der ToStringStyle, der zur Erzeugung der Zeichenkettenrepräsentation verwendet wird. |

**Returns:**
java.lang.String - eine Zeichenkettenrepräsentation dieses Objekts unter Verwendung des angegebenen ToStringStyle.
