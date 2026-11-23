---
title: "IPageStreamFactory"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "出力ページストリームのインスタンス化と解放に必要なメソッドを定義します。"
type: docs
weight: 760
url: /ja/net/groupdocs.viewer.interfaces/ipagestreamfactory/
---

## IPageStreamFactory interface

出力ページストリームのインスタンス化と解放に必要なメソッドを定義します。

```csharp
public interface IPageStreamFactory
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreatePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/createpagestream)(int) | 出力ページデータを書き込むために使用されるストリームを作成します。 |
| [ReleasePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/releasepagestream)(int, Stream) | [`CreatePageStream`](./createpagestream) メソッドによって作成されたストリームを解放します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
