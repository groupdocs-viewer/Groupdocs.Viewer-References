---
title: ForSplitSheetIntoPages
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırSpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions sayfayı sayfalara dönüştürmek için.
type: docs
weight: 40
url: /tr/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---
## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

Yeni örneğini başlatır[`SpreadsheetOptions`](../../spreadsheetoptions) sayfayı sayfalara dönüştürmek için.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| countRowsPerPage | Int32 | Her sayfaya eklenecek satır sayısı. |

### Geri dönüş değeri

Yeni örneği[`SpreadsheetOptions`](../../spreadsheetoptions) sayfayı sayfalara dönüştürmek için.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*countRowsPerPage* eşittir veya sıfırdan küçüktür. |

### Ayrıca bakınız

* class [SpreadsheetOptions](../../spreadsheetoptions)
* ad alanı [GroupDocs.Viewer.Options](../../spreadsheetoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

Yeni örneğini başlatır[`SpreadsheetOptions`](../../spreadsheetoptions) sayfayı sayfalara dönüştürmek için.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| countRowsPerPage | Int32 | Her sayfaya eklenecek satır sayısı. |
| countColumnsPerPage | Int32 | Sütunlar her sayfaya eklenecek sayılır. |

### Geri dönüş değeri

Yeni örneği[`SpreadsheetOptions`](../../spreadsheetoptions) sayfayı sayfalara dönüştürmek için.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | Ne zaman atıldı*countRowsPerPage* eşittir veya sıfırdan küçüktür. |
| ArgumentException | Ne zaman atıldı*countColumnsPerPage* eşittir veya sıfırdan küçüktür. |

### Ayrıca bakınız

* class [SpreadsheetOptions](../../spreadsheetoptions)
* ad alanı [GroupDocs.Viewer.Options](../../spreadsheetoptions)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
