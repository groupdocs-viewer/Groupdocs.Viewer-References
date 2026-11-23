---
title: "Klassen JpgViewOptions kapslar in ytterligare inställningar och parametrar som kan användas för att styra rendering av dokument till JPG-format i GroupDocs.Viewer-komponenten."
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av dokument till JPG-format."
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Tillhandahåller alternativ för rendering av dokument till JPG-format.

Initierar en ny instans av klassen JpgViewOptions.

Exempel på användning:

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna. |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna. |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna. |
| [JpgViewOptions()](#JpgViewOptions--) | Hämtar den maximala bredden på en utdatabild i pixlar. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna. |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | Hämtar kvaliteten på utdatabilden. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Ställer in den maximala bredden på en utdata-bild i pixlar. |
| [getMaxHeight()](#getMaxHeight--) | Hämtar den maximala höjden på en utdata bild i pixlar. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Ställer in den maximala höjden på en utdata-bild i pixlar. |
| [getQuality()](#getQuality--) | Ställer in kvaliteten på utdatabilden. |
| [setQuality(byte value)](#setQuality-byte-) | Hämtar höjden på utdatabilden i pixlar. |
| [isExtractText()](#isExtractText--) | Aktiverar textutdragning. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | Aktiverar eller inaktiverar textutdragning. |
| [getWidth()](#getWidth--) | Hämtar bredden på utdata bilden i pixlar. |
| [setWidth(int value)](#setWidth-int-) | Ställer in bredden på utdata-bilden i pixlar. |
| [getHeight()](#getHeight--) | Hämtar fabriken som implementerar metoder för att skapa och frigöra utdata‑sidströmmen. |
| [setHeight(int value)](#setHeight-int-) | Ställer in höjden på den utgående bilden i pixlar. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Hämtar återanropet för att uppskatta sparningsförloppet för ett Words- eller Email-dokument. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Ställer in återanropet för att uppskatta sparningsförloppet för ett Words- eller Email-dokument. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Metoden som frigör strömmen som skapats av metoden tilldelad delegaten som skickas till parametern createPageStream. |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar strömmen som används för att skriva utdata för siddata. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar strömmen som används för att skriva utdata för siddata. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna. Utdatafilerna kommer att placeras i applikationens aktuella arbetskatalog. |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabriken som implementerar metoder för att skapa och frigöra utdata‑strömen för sidan. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Filvägsformatet, t.ex. 'page\_\{0\}.jpg'.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Använd den här egenskapen för att ange den maximala bredden på utdatabilden (i pixlar). För kodexempel, se [documentation][]. Om du sätter egenskapen \#setWidth(int).setWidth(int) ignoreras denna egenskap. |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Initierar en ny instans av JpgViewOptions med "p\_\{0\}.jpg" som filvägsformat för utdatafilerna.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Använd den här egenskapen för att ange den maximala bredden på utdatabilden (i pixlar). För kodexempel, se [documentation][]. Om du sätter egenskapen \#setWidth(int).setWidth(int) ignoreras denna egenskap. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Hämtar kvaliteten på utdatabilden.

Använd den här egenskapen för att ange den maximala bredden på utdata bilden (i pixlar). För kodexempel, se [dokumentation][]. Om du sätter egenskapen \#setWidth(int).setWidth(int) så ignoreras den här egenskapen.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - den maximala bredden på en utdata bild.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Ställer in den maximala bredden på en utdata-bild i pixlar.

Använd den här egenskapen för att ange den maximala bredden på utdata bilden (i pixlar). För kodexempel, se [dokumentation][]. Om du sätter egenskapen \#setWidth(int).setWidth(int) så ignoreras den här egenskapen.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxWidth | int | Den maximala bredden på en utdata bild. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Hämtar den maximala höjden på en utdata bild i pixlar.

Använd den här egenskapen för att ange den maximala höjden på den utgående bilden (i pixlar). För kodexempel, se [documentation][]. Om du anger egenskapen \#setHeight(int).setHeight(int) så ignoreras denna egenskap.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - den maximala höjden på en utdata bild.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Ställer in den maximala höjden på en utdata-bild i pixlar.

Använd den här egenskapen för att ange den maximala höjden på den utgående bilden (i pixlar). För kodexempel, se [documentation][]. Om du anger egenskapen \#setHeight(int).setHeight(int) så ignoreras denna egenskap.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxHeight | int | Den maximala höjden på en utdata bild. |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Ställer in kvaliteten på utdatabilden.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - kvaliteten på den utgående bilden.
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Hämtar höjden på utdatabilden i pixlar.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte | Kvaliteten på den utgående bilden. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Aktiverar textutdragning.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  om textutdragning är aktiverad,  false  annars.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Aktiverar eller inaktiverar textutdragning.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att aktivera textutdragning,  false  för att inaktivera den. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på utdata bilden i pixlar.

Använd den här egenskapen för att ange bildens bredd (i pixlar). För kodexempel, se [documentation][]. Om du anger denna egenskap ignoreras egenskapen \#setMaxWidth(int).setMaxWidth(int).


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - bredden på en utdata bild.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in bredden på utdata-bilden i pixlar.

Använd den här egenskapen för att ange bildens bredd (i pixlar). För kodexempel, se [documentation][]. Om du anger denna egenskap ignoreras egenskapen \#setMaxWidth(int).setMaxWidth(int).


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | Bredden på den utdata bilden. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar fabriken som implementerar metoder för att skapa och frigöra utdata‑sidströmmen.

Använd den här egenskapen för att ange bildens höjd (i pixlar). För kodexempel, se [documentation][]. Om du anger denna egenskap ignoreras egenskapen \#setMaxHeight(int).setMaxHeight(int).


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - höjden på utdatabilden.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in höjden på den utgående bilden i pixlar.

Använd den här egenskapen för att ange bildens höjd (i pixlar). För kodexempel, se [documentation][]. Om du anger denna egenskap ignoreras egenskapen \#setMaxHeight(int).setMaxHeight(int).


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | Höjden på utdatabilden. |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Hämtar återanropet för att uppskatta sparningsförloppet för ett Words- eller Email-dokument.

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Ställer in återanropet för att uppskatta sparningsförloppet för ett Words- eller Email-dokument.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - återanropet för att uppskatta dokumentets sparningsförlopp.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Metoden som frigör strömmen som skapats av metoden tilldelad delegaten som skickas till parametern createPageStream.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Återanropet för att uppskatta dokumentets sparningsförlopp. |

