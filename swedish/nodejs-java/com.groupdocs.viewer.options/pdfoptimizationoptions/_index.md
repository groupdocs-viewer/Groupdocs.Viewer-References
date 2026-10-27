---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Använd den här klassen för att ange PDF-optimeringsalternativ som ska tillämpas på den genererade PDF-filen."
type: docs
weight: 21
url: /sv/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Använd den här klassen för att ange PDF-optimeringsalternativ som ska tillämpas på den genererade PDF-filen.

Dessa optimeringsalternativ stöds för alla inmatningsfilformat som stöds för export till PDF. För detaljer och kodexempel, se denna [sida][] och dess underordnade.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Ställer in standardvärden för MaxResolution‑alternativet till 300 och ImageQuality‑alternativet till 100. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isLinearize()](#isLinearize--) | Aktiverar optimering av utdata‑PDF‑filen för visning online med en webbläsare. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Ställer in om utdata‑PDF ska optimeras för online‑bläddring med en webbläsare. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Anmärkningar kan tas bort när de är onödiga. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Ställer in om onödiga anmärkningar ska tas bort från PDF‑filen. |
| [isRemoveFormFields()](#isRemoveFormFields--) | Om PDF‑dokumentet innehåller AcroForms kan vi försöka minska filstorleken genom att platta till formulärfält. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Ställer in om formulärfält ska tas bort från PDF‑filen. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF‑filen består av text, bild, bilaga, anmärkningar, grafer och andra objekt. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Ställer in om PDF‑filen ska konverteras till gråskala. |
| [isSubsetFonts()](#isSubsetFonts--) | Varje teckensnitt som används för att visa text på sidan innehåller en uppsättning glyfer för teckensnittets tecken. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Ställer in om teckensnitten i PDF‑filen ska delmängdas. |
| [isCompressImages()](#isCompressImages--) | Om käll‑PDF‑filen innehåller bilder, överväg att komprimera bilderna och ange deras kvalitet. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Ställer in om bilderna i PDF‑filen ska komprimeras. |
| [getImageQuality()](#getImageQuality--) | Om käll‑PDF‑filen innehåller bilder, överväg att komprimera bilderna och ange deras kvalitet. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | Ställer in bildkvaliteten för komprimering av bilderna i PDF‑filen. |
| [isResizeImages()](#isResizeImages--) | Kan användas med alternativet CompressImages för att ändra storlek på bilderna med lägre upplösning. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Ställer in om bilderna i PDF‑filen ska skalas om. |
| [getMaxResolution()](#getMaxResolution--) | Kan användas med alternativet CompressImages för att ändra storlek på bilderna med lägre upplösning. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Ställer in den maximala upplösningen för att ändra storlek på bilderna i PDF‑filen. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimera Excel‑kalkylbladsramar och teckensnitt för mindre utdatafilstorlek. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Ställer in om kalkylbladen i PDF‑filen ska optimeras. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Ta bort privat information (sidinformation) om den är inställd på true. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Ställer in om privat information ska tas bort från PDF‑filen. |
| [isUnembedFonts()](#isUnembedFonts--) | Om dokumentet använder inbäddade teckensnitt betyder det att all teckensnittsdata är placerad i dokumentet. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Ställer in om de inbäddade teckensnitten i PDF‑filen ska avbäddas. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Ibland innehåller ett dokument flera identiska resursströmmar (till exempel bilder). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Ställer in om duplicerade strömmar i PDF‑filen ska länkas. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | Om den här egenskapen är inställd på true kommer sidinnehållet att återanvändas när dokumentet optimeras för identiska sidor. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Ställer in om sidinnehållet får återanvändas i PDF:en. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Ibland innehåller ett dokument oanvända resursströmmar. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Ställer in om oanvända strömmar ska tas bort från PDF:en. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Ett PDF-dokument innehåller ibland PDF-objekt som inte refereras från något annat objekt i dokumentet. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Ställer in om oanvända objekt ska tas bort från PDF:en. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Ställer in standardvärden för MaxResolution‑alternativet till 300 och ImageQuality‑alternativet till 100.

För detaljer och kodexempel, se denna [page][] och dess underordnade.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Aktiverar optimering av utdata‑PDF‑filen för visning online med en webbläsare.

För kodexempel, se denna [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  om den genererade PDF-filen är optimerad för online‑bläddring,  false  annars.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Ställer in om utdata‑PDF ska optimeras för online‑bläddring med en webbläsare.

För kodexempel, se denna [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| linearize | boolean | true  för att optimera den genererade PDF-filen för online‑bläddring,  false  annars. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Anmärkningar kan tas bort när de är onödiga. När de behövs men inte kräver ytterligare redigering kan de plattas ut. Det minskar filstorleken.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  om anmärkningar tas bort,  false  annars.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Ställer in om onödiga anmärkningar ska tas bort från PDF‑filen.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removeAnnotations | boolean | true  för att ta bort onödiga anmärkningar,  false  annars. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Om PDF‑dokumentet innehåller AcroForms kan vi försöka minska filstorleken genom att platta till formulärfält.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  om formulärfält tas bort,  false  annars.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Ställer in om formulärfält ska tas bort från PDF‑filen.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removeFormFields | boolean | true  för att ta bort formulärfält,  false  annars. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


En PDF-fil består av Text, Bild, Bilaga, Anmärkningar, Grafer och andra objekt. Du kan stöta på ett krav att konvertera en PDF från RGB-färgrymd till gråskala så att utskrift av dessa PDF-filer blir snabbare. När filen konverteras till gråskala minskar även dokumentets storlek, men med denna förändring kan dokumentets kvalitet försämras. För närvarande stöds denna funktion av Pre‑Flight‑funktionen i Adobe Acrobat.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  om PDF-filen konverteras till gråskala,  false  annars.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Ställer in om PDF‑filen ska konverteras till gråskala.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertToGrayScale | boolean | true  för att konvertera PDF-filen till gråskala,  false  annars. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Varje teckensnitt som används för att visa text på sidan innehåller en uppsättning glyfer för teckensnittets tecken. PDF‑specifikationen stödjer "font subset", dvs. ett teckensnitt med endast de glyfer som används. Detta kan orsaka problem när text ska uppdateras (eftersom nödvändiga glyfer kanske saknas i teckensnittet), men för ett dokument som inte planeras att ändras möjliggör detta en minskning av storleken.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  om teckensnitt är subsetade,  false  annars.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Ställer in om teckensnitten i PDF‑filen ska delmängdas.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subsetFonts | boolean | true  för att subseta teckensnitten,  false  annars. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Om käll-PDF-filen innehåller bilder, överväg att komprimera bilderna och ställa in deras kvalitet. För att aktivera bildkomprimering, sätt detta alternativ till true. Alla bilder i ett dokument kommer att komprimeras om. Komprimeringen definieras av ImageQuality property, som är värdet på kvaliteten i procent. 100 % är oförändrad kvalitet. För att minska bildkvaliteten, sätt ImageQuality property till mindre än 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  om bilder är komprimerade,  false  annars.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Ställer in om bilderna i PDF‑filen ska komprimeras.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| compressImages | boolean | true  för att komprimera bilderna,  false  annars. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Om käll-PDF-filen innehåller bilder, överväg att komprimera bilderna och ställa in deras kvalitet. För att aktivera bildkomprimering, sätt CompressImages alternativet till true. Alla bilder i ett dokument kommer att komprimeras om. Komprimeringen definieras av ImageQuality property, som är värdet på kvaliteten i procent. 100 % är oförändrad kvalitet. För att minska bildkvaliteten, sätt CompressImages alternativet till true och ImageQuality property till mindre än 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - bildkvaliteten (värde mellan 1 och 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Ställer in bildkvaliteten för komprimering av bilderna i PDF‑filen.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageQuality | int | bildkvaliteten (värde mellan 1 och 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Kan användas med CompressImages alternativet för att ändra storlek på bilderna med en lägre upplösning. I detta fall bör vi sätta CompressImage till true, ResizeImages till true och MaxResolution till lämpligt värde.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  om bilder har ändrats i storlek,  false  annars.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Ställer in om bilderna i PDF‑filen ska skalas om.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeImages | boolean | true  för att ändra storlek på bilderna,  false  annars. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Kan användas med CompressImages alternativet för att ändra storlek på bilderna med en lägre upplösning. I detta fall bör vi sätta CompressImage till true, ResizeImages till true och MaxResolution till lämpligt värde.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - den maximala upplösningen för bilderna.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Ställer in den maximala upplösningen för att ändra storlek på bilderna i PDF‑filen.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxResolution | int | den maximala upplösningen för bilderna. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimera Excel‑kalkylbladsramar och teckensnitt för mindre utdatafilstorlek.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  om kalkylblad är optimerade,  false  annars.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Ställer in om kalkylbladen i PDF‑filen ska optimeras.

För kodexempel, se denna [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  för att optimera kalkylbladen,  false  annars. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Ta bort privat information (sidinformation) om den är inställd på true.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  om privat information tas bort,  false  annars.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Ställer in om privat information ska tas bort från PDF‑filen.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removePrivateInfo | boolean | true  för att ta bort privat information,  false  annars. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Om dokumentet använder inbäddade teckensnitt betyder det att all teckensnittsdata placeras i dokumentet. Fördelen är att dokumentet kan visas oavsett om teckensnittet är installerat på användarens maskin eller inte. Men inbäddning av teckensnitt gör dokumentet större. Metoden unembed fonts tar bort alla inbäddade teckensnitt. Detta minskar dokumentets storlek men dokumentet kan bli oläsligt om rätt teckensnitt inte är installerat.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  om inbäddade teckensnitt har avbäddats,  false  annars.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Ställer in om de inbäddade teckensnitten i PDF‑filen ska avbäddas.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unembedFonts | boolean | true  för att avbädda de inbäddade teckensnitten,  false  annars. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Ibland innehåller ett dokument flera identiska resursströmmar (till exempel bilder). Detta kan hända till exempel när ett dokument konkateneras med sig självt. Utdata-dokumentet innehåller två oberoende kopior av samma resursström. Vi analyserar alla resursströmmar och jämför dem. Om strömmar är duplicerade slås de ihop, det vill säga att bara en kopia blir kvar, referenser ändras på lämpligt sätt och kopior av objektet tas bort. Ibland minskar detta dokumentets storlek.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  om duplicerade strömmar är länkade,  false  annars.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Ställer in om duplicerade strömmar i PDF‑filen ska länkas.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  för att länka duplicerade strömmar,  false  annars. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Om den här egenskapen är inställd på true kommer sidinnehållet att återanvändas när dokumentet optimeras för identiska sidor.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  om sidinnehåll återanvänds,  false  annars.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Ställer in om sidinnehållet får återanvändas i PDF:en.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| allowReusePageContent | boolean | true  för att tillåta återanvändning av sidinnehåll,  false  annars. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Ibland innehåller ett dokument oanvända resursströmmar. Dessa strömmar är inte \u201cunused objects\u201d eftersom de refereras från en sidas resursdictionary. Detta kan hända i fall där en bild har tagits bort från sidan men inte från sidans resurser. Dessutom uppstår denna situation ofta när sidor extraheras från dokumentet och dokumentsidor har \u201ccommon\u201d resurser, det vill säga samma Resources-objekt. Sidinnehåll analyseras för att avgöra om en resursström används eller inte. Oanvända strömmar tas bort. Ibland minskar detta dokumentets storlek.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  om oanvända strömmar tas bort,  false  annars.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Ställer in om oanvända strömmar ska tas bort från PDF:en.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  för att ta bort oanvända strömmar,  false  annars. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Ett PDF-dokument innehåller ibland PDF-objekt som inte refereras från något annat objekt i dokumentet. Detta kan hända, till exempel, när en sida tas bort från dokumentets sidträd men sidobjektet självt isn\u2019t tas bort. Att ta bort dessa objekt gör inte dokumentet ogiltigt utan minskar det istället.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  om oanvända objekt tas bort,  false  annars.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Ställer in om oanvända objekt ska tas bort från PDF:en.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  för att ta bort oanvända objekt,  false  annars. |

