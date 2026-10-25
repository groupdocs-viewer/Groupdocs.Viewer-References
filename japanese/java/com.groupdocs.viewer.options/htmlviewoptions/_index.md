---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ドキュメントを HTML 形式でレンダリングするオプションを提供します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

ドキュメントを HTML 形式でレンダリングするオプションを提供します。


HtmlViewOptions クラスは追加の設定とパラメータをカプセル化します
これは、GroupDocs.Viewer コンポーネントでドキュメントを HTML 形式にレンダリングする制御に使用できます。


詳細については、[topic](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) とその子項目をご覧ください。


使用例:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | レスポンシブレンダリングが有効かどうかを決定します。 |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | レスポンシブレンダリングが有効かどうかを設定します。 |
|
|  | [isMinify()](#isMinify--) | HTML コンテンツと HTML リソースの縮小が有効かどうかを確認します。 |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | HTML コンテンツと HTML リソースの縮小が有効かどうかを設定します。 |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | ドキュメント全体を 1 つの HTML ファイルにレンダリングできるようにします。 |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | ドキュメント全体を 1 つの HTML ファイルにレンダリングできるようにします。 |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | 出力画像の最大幅（ピクセル）を返します。 |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | 出力画像の最大幅（ピクセル）を設定します。 |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | 出力画像の最大高さ（ピクセル）を取得します。 |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | 出力画像の最大高さ（ピクセル）を設定します。 |
|
|  | [getImageWidth()](#getImageWidth--) | 出力画像の幅（ピクセル）を取得します。 |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | 出力画像の幅（ピクセル）を設定します。 |
|
|  | [getImageHeight()](#getImageHeight--) | 単一画像を HTML に変換する際の出力画像の高さ（ピクセル）を取得します。 |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | 単一画像を HTML に変換する際の出力画像の高さ（ピクセル）を設定します。 |
|
|  | [isForPrinting()](#isForPrinting--) | 出力 HTML が印刷用に最適化されるかどうかを確認します。 |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | 出力 HTML が印刷用に最適化されるかどうかを設定します。 |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | HTML ドキュメントからフォントを除外するかどうかを決定します。 |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | HTML ドキュメントからフォントを除外するかどうかを設定します。 |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | HTML ドキュメントから除外するフォント名のリストを取得します。 |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | HTML ドキュメントから除外するフォント名のリストを設定します。 |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | 入力ドキュメントにスクリプトが含まれている場合、結果の HTML ドキュメント内のリンクから JavaScript ソースコードを削除できるようにします。 |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | 入力ドキュメントにスクリプトが含まれている場合、結果の HTML ドキュメント内のリンクから JavaScript ソースコードを削除する権限を設定します。 |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words または Email ドキュメントの保存進行状況を推定するために使用されるコールバックを取得します。 |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words または Email ドキュメントの保存進行状況を推定するために使用されるコールバックを設定します。 |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | 新しいインスタンスを初期化します |
HtmlViewOptions
埋め込みリソースでHTMLにレンダリングするクラスです。
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | 新しいインスタンスを初期化します |
HtmlViewOptions
埋め込みリソースでHTMLにレンダリングするクラスです。
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | 新しいインスタンスを初期化します |
HtmlViewOptions
埋め込みリソースでHTMLにレンダリングするクラスです。
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | 新しいインスタンスを初期化します |
HtmlViewOptions
クラス。
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | 新しいインスタンスを初期化します |
HtmlViewOptions
クラス。
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | 新しいインスタンスを初期化します |
HtmlViewOptions
クラス。
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | 新しいインスタンスを初期化します |
HtmlViewOptions
外部リソースでHTMLにレンダリングするクラスです。
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | 新しいインスタンスを初期化します |
HtmlViewOptions
外部リソースでHTMLにレンダリングするクラスです。
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | 新しいインスタンスを初期化します |
HtmlViewOptions
外部リソースでHTMLにレンダリングするクラスです。
|
|  | [forExternalResources()](#forExternalResources--) | 新しいインスタンスを初期化します |
HtmlViewOptions
クラス。
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | 新しいインスタンスを初期化します |
HtmlViewOptions
クラス。
|
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


レスポンシブレンダリングが有効かどうかを決定します。
レスポンシブウェブページは、異なる画面サイズのデバイスで適切に表示されます。


レスポンシブデザインは、さまざまなデバイスでウェブページが適切に表示されることを目的としています。レスポンシブレイアウトでレンダリングするには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/)をご覧ください。


**Returns:**
boolean -  true  がレスポンシブレンダリングが有効な場合、  false  がそれ以外の場合。

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


レスポンシブレンダリングが有効かどうかを設定します。
レスポンシブウェブページは、異なる画面サイズのデバイスで適切に表示されます。


レスポンシブデザインは、さまざまなデバイスでウェブページが適切に表示されることを目的としています。レスポンシブレイアウトでレンダリングするには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true  はレスポンシブレンダリングを有効にし、  false  は無効にします。 |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


HTML コンテンツと HTML リソースの縮小が有効かどうかを確認します。


出力コンテンツ（HTML、CSS、SVG）の圧縮は、HTMLファイルを最適化する方法の一つです。これを行うには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/minify-html/)をご覧ください。


**Returns:**
boolean -  true  が圧縮が有効な場合、  false  がそれ以外の場合。

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


HTML コンテンツと HTML リソースの縮小が有効かどうかを設定します。


出力コンテンツ（HTML、CSS、SVG）の圧縮は、HTMLファイルを最適化する方法の一つです。これを行うには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/minify-html/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true  は圧縮を有効にし、  false  は無効にします。 |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


ドキュメント全体を 1 つの HTML ファイルにレンダリングできるようにします。

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


ドキュメント全体を 1 つの HTML ファイルにレンダリングできるようにします。

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer("invoice.docx")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


出力画像の最大幅（ピクセル）を返します。
***Note:** This value is used when converting a single image to HTML.
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)をご覧ください。*


**Returns:**
int - 出力画像の最大幅。

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


出力画像の最大幅（ピクセル）を設定します。
***Note:** This value is used when converting a single image to HTML.
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)をご覧ください。*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | imageMaxWidth | int | 出力画像の最大幅です。 |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


出力画像の最大高さ（ピクセル）を取得します。
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)をご覧ください。*


