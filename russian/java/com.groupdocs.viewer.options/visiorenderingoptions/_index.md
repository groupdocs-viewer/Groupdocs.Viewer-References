---
title: "VisioRenderingOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Содержит параметры для визуализации документов Visio."
type: docs
weight: 36
url: /ru/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Содержит параметры для визуализации документов Visio.


Класс VisioRenderingOptions предоставляет параметры для обработки и рендеринга файлов Visio
в компоненте GroupDocs.Viewer. Он инкапсулирует настройки и параметры, которые могут быть использованы
для управления процессом рендеринга и форматом вывода Visio‑документов.
Для деталей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


Пример использования:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | Инициализирует новый экземпляр |
VisioRenderingOptions
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Отрисовывать только фигуры Visio, исключая диаграмму. |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Устанавливает флаг для отрисовки только фигур Visio, исключая диаграмму. |
|
|  | [getFigureWidth()](#getFigureWidth--) | Получает ширину фигуры. |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Устанавливает ширину фигуры. |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Инициализирует новый экземпляр
VisioRenderingOptions
класса.


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Отрисовывать только фигуры Visio, исключая диаграмму.
Для деталей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Returns:**
boolean —  true  если следует отрисовывать только фигуры Visio,  false  в противном случае.

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Устанавливает флаг для отрисовки только фигур Visio, исключая диаграмму.
Для деталей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  — отрисовывать только фигуры Visio,  false  — включать диаграмму. |
|

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Получает ширину фигуры. Высота будет рассчитана автоматически.


**Returns:**
int — ширина фигуры.

### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Устанавливает ширину фигуры. Высота будет рассчитана автоматически.


***Note:** Default value is 100.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | figureWidth | int | Ширина фигуры. |
|

