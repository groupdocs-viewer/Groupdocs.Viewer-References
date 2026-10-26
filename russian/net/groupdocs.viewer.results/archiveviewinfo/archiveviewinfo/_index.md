---
title: "ArchiveViewInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса ArchiveViewInfogroupdocs.viewer.results/archiveviewinfo."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/archiveviewinfo/archiveviewinfo/
---

## ArchiveViewInfo() {#constructor}

Инициализирует новый экземпляр класса [`ArchiveViewInfo`](../../archiveviewinfo).

```csharp
public ArchiveViewInfo()
```

### См. также

* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ArchiveViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

Инициализирует новый экземпляр класса [`ArchiveViewInfo`](../../archiveviewinfo).

```csharp
public ArchiveViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| fileType | FileType | Тип файла. |
| страницы | List`1 | Список страниц для просмотра. |
| папки | List`1 | Список папок, содержащихся в архивном файле. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *fileType* равно null. |
| ArgumentNullException | Выбрасывается, когда *pages* равно null. |
| ArgumentNullException | Выбрасывается, когда *folders* равно null. |

### См. также

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
