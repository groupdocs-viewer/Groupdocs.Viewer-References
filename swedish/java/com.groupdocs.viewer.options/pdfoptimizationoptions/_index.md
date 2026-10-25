---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Använd den här klassen för att ange PDF-optimeringsalternativ som ska tillämpas på den genererade PDF-filen."
type: docs
weight: 21
url: /sv/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Använd den här klassen för att ange PDF-optimeringsalternativ som ska tillämpas på den genererade PDF-filen.


Dessa optimeringsalternativ stöds för alla inmatningsfilformat som stöds för export till PDF.
För detaljer och kodexempel, se denna [sida](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) och dess underordnade.


Exempel på användning:

````

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
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Ställer in standardvärden för MaxResolution-alternativet till 300 och ImageQuality-alternativet till 100. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Aktiverar optimering av den genererade PDF-filen för visning online i en webbläsare. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Ställer in om PDF-filen ska optimeras för onlinebläddring i en webbläsare. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | Anmärkningar kan tas bort när de är onödiga. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Ställer in om onödiga anmärkningar ska tas bort från PDF-filen. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | Om PDF-dokumentet innehåller AcroForms kan vi försöka minska filstorleken genom att platta till formulärfält. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Ställer in om formulärfält ska tas bort från PDF-filen. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF-filen består av Text, Bild, Bilaga, Anmärkningar, Grafer och andra objekt. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Ställer in om PDF-filen ska konverteras till gråskala. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | Varje teckensnitt som används för att visa text på sidan innehåller en uppsättning glyfer för teckensnittets tecken. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Ställer in om teckensnitten i PDF-filen ska delmängdas. |
|
|  | [isCompressImages()](#isCompressImages--) | Om käll-PDF-filen innehåller bilder, överväg att komprimera bilderna och ställa in deras kvalitet. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Ställer in om bilderna i PDF-filen ska komprimeras. |
|
|  | [getImageQuality()](#getImageQuality--) | Om käll-PDF-filen innehåller bilder, överväg att komprimera bilderna och ställa in deras kvalitet. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | Ställer in bildkvaliteten för komprimering av bilderna i PDF-filen. |
|
|  | [isResizeImages()](#isResizeImages--) | Kan användas med CompressImages-alternativet för att ändra storlek på bilderna med en lägre upplösning. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Anger om bilderna i PDF-filen ska skalas om. |
|
|  | [getMaxResolution()](#getMaxResolution--) | Kan användas med CompressImages-alternativet för att ändra storlek på bilderna med en lägre upplösning. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Anger den maximala upplösningen för att skala om bilderna i PDF-filen. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimera Excel-kalkylblads kantlinjer och teckensnitt för en mindre utdatafilstorlek. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Anger om kalkylbladen i PDF-filen ska optimeras. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Ta bort privat information (sidinformation) om den är satt till true. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Anger om privat information ska tas bort från PDF-filen. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | Om dokumentet använder inbäddade teckensnitt betyder det att all teckensnittsdata placeras i dokumentet. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Anger om de inbäddade teckensnitten i PDF-filen ska avbäddas. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Ibland innehåller ett dokument flera identiska resursströmmar (till exempel bilder). |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Anger om dubblettströmmar i PDF-filen ska länkas. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | Om den här egenskapen är satt till true kommer sidinnehållet att återanvändas när dokumentet optimeras för identiska sidor. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Anger om återanvändning av sidinnehåll i PDF-filen ska tillåtas. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Ibland innehåller ett dokument oanvända resursströmmar. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Anger om oanvända strömmar ska tas bort från PDF-filen. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | Ett PDF-dokument innehåller ibland PDF-objekt som inte refereras |
från något annat objekt i dokumentet.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Anger om oanvända objekt ska tas bort från PDF-filen. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Ställer in standardvärden för MaxResolution-alternativet till 300 och ImageQuality-alternativet till 100.


För detaljer och kodexempel, se denna [sida](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) och dess underordnade.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Aktiverar optimering av den genererade PDF-filen för visning online i en webbläsare.


För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Returns:**
boolean -  true  om den genererade PDF-filen är optimerad för online‑visning,  false  annars.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Ställer in om PDF-filen ska optimeras för onlinebläddring i en webbläsare.


För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | linearize | boolean | true  för att optimera den genererade PDF-filen för online‑visning,  false  annars. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Anmärkningar kan tas bort när de är onödiga. När de behövs men inte kräver ytterligare redigering kan de plattas ut. Detta minskar filstorleken.


***Note:** The default value is 
false
.*
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Returns:**
boolean -  true  om anmärkningar tas bort,  false  annars.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Ställer in om onödiga anmärkningar ska tas bort från PDF-filen.


***Note:** The default value is 
false
.*
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  för att ta bort onödiga annoteringar,  false  annars. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Om PDF-dokumentet innehåller AcroForms kan vi försöka minska filstorleken genom att platta till formulärfält.


***Note:** The default value is 
false
.*
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
boolean -  true  om formulärfält tas bort,  false  annars.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Ställer in om formulärfält ska tas bort från PDF-filen.


***Note:** The default value is 
false
.*
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | removeFormFields | boolean | true  för att ta bort formulärfält,  false  annars. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF-filen består av Text, Bild, Bilaga, Anmärkningar, Grafer och andra objekt.
Du kan stöta på ett krav att konvertera en PDF från RGB-färgrymd till gråskala så att den blir snabbare vid utskrift av dessa PDF-filer.
När filen också konverteras till gråskala minskar dokumentets storlek, men med denna förändring kan dokumentets kvalitet försämras.
För närvarande stöds denna funktion av Pre-Flight-funktionen i Adobe Acrobat.


***Note:** The default value is 
false
.*
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
boolean -  true  om PDF:en konverteras till gråskala,  false  annars.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Ställer in om PDF-filen ska konverteras till gråskala.


***Note:** The default value is 
false
.*
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  för att konvertera PDF:en till gråskala,  false  annars. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Varje teckensnitt som används för att visa text på sidan innehåller en uppsättning glyfer för teckensnittets tecken.
PDF-specifikationen stödjer "font subset", d.v.s. ett typsnitt med endast de glyfer som används.
Detta kan orsaka problem när text ska uppdateras (eftersom de nödvändiga glyferna sannolikt saknas i typsnittet), men för dokument som inte planeras att ändras möjliggör detta en minskning av storleken.


***Note:** The default value is 
false
.*
Om filen använder inbäddade typsnitt innehåller den all typsnittsdata. GroupDocs.Viewer kan skapa delmängder av inbäddade typsnitt för att minska filstorleken. För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
boolean -  true  om typsnitt har delmängdsats,  false  annars.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Ställer in om teckensnitten i PDF-filen ska delmängdas.


***Note:** The default value is 
false
.*
Om filen använder inbäddade typsnitt innehåller den all typsnittsdata. GroupDocs.Viewer kan skapa delmängder av inbäddade typsnitt för att minska filstorleken. För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | subsetFonts | boolean | true  för att skapa delmängd av typsnitten,  false  annars. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Om käll-PDF-filen innehåller bilder, överväg att komprimera bilderna och ställa in deras kvalitet.
För att aktivera bildkomprimering, sätt detta alternativ till true. Alla bilder i ett dokument kommer att komprimeras om.
Komprimeringen definieras av egenskapen ImageQuality, som är värdet för kvaliteten i procent.
100% är oförändrad kvalitet. För att minska bildkvaliteten, sätt egenskapen ImageQuality till mindre än 100.


***Note:** The default value is 
false
.*
Använd detta alternativ för att möjliggöra andra komprimeringsalternativ: #setImageQuality(int).setImageQuality(int) och . För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
boolean -  true  om bilder komprimeras,  false  annars.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Ställer in om bilderna i PDF-filen ska komprimeras.


***Note:** The default value is 
false
.*
Använd detta alternativ för att möjliggöra andra komprimeringsalternativ: #setImageQuality(int).setImageQuality(int) och . För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | compressImages | boolean | true  för att komprimera bilderna,  false  annars. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Om käll-PDF-filen innehåller bilder, överväg att komprimera bilderna och ställa in deras kvalitet. För att aktivera bildkomprimering, sätt CompressImages-alternativet till true. Alla bilder i ett dokument kommer att komprimeras om. Komprimeringen definieras av ImageQuality-egenskapen, som är värdet på kvaliteten i procent. 100 % är oförändrad kvalitet. För att minska bildkvaliteten, sätt CompressImages-alternativet till true och ImageQuality-egenskapen till mindre än 100.

<br />


***Note:** The default value is 
100
.*
För att ändra bildkvaliteten, sätt först #setCompressImages(boolean).setCompressImages(boolean)-egenskapen till true. För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
int - bildkvaliteten (värde mellan 1 och 100).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Ställer in bildkvaliteten för komprimering av bilderna i PDF-filen.


***Note:** The default value is 
100
.*
För att ändra bildkvaliteten, sätt först #setCompressImages(boolean).setCompressImages(boolean)-egenskapen till true. För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | imageQuality | int | bildkvaliteten (värde mellan 1 och 100). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Kan användas med CompressImages-alternativet för att ändra storlek på bilderna med en lägre upplösning.
I det här fallet bör vi sätta CompressImage till true, ResizeImages till true och MaxResolution till lämpligt värde.


***Note:** The default value is 
false
.*
För att möjliggöra detta alternativ, sätt egenskapen till true. Detta alternativ tillåter att sätta egenskapen. För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
boolean -  true  om bilder har ändrats i storlek,  false  annars.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Anger om bilderna i PDF-filen ska skalas om.


***Note:** The default value is 
false
.*
För att möjliggöra detta alternativ, sätt egenskapen till true. Detta alternativ tillåter att sätta egenskapen. För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | resizeImages | boolean | true  för att ändra storlek på bilderna,  false  annars. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Kan användas med CompressImages-alternativet för att ändra storlek på bilderna med en lägre upplösning. I det här fallet bör vi sätta CompressImage till true, ResizeImages till true och MaxResolution till lämpligt värde.


***Note:** The default value is 
300
.*
För att möjliggöra detta alternativ, sätt #setCompressImages(boolean).setCompressImages(boolean)- och #setMaxResolution(int).setMaxResolution(int)-egenskaperna till true.
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
int - den maximala upplösningen för bilderna.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Anger den maximala upplösningen för att skala om bilderna i PDF-filen.


***Note:** The default value is 
300
.*
För att möjliggöra detta alternativ, sätt #setCompressImages(boolean).setCompressImages(boolean)- och #setMaxResolution(int).setMaxResolution(int)-egenskaperna till true.
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxResolution | int | den maximala upplösningen för bilderna. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimera Excel-kalkylblads kantlinjer och teckensnitt för en mindre utdatafilstorlek.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Returns:**
boolean -  true  om kalkylblad är optimerade,  false  annars.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Anger om kalkylbladen i PDF-filen ska optimeras.


För kodexempel, se denna [dokumentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  för att optimera kalkylbladen,  false  annars. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Ta bort privat information (sidinformation) om den är satt till true.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  om privat information tas bort,  false  annars.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Anger om privat information ska tas bort från PDF-filen.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  för att ta bort privat information,  false  annars. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Om dokumentet använder inbäddade teckensnitt betyder det att all teckensnittsdata placeras i dokumentet.
Fördelen är att dokumentet kan visas oavsett om teckensnittet är installerat på användarens maskin eller inte. Men inbäddning av teckensnitt gör dokumentet större.
Metoden för att avbädda teckensnitt tar bort alla inbäddade teckensnitt. Detta minskar dokumentets storlek men dokumentet kan bli oläsligt om rätt teckensnitt inte är installerat.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  om inbäddade teckensnitt avbäddas,  false  annars.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Anger om de inbäddade teckensnitten i PDF-filen ska avbäddas.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | unembedFonts | boolean | true  för att avbädda de inbäddade teckensnitten,  false  annars. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Ibland innehåller ett dokument flera identiska resursströmmar (till exempel bilder).
Detta kan till exempel inträffa när ett dokument sammanfogas med sig självt.
Utdatadokumentet innehåller två oberoende kopior av samma resursström.
Vi analyserar alla resursströmmar och jämför dem. Om strömmar är duplicerade slås de ihop, det vill säga att endast en kopia blir kvar, referenser ändras på lämpligt sätt och kopior av objektet tas bort.
Ibland minskar detta dokumentets storlek.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  om duplicerade strömmar länkas,  false  annars.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Anger om dubblettströmmar i PDF-filen ska länkas.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  för att länka duplicerade strömmar,  false  annars. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Om den här egenskapen är satt till true kommer sidinnehållet att återanvändas när dokumentet optimeras för identiska sidor.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  om sidinnehåll återanvänds,  false  annars.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Anger om återanvändning av sidinnehåll i PDF-filen ska tillåtas.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  för att tillåta återanvändning av sidinnehåll,  false  annars. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Ibland innehåller ett dokument oanvända resursströmmar.
Dessa strömmar är inte \u201coanvända objekt\u201d eftersom de refereras från en sidans resursordbok.
Detta kan inträffa i fall där en bild har tagits bort från sidan men inte från sidans resurser.
Dessutom uppstår denna situation ofta när sidor extraheras från dokumentet och dokumentsidor har \u201cgemensamma\u201d resurser,
det vill säga samma Resources-objekt. Sidinnehåll analyseras för att avgöra om en resursström
används eller inte. Oanvända strömmar tas bort. Ibland minskar detta dokumentets storlek.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  om oanvända strömmar tas bort,  false  annars.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Anger om oanvända strömmar ska tas bort från PDF-filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  för att ta bort oanvända strömmar,  false  annars. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


Ett PDF-dokument innehåller ibland PDF-objekt som inte refereras
från något annat objekt i dokumentet. Detta kan till exempel inträffa,
när en sida tas bort från dokumentets sidträd men sidobjektet självt inte tas bort.
Att ta bort dessa objekt gör inte dokumentet ogiltigt utan minskar det istället.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  om oanvända objekt tas bort,  false  annars.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Anger om oanvända objekt ska tas bort från PDF-filen.


***Note:** The default value is 
false
.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  för att ta bort oanvända objekt,  false  annars. |
|

