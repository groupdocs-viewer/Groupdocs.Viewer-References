---
title: "Watermark"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет текстовый водяной знак."
type: docs
weight: 37
url: /ru/nodejs-java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Представляет текстовый водяной знак. Подробности см. в [documentation][].

Класс Watermark представляет текстовый водяной знак в компоненте GroupDocs.Viewer. Он используется для определения и применения водяного знака к отрендеренному выводу документов.

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


[documentation]: https://docs.groupdocs.com/viewer/net/add-text-watermark/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Инициализирует новый экземпляр класса  Watermark  . |
## Методы

| Метод | Описание |
| --- | --- |
| [getText()](#getText--) | Возвращает текст водяного знака. |
| [getColor()](#getColor--) | Возвращает цвет водяного знака. |
| [getColorAsHex()](#getColorAsHex--) | Возвращает цвет водяного знака в шестнадцатеричном формате. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Устанавливает цвет водяного знака. |
| [setColor(String colorName)](#setColor-java.lang.String-) | Устанавливает цвет водяного знака. |
| [getPosition()](#getPosition--) | Возвращает позицию водяного знака. |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Устанавливает позицию водяного знака. |
| [getSize()](#getSize--) | Возвращает размер водяного знака. |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Устанавливает размер водяного знака. |
| [getFontName()](#getFontName--) | Возвращает название шрифта, используемого для водяного знака. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Устанавливает название шрифта, используемого для водяного знака. |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Инициализирует новый экземпляр класса  Watermark  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | java.lang.String | Текст водяного знака. |

### getText() {#getText--}
```
public final String getText()
```


Возвращает текст водяного знака. Этот метод извлекает текст водяного знака, применённого к документу.

**Returns:**
java.lang.String - текст водяного знака.
### getColor() {#getColor--}
```
public final Color getColor()
```


Возвращает цвет водяного знака. Этот метод извлекает цвет водяного знака, применённого к документу.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - цвет водяного знака.
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Возвращает цвет водяного знака в шестнадцатеричном формате. Этот метод извлекает цвет водяного знака, применённого к документу.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - цвет водяного знака в шестнадцатеричном формате.
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Устанавливает цвет водяного знака. Этот метод задаёт цвет водяного знака, применённого к документу.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.Color | Цвет водяного знака для установки. |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Устанавливает цвет водяного знака. Этот метод задаёт цвет водяного знака, применённого к документу.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorName | java.lang.String | Цвет водяного знака для установки. |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Возвращает позицию водяного знака. Этот метод возвращает позицию водяного знака, применённого к документу.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Устанавливает позицию водяного знака. Этот метод задаёт позицию водяного знака, применённого к документу.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | Позиция водяного знака. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Возвращает размер водяного знака. Этот метод извлекает размер водяного знака, применённого к документу.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Устанавливает размер водяного знака. Этот метод задает размер водяного знака, который будет применён к документу.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | Размер водяного знака. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Возвращает название шрифта, используемого для водяного знака.

**Returns:**
java.lang.String - имя шрифта, используемого для водяного знака.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Устанавливает название шрифта, используемого для водяного знака.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Имя шрифта, используемого для водяного знака. |

