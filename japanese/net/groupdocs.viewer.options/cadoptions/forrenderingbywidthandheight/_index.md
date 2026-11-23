---
title: "ForRenderingByWidthAndHeight"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "CadOptionsgroupdocs.viewer.options/cadoptions クラスのインスタンスを、幅と高さによるレンダリング用に初期化します。"
type: docs
weight: 40
url: /ja/net/groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight/
---

## CadOptions.ForRenderingByWidthAndHeight method

[`CadOptions`](../../cadoptions) クラスのインスタンスを、幅と高さによるレンダリング用に初期化します。

```csharp
public static CadOptions ForRenderingByWidthAndHeight(int width, int height)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| width | Int32 | 出力結果の幅（ピクセル単位）。 |
| height | Int32 | 出力結果の高さ（ピクセル単位）。 |

### 戻り値

幅と高さによるレンダリング用の新しい [`CadOptions`](../../cadoptions) クラスのインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *width* が 0 以下の場合にスローされます。 |
| ArgumentException | *height* が 0 以下の場合にスローされます。 |

### 備考

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size) を参照してください。

### 関連項目

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
