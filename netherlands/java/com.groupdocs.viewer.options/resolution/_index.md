---
title: "Resolution"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt een optie om de resolutie voor afbeeldingen in het uitvoerdocument in te stellen."
type: docs
weight: 44
url: /nl/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Biedt een optie om de resolutie voor afbeeldingen in te stellen: uitvoerdocument.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [DPI_330](#DPI-330) | Goede kwaliteit voor high-definition (HD) displays. |
|
|  | [DPI_220](#DPI-220) | Uitstekende kwaliteit op de meeste printers en schermen. |
|
|  | [DPI_150](#DPI-150) | Goed voor webpagina's en projectoren. |
|
|  | [DPI_96](#DPI-96) | Goed voor webpagina's en projectoren. |
|
|  | [DPI_72](#DPI-72) | Standaard compressieniveau. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Standaard compressieniveau - zoals het document. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | Kwaliteit DPI. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Haal de resolutie van Aspose.Slides-afbeeldingen op uit de opties van de Resolution-klasse. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Goede kwaliteit voor high-definition (HD) displays.


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Uitstekende kwaliteit op de meeste printers en schermen.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Goed voor webpagina's en projectoren.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Goed voor webpagina's en projectoren.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Standaard compressieniveau.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Standaard compressieniveau - zoals het document.


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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


Kwaliteit DPI.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Haal de resolutie van Aspose.Slides-afbeeldingen op uit de opties van de Resolution-klasse.


**Returns:**
int
