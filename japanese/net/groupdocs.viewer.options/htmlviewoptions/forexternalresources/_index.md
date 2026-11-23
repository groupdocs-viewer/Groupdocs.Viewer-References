---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "外部リソースを使用して HTML にレンダリングするために、HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions クラスのインスタンスを初期化します。"
type: docs
weight: 20
url: /ja/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

外部リソースを使用して HTML にレンダリングするために、[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |
| createResourceStream | CreateResourceStream | *createPageStream* メソッドで作成されたストリームを解放するメソッドです。 |
| createResourceUrl | CreateResourceUrl | HTML リソースの URL を作成するメソッドです。 |

### 戻り値

外部リソースを使用して HTML にレンダリングするための [`HtmlViewOptions`](../../htmlviewoptions) クラスの新しいインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createPageStream* が null の場合にスローされます。 |
| ArgumentNullException | *createResourceStream* が null の場合にスローされます。 |
| ArgumentNullException | *createResourceUrl* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

外部リソースを使用して HTML にレンダリングするために、[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |
| createResourceStream | CreateResourceStream | 出力HTMLリソースデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| createResourceUrl | CreateResourceUrl | HTML リソースの URL を作成するメソッドです。 |
| releasePageStream | ReleasePageStream | *createPageStream* パラメータに渡されたデリゲートに割り当てられたメソッドによって作成されたストリームを解放するメソッドです。 |
| releaseResourceStream | ReleaseResourceStream | *createResourceStream* パラメータに渡されたデリゲートに割り当てられたメソッドによって作成されたストリームを解放するメソッドです。 |

### 戻り値

外部リソースを使用して HTML にレンダリングするための [`HtmlViewOptions`](../../htmlviewoptions) クラスの新しいインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createPageStream* が null の場合にスローされます。 |
| ArgumentNullException | *createResourceStream* が null の場合にスローされます。 |
| ArgumentNullException | *createResourceUrl* が null の場合にスローされます。 |
| ArgumentNullException | *releasePageStream* が null の場合にスローされます。 |
| ArgumentNullException | *releaseResourceStream* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

外部リソースを使用して HTML にレンダリングするために、[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 出力ページストリームの作成と解放のためのメソッドを実装するファクトリです。 |
| resourceStreamFactory | IResourceStreamFactory | リソースURLの作成、出力HTMLリソースストリームのインスタンス化および解放に必要なメソッドを実装するファクトリです。 |

### 戻り値

外部リソースを使用して HTML にレンダリングするための [`HtmlViewOptions`](../../htmlviewoptions) クラスの新しいインスタンスです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* が null の場合にスローされます。 |
| ArgumentNullException | *resourceStreamFactory* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。

### 関連項目

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForExternalResources()
```

### 備考

このコンストラクタは [`HtmlViewOptions`](../../htmlviewoptions) のインスタンスを初期化します。

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。

### 関連項目

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

[`HtmlViewOptions`](../../htmlviewoptions) クラスのインスタンスを初期化します。

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイルパスの形式（例: 'page_{0}.html'）です。 |
| resourceFilePathFormat | String | リソースファイルパスの形式（例: 'page_{0}/resource_{1}'）です。 |
| resourceUrlFormat | String | リソースURLの形式（例: 'page_{0}/resource_{1}'）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *filePathFormat* が null または空の場合にスローされます。 |
| ArgumentException | *resourceFilePathFormat* が null または空の場合にスローされます。 |
| ArgumentException | *resourceUrlFormat* が null または空の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。

### 関連項目

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
