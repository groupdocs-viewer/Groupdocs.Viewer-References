---
title: "TryRepair"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Когда включено, GroupDocs.Viewer пытается исправить структурные повреждения PDF‑документов. Значение по умолчанию — false."
type: docs
weight: 80
url: /ru/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

Когда включено, GroupDocs.Viewer пытается исправить структурные повреждения PDF‑документов. Значение по умолчанию — `false`.

```csharp
public bool TryRepair { get; set; }
```

### Примечания

Эта функция решает следующие проблемы в PDF‑документе:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### См. также

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
