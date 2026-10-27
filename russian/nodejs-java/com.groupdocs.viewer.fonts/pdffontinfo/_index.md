---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Инкапсулирует метаинформацию и бинарные данные одного шрифта из PDF‑документа, загруженного в экземпляр Viewer."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Инкапсулирует метаинформацию и двоичные данные одного шрифта из PDF‑документа, загруженного в экземпляр Viewer.

Этот шрифт используется в содержимом документа и является либо:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Внутренний конструктор, используемый при извлечении шрифтов из PDF. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Получает название семейства шрифта. |
| [getStyle()](#getStyle--) | Получает стиль этого шрифта. |
| [isEmbedded()](#isEmbedded--) | Возвращает, встроен ли шрифт в документ PDF. |
| [isInstalled()](#isInstalled--) | Возвращает, установлен ли шрифт в ОС. |
| [getFormat()](#getFormat--) | Возвращает формат файла шрифта. |
| [getContent()](#getContent--) | Возвращает двоичное содержимое шрифта. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Сериализует этот шрифт как правило CSS  @font-face  . |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Внутренний конструктор, используемый при извлечении шрифтов из PDF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| familyName | java.lang.String | название семейства шрифта |
| стиль | com.groupdocs.viewer.fonts.FontStyles | стиль (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true, если шрифт встроен в PDF |
| isInstalled | boolean | true, если шрифт установлен в ОС |
| content | byte[] | двоичные данные шрифта (nullable) |
| format | int | формат файла шрифта |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Получает название семейства шрифта.

**Returns:**
java.lang.String - строка названия семейства (никогда не null и не пустая)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Получает стиль этого шрифта.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - стиль шрифта
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Возвращает, встроен ли шрифт в документ PDF.

**Returns:**
boolean - true, если встроен
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Возвращает, установлен ли шрифт в ОС.

**Returns:**
boolean - true, если установлен
### getFormat() {#getFormat--}
```
public int getFormat()
```


Возвращает формат файла шрифта.

**Returns:**
int - перечисление формата шрифта
### getContent() {#getContent--}
```
public byte[] getContent()
```


Возвращает двоичное содержимое шрифта.

**Returns:**
byte[] - массив байтов или null, если недоступно
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Сериализует этот шрифт как правило CSS  @font-face  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| вывод | java.io.Writer | writer, в который будет записан CSS |

