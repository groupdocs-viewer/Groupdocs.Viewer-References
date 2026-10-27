---
title: "FontFormat"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет все форматы шрифтов, которые могут присутствовать в классе UsedFontInfo."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
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
| [Unknown](#Unknown) | Неизвестный или недействительный формат шрифта. |
| [TrueType](#TrueType) | Формат шрифта TrueType (TTF). |
| [OpenType](#OpenType) | Формат шрифта OpenType (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | Формат шрифта TrueType Collection (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Формат встроенного OpenType (EOT). |
## Методы

| Метод | Описание |
| --- | --- |
| [toString(int format)](#toString-int-) | Преобразует значение формата в человекочитаемую строку. |
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


Формат шрифта TrueType Collection (TTC).

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Формат встроенного OpenType (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Преобразует значение формата в человекочитаемую строку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | int | значение формата шрифта |

**Returns:**
java.lang.String — строковое представление формата шрифта
