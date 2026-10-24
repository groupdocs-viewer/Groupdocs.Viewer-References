---
title: "Auflösung"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Bietet die Möglichkeit, die Auflösung für Bilder im Ausgabedokument festzulegen."
type: docs
weight: 44
url: /de/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Bietet die Option, die Auflösung für Bilder festzulegen: Ausgabedokument.

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [DPI_330](#DPI-330) | Gute Qualität für hochauflösende (HD) Anzeigen. |
|
|  | [DPI_220](#DPI-220) | Ausgezeichnete Qualität auf den meisten Druckern und Bildschirmen. |
|
|  | [DPI_150](#DPI-150) | Gut für Webseiten und Projektoren. |
|
|  | [DPI_96](#DPI-96) | Gut für Webseiten und Projektoren. |
|
|  | [DPI_72](#DPI-72) | Standard-Komprimierungsstufe. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Standard-Komprimierungsstufe – wie im Dokument. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | Qualitäts‑DPI. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Abrufen der Auflösung von Aspose.Slides-Bildern aus der Optionsklasse Resolution. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Gute Qualität für hochauflösende (HD) Anzeigen.


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Ausgezeichnete Qualität auf den meisten Druckern und Bildschirmen.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Gut für Webseiten und Projektoren.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Gut für Webseiten und Projektoren.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Standard-Komprimierungsstufe.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Standard-Komprimierungsstufe – wie im Dokument.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


Qualitäts‑DPI.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Abrufen der Auflösung von Aspose.Slides-Bildern aus der Optionsklasse Resolution.


**Returns:**
int
