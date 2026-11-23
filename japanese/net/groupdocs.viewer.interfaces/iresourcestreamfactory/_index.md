---
title: "IResourceStreamFactory"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "リソース URL の作成と出力 HTML リソースストリームのインスタンス化および解放に必要なメソッドを定義します。"
type: docs
weight: 770
url: /ja/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

リソースURLの作成、出力HTMLリソースストリームのインスタンス化と解放に必要なメソッドを定義します。

```csharp
public interface IResourceStreamFactory
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | 出力 HTML リソースデータを書き込むために使用されるストリームを作成します。 |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | HTML リソースの URL を作成します。 |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | [`CreateResourceStream`](./createresourcestream) メソッドによって作成されたストリームを解放します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
