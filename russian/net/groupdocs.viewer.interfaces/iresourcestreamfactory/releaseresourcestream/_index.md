---
title: "ReleaseResourceStream"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Освобождает поток, созданный методом CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream."
type: docs
weight: 30
url: /ru/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

Освобождает поток, созданный методом [`CreateResourceStream`](../createresourcestream).

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| resource | Ресурс | HTML‑ресурс, такой как шрифт, стиль, изображение или графика. |
| resourceStream | Stream | Поток, созданный методом [`CreateResourceStream`](../createresourcestream). |

### См. также

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
