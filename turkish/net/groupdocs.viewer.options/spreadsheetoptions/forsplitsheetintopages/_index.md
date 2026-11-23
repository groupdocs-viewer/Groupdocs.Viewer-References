---
title: "ForSplitSheetIntoPages"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Sayfayı sayfalara render etmek için SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions sınıfının bir örneğini başlatır."
type: docs
weight: 50
url: /tr/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

Sayfayı sayfalara render etmek için [`SpreadsheetOptions`](../../spreadsheetoptions) sınıfının bir örneğini başlatır.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| countRowsPerPage | Int32 | Her sayfaya dahil edilecek satır sayısı. |

### Dönüş Değeri

Sayfayı sayfalara render etmek için yeni bir [`SpreadsheetOptions`](../../spreadsheetoptions) örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *countRowsPerPage* sıfır veya daha az olduğunda fırlatılır. |

### Açıklamalar

Ayrıntılar için, [belgelere](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).

### Ayrıca Bakınız

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

Sayfayı sayfalara render etmek için [`SpreadsheetOptions`](../../spreadsheetoptions) sınıfının bir örneğini başlatır.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| countRowsPerPage | Int32 | Her sayfaya dahil edilecek satır sayısı. |
| countColumnsPerPage | Int32 | Her sayfaya dahil edilecek sütun sayısı. |

### Dönüş Değeri

Sayfayı sayfalara render etmek için yeni bir [`SpreadsheetOptions`](../../spreadsheetoptions) örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *countRowsPerPage* sıfır veya daha az olduğunda fırlatılır. |
| ArgumentException | *countColumnsPerPage* sıfır veya daha az olduğunda fırlatılır. |

### Açıklamalar

Ayrıntılar için, [belgelere](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).

### Ayrıca Bakınız

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
