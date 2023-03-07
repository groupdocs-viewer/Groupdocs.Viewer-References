---
title: ForExternalResources
second_title: GroupDocs.Viewer for .NET API リファレンス
description: の新しいインスタンスを初期化しますHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions外部リソースを使用して HTML にレンダリングするためのクラス.
type: docs
weight: 20
url: /ja/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

の新しいインスタンスを初期化します[`HtmlViewOptions`](../../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| createResourceStream | CreateResourceStream | 作成したストリームを解放するメソッド*createPageStream*方法。 |
| createResourceUrl | CreateResourceUrl | HTML リソースの URL を作成するメソッド。 |

### 戻り値

の新しいインスタンス[`HtmlViewOptions`](../../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*createPageStream*無効である。 |
| ArgumentNullException | スローされるタイミング*createResourceStream*無効である。 |
| ArgumentNullException | スローされるタイミング*createResourceUrl*無効である。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* 名前空間 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 組み立て [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

の新しいインスタンスを初期化します[`HtmlViewOptions`](../../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| createResourceStream | CreateResourceStream | 出力 HTML リソース データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| createResourceUrl | CreateResourceUrl | HTML リソースの URL を作成するメソッド。 |
| releasePageStream | ReleasePageStream | 渡されたデリゲートに割り当てられたメソッドによって作成されたストリームを解放するメソッド*createPageStream*パラメータ。 |
| releaseResourceStream | ReleaseResourceStream | 渡されたデリゲートに割り当てられたメソッドによって作成されたストリームを解放するメソッド*createResourceStream*パラメータ。 |

### 戻り値

の新しいインスタンス[`HtmlViewOptions`](../../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*createPageStream*無効である。 |
| ArgumentNullException | スローされるタイミング*createResourceStream*無効である。 |
| ArgumentNullException | スローされるタイミング*createResourceUrl*無効である。 |
| ArgumentNullException | スローされるタイミング*releasePageStream*無効である。 |
| ArgumentNullException | スローされるタイミング*releaseResourceStream*無効である。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* 名前空間 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 組み立て [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

の新しいインスタンスを初期化します[`HtmlViewOptions`](../../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 出力ページ ストリームを作成および解放するためのメソッドを実装するファクトリ。 |
| resourceStreamFactory | IResourceStreamFactory | リソース URL の作成、出力 HTML リソース ストリームのインスタンス化および解放に必要なメソッドを実装するファクトリ。 |

### 戻り値

の新しいインスタンス[`HtmlViewOptions`](../../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*pageStreamFactory*無効である。 |
| ArgumentNullException | スローされるタイミング*resourceStreamFactory*無効である。 |

### 関連項目

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* 名前空間 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 組み立て [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

の新しいインスタンスを初期化します[`HtmlViewOptions`](../../htmlviewoptions)class.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### 備考

このコンストラクターは、の新しいインスタンスを初期化します[`HtmlViewOptions`](../../htmlviewoptions) - 出力 HTML ファイルのファイル パス形式として "p_{0}.html" を使用; - 出力 HTML リソース ファイルのファイル パス形式として "p_{0}_{1}" を使用; - " HTML リソースの URL 形式としての p_{0}_{1}"; 出力ファイルは、アプリケーションの現在の作業ディレクトリに配置されます。

### 関連項目

* class [HtmlViewOptions](../../htmlviewoptions)
* 名前空間 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 組み立て [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

の新しいインスタンスを初期化します[`HtmlViewOptions`](../../htmlviewoptions)class.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | 'page_{0}.html' などのファイル パス形式。 |
| resourceFilePathFormat | String | リソース ファイル パスの形式 (「page_{0}/resource_{1}」など)。 |
| resourceUrlFormat | String | リソースの URL 形式 (「page_{0}/resource_{1}」など)。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | スローされるタイミング*filePathFormat*null または空です。 |
| ArgumentException | スローされるタイミング*resourceFilePathFormat*null または空です。 |
| ArgumentException | スローされるタイミング*resourceUrlFormat*null または空です。 |

### 関連項目

* class [HtmlViewOptions](../../htmlviewoptions)
* 名前空間 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 組み立て [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
