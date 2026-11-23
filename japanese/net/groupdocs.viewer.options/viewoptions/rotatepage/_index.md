---
title: "RotatePage"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ページに時計回りの回転を適用します。"
type: docs
weight: 30
url: /ja/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

ページに時計回りの回転を適用します。

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページ番号は、0 より大きくなければなりません。 |
| rotation | Rotation | 回転値です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *pageNumber* が 0 以下のときにスローされます。 |
| ArgumentException | ページ番号 *pageNumber* の回転が既に追加されているときにスローされます。 |

### 備考

詳細については、[ドキュメント](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/) を参照してください。

### 関連項目

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
