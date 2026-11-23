---
title: "Resolution"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona una opción para establecer la resolución de las imágenes del documento de salida."
type: docs
weight: 44
url: /es/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Proporciona una opción para establecer la resolución de las imágenes: documento de salida.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [DPI_330](#DPI-330) | Buena calidad para pantallas de alta definición (HD). |
|
|  | [DPI_220](#DPI-220) | Excelente calidad en la mayoría de impresoras y pantallas. |
|
|  | [DPI_150](#DPI-150) | Adecuado para páginas web y proyectores. |
|
|  | [DPI_96](#DPI-96) | Adecuado para páginas web y proyectores. |
|
|  | [DPI_72](#DPI-72) | Nivel de compresión predeterminado. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Nivel de compresión predeterminado - como el documento. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | DPI de calidad. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Obtenga la resolución de las imágenes de Aspose.Slides desde la clase Resolution de opciones. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Buena calidad para pantallas de alta definición (HD).


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Excelente calidad en la mayoría de impresoras y pantallas.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Adecuado para páginas web y proyectores.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Adecuado para páginas web y proyectores.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Nivel de compresión predeterminado.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Nivel de compresión predeterminado - como el documento.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


DPI de calidad.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Obtenga la resolución de las imágenes de Aspose.Slides desde la clase Resolution de opciones.


**Returns:**
int
