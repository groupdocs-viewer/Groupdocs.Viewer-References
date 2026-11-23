---
title: "MboxViewInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса MboxViewInfogroupdocs.viewer.results/mboxviewinfo."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/mboxviewinfo/mboxviewinfo/
---

## MboxViewInfo() {#constructor}

Инициализирует новый экземпляр класса [`MboxViewInfo`](../../mboxviewinfo).

```csharp
public MboxViewInfo()
```

### См. также

* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## MboxViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

Инициализирует новый экземпляр класса [`MboxViewInfo`](../../mboxviewinfo).

```csharp
public MboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| fileType | FileType | Тип файла. |
| страницы | List`1 | Список страниц для просмотра. |
| notesCount | Int32 | Количество заметок, содержащихся в файле хранилища базы данных Lotus. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *fileType* равно null. |
| ArgumentNullException | Выбрасывается, когда *pages* равно null. |
| ArgumentNullException | Выбрасывается, когда *notesCount* равно null. |

### См. также

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
