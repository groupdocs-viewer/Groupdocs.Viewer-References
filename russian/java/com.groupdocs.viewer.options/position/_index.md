---
title: "Позиция"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Определяет позицию водяного знака."
type: docs
weight: 43
url: /ru/java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Определяет позицию водяного знака.


Перечисление Position представляет различные позиции для водяного знака в компоненте GroupDocs.Viewer.
Он предоставляет набор предопределённых позиций, которые можно использовать для указания размещения водяного знака
на документе или изображении во время процесса рендеринга.


Пример использования:

````

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
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [DIAGONAL](#DIAGONAL) | Диагональная позиция. |
|
|  | [TOP_LEFT](#TOP-LEFT) | Позиция в левом верхнем углу. |
|
|  | [TOP_CENTER](#TOP-CENTER) | Позиция в верхнем центре. |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | Позиция в правом верхнем углу. |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | Позиция в левом нижнем углу. |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | Позиция в нижнем центре. |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | Позиция в правом нижнем углу. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


Диагональная позиция.
Эта позиция представляет диагональное выравнивание или размещение.


### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


Позиция в левом верхнем углу.
Эта позиция представляет выравнивание или размещение в левом верхнем углу.


### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


Позиция в верхнем центре.
Эта позиция представляет выравнивание или размещение в верхнем центре.


### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


Позиция в правом верхнем углу.
Эта позиция представляет выравнивание или размещение в правом верхнем углу.


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


Позиция в левом нижнем углу.
Эта позиция представляет выравнивание или размещение в левом нижнем углу.


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


Позиция в нижнем центре.
Эта позиция представляет выравнивание или размещение в нижнем центре.


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


Позиция в правом нижнем углу.
Эта позиция представляет выравнивание или размещение в правом нижнем углу.


### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
