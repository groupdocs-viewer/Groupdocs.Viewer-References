---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "LotusNotesViewInfogroupdocs.viewer.results/lotusnotesviewinfo クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/lotusnotesviewinfo/lotusnotesviewinfo/
---

## LotusNotesViewInfo() {#constructor}

[`LotusNotesViewInfo`](../../lotusnotesviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public LotusNotesViewInfo()
```

### 関連項目

* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## LotusNotesViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

[`LotusNotesViewInfo`](../../lotusnotesviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public LotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileType | FileType | ファイルのタイプです。 |
| ページ | List`1 | 表示するページの一覧です。 |
| notesCount | Int32 | Lotus データベースストレージファイルに含まれるノート数です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileType* が null のときにスローされます。 |
| ArgumentNullException | *pages* が null のときにスローされます。 |
| ArgumentNullException | *notesCount* が null の場合にスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
