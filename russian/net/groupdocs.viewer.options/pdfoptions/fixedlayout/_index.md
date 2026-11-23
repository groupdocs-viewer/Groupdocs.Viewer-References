---
title: "FixedLayout"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Включает рендеринг PDF‑ и EPUB‑документов в HTML с фиксированным макетом."
type: docs
weight: 70
url: /ru/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

Включает рендеринг PDF‑ и EPUB‑документов в HTML с фиксированным макетом.

```csharp
public bool FixedLayout { get; set; }
```

### Примечания

PDF и EPUB документы первоначально рендерятся в HTML с фиксированным макетом, чтобы сохранить внешний вид исходного документа. Этот фиксированный макет означает, что все HTML‑элементы имеют точные позиции внутри контейнера заданного размера. Изменение размера окна браузера не влияет на позицию и размер элементов в документе.

Эта опция доступна только при рендеринге в HTML. Значение по умолчанию — `true`. Чтобы рендерить с гибким макетом, установите это свойство в `false`.

При рендеринге с гибким макетом изображения пропускаются. Используйте гибкий макет при рендеринге PDF‑документов с текстовым содержимым.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout).

### См. также

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
