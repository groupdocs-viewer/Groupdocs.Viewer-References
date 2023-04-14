---
title: CreateResourceStream
second_title: GroupDocs.Viewer for .NET API リファレンス
description: 出力 HTML リソース データの書き込みに使用されるストリームを作成します
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream/
---
## IResourceStreamFactory.CreateResourceStream method

出力 HTML リソース データの書き込みに使用されるストリームを作成します。

```csharp
public Stream CreateResourceStream(int pageNumber, Resource resource)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページ数。 |
| resource | Resource | フォント、スタイル、画像、グラフィックなどの HTML リソース。 |

### 戻り値

出力リソース データの書き込みに使用されるストリーム。

### 関連項目

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* 名前空間 [GroupDocs.Viewer.Interfaces](../../iresourcestreamfactory)
* 組み立て [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->