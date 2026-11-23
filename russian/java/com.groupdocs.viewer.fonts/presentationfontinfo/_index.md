---
title: "PresentationFontInfo"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Инкапсулирует метаданные и бинарные данные шрифта, используемого в документе Presentation, загруженном в экземпляр Viewer."
type: docs
weight: 15
url: /ru/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Инкапсулирует метаданные и бинарные данные шрифта, используемого в документе Presentation, загруженном в экземпляр Viewer. Этот шрифт используется в содержимом документа и может быть встроен в сам документ или установлен в операционной системе, где работает GroupDocs.Viewer.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Получает семейное имя шрифта (никогда не null и не пустое). |
|
|  | [getStyle()](#getStyle--) | Получает стиль шрифта: Regular, Bold, Italic или BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Указывает, встроен ли этот шрифт в документ, загруженный в экземпляр Viewer. |
|
|  | [getFormat()](#getFormat--) | Получает формат шрифта (TrueType, OpenType и т.д.). |
|
|  | [getContent()](#getContent--) | Получает бинарное содержимое шрифта, или null, если данные шрифта недоступны. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Сериализует информацию о шрифте в правило CSS @font-face, используя указанный writer. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Получает семейное имя шрифта (никогда не null и не пустое).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Получает стиль шрифта: Regular, Bold, Italic или BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Указывает, встроен ли этот шрифт в документ, загруженный в экземпляр Viewer. Примечание: документы Spreadsheet не могут содержать встроенные шрифты, поэтому для них всегда возвращается false.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Получает формат шрифта (TrueType, OpenType и т.д.). Если доступна только метаинформация, возвращает FontFormat.Unknown.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Получает бинарное содержимое шрифта, или null, если данные шрифта недоступны.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Сериализует информацию о шрифте в правило CSS @font-face, используя указанный writer.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | output | java.io.Writer | writer для записи CSS (не должен быть null) |
|

