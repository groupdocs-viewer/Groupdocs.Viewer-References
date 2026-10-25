---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "このパッケージは、レンダリングプロセス中に使用されるフォントを管理するためのクラスと列挙型を提供します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.viewer.fonts/
---

このパッケージは、レンダリングプロセス中に使用されるフォントを管理するためのクラスと列挙型を提供します。

このパッケージの主なクラスとインターフェイスは次のとおりです：

* [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
* [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
* [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.


GroupDocs.Viewer でのフォントの扱いに関する詳細は、以下をご参照ください。
[GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## クラス

| クラス | 説明 |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | TrueType フォントを含むフォルダーを表します。 |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | UsedFontInfo クラスに存在する可能性のあるすべてのフォント形式を表します。 |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | TrueType フォントを検索するソースを操作するためのメソッドを提供します。 |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | ドキュメントで使用されるフォントの 4 つの可能なスタイル（Regular、Bold、Italic、Bold Italic）を表します。 |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | PDF ドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化し、Viewer インスタンスにロードします。 |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Presentation ドキュメントで使用されるフォントのメタデータとバイナリデータをカプセル化し、Viewer インスタンスにロードします。 |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Spreadsheet ドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化し、Viewer インスタンスにロードします。 |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | WordProcessing ドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化し、Viewer インスタンスにロードします。 |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | GroupDocs.Viewer を介して WordProcessing ドキュメントで使用される置換フォント 1 つのメタデータとバイナリデータをカプセル化します。 |

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | フォントソース用のマーカーインターフェイスです。 |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | PDF、WordProcessing、Spreadsheet、Presentation の各ドキュメント形式から抽出可能なすべてのフォントに対する共通インターフェイスです。 |

## 列挙型

| 列挙体 | 説明 |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | 現在のフォルダーのみ検索するか、現在のフォルダーとすべてのサブフォルダーも検索するかを指定します。 |
