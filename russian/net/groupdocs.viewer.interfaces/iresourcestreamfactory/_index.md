---
title: "IResourceStreamFactory"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Определяет методы, необходимые для создания URL ресурса, инстанцирования и освобождения выходного потока HTML‑ресурса."
type: docs
weight: 770
url: /ru/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

Определяет методы, необходимые для создания URL ресурса, создания и освобождения потока выходного HTML‑ресурса.

```csharp
public interface IResourceStreamFactory
```

## Методы

| Имя | Описание |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | Создаёт поток, используемый для записи выходных данных HTML‑ресурса. |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | Создаёт URL для HTML‑ресурса. |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | Освобождает поток, созданный методом [`CreateResourceStream`](./createresourcestream). |

### См. также

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
