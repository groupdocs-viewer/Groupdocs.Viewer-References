---
title: "ReleaseResourceStream"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream メソッドで作成されたストリームを解放します。"
type: docs
weight: 30
url: /ja/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

[`CreateResourceStream`](../createresourcestream) メソッドで作成されたストリームを解放します。

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページの番号。 |
| リソース | Resource | フォント、スタイル、画像、またはグラフィックなどの HTML リソース。 |
| resourceStream | Stream | [`CreateResourceStream`](../createresourcestream) メソッドで作成されたストリーム。 |

### 関連項目

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
