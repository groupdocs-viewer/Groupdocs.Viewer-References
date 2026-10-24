---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Dokumenten im HTML-Format bereit."
type: docs
weight: 16
url: /de/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Stellt Optionen zum Rendern von Dokumenten im HTML-Format bereit.


Die HtmlViewOptions-Klasse kapselt zusätzliche Einstellungen und Parameter
die verwendet werden kann, um die Darstellung von Dokumenten im HTML-Format in der GroupDocs.Viewer-Komponente zu steuern.


Weitere Details finden Sie im [Thema](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) und dessen Unterseiten.


Beispielverwendung:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | Bestimmt, ob responsives Rendering aktiviert ist. |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Legt fest, ob responsives Rendering aktiviert ist. |
|
|  | [isMinify()](#isMinify--) | Prüft, ob die Minimierung von HTML-Inhalt und HTML-Ressourcen aktiviert ist. |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | Legt fest, ob die Minimierung von HTML-Inhalt und HTML-Ressourcen aktiviert ist. |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | Ermöglicht das Rendern eines gesamten Dokuments in eine HTML-Datei. |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Ermöglicht das Rendern eines gesamten Dokuments in eine HTML-Datei. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Gibt die maximale Breite des Ausgabebildes in Pixeln zurück. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Legt die maximale Breite eines Ausgabebildes in Pixeln fest. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Gibt die maximale Höhe des Ausgabebildes in Pixeln zurück. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Legt die maximale Höhe eines Ausgabebildes in Pixeln fest. |
|
|  | [getImageWidth()](#getImageWidth--) | Gibt die Breite des Ausgabebildes in Pixeln zurück. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Legt die Breite des Ausgabebildes in Pixeln fest. |
|
|  | [getImageHeight()](#getImageHeight--) | Gibt die Höhe des Ausgabebildes in Pixeln zurück, wenn ein einzelnes Bild in HTML konvertiert wird. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Legt die Höhe des Ausgabebildes in Pixeln fest, wenn ein einzelnes Bild in HTML konvertiert wird. |
|
|  | [isForPrinting()](#isForPrinting--) | Prüft, ob das Ausgab-HTML für den Druck optimiert werden soll. |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | Legt fest, ob das Ausgab-HTML für den Druck optimiert werden soll. |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | Bestimmt, ob Schriftarten aus dem HTML-Dokument ausgeschlossen werden sollen. |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Legt fest, ob Schriftarten aus dem HTML-Dokument ausgeschlossen werden sollen. |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | Ruft die Liste von Schriftartnamen ab, die aus dem HTML-Dokument ausgeschlossen werden sollen. |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Legt die Liste von Schriftartnamen fest, die aus dem HTML-Dokument ausgeschlossen werden sollen. |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | Ermöglicht das Entfernen des JavaScript-Quellcodes aus den Links in resultierenden HTML-Dokumenten, wenn Eingabedokumente gerendert werden, die Skripte enthalten. |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Legt die Erlaubnis fest, den JavaScript-Quellcode aus den Links in resultierenden HTML-Dokumenten zu entfernen, wenn Eingabedokumente gerendert werden, die Skripte enthalten. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ruft den Callback ab, der verwendet wird, um den Speicherfortschritt eines Words- oder E-Mail-Dokuments zu schätzen. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Legt den Callback fest, der verwendet wird, um den Speicherfortschritt eines Words- oder E-Mail-Dokuments zu schätzen. |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse zum Rendern von HTML mit eingebetteten Ressourcen.
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse zum Rendern von HTML mit eingebetteten Ressourcen.
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse zum Rendern von HTML mit eingebetteten Ressourcen.
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse.
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse.
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse zum Rendern von HTML mit externen Ressourcen.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse zum Rendern von HTML mit externen Ressourcen.
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse zum Rendern von HTML mit externen Ressourcen.
|
|  | [forExternalResources()](#forExternalResources--) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse.
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz von |
HtmlViewOptions
Klasse.
|
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


Bestimmt, ob responsives Rendering aktiviert ist.
Responsive Webseiten werden auf Geräten mit unterschiedlichen Bildschirmgrößen gut dargestellt.


Responsive Design zielt darauf ab, Webseiten auf einer Vielzahl von Geräten gut darzustellen. Um mit einem responsiven Layout zu rendern, setzen Sie diese Eigenschaft auf true.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Returns:**
boolean -  true  wenn responsives Rendering aktiviert ist,  false  andernfalls.

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Legt fest, ob responsives Rendering aktiviert ist.
Responsive Webseiten werden auf Geräten mit unterschiedlichen Bildschirmgrößen gut dargestellt.


Responsive Design zielt darauf ab, Webseiten auf einer Vielzahl von Geräten gut darzustellen. Um mit einem responsiven Layout zu rendern, setzen Sie diese Eigenschaft auf true.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um responsives Rendering zu aktivieren,  false  um es zu deaktivieren. |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Prüft, ob die Minimierung von HTML-Inhalt und HTML-Ressourcen aktiviert ist.


Die Komprimierung des Ausgabecodes (HTML, CSS und SVG) ist eine Möglichkeit, die HTML‑Datei zu optimieren. Setzen Sie dazu diese Eigenschaft auf true.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Returns:**
boolean -  true  wenn Minifizierung aktiviert ist,  false  andernfalls.

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Legt fest, ob die Minimierung von HTML-Inhalt und HTML-Ressourcen aktiviert ist.


Die Komprimierung des Ausgabecodes (HTML, CSS und SVG) ist eine Möglichkeit, die HTML‑Datei zu optimieren. Setzen Sie dazu diese Eigenschaft auf true.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um Minifizierung zu aktivieren,  false  um sie zu deaktivieren. |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Ermöglicht das Rendern eines gesamten Dokuments in eine HTML-Datei.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolesch
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Ermöglicht das Rendern eines gesamten Dokuments in eine HTML-Datei.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderSinglePage | boolesch |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Gibt die maximale Breite des Ausgabebildes in Pixeln zurück.
***Note:** This value is used when converting a single image to HTML.
Für Details und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - die maximale Breite eines Ausgabebildes.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Legt die maximale Breite eines Ausgabebildes in Pixeln fest.
***Note:** This value is used when converting a single image to HTML.
Für Details und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageMaxWidth | int | Die maximale Breite eines Ausgabebildes. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Gibt die maximale Höhe des Ausgabebildes in Pixeln zurück.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Für Details und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - die maximale Höhe eines Ausgabebildes.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Legt die maximale Höhe eines Ausgabebildes in Pixeln fest.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Für Details und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageMaxHeight | int | Die maximale Höhe eines Ausgabebildes. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Gibt die Breite des Ausgabebildes in Pixeln zurück.


***Note:** This value is applicable only when converting a single image to HTML.*
Für Details und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - die Breite des Ausgabebildes.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Legt die Breite des Ausgabebildes in Pixeln fest.


***Note:** This value is applicable only when converting a single image to HTML.*
Für Details und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageWidth | int | Die Breite des Ausgabebildes. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Gibt die Höhe des Ausgabebildes in Pixeln zurück, wenn ein einzelnes Bild in HTML konvertiert wird.


Für Details und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int – die Höhe des Ausgabebildes in Pixeln.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Legt die Höhe des Ausgabebildes in Pixeln fest, wenn ein einzelnes Bild in HTML konvertiert wird.


Für Details und ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | imageHeight | int | Die Höhe des Ausgabebildes in Pixeln. |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Prüft, ob das Ausgab-HTML für den Druck optimiert werden soll.


Aktivieren Sie diese Option, um die Ausgabeseiten in HTML in das Vektor‑SVG‑Format zu konvertieren.
Weitere Details und ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Returns:**
boolean -  true  wenn das Ausgabedokument HTML für den Druck optimiert werden soll,  false  sonst.

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Legt fest, ob das Ausgab-HTML für den Druck optimiert werden soll.


Aktivieren Sie diese Option, um die Ausgabeseiten in HTML in das Vektor‑SVG‑Format zu konvertieren.
Weitere Details und ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um das Ausgabedokument HTML für den Druck zu optimieren,  false  sonst. |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Bestimmt, ob Schriftarten aus dem HTML-Dokument ausgeschlossen werden sollen.


Standardmäßig bettet GroupDocs.Viewer die im Dokument verwendeten Schriftarten in HTML ein. Um dies zu verhindern, setzen Sie diese Eigenschaft auf true.
Weitere Details und ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
boolean -  true  wenn Schriftarten ausgeschlossen werden sollen,  false  sonst.

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Legt fest, ob Schriftarten aus dem HTML-Dokument ausgeschlossen werden sollen.


Standardmäßig bettet GroupDocs.Viewer die im Dokument verwendeten Schriftarten in HTML ein. Um dies zu verhindern, setzen Sie diese Eigenschaft auf true.
Weitere Details und ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | boolesch | true  um Schriftarten auszuschließen,  false  sonst. |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Ruft die Liste von Schriftartnamen ab, die aus dem HTML-Dokument ausgeschlossen werden sollen.


Diese Option wird nur für Präsentationen unterstützt.
Das Einbinden von Schriftarten in das HTML‑Dokument verbessert die Stabilität der Ausgabeansicht, erhöht jedoch die Größe des Rendering‑Ergebnisses.
Verwenden Sie diese Option, um einen Kompromiss zwischen Stabilität und Ausgabengröße zu finden.
Schriftartnamen einbeziehen, die populär und auf den meisten Systemen installiert sind.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) Option ist deaktiviert.*
Weitere Details und ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
java.util.List<java.lang.String> – die Liste der Schriftartnamen, die aus dem HTML‑Dokument ausgeschlossen werden sollen.

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Legt die Liste von Schriftartnamen fest, die aus dem HTML-Dokument ausgeschlossen werden sollen.


Diese Option wird nur für Präsentationen unterstützt.
Das Einbinden von Schriftarten in das HTML‑Dokument verbessert die Stabilität der Ausgabeansicht, erhöht jedoch die Größe des Rendering‑Ergebnisses.
Verwenden Sie diese Option, um einen Kompromiss zwischen Stabilität und Ausgabengröße zu finden.
Schriftartnamen einbeziehen, die populär und auf den meisten Systemen installiert sind.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) Option ist deaktiviert.*
Weitere Details und ein Codebeispiel finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.util.List<java.lang.String> | Die Liste der Schriftartnamen, die aus dem HTML‑Dokument ausgeschlossen werden sollen. |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Ermöglicht das Entfernen des JavaScript‑Quellcodes aus den Links in resultierenden HTML‑Dokumenten beim Rendern von Eingabedokumenten, die Skripte enthalten. Standardmäßig ist dies aktiviert (true).


Weitere Details zum Entfernen von JavaScript finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Returns:**
boolesch
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Legt die Berechtigung fest, den JavaScript‑Quellcode aus den Links in resultierenden HTML‑Dokumenten zu entfernen, wenn Eingabedokumente gerendert werden, die Skripte enthalten. Standardmäßig ist dies aktiviert (true).


Weitere Details zum Entfernen von JavaScript finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolesch |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ruft den Callback ab, der verwendet wird, um den Speicherfortschritt eines Words- oder E-Mail-Dokuments zu schätzen.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback – der Callback, der verwendet wird, um den Fortschritt des Dokumentenspeicherns zu schätzen.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Legt den Callback fest, der verwendet wird, um den Speicherfortschritt eines Words- oder E-Mail-Dokuments zu schätzen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Der Callback, der verwendet wird, um den Fortschritt des Dokumentenspeicherns zu schätzen. |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse zum Rendern von HTML mit eingebetteten Ressourcen.


***Note:** The method takes a 
CreatePageStream
Parameter, der eine Methode ist, die verwendet wird, um einen Stream zum Schreiben von Ausgabeseitendaten zu instanziieren.*
Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die einen Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse zum Rendern von HTML mit eingebetteten Ressourcen.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die einen Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Die Methode, die den von der Methode, die dem Parameter createPageStream zugewiesen ist, erstellten Stream freigibt. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse zum Rendern von HTML mit eingebetteten Ressourcen.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten-Streams implementiert. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Das Dateipfadformat, z. B. 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse zum Rendern von HTML mit externen Ressourcen.


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Die Methode, die den von der Methode createPageStream erstellten Stream freigibt. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Die Methode, die die URL für die HTML-Ressource erstellt. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse zum Rendern von HTML mit externen Ressourcen.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Die Methode, die den Stream erstellt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Die Methode, die den Stream erstellt, der zum Schreiben von Ausgabedaten der HTML-Ressource verwendet wird. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Die Methode, die die URL für die HTML-Ressource erstellt. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Die Methode, die den von der Methode createPageStream erstellten Stream freigibt. |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | Die Methode, die den von der Methode createResourceStream erstellten Stream freigibt. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse zum Rendern von HTML mit externen Ressourcen.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Die Fabrik, die Methoden zum Erstellen und Freigeben des Ausgabeseiten-Streams implementiert. |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Die Fabrik, die Methoden zum Erstellen von Ressourcen-URLs sowie zum Instanziieren/Freigeben des Ausgabestreams der HTML-Ressource implementiert. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse.


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

Die Ausgabedateien werden im aktuellen Arbeitsverzeichnis der Anwendung abgelegt. Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Initialisiert eine neue Instanz von
HtmlViewOptions
Klasse.


Für das Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'page_{0}.html'. |
|
|  | resourceFilePathFormat | java.lang.String | Das Ressourcen-Dateipfadformat, z. B. 'page_{0}/resource_{1}'. |
|
|  | resourceUrlFormat | java.lang.String | Das Ressourcen-URL-Format, z. B. 'page_{0}/resource_{1}'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
