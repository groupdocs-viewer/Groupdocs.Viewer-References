---
title: "PresentationOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для визуализации презентаций."
type: docs
weight: 26
url: /ru/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Предоставляет параметры для визуализации презентаций.


Для подробностей см. [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Включает новый режим рендеринга HTML для документов Presentation. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Включает новый режим рендеринга HTML для документов Presentation. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Включает рендеринг заполнителей в заголовке и нижнем колонтитуле слайда. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Включает рендеринг заполнителей в заголовке и нижнем колонтитуле слайда. |
|
|  | [getResolution()](#getResolution--) | Разрешение изображений внутри презентации (только для рендеринга в HTML/PDF). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Разрешение изображений внутри презентации (только для рендеринга в HTML/PDF). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Включает новый режим рендеринга HTML для документов Presentation.


В этом режиме файлы Presentation рендерятся в чистую разметку HTML/CSS без SVG‑изображений.
По умолчанию эта функция отключена (false). Если эта опция не включена, используется существующий HTML‑рендерер на основе SVG.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Включает новый режим рендеринга HTML для документов Presentation.


В этом режиме файлы Presentation рендерятся в чистую разметку HTML/CSS без SVG‑изображений.
По умолчанию эта функция отключена (false). Если эта опция не включена, используется существующий HTML‑рендерер на основе SVG.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Включает отображение заполнителей в верхнем и нижнем колонтитулах слайда. Отключено по умолчанию (false). Эта опция применяется ко всем 4 режимам рендеринга презентаций: HTML, PDF, PNG и JPEG. Не применяется при рендеринге презентации в чистый HTML/CSS разметку с использованием .


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Включает отображение заполнителей в верхнем и нижнем колонтитулах слайда. Отключено по умолчанию (false). Эта опция применяется ко всем 4 режимам рендеринга презентаций: HTML, PDF, PNG и JPEG. Не применяется при рендеринге презентации в чистый HTML/CSS разметку с использованием .


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Разрешение изображений внутри презентации (только для рендеринга в HTML/PDF).


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Разрешение изображений внутри презентации (только для рендеринга в HTML/PDF).


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

