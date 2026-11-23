---
title: "KnownColors"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: 
type: docs
weight: 10
url: /ru/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Методы

| Метод | Описание |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Пытается найти цвет по его строковому имени. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Пытается найти название цвета по его RGB‑значению. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Пытается найти цвет по его строковому имени.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | ключевое слово | java.lang.String | Название цвета. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | Контейнер результата для найденного цвета, или CssLevel1.Black в случае неудачи. |
|

**Returns:**
boolean — True, если цвет был успешно найден по имени, иначе false.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Пытается найти название цвета по его RGB‑значению.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Экземпляр цвета. |
|
|  | имя | java.lang.String[] | Контейнер результата для найденного названия цвета, или null в случае неудачи. |
|

**Returns:**
boolean — True, если название было успешно найдено для данного цвета, иначе false.

