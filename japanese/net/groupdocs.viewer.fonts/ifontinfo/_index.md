---
title: "IFontInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "PDF、ワードプロセッシング、スプレッドシート、プレゼンテーションなど、サポートされているすべての文書形式のフォントファミリーから抽出可能なすべてのフォントの共通インターフェイスです。"
type: docs
weight: 820
url: /ja/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

PDF、WordProcessing、Spreadsheet、Presentation のすべてのサポート対象ドキュメント形式ファミリから抽出できるすべてのフォントに共通のインターフェイスです。

```csharp
public interface IFontInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | フォントのバイナリ内容をバイト配列として取得します。利用可能な場合はその配列を、利用できない場合は `null` を返します。 |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | フォントのファミリ名を文字列として取得します。 |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | このフォントの形式を列挙型で表します — TrueType、TrueType Collection、OpenType、Embedded OpenType、または Unknown。 |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | フォントのスタイルを列挙型で表します — Regular、Bold、Italic、または Bold Italic。一部の文書形式では、[`Regular`](../fontstyles/regular) スタイルのみのフォントが存在する場合があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | このフォント情報を @font-face ルールとしてシリアライズし、指定されたテキストライターに書き込みます。 |

### 関連項目

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
