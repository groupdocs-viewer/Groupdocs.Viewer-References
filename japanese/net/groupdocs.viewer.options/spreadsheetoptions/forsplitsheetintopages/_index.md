---
title: "ForSplitSheetIntoPages"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "シートをページにレンダリングするために、SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions クラスのインスタンスを初期化します。"
type: docs
weight: 50
url: /ja/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

シートをページにレンダリングするために、[`SpreadsheetOptions`](../../spreadsheetoptions) クラスのインスタンスを初期化します。

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| countRowsPerPage | Int32 | 各ページに含める行数。 |

### 戻り値

シートをページにレンダリングするための [`SpreadsheetOptions`](../../spreadsheetoptions) クラスの新しいインスタンス。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *countRowsPerPage* が 0 以下の場合にスローされます。 |

### 備考

詳細については、[documentation](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows) を参照してください。

### 関連項目

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

シートをページにレンダリングするために、[`SpreadsheetOptions`](../../spreadsheetoptions) クラスのインスタンスを初期化します。

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| countRowsPerPage | Int32 | 各ページに含める行数。 |
| countColumnsPerPage | Int32 | 各ページに含める列数。 |

### 戻り値

シートをページにレンダリングするための [`SpreadsheetOptions`](../../spreadsheetoptions) クラスの新しいインスタンス。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *countRowsPerPage* が 0 以下の場合にスローされます。 |
| ArgumentException | *countColumnsPerPage* が 0 以下の場合にスローされます。 |

### 備考

詳細については、[documentation](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns) をご覧ください。

### 関連項目

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
