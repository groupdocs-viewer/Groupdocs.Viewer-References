---
title: "Resolution"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет возможность установить разрешение для изображений выходного документа."
type: docs
weight: 44
url: /ru/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Предоставляет возможность установить разрешение для изображений : выходной документ.

## Поля

| Поле | Описание |
| --- | --- |
|  | [DPI_330](#DPI-330) | Хорошее качество для дисплеев высокой чёткости (HD). |
|
|  | [DPI_220](#DPI-220) | Отличное качество на большинстве принтеров и экранов. |
|
|  | [DPI_150](#DPI-150) | Подходит для веб-страниц и проекторов. |
|
|  | [DPI_96](#DPI-96) | Подходит для веб-страниц и проекторов. |
|
|  | [DPI_72](#DPI-72) | Уровень сжатия по умолчанию. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Уровень сжатия по умолчанию — как у документа. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | Качество DPI. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Получить разрешение изображений Aspose.Slides из класса параметров Resolution. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Хорошее качество для дисплеев высокой чёткости (HD).


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Отличное качество на большинстве принтеров и экранов.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Подходит для веб-страниц и проекторов.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Подходит для веб-страниц и проекторов.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Уровень сжатия по умолчанию.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Уровень сжатия по умолчанию — как у документа.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


Качество DPI.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Получить разрешение изображений Aspose.Slides из класса параметров Resolution.


**Returns:**
int
