---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av dokument till HTML-format."
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Tillhandahåller alternativ för rendering av dokument till HTML-format.

HtmlViewOptions‑klassen kapslar in ytterligare inställningar och parametrar som kan användas för att styra rendering av dokument till HTML‑format i GroupDocs.Viewer‑komponenten.

För detaljer, se [topic][] och dess underordnade.

Exempel på användning:

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
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isRenderResponsive()](#isRenderResponsive--) | Avgör om responsiv rendering är aktiverad. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Ställer in om responsiv rendering är aktiverad. |
| [isMinify()](#isMinify--) | Kontrollerar om minifiering av HTML‑innehåll och HTML‑resurser är aktiverad. |
| [setMinify(boolean value)](#setMinify-boolean-) | Ställer in om minifiering av HTML‑innehåll och HTML‑resurser är aktiverad. |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Aktiverar rendering av ett helt dokument till en HTML‑fil. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Aktiverar rendering av ett helt dokument till en HTML‑fil. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Returnerar den maximala bredden på en utdata bild i pixlar. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Ställer in den maximala bredden på en utdata-bild i pixlar. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Hämtar den maximala höjden på en utdata bild i pixlar. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Ställer in den maximala höjden på en utdata-bild i pixlar. |
| [getImageWidth()](#getImageWidth--) | Hämtar bredden på utdata bilden i pixlar. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Ställer in bredden på utdata-bilden i pixlar. |
| [getImageHeight()](#getImageHeight--) | Hämtar höjden på utdata bilden i pixlar när en enskild bild konverteras till HTML. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Ställer in höjden på utdata bilden i pixlar när en enskild bild konverteras till HTML. |
| [isForPrinting()](#isForPrinting--) | Kontrollerar om utdata‑HTML bör optimeras för utskrift. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Ställer in om utdata‑HTML ska optimeras för utskrift. |
| [isExcludeFonts()](#isExcludeFonts--) | Avgör om teckensnitt ska uteslutas från HTML‑dokumentet. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Ställer in om teckensnitt ska uteslutas från HTML‑dokumentet. |
| [getFontsToExclude()](#getFontsToExclude--) | Hämtar listan med teckensnittsnamn som ska uteslutas från HTML‑dokumentet. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Ställer in listan med teckensnittsnamn som ska uteslutas från HTML‑dokumentet. |
| [isRemoveJavaScript()](#isRemoveJavaScript--) | Tillåter att JavaScript‑källkoden tas bort från länkarna i resulterande HTML‑dokument när inmatningsdokument med skript renderas. |
| [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Ställer in behörighet att ta bort JavaScript‑källkoden från länkarna i resulterande HTML‑dokument när inmatningsdokument med skript renderas. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Hämtar återuppringningsfunktionen som används för att uppskatta sparningsförloppet för ett Words‑ eller e‑post‑dokument. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ställer in återuppringningsfunktionen som används för att uppskatta sparningsförloppet för ett Words‑ eller e‑post‑dokument. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med inbäddade resurser. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med inbäddade resurser. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med inbäddade resurser. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Initierar en ny instans av klassen  HtmlViewOptions . |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Initierar en ny instans av klassen  HtmlViewOptions . |
| [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Initierar en ny instans av klassen  HtmlViewOptions . |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med externa resurser. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med externa resurser. |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med externa resurser. |
| [forExternalResources()](#forExternalResources--) | Initierar en ny instans av klassen  HtmlViewOptions . |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen  HtmlViewOptions . |
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


Avgör om responsiv rendering är aktiverad. Responsiva webbsidor renderas väl på enheter med olika skärmstorlekar.

Responsiv design syftar till att få webbsidor att renderas väl på en mängd olika enheter. För att rendera med en responsiv layout, sätt denna egenskap till true. För kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Returns:**
boolesk -  true  om responsiv rendering är aktiverad,  false  annars.
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Ställer in om responsiv rendering är aktiverad. Responsiva webbsidor renderas väl på enheter med olika skärmstorlekar.

Responsiv design syftar till att få webbsidor att renderas väl på en mängd olika enheter. För att rendera med en responsiv layout, sätt denna egenskap till true. För kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att aktivera responsiv rendering,  false  för att inaktivera den. |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Kontrollerar om minifiering av HTML‑innehåll och HTML‑resurser är aktiverad.

Komprimering av utdata innehållet (HTML, CSS och SVG) är ett av sätten att optimera HTML‑filen. För att göra detta, sätt denna egenskap till true. För kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Returns:**
boolean -  true  om minifiering är aktiverad,  false  annars.
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Ställer in om minifiering av HTML‑innehåll och HTML‑resurser är aktiverad.

Komprimering av utdata innehållet (HTML, CSS och SVG) är ett av sätten att optimera HTML‑filen. För att göra detta, sätt denna egenskap till true. För kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att aktivera minifiering,  false  för att inaktivera. |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Aktiverar rendering av ett helt dokument till en HTML‑fil.

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


Aktiverar rendering av ett helt dokument till en HTML‑fil.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Returnerar den maximala bredden på en utdata bild i pixlar.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - den maximala bredden på en utdata bild.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Ställer in den maximala bredden på en utdata-bild i pixlar.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageMaxWidth | int | Den maximala bredden på en utdata bild. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Hämtar den maximala höjden på en utdata bild i pixlar.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - den maximala höjden på en utdata bild.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Ställer in den maximala höjden på en utdata-bild i pixlar.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageMaxHeight | int | Den maximala höjden på en utdata bild. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Hämtar bredden på utdata bilden i pixlar.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - bredden på en utdata bild.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Ställer in bredden på utdata-bilden i pixlar.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageWidth | int | Bredden på den utdata bilden. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Hämtar höjden på utdata bilden i pixlar när en enskild bild konverteras till HTML.

För detaljer och kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - höjden på utdata bilden i pixlar.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Ställer in höjden på utdata bilden i pixlar när en enskild bild konverteras till HTML.

För detaljer och kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageHeight | int | Höjden på utdata bilden i pixlar. |

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Kontrollerar om utdata‑HTML bör optimeras för utskrift.

Aktivera detta alternativ för att konvertera de utdata HTML‑sidorna till vektor‑SVG‑formatet. För detaljer och kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Returns:**
boolean -  true  om den utdata HTML‑en ska optimeras för utskrift,  false  annars.
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Ställer in om utdata‑HTML ska optimeras för utskrift.

Aktivera detta alternativ för att konvertera de utdata HTML‑sidorna till vektor‑SVG‑formatet. För detaljer och kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att optimera den utdata HTML för utskrift,  false  annars. |

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Avgör om teckensnitt ska uteslutas från HTML‑dokumentet.

Som standard bäddar GroupDocs.Viewer in de teckensnitt som används i dokumentet i HTML. För att förhindra detta, sätt denna egenskap till true. För detaljer och kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
boolean -  true  om teckensnitt ska exkluderas,  false  annars.
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Ställer in om teckensnitt ska uteslutas från HTML‑dokumentet.

Som standard bäddar GroupDocs.Viewer in de teckensnitt som används i dokumentet i HTML. För att förhindra detta, sätt denna egenskap till true. För detaljer och kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att exkludera teckensnitt,  false  annars. |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Hämtar listan med teckensnittsnamn som ska uteslutas från HTML‑dokumentet.

Detta alternativ stöds endast för presentationer. Att inkludera teckensnitt i HTML‑dokumentet förbättrar stabiliteten i den renderade vyn men ökar storleken på renderingsresultatet. Använd detta alternativ för att hitta en kompromiss mellan stabilitet och utdata‑storlek. Inkludera teckensnittsnamn som är vanliga och installerade på de flesta system.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
java.util.List<java.lang.String> - listan med teckensnittsnamn som ska exkluderas från HTML‑dokumentet.
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Ställer in listan med teckensnittsnamn som ska uteslutas från HTML‑dokumentet.

Detta alternativ stöds endast för presentationer. Att inkludera teckensnitt i HTML‑dokumentet förbättrar stabiliteten i den renderade vyn men ökar storleken på renderingsresultatet. Använd detta alternativ för att hitta en kompromiss mellan stabilitet och utdata‑storlek. Inkludera teckensnittsnamn som är vanliga och installerade på de flesta system.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | Listan med teckensnittsnamn som ska exkluderas från HTML‑dokumentet. |

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Tillåter att ta bort JavaScript‑källkoden från länkarna i resulterande HTML‑dokument när inmatningsdokument som innehåller skript renderas. Som standard är den aktiverad (true).

För detaljer om borttagning av JavaScript, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Ställer in behörigheten att ta bort JavaScript‑källkoden från länkarna i resulterande HTML‑dokument när inmatningsdokument som innehåller skript renderas. Som standard är den aktiverad (true).

För detaljer om borttagning av JavaScript, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Hämtar återuppringningsfunktionen som används för att uppskatta sparningsförloppet för ett Words‑ eller e‑post‑dokument.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - återanropet som används för att uppskatta dokumentets sparningsförlopp.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Ställer in återuppringningsfunktionen som används för att uppskatta sparningsförloppet för ett Words‑ eller e‑post‑dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Återanropet som används för att uppskatta dokumentets sparningsförlopp. |

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med inbäddade resurser.

***Note:** The method takes a  CreatePageStream  parameter, which is a method used to instantiate a stream for writing output page data.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar en ström som används för att skriva utdata för siddata. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med inbäddade resurser.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar en ström som används för att skriva utdata för siddata. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Metoden som frigör strömmen som skapats av metoden som tilldelats parametern  createPageStream . |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med inbäddade resurser.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabriken som implementerar metoder för att skapa och frigöra utdata‑strömen för sidan. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Initierar en ny instans av klassen  HtmlViewOptions .

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Initierar en ny instans av klassen  HtmlViewOptions .

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filvägsformatet, t.ex. 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Initierar en ny instans av klassen  HtmlViewOptions .

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Filvägsformatet, t.ex. 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med externa resurser.

***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar strömmen som används för att skriva utdata för siddata. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Metoden som frigör strömmen som skapats av  createPageStream ‑metoden. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Metoden som skapar URL:en för HTML‑resursen. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med externa resurser.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar strömmen som används för att skriva utdata för siddata. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Metoden som instansierar strömmen som används för att skriva utdata för HTML‑resursdata. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | Metoden som skapar URL:en för HTML‑resursen. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Metoden som frigör strömmen som skapats av  createPageStream ‑metoden. |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | Metoden som frigör strömmen som skapats av  createResourceStream ‑metoden. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Initierar en ny instans av klassen  HtmlViewOptions  för rendering till HTML med externa resurser.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabriken som implementerar metoder för att skapa och frigöra utdata‑strömen för sidan. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Fabriken som implementerar metoder för att skapa resurs‑URL:er samt instansiera/frigöra utdata‑HTML‑resursströmmen. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Initierar en ny instans av klassen  HtmlViewOptions .

 *  \- with "p\_\{0\}.html" as file path format for the output HTML files;
 *  \- with "p\_\{0\}\_\{1\}" as file path format for the output HTML-resource files;
 *  \- with "p\_\{0\}\_\{1\}" as URL format for HTML-resources;

Utdatafilerna kommer att placeras i applikationens aktuella arbetskatalog. För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Initierar en ny instans av klassen  HtmlViewOptions .

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filvägsformatet, t.ex. 'page\_\{0\}.html'. |
| resourceFilePathFormat | java.lang.String | Resursfilvägsformatet, t.ex. 'page\_\{0\}/resource\_\{1\}'. |
| resourceUrlFormat | java.lang.String | Resurs‑URL‑formatet, t.ex. 'page\_\{0\}/resource\_\{1\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
