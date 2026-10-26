---
title: "PdfOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen zum Rendern von PDF‑Dokumenten."
type: docs
weight: 22
url: /de/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Bietet Optionen zum Rendern von PDF‑Dokumenten.

Die PdfOptions-Klasse kapselt verschiedene Einstellungen und Parameter, die zur Steuerung der Darstellung von PDF-Dokumenten in der GroupDocs.Viewer-Komponente verwendet werden können. Weitere Details finden Sie in der [documentation][].

Beispielhafte Verwendung:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Initialisiert eine neue Instanz der PdfOptions-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | Deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Bestimmt, ob der Text aus der Quelle in HTML als Bild gerendert wird. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Legt fest, ob der Text aus der Quelle in HTML als Bild gerendert wird. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Prüft, ob die Zeichen‑gruppierung deaktiviert ist, um maximale Präzision bei der Zeichenpositionierung beim Rendern der Seite beizubehalten. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Setzt die Option, die Zeichen‑gruppierung zu deaktivieren, um maximale Präzision bei der Zeichenpositionierung beim Rendern der Seite zu gewährleisten. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Prüft, ob das Rendern von Text und Grafiken beim Rendern in HTML der Z‑Reihenfolge im ursprünglichen PDF-Dokument folgen soll. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Aktiviert oder deaktiviert das Rendern von Text und Grafiken gemäß der Z‑Reihenfolge im ursprünglichen PDF-Dokument beim Rendern in HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Bestimmt, ob Font‑Hinting aktiviert ist. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Aktiviert Font‑Hinting. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Ermöglicht das Rendern von Seiten mit derselben Größe in Pixeln wie die Seitengröße im Quell‑PDF-Dokument. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Ermöglicht das Rendern von Seiten mit derselben Größe in Pixeln wie die Seitengröße im Quell‑PDF-Dokument. |
| [getImageQuality()](#getImageQuality--) | Ruft die Ausgabe‑Bildqualität für Bildressourcen beim Rendern in HTML ab. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Setzt die Ausgabe‑Bildqualität für Bildressourcen beim Rendern in HTML. |
| [isFixedLayout()](#isFixedLayout--) | PDF ist ein festes Format, sodass alle Elemente einen bestimmten Platz auf einer Seite haben. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF ist ein festes Format, sodass alle Elemente einen bestimmten Platz auf einer Seite haben. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Aktivieren Sie diese Option, um jedes Bild im ausgegebenen HTML-Dokument in ein SVG‑Tag zu verpacken, um die Ausgabequalität zu verbessern. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Aktivieren Sie diese Option, um jedes Bild im ausgegebenen HTML-Dokument in ein SVG‑Tag zu verpacken, um die Ausgabequalität zu verbessern. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Versucht, das Problem zu beheben, wenn der gesamte HTML‑Seiteninhalt ein Link ist. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Versucht, das Problem zu beheben, wenn der gesamte HTML‑Seiteninhalt ein Link ist. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Ersetzt Schriften bei Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Ersetzt Schriften bei Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Deaktiviert alle Lizenzbeschränkungen für alle Schriften im aktuellen XPS/OXPS-Dokument. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Setzen Sie das Flag, um alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument zu deaktivieren. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Initialisiert eine neue Instanz der PdfOptions-Klasse.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML.

Beim Rendern von PDF‑Dateien mit Schutz vor dem Kopieren von Text und Bildern nach HTML fügt GroupDocs.Viewer dem HTML‑BODY‑Tag ein 'inert'-HTML‑Attribut hinzu. Der Standardwert dieser Option ist  false .

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Deaktiviert den Kopierschutz für Inhalte beim Rendern zu HTML.

Beim Rendern von PDF‑Dateien mit Schutz vor dem Kopieren von Text und Bildern nach HTML fügt GroupDocs.Viewer dem HTML‑BODY‑Tag ein 'inert'-HTML‑Attribut hinzu. Der Standardwert dieser Option ist  false .

Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Bestimmt, ob der Text aus der Quelle in HTML als Bild gerendert wird.

Wenn diese Option auf  true  gesetzt ist, wird der Text im Ausgabe‑HTML als Bild gerendert. Aktivieren Sie diese Option, um den Text nicht auswählbar zu machen oder die Zeichen­darstellung zu korrigieren und das HTML wie ein PDF aussehen zu lassen. Diese Option wird beim Rendern nach HTML unterstützt.

***Note:** The default value is  false .*

**Returns:**
boolean –  true  wenn der Text in HTML als Bild gerendert wird,  false  sonst.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Legt fest, ob der Text aus der Quelle in HTML als Bild gerendert wird.

Wenn diese Option auf  true  gesetzt ist, wird der Text im Ausgabe‑HTML als Bild gerendert. Aktivieren Sie diese Option, um den Text nicht auswählbar zu machen oder die Zeichen­darstellung zu korrigieren und das HTML wie ein PDF aussehen zu lassen. Diese Option wird beim Rendern nach HTML unterstützt.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderTextAsImage | boolean | true  um den Text in HTML als Bild zu rendern,  false  sonst. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Prüft, ob die Zeichen­gruppierung deaktiviert ist, um maximale Präzision bei der Zeichen­positionierung beim Rendern der Seite zu erhalten. Wenn diese Option aktiviert ist, werden die Zeichen ohne jegliche Gruppierung gerendert, was maximale Präzision gewährleistet.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean –  true  wenn die Zeichen­gruppierung deaktiviert ist,  false  sonst.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Setzt die Option, die Zeichen­gruppierung zu deaktivieren, um maximale Präzision bei der Zeichen­positionierung beim Rendern der Seite zu gewährleisten. Wenn diese Option durch Setzen des Wertes auf  true  aktiviert wird, ist die Zeichen­gruppierung deaktiviert, was maximale Präzision sicherstellt.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  um die Zeichen­gruppierung zu deaktivieren,  false  um sie zu aktivieren. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Prüft, ob das Rendern von Text und Grafiken der Z‑Reihenfolge im ursprünglichen PDF‑Dokument beim Rendern nach HTML folgen soll. Wenn diese Option durch Rückgabe von  true  aktiviert wird, werden Text und Grafiken gemäß ihrer Z‑Reihenfolge im ursprünglichen PDF‑Dokument gerendert.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean –  true  wenn das schichtweise Rendern aktiviert ist,  false  sonst.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Aktiviert oder deaktiviert das Rendern von Text und Grafiken gemäß der Z‑Reihenfolge im ursprünglichen PDF-Dokument beim Rendern in HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  um das schichtweise Rendern zu aktivieren,  false  um es zu deaktivieren. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Bestimmt, ob Font‑Hinting aktiviert ist. Font‑Hinting passt die Darstellung einer Kontur­schrift an. Diese Option wird nur für TrueType‑Schriften (TTF) unterstützt, wenn sie im Quell‑Dokument verwendet werden.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean –  true  wenn Font‑Hinting aktiviert ist,  false  sonst.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Aktiviert Font‑Hinting. Font‑Hinting passt die Darstellung einer Kontur­schrift an und wird nur für TrueType‑Schriften (TTF) unterstützt, wenn sie im Quell‑Dokument verwendet werden.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  um Font‑Hinting zu aktivieren,  false  um es zu deaktivieren. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Ermöglicht das Rendern von Seiten mit derselben Größe in Pixeln wie die Seitengröße im Quell‑PDF-Dokument.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean –  true  wenn die Option aktiviert ist,  false  sonst.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Ermöglicht das Rendern von Seiten mit derselben Größe in Pixeln wie die Seitengröße im Quell‑PDF-Dokument.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true  um das Rendern mit der Original‑Seiten­größe zu aktivieren,  false  sonst. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Ruft die Ausgabe‑Bildqualität für Bild‑Ressourcen beim Rendern nach HTML ab. Der Standardwert ist Low.

Wenn diese Option auf true gesetzt ist, rendert GroupDocs.Viewer den Text im HTML‑Ausgabe als Bild. Dadurch wird der Text nicht auswählbar und die Zeichen­darstellung verbessert, sodass das HTML ein PDF‑ähnliches Aussehen erhält. Der Standardwert ist false. Diese Option ist für das Rendern nach HTML verfügbar. Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Setzt die Ausgabe‑Bildqualität für Bild‑Ressourcen beim Rendern nach HTML. Der Standardwert ist Low.

Wenn diese Option auf true gesetzt ist, rendert GroupDocs.Viewer den Text im HTML‑Ausgabe als Bild. Dadurch wird der Text nicht auswählbar und die Zeichen­darstellung verbessert, sodass das HTML ein PDF‑ähnliches Aussehen erhält. Der Standardwert ist false. Diese Option ist für das Rendern nach HTML verfügbar. Für ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | Die Ausgabe-Bildqualität für Bildressourcen beim Rendern in HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF ist ein festes Format, sodass alle Elemente einen bestimmten Platz auf einer Seite haben. Um sicherzustellen, dass das ausgegebene HTML genauso aussieht wie das Quell‑PDF, werden die Dokumente standardmäßig mit einem festen Layout in HTML gerendert. Beim Rendern mit festem Layout hat das ausgegebene HTML eine feste Größe, sodass die Elemente an derselben Stelle bleiben, unabhängig von der Fenstergröße. Um HTML mit fluidem Layout zu rendern, setzen Sie diese Eigenschaft auf false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - true, wenn es ein festes Layout ist
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF ist ein festes Format, sodass alle Elemente einen bestimmten Platz auf einer Seite haben. Um sicherzustellen, dass das ausgegebene HTML genauso aussieht wie das Quell‑PDF, werden die Dokumente standardmäßig mit einem festen Layout in HTML gerendert. Beim Rendern mit festem Layout hat das ausgegebene HTML eine feste Größe, sodass die Elemente an derselben Stelle bleiben, unabhängig von der Fenstergröße. Um HTML mit fluidem Layout zu rendern, setzen Sie diese Eigenschaft auf false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fixedLayout | boolean | true, wenn es ein festes Layout ist |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Aktivieren Sie diese Option, um jedes Bild im ausgegebenen HTML-Dokument in ein SVG‑Tag zu verpacken, um die Ausgabequalität zu verbessern.

Diese Option wird unterstützt, wenn Sie [PDF- und Page‑Layout-Dateiformate][] in HTML mit eingebetteten und externen Ressourcen rendern.

Standardmäßig werden beim Rendern in PDF‑ und Page‑Layout‑Dateien alle Bilder zu einem einzigen PNG‑Bild gerendert. Das gerenderte PNG‑Bild wird als Hintergrund für das ausgegebene HTML‑Dokument verwendet.

Mehr erfahren:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean –  true, wenn Bilder in SVG eingebettet sind,  false  sonst.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Aktivieren Sie diese Option, um jedes Bild im ausgegebenen HTML-Dokument in ein SVG‑Tag zu verpacken, um die Ausgabequalität zu verbessern.

Diese Option wird unterstützt, wenn Sie [PDF- und Page‑Layout-Dateiformate][] in HTML mit eingebetteten und externen Ressourcen rendern.

Standardmäßig werden beim Rendern in PDF‑ und Page‑Layout‑Dateien alle Bilder zu einem einzigen PNG‑Bild gerendert. Das gerenderte PNG‑Bild wird als Hintergrund für das ausgegebene HTML‑Dokument verwendet.

Mehr erfahren:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true, wenn Bilder in SVG eingebettet werden sollen, false sonst. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Versucht, das Problem zu beheben, wenn der gesamte HTML‑Seiteninhalt ein Link ist. Funktioniert nur, wenn das Eingabeformat PDF und das Ausgabeformat HTML (mit eingebetteten oder externen Ressourcen) ist. Standardmäßig ist es deaktiviert (false). Aktivieren Sie es nur, wenn Sie wissen, was und warum Sie es tun. Das Aktivieren dieser Option erhöht die Dokumentverarbeitungszeit.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Versucht, das Problem zu beheben, wenn der gesamte HTML‑Seiteninhalt ein Link ist. Funktioniert nur, wenn das Eingabeformat PDF und das Ausgabeformat HTML (mit eingebetteten oder externen Ressourcen) ist. Standardmäßig ist es deaktiviert (false). Aktivieren Sie es nur, wenn Sie wissen, was und warum Sie es tun. Das Aktivieren dieser Option erhöht die Dokumentverarbeitungszeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fixLinkIssue | boolean | true, wenn das Problem behoben werden soll, sonst false. |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Ersetzt Schriften bei Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können.

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Ersetzt Schriften bei Bedarf, um sicherzustellen, dass alle Zeichen im Text angezeigt werden können.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| analyzeFonts | boolean | true, wenn die Schriftarten angezeigt werden sollen, sonst false. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Deaktiviert alle Lizenzbeschränkungen für alle Schriften im aktuellen XPS/OXPS-Dokument.

Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind. Beispielsweise kann eine Schriftart nicht in ein PDF‑Dokument eingebettet werden, wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet das, dass die Person, die dieses Flag setzt, die gesamte Verantwortung für mögliche Lizenz‑/Gesetzesverstöße selbst übernimmt. Sie handeln also auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich sicher sind, dass Sie kein Urheberrecht verletzen. Standardmäßig false. Für ein Code‑Beispiel siehe die [Dokumentation][].

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Setzen Sie das Flag, um alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument zu deaktivieren.

Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn diese Vorgänge durch die Lizenz dieser Schriftart verboten sind. Beispielsweise kann eine Schriftart nicht in ein PDF‑Dokument eingebettet werden, wenn die Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet das, dass die Person, die dieses Flag setzt, die gesamte Verantwortung für mögliche Lizenz‑/Gesetzesverstöße selbst übernimmt. Sie handeln also auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich sicher sind, dass Sie kein Urheberrecht verletzen. Standardmäßig false. Für ein Code‑Beispiel siehe die [Dokumentation][].

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

