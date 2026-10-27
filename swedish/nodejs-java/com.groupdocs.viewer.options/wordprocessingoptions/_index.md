---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av ordbehandlingsdokument."
type: docs
weight: 38
url: /sv/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Tillhandahåller alternativ för rendering av ordbehandlingsdokument.

WordProcessingOptions-klassen tillhandahåller alternativ för rendering av ordbehandlingsdokument i GroupDocs.Viewer-komponenten. Den kapslar in inställningar och parametrar som kan användas för att styra renderingsprocessen och utdataformatet för ordbehandlingsfiler. För detaljer, se [documentation][].

Exempel på användning:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | Initierar en ny instans av WordProcessingOptions-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageSize()](#getPageSize--) | Hämtar sidstorleken för rendering av HTM- och HTML-filer. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Ställer in sidstorleken för rendering av HTM- och HTML-filer. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Anger om rendering av spårade ändringar (revisioner) är aktiverad. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Ställer in om rendering av spårade ändringar (revisioner) är aktiverad. |
| [getLeftMargin()](#getLeftMargin--) | Hämtar vänstermarginalen för HTML-rendering. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Ställer in vänstermarginalen för HTML-rendering. |
| [getRightMargin()](#getRightMargin--) | Hämtar högermarginalen för HTML-rendering. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Ställer in högermarginalen för HTML-rendering. |
| [getTopMargin()](#getTopMargin--) | Hämtar överstermarginalen för HTML-rendering. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Ställer in den övre sidmarginalen för HTML-rendering. |
| [getBottomMargin()](#getBottomMargin--) | Undermarginal (endast för HTML-rendering) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Ställer in undermarginalen för HTML-rendering. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Det här alternativet aktiverar kerning och andra OpenType-funktioner när man renderar arabiska, hebreiska, indiska skript, latinbaserade eller kyrilliska skript. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Det här alternativet aktiverar kerning och andra OpenType-funktioner när man renderar arabiska, hebreiska, indiska skript, latinbaserade eller kyrilliska skript. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Indikerar om navigering i innehållsförteckning ska inaktiveras vid rendering till HTML eller PDF. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Ställer in om navigering i innehållsförteckning ska inaktiveras vid rendering till HTML eller PDF. |
| [isUpdateFields()](#isUpdateFields--) | Hämtar ett värde som avgör om fält av vissa typer ska uppdateras innan det inmatade WordProcessing-dokumentet sparas till HTML-, PDF-, PNG- eller JPEG-utdataformat. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Ställer in ett värde som avgör om fält av vissa typer ska uppdateras innan det inmatade WordProcessing-dokumentet sparas till HTML-, PDF-, PNG- eller JPEG-utdataformat. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om alternativen har ändrats. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Initierar en ny instans av klassen  WordProcessingOptions . Innehåller alternativ för rendering av ordbehandlingsdokument. För detaljer, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Hämtar sidstorleken för rendering av HTM- och HTML-filer.

När standard sidstorlek används kan vissa innehåll inte få plats i sidramen. För att anpassa innehållet kan du ange en större sidstorlek, till exempel A3, med hjälp av [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Ställer in sidstorleken för rendering av HTM- och HTML-filer.

När standard sidstorlek används kan vissa innehåll inte få plats i sidramen. För att anpassa innehållet kan du ange en större sidstorlek, till exempel A3, med hjälp av [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Storleken på utskriftssidan. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Anger om rendering av spårade ändringar (revisioner) är aktiverad.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean -  true  om rendering av spårade ändringar är aktiverad,  false  annars.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Ställer in om rendering av spårade ändringar (revisioner) är aktiverad.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | true  för att aktivera rendering av spårade ändringar,  false  för att inaktivera den. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Hämtar vänstermarginalen för HTML-rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - värdet för vänster sidmarginal.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Ställer in vänstermarginalen för HTML-rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftMargin | java.lang.Double | Värdet för vänster sidmarginal att ange. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Hämtar högermarginalen för HTML-rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - värdet för höger sidmarginal.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Ställer in högermarginalen för HTML-rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rightMargin | java.lang.Double | Värdet för höger sidmarginal att ange. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Hämtar överstermarginalen för HTML-rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - värdet för övre sidmarginal.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Ställer in den övre sidmarginalen för HTML-rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| topMargin | java.lang.Double | Värdet för övre sidmarginal att ange. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Undermarginal (endast för HTML-rendering)

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - värdet för undre sidmarginal.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Ställer in undermarginalen för HTML-rendering.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bottomMargin | java.lang.Double | Värdet för undre sidmarginal att ange. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Det här alternativet aktiverar kerning och andra OpenType-funktioner när man renderar arabiska, hebreiska, indiska skript, latinbaserade eller kyrilliska skript.

**Returns:**
boolean - True om OpenType-funktioner är aktiverade, false annars.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Det här alternativet aktiverar kerning och andra OpenType-funktioner när man renderar arabiska, hebreiska, indiska skript, latinbaserade eller kyrilliska skript.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | Sant för att aktivera OpenType-funktioner, falskt annars. |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Indikerar om navigering i innehållsförteckning ska inaktiveras vid rendering till HTML eller PDF. När detta alternativ är satt till true, kommer relativa länkar från innehållsförteckningen vid HTML-rendering att ersättas med span-taggar, vilket tar bort funktionaliteten men bevarar det visuella utseendet. Vid PDF-rendering kommer innehållsförteckningen att renderas som vanlig text utan länkar.

**Returns:**
boolean - Sant om navigering i innehållsförteckning är inaktiverad; annars falskt.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Ställer in om navigering i innehållsförteckning ska inaktiveras vid rendering till HTML eller PDF. När detta alternativ är satt till true, kommer relativa länkar från innehållsförteckningen vid HTML-rendering att ersättas med span-taggar, vilket tar bort funktionaliteten men bevarar det visuella utseendet. Vid PDF-rendering kommer innehållsförteckningen att renderas som vanlig text utan länkar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unlinkTableOfContents | boolean | Indikerar om navigering i innehållsförteckning ska inaktiveras. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Hämtar ett värde som bestämmer om fält av vissa typer ska uppdateras innan det inmatade WordProcessing-dokumentet sparas till HTML-, PDF-, PNG- eller JPEG-utdataformaten. Standardvärdet för denna egenskap är true \\u2014 fält kommer att uppdateras innan sparning.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Ställer in ett värde som bestämmer om fält av vissa typer ska uppdateras innan det inmatade WordProcessing-dokumentet sparas till HTML-, PDF-, PNG- eller JPEG-utdataformaten. Standardvärdet för denna egenskap är true \\u2014 fält kommer att uppdateras innan sparning.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om alternativen har ändrats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Objektet att jämföra för likhet. |

**Returns:**
boolean -  true  om alternativen är lika med det angivna objektet,  false  annars.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Beräknar hashkodsvärdet för detta objekt. Hashkoden baseras på objektets interna tillstånd och används i hashbaserade datastrukturer såsom hash‑mappar och hash‑set.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - hashkodsvärdet för detta objekt.
