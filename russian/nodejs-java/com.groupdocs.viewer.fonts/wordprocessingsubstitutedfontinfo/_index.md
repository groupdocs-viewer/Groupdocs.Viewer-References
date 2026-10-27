---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Инкапсулирует метаданные и двоичные данные одного заменённого шрифта, используемого в документе WordProcessing через GroupDocs.Viewer."
type: docs
weight: 18
url: /ru/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

Инкапсулирует метаданные и двоичные данные одного заменённого шрифта, используемого в документе WordProcessing через GroupDocs.Viewer. Неизменяемый класс.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | Конструктор для инициализации всех полей. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Возвращает семейное имя заменённого шрифта (никогда не null). |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | Возвращает семейное имя оригинального шрифта (никогда не null). |
| [getStyle()](#getStyle--) | Возвращает стиль оригинального шрифта. |
| [getContent()](#getContent--) | Возвращает двоичное содержимое заменённого шрифта (никогда не null). |
| [getFormat()](#getFormat--) | Возвращает формат заменённого шрифта. |
| [toString()](#toString--) | Возвращает строку, описывающую этот заменённый шрифт: "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | Сравнение основано на оригинальном семействе, заменённом семействе и стиле. |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Сериализуйте этот шрифт как правило @font-face CSS с использованием вспомогательного метода. |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


Конструктор для инициализации всех полей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| originalFamilyName | java.lang.String | Оригинальное имя шрифта (не найдено в системе) |
| substitutedFamilyName | java.lang.String | Заменённое имя шрифта (доступно) |
| стиль | com.groupdocs.viewer.fonts.FontStyles | Стиль шрифта (Regular, Bold, Italic, BoldItalic) |
| content | byte[] | Двоичное содержимое заменённого шрифта (никогда не null) |
| format | int | Формат шрифта (TrueType, OpenType и др.) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Возвращает семейное имя заменённого шрифта (никогда не null).

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


Возвращает семейное имя оригинального шрифта (никогда не null).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Возвращает стиль оригинального шрифта.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


Возвращает двоичное содержимое заменённого шрифта (никогда не null).

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Возвращает формат заменённого шрифта.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, описывающую этот заменённый шрифт: "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Сравнение основано на оригинальном семействе, заменённом семействе и стиле. Требуется для использования в HashSet или HashMap, как C\# IEqualityComparer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Сериализуйте этот шрифт как правило @font-face CSS с использованием вспомогательного метода.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| вывод | java.io.Writer |  |

