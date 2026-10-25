---
title: "ReleasePageStream"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "CreatePageStream./createpagestream デリゲートに関連付けられたメソッドによってインスタンス化されたストリームを解放します。"
type: docs
weight: 710
url: /ja/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

[`CreatePageStream`](../createpagestream) デリゲートに関連付けられたメソッドによってインスタンス化されたストリームを解放します。

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページ番号。 |
| pageStream | Stream | [`CreatePageStream`](../createpagestream) デリゲートに関連付けられたメソッドによって作成されたストリームです。 |

### 関連項目

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
