---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions クラスのインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

[`PdfViewOptions`](../../pdfviewoptions) クラスのインスタンスを初期化します。

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createFileStream | CreateFileStream | 出力ファイルデータの書き込みに使用されるストリームを生成するメソッドです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createFileStream* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) を参照してください。

### 関連項目

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

[`PdfViewOptions`](../../pdfviewoptions) クラスのインスタンスを初期化します。

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createFileStream | CreateFileStream | 出力ファイルデータの書き込みに使用されるストリームを生成するメソッドです。 |
| releaseFileStream | ReleaseFileStream | *createFileStream* パラメータに渡されたデリゲートに割り当てられたメソッドが作成したストリームを解放するメソッドです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *createFileStream* が null の場合にスローされます。 |
| ArgumentNullException | *releaseFileStream* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) を参照してください。

### 関連項目

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

[`PdfViewOptions`](../../pdfviewoptions) クラスのインスタンスを初期化します。

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | 出力ファイルストリームの作成と解放のメソッドを実装するファクトリです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileStreamFactory* が null の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) を参照してください。

### 関連項目

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

[`PdfViewOptions`](../../pdfviewoptions) クラスのインスタンスを初期化します。

```csharp
public PdfViewOptions()
```

### 備考

このコンストラクタは、[`PdfViewOptions`](../../pdfviewoptions) のインスタンスを初期化し、出力ファイルのパス形式として "output.pdf" を使用します。出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) を参照してください。

### 関連項目

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

[`PdfViewOptions`](../../pdfviewoptions) クラスのインスタンスを初期化します。

```csharp
public PdfViewOptions(string outputFilePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputFilePath | String | 出力 PDF ファイルのパスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *outputFilePath* が null または空の場合にスローされます。 |

### 備考

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) を参照してください。

### 関連項目

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
