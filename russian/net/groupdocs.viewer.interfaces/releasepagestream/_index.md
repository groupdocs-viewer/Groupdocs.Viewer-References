---
title: "ReleasePageStream"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Освобождает поток, который был создан методом, связанным с делегатом CreatePageStream./createpagestream."
type: docs
weight: 710
url: /ru/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

Освобождает поток, который был создан методом, связанным с делегатом [`CreatePageStream`](../createpagestream).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| pageStream | Stream | Поток, созданный методом, связанным с делегатом [`CreatePageStream`](../createpagestream). |

### См. также

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
