---
title: "MboxViewInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "MboxViewInfogroupdocs.viewer.results/mboxviewinfo クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/mboxviewinfo/mboxviewinfo/
---

## MboxViewInfo() {#constructor}

[`MboxViewInfo`](../../mboxviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public MboxViewInfo()
```

### 関連項目

* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## MboxViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

[`MboxViewInfo`](../../mboxviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public MboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
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
* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
