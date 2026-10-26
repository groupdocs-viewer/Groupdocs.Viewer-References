---
title: "IPageStreamFactory"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Определяет методы, необходимые для создания и освобождения потока выходной страницы."
type: docs
weight: 760
url: /ru/net/groupdocs.viewer.interfaces/ipagestreamfactory/
---

## IPageStreamFactory interface

Определяет методы, необходимые для создания и освобождения потока выходной страницы.

```csharp
public interface IPageStreamFactory
```

## Методы

| Имя | Описание |
| --- | --- |
| [CreatePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/createpagestream)(int) | Создаёт поток, используемый для записи выходных данных страницы. |
| [ReleasePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/releasepagestream)(int, Stream) | Освобождает поток, созданный методом [`CreatePageStream`](./createpagestream). |

### См. также

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
