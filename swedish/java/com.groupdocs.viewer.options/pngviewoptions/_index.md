---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för rendering av dokument till PNG-format."
type: docs
weight: 25
url: /sv/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Tillhandahåller alternativ för rendering av dokument till PNG-format.


Klassen PngViewOptions kapslar in ytterligare inställningar och parametrar som kan användas
för att kontrollera rendering av dokument till PNG-format i GroupDocs.Viewer-komponenten.


Exempel på användning:

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
För detaljer, se denna [sida](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) och dess underordnade.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Initierar en ny instans av |
PngViewOptions
klassen.
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Initierar en ny instans av |
PngViewOptions
klassen.
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Initierar en ny instans av |
PngViewOptions
klassen.
|
|  | [PngViewOptions()](#PngViewOptions--) | Initierar en ny instans av |
PngViewOptions
klassen.
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Initierar en ny instans av |
PngViewOptions
klassen.
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Initierar en ny instans av |
PngViewOptions
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Returnerar den maximala bredden på en utdata bild i pixlar. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Ställer in den maximala bredden på en utdata-bild i pixlar. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Returnerar den maximala höjden för en utdata bild i pixlar. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Ställer in den maximala höjden på en utdata-bild i pixlar. |
|
|  | [isExtractText()](#isExtractText--) | Bestämmer om textutdragning är aktiverad. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Aktiverar eller inaktiverar textutdragning. |
|
|  | [getWidth()](#getWidth--) | Returnerar bredden på utdata bilden i pixlar. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ställer in bredden på utdata bilden i pixlar. |
|
|  | [getHeight()](#getHeight--) | Returnerar höjden på utdata bilden i pixlar. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ställer in höjden på utdata bilden i pixlar. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Hämtar återanropet för att uppskatta sparningsförloppet för ett dokument. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ställer in återanropet för att uppskatta sparningsförloppet för ett dokument. |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Initierar en ny instans av
PngViewOptions
klassen.


För kodexemplet, se [dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Initierar en ny instans av
PngViewOptions
klassen.


För kodexemplet, se [dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | Metoden som frigör strömmen som skapats av metoden som tilldelats parametern createPageStream. |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Initierar en ny instans av
PngViewOptions
klassen.


För kodexemplet, se [dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Fabriken som implementerar metoder för att skapa och frigöra utdata‑sidströmmen. |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Initierar en ny instans av
PngViewOptions
klassen.


Denna konstruktor initierar en ny instans av
PngViewOptions

med "p_{0}.png" som filvägsformat för utdatafilerna.
Utdatafilerna kommer att placeras i applikationens aktuella arbetskatalog.
För kodexemplet, se [dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Initierar en ny instans av
PngViewOptions
klassen.


Till exempel, om filvägsformatet är 'page_{0}.png', kommer utdatafilerna att vara
namnade som 'page_1.png', 'page_2.png' och så vidare, baserat på sidnumret.


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
För kodexemplet, se [dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Filvägsformatet, t.ex. 'page_{0}.png'. |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Initierar en ny instans av
PngViewOptions
klassen.


Till exempel, om filvägsformatet är 'page_{0}.png', kommer utdatafilerna att vara
namnade som 'page_1.png', 'page_2.png' och så vidare, baserat på sidnumret.
För kodexemplet, se [dokumentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Filvägsformatet, t.ex. 'page_{0}.png'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Returnerar den maximala bredden på en utdata bild i pixlar.


Använd den här egenskapen för att ange den maximala bredden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Om du anger egenskapen ignoreras denna egenskap.


**Returns:**
int - den maximala bredden på utdatabilden.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Ställer in den maximala bredden på en utdata-bild i pixlar.


Använd den här egenskapen för att ange den maximala bredden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Om du anger egenskapen ignoreras denna egenskap.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxWidth | int | Den maximala bredden på utdatabilden. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Returnerar den maximala höjden för en utdata bild i pixlar.


Använd den här egenskapen för att ange den maximala höjden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Om du anger egenskapen ignoreras denna egenskap.


**Returns:**
int - den maximala höjden på utdatabilden.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Ställer in den maximala höjden på en utdata-bild i pixlar.


Använd den här egenskapen för att ange den maximala höjden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Om du anger egenskapen ignoreras denna egenskap.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxHeight | int | Den maximala höjden på utdatabilden. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Bestämmer om textutdragning är aktiverad.


Det här alternativet kan vara användbart när du vill lägga till ett markerbart textlager över bilden.
Använd den här egenskapen för att hämta texten som finns i ett källdokument och dess koordinater. Därefter kan du använda dessa data för att lägga till en markerbar text över bilden eller för att implementera textsökning i bildbaserad rendering.
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  om textutdragning är aktiverad,  false  annars.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Aktiverar eller inaktiverar textutdragning.


Det här alternativet kan vara användbart när du vill lägga till ett markerbart textlager över bilden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att aktivera textutdragning,  false  för att inaktivera den. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Returnerar bredden på utdata bilden i pixlar.


Använd den här egenskapen för att ange bredden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Om du anger denna egenskap ignoreras egenskapen.


**Returns:**
int - bredden på den utdata bilden.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in bredden på utdata bilden i pixlar.


Använd den här egenskapen för att ange bredden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Om du anger denna egenskap ignoreras egenskapen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Bredden på den utdata bilden. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Returnerar höjden på utdata bilden i pixlar.


Använd den här egenskapen för att ange höjden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Om du anger denna egenskap ignoreras egenskapen.


**Returns:**
int - höjden på utdatabilden.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in höjden på utdata bilden i pixlar.


Använd den här egenskapen för att ange höjden på utdatabilden (i pixlar). För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Om du anger denna egenskap ignoreras egenskapen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Höjden på utdatabilden. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Hämtar återanropet för att uppskatta sparningsförloppet för ett dokument.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - återuppringningsfunktionen för att uppskatta dokumentets sparningsförlopp.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Ställer in återanropet för att uppskatta sparningsförloppet för ett dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Återuppringningsfunktionen för att uppskatta dokumentets sparningsförlopp. |
|

