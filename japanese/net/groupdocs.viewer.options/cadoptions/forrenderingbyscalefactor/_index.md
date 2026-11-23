---
title: "ForRenderingByScaleFactor"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "スケールファクターでレンダリングするための CadOptionsgroupdocs.viewer.options/cadoptions クラスのインスタンスを初期化します。"
type: docs
weight: 20
url: /ja/net/groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor/
---

## CadOptions.ForRenderingByScaleFactor method

スケールファクターでレンダリングするための [`CadOptions`](../../cadoptions) クラスのインスタンスを初期化します。

```csharp
public static CadOptions ForRenderingByScaleFactor(float scaleFactor)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| scaleFactor | 単一 | 1 より大きい値は出力結果を拡大し、0 から 1 の間の値は出力結果を縮小します。 |

### 戻り値

スケールファクターでレンダリングするための新しい [`CadOptions`](../../cadoptions) クラスのインスタンス。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *scaleFactor* が 0 以下の場合にスローされます。 |

### 備考

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size) を参照してください。

### 関連項目

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
