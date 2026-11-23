---
title: "ForEmbeddedResources"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "埋め込みリソースを使用して HTML にレンダリングするために、HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions クラスのインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

埋め込みリソースを使用して HTML にレンダリングするために、[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |

### 戻り値

埋め込みリソースを使用して HTML にレンダリングするための [`HtmlViewOptions`](../../htmlviewoptions) クラスの新しいインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createPageStream* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

埋め込みリソースを使用して HTML にレンダリングするために、[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |
| releasePageStream | ReleasePageStream | *createPageStream* パラメータに渡されたデリゲートに割り当てられたメソッドによって作成されたストリームを解放するメソッドです。 |

### 戻り値

埋め込みリソースを使用して HTML にレンダリングするための [`HtmlViewOptions`](../../htmlviewoptions) クラスの新しいインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createPageStream* が null の場合にスローされます。 |
| ArgumentNullException | *releasePageStream* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

埋め込みリソースを使用して HTML にレンダリングするために、[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 出力ページストリームの作成と解放のためのメソッドを実装するファクトリです。 |

### 戻り値

埋め込みリソースを使用して HTML にレンダリングするための [`HtmlViewOptions`](../../htmlviewoptions) クラスの新しいインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。

### 関連項目

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。

### 関連項目

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイルパスの形式（例: 'page_{0}.html'）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *filePathFormat* が null または空の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。

### 関連項目

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
