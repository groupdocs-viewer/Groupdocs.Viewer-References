---
title: "Resolution"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit une option pour définir la résolution des images du document de sortie."
type: docs
weight: 44
url: /fr/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Fournit une option pour définir la résolution des images du document de sortie.

## Champs

| Champ | Description |
| --- | --- |
|  | [DPI_330](#DPI-330) | Bonne qualité pour les écrans haute définition (HD). |
|
|  | [DPI_220](#DPI-220) | Excellente qualité sur la plupart des imprimantes et écrans. |
|
|  | [DPI_150](#DPI-150) | Bon pour les pages web et les projecteurs. |
|
|  | [DPI_96](#DPI-96) | Bon pour les pages web et les projecteurs. |
|
|  | [DPI_72](#DPI-72) | Niveau de compression par défaut. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Niveau de compression par défaut - comme le document. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | DPI de qualité. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Obtenez la résolution des images Aspose.Slides à partir de la classe d'options Resolution. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Bonne qualité pour les écrans haute définition (HD).


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Excellente qualité sur la plupart des imprimantes et écrans.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Bon pour les pages web et les projecteurs.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Bon pour les pages web et les projecteurs.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Niveau de compression par défaut.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Niveau de compression par défaut - comme le document.


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


DPI de qualité.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Obtenez la résolution des images Aspose.Slides à partir de la classe d'options Resolution.


**Returns:**
int
