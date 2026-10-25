---
title: "FromOtherWithAlpha"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "指定されたものから新しい Argb32Colorgroupdocs.viewer.drawing/argb32color インスタンスを作成し、アルファ（不透明度）値を再定義します。"
type: docs
weight: 40
url: /ja/net/groupdocs.viewer.drawing/argb32color/fromotherwithalpha/
---

## FromOtherWithAlpha(Argb32Color, byte) {#fromotherwithalpha}

指定されたものから新しい [`Argb32Color`](../../argb32color) インスタンスを作成し、アルファ（不透明度）値を再定義します。

```csharp
public static Argb32Color FromOtherWithAlpha(Argb32Color other, byte newAlpha)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| other | Argb32Color | 新しいインスタンスが作成される元となる他の [`Argb32Color`](../../argb32color) インスタンス |
| newAlpha | Byte | 再定義されたアルファチャンネルの値（255 - 完全に不透明、0 - 完全に透明） |

### 戻り値

新しい[`Argb32Color`](../../argb32color)インスタンス

### 関連項目

* struct [Argb32Color](../../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../../)

---

## FromOtherWithAlpha(Rgb24Color, byte) {#fromotherwithalpha_1}

指定された[`Rgb24Color`](../../rgb24color)から新しい[`Argb32Color`](../../argb32color)インスタンスを作成しますが、指定されたアルファ（不透明度）値を使用します

```csharp
public static Argb32Color FromOtherWithAlpha(Rgb24Color other, byte newAlpha)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| other | Rgb24Color | 新しいインスタンスが作成される元となる他の[`Rgb24Color`](../../rgb24color)インスタンス |
| newAlpha | Byte | アルファチャンネルの値（255 - 完全に不透明、0 - 完全に透明） |

### 戻り値

新しい[`Argb32Color`](../../argb32color)インスタンス

### 関連項目

* struct [Rgb24Color](../../rgb24color)
* struct [Argb32Color](../../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
