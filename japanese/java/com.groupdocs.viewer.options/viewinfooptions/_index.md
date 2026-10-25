---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ビューに関する情報取得に使用されるオプションを提供します。"
type: docs
weight: 34
url: /ja/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

ビューに関する情報取得に使用されるオプションを提供します。


ViewInfoOptions クラスは、追加の設定とパラメーターをカプセル化します。
GroupDocs.Viewer コンポーネントのビューに関する情報を取得するために使用できます。


使用例:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | テキスト抽出が有効かどうかを示します。 |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | テキスト抽出が有効かどうかを示すフラグを設定します。 |
|
|  | [getMaxWidth()](#getMaxWidth--) | PNG/JPG にレンダリングするための出力画像の最大幅を返します。 |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 出力画像の最大幅を設定します（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。 |
|
|  | [getMaxHeight()](#getMaxHeight--) | PNG/JPG にレンダリングするための出力画像の最大高さを返します。 |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 出力画像の最大高さを設定します（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。 |
|
|  | [getWidth()](#getWidth--) | 出力画像の幅（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。 |
|
|  | [setWidth(int width)](#setWidth-int-) | 出力画像の幅（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。 |
|
|  | [getHeight()](#getHeight--) | 出力画像の高さ（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。 |
|
|  | [setHeight(int height)](#setHeight-int-) | 出力画像の高さ（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。 |
|
|  | [forHtmlView()](#forHtmlView--) | 新しいインスタンスを初期化します |
ViewInfoOptions
HTML にレンダリングする際にビュー情報を取得するクラス。
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | 新しいインスタンスを初期化します |
ViewInfoOptions
HTML にレンダリングする際にビュー情報を取得するクラス。
|
|  | [forJpgView()](#forJpgView--) | 新しいインスタンスを初期化します |
ViewInfoOptions
JPG にレンダリングする際にビュー情報を取得するクラス。
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | 新しいインスタンスを初期化します |
ViewInfoOptions
JPG にレンダリングする際にビュー情報を取得するクラス。
|
|  | [forPngView()](#forPngView--) | 新しいインスタンスを初期化します |
ViewInfoOptions
PNG にレンダリングする際にビュー情報を取得するクラス。
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | 新しいインスタンスを初期化します |
ViewInfoOptions
PNG にレンダリングする際にビュー情報を取得するクラス。
|
|  | [forPdfView()](#forPdfView--) | PDF にレンダリングする際にビュー情報を取得するために、ViewInfoOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | 新しいインスタンスを初期化します |
ViewInfoOptions
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) オブジェクトに基づくクラス。
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | 新しいインスタンスを初期化します |
ViewInfoOptions
[PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) オブジェクトに基づくクラス。
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | 新しいインスタンスを初期化します |
ViewInfoOptions
[JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) オブジェクトに基づくクラス。
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | [PdfViewOptions] オブジェクトに基づく、[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) クラスの新しいインスタンスを初期化します。 |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


テキスト抽出が有効かどうかを示します。
このプロパティを使用して、ソースドキュメントに含まれるテキストとその座標を取得します。そのデータを使用して画像上に選択可能なテキストを追加したり、画像ベースのレンダリングでテキスト検索を実装したりできます。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/) を参照してください。


**Returns:**
boolean - テキスト抽出が有効な場合は True、無効な場合は false。

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


テキスト抽出が有効かどうかを示すフラグを設定します。
このプロパティを使用して、ソースドキュメントに含まれるテキストとその座標を取得します。そのデータを使用して画像上に選択可能なテキストを追加したり、画像ベースのレンダリングでテキスト検索を実装したりできます。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | extractText | boolean | テキスト抽出を有効にする場合は True、無効にする場合は false。 |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


PNG/JPG にレンダリングするための出力画像の最大幅を返します。
このプロパティを使用して、出力画像の最大幅（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/) を参照してください。プロパティを設定した場合、このプロパティは無視されます。


**Returns:**
int - 出力画像の最大幅です。

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


出力画像の最大幅を設定します（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。
このプロパティを使用して、出力画像の最大幅（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/) を参照してください。プロパティを設定した場合、このプロパティは無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxWidth | int | 出力画像の最大幅です。 |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


PNG/JPG にレンダリングするための出力画像の最大高さを返します。
このプロパティを使用して、出力画像の最大高さ（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/) を参照してください。プロパティを設定した場合、このプロパティは無視されます。


**Returns:**
int - 出力画像の最大高さです。

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


出力画像の最大高さを設定します（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。
このプロパティを使用して、出力画像の最大高さ（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/) を参照してください。プロパティを設定した場合、このプロパティは無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxHeight | int | 出力画像の最大高さです。 |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


出力画像の幅（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。
このプロパティを使用して、出力画像の幅（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/) を参照してください。このプロパティを設定した場合、プロパティは無視されます。


**Returns:**
int - 画像の幅。

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


出力画像の幅（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。
このプロパティを使用して、出力画像の幅（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/) を参照してください。このプロパティを設定した場合、プロパティは無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | width | int | 画像の幅。 |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


出力画像の高さ（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。
このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/) を参照してください。このプロパティを設定した場合、プロパティは無視されます。


**Returns:**
int - 画像の高さ。

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


出力画像の高さ（ピクセル単位、PNG/JPG にレンダリングする場合のみ）。
このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/) を参照してください。このプロパティを設定した場合、プロパティは無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | height | int | 画像の高さ。 |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


新しいインスタンスを初期化します
ViewInfoOptions
HTML にレンダリングする際にビュー情報を取得するクラス。


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


新しいインスタンスを初期化します
ViewInfoOptions
HTML にレンダリングする際にビュー情報を取得するクラス。


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | renderSinglePage | boolean | HTML コンテンツを単一ページにレンダリングできるようにします。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


新しいインスタンスを初期化します
ViewInfoOptions
JPG にレンダリングする際にビュー情報を取得するクラス。


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


新しいインスタンスを初期化します
ViewInfoOptions
JPG にレンダリングする際にビュー情報を取得するクラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | extractText | boolean | テキスト抽出を有効にします。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


新しいインスタンスを初期化します
ViewInfoOptions
PNG にレンダリングする際にビュー情報を取得するクラス。


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


新しいインスタンスを初期化します
ViewInfoOptions
PNG にレンダリングする際にビュー情報を取得するクラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | extractText | boolean | テキスト抽出を有効にします。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


PDF にレンダリングする際にビュー情報を取得するために、ViewInfoOptions クラスの新しいインスタンスを初期化します。


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


新しいインスタンスを初期化します
ViewInfoOptions
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) オブジェクトに基づくクラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML ビューオプション。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


新しいインスタンスを初期化します
ViewInfoOptions
[PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) オブジェクトに基づくクラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG の表示オプションです。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


新しいインスタンスを初期化します
ViewInfoOptions
[JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) オブジェクトに基づくクラス。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG の表示オプションです。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


[PdfViewOptions] オブジェクトに基づく、[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF の表示オプションです。 |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

