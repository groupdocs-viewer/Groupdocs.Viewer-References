---
title: "CadViewInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса CadViewInfogroupdocs.viewer.results/cadviewinfo."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---

## CadViewInfo constructor

Инициализирует новый экземпляр класса [`CadViewInfo`](../../cadviewinfo).

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| fileType | FileType | Тип файла. |
| страницы | List`1 | Список страниц для просмотра. |
| layers | List`1 | Список слоёв, содержащихся в CAD‑чертежe. |
| layouts | List`1 | Список слоёв, содержащихся в CAD‑чертежe. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *fileType* равно null. |
| ArgumentNullException | Выбрасывается, когда *pages* равно null. |
| ArgumentNullException | Выбрасывается, когда *layers* равно null. |
| ArgumentNullException | Выбрасывается, когда *layouts* равно null. |

### См. также

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
