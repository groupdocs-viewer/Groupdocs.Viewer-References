---
title: "PdfOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von PDF‑Dokumenten bereit."
type: docs
weight: 22
url: /de/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Stellt Optionen zum Rendern von PDF‑Dokumenten bereit.


Die PdfOptions-Klasse kapselt verschiedene Einstellungen und Parameter, die verwendet werden können
um die Darstellung von PDF-Dokumenten in der GroupDocs.Viewer-Komponente zu steuern.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Beispielverwendung:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Initialisiert eine neue Instanz von |
PdfOptions
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Bestimmt, ob der Text aus der Quelle in HTML als Bild gerendert wird. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Legt fest, ob der Text aus der Quelle in HTML als Bild gerendert wird. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Überprüft, ob die Zeichengruppierung deaktiviert ist, um maximale Präzision bei der Zeichenpositionierung beim Rendern der Seite zu gewährleisten. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Setzt die Option, die Zeichengruppierung zu deaktivieren, um maximale Präzision bei der Zeichenpositionierung beim Rendern der Seite sicherzustellen. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Überprüft, ob das Rendern von Text und Grafiken der Z‑Reihenfolge im ursprünglichen PDF-Dokument folgen soll, wenn in HTML gerendert wird. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Aktiviert oder deaktiviert das Rendern von Text und Grafiken gemäß der Z‑Reihenfolge im ursprünglichen PDF-Dokument beim Rendern in HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Bestimmt, ob Font‑Hinting aktiviert ist. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Aktiviert Font‑Hinting. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Ermöglicht das Rendern von Seiten mit derselben Größe in Pixeln wie die Seitengröße im Quell‑PDF-Dokument. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Ermöglicht das Rendern von Seiten mit derselben Größe in Pixeln wie die Seitengröße im Quell‑PDF-Dokument. |
|
|  | [getImageQuality()](#getImageQuality--) | Ruft die Ausgabe‑Bildqualität für Bildressourcen beim Rendern in HTML ab. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Setzt die Ausgabe‑Bildqualität für Bildressourcen beim Rendern in HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF ist ein festes Format, sodass alle Elemente einen festen Platz auf einer Seite haben. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF ist ein festes Format, sodass alle Elemente einen festen Platz auf einer Seite haben. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Aktivieren Sie diese Option, um jedes Bild im ausgegebenen HTML-Dokument in ein SVG-Tag zu verpacken und die Ausgabequalität zu verbessern. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Aktivieren Sie diese Option, um jedes Bild im ausgegebenen HTML-Dokument in ein SVG-Tag zu verpacken und die Ausgabequalität zu verbessern. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Ersetzt bei Bedarf Schriftarten, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Ersetzt bei Bedarf Schriftarten, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Deaktivieren Sie alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Setzen Sie das Flag, um alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument zu deaktivieren. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initialisiert eine neue Instanz von
PdfOptions
Klasse.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML.


Beim Rendern von PDF-Dateien mit Schutz gegen das Kopieren von Text und Bildern nach HTML fügt GroupDocs.Viewer dem HTML‑BODY‑Tag ein 'inert'-HTML-Attribut hinzu.
Der Standardwert dieser Option ist
false
.


Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolesch
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML.


Beim Rendern von PDF-Dateien mit Schutz gegen das Kopieren von Text und Bildern nach HTML fügt GroupDocs.Viewer dem HTML‑BODY‑Tag ein 'inert'-HTML-Attribut hinzu.
Der Standardwert dieser Option ist
false
.


Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| disableCopyProtection | boolesch |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Bestimmt, ob der Text aus der Quelle in HTML als Bild gerendert wird.


Wenn diese Option auf
true
, wird der Text im ausgegebenen HTML als Bild gerendert.
Aktivieren Sie diese Option, um den Text nicht auswählbar zu machen oder die Zeichenrenderung zu korrigieren und das HTML wie ein PDF aussehen zu lassen.
Diese Option wird beim Rendern nach HTML unterstützt.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  wenn der Text in HTML als Bild gerendert wird,  false  andernfalls.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Legt fest, ob der Text aus der Quelle in HTML als Bild gerendert wird.


Wenn diese Option auf
true
, wird der Text im ausgegebenen HTML als Bild gerendert.
Aktivieren Sie diese Option, um den Text nicht auswählbar zu machen oder die Zeichenrenderung zu korrigieren und das HTML wie ein PDF aussehen zu lassen.
Diese Option wird beim Rendern nach HTML unterstützt.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | renderTextAsImage | boolesch | true  um den Text in HTML als Bild zu rendern,  false  andernfalls. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Überprüft, ob die Zeichengruppierung deaktiviert ist, um maximale Präzision bei der Zeichenpositionierung beim Rendern der Seite zu gewährleisten.
Wenn diese Option aktiviert ist, werden die Zeichen ohne jegliche Gruppierung gerendert, was maximale Präzision gewährleistet.


***Note:** By default, character grouping is enabled.*
Beim Konvertieren von PDF-Dateien gruppiert GroupDocs.Viewer einzelne Zeichen zu Wörtern, um die Rendering‑Leistung zu verbessern. Enthält Ihr Dokument Hieroglyphen oder Sonderzeichen, möchten Sie möglicherweise die Zeichen­gruppierung verbieten, um ein präziseres Layout zu gewährleisten. Der Standardwert ist false.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean -  true  wenn die Zeichen­gruppierung deaktiviert ist,  false  andernfalls.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Setzt die Option, die Zeichengruppierung zu deaktivieren, um maximale Präzision bei der Zeichenpositionierung beim Rendern der Seite sicherzustellen.
Wenn diese Option aktiviert wird, indem der Wert auf
true
, die Zeichen­gruppierung deaktiviert ist, was maximale Präzision gewährleistet.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
Beim Konvertieren von PDF-Dateien gruppiert GroupDocs.Viewer einzelne Zeichen zu Wörtern, um die Rendering‑Leistung zu verbessern. Enthält Ihr Dokument Hieroglyphen oder Sonderzeichen, möchten Sie möglicherweise die Zeichen­gruppierung verbieten, um ein präziseres Layout zu gewährleisten. Der Standardwert ist false.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um die Zeichen‑gruppierung zu deaktivieren,  false  um sie zu aktivieren. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Überprüft, ob das Rendern von Text und Grafiken der Z‑Reihenfolge im ursprünglichen PDF-Dokument folgen soll, wenn in HTML gerendert wird.
Wenn diese Option durch Zurückgeben aktiviert wird
true
, werden Text und Grafiken gemäß ihrer Z‑Reihenfolge im ursprünglichen PDF‑Dokument gerendert.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Standardmäßig rendert GroupDocs.Veiewer Text und Grafiken als eine einzelne Ebene in HTML. Diese Option ermöglicht es Ihnen, Objekte in derselben Reihenfolge wie in der Quelldatei anzuordnen. Der Standardwert ist false.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean -  true  wenn mehrschichtiges Rendering aktiviert ist,  false  andernfalls.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Aktiviert oder deaktiviert das Rendern von Text und Grafiken gemäß der Z‑Reihenfolge im ursprünglichen PDF-Dokument beim Rendern in HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Standardmäßig rendert GroupDocs.Veiewer Text und Grafiken als eine einzelne Ebene in HTML. Diese Option ermöglicht es Ihnen, Objekte in derselben Reihenfolge wie in der Quelldatei anzuordnen. Der Standardwert ist false.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um mehrschichtiges Rendering zu aktivieren,  false  um es zu deaktivieren. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Bestimmt, ob Font‑Hinting aktiviert ist. Font‑Hinting passt die Darstellung einer Kontur‑Schriftart an.
Diese Option wird nur für TrueType‑Schriften (TTF) unterstützt, wenn sie im Quelldokument verwendet werden.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Font‑Hinting passt an, wie eine Kontur‑Schriftart dargestellt wird. Nur anwendbar auf TTF‑Schriften, die im Quelldokument verwendet werden. Diese Option ist für das Rendering in PNG‑ oder JPG‑Formate verfügbar. Der Standardwert ist false.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean -  true  wenn Font‑Hinting aktiviert ist,  false  andernfalls.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Aktiviert Font‑Hinting. Font‑Hinting passt die Darstellung einer Kontur‑Schriftart an und wird nur für TrueType‑Schriften (TTF) unterstützt, wenn sie im Quelldokument verwendet werden.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Font‑Hinting passt an, wie eine Kontur‑Schriftart dargestellt wird. Nur anwendbar auf TTF‑Schriften, die im Quelldokument verwendet werden. Diese Option ist für das Rendering in PNG‑ oder JPG‑Formate verfügbar. Der Standardwert ist false.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um Font‑Hinting zu aktivieren,  false  um es zu deaktivieren. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Ermöglicht das Rendern von Seiten mit derselben Größe in Pixeln wie die Seitengröße im Quell‑PDF-Dokument.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Standardmäßig berechnet GroupDocs.Viewer die Seitengröße der Ausgabebilder für eine bessere Rendering‑Qualität. Aktivieren Sie diese Option, um sicherzustellen, dass die Ausgabeseiten dieselbe Größe wie die Seitengröße des Quell‑PDF‑Dokuments (in Pixeln) haben. Der Standardwert ist false.
Diese Option ist für das Rendering in PNG‑ oder JPG‑Formate verfügbar.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean -  true  wenn die Option aktiviert ist,  false  andernfalls.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Ermöglicht das Rendern von Seiten mit derselben Größe in Pixeln wie die Seitengröße im Quell‑PDF-Dokument.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Standardmäßig berechnet GroupDocs.Viewer die Seitengröße der Ausgabebilder für eine bessere Rendering‑Qualität. Aktivieren Sie diese Option, um sicherzustellen, dass die Ausgabeseiten dieselbe Größe wie die Seitengröße des Quell‑PDF‑Dokuments (in Pixeln) haben. Der Standardwert ist false.
Diese Option ist für das Rendering in PNG‑ oder JPG‑Formate verfügbar.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | renderOriginalPageSize | boolesch | true  um das Rendering mit der Originalseitengröße zu aktivieren,  false  andernfalls. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Ruft die Bildqualität für Bildressourcen beim Rendering in HTML ab. Der Standardwert ist Low.


Wenn diese Option auf true gesetzt ist, rendert GroupDocs.Viewer Text als Bild in der HTML‑Ausgabe. Dadurch wird der Text nicht auswählbar und die Zeichen‑darstellung verbessert, was ein PDF‑ähnliches Aussehen in HTML gewährleistet. Der Standardwert ist false.
Diese Option ist für das Rendering in HTML verfügbar.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Legt die Bildqualität für Bildressourcen beim Rendering in HTML fest. Der Standardwert ist Low.


Wenn diese Option auf true gesetzt ist, rendert GroupDocs.Viewer Text als Bild in der HTML‑Ausgabe. Dadurch wird der Text nicht auswählbar und die Zeichen‑darstellung verbessert, was ein PDF‑ähnliches Aussehen in HTML gewährleistet. Der Standardwert ist false.
Diese Option ist für das Rendering in HTML verfügbar.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Die Ausgabe-Bildqualität für Bildressourcen beim Rendern in HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF ist ein festes Format, sodass alle Elemente einen festen Platz auf einer Seite haben.
Um sicherzustellen, dass das ausgegebene HTML genauso aussieht wie das Quell-PDF, werden die Dokumente standardmäßig mit einem festen Layout in HTML gerendert.
Beim Rendern mit festem Layout hat das ausgegebene HTML eine feste Größe, sodass die Elemente an derselben Stelle bleiben, unabhängig von der Fenstergröße.
Um in HTML mit fluidem Layout zu rendern, setzen Sie diese Eigenschaft auf false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF- und EPUB-Dokumente werden zunächst mit einem festen Layout in HTML gerendert, um das Aussehen des Ausgangsdokuments beizubehalten. Dieses feste Layout bedeutet, dass alle HTML-Elemente präzise Positionen innerhalb eines Containers mit fester Größe haben. Das Ändern der Größe des Browserfensters beeinflusst nicht die Position und Größe der Elemente im Dokument.
Diese Option ist nur beim Rendern zu HTML verfügbar. Der Standardwert ist true. Um mit fluidem Layout zu rendern, setzen Sie diese Eigenschaft auf false.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean – true, wenn es ein festes Layout ist

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF ist ein festes Format, sodass alle Elemente einen festen Platz auf einer Seite haben.
Um sicherzustellen, dass das ausgegebene HTML genauso aussieht wie das Quell-PDF, werden die Dokumente standardmäßig mit einem festen Layout in HTML gerendert.
Beim Rendern mit festem Layout hat das ausgegebene HTML eine feste Größe, sodass die Elemente an derselben Stelle bleiben, unabhängig von der Fenstergröße.
Um in HTML mit fluidem Layout zu rendern, setzen Sie diese Eigenschaft auf false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF- und EPUB-Dokumente werden zunächst mit einem festen Layout in HTML gerendert, um das Aussehen des Ausgangsdokuments beizubehalten. Dieses feste Layout bedeutet, dass alle HTML-Elemente präzise Positionen innerhalb eines Containers mit fester Größe haben. Das Ändern der Größe des Browserfensters beeinflusst nicht die Position und Größe der Elemente im Dokument.
Diese Option ist nur beim Rendern zu HTML verfügbar. Der Standardwert ist true. Um mit fluidem Layout zu rendern, setzen Sie diese Eigenschaft auf false.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fixedLayout | boolesch | true, wenn es ein festes Layout ist |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Aktivieren Sie diese Option, um jedes Bild im ausgegebenen HTML-Dokument in ein SVG-Tag zu verpacken und die Ausgabequalität zu verbessern.


Diese Option wird unterstützt, wenn [PDF- und Page‑Layout-Dateiformate](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) zu HTML mit eingebetteten und externen Ressourcen gerendert werden.


Standardmäßig werden beim Rendern zu PDF- und Page‑Layout-Dateien alle Bilder zu einem einzigen PNG-Bild zusammengeführt. Das gerenderte PNG-Bild wird als Hintergrund für das ausgegebene HTML-Dokument verwendet.


Mehr erfahren:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean – true, wenn Bilder in SVG eingebettet sind, false andernfalls.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Aktivieren Sie diese Option, um jedes Bild im ausgegebenen HTML-Dokument in ein SVG-Tag zu verpacken und die Ausgabequalität zu verbessern.


Diese Option wird unterstützt, wenn [PDF- und Page‑Layout-Dateiformate](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) zu HTML mit eingebetteten und externen Ressourcen gerendert werden.


Standardmäßig werden beim Rendern zu PDF- und Page‑Layout-Dateien alle Bilder zu einem einzigen PNG-Bild zusammengeführt. Das gerenderte PNG-Bild wird als Hintergrund für das ausgegebene HTML-Dokument verwendet.


Mehr erfahren:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | wrapImagesInSvg | boolesch | true, wenn Bilder in SVG eingebettet werden sollen, false andernfalls. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Ersetzt bei Bedarf Schriftarten, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können.


**Returns:**
boolesch
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Ersetzt bei Bedarf Schriftarten, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | analyzeFonts | boolesch | true, wenn die Schriftarten angezeigt werden sollen, false andernfalls. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Deaktivieren Sie alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument.


Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind.
Beispielsweise kann eine Schriftart nicht in ein PDF-Dokument eingebettet werden, wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren.
Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet das, dass die Person, die dieses Flag setzt, die gesamte Verantwortung übernimmt
für mögliche Lizenz-/Gesetzesverstöße auf eigene Gefahr. Es wird dringend empfohlen,
dieses Flag nur zu setzen, wenn Sie sich sicher sind, dass Sie kein Urheberrecht verletzen. Standardmäßig false.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolesch
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Setzen Sie das Flag, um alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument zu deaktivieren.


Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind.
Beispielsweise kann eine Schriftart nicht in ein PDF-Dokument eingebettet werden, wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren.
Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet das, dass die Person, die dieses Flag setzt, die gesamte Verantwortung übernimmt
für mögliche Lizenz-/Gesetzesverstöße auf eigene Gefahr. Es wird dringend empfohlen,
dieses Flag nur zu setzen, wenn Sie sich sicher sind, dass Sie kein Urheberrecht verletzen. Standardmäßig false.
Für ein Code‑Beispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| disableFontLicenseVerifications | boolesch |  |

