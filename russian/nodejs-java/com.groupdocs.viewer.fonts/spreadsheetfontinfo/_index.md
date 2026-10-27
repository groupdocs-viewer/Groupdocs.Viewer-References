---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Инкапсулирует метаданные и бинарные данные одного шрифта из документа Spreadsheet, загруженного в экземпляр Viewer."
type: docs
weight: 16
url: /ru/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Инкапсулирует метаданные и бинарные данные одного шрифта из документа Spreadsheet, загруженного в экземпляр Viewer. Документы Spreadsheet не могут содержать встроенные шрифты, поэтому этот конкретный шрифт, если он возвращается методом Viewer.getAllFonts(), установлен в операционной системе, где работает GroupDocs.Viewer.
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Имя семейства шрифта без стиля, никогда не равно null и не пустое. |
| [getStyle()](#getStyle--) | Стиль этого шрифта — может быть Regular, Bold, Italic или BoldItalic. |
| [isStrikeout()](#isStrikeout--) | Указывает, имеет ли шрифт одиночное зачеркивание. |
| [isUnderline()](#isUnderline--) | Указывает, имеет ли шрифт подчеркивание. |
| [getColor()](#getColor--) | Цвет этого шрифта. |
| [getCharset()](#getCharset--) | Набор символов этого шрифта. |
| [getContent()](#getContent--) | Содержимое этого шрифта в виде массива байтов. |
| [getFormat()](#getFormat--) | Формат этого шрифта. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный writer. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Имя семейства шрифта без стиля, никогда не равно null и не пустое.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Стиль этого шрифта — может быть Regular, Bold, Italic или BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Указывает, имеет ли шрифт одиночное зачеркивание.

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
com.groupdocs.viewer.drawing.Argb32Color
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


Содержимое этого шрифта в виде массива байтов. Может быть null, если доступны только метаданные.

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


Сериализует информацию о шрифте как правило @font-face и записывает её в указанный writer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| вывод | java.io.Writer | Устройство для записи сериализованных текстовых данных. |

