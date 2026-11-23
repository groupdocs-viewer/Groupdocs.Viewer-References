---
title: "DisableCopyProtection"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Отключает защиту копирования контента при рендеринге в HTML."
type: docs
weight: 30
url: /ru/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

Отключает защиту копирования контента при рендеринге в HTML.

```csharp
public bool DisableCopyProtection { get; set; }
```

### Примечания

При рендеринге PDF‑файлов с защитой от копирования текста и изображений в HTML GroupDocs.Viewer добавляет атрибут HTML `inert` к тегу BODY. Значение по умолчанию для этой опции — `false`, что указывает на то, что атрибут `intent` добавляется только если PDF‑документ защищён.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).

### См. также

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
