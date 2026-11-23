---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "OutlookViewInfogroupdocs.viewer.results/outlookviewinfo クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/outlookviewinfo/outlookviewinfo/
---

## OutlookViewInfo() {#constructor}

[`OutlookViewInfo`](../../outlookviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public OutlookViewInfo()
```

### 関連項目

* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## OutlookViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

[`OutlookViewInfo`](../../outlookviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public OutlookViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileType | FileType | ファイルのタイプです。 |
| ページ | List`1 | 表示するページの一覧です。 |
| folders | List`1 | Outlook データファイルに含まれるフォルダーの一覧です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileType* が null のときにスローされます。 |
| ArgumentNullException | *pages* が null のときにスローされます。 |
| ArgumentNullException | *folders* が null の場合にスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
