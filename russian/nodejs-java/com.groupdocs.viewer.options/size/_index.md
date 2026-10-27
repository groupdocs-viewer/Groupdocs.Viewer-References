---
title: "Size"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Содержит размер водяного знака."
type: docs
weight: 30
url: /ru/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Содержит размер водяного знака.

Класс Size представляет размер водяного знака в компоненте GroupDocs.Viewer. Он предоставляет параметры для указания размеров водяного знака, таких как ширина и высота.

Пример использования:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Инициализирует новый экземпляр класса  Size . |
## Поля

| Поле | Описание |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | Представляет максимальный размер текста водяного знака, который помещается на страницу. |
| [HALF_SIZE](#HALF-SIZE) | Представляет половину максимального размера текста водяного знака, который помещается на страницу. |
| [ONE_THIRD](#ONE-THIRD) | Представляет одну треть максимального размера текста водяного знака, который помещается на страницу. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | Возвращает размер текста водяного знака в процентах относительно ширины страницы. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Инициализирует новый экземпляр класса  Size .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| relativeSize | byte | Размер в процентах относительно размера страницы. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Представляет максимальный размер текста водяного знака, который помещается на страницу.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Представляет половину максимального размера текста водяного знака, который помещается на страницу.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Представляет одну треть максимального размера текста водяного знака, который помещается на страницу.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Возвращает размер текста водяного знака в процентах относительно ширины страницы.

**Returns:**
byte — размер текста водяного знака в процентах.
