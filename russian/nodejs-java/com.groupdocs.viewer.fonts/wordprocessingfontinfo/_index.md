---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Инкапсулирует метаинформацию и бинарные данные одного шрифта из документа WordProcessing, загруженного в экземпляр Viewer."
type: docs
weight: 17
url: /ru/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Инкапсулирует метаданные и бинарные данные одного шрифта из документа WordProcessing, загруженного в экземпляр Viewer. Этот шрифт используется в содержимом документа и встроен в сам документ или установлен в операционной системе, где работает GroupDocs.Viewer.

Неизменяемый класс. Его экземпляры создаются и возвращаются публичным API GroupDocs.Viewer и обычно не должны создаваться пользователем. Для подробностей см. документацию: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Имя семейства шрифта без стиля, никогда не равно null и не пустое. |
| [getAltFamilyName()](#getAltFamilyName--) | Альтернативное имя семейства шрифта. |
| [getStyle()](#getStyle--) | Стиль шрифта \\u2014 может быть Regular, Bold, Italic или BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Указывает, встроен ли этот шрифт в документ (true) или является системным шрифтом (false). |
| [getFormat()](#getFormat--) | Формат этого шрифта. |
| [getContent()](#getContent--) | Содержимое этого шрифта в виде массива байтов или null, если недоступно. |
| [getCharset()](#getCharset--) | Набор символов этого шрифта. |
| [toString()](#toString--) | Возвращает отладочную информацию о этом шрифте в следующем шаблоне: \"name style, embedded/system, format\" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Сериализует информацию о шрифте как правило CSS @font-face и записывает её в указанный writer. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Имя семейства шрифта без стиля, никогда не равно null и не пустое.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Альтернативное имя семейства шрифта. Если отсутствует, возвращает пустую строку.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Стиль шрифта \\u2014 может быть Regular, Bold, Italic или BoldItalic.

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


Формат этого шрифта. Если присутствуют только метаданные и отсутствует бинарное содержимое, может вернуть FontFormat.UNKNOWN.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Содержимое этого шрифта в виде массива байтов или null, если недоступно.

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


Возвращает отладочную информацию о этом шрифте в следующем шаблоне: \"name style, embedded/system, format\"

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
| вывод | java.io.Writer | Writer для получения сериализованного CSS. |

