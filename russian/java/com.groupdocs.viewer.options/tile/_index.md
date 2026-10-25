---
title: "Плитка"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет область рисования."
type: docs
weight: 33
url: /ru/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Представляет область рисования.


Класс Tile представляет область рисования в компоненте GroupDocs.Viewer.
Он используется для определения конкретной области или региона внутри документа, которые необходимо отобразить или обработать отдельно.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


Пример использования:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Инициализирует новый экземпляр |
Плитка
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | Получает координату X нижней левой точки рисунка, где начинается плитка. |
|
|  | [getStartPointY()](#getStartPointY--) | Получает координату Y самой нижней левой точки на чертеже, где начинается плитка. |
|
|  | [getWidth()](#getWidth--) | Получает ширину плитки в пикселях. |
|
|  | [getHeight()](#getHeight--) | Получает высоту плитки в пикселях. |
|
|  | [getEndPointX()](#getEndPointX--) | Возвращает координату X самой верхней правой точки на чертеже, где заканчивается плитка. |
|
|  | [getEndPointY()](#getEndPointY--) | Возвращает координату Y самой верхней правой точки на чертеже, где заканчивается плитка. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Инициализирует новый экземпляр
Плитка
класса.


Этот конструктор создает новый объект плитки с указанными начальной точкой, шириной и высотой.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | startPointX | int | Координата X самой нижней левой точки на чертеже, где начинается плитка. |
|
|  | startPointY | int | Координата Y самой нижней левой точки на чертеже, где начинается плитка. |
|
|  | width | int | Ширина плитки в пикселях. |
|
|  | height | int | Высота плитки в пикселях. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Получает координату X нижней левой точки рисунка, где начинается плитка.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int — координата X самой нижней левой точки.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Получает координату Y самой нижней левой точки на чертеже, где начинается плитка.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int — координата Y самой нижней левой точки.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину плитки в пикселях.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int — ширина плитки.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту плитки в пикселях.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int — высота плитки.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Возвращает координату X самой верхней правой точки на чертеже, где заканчивается плитка.


**Returns:**
int — координата X самой верхней правой точки.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Возвращает координату Y самой верхней правой точки на чертеже, где заканчивается плитка.


**Returns:**
int — координата Y самой верхней правой точки.

