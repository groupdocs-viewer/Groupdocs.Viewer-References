---
title: "WrapImagesInSvg"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Включает оборачивание каждого изображения в выходном HTML‑документе в тег SVG для повышения качества вывода."
type: docs
weight: 110
url: /ru/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

Включает оборачивание каждого изображения в выходном HTML‑документе в тег SVG для повышения качества вывода.

```csharp
public bool WrapImagesInSvg { get; set; }
```

### Примечания

По умолчанию при рендеринге PDF и файлов Page Layout в HTML все изображения объединяются в один PNG‑файл. Полученный PNG‑изображение используется как фон выходного HTML‑документа.

Эта опция доступна при рендеринге [PDF и файлов форматов Page Layout](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) в HTML с встроенными и внешними ресурсами. Она позволяет оборачивать каждое изображение в выходном HTML‑документе в тег SVG. Значение по умолчанию — `false`.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files).

### См. также

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
