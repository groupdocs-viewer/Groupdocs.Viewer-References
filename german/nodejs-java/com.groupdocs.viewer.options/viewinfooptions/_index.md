---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Optionen zum Abrufen von Informationen über die Ansicht bereit."
type: docs
weight: 34
url: /de/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Stellt Optionen zum Abrufen von Informationen über die Ansicht bereit.

Die ViewInfoOptions‑Klasse kapselt zusätzliche Einstellungen und Parameter, die verwendet werden können, um Informationen über eine Ansicht in der GroupDocs.Viewer‑Komponente abzurufen.

Beispielhafte Verwendung:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isExtractText()](#isExtractText--) | Gibt an, ob die Textextraktion aktiviert ist. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | Setzt das Flag, das angibt, ob die Textextraktion aktiviert ist. |
| [getMaxWidth()](#getMaxWidth--) | Gibt die maximale Breite des Ausgabebildes für das Rendern zu PNG/JPG zurück. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Setzt die maximale Breite eines Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG). |
| [getMaxHeight()](#getMaxHeight--) | Gibt die maximale Höhe des Ausgabebildes für das Rendern zu PNG/JPG zurück. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Setzt die maximale Höhe eines Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG). |
| [getWidth()](#getWidth--) | Die Breite des Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG). |
| [setWidth(int width)](#setWidth-int-) | Die Breite des Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG). |
| [getHeight()](#getHeight--) | Die Höhe des Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG). |
| [setHeight(int height)](#setHeight-int-) | Die Höhe des Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG). |
| [forHtmlView()](#forHtmlView--) | Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in HTML abzurufen. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in HTML abzurufen. |
| [forJpgView()](#forJpgView--) | Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in JPG abzurufen. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in JPG abzurufen. |
| [forPngView()](#forPngView--) | Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in PNG abzurufen. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in PNG abzurufen. |
| [forPdfView()](#forPdfView--) | Initialisiert eine neue Instanz der ViewInfoOptions-Klasse, um Informationen zur Ansicht beim Rendern in PDF abzurufen. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Initialisiert eine neue Instanz der ViewInfoOptions-Klasse basierend auf dem [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)-Objekt. |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Initialisiert eine neue Instanz der ViewInfoOptions-Klasse basierend auf dem [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions)-Objekt. |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Initialisiert eine neue Instanz der ViewInfoOptions-Klasse basierend auf dem [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions)-Objekt. |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Initialisiert eine neue Instanz der [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions)-Klasse basierend auf einem PdfViewOptions-Objekt. |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Gibt an, ob die Textextraktion aktiviert ist.

Verwenden Sie diese Eigenschaft, um den Text eines Quelldokuments und seine Koordinaten abzurufen. Anschließend können Sie diese Daten nutzen, um einen auswählbaren Text über dem Bild hinzuzufügen oder eine Textsuche bei bildbasiertem Rendering zu implementieren. Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
boolean – True, wenn die Textextraktion aktiviert ist, sonst false.
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Setzt das Flag, das angibt, ob die Textextraktion aktiviert ist.

Verwenden Sie diese Eigenschaft, um den Text eines Quelldokuments und seine Koordinaten abzurufen. Anschließend können Sie diese Daten nutzen, um einen auswählbaren Text über dem Bild hinzuzufügen oder eine Textsuche bei bildbasiertem Rendering zu implementieren. Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extractText | boolean | True, um die Textextraktion zu aktivieren, false, um sie zu deaktivieren. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Gibt die maximale Breite des Ausgabebildes für das Rendern zu PNG/JPG zurück.

Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - die maximale Breite des Ausgabebildes.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Setzt die maximale Breite eines Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG).

Verwenden Sie diese Eigenschaft, um die maximale Breite des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxWidth | int | Die maximale Breite des Ausgabebildes. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Gibt die maximale Höhe des Ausgabebildes für das Rendern zu PNG/JPG zurück.

Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - die maximale Höhe des Ausgabebildes.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Setzt die maximale Höhe eines Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG).

Verwenden Sie diese Eigenschaft, um die maximale Höhe des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie die  Eigenschaft setzen, wird diese Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxHeight | int | Die maximale Höhe des Ausgabebildes. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Die Breite des Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG).

Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int – die Breite des Bildes.
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Die Breite des Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG).

Verwenden Sie diese Eigenschaft, um die Breite des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Breite des Bildes. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Die Höhe des Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG).

Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int – die Höhe des Bildes.
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Die Höhe des Ausgabebildes (in Pixeln, nur für das Rendern zu PNG/JPG).

Verwenden Sie diese Eigenschaft, um die Höhe des Ausgabebildes (in Pixeln) festzulegen. Für das Codebeispiel siehe die [documentation][]. Wenn Sie diese Eigenschaft setzen, wird die  Eigenschaft ignoriert.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| height | int | Die Höhe des Bildes. |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in HTML abzurufen.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in HTML abzurufen.

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderSinglePage | boolean | Ermöglicht das Rendern von HTML-Inhalten auf einer einzelnen Seite. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in JPG abzurufen.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in JPG abzurufen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extractText | boolean | Ermöglicht die Textextraktion. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in PNG abzurufen.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Initialisiert eine neue Instanz der  ViewInfoOptions  Klasse, um Informationen über die Ansicht beim Rendern in PNG abzurufen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extractText | boolean | Ermöglicht die Textextraktion. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Initialisiert eine neue Instanz der ViewInfoOptions-Klasse, um Informationen zur Ansicht beim Rendern in PDF abzurufen.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Initialisiert eine neue Instanz der ViewInfoOptions-Klasse basierend auf dem [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | Die HTML-Ansichtsoptionen. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Initialisiert eine neue Instanz der ViewInfoOptions-Klasse basierend auf dem [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions)-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | Die PNG-Ansichtsoptionen. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Initialisiert eine neue Instanz der ViewInfoOptions-Klasse basierend auf dem [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions)-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | Die JPG-Ansichtsoptionen. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Initialisiert eine neue Instanz der [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions)-Klasse basierend auf einem PdfViewOptions-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | Die PDF-Ansichtsoptionen. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
