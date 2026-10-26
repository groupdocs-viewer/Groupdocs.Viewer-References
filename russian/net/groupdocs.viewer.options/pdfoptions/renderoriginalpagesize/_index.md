---
title: "RenderOriginalPageSize"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Устанавливает размер выходной страницы таким же, как размер страницы исходного PDF‑документа."
type: docs
weight: 90
url: /ru/net/groupdocs.viewer.options/pdfoptions/renderoriginalpagesize/
---

## PdfOptions.RenderOriginalPageSize property

Устанавливает размер выходной страницы, совпадающий с размером страницы исходного PDF‑документа.

```csharp
public bool RenderOriginalPageSize { get; set; }
```

### Примечания

По умолчанию GroupDocs.Viewer рассчитывает размер выходной страницы изображения для более качественного рендеринга. Включите эту опцию, чтобы гарантировать, что выходные страницы имеют тот же размер, что и страницы исходного PDF‑документа (в пикселях). Значение по умолчанию — `false`.

Эта опция доступна при рендеринге в форматы PNG или JPG.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#preserve-the-size-of-document-pages).

### См. также

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
