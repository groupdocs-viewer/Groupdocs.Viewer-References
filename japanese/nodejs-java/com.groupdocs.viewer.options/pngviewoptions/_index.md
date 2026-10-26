---
title: "PngViewOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ドキュメントを PNG 形式でレンダリングするオプションを提供します。"
type: docs
weight: 25
url: /ja/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

ドキュメントを PNG 形式でレンダリングするオプションを提供します。

PngViewOptions クラスは、GroupDocs.Viewer コンポーネントでドキュメントを PNG 形式にレンダリングする際に使用できる追加設定およびパラメータをカプセル化します。

使用例:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | PngViewOptions クラスの新しいインスタンスを初期化します。 |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | PngViewOptions クラスの新しいインスタンスを初期化します。 |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | PngViewOptions クラスの新しいインスタンスを初期化します。 |
| [PngViewOptions()](#PngViewOptions--) | PngViewOptions クラスの新しいインスタンスを初期化します。 |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | PngViewOptions クラスの新しいインスタンスを初期化します。 |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | PngViewOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | 出力画像の最大幅（ピクセル単位）を返します。 |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 出力画像の最大幅（ピクセル）を設定します。 |
| [getMaxHeight()](#getMaxHeight--) | 出力画像の最大高さ（ピクセル単位）を返します。 |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 出力画像の最大高さ（ピクセル）を設定します。 |
| [isExtractText()](#isExtractText--) | テキスト抽出が有効かどうかを判定します。 |
| [setExtractText(boolean value)](#setExtractText-boolean-) | テキスト抽出を有効化または無効化します。 |
| [getWidth()](#getWidth--) | 出力画像の幅（ピクセル単位）を返します。 |
| [setWidth(int value)](#setWidth-int-) | 出力画像の幅（ピクセル）を設定します。 |
| [getHeight()](#getHeight--) | 出力画像の高さ（ピクセル単位）を返します。 |
| [setHeight(int value)](#setHeight-int-) | 出力画像の高さ（ピクセル）を設定します。 |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | ドキュメントの保存進行状況を推定するコールバックを取得します。 |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | ドキュメントの保存進行状況を推定するコールバックを設定します。 |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


PngViewOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


PngViewOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream パラメータに割り当てられたメソッドによって作成されたストリームを解放するメソッドです。 |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


PngViewOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 出力ページストリームの作成と解放のためのメソッドを実装するファクトリ。 |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


PngViewOptions クラスの新しいインスタンスを初期化します。

このコンストラクタは、出力ファイルのファイルパス形式として "p\_\{0\}.png" を使用して PngViewOptions の新しいインスタンスを初期化します。出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


PngViewOptions クラスの新しいインスタンスを初期化します。

例として、ファイルパス形式が 'page\_\{0\}.png' の場合、出力ファイルはページ番号に基づき 'page\_1.png'、'page\_2.png' などと命名されます。

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイルパス形式（例: 'page\_\{0\}.png'）。 |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


PngViewOptions クラスの新しいインスタンスを初期化します。

例として、ファイルパス形式が 'page\_\{0\}.png' の場合、出力ファイルはページ番号に基づき 'page\_1.png'、'page\_2.png' などと命名されます。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | ファイルパス形式（例: 'page\_\{0\}.png'）。 |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


出力画像の最大幅（ピクセル単位）を返します。

このプロパティを使用して、出力画像の最大幅（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 出力画像の最大幅。
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


出力画像の最大幅（ピクセル）を設定します。

このプロパティを使用して、出力画像の最大幅（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxWidth | int | 出力画像の最大幅。 |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


出力画像の最大高さ（ピクセル単位）を返します。

このプロパティを使用して、出力画像の最大高さ（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 出力画像の最大高さ。
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


出力画像の最大高さ（ピクセル）を設定します。

このプロパティを使用して、出力画像の最大高さ（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxHeight | int | 出力画像の最大高さ。 |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


テキスト抽出が有効かどうかを判定します。

このオプションは、画像上に選択可能なテキストレイヤーを追加したい場合に役立つことがあります。このプロパティを使用して、ソースドキュメントに含まれるテキストとその座標を取得します。そのデータを使用して、画像上に選択可能なテキストを追加したり、画像ベースのレンダリングでテキスト検索を実装したりできます。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean - テキスト抽出が有効な場合は true、無効な場合は false。
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


テキスト抽出を有効化または無効化します。

このオプションは、画像上に選択可能なテキストレイヤーを追加したい場合に役立つことがあります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true はテキスト抽出を有効にし、false は無効にします。 |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


出力画像の幅（ピクセル単位）を返します。

このプロパティを使用して、出力画像の幅（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。このプロパティを設定した場合、他のプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - 出力画像の幅。
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


出力画像の幅（ピクセル）を設定します。

このプロパティを使用して、出力画像の幅（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。このプロパティを設定した場合、他のプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int | 出力画像の幅。 |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


出力画像の高さ（ピクセル単位）を返します。

このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。このプロパティを設定した場合、他のプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - 出力画像の高さ。
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


出力画像の高さ（ピクセル）を設定します。

このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。このプロパティを設定した場合、他のプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int | 出力画像の高さ。 |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


ドキュメントの保存進行状況を推定するコールバックを取得します。

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - ドキュメント保存進行状況を推定するコールバック。
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


ドキュメントの保存進行状況を推定するコールバックを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | ドキュメント保存進行状況を推定するコールバック。 |

