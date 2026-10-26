---
title: "CadOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры для рендеринга CAD‑чертежей. Для получения дополнительной информации и примеров кода см. Render CAD drawings and models as HTML PDF and image fileshttps//docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ и Specify rendering options for CAD fileshttps//docs.groupdocs.com/viewer/net/specifycadrenderingoptions/."
type: docs
weight: 280
url: /ru/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

Содержит параметры для рендеринга CAD‑чертежей. Для получения дополнительной информации и примеров кода см. [Рендеринг CAD‑чертежей и моделей в HTML, PDF и графические файлы](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) и [Указание параметров рендеринга для CAD‑файлов](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/).

```csharp
public class CadOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | Цвет фона изображения. |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | Установка этого флага в `true` включает специальный режим конвертации, ориентированный на производительность, для всех форматов семейства CAD — в этом режиме скорость конвертации значительно выше, но качество получаемых документов существенно хуже. По умолчанию отключён (`false`) — качество получаемых документов максимально возможное, но за счёт производительности. |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | Высота выходного результата (в пикселях). |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | Слои CAD‑чертежа для рендеринга. |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | Имя конкретного макета для рендеринга. Имя макета чувствительно к регистру. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - файл конфигурации плоттера |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | Флаг, указывающий, следует ли рендерить макеты из CAD‑документа. |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | Значение больше 1 увеличивает результат вывода; значение от 0 до 1 уменьшает результат вывода. |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | Области чертежа для рендеринга. |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | Ширина результата вывода (в пикселях). |

## Методы

| Имя | Описание |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | Инициализирует экземпляр класса [`CadOptions`](../cadoptions) для рендеринга по высоте. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | Инициализирует экземпляр класса [`CadOptions`](../cadoptions) для рендеринга по коэффициенту масштабирования. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | Инициализирует экземпляр класса [`CadOptions`](../cadoptions) для рендеринга по ширине. |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | Инициализирует экземпляр класса [`CadOptions`](../cadoptions) для рендеринга по ширине и высоте. |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
