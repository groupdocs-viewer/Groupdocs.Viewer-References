---
title: "LoadOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ファイルを開く際に使用されるオプションを含みます。詳細はこのページ https//docs.groupdocs.com/viewer/net/loading/ とその子ページを参照してください。"
type: docs
weight: 360
url: /ja/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

ファイルを開くために使用されるオプションが含まれています。詳細については、この [page](https://docs.groupdocs.com/viewer/net/loading/) とその子項目を参照してください。

```csharp
public class LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | [`LoadOptions`](../loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions](loadoptions#constructor_1)(FileType) | [`LoadOptions`](../loadoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | [`TXT`](../../groupdocs.viewer/filetype/txt)、[`CSV`](../../groupdocs.viewer/filetype/csv)、[`TSV`](../../groupdocs.viewer/filetype/tsv) ファイルのエンコーディング検出を有効にします。 |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | テキストベースのファイルやメールメッセージを開く際に使用されるエンコーディングを設定します。[`CSV`](../../groupdocs.viewer/filetype/csv)、[`TXT`](../../groupdocs.viewer/filetype/txt)、および[`MSG`](../../groupdocs.viewer/filetype/msg)などが対象です。デフォルト値は UTF8 です。 |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | 開くファイルのタイプを設定します。 |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | 暗号化されたファイルを開くためのパスワードを設定します。 |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | 外部リソースの読み込みタイムアウトを設定します。 |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | 画像などの外部リソースの読み込みを無効にします。ただし[`WhitelistedResources`](./whitelistedresources)は除きます。 |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | 有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的破損を修復しようとします。デフォルト値は `false` です。 |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | `[`SkipExternalResources`](./skipexternalresources)` が `true` に設定されているときに読み込むべき外部リソースに対応する URL フラグメントの一覧です。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
