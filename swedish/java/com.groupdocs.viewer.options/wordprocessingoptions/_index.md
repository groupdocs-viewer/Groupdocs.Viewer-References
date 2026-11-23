---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för rendering av ordbehandlingsdokument."
type: docs
weight: 38
url: /sv/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Tillhandahåller alternativ för rendering av ordbehandlingsdokument.


WordProcessingOptions‑klassen tillhandahåller alternativ för rendering av ordbehandlingsdokument
i GroupDocs.Viewer-komponenten. Den kapslar in inställningar och parametrar som kan användas
för att kontrollera renderingsprocessen och utdataformatet för ordbehandlingsfiler.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


Exempel på användning:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Initierar en ny instans av |
WordProcessingOptions
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Hämtar sidstorleken för rendering av HTM‑ och HTML‑filer. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Ställer in sidstorleken för rendering av HTM‑ och HTML‑filer. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Indikerar om rendering av spårade ändringar (revisioner) är aktiverad. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Ställer in om rendering av spårade ändringar (revisioner) är aktiverad. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Hämtar vänstermarginalen för HTML‑rendering. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Ställer in vänstermarginalen för HTML‑rendering. |
|
|  | [getRightMargin()](#getRightMargin--) | Hämtar högermarginalen för HTML‑rendering. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Ställer in högermarginalen för HTML-rendering. |
|
|  | [getTopMargin()](#getTopMargin--) | Hämtar översta sidmarginalen för HTML-rendering. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Ställer in översta sidmarginalen för HTML-rendering. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Undermarginal (endast för HTML-rendering) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Ställer in undermarginalen för HTML-rendering. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Detta alternativ aktiverar kerning och andra OpenType-funktioner när man renderar arabiska, hebreiska, indiska skript, latinbaserade eller kyrilliska skript. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Detta alternativ aktiverar kerning och andra OpenType-funktioner när man renderar arabiska, hebreiska, indiska skript, latinbaserade eller kyrilliska skript. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Anger om innehållsförteckningens navigering ska inaktiveras vid rendering till HTML eller PDF. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Ställer in om innehållsförteckningens navigering ska inaktiveras vid rendering till HTML eller PDF. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Hämtar ett värde som bestämmer om fält av vissa typer ska uppdateras innan det inmatade WordProcessing-dokumentet sparas till HTML-, PDF-, PNG- eller JPEG-utdataformat. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Ställer in ett värde som bestämmer om fält av vissa typer ska uppdateras innan det inmatade WordProcessing-dokumentet sparas till HTML-, PDF-, PNG- eller JPEG-utdataformat. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Hämtar den horisontella upplösningen för genererade bilder i punkter per tum. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Ställer in den horisontella upplösningen för genererade bilder i punkter per tum. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Hämtar den vertikala upplösningen för genererade bilder i punkter per tum. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Ställer in den vertikala upplösningen för genererade bilder i punkter per tum. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Tillåter att tvinga på sidnumrering för det inlästa WordProcessing-dokumentet. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Tillåter att tvinga på sidnumrering för det inlästa WordProcessing-dokumentet. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om alternativen har ändrats. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Initierar en ny instans av
WordProcessingOptions
klassen.
Innehåller alternativ för rendering av ordbehandlingsdokument. För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Hämtar sidstorleken för rendering av HTM‑ och HTML‑filer.


När standard sidstorlek används kan en del innehåll inte få plats i sidramen.
För att få plats med innehållet kan du ange en större sidstorlek, till exempel A3, med hjälp av [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Ställer in sidstorleken för rendering av HTM‑ och HTML‑filer.


När standard sidstorlek används kan en del innehåll inte få plats i sidramen.
För att få plats med innehållet kan du ange en större sidstorlek, till exempel A3, med hjälp av [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Storleken på utskriftsidan. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Indikerar om rendering av spårade ändringar (revisioner) är aktiverad.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
boolean -  true  om rendering av spårade ändringar är aktiverad,  false  annars.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Ställer in om rendering av spårade ändringar (revisioner) är aktiverad.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | boolean | true  för att aktivera rendering av spårade ändringar,  false  för att inaktivera den. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Hämtar vänstermarginalen för HTML‑rendering.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - värdet för vänstermarginalen.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Ställer in vänstermarginalen för HTML‑rendering.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | Värdet för vänstermarginalen att ange. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Hämtar högermarginalen för HTML‑rendering.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - det högra sidmarginalvärdet.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Ställer in högermarginalen för HTML-rendering.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | Det högra sidmarginalvärdet att sätta. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Hämtar översta sidmarginalen för HTML-rendering.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - den övre sidmarginalen.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Ställer in översta sidmarginalen för HTML-rendering.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | topMargin | java.lang.Double | Den övre sidmarginalen att sätta. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Undermarginal (endast för HTML-rendering)
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - den nedre sidmarginalen.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Ställer in undermarginalen för HTML-rendering.
För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | Den nedre sidmarginalen att sätta. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Detta alternativ aktiverar kerning och andra OpenType-funktioner när man renderar arabiska, hebreiska, indiska skript, latinbaserade eller kyrilliska skript.


**Returns:**
boolean - Sant om OpenType-funktioner är aktiverade, falskt annars.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Detta alternativ aktiverar kerning och andra OpenType-funktioner när man renderar arabiska, hebreiska, indiska skript, latinbaserade eller kyrilliska skript.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | Sant för att aktivera OpenType-funktioner, falskt annars. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Indikerar om navigering i innehållsförteckning ska inaktiveras vid rendering till HTML eller PDF. När detta alternativ är satt till sant, kommer relativa länkar från innehållsförteckningen vid HTML-rendering att ersättas med span-taggar, vilket tar bort funktionaliteten men bevarar det visuella utseendet. Vid PDF-rendering kommer innehållsförteckningen att renderas som vanlig text utan länkar.


**Returns:**
boolean - Sant om navigering i innehållsförteckning är inaktiverad; annars falskt.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Sätter om navigering i innehållsförteckning ska inaktiveras vid rendering till HTML eller PDF. När detta alternativ är satt till sant, kommer relativa länkar från innehållsförteckningen vid HTML-rendering att ersättas med span-taggar, vilket tar bort funktionaliteten men bevarar det visuella utseendet. Vid PDF-rendering kommer innehållsförteckningen att renderas som vanlig text utan länkar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | Indikerar om navigering i innehållsförteckning ska inaktiveras. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Hämtar ett värde som bestämmer om fält av vissa typer ska uppdateras innan den inmatade WordProcessing-dokumentet sparas till HTML, PDF, PNG eller JPEG-utdataformat. Standardvärdet för denna egenskap är sant \\u2014 fält kommer att uppdateras innan sparning.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Sätter ett värde som bestämmer om fält av vissa typer ska uppdateras innan den inmatade WordProcessing-dokumentet sparas till HTML, PDF, PNG eller JPEG-utdataformat. Standardvärdet för denna egenskap är sant \\u2014 fält kommer att uppdateras innan sparning.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Hämtar den horisontella upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av WordProcessing-dokument till PNG- eller JPEG-format.


Standardvärdet är 96 DPI. Minsta möjliga värde – 72 DPI, största möjliga värde – 600 DPI.
Om det användarspecificerade värdet ligger utanför dessa gränser kommer det minsta eller största möjliga värdet att tillämpas.


**Returns:**
int – den horisontella upplösningen i DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Sätter den horisontella upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av WordProcessing-dokument till PNG- eller JPEG-format.


Standardvärdet är 96 DPI. Minsta möjliga värde – 72 DPI, största möjliga värde – 600 DPI.
Om det användarspecificerade värdet ligger utanför dessa gränser kommer det minsta eller största möjliga värdet att tillämpas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | horizontalResolution | int | den horisontella upplösningen i DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Hämtar den vertikala upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av WordProcessing-dokument till PNG- eller JPEG-format.


Standardvärdet är 96 DPI. Minsta möjliga värde – 72 DPI, största möjliga värde – 600 DPI.
Om det användarspecificerade värdet ligger utanför dessa gränser kommer det minsta eller största möjliga värdet att tillämpas.


**Returns:**
int – den vertikala upplösningen i DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Sätter den vertikala upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av WordProcessing-dokument till PNG- eller JPEG-format.


Standardvärdet är 96 DPI. Minsta möjliga värde – 72 DPI, största möjliga värde – 600 DPI.
Om det användarspecificerade värdet ligger utanför dessa gränser kommer det minsta eller största möjliga värdet att tillämpas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | verticalResolution | int | den vertikala upplösningen i DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Tillåter att tvinga på sidnumrering för det inlästa WordProcessing-dokumentet. Som standard är [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APP) \\u2014 dokumentet är intakt.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Tillåter att tvinga på sidnumrering för det inlästa WordProcessing-dokumentet. Som standard är [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APP) \\u2014 dokumentet är intakt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | sidnumreringsplatsen. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om alternativen har ändrats.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | o | java.lang.Object | Objektet att jämföra för likhet. |
|

**Returns:**
boolean -  true  om alternativen är lika med det angivna objektet,  false  annars.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Beräknar hashkodsvärdet för detta objekt. Hashkoden baseras på
objektets interna tillstånd och används i hashbaserade datastrukturer
såsom hash‑kartor och hash‑uppsättningar.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - hashkodsvärdet för detta objekt.

