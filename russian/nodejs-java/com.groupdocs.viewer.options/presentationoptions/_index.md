---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга презентаций."
type: docs
weight: 26
url: /ru/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Предоставляет параметры для рендеринга презентаций.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Включает новый режим рендеринга HTML для документов Presentation. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Включает новый режим рендеринга HTML для документов Presentation. |
| [getResolution()](#getResolution--) | Разрешение для изображений внутри презентации (только для рендеринга в HTML/PDF). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Разрешение для изображений внутри презентации (только для рендеринга в HTML/PDF). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Включает новый режим рендеринга HTML для документов Presentation.

В этом режиме файлы Presentation рендерятся в чистую разметку HTML/CSS без изображений SVG. По умолчанию эта функция отключена (false). Если эта опция не включена, используется существующий рендерер HTML на основе SVG.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Включает новый режим рендеринга HTML для документов Presentation.

В этом режиме файлы Presentation рендерятся в чистую разметку HTML/CSS без изображений SVG. По умолчанию эта функция отключена (false). Если эта опция не включена, используется существующий рендерер HTML на основе SVG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Разрешение для изображений внутри презентации (только для рендеринга в HTML/PDF).

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Разрешение для изображений внутри презентации (только для рендеринга в HTML/PDF).

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

