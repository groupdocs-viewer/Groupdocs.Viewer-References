---
title: "ビューア"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ドキュメントのレンダリングプロセスを制御するメインクラスを表します。"
type: docs
weight: 50
url: /ja/net/groupdocs.viewer/viewer/
---

## Viewer class

ドキュメントのレンダリングプロセスを制御するメインクラスを表します。

```csharp
public class Viewer : IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_4)(Stream) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_12)(string) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_5)(Stream, bool) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | `Viewer` クラスの新しいインスタンスを初期化します。 |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | `Viewer` クラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | ファイルストリームと管理された内部リソースを解放します。 |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | 読み込まれたドキュメントで使用されているすべてのフォントを返します。これには、ドキュメント自体に埋め込まれているフォントと、OS にインストールされドキュメントで使用されているシステムフォントが含まれます。 |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | ドキュメントに含まれる添付ファイルを返します。 |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | ドキュメントに含まれる添付ファイルを返します。 |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | ファイルタイプやファイルが暗号化されているかを示すフラグなど、ファイルに関する情報を返します。 |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | ビューおよびドキュメント固有の情報を返します。 |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | ビューおよびドキュメント固有の情報を返します。 |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | *destination* ストリームに添付ファイルを保存します。 |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | *destination* ストリームに添付ファイルを保存します。 |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | 読み込まれたドキュメントで、ロードされたオプションに従ってテキスト検索と（見つかった場合の）ハイライトを実行します。 |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | すべてのドキュメントページのビューを作成します。 |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | すべてのドキュメントページのビューを作成します。 |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | 特定のドキュメントページのビューを作成します。 |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | 特定のドキュメントページのビューを作成します。 |

### 関連項目

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