**Returns:**
int - 出力画像の最大高さ。

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


出力画像の最大高さ（ピクセル）を設定します。
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)をご覧ください。*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | imageMaxHeight | int | 出力画像の最大高さです。 |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


出力画像の幅（ピクセル）を取得します。


***Note:** This value is applicable only when converting a single image to HTML.*
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)をご覧ください。


**Returns:**
int - 出力画像の幅。

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


出力画像の幅（ピクセル）を設定します。


***Note:** This value is applicable only when converting a single image to HTML.*
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | imageWidth | int | 出力画像の幅です。 |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


単一画像を HTML に変換する際の出力画像の高さ（ピクセル）を取得します。


詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)をご覧ください。


**Returns:**
int - 出力画像の高さ（ピクセル）。

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


単一画像を HTML に変換する際の出力画像の高さ（ピクセル）を設定します。


詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | imageHeight | int | 出力画像の高さ（ピクセル）。 |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


出力 HTML が印刷用に最適化されるかどうかを確認します。


このオプションを有効にすると、出力HTMLページをベクターSVG形式に変換します。
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/) を参照してください。


**Returns:**
boolean - 出力HTMLを印刷用に最適化する場合は true、そうでない場合は false。

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


出力 HTML が印刷用に最適化されるかどうかを設定します。


このオプションを有効にすると、出力HTMLページをベクターSVG形式に変換します。
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true は出力HTMLを印刷用に最適化し、false はそれ以外です。 |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


HTML ドキュメントからフォントを除外するかどうかを決定します。


デフォルトでは、GroupDocs.Viewer は文書で使用されているフォントをHTMLに埋め込みます。これを防止するには、このプロパティを true に設定します。
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/) を参照してください。


**Returns:**
boolean - フォントを除外する場合は true、そうでない場合は false。

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


HTML ドキュメントからフォントを除外するかどうかを設定します。


デフォルトでは、GroupDocs.Viewer は文書で使用されているフォントをHTMLに埋め込みます。これを防止するには、このプロパティを true に設定します。
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true はフォントを除外し、false はそれ以外です。 |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


HTML ドキュメントから除外するフォント名のリストを取得します。


