---
title: "EmailOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "メールメッセージのレンダリングオプションを含みます。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/emailoptions/
is_root: false
weight: 40
---


## EmailOptions class

メールメッセージのレンダリングオプションを含みます。

GroupDocs.Viewer は、メールメッセージのレンダリング用にさまざまなオプションを指定できる EmailOptions クラスをサポートしています。これらのオプションにアクセスするには、目的の出力形式に応じて、以下のビューオプションクラスのいずれかの EmailOptions プロパティを使用してください：

- [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
- [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
- [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
- [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)

EmailOptions 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/emailoptions/__init__/) | [`EmailOptions`](/viewer/python-net/groupdocs.viewer.options/emailoptions/) クラスのインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [date_time_format](/viewer/python-net/groupdocs.viewer.options/emailoptions/date_time_format/) | 時間形式（TimeZone を含めることができます）。設定されていない場合、現在のシステム形式が使用されます。 |
| [field_text_map](/viewer/python-net/groupdocs.viewer.options/emailoptions/field_text_map/) | メールメッセージの [`Field`](/viewer/python-net/groupdocs.viewer.options/field/) とフィールドテキスト表現とのマッピングです。 |
| [page_size](/viewer/python-net/groupdocs.viewer.options/emailoptions/page_size/) | 出力ページのサイズ。 |
| [time_zone_offset](/viewer/python-net/groupdocs.viewer.options/emailoptions/time_zone_offset/) | メッセージのタイムゾーンオフセットです。 |

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
