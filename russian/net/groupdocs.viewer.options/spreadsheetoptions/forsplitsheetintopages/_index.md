---
title: "ForSplitSheetIntoPages"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует экземпляр класса SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions для рендеринга листа в страницы."
type: docs
weight: 50
url: /ru/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

Инициализирует экземпляр класса [`SpreadsheetOptions`](../../spreadsheetoptions) для рендеринга листа в страницы.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| countRowsPerPage | Int32 | Количество строк, включаемых в каждую страницу. |

### Возвращаемое значение

Новый экземпляр [`SpreadsheetOptions`](../../spreadsheetoptions) для рендеринга листа в страницы.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *countRowsPerPage* равно нулю или меньше. |

### Примечания

Для получения подробной информации см. [документацию](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).

### См. также

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

Инициализирует экземпляр класса [`SpreadsheetOptions`](../../spreadsheetoptions) для рендеринга листа в страницы.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| countRowsPerPage | Int32 | Количество строк, включаемых в каждую страницу. |
| countColumnsPerPage | Int32 | Количество столбцов, включаемых в каждую страницу. |

### Возвращаемое значение

Новый экземпляр [`SpreadsheetOptions`](../../spreadsheetoptions) для рендеринга листа в страницы.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *countRowsPerPage* равно нулю или меньше. |
| ArgumentException | Выбрасывается, когда *countColumnsPerPage* равно нулю или меньше. |

### Примечания

Для получения подробной информации см. [документацию](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).

### См. также

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
