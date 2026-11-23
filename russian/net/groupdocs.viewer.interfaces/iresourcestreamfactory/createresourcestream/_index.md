---
title: "CreateResourceStream"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Создаёт поток, используемый для записи выходных данных HTML‑ресурса."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream/
---

## IResourceStreamFactory.CreateResourceStream method

Создаёт поток, используемый для записи выходных данных HTML‑ресурса.

```csharp
public Stream CreateResourceStream(int pageNumber, Resource resource)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| resource | Ресурс | HTML‑ресурс, такой как шрифт, стиль, изображение или графика. |

### Возвращаемое значение

Поток, используемый для записи выходных данных ресурса.

### См. также

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
