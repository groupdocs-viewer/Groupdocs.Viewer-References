---
title: "FontFormat"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет все форматы шрифтов, которые могут присутствовать в классе UsedFontInfo."
type: docs
weight: 11
url: /ru/java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Представляет все форматы шрифтов, которые могут присутствовать в классе UsedFontInfo.

## Поля

| Поле | Описание |
| --- | --- |
|  | [Unknown](#Unknown) | Неизвестный или недействительный формат шрифта. |
|
|  | [TrueType](#TrueType) | Формат шрифта TrueType (TTF). |
|
|  | [OpenType](#OpenType) | Формат шрифта OpenType (OTF). |
|
|  | [TrueTypeCollection](#TrueTypeCollection) | Формат коллекции шрифтов TrueType (TTC). |
|
|  | [EmbeddedOpenType](#EmbeddedOpenType) | Встроенный формат шрифта OpenType (EOT). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [toString(int format)](#toString-int-) | Преобразует значение формата в человекочитаемую строку. |
|
### Unknown {#Unknown}
```
public static final int Unknown
```


Неизвестный или недействительный формат шрифта.


### TrueType {#TrueType}
```
public static final int TrueType
```


Формат шрифта TrueType (TTF).


### OpenType {#OpenType}
```
public static final int OpenType
```


Формат шрифта OpenType (OTF).


### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


Формат коллекции шрифтов TrueType (TTC).


### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Встроенный формат шрифта OpenType (EOT).


### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Преобразует значение формата в человекочитаемую строку.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | формат | int | значение формата шрифта |
|

**Returns:**
java.lang.String — строковое представление формата шрифта

