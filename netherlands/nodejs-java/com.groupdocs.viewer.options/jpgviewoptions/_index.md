---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van documenten naar JPG-indeling."
type: docs
weight: 17
url: /nl/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Biedt opties voor het renderen van documenten naar JPG-indeling.

De JpgViewOptions-klasse omvat extra instellingen en parameters die kunnen worden gebruikt om de weergave van documenten in JPG-formaat te regelen in de GroupDocs.Viewer-component.

Voorbeeldgebruik:

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse. |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse. |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse. |
| [JpgViewOptions()](#JpgViewOptions--) | Initialiseert een nieuw exemplaar van  JpgViewOptions  met "p\_\{0\}.jpg" als bestandspadformaat voor de uitvoerbestanden. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse. |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Haalt de maximale breedte van een uitvoerafbeelding op in pixels. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Stelt de maximale breedte van een uitvoerafbeelding in pixels in. |
| [getMaxHeight()](#getMaxHeight--) | Haalt de maximale hoogte van een uitvoerafbeelding op in pixels. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Stelt de maximale hoogte van een uitvoerafbeelding in pixels in. |
| [getQuality()](#getQuality--) | Haalt de kwaliteit van de uitvoerafbeelding op. |
| [setQuality(byte value)](#setQuality-byte-) | Stelt de kwaliteit van de uitvoerafbeelding in. |
| [isExtractText()](#isExtractText--) | Schakelt tekstextractie in. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Schakelt tekstextractie in of uit. |
| [getWidth()](#getWidth--) | Haalt de breedte van de uitvoerafbeelding op in pixels. |
| [setWidth(int value)](#setWidth-int-) | Stelt de breedte van de uitvoerafbeelding in pixels in. |
| [getHeight()](#getHeight--) | Haalt de hoogte van de uitvoerafbeelding op in pixels. |
| [setHeight(int value)](#setHeight-int-) | Stelt de hoogte van de uitvoerafbeelding in pixels in. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Haalt de factory op die methoden implementeert voor het maken en vrijgeven van de uitvoerpagina‑stroom. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Haalt de callback op om de voortgang van het opslaan van een Words- of e-maildocument te schatten. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Stelt de callback in om de voortgang van het opslaan van een Words- of e-maildocument te schatten. |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse.

Zie voor het code‑voorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | De methode die de stream instantieert die wordt gebruikt om de uitvoerpagina‑gegevens te schrijven. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse.

Zie voor het code‑voorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | De methode die de stream instantieert die wordt gebruikt om de uitvoerpagina‑gegevens te schrijven. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | De methode die de stroom vrijgeeft die is gemaakt door de methode die is toegewezen aan de delegate die aan de  createPageStream  parameter is doorgegeven. |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse.

Zie voor het code‑voorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | De fabriek die methoden implementeert voor het creëren en vrijgeven van de uitvoer-paginastream. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Initialiseert een nieuw exemplaar van  JpgViewOptions  met "p\_\{0\}.jpg" als bestandspadformaat voor de uitvoerbestanden. De uitvoerbestanden worden geplaatst in de huidige werkmap van de applicatie.

Zie voor het code‑voorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse.

Zie voor het code‑voorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat, bijv. 'page\_\{0\}.jpg'. |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Initialiseert een nieuw exemplaar van de  JpgViewOptions  klasse.

Zie voor het code‑voorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Het bestandspadformaat, bijv. 'page\_\{0\}.jpg'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Haalt de maximale breedte van een uitvoerafbeelding op in pixels.

Gebruik deze eigenschap om de maximale breedte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentation][]. Als je de \#setWidth(int).setWidth(int)-eigenschap instelt, wordt deze eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - de maximale breedte van een uitvoerafbeelding.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Stelt de maximale breedte van een uitvoerafbeelding in pixels in.

Gebruik deze eigenschap om de maximale breedte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentation][]. Als je de \#setWidth(int).setWidth(int)-eigenschap instelt, wordt deze eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxWidth | int | De maximale breedte van een uitvoerafbeelding. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Haalt de maximale hoogte van een uitvoerafbeelding op in pixels.

Gebruik deze eigenschap om de maximale hoogte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie][]. Als u de \#setHeight(int).setHeight(int) eigenschap instelt, wordt deze eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - de maximale hoogte van een uitvoerafbeelding.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Stelt de maximale hoogte van een uitvoerafbeelding in pixels in.

Gebruik deze eigenschap om de maximale hoogte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie][]. Als u de \#setHeight(int).setHeight(int) eigenschap instelt, wordt deze eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxHeight | int | De maximale hoogte van een uitvoerafbeelding. |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Haalt de kwaliteit van de uitvoerafbeelding op.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - de kwaliteit van de uitvoerafbeelding.
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Stelt de kwaliteit van de uitvoerafbeelding in.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte | De kwaliteit van de uitvoerafbeelding. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Schakelt tekstextractie in.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  als tekstextractie is ingeschakeld,  false  anders.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Schakelt tekstextractie in of uit.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean | true  om tekstextractie in te schakelen,  false  om het uit te schakelen. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de breedte van de uitvoerafbeelding op in pixels.

Gebruik deze eigenschap om de breedte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie][]. Als u deze eigenschap instelt, wordt de \#setMaxWidth(int).setMaxWidth(int) eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - de breedte van de uitvoerafbeelding.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Stelt de breedte van de uitvoerafbeelding in pixels in.

Gebruik deze eigenschap om de breedte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie][]. Als u deze eigenschap instelt, wordt de \#setMaxWidth(int).setMaxWidth(int) eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | De breedte van de uitvoerafbeelding. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de hoogte van de uitvoerafbeelding op in pixels.

Gebruik deze eigenschap om de hoogte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie][]. Als u deze eigenschap instelt, wordt de \#setMaxHeight(int).setMaxHeight(int) eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - de hoogte van de uitvoerafbeelding.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stelt de hoogte van de uitvoerafbeelding in pixels in.

Gebruik deze eigenschap om de hoogte van de uitvoerafbeelding in te stellen (in pixels). Voor een codevoorbeeld, zie de [documentatie][]. Als u deze eigenschap instelt, wordt de \#setMaxHeight(int).setMaxHeight(int) eigenschap genegeerd.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | De hoogte van de uitvoerafbeelding. |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Haalt de factory op die methoden implementeert voor het maken en vrijgeven van de uitvoerpagina‑stroom.

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Haalt de callback op om de voortgang van het opslaan van een Words- of e-maildocument te schatten.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - de callback om de voortgang van het opslaan van het document te schatten.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Stelt de callback in om de voortgang van het opslaan van een Words- of e-maildocument te schatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | De callback om de voortgang van het opslaan van het document te schatten. |

