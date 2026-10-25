---
title: "SpreadsheetFontInfo"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Инкапсулирует метаинформацию и бинарные данные одного шрифта из документа Spreadsheet, загруженного в экземпляр Viewer."
type: docs
weight: 16
url: /ru/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Инкапсулирует метаинформацию и бинарные данные одного шрифта из документа Spreadsheet, загруженного в экземпляр Viewer. Документы Spreadsheet не могут содержать встроенные шрифты, поэтому этот конкретный шрифт, если он возвращён методом Viewer.getAllFonts(), установлен в операционной системе, где работает GroupDocs.Viewer.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Семейное имя шрифта без стиля, никогда не null и не пустое. |
|
|  | [getStyle()](#getStyle--) | Стиль этого шрифта \\u2014 может быть Regular, Bold, Italic или BoldItalic. |
|
|  | [isStrikeout()](#isStrikeout--) | Указывает, является ли шрифт одинарным зачеркиванием. |
|
|  | [isUnderline()](#isUnderline--) | Указывает, имеет ли шрифт подчеркивание. |
|
|  | [getColor()](#getColor--) | Цвет этого шрифта. |
|
|  | [getCharset()](#getCharset--) | Набор символов этого шрифта. |
|
|  | [getContent()](#getContent--) | Содержимое этого шрифта в виде массива байтов. |
|
|  | [getFormat()](#getFormat--) | Формат этого шрифта. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Сериализует информацию о шрифте как правило @font-face at-rule и записывает её в указанный writer. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Семейное имя шрифта без стиля, никогда не null и не пустое.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Стиль этого шрифта \\u2014 может быть Regular, Bold, Italic или BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Указывает, является ли шрифт одинарным зачеркиванием.


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Указывает, имеет ли шрифт подчеркивание.


**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Цвет этого шрифта.


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


Набор символов этого шрифта.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Содержимое этого шрифта в виде массива байтов. Может быть null, если доступна только метаинформация.


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Формат этого шрифта.


**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Сериализует информацию о шрифте как правило @font-face at-rule и записывает её в указанный writer.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | output | java.io.Writer | Устройство для записи сериализованных текстовых данных. |
|