このオプションはプレゼンテーションでのみサポートされます。
HTMLドキュメントにフォントを含めると、出力ビューの安定性が向上しますが、レンダリング結果のサイズが増加します。
このオプションを使用して、安定性と出力サイズの間の妥協点を見つけます。
多くのシステムにインストールされている一般的なフォント名を含めます。


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) オプションは無効です.*
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/) を参照してください。


**Returns:**
java.util.List<java.lang.String> - HTMLドキュメントから除外するフォント名のリスト。

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


HTML ドキュメントから除外するフォント名のリストを設定します。


このオプションはプレゼンテーションでのみサポートされます。
HTMLドキュメントにフォントを含めると、出力ビューの安定性が向上しますが、レンダリング結果のサイズが増加します。
このオプションを使用して、安定性と出力サイズの間の妥協点を見つけます。
多くのシステムにインストールされている一般的なフォント名を含めます。


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) オプションは無効です.*
詳細とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/exclude-fonts/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.util.List<java.lang.String> | HTMLドキュメントから除外するフォント名のリストです。 |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


入力ドキュメントにスクリプトが含まれている場合、結果のHTMLドキュメント内のリンクからJavaScriptソースコードを削除できるようにします。デフォルトでは有効 (true) です。


JavaScript の削除に関する詳細は、[documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html) を参照してください。


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


入力ドキュメントにスクリプトが含まれている場合、結果のHTMLドキュメント内のリンクからJavaScriptソースコードを削除する権限を設定します。デフォルトでは有効 (true) です。


JavaScript の削除に関する詳細は、[documentation](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words または Email ドキュメントの保存進行状況を推定するために使用されるコールバックを取得します。


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - ドキュメント保存の進行状況を推定するために使用されるコールバック。

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words または Email ドキュメントの保存進行状況を推定するために使用されるコールバックを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | ドキュメント保存の進行状況を推定するために使用されるコールバックです。 |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


新しいインスタンスを初期化します
HtmlViewOptions
埋め込みリソースでHTMLにレンダリングするクラスです。


***Note:** The method takes a 
CreatePageStream
パラメータは、出力ページデータを書き込むためのストリームをインスタンス化するメソッドです。*
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


新しいインスタンスを初期化します
HtmlViewOptions
埋め込みリソースでHTMLにレンダリングするクラスです。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream パラメータに割り当てられたメソッドによって作成されたストリームを解放するメソッドです。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


新しいインスタンスを初期化します
HtmlViewOptions
埋め込みリソースでHTMLにレンダリングするクラスです。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 出力ページストリームの作成と解放のためのメソッドを実装するファクトリです。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


新しいインスタンスを初期化します
HtmlViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


新しいインスタンスを初期化します
HtmlViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | ファイルパスの形式です。例: 'page_{0}.html'。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


新しいインスタンスを初期化します
HtmlViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | ファイルパスの形式です。例: 'page_{0}.html'。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


新しいインスタンスを初期化します
HtmlViewOptions
外部リソースでHTMLにレンダリングするクラスです。


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | createPageStream メソッドによって作成されたストリームを解放するメソッドです。 |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | HTML リソースの URL を作成するメソッドです。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


新しいインスタンスを初期化します
HtmlViewOptions
外部リソースでHTMLにレンダリングするクラスです。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータを書き込むために使用されるストリームを生成するメソッドです。 |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | 出力 HTML リソースデータを書き込むために使用されるストリームを生成するメソッドです。 |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | HTML リソースの URL を作成するメソッドです。 |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream メソッドによって作成されたストリームを解放するメソッドです。 |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | createResourceStream メソッドによって作成されたストリームを解放するメソッドです。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


新しいインスタンスを初期化します
HtmlViewOptions
外部リソースでHTMLにレンダリングするクラスです。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 出力ページストリームの作成と解放のためのメソッドを実装するファクトリです。 |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | リソース URL の作成および出力 HTML リソースストリームの生成/解放のためのメソッドを実装するファクトリです。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


新しいインスタンスを初期化します
HtmlViewOptions
クラス。


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


新しいインスタンスを初期化します
HtmlViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | ファイルパスの形式です。例: 'page_{0}.html'。 |
|
|  | resourceFilePathFormat | java.lang.String | リソースファイルパスの形式です。例: 'page_{0}/resource_{1}'。 |
|
|  | resourceUrlFormat | java.lang.String | リソース URL の形式です。例: 'page_{0}/resource_{1}'。 |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
