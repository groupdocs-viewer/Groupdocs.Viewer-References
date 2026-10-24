---
title: "Resolution"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce l'opzione per impostare la risoluzione per le immagini del documento di output."
type: docs
weight: 44
url: /it/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Fornisce l'opzione per impostare la risoluzione delle immagini : documento di output.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [DPI_330](#DPI-330) | Buona qualità per display ad alta definizione (HD). |
|
|  | [DPI_220](#DPI-220) | Qualità eccellente sulla maggior parte delle stampanti e degli schermi. |
|
|  | [DPI_150](#DPI-150) | Buono per pagine web e proiettori. |
|
|  | [DPI_96](#DPI-96) | Buono per pagine web e proiettori. |
|
|  | [DPI_72](#DPI-72) | Livello di compressione predefinito. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Livello di compressione predefinito - come il documento. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | DPI di qualità. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Ottieni la risoluzione delle immagini Aspose.Slides dalle opzioni della classe Resolution. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Buona qualità per display ad alta definizione (HD).


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Qualità eccellente sulla maggior parte delle stampanti e degli schermi.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Buono per pagine web e proiettori.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Buono per pagine web e proiettori.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Livello di compressione predefinito.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Livello di compressione predefinito - come il documento.


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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


DPI di qualità.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Ottieni la risoluzione delle immagini Aspose.Slides dalle opzioni della classe Resolution.


**Returns:**
int
