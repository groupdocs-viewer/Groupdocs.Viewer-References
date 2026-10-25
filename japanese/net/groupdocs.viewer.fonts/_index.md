---
title: "GroupDocs.Viewer.Fonts"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "この名前空間は、レンダリングプロセスで使用されるフォントを管理するためのクラスと列挙体を提供します。"
type: docs
weight: 50
url: /ja/net/groupdocs.viewer.fonts/
---

この名前空間は、レンダリングプロセスで使用されるフォントを管理するためのクラスと列挙体を提供します。

## クラス

| クラス | 説明 |
| --- | --- |
| [FolderFontSource](./folderfontsource) | TrueType フォントを含むフォルダーを表します。 |
| [FontSettings](./fontsettings) | TrueType フォントを検索するためのソースを扱うメソッドを提供します。 |
## Structures

| 構造体 | 説明 |
| --- | --- |
| [FontStyles](./fontstyles) | 文書で使用されるフォントの 4 つの可能なスタイルを表します: Regular、Bold、Italic、または Bold Italic |
| [PdfFontInfo](./pdffontinfo) | PDF ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、[`Viewer`](../groupdocs.viewer/viewer) インスタンスにロードされます。このフォントはドキュメントの内容で使用され、ドキュメント自体に埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティング システムにインストールされています。 |
| [PresentationFontInfo](./presentationfontinfo) | プレゼンテーション ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、[`Viewer`](../groupdocs.viewer/viewer) インスタンスにロードされます。このフォントはドキュメントの内容で使用され、ドキュメント自体に埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティング システムにインストールされています。 |
| [SpreadsheetFontInfo](./spreadsheetfontinfo) | スプレッドシート ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、[`Viewer`](../groupdocs.viewer/viewer) インスタンスにロードされます。スプレッドシート ドキュメントは埋め込みフォントを持つことができないため、[`GetAllFonts`](../groupdocs.viewer/viewer/getallfonts) メソッドで返されたこの特定のフォントは、GroupDocs.Viewer が実行されているオペレーティング システムにインストールされています。 |
| [WordProcessingFontInfo](./wordprocessingfontinfo) | WordProcessing ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、[`Viewer`](../groupdocs.viewer/viewer) インスタンスにロードされます。このフォントはドキュメントの内容で使用され、ドキュメント自体に埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティング システムにインストールされています。 |
| [WordProcessingSubstitutedFontInfo](./wordprocessingsubstitutedfontinfo) | WordProcessing ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化します。このフォントは元々ロードされた [`Viewer`](../groupdocs.viewer/viewer) インスタンスのドキュメントで使用されていませんが、対象マシンで見つからないフォントの代替として機能します。代替フォントは WordProcessing 系フォーマットファミリにのみ存在します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IFontInfo](./ifontinfo) | PDF、WordProcessing、Spreadsheet、Presentation のすべてのサポート対象ドキュメント形式ファミリから抽出できるすべてのフォントに共通のインターフェイスです。 |
| [IFontSource](./ifontsource) | フォント ソース用のマーカーインターフェイスです。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [FontFormat](./fontformat) | [`IFontInfo`](../groupdocs.viewer.fonts/ifontinfo) の継承クラスに存在し得るすべてのフォント形式を表します。 |
| [SearchOption](./searchoption) | 現在のフォルダーのみを検索するか、現在のフォルダーとすべてのサブフォルダーを検索するかを指定します。 |

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
