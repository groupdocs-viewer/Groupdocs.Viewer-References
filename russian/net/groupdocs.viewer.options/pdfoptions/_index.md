---
title: "PdfOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры для рендеринга PDF‑документов. For details see the documentationhttps//docs.groupdocs.com/viewer/net/renderpdfdocuments/."
type: docs
weight: 410
url: /ru/net/groupdocs.viewer.options/pdfoptions/
---

## PdfOptions class

Содержит параметры для рендеринга в PDF‑документы. Для подробностей см. [документацию](https://docs.groupdocs.com/viewer/net/render-pdf-documents/).

```csharp
public class PdfOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfOptions](pdfoptions)() | Инициализирует новый экземпляр класса [`PdfOptions`](../pdfoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [DisableCharsGrouping](../../groupdocs.viewer.options/pdfoptions/disablecharsgrouping) { get; set; } | Отключает группировку символов для точного позиционирования символов при рендеринге страницы. |
| [DisableCopyProtection](../../groupdocs.viewer.options/pdfoptions/disablecopyprotection) { get; set; } | Отключает защиту копирования контента при рендеринге в HTML. |
| [DisableFontLicenseVerifications](../../groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications) { get; set; } | Отключает любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS. |
| [EnableFontHinting](../../groupdocs.viewer.options/pdfoptions/enablefonthinting) { get; set; } | Включает хинтинг шрифтов. |
| [EnableLayeredRendering](../../groupdocs.viewer.options/pdfoptions/enablelayeredrendering) { get; set; } | Включает рендеринг текста и графики в оригинальном порядке слоёв PDF‑документа при рендеринге в HTML. |
| [FixedLayout](../../groupdocs.viewer.options/pdfoptions/fixedlayout) { get; set; } | Включает рендеринг PDF‑ и EPUB‑документов в HTML с фиксированным макетом. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptions/imagequality) { get; set; } | Устанавливает качество выходных изображений для ресурсов изображений при рендеринге в HTML. Качество по умолчанию — `Low`. |
| [RenderOriginalPageSize](../../groupdocs.viewer.options/pdfoptions/renderoriginalpagesize) { get; set; } | Устанавливает размер выходной страницы, совпадающий с размером страницы исходного PDF‑документа. |
| [RenderTextAsImage](../../groupdocs.viewer.options/pdfoptions/rendertextasimage) { get; set; } | Включает рендеринг текста из PDF‑файлов в виде изображения в HTML‑выводе. |
| [WrapImagesInSvg](../../groupdocs.viewer.options/pdfoptions/wrapimagesinsvg) { get; set; } | Включает оборачивание каждого изображения в выходном HTML‑документе в тег SVG для повышения качества вывода. |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
