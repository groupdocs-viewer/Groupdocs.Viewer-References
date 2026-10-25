---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ArchiveViewInfogroupdocs.viewer.results/archiveviewinfo クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/archiveviewinfo/archiveviewinfo/
---

## ArchiveViewInfo() {#constructor}

[`ArchiveViewInfo`](../../archiveviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public ArchiveViewInfo()
```

### 関連項目

* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ArchiveViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

[`ArchiveViewInfo`](../../archiveviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public ArchiveViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileType | FileType | ファイルのタイプです。 |
| ページ | List`1 | 表示するページの一覧です。 |
| folders | List`1 | アーカイブファイルに含まれるフォルダーの一覧です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileType* が null のときにスローされます。 |
| ArgumentNullException | *pages* が null のときにスローされます。 |
| ArgumentNullException | *folders* が null の場合にスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
