---
title: "Image2DFormat クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "最も一般的な 2D 画像フォーマットを表し、ラスタ形式とベクタ形式の両方をサポートします。"
type: docs
url: /ja/python-net/groupdocs.viewer.drawing/image2dformat/
is_root: false
weight: 60
---


## Image2DFormat class

最も一般的な 2D 画像フォーマットを表し、ラスタ形式とベクタ形式の両方をサポートします。

Image2DFormat 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#other) | このインスタンスが指定された[`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/)インスタンスと等しいかどうかを判断します。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#obj) | このインスタンスが指定されたオブジェクトと等しいかどうかを判断します。そのオブジェクトは別の[`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/)インスタンスであると想定されます。 |
| [equals_image_2d_format](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_image_2d_format/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/get_hash_code/) | この特定のインスタンスに対する不変の数であるハッシュコードを返します。 |
| [parse_from_filename_with_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/#filename) | 指定されたファイル名から抽出されたファイル拡張子に対応するImage2DFormat値を返します。 |
| [parse_from_mime](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/#mime_code) | 指定されたMIMEコードに対応する[`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/)値を返します。 |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/to_string/) | [`Image2DFormat.name`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/)プロパティを返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [file_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/file_extension/) | 特定の画像タイプのファイル拡張子（先頭のドット文字を除く）を小文字で表します。 |
| [is_vector](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/is_vector/) | フォーマットはベクター（`True`）またはラスタ（`False`）です。 |
| [mime_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/mime_code/) | 特定の画像タイプのMIMEコードを文字列として表します。Undefinedタイプの場合は文字列 'unsefined' を返します。 |
| [name](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) | この画像フォーマットの正式名称です。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [UNDEFINED](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/undefined/) | 未定義の画像タイプ - 通常は発生しない特別な値 |
| [JPEG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/jpeg/) | JPEG画像タイプ |
| [PNG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/png/) | PNG画像タイプ |
| [BMP](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/bmp/) | BMP画像タイプ |
| [GIF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/gif/) | GIF画像タイプ |
| [ICON](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/icon/) | ICON画像タイプ |
| [SVG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/svg/) | SVGベクター画像タイプ |
| [WMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/wmf/) | WMF (Windows MetaFile) ベクター画像タイプ |
| [EMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/emf/) | EMF (Enhanced MetaFile) ベクター画像タイプ |
| [TIFF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/tiff/) | TIFF (Tagged Image File Format) ラスター画像タイプ |

### 参照
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
