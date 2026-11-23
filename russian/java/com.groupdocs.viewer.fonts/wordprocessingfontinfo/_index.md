---
title: "WordProcessingFontInfo"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Инкапсулирует метаданные и двоичные данные одного шрифта из документа WordProcessing, загруженного в экземпляр Viewer."
type: docs
weight: 17
url: /ru/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Инкапсулирует метаданные и двоичные данные одного шрифта из документа WordProcessing, загруженного в экземпляр Viewer. Этот шрифт используется в содержимом документа и встроен непосредственно в документ или установлен в операционной системе, где работает GroupDocs.Viewer.

Неизменяемый класс. Его экземпляры создаются и возвращаются GroupDocs.Viewer
публичный API и обычно не должен создаваться пользователем.
Для получения подробностей см. документацию:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Семейное имя шрифта без стиля, никогда не null и не пустое. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | Альтернативное семейное имя шрифта. |
|
|  | [getStyle()](#getStyle--) | Стиль шрифта — может быть Regular, Bold, Italic или BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Указывает, встроен ли этот шрифт в документ (true) или является системным шрифтом (false). |
|
|  | [getFormat()](#getFormat--) | Формат этого шрифта. |
|
|  | [getContent()](#getContent--) | Содержимое этого шрифта в виде массива байтов, или null, если недоступно. |
|
|  | [getCharset()](#getCharset--) | Набор символов этого шрифта. |
|
|  | [toString()](#toString--) | Возвращает отладочную информацию об этом шрифте в следующем шаблоне: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Сериализует информацию о шрифте как правило CSS @font-face и записывает её в указанный writer. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Семейное имя шрифта без стиля, никогда не null и не пустое.


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Альтернативное семейное имя шрифта. Если отсутствует, возвращает пустую строку.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Стиль шрифта — может быть Regular, Bold, Italic или BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Указывает, встроен ли этот шрифт в документ (true) или является системным шрифтом (false).


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Формат этого шрифта. Если присутствует только метаинформация и бинарное содержимое отсутствует, может вернуть FontFormat.UNKNOWN.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Содержимое этого шрифта в виде массива байтов, или null, если недоступно.


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Набор символов этого шрифта.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Возвращает отладочную информацию об этом шрифте в следующем шаблоне: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Сериализует информацию о шрифте как правило CSS @font-face и записывает её в указанный writer.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | output | java.io.Writer | Writer для получения сериализованного CSS. |
|

