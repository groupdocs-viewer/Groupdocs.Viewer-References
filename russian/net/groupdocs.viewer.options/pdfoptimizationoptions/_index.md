---
title: "PdfOptimizationOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры оптимизации PDF, применяемые к выходному PDF‑файлу. Для получения подробностей и примеров кода см. эту страницуhttps//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ и её дочерние элементы."
type: docs
weight: 400
url: /ru/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

Содержит параметры оптимизации PDF, применяемые к выходному PDF‑файлу. Для подробностей и примеров кода см. эту [страницу](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) и её дочерние элементы.

```csharp
public class PdfOptimizationOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Устанавливает значения по умолчанию параметра MaxResolution равным 300 и параметра ImageQuality равным 100. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | Включает сжатие изображений в выходном PDF‑файле. |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | Включает преобразование выходного PDF‑файла в градации серого. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | Устанавливает качество изображения в выходном PDF‑файле (в процентах). |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | Включает оптимизацию выходного PDF‑файла для онлайн‑просмотра в веб‑браузере. |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | Устанавливает максимальное разрешение в выходном PDF‑файле. |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | Включает оптимизацию электронных таблиц в PDF‑файлах. |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | Включает удаление аннотаций из выходного PDF‑файла. |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | Позволяет удалять поля формы из PDF‑файла. |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Удаляет неиспользуемые (осиротевшие) объекты из PDF‑файла, которые находятся в документе PDF, но не ссылаются из словарей ресурсов любой страницы и поэтому вообще не используются. Включение этого свойства (`true`) уменьшит размер выходного PDF‑документа. По умолчанию отключено (`false`). |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Удаляет неиспользуемые (осиротевшие) потоки из PDF‑файла, которые всё ещё указаны в словаре ресурсов страницы, но фактически никогда не используются в содержимом страницы. По умолчанию отключено (`false`), включение (`true`) уменьшит размер выходного PDF‑документа. |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | Позволяет задать максимальное разрешение в выходном PDF‑файле. |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | Создаёт подмножества шрифтов в выходном PDF‑файле. |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
