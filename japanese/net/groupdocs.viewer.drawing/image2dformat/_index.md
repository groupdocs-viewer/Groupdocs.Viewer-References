---
title: "Image2DFormat"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ラスタ形式とベクトル形式の両方をサポートする、最も一般的な2D画像フォーマットを表します。"
type: docs
weight: 960
url: /ja/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

最も一般的な 2D 画像フォーマットを表し、ラスタ形式とベクタ形式の両方をサポートします。

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | BMP 画像タイプ |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | EMF（拡張メタファイル）ベクトル画像タイプ |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | GIF 画像タイプ |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | ICON 画像タイプ |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | JPEG 画像タイプ |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | PNG 画像タイプ |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | SVG ベクトル画像タイプ |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | TIFF（タグ付き画像ファイル形式）ラスタ画像タイプ |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | 未定義の画像タイプ - 通常は発生しない特別な値 |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | WMF（Windows メタファイル）ベクトル画像タイプ |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | 特定の画像タイプのファイル拡張子（先頭のドット文字なし）を小文字で表します。[`Undefined`](./undefined) の値の場合は文字列 'undefined' を返します。 |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | この特定のフォーマットがベクター（`true`）かラスタ（`false`）かを示します |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | 特定の画像タイプの MIME コードを文字列として表します。Undefined タイプの場合は文字列 'unsefined' を返します。 |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | この画像フォーマットの正式名称を返します。NULL を返すことはありません。インスタンスが破損していない限り、例外をスローすることはありません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | 指定されたファイル名から抽出されたファイル拡張子に相当する ImageFormat 値を返します |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | 指定された MIME コードに相当する [`Image2DFormat`](../image2dformat) 値を返します |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | このインスタンスが指定された "[`Image2DFormat`](../image2dformat)" インスタンスと等しいかどうかを判定します |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | このインスタンスが指定されたキャストされていないオブジェクト（おそらく別の "[`Image2DFormat`](../image2dformat)" インスタンス）と等しいかどうかを判定します |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | この特定のインスタンスに対する不変の数値であるハッシュコードを返します |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | [`Name`](./name) プロパティを返します |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | 2つの特定の [`Image2DFormat`](../image2dformat) インスタンスが等しいかどうかを定義します |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | 2つの特定の [`Image2DFormat`](../image2dformat) インスタンスが等しくないかどうかを定義します |

### 関連項目

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
