---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions クラスのインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

[`JpgViewOptions`](../../jpgviewoptions) クラスのインスタンスを初期化します。

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータの書き込みに使用されるストリームを生成するメソッドです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createPageStream* が null の場合にスローされます。 |

### 備考

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

[`JpgViewOptions`](../../jpgviewoptions) クラスのインスタンスを初期化します。

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
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

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

[`JpgViewOptions`](../../jpgviewoptions) クラスのインスタンスを初期化します。

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 出力ページストリームの作成と解放のためのメソッドを実装するファクトリです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* が null の場合にスローされます。 |

### 備考

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。

### 関連項目

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

[`JpgViewOptions`](../../jpgviewoptions) クラスのインスタンスを初期化します。

```csharp
public JpgViewOptions()
```

### 備考

このコンストラクタは、出力ファイルのファイルパス形式として \"p_{0}.jpg\" を使用して、[`JpgViewOptions`](../../jpgviewoptions) のインスタンスを初期化します。出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。

### 関連項目

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

[`JpgViewOptions`](../../jpgviewoptions) クラスのインスタンスを初期化します。

```csharp
public JpgViewOptions(string filePathFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイルパス形式は、例として 'page_{0}.jpg' です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *filePathFormat* が null または空の場合にスローされます。 |

### 備考

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。

### 関連項目

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
