---
title: "PdfViewOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ドキュメントを PDF 形式でレンダリングするオプションを提供します。"
type: docs
weight: 23
url: /ja/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

ドキュメントを PDF 形式でレンダリングするオプションを提供します。

PdfViewOptions クラスは、GroupDocs.Viewer コンポーネントでドキュメントを PDF 形式にレンダリングする際に使用できる追加の設定やパラメータをカプセル化します。詳細については、[documentation][] を参照してください。

使用例:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | PdfViewOptions クラスの新しいインスタンスを初期化します。 |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | PdfViewOptions クラスの新しいインスタンスを初期化します。 |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | PdfViewOptions クラスの新しいインスタンスを初期化します。 |
| [PdfViewOptions()](#PdfViewOptions--) | PdfViewOptions クラスの新しいインスタンスをデフォルト設定で初期化します。 |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | PdfViewOptions クラスの新しいインスタンスを初期化します。 |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | PdfViewOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | さまざまなオプションを使用した最適化手法を適用して、出力 PDF ファイルのサイズを削減します。 |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | さまざまなオプションを使用した最適化手法を適用して、出力 PDF ファイルのサイズを削減します。 |
| [getImageMaxWidth()](#getImageMaxWidth--) | 出力画像の最大幅（ピクセル）を取得します。 |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | 出力画像の最大幅（ピクセル）を設定します。 |
| [getImageMaxHeight()](#getImageMaxHeight--) | 出力画像の最大高さ（ピクセル）を取得します。 |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | 出力画像の最大高さ（ピクセル）を設定します。 |
| [getImageWidth()](#getImageWidth--) | 出力画像の幅（ピクセル）を取得します。 |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | 出力画像の幅（ピクセル）を設定します。 |
| [getImageHeight()](#getImageHeight--) | 出力画像の高さ（ピクセル）を取得します。 |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | 出力画像の高さ（ピクセル）を設定します。 |
| [getSecurity()](#getSecurity--) | 出力PDFドキュメントのセキュリティオプションを取得します。 |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | 出力PDFドキュメントのセキュリティオプションを設定します。 |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | WordsまたはEmailドキュメントの保存進行状況を推定するために使用されるコールバックを取得します。 |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | WordsまたはEmailドキュメントの保存進行状況を推定するために使用されるコールバックを設定します。 |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


PdfViewOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


PdfViewOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | 出力ファイルデータを書き込むためのストリームをインスタンス化する際に使用されるメソッドです。 |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | createFileStream メソッドによって作成されたストリームを解放する際に使用されるメソッドです。 |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


PdfViewOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | 出力ファイルストリームの作成と解放のためのメソッドを実装するファクトリです。 |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


PdfViewOptions クラスの新しいインスタンスをデフォルト設定で初期化します。

このコンストラクタは、出力ファイルのファイルパス形式として "output.pdf" を使用して新しい PdfViewOptions オブジェクトを作成します。出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


PdfViewOptions クラスの新しいインスタンスを初期化します。

このコンストラクタは、出力PDFファイルのパスを表す指定された outputFilePath パラメータを使用して新しい PdfViewOptions オブジェクトを作成します。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFilePath | java.lang.String | 出力PDFファイルのパス。 |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


PdfViewOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | 出力PDFファイルのパス。 |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


さまざまなオプションを使用した最適化手法を適用して、出力 PDF ファイルのサイズを削減します。

このオプションは、PDFへの変換がサポートされているすべての入力ファイル形式で使用できます: [Supported document formats][] 詳細およびコードサンプルについては、この [page][] とその子ページを参照してください。


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


さまざまなオプションを使用した最適化手法を適用して、出力 PDF ファイルのサイズを削減します。

このオプションは、PDFへの変換がサポートされているすべての入力ファイル形式で使用できます: [Supported document formats][] 詳細およびコードサンプルについては、この [page][] とその子ページを参照してください。


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions オブジェクトまたは null。 |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


出力画像の最大幅（ピクセル）を取得します。このパラメータは、単一画像をHTMLに変換する場合にのみ適用されます。

このプロパティを使用して、出力画像の最大幅（ピクセル）を設定します。GroupDocs.Viewer は単一画像をPDFにレンダリングする際にこのプロパティを適用します。詳細については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 出力画像の最大幅（ピクセル）。
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


出力画像の最大幅（ピクセル）を設定します。このパラメータは、単一画像をHTMLに変換する場合にのみ適用されます。

このプロパティを使用して、出力画像の最大幅（ピクセル）を設定します。GroupDocs.Viewer は単一画像をPDFにレンダリングする際にこのプロパティを適用します。詳細については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageMaxWidth | int | 出力画像の最大幅（ピクセル）。 |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


出力画像の最大高さ（ピクセル）を取得します。このパラメータは、単一画像をHTMLに変換する場合にのみ適用されます。

このプロパティを使用して、出力画像の最大高さ（ピクセル）を設定します。GroupDocs.Viewer は単一画像をPDFにレンダリングする際にこのプロパティを適用します。詳細については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 出力画像の最大高さ（ピクセル）。
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


出力画像の最大高さ（ピクセル単位）を設定します。このパラメーターは、単一画像をHTMLに変換する場合にのみ適用されます。

このプロパティを使用して、出力画像の最大高さ（ピクセル）を設定します。GroupDocs.Viewer は、単一画像をHTMLにレンダリングする場合にのみこのプロパティを適用します。詳細については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageMaxHeight | int | 出力画像の最大高さ（ピクセル）。 |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


出力画像の幅（ピクセル）を取得します。このパラメーターは、単一画像をHTMLに変換する場合にのみ適用されます。

このプロパティを使用して、出力画像の幅（ピクセル）を設定します。GroupDocs.Viewer は、単一画像をPDFにレンダリングする際にこのプロパティを適用します。詳細については、[documentation][] を参照してください。このプロパティを設定した場合、  プロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 出力画像の幅（ピクセル）。
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


出力画像の幅（ピクセル）を設定します。このパラメーターは、単一画像PDFに変換する場合にのみ適用されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageWidth | int | 出力画像の幅（ピクセル）。 |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


出力画像の高さ（ピクセル）を取得します。このパラメーターは、単一画像をHTMLに変換する場合にのみ適用されます。

このプロパティを使用して、出力画像の高さ（ピクセル）を設定します。GroupDocs.Viewer は、単一画像をHTMLにレンダリングする場合にのみこのプロパティを適用します。詳細については、[documentation][] を参照してください。このプロパティを設定した場合、  プロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 出力画像の高さ（ピクセル）。
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


出力画像の高さ（ピクセル）を設定します。このパラメーターは、単一画像をHTMLに変換する場合にのみ適用されます。

このプロパティを使用して、出力画像の高さ（ピクセル）を設定します。GroupDocs.Viewer は、単一画像をHTMLにレンダリングする場合にのみこのプロパティを適用します。詳細については、[documentation][] を参照してください。このプロパティを設定した場合、  プロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageHeight | int | 出力画像の高さ（ピクセル）。 |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


出力PDFドキュメントのセキュリティオプションを取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


出力PDFドキュメントのセキュリティオプションを設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | 出力PDFドキュメントのセキュリティオプション。 |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


WordsまたはEmailドキュメントの保存進行状況を推定するために使用されるコールバックを取得します。

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - ドキュメント保存進行状況を推定するコールバック。
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


WordsまたはEmailドキュメントの保存進行状況を推定するために使用されるコールバックを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | ドキュメント保存進行状況を推定するコールバック。 |

