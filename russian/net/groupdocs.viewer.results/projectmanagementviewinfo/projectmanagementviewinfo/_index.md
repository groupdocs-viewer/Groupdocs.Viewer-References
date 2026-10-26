---
title: "ProjectManagementViewInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр ProjectManagementViewInfogroupdocs.viewer.results/projectmanagementviewinfo класса."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/projectmanagementviewinfo/projectmanagementviewinfo/
---

## ProjectManagementViewInfo() {#constructor}

Инициализирует новый экземпляр [`ProjectManagementViewInfo`](../../projectmanagementviewinfo) класса.

```csharp
public ProjectManagementViewInfo()
```

### См. также

* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ProjectManagementViewInfo(FileType, List&lt;Page&gt;, DateTime, DateTime) {#constructor_1}

Инициализирует новый экземпляр [`ProjectManagementViewInfo`](../../projectmanagementviewinfo) класса.

```csharp
public ProjectManagementViewInfo(FileType fileType, List<Page> pages, DateTime startDate, 
    DateTime endDate)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| fileType | FileType | Тип файла. |
| страницы | List`1 | Список страниц для просмотра. |
| startDate | DateTime | Дата и время начала проекта. |
| endDate | DateTime | Дата и время, к которым проект должен быть завершён. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *fileType* равно null. |
| ArgumentNullException | Выбрасывается, когда *pages* равно null. |

### См. также

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
