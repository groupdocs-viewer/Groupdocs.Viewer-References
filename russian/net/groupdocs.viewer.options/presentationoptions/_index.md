---
title: "PresentationOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры для отрисовки презентаций. Подробнее см. документацию https://docs.groupdocs.com/viewer/net/renderpresentations/."
type: docs
weight: 460
url: /ru/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

Содержит параметры для рендеринга презентаций. Для подробностей см. [документацию](https://docs.groupdocs.com/viewer/net/render-presentations/).

```csharp
public class PresentationOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PresentationOptions](presentationoptions)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | Включает отрисовку заполнителей в заголовке и нижнем колонтитуле слайда. Отключено по умолчанию (`false`). Эта опция применяется ко всем 4 режимам отрисовки презентаций: HTML, PDF, PNG и JPEG. Не применяется при отрисовке презентации в чистый HTML/CSS с помощью [`RenderToPureHtml`](./rendertopurehtml). |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | Включает новый режим отрисовки HTML для документов Presentation — в этом режиме файлы Presentation отрисовываются в **pure HTML/CSS markup**, без SVG‑изображений. По умолчанию отключено (`false`) — используется существующий HTML‑рендерер на основе SVG. |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | Разрешение изображений презентации (только для отрисовки в HTML/PDF). |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
