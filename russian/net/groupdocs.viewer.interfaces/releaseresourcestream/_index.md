---
title: "ReleaseResourceStream"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Освобождает поток, который был создан методом, связанным с делегатом CreateResourceStream./createresourcestream."
type: docs
weight: 730
url: /ru/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

Освобождает поток, который был создан методом, связанным с делегатом [`CreateResourceStream`](../createresourcestream).

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| resource | Ресурс | HTML‑ресурс, такой как шрифт, стиль, изображение или графика. |
| resourceStream | Stream | Поток, созданный методом, связанным с делегатом [`CreateResourceStream`](../createresourcestream). |

### См. также

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
