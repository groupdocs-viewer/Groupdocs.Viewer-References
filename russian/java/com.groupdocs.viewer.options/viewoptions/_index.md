---
title: "ViewOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Содержит параметры визуализации."
type: docs
weight: 35
url: /ru/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Содержит параметры визуализации.


Класс ViewOptions расширяет класс BaseViewOptions и служит базовым классом для параметров рендеринга
в компоненте GroupDocs.Viewer. Он инкапсулирует общие настройки и параметры, которые могут быть использованы
для рендеринга различных типов документов в разные форматы.


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | Получает текстовый водяной знак, применяемый к каждой странице. |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Устанавливает текстовый водяной знак, который будет применяться к каждой странице. |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Применяет вращение по часовой стрелке к указанной странице. |
|
|  | [getPageRotations()](#getPageRotations--) | Получает вращения страниц. |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Чтобы избежать создания экземпляра только для проверки, что он пуст |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Получает текстовый водяной знак, применяемый к каждой странице.


В случае, если указаны оба #setWatermark(Watermark).setWatermark(Watermark) и #getPageRotations().getPageRotations(),
водяной знак будет применен к повернутым страницам.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Устанавливает текстовый водяной знак, который будет применяться к каждой странице.


В случае, если оба
ViewOptions.Watermark
и #getPageRotations().getPageRotations() указаны,
водяной знак будет применен к повернутым страницам.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | Текстовый водяной знак, который будет установлен. |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Применяет вращение по часовой стрелке к указанной странице.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageNumber | int | Номер страницы должен быть строго больше 0. |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | Значение вращения. |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Получает вращения страниц.


Если оба [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) и
getPageRotations()
указаны,
водяной знак будет применен к повернутым страницам.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - карта, содержащая номера страниц в качестве ключей и их соответствующие вращения в качестве значений.

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Чтобы избежать создания экземпляра только для проверки, что он пуст


**Returns:**
boolean
