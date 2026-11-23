---
title: "FromMediaType"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ファイルのメディアタイプをファイルタイプにマッピングします。例: application/pdf は PDFgroupdocs.viewer/filetype/pdf にマッピングされます。"
type: docs
weight: 1990
url: /ja/net/groupdocs.viewer/filetype/frommediatype/
---

## FileType.FromMediaType method

ファイルのメディアタイプをファイルタイプにマッピングします。例: 'application/pdf' は [`PDF`](../pdf) にマッピングされます。

```csharp
public static FileType FromMediaType(string mediaType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| mediaType | String | ファイルのメディアタイプ（例: application/pdf）。 |

### 戻り値

該当するメディアタイプが見つかった場合はそれを返し、見つからない場合はデフォルトの [`Unknown`](../unknown) ファイルタイプを返します。

### 関連項目

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
