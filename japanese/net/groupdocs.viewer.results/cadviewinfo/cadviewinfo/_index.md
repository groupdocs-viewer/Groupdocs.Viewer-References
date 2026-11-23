---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "CadViewInfogroupdocs.viewer.results/cadviewinfo クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---

## CadViewInfo constructor

[`CadViewInfo`](../../cadviewinfo) クラスの新しいインスタンスを初期化します。

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileType | FileType | ファイルのタイプです。 |
| ページ | List`1 | 表示するページの一覧です。 |
| レイヤー | List`1 | CAD 図面に含まれるレイヤーの一覧です。 |
| レイアウト | List`1 | CAD 図面に含まれるレイヤーの一覧です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileType* が null のときにスローされます。 |
| ArgumentNullException | *pages* が null のときにスローされます。 |
| ArgumentNullException | *layers* が null の場合にスローされます。 |
| ArgumentNullException | *layouts* が null の場合にスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
