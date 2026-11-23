---
title: "ReleaseResourceStream"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "CreateResourceStream./createresourcestream デリゲートに関連付けられたメソッドによって生成されたストリームを解放します。"
type: docs
weight: 730
url: /ja/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

[`CreateResourceStream`](../createresourcestream) デリゲートに関連付けられたメソッドによって生成されたストリームを解放します。

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページ番号。 |
| リソース | Resource | フォント、スタイル、画像、またはグラフィックなどの HTML リソース。 |
| resourceStream | Stream | [`CreateResourceStream`](../createresourcestream) デリゲートに関連付けられたメソッドによって作成されたストリームです。 |

### 関連項目

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
