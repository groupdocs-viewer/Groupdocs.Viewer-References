---
title: "Resolution"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller ett alternativ för att ställa in upplösning för bilder i utdata-dokumentet."
type: docs
weight: 44
url: /sv/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Tillhandahåller alternativ för att ange upplösning för bilder : utdata-dokument.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [DPI_330](#DPI-330) | Bra kvalitet för högupplösta (HD) skärmar. |
|
|  | [DPI_220](#DPI-220) | Utmärkt kvalitet på de flesta skrivare och skärmar. |
|
|  | [DPI_150](#DPI-150) | Bra för webbsidor och projektorer. |
|
|  | [DPI_96](#DPI-96) | Bra för webbsidor och projektorer. |
|
|  | [DPI_72](#DPI-72) | Standardkomprimeringsnivå. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Standardkomprimeringsnivå – som dokumentet. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | Kvalitet DPI. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Hämta Aspose.Slides-bilders upplösning från alternativklassen Resolution. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Bra kvalitet för högupplösta (HD) skärmar.


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Utmärkt kvalitet på de flesta skrivare och skärmar.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Bra för webbsidor och projektorer.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Bra för webbsidor och projektorer.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Standardkomprimeringsnivå.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Standardkomprimeringsnivå – som dokumentet.


### values() {#values--}
```
public static Resolution[] values()
```




**Returns:**
com.groupdocs.viewer.options.Resolution[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Resolution valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


Kvalitet DPI.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Hämta Aspose.Slides-bilders upplösning från alternativklassen Resolution.


**Returns:**
int
