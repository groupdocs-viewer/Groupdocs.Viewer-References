---
title: "CadOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von CAD-Zeichnungen bereit."
type: docs
weight: 13
url: /de/java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Stellt Optionen zum Rendern von CAD-Zeichnungen bereit.


Die CadOptions‑Klasse kapselt verschiedene Einstellungen und Parameter, die verwendet werden können
um die Darstellung von CAD‑Zeichnungen in der GroupDocs.Viewer‑Komponente zu steuern.


Weitere Informationen und Code‑Beispiele finden Sie unter [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/) und [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


Beispielverwendung:

````

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
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPc3File()](#getPc3File--) | Ruft die PC3 (Plotter Configuration)-Datei ab, die dem Plotter zugeordnet ist. |
|
|  | [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Setzt die PC3 (Plotter Configuration)-Datei, die dem Plotter zugeordnet ist. |
|
|  | [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Initialisiert eine neue Instanz von |
CadOptions
Klasse für die Darstellung mittels Skalierungsfaktor.
|
|  | [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Initialisiert eine neue Instanz von |
CadOptions
Klasse für die Darstellung nach Breite.
|
|  | [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Initialisiert eine neue Instanz von |
CadOptions
Klasse für die Darstellung nach Höhe.
|
|  | [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Initialisiert eine neue Instanz von |
CadOptions
Klasse für die Darstellung nach Breite und Höhe.
|
|  | [getScaleFactor()](#getScaleFactor--) | Liefert den Skalierungsfaktor für die Darstellung. |
|
|  | [getWidth()](#getWidth--) | Liefert die Breite des Ausgabeergebnisses in Pixeln. |
|
|  | [getHeight()](#getHeight--) | Liefert die Höhe des Ausgabeergebnisses in Pixeln. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Liefert die Hintergrundfarbe des Bildes. |
|
|  | [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Liefert die Hintergrundfarbe des Bildes. |
|
|  | [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Setzt die Hintergrundfarbe des Bildes. |
|
|  | [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Setzt die Hintergrundfarbe des Bildes. |
|
|  | [getTiles()](#getTiles--) | Liefert die zu rendernden Zeichenbereiche. |
|
|  | [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Setzt die zu rendernden Zeichenbereiche. |
|
|  | [isRenderLayouts()](#isRenderLayouts--) | Gibt an, ob Layouts aus dem CAD‑Dokument gerendert werden sollen. |
|
|  | [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Legt fest, ob Layouts aus dem CAD‑Dokument gerendert werden sollen. |
|
|  | [getLayoutName()](#getLayoutName--) | Liest den Namen des spezifischen Layouts, das gerendert werden soll. |
|
|  | [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Setzt den Namen des spezifischen Layouts, das gerendert werden soll. |
|
|  | [getLayers()](#getLayers--) | Liest die CAD-Zeichnungsebenen, die gerendert werden sollen. |
|
|  | [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Liest die CAD-Zeichnungsebenen, die gerendert werden sollen. |
|
|  | [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Wenn dieses Flag auf true gesetzt wird, aktiviert es einen speziellen, leistungsorientierten Konvertierungsmodus für alle Formate der CAD-Familie. |
|
|  | [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Wenn dieses Flag auf true gesetzt wird, aktiviert es einen speziellen, leistungsorientierten Konvertierungsmodus für alle Formate der CAD-Familie. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Prüft, ob dieses CadOptions-Objekt einem anderen Objekt gleich ist. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
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


Ruft die PC3 (Plotter Configuration)-Datei ab, die dem Plotter zugeordnet ist.


**Returns:**
java.lang.String - der PC3-Dateipfad.

### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Setzt die PC3 (Plotter Configuration)-Datei, die dem Plotter zugeordnet ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pc3File | java.lang.String | Der PC3-Dateipfad. |
|

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Initialisiert eine neue Instanz von
CadOptions
Klasse für die Darstellung mittels Skalierungsfaktor.


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | scaleFactor | double | Der Skalierungsfaktor für das Rendering. Werte größer als 1 vergrößern das Ausgabeergebnis, während Werte zwischen 0 und 1 das Ausgabeergebnis verkleinern. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.

### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Initialisiert eine neue Instanz von
CadOptions
Klasse für die Darstellung nach Breite.


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | width | int | Die Breite des Ausgabeergebnisses in Pixeln. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.

### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Initialisiert eine neue Instanz von
CadOptions
Klasse für die Darstellung nach Höhe.


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | height | int | Die Höhe des Ausgabeergebnisses in Pixeln. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.

### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Initialisiert eine neue Instanz von
CadOptions
Klasse für die Darstellung nach Breite und Höhe.


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | width | int | Die Breite des Ausgabeergebnisses in Pixeln. |
|
|  | height | int | Die Höhe des Ausgabeergebnisses in Pixeln. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Liefert den Skalierungsfaktor für die Darstellung.
Werte über 1 vergrößern das Ausgabeergebnis, während Werte zwischen 0 und 1 das Ausgabeergebnis verkleinern.


**Returns:**
double - der Skalierungsfaktor für das Rendering.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Liefert die Breite des Ausgabeergebnisses in Pixeln.


**Returns:**
int - die Breite des Ausgabeergebnisses.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Liefert die Höhe des Ausgabeergebnisses in Pixeln.


**Returns:**
int - die Höhe des Ausgabeergebnisses.

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
java.lang.String - die Hintergrundfarbe des Bildes im Format 0xFFFFFF.

### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Setzt die Hintergrundfarbe des Bildes.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | backgroundColor | java.awt.Color | Die Hintergrundfarbe des Bildes. |
|

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Setzt die Hintergrundfarbe des Bildes.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | colorName | java.lang.String | Der Name der Hintergrundfarbe des Bildes. |
|

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Liefert die zu rendernden Zeichenbereiche.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
Die
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoperations#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoperations#setRenderLayouts-boolean-))
und
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadoperations#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoperations#setLayoutName-String-)) Optionen werden ignoriert
beim Rendern nach Kacheln.*


**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - die Liste der zu rendernden Zeichenbereiche.

### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Setzt die zu rendernden Zeichenbereiche.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
Die
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoperations#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoperations#setRenderLayouts-boolean-))
und
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadoperations#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoperations#setLayoutName-String-)) Optionen werden ignoriert
beim Rendern nach Kacheln.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.viewer.options.Tile> | Die Liste der zu rendernden Zeichenbereiche. |
|

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Gibt an, ob Layouts aus dem CAD‑Dokument gerendert werden sollen.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Standardmäßig wird nur das Modell gerendert.*


**Returns:**
boolean -  true  wenn Layouts gerendert werden sollen,  false  sonst.

### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Legt fest, ob Layouts aus dem CAD‑Dokument gerendert werden sollen.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Standardmäßig wird nur das Modell gerendert.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  zum Rendern von Layouts,  false  sonst. |
|

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Liest den Namen des zu rendernden spezifischen Layouts. Der Layout-Name ist case-sensitive.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Standardmäßig wird nur das Modell gerendert.*


**Returns:**
java.lang.String - der Name des zu rendernden spezifischen Layouts.

### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Setzt den Namen des zu rendernden spezifischen Layouts. Der Layout-Name ist case-sensitive.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Standardmäßig wird nur das Modell gerendert.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Name des zu rendernden spezifischen Layouts. |
|

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Liest die CAD-Zeichnungsebenen, die gerendert werden sollen.


**Note:** By default, all layers are rendered. Layer names are case-sensitive.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - die CAD-Zeichnungsebenen.

### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Liest die CAD-Zeichnungsebenen, die gerendert werden sollen.
***Note:** By default, all layers are rendered. Layer names are case-sensitive.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.viewer.results.Layer> | Die CAD-Zeichnungsebenen. |
|

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Durch Setzen dieses Flags auf true wird ein spezieller, leistungsorientierter Konvertierungsmodus für alle Formate der CAD-Familie aktiviert. In diesem Modus ist die Konvertierungsgeschwindigkeit deutlich höher, jedoch ist die Qualität der resultierenden Dokumente erheblich schlechter. Standardmäßig ist er deaktiviert (false). Die Qualität der resultierenden Dokumente ist bestmöglich, jedoch zulasten der Leistung.


**Returns:**
boolean -  true  wenn der leistungsorientierte Konvertierungsmodus aktiviert ist,  false  sonst.

### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Durch Setzen dieses Flags auf true wird ein spezieller, leistungsorientierter Konvertierungsmodus für alle Formate der CAD-Familie aktiviert. In diesem Modus ist die Konvertierungsgeschwindigkeit deutlich höher, jedoch ist die Qualität der resultierenden Dokumente erheblich schlechter. Standardmäßig ist er deaktiviert (false). Die Qualität der resultierenden Dokumente ist bestmöglich, jedoch zulasten der Leistung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | enablePerformanceConversionMode | boolesch | true  zum Aktivieren des leistungsorientierten Konvertierungsmodus,  false  zum Deaktivieren. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Prüft, ob dieses CadOptions-Objekt einem anderen Objekt gleich ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | o | java.lang.Object | Das Objekt zum Vergleichen mit. |
|

**Returns:**
boolean -  true  wenn die Objekte gleich sind,  false  sonst.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Berechnet den Hashcode-Wert für dieses Objekt. Der Hashcode basiert auf
dem internen Zustand des Objekts und wird in hashbasierten Datenstrukturen verwendet
wie z.B. Hash-Maps und Hash-Sets.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - der Hashcode-Wert für dieses Objekt.

### toString() {#toString--}
```
public String toString()
```


Gibt eine String-Darstellung dieses Objekts zurück.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Returns:**
java.lang.String - eine String-Darstellung dieses Objekts.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Gibt eine String-Darstellung dieses Objekts zurück.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stil | org.apache.commons.lang3.builder.ToStringStyle | Der ToStringStyle, der zur Erzeugung der String-Darstellung verwendet wird. |
|

**Returns:**
java.lang.String - eine String-Darstellung dieses Objekts unter Verwendung des angegebenen ToStringStyle.

