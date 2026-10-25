---
title: "添付ファイル"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "メールメッセージのアーカイブ PDF ドキュメントまたは Outlook データファイルに含まれる添付ファイルを表します。"
type: docs
weight: 80
url: /ja/net/groupdocs.viewer.results/attachment/
---

## Attachment class

メール メッセージ、アーカイブ、PDF ドキュメント、または Outlook データ ファイルに含まれる添付ファイルを表します。

```csharp
public class Attachment
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Attachment](attachment#constructor)() | 新しい [`Attachment`](../attachment) クラスのインスタンスを初期化します。 |
| [Attachment](attachment#constructor_1)(string, string) | 新しい [`Attachment`](../attachment) クラスのインスタンスを初期化します。 |
| [Attachment](attachment#constructor_3)(string, string, string, long) | 新しい [`Attachment`](../attachment) クラスのインスタンスを初期化します。 |
| [Attachment](attachment#constructor_2)(string, string, string, FileType, long) | 新しい [`Attachment`](../attachment) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FileName](../../groupdocs.viewer.results/attachment/filename) { get; set; } | 添付ファイル名。 |
| [FilePath](../../groupdocs.viewer.results/attachment/filepath) { get; set; } | 添付ファイルの相対パス（例: folder/file.docx、またはアーカイブのルート、メールメッセージ、データファイルにある場合はファイル名）。 |
| [FileType](../../groupdocs.viewer.results/attachment/filetype) { get; set; } | 添付ファイルの種類。 |
| [Id](../../groupdocs.viewer.results/attachment/id) { get; set; } | この添付ファイルを含む単一ファイルのコンテキスト内での添付ファイルの一意の識別子。 |
| [Size](../../groupdocs.viewer.results/attachment/size) { get; set; } | 添付ファイルのサイズ（バイト単位）。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [ToString](../../groupdocs.viewer.results/attachment/tostring)() | 現在のオブジェクトを表す文字列を返します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Results](../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
