---
title: "CadOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга CAD‑чертежей."
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Предоставляет параметры для рендеринга CAD‑чертежей.

Класс CadOptions инкапсулирует различные настройки и параметры, которые можно использовать для управления рендерингом CAD‑чертежей в компоненте GroupDocs.Viewer.

Для получения дополнительной информации и примеров кода см. [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] и [Specify rendering options for CAD files][].

Пример использования:

```

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## Поля

| Поле | Описание |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getPc3File()](#getPc3File--) | Получает файл PC3 (Plotter Configuration), связанный с плоттером. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Устанавливает файл PC3 (Plotter Configuration), связанный с плоттером. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Инициализирует новый экземпляр класса CadOptions для рендеринга по коэффициенту масштабирования. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Инициализирует новый экземпляр класса CadOptions для рендеринга по ширине. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Инициализирует новый экземпляр класса CadOptions для рендеринга по высоте. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Инициализирует новый экземпляр класса  CadOptions  для рендеринга по ширине и высоте. |
| [getScaleFactor()](#getScaleFactor--) | Получает коэффициент масштабирования для рендеринга. |
| [getWidth()](#getWidth--) | Получает ширину выходного результата в пикселях. |
| [getHeight()](#getHeight--) | Получает высоту выходного результата в пикселях. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона изображения. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Получает цвет фона изображения. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Устанавливает цвет фона изображения. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Устанавливает цвет фона изображения. |
| [getTiles()](#getTiles--) | Получает области чертежа для рендеринга. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Устанавливает области чертежа для рендеринга. |
| [isRenderLayouts()](#isRenderLayouts--) | Указывает, следует ли рендерить макеты из CAD‑документа. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Устанавливает, следует ли рендерить макеты из CAD‑документа. |
| [getLayoutName()](#getLayoutName--) | Получает имя конкретного макета для рендеринга. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Устанавливает имя конкретного макета для рендеринга. |
| [getLayers()](#getLayers--) | Получает слои чертежа CAD для рендеринга. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Получает слои чертежа CAD для рендеринга. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Установка этого флага в true включает специальный ориентированный на производительность режим конвертации для всех форматов семейства CAD. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Установка этого флага в true включает специальный ориентированный на производительность режим конвертации для всех форматов семейства CAD. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равен ли этот объект CadOptions другому объекту. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Получает файл PC3 (Plotter Configuration), связанный с плоттером.

**Returns:**
java.lang.String - путь к файлу PC3.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Устанавливает файл PC3 (Plotter Configuration), связанный с плоттером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pc3File | java.lang.String | Путь к файлу PC3. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Инициализирует новый экземпляр класса CadOptions для рендеринга по коэффициенту масштабирования.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleFactor | double | Коэффициент масштабирования для рендеринга. Значения больше 1 увеличат выходной результат, а значения от 0 до 1 уменьшат его. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Инициализирует новый экземпляр класса CadOptions для рендеринга по ширине.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина выходного результата в пикселях. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Инициализирует новый экземпляр класса CadOptions для рендеринга по высоте.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| height | int | Высота выходного результата в пикселях. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Инициализирует новый экземпляр класса  CadOptions  для рендеринга по ширине и высоте.

Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина выходного результата в пикселях. |
| height | int | Высота выходного результата в пикселях. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Получает коэффициент масштабирования для рендеринга. Значения выше 1 увеличат выходной результат, а значения от 0 до 1 уменьшат его.

**Returns:**
double - коэффициент масштабирования для рендеринга.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину выходного результата в пикселях.

**Returns:**
int - ширина выходного результата.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту выходного результата в пикселях.

**Returns:**
int - высота выходного результата.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает цвет фона изображения.

**Returns:**
java.awt.Color - цвет фона изображения.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Получает цвет фона изображения.

**Returns:**
java.lang.String - цвет фона изображения в формате 0xFFFFFF.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Устанавливает цвет фона изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| backgroundColor | java.awt.Color | Цвет фона изображения. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Устанавливает цвет фона изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorName | java.lang.String | Название цвета фона изображения. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Получает области чертежа для рендеринга.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - список областей рисования для рендеринга.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Устанавливает области чертежа для рендеринга.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | Список областей рисования для рендеринга. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Указывает, следует ли рендерить макеты из CAD‑документа.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  если макеты должны быть отрисованы,  false  иначе.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Устанавливает, следует ли рендерить макеты из CAD‑документа.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true  для отрисовки макетов,  false  иначе. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Получает имя конкретного макета для отрисовки. Имя макета чувствительно к регистру.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - имя конкретного макета для отрисовки.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Устанавливает имя конкретного макета для отрисовки. Имя макета чувствительно к регистру.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Имя конкретного макета для отрисовки. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Получает слои чертежа CAD для рендеринга.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - слои CAD-рисунка.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Получает слои чертежа CAD для рендеринга.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | Слои CAD-рисунка. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Установка этого флага в значение true включает специальный режим конвертации, ориентированный на производительность, для всех форматов семейства CAD. В этом режиме скорость конвертации значительно выше, но качество получаемых документов значительно хуже. По умолчанию он отключён (false). Качество получаемых документов максимально возможное за счёт производительности.

**Returns:**
boolean -  true  если режим конвертации, ориентированный на производительность, включён,  false  иначе.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Установка этого флага в значение true включает специальный режим конвертации, ориентированный на производительность, для всех форматов семейства CAD. В этом режиме скорость конвертации значительно выше, но качество получаемых документов значительно хуже. По умолчанию он отключён (false). Качество получаемых документов максимально возможное за счёт производительности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  для включения режима конвертации, ориентированного на производительность,  false  для его отключения. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Проверяет, равен ли этот объект CadOptions другому объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Объект для сравнения. |

**Returns:**
boolean -  true  если объекты равны,  false  иначе.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Вычисляет значение хеш‑кода для этого объекта. Хеш‑код основан на внутреннем состоянии объекта и используется в хеш‑ориентированных структурах данных, таких как хеш‑карты и хеш‑множества.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - значение хеш‑кода для этого объекта.
### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление этого объекта.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - строковое представление этого объекта.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Возвращает строковое представление этого объекта.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| стиль | org.apache.commons.lang3.builder.ToStringStyle | ToStringStyle, используемый для генерации строкового представления. |

**Returns:**
java.lang.String - строковое представление этого объекта с использованием указанного ToStringStyle.
