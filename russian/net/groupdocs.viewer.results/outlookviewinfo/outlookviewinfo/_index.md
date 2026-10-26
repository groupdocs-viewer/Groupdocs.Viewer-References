---
title: "OutlookViewInfo"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса OutlookViewInfogroupdocs.viewer.results/outlookviewinfo."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/outlookviewinfo/outlookviewinfo/
---

## OutlookViewInfo() {#constructor}

Инициализирует новый экземпляр класса [`OutlookViewInfo`](../../outlookviewinfo).

```csharp
public OutlookViewInfo()
```

### См. также

* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## OutlookViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

Инициализирует новый экземпляр класса [`OutlookViewInfo`](../../outlookviewinfo).

```csharp
public OutlookViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| fileType | FileType | Тип файла. |
| страницы | List`1 | Список страниц для просмотра. |
| папки | List`1 | Список папок, содержащихся в файле данных Outlook. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *fileType* равно null. |
| ArgumentNullException | Выбрасывается, когда *pages* равно null. |
| ArgumentNullException | Выбрасывается, когда *folders* равно null. |

### См. также

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
