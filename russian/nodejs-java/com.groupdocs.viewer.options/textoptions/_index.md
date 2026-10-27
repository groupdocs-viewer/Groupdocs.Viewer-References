---
title: "TextOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Параметры разбиения текстовых файлов на страницы."
type: docs
weight: 32
url: /ru/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Параметры разбиения текстовых файлов на страницы.

Класс TextOptions предоставляет параметры для разбиения текстовых файлов на страницы в компоненте GroupDocs.Viewer. Он позволяет управлять тем, как текстовые файлы делятся на отдельные страницы для рендеринга и просмотра.

Пример использования:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextOptions()](#TextOptions--) | Инициализирует новый экземпляр класса TextOptions. |
## Методы

| Метод | Описание |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Получает максимальное количество символов в строке на странице. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Устанавливает максимальное количество символов в строке на странице. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Получает максимальное количество строк на странице. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Устанавливает максимальное количество строк на странице. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Инициализирует новый экземпляр класса TextOptions.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Получает максимальное количество символов в строке на странице.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - максимальное количество символов в строке на странице.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Устанавливает максимальное количество символов в строке на странице.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxCharsPerRow | int | Максимальное количество символов в строке на странице. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Получает максимальное количество строк на странице.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - максимальное количество строк.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Устанавливает максимальное количество строк на странице.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxRowsPerPage | int | Максимальное количество строк. |

