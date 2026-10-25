---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Word ドキュメントのレンダリングオプションを含みます。詳細はドキュメント https//docs.groupdocs.com/viewer/net/renderworddocuments/ を参照してください。"
type: docs
weight: 630
url: /ja/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Word ドキュメントのレンダリングオプションを含みます。詳細については、[documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/) を参照してください。

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | ワードプロセッシングドキュメントのレンダリングオプションを含みます。詳細は [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/) を参照してください。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | ページの下余白を設定します。 |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | このオプションは、アラビア語、ヘブライ語、インド系ラテン文字、またはキリル文字ベースのスクリプトをレンダリングする際に、カーニングやその他の OpenType 機能を有効にします。 |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | 生成された画像の水平解像度（dpi）を取得または設定します。このオプションは、WordProcessing ドキュメントを PNG または JPEG 形式にレンダリングする場合にのみ使用されます。 |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | ページの左余白を設定します。 |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | ロードされた WordProcessing ドキュメントにページ番号付けを強制的に適用できるようにします。デフォルトは NotApply で、ドキュメントはそのままです。 |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | 出力ページのサイズです。デフォルト値は Unspecified で、これはページ設定（ページ設定）でページサイズが指定されていることを意味します。HTM および HTML ファイルをレンダリングする場合、デフォルトのページサイズは Letter（792 x 612 ポイント）に設定されます。その結果、コンテンツの一部がページ枠に収まらないことがあります。コンテンツを収めるために、例えば A3 などの大きなページサイズを設定してください。 |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | トラッキングされた変更（リビジョン）のレンダリングを有効にします。 |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | ページの右余白を設定します。 |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | ページの上余白を設定します。 |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | HTML または PDF にレンダリングする際、このオプションを `true` に設定すると目次からのナビゲーションを無効にできます。HTML レンダリングの場合、相対リンクを持つ `a` タグは `span` タグに置き換えられ、機能は削除されますが視覚的な外観は保持されます。PDF レンダリングの場合、目次はリンクなしのプレーンテキストとしてレンダリングされ、文書セクションへのリンクは含まれません。 |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | 入力の WordProcessing ドキュメントを HTML、PDF、PNG、または JPEG の出力形式で保存する前に、特定のタイプのフィールドを更新するかどうかを決定する値を取得または設定します。このプロパティのデフォルト値は `true` で、保存前にフィールドが更新されます。 |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | 生成された画像の垂直解像度（dpi）を取得または設定します。このオプションは WordProcessing ドキュメントを PNG または JPEG 形式にレンダリングする場合にのみ使用されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | このオプションの完全なディープコピーを作成して返します。 |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | 指定された [`WordProcessingOptions`](../wordprocessingoptions) のインスタンスがこれと等しいかどうかを判断します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
