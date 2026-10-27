---
title: "Tile"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет область рисования."
type: docs
weight: 33
url: /ru/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Представляет область рисования.

Класс Tile представляет область рисования в компоненте GroupDocs.Viewer. Он используется для определения конкретной области или региона внутри документа, который необходимо отрисовать или обработать отдельно. Для подробностей см. [documentation][].

Пример использования:

```

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Инициализирует новый экземпляр класса  Tile . |
## Методы

| Метод | Описание |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Получает координату X нижней левой точки на рисунке, где начинается tile. |
| [getStartPointY()](#getStartPointY--) | Получает координату Y нижней левой точки на рисунке, где начинается tile. |
| [getWidth()](#getWidth--) | Получает ширину tile в пикселях. |
| [getHeight()](#getHeight--) | Получает высоту tile в пикселях. |
| [getEndPointX()](#getEndPointX--) | Возвращает координату X верхней правой точки на рисунке, где заканчивается tile. |
| [getEndPointY()](#getEndPointY--) | Возвращает координату Y верхней правой точки на рисунке, где заканчивается tile. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Инициализирует новый экземпляр класса  Tile .

Этот конструктор создаёт новый объект tile с указанными начальной точкой, шириной и высотой. Для подробностей см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startPointX | int | Координата X нижней левой точки на рисунке, где начинается tile. |
| startPointY | int | Координата Y нижней левой точки на рисунке, где начинается tile. |
| width | int | Ширина tile в пикселях. |
| height | int | Высота tile в пикселях. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Получает координату X нижней левой точки на рисунке, где начинается tile.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - координата X нижней левой точки.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Получает координату Y нижней левой точки на рисунке, где начинается tile.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - координата Y нижней левой точки.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину tile в пикселях.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - ширина tile.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту tile в пикселях.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - высота tile.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Возвращает координату X верхней правой точки на рисунке, где заканчивается tile.

**Returns:**
int - координата X верхней правой точки.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Возвращает координату Y верхней правой точки на рисунке, где заканчивается tile.

**Returns:**
int - координата Y самой верхней правой точки.
