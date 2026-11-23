---
title: "CreateResourceStream"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "出力HTMLリソースデータを書き込むために使用されるストリームをインスタンス化するメソッドを表します。"
type: docs
weight: 720
url: /ja/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

出力HTMLリソースデータを書き込むために使用されるストリームをインスタンス化するメソッドを表します。

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページ番号。 |
| リソース | Resource | フォント、スタイル、画像、またはグラフィックなどの HTML リソース。 |

### 戻り値

出力 HTML リソースデータを書き込むために使用されるストリーム。

### 関連項目

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
