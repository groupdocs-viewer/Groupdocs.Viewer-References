---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Содержит параметры для рендеринга документов Visio."
type: docs
weight: 36
url: /ru/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Содержит параметры для рендеринга документов Visio.

Класс VisioRenderingOptions предоставляет параметры для обработки и рендеринга файлов Visio в компоненте GroupDocs.Viewer. Он инкапсулирует настройки и параметры, которые можно использовать для управления процессом рендеринга и форматом вывода Visio‑документов. Подробности см. в [documentation][].

Пример использования:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Инициализирует новый экземпляр класса VisioRenderingOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Рендерить только фигуры Visio, исключая схему. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Устанавливает флаг для рендеринга только фигур Visio, исключая схему. |
| [getFigureWidth()](#getFigureWidth--) | Получает ширину фигуры. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Устанавливает ширину фигуры. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Инициализирует новый экземпляр класса VisioRenderingOptions.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Рендерить только фигуры Visio, исключая схему.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  если следует отрисовывать только фигуры Visio,  false  в противном случае.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Устанавливает флаг для рендеринга только фигур Visio, исключая схему.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  для отрисовки только фигур Visio,  false  для включения диаграммы. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Получает ширину фигуры. Высота будет вычислена автоматически.

**Returns:**
int - ширина фигуры.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Устанавливает ширину фигуры. Высота будет вычислена автоматически.

***Note:** Default value is 100.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figureWidth | int | Ширина фигуры. |

