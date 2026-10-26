---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen zum Rendern von Dokumenten in das HTML‑Format."
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Bietet Optionen zum Rendern von Dokumenten in das HTML‑Format.

Die HtmlViewOptions‑Klasse fasst zusätzliche Einstellungen und Parameter zusammen, die zur Steuerung der Darstellung von Dokumenten im HTML‑Format in der GroupDocs.Viewer‑Komponente verwendet werden können.

Weitere Details finden Sie im [topic][] und dessen Unterseiten.

Beispielhafte Verwendung:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```


[topic]: https://docs.groupdocs.com/viewer/java/rendering-to-html/
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isRenderResponsive()](#isRenderResponsive--) | Bestimmt, ob responsives Rendering aktiviert ist. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Legt fest, ob responsives Rendering aktiviert ist. |
| [isMinify()](#isMinify--) | Prüft, ob die Minimierung von HTML‑Inhalten und HTML‑Ressourcen aktiviert ist. |
| [setMinify(boolean value)](#setMinify-boolean-) | Legt fest, ob die Minimierung von HTML‑Inhalten und HTML‑Ressourcen aktiviert ist. |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Ermöglicht das Rendern eines gesamten Dokuments in einer einzigen HTML‑Datei. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Ermöglicht das Rendern eines gesamten Dokuments in einer einzigen HTML‑Datei. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Gibt die maximale Breite eines Ausgabebildes in Pixel zurück. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Setzt die maximale Breite eines Ausgabebildes in Pixeln. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Ermittelt die maximale Höhe eines Ausgabebildes in Pixel. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Setzt die maximale Höhe eines Ausgabebildes in Pixeln. |
| [getImageWidth()](#getImageWidth--) | Ermittelt die Breite des Ausgabebildes in Pixel. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Setzt die Breite des Ausgabebildes in Pixeln. |
| [getImageHeight()](#getImageHeight--) | Ermittelt die Höhe des Ausgabebildes in Pixel beim Konvertieren eines einzelnen Bildes zu HTML. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Legt die Höhe des Ausgabebildes in Pixel beim Konvertieren eines einzelnen Bildes zu HTML fest. |
| [isForPrinting()](#isForPrinting--) | Prüft, ob das Ausgabe‑HTML für den Druck optimiert werden soll. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Legt fest, ob das Ausgabe‑HTML für den Druck optimiert werden soll. |
| [isExcludeFonts()](#isExcludeFonts--) | Bestimmt, ob Schriftarten aus dem HTML‑Dokument ausgeschlossen werden sollen. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Legt fest, ob Schriftarten aus dem HTML‑Dokument ausgeschlossen werden sollen. |
| [getFontsToExclude()](#getFontsToExclude--) | Ruft die Liste der Schriftartnamen ab, die aus dem HTML‑Dokument ausgeschlossen werden sollen. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Legt die Liste der Schriftartnamen fest, die aus dem HTML‑Dokument ausgeschlossen werden sollen. |
| [isRemoveJavaScript()](#isRemoveJavaScript--) | Ermöglicht das Entfernen des JavaScript-Quellcodes aus den Links in resultierenden HTML‑Dokumenten, wenn Eingabedokumente gerendert werden, die Skripte enthalten. |
| [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Legt die Erlaubnis fest, den JavaScript-Quellcode aus den Links in resultierenden HTML‑Dokumenten zu entfernen, wenn Eingabedokumente gerendert werden, die Skripte enthalten. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ruft den Callback ab, der zur Schätzung des Speicherfortschritts eines Words‑ oder E‑Mail‑Dokuments verwendet wird. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Legt den Callback fest, der zur Schätzung des Speicherfortschritts eines Words‑ oder E‑Mail‑Dokuments verwendet wird. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit eingebetteten Ressourcen. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit eingebetteten Ressourcen. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit eingebetteten Ressourcen. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse. |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse. |
| [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit externen Ressourcen. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit externen Ressourcen. |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit externen Ressourcen. |
| [forExternalResources()](#forExternalResources--) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse. |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse. |
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Bestimmt, ob responsives Rendering aktiviert ist. Responsive Webseiten werden auf Geräten mit unterschiedlichen Bildschirmgrößen gut dargestellt.

Responsive Design zielt darauf ab, Webseiten auf einer Vielzahl von Geräten gut darzustellen. Um mit einem responsiven Layout zu rendern, setzen Sie diese Eigenschaft auf true. Für ein Codebeispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Returns:**
boolescher Wert – true, wenn responsives Rendering aktiviert ist, sonst false.
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Legt fest, ob responsives Rendering aktiviert ist. Responsive Webseiten werden auf Geräten mit unterschiedlichen Bildschirmgrößen gut dargestellt.

Responsive Design zielt darauf ab, Webseiten auf einer Vielzahl von Geräten gut darzustellen. Um mit einem responsiven Layout zu rendern, setzen Sie diese Eigenschaft auf true. Für ein Codebeispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true, um responsives Rendering zu aktivieren, false, um es zu deaktivieren. |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Prüft, ob die Minimierung von HTML‑Inhalten und HTML‑Ressourcen aktiviert ist.

Die Komprimierung des Ausgabecodes (HTML, CSS und SVG) ist eine Möglichkeit, die HTML‑Datei zu optimieren. Setzen Sie diese Eigenschaft dazu auf true. Für ein Codebeispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Returns:**
boolean -  true  wenn die Minimierung aktiviert ist,  false  sonst.
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Legt fest, ob die Minimierung von HTML‑Inhalten und HTML‑Ressourcen aktiviert ist.

Die Komprimierung des Ausgabecodes (HTML, CSS und SVG) ist eine Möglichkeit, die HTML‑Datei zu optimieren. Setzen Sie diese Eigenschaft dazu auf true. Für ein Codebeispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  zum Aktivieren der Minimierung,  false  zum Deaktivieren. |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Ermöglicht das Rendern eines gesamten Dokuments in einer einzigen HTML‑Datei.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Ermöglicht das Rendern eines gesamten Dokuments in einer einzigen HTML‑Datei.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Gibt die maximale Breite eines Ausgabebildes in Pixel zurück.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - die maximale Breite eines Ausgabebildes.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Setzt die maximale Breite eines Ausgabebildes in Pixeln.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageMaxWidth | int | Die maximale Breite eines Ausgabebildes. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Ermittelt die maximale Höhe eines Ausgabebildes in Pixel.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - die maximale Höhe eines Ausgabebildes.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Setzt die maximale Höhe eines Ausgabebildes in Pixeln.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageMaxHeight | int | Die maximale Höhe eines Ausgabebildes. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Ermittelt die Breite des Ausgabebildes in Pixel.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - die Breite des Ausgabebildes.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Setzt die Breite des Ausgabebildes in Pixeln.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageWidth | int | Die Breite des Ausgabebildes. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Ermittelt die Höhe des Ausgabebildes in Pixel beim Konvertieren eines einzelnen Bildes zu HTML.

Für Details und ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int – die Höhe des Ausgabebildes in Pixeln.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Legt die Höhe des Ausgabebildes in Pixel beim Konvertieren eines einzelnen Bildes zu HTML fest.

Für Details und ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageHeight | int | Die Höhe des Ausgabebildes in Pixeln. |

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Prüft, ob das Ausgabe‑HTML für den Druck optimiert werden soll.

Aktivieren Sie diese Option, um die ausgegebenen HTML‑Seiten in das Vektor‑SVG‑Format zu konvertieren. Für Details und ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Returns:**
boolean -  true  wenn das ausgegebene HTML für den Druck optimiert werden soll,  false  sonst.
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Legt fest, ob das Ausgabe‑HTML für den Druck optimiert werden soll.

Aktivieren Sie diese Option, um die ausgegebenen HTML‑Seiten in das Vektor‑SVG‑Format zu konvertieren. Für Details und ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  um das ausgegebene HTML für den Druck zu optimieren,  false  sonst. |

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Bestimmt, ob Schriftarten aus dem HTML‑Dokument ausgeschlossen werden sollen.

Standardmäßig bettet GroupDocs.Viewer die im Dokument verwendeten Schriftarten in HTML ein. Um dies zu verhindern, setzen Sie diese Eigenschaft auf true. Für Details und ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
boolean -  true  wenn Schriftarten ausgeschlossen werden sollen,  false  sonst.
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Legt fest, ob Schriftarten aus dem HTML‑Dokument ausgeschlossen werden sollen.

Standardmäßig bettet GroupDocs.Viewer die im Dokument verwendeten Schriftarten in HTML ein. Um dies zu verhindern, setzen Sie diese Eigenschaft auf true. Für Details und ein Code‑Beispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | true  um Schriftarten auszuschließen,  false  sonst. |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Ruft die Liste der Schriftartnamen ab, die aus dem HTML‑Dokument ausgeschlossen werden sollen.

Diese Option wird nur für Präsentationen unterstützt. Das Einbinden von Schriftarten in das HTML‑Dokument verbessert die Stabilität der Ausgabeansicht, erhöht jedoch die Größe des Rendering‑Ergebnisses. Verwenden Sie diese Option, um einen Kompromiss zwischen Stabilität und Ausgabengröße zu finden. Schließen Sie Schriftartnamen ein, die verbreitet und auf den meisten Systemen installiert sind.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
java.util.List<java.lang.String> - die Liste der Schriftartnamen, die aus dem HTML‑Dokument ausgeschlossen werden sollen.
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Legt die Liste der Schriftartnamen fest, die aus dem HTML‑Dokument ausgeschlossen werden sollen.

Diese Option wird nur für Präsentationen unterstützt. Das Einbinden von Schriftarten in das HTML‑Dokument verbessert die Stabilität der Ausgabeansicht, erhöht jedoch die Größe des Rendering‑Ergebnisses. Verwenden Sie diese Option, um einen Kompromiss zwischen Stabilität und Ausgabengröße zu finden. Schließen Sie Schriftartnamen ein, die verbreitet und auf den meisten Systemen installiert sind.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | Die Liste der Schriftartnamen, die aus dem HTML‑Dokument ausgeschlossen werden sollen. |

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Ermöglicht das Entfernen des JavaScript‑Quellcodes aus den Links in resultierenden HTML‑Dokumenten beim Rendern von Eingabedokumenten, die Skripte enthalten. Standardmäßig ist dies aktiviert (true).

Weitere Details zum Entfernen von JavaScript finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Legt die Berechtigung fest, den JavaScript‑Quellcode aus den Links in resultierenden HTML‑Dokumenten zu entfernen, wenn Eingabedokumente mit Skripten gerendert werden. Standardmäßig ist dies aktiviert (true).

Weitere Details zum Entfernen von JavaScript finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ruft den Callback ab, der zur Schätzung des Speicherfortschritts eines Words‑ oder E‑Mail‑Dokuments verwendet wird.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - der Callback, der verwendet wird, um den Fortschritt des Dokumentenspeicherns zu schätzen.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Legt den Callback fest, der zur Schätzung des Speicherfortschritts eines Words‑ oder E‑Mail‑Dokuments verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Der Callback, der verwendet wird, um den Fortschritt des Dokumentenspeicherns zu schätzen. |

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit eingebetteten Ressourcen.

***Note:** The method takes a  CreatePageStream  parameter, which is a method used to instantiate a stream for writing output page data.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die einen Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit eingebetteten Ressourcen.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die einen Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Die Methode, die den von der Methode, die dem Parameter createPageStream zugewiesen ist, erstellten Stream freigibt. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit eingebetteten Ressourcen.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten-Streams implementiert. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Das Dateipfadformat, z. B. 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit externen Ressourcen.

***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Die Methode, die den von der Methode createPageStream erstellten Stream freigibt. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Die Methode, die die URL für die HTML-Ressource erstellt. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit externen Ressourcen.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Die Methode, die den Stream erstellt, der zum Schreiben von Ausgabedaten der HTML-Ressource verwendet wird. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Die Methode, die die URL für die HTML-Ressource erstellt. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Die Methode, die den von der Methode createPageStream erstellten Stream freigibt. |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | Die Methode, die den von der Methode createResourceStream erstellten Stream freigibt. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse für das Rendern nach HTML mit externen Ressourcen.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten-Streams implementiert. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Die Fabrik, die Methoden zum Erstellen von Ressourcen-URLs und zum Instanziieren/Freigeben des Ausgabestreams der HTML-Ressource implementiert. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse.

 *  \- with "p\_\{0\}.html" as file path format for the output HTML files;
 *  \- with "p\_\{0\}\_\{1\}" as file path format for the output HTML-resource files;
 *  \- with "p\_\{0\}\_\{1\}" as URL format for HTML-resources;

Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt. Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Initialisiert eine neue Instanz der HtmlViewOptions‑Klasse.

Für das Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'page\_\{0\}.html'. |
| resourceFilePathFormat | java.lang.String | Das Ressourcen-Dateipfadformat, z. B. 'page\_\{0\}/resource\_\{1\}'. |
| resourceUrlFormat | java.lang.String | Das Ressourcen-URL-Format, z. B. 'page\_\{0\}/resource\_\{1\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
