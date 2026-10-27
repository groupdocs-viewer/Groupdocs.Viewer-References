---
title: "Page"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет одну страницу, которую можно просмотреть."
type: docs
weight: 21
url: /ru/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Представляет одну страницу, которую можно просмотреть.

Интерфейс Page определяет контракт для доступа и манипулирования отдельной страницей, которую можно просматривать в компоненте GroupDocs.Viewer. Он предоставляет методы для получения информации, такой как номер страницы, размер и другие свойства.

Пример использования:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Получает имя листа или страницы. |
| [setName(String name)](#setName-java.lang.String-) | Устанавливает имя листа или страницы. |
| [getNumber()](#getNumber--) | Получает номер страницы. |
| [setNumber(int number)](#setNumber-int-) | Устанавливает номер страницы. |
| [isVisible()](#isVisible--) | Получает индикатор видимости страницы. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Устанавливает индикатор видимости страницы. |
| [getWidth()](#getWidth--) | Получает ширину страницы в пикселях при просмотре в формате JPG или PNG. |
| [setWidth(int width)](#setWidth-int-) | Устанавливает ширину страницы в пикселях при просмотре в формате JPG или PNG. |
| [getHeight()](#getHeight--) | Получает высоту страницы в пикселях при просмотре в формате JPG или PNG. |
| [setHeight(int height)](#setHeight-int-) | Устанавливает высоту страницы в пикселях при просмотре в формате JPG или PNG. |
| [getLines()](#getLines--) | Получает строки, содержащиеся на странице при просмотре в формате JPG или PNG с включённым извлечением текста. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Устанавливает строки, содержащиеся на странице при просмотре в формате JPG или PNG с включённым извлечением текста. |
### getName() {#getName--}
```
public abstract String getName()
```


Получает имя листа или страницы.

**Returns:**
java.lang.String - имя листа или страницы.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Устанавливает имя листа или страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | имя, которое следует установить для листа или страницы. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Получает номер страницы.

**Returns:**
int - номер страницы.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Устанавливает номер страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| number | int | номер страницы, который следует установить. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Получает индикатор видимости страницы.

**Returns:**
boolean - индикатор видимости страницы.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Устанавливает индикатор видимости страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| видимый | boolean | true, если страница видима, false в противном случае. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Получает ширину страницы в пикселях при просмотре в формате JPG или PNG.

**Returns:**
int — ширина страницы.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Устанавливает ширину страницы в пикселях при просмотре в формате JPG или PNG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | ширина, которую нужно установить для страницы. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Получает высоту страницы в пикселях при просмотре в формате JPG или PNG.

**Returns:**
int — высота страницы.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Устанавливает высоту страницы в пикселях при просмотре в формате JPG или PNG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| height | int | высота, которую нужно установить для страницы. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Получает строки, содержащиеся на странице при просмотре в формате JPG или PNG с включённым извлечением текста.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> — строки, содержащиеся на странице.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Устанавливает строки, содержащиеся на странице при просмотре в формате JPG или PNG с включённым извлечением текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | список строк, который нужно установить для страницы. |

