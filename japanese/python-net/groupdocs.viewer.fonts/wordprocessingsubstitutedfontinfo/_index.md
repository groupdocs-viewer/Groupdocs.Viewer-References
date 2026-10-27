---
title: "WordProcessingSubstitutedFontInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "WordProcessing ドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化します。このフォントは元々ロードされた Viewer インスタンスのドキュメントでは使用されませんが、置換フォントとして機能します…"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

ロードされた [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) インスタンスのドキュメントで元々使用されていない WordProcessing ドキュメントからのフォント1つのメタ情報とバイナリデータをカプセル化しますが、対象マシンで見つからないフォントの代替フォントとして機能します。代替フォントは WordProcessing フォーマットファミリーにのみ存在します。

不変構造体です。そのインスタンスは [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) の公開 API によって生成・返却され、通常ユーザーが作成すべきではありません。詳細はドキュメントをご覧ください：https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingSubstitutedFontInfo 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | フォント情報を @font-face の at-rule としてシリアライズし、指定されたテキストライターに書き込みます。 |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | フォント情報を含むデバッグ文字列を返します。形式は "original-name -> substituted-name style, format" です。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | 置換フォントの内容をバイト配列として取得します。None になることはありません。 |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | スタイルなしの置換フォントのファミリ名を取得します。 |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | この置換フォント（元のフォントではありません）の形式を取得します。 |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | 対象マシンで見つからない元のフォントのファミリ名を取得します（スタイルなし）。null や空文字列になることはありません。 |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | 元のフォントのスタイルを取得します — Regular、Bold、Italic、または Bold Italic のいずれかです。 |

### 参照
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
