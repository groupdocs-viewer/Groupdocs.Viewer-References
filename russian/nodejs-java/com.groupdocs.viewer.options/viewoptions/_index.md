---
title: "ViewOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Содержит параметры рендеринга."
type: docs
weight: 35
url: /ru/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Содержит параметры рендеринга.

Класс ViewOptions наследует класс BaseViewOptions и служит базовым классом для параметров рендеринга в компоненте GroupDocs.Viewer. Он инкапсулирует общие настройки и параметры, которые могут использоваться для рендеринга различных типов документов в разные форматы.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWatermark()](#getWatermark--) | Получает текстовый водяной знак, применяемый к каждой странице. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Устанавливает текстовый водяной знак, который будет применяться к каждой странице. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Применяет вращение по часовой стрелке к указанной странице. |
| [getPageRotations()](#getPageRotations--) | Получает вращения страниц. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Чтобы избежать создания экземпляра только для проверки, что он пустой |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Получает текстовый водяной знак, применяемый к каждой странице.

В случае, если указаны как \#setWatermark(Watermark).setWatermark(Watermark), так и \#getPageRotations().getPageRotations(), водяной знак будет применён к повернутым страницам. Подробности см. в [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Устанавливает текстовый водяной знак, который будет применяться к каждой странице.

В случае, если указаны как ViewOptions.Watermark, так и \#getPageRotations().getPageRotations(), водяной знак будет применён к повернутым страницам. Подробности см. в [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Текстовый водяной знак, который необходимо установить. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Применяет вращение по часовой стрелке к указанной странице.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы должен быть строго больше 0. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Значение вращения. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Получает вращения страниц.

Если одновременно указаны [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) и getPageRotations(), водяной знак будет применён к повернутым страницам. Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> — отображение, содержащее номера страниц в качестве ключей и их соответствующие вращения в качестве значений.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Чтобы избежать создания экземпляра только для проверки, что он пустой

**Returns:**
boolean
