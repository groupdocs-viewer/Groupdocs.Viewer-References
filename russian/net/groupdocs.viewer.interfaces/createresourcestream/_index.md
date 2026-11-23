---
title: "CreateResourceStream"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Представляет метод, который создает поток, используемый для записи данных выходного HTML‑ресурса."
type: docs
weight: 720
url: /ru/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

Представляет метод, который создает поток, используемый для записи данных выходного HTML‑ресурса.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| resource | Ресурс | HTML‑ресурс, такой как шрифт, стиль, изображение или графика. |

### Возвращаемое значение

Поток, используемый для записи выходных данных HTML‑ресурса.

### См. также

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
