---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "PngViewOptionsgroupdocs.viewer.options/pngviewoptions クラスのインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

[`PngViewOptions`](../../pngviewoptions) クラスのインスタンスを初期化します。

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータの書き込みに使用されるストリームを生成するメソッドです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createPageStream* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) を参照してください。

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

[`PngViewOptions`](../../pngviewoptions) クラスのインスタンスを初期化します。

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータの書き込みに使用されるストリームを生成するメソッドです。 |
| releasePageStream | ReleasePageStream | *createPageStream* パラメータに渡されたデリゲートに割り当てられたメソッドが作成したストリームを解放するメソッドです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createPageStream* が null の場合にスローされます。 |
| ArgumentNullException | *releasePageStream* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) を参照してください。

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

[`PngViewOptions`](../../pngviewoptions) クラスのインスタンスを初期化します。

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 出力ページストリームの作成と解放のためのメソッドを実装するファクトリです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) を参照してください。

### 関連項目

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

[`PngViewOptions`](../../pngviewoptions) クラスのインスタンスを初期化します。

```csharp
public PngViewOptions()
```

### 備考

このコンストラクタは、出力ファイルのファイルパス形式として "p_{0}.png" を使用して、[`PngViewOptions`](../../pngviewoptions) のインスタンスを初期化します。出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) を参照してください。

### 関連項目

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

[`PngViewOptions`](../../pngviewoptions) クラスのインスタンスを初期化します。

```csharp
public PngViewOptions(string filePathFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイルパス形式（例: 'page_{0}.png'）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *filePathFormat* が null または空の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) を参照してください。

### 関連項目

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
