---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för rendering av dokument till JPG-format."
type: docs
weight: 17
url: /sv/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Tillhandahåller alternativ för rendering av dokument till JPG-format.


JpgViewOptions-klassen kapslar in ytterligare inställningar och parametrar som kan användas för att kontrollera rendering av dokument.
till JPG-format i GroupDocs.Viewer-komponenten.


Exempel på användning:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initierar en ny instans av |
JpgViewOptions
klassen.
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initierar en ny instans av |
JpgViewOptions
klassen.
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initierar en ny instans av |
JpgViewOptions
klassen.
|
|  | [JpgViewOptions()](#JpgViewOptions--) | Initierar en ny instans av |
JpgViewOptions
med "p_{0}.jpg" som filvägsformat för utdatafilerna.
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Initierar en ny instans av |
JpgViewOptions
klassen.
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Initierar en ny instans av |
JpgViewOptions
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Hämtar den maximala bredden på en utdata bild i pixlar. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Ställer in den maximala bredden på en utdata-bild i pixlar. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Hämtar den maximala höjden på en utdata bild i pixlar. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Ställer in den maximala höjden på en utdata-bild i pixlar. |
|
|  | [getQuality()](#getQuality--) | Hämtar kvaliteten på utdata bilden. |
|
|  | [setQuality(byte value)](#setQuality-byte-) | Ställer in kvaliteten på utdata bilden. |
|
|  | [isExtractText()](#isExtractText--) | Gör det möjligt att extrahera text. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Aktiverar eller inaktiverar textutdragning. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på utdata bilden i pixlar. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ställer in bredden på utdata bilden i pixlar. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på utdata bilden i pixlar. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ställer in höjden på utdata bilden i pixlar. |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | Hämtar fabriken som implementerar metoder för att skapa och frigöra utdata sidströmmen. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Hämtar återanropet för att uppskatta sparningsförloppet för ett Words- eller Email-dokument. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ställer in återanropet för att uppskatta sparningsförloppet för ett Words- eller Email-dokument. |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Initierar en ny instans av
JpgViewOptions
klassen.


För kodexemplet, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initierar en ny instans av
JpgViewOptions
klassen.


För kodexemplet, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Metoden som frigör strömmen som skapats av metoden tilldelad delegaten som skickas till parametern  createPageStream . |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Initierar en ny instans av
JpgViewOptions
klassen.


För kodexemplet, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabriken som implementerar metoder för att skapa och frigöra utdata‑sidströmmen. |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Initierar en ny instans av
JpgViewOptions
med "p_{0}.jpg" som filvägsformat för utdatafilerna.
Utdatafilerna kommer att placeras i applikationens aktuella arbetskatalog.


För kodexemplet, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Initierar en ny instans av
JpgViewOptions
klassen.


För kodexemplet, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Filvägsformatet, t.ex. 'page_{0}.jpg'. |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Initierar en ny instans av
JpgViewOptions
klassen.


För kodexemplet, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Filvägsformatet, t.ex. 'page_{0}.jpg'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Hämtar den maximala bredden på en utdata bild i pixlar.


Använd den här egenskapen för att ange den maximala bredden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Om du anger egenskapen #setWidth(int).setWidth(int) ignoreras denna egenskap.


**Returns:**
int - den maximala bredden på en utdata bild.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Ställer in den maximala bredden på en utdata-bild i pixlar.


Använd den här egenskapen för att ange den maximala bredden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Om du anger egenskapen #setWidth(int).setWidth(int) ignoreras denna egenskap.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxWidth | int | Den maximala bredden på en utdata bild. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Hämtar den maximala höjden på en utdata bild i pixlar.


Använd den här egenskapen för att ange den maximala höjden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Om du anger egenskapen #setHeight(int).setHeight(int) ignoreras denna egenskap.


**Returns:**
int - den maximala höjden på en utdata bild.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Ställer in den maximala höjden på en utdata-bild i pixlar.


Använd den här egenskapen för att ange den maximala höjden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Om du anger egenskapen #setHeight(int).setHeight(int) ignoreras denna egenskap.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxHeight | int | Den maximala höjden på en utdata bild. |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Hämtar kvaliteten på utdata bilden.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Returns:**
byte - kvaliteten på den utdata bilden.

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Ställer in kvaliteten på utdata bilden.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte | Kvaliteten på utdata bilden. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Gör det möjligt att extrahera text.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  om textutdragning är aktiverad,  false  annars.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Aktiverar eller inaktiverar textutdragning.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att aktivera textutdragning,  false  för att inaktivera den. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden på utdata bilden i pixlar.


Använd den här egenskapen för att ange bredden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Om du anger denna egenskap ignoreras egenskapen #setMaxWidth(int).setMaxWidth(int).


**Returns:**
int - bredden på den utdata bilden.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in bredden på utdata bilden i pixlar.


Använd den här egenskapen för att ange bredden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Om du anger denna egenskap ignoreras egenskapen #setMaxWidth(int).setMaxWidth(int).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Bredden på den utdata bilden. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden på utdata bilden i pixlar.


Använd den här egenskapen för att ange höjden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Om du anger denna egenskap ignoreras egenskapen #setMaxHeight(int).setMaxHeight(int).


**Returns:**
int - höjden på utdatabilden.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in höjden på utdata bilden i pixlar.


Använd den här egenskapen för att ange höjden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Om du anger denna egenskap ignoreras egenskapen #setMaxHeight(int).setMaxHeight(int).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Höjden på utdatabilden. |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Hämtar fabriken som implementerar metoder för att skapa och frigöra utdata sidströmmen.


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Hämtar återanropet för att uppskatta sparningsförloppet för ett Words- eller Email-dokument.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - återuppringningsfunktionen för att uppskatta dokumentets sparningsförlopp.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Ställer in återanropet för att uppskatta sparningsförloppet för ett Words- eller Email-dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Återuppringningsfunktionen för att uppskatta dokumentets sparningsförlopp. |
|

