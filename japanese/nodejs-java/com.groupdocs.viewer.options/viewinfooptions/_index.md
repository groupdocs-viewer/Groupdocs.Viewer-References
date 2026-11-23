---
title: "ViewInfoOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ビューに関する情報取得に使用されるオプションを提供します。"
type: docs
weight: 34
url: /ja/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

ビューに関する情報取得に使用されるオプションを提供します。

ViewInfoOptions クラスは、GroupDocs.Viewer コンポーネントのビューに関する情報を取得するために使用できる追加の設定やパラメーターをカプセル化します。

使用例:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isExtractText()](#isExtractText--) | テキスト抽出が有効かどうかを示します。 |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | テキスト抽出が有効かどうかを示すフラグを設定します。 |
| [getMaxWidth()](#getMaxWidth--) | PNG/JPG へのレンダリング用の出力画像の最大幅を返します。 |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | PNG/JPG のみのレンダリング用に、出力画像の最大幅（ピクセル単位）を設定します。 |
| [getMaxHeight()](#getMaxHeight--) | PNG/JPG へのレンダリング用の出力画像の最大高さを返します。 |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | PNG/JPG のみのレンダリング用に、出力画像の最大高さ（ピクセル単位）を設定します。 |
| [getWidth()](#getWidth--) | PNG/JPG のみのレンダリング用の出力画像の幅（ピクセル単位）です。 |
| [setWidth(int width)](#setWidth-int-) | PNG/JPG のみのレンダリング用の出力画像の幅（ピクセル単位）です。 |
| [getHeight()](#getHeight--) | PNG/JPG のみのレンダリング用の出力画像の高さ（ピクセル単位）です。 |
| [setHeight(int height)](#setHeight-int-) | PNG/JPG のみのレンダリング用の出力画像の高さ（ピクセル単位）です。 |
| [forHtmlView()](#forHtmlView--) | HTML にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | HTML にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [forJpgView()](#forJpgView--) | JPG にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | JPG にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [forPngView()](#forPngView--) | PNG にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [forPngView(boolean extractText)](#forPngView-boolean-) | PNG にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [forPdfView()](#forPdfView--) | PDF にレンダリングする際のビュー情報を取得するために、ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | HtmlViewOptions オブジェクトに基づいて、ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | PngViewOptions オブジェクトに基づいて、ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | JpgViewOptions オブジェクトに基づいて、ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | PdfViewOptions オブジェクトに基づいて、ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


テキスト抽出が有効かどうかを示します。

このプロパティを使用して、ソースドキュメントに含まれるテキストとその座標を取得します。そのデータを使用して画像上に選択可能なテキストを追加したり、画像ベースのレンダリングでテキスト検索を実装したりできます。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
boolean - テキスト抽出が有効な場合は True、そうでない場合は false。
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


テキスト抽出が有効かどうかを示すフラグを設定します。

このプロパティを使用して、ソースドキュメントに含まれるテキストとその座標を取得します。そのデータを使用して画像上に選択可能なテキストを追加したり、画像ベースのレンダリングでテキスト検索を実装したりできます。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| extractText | boolean | テキスト抽出を有効にする場合は True、無効にする場合は false。 |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


PNG/JPG へのレンダリング用の出力画像の最大幅を返します。

このプロパティを使用して、出力画像の最大幅（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 出力画像の最大幅。
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


PNG/JPG のみのレンダリング用に、出力画像の最大幅（ピクセル単位）を設定します。

このプロパティを使用して、出力画像の最大幅（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxWidth | int | 出力画像の最大幅。 |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


PNG/JPG へのレンダリング用の出力画像の最大高さを返します。

このプロパティを使用して、出力画像の最大高さ（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 出力画像の最大高さ。
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


PNG/JPG のみのレンダリング用に、出力画像の最大高さ（ピクセル単位）を設定します。

このプロパティを使用して、出力画像の最大高さ（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。プロパティを設定した場合、このプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxHeight | int | 出力画像の最大高さ。 |

### getWidth() {#getWidth--}
```
public int getWidth()
```


PNG/JPG のみのレンダリング用の出力画像の幅（ピクセル単位）です。

このプロパティを使用して、出力画像の幅（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。このプロパティを設定した場合、他のプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - 画像の幅。
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


PNG/JPG のみのレンダリング用の出力画像の幅（ピクセル単位）です。

このプロパティを使用して、出力画像の幅（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。このプロパティを設定した場合、他のプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | int | 画像の幅。 |

### getHeight() {#getHeight--}
```
public int getHeight()
```


PNG/JPG のみのレンダリング用の出力画像の高さ（ピクセル単位）です。

このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。このプロパティを設定した場合、他のプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - 画像の高さ。
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


PNG/JPG のみのレンダリング用の出力画像の高さ（ピクセル単位）です。

このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。コード例については、[documentation][] を参照してください。このプロパティを設定した場合、他のプロパティは無視されます。


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| height | int | 画像の高さ。 |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


HTML にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


HTML にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderSinglePage | boolean | HTML コンテンツを単一ページにレンダリングできるようにします。 |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


JPG にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


JPG にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| extractText | boolean | テキスト抽出を有効にします。 |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


PNG にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


PNG にレンダリングする際にビューに関する情報を取得するための ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| extractText | boolean | テキスト抽出を有効にします。 |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


PDF にレンダリングする際のビュー情報を取得するために、ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


HtmlViewOptions オブジェクトに基づいて、ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML ビューオプション。 |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


PngViewOptions オブジェクトに基づいて、ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG ビューオプション。 |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


JpgViewOptions オブジェクトに基づいて、ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG ビューオプション。 |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


PdfViewOptions オブジェクトに基づいて、ViewInfoOptions クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF ビューオプション。 |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
