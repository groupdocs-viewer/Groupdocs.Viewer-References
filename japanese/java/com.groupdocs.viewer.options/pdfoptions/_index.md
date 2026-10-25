---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "PDF ドキュメントのレンダリングオプションを提供します。"
type: docs
weight: 22
url: /ja/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

PDF ドキュメントのレンダリングオプションを提供します。


PdfOptions クラスは、使用できるさまざまな設定とパラメータをカプセル化します
GroupDocs.Viewer コンポーネントで PDF ドキュメントのレンダリングを制御するために
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/) を参照してください。


使用例:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | 新しいインスタンスを初期化します |
PdfOptions
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | HTML にレンダリングする際にコンテンツのコピー保護をオフにします。 |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | HTML にレンダリングする際にコンテンツのコピー保護をオフにします。 |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | ソースからのテキストが HTML で画像としてレンダリングされるかどうかを決定します。 |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | ソースからのテキストを HTML で画像としてレンダリングするかどうかを設定します。 |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | ページをレンダリングする際の文字位置決めで最大精度を維持するために、文字のグルーピングが無効になっているかどうかを確認します。 |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | ページをレンダリングする際の文字位置決めで最大精度を確保するために、文字のグルーピングを無効にするオプションを設定します。 |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | HTML にレンダリングする際に、テキストとグラフィックのレンダリングが元の PDF ドキュメントの Z オーダーに従うかどうかを確認します。 |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | HTML にレンダリングする際に、テキストとグラフィックのレンダリングを元の PDF ドキュメントの Z オーダーに従って有効または無効にします。 |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | フォントヒンティングが有効かどうかを決定します。 |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | フォントヒンティングを有効にします。 |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | ソース PDF ドキュメントのページサイズと同じピクセルサイズでページのレンダリングを有効にします。 |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | ソース PDF ドキュメントのページサイズと同じピクセルサイズでページのレンダリングを有効にします。 |
|
|  | [getImageQuality()](#getImageQuality--) | HTML にレンダリングする際の画像リソースの出力画像品質を取得します。 |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | HTML にレンダリングする際の画像リソースの出力画像品質を設定します。 |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF は固定フォーマットであるため、すべての要素はページ上に特定の位置を持ちます。 |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF は固定フォーマットであるため、すべての要素はページ上に特定の位置を持ちます。 |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | 出力HTMLドキュメント内の各画像をSVGタグでラップして、出力品質を向上させるためにこのオプションを有効にします。 |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | 出力HTMLドキュメント内の各画像をSVGタグでラップして、出力品質を向上させるためにこのオプションを有効にします。 |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。 |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。 |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | 現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。 |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | 現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にするフラグを設定します。 |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


新しいインスタンスを初期化します
PdfOptions
クラス。


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


HTML にレンダリングする際にコンテンツのコピー保護をオフにします。


テキストや画像のコピーを防止する保護付きでPDFファイルをHTMLにレンダリングする場合、GroupDocs.Viewer は HTML の BODY タグに 'inert' 属性を追加します。
このオプションのデフォルト値は
false
.


コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection)をご覧ください。


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


HTML にレンダリングする際にコンテンツのコピー保護をオフにします。


テキストや画像のコピーを防止する保護付きでPDFファイルをHTMLにレンダリングする場合、GroupDocs.Viewer は HTML の BODY タグに 'inert' 属性を追加します。
このオプションのデフォルト値は
false
.


コード例については、[documentation](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


ソースからのテキストが HTML で画像としてレンダリングされるかどうかを決定します。


このオプションが設定されている場合は
true
, テキストは出力HTMLで画像としてレンダリングされます。
テキストを選択できないようにしたり、文字のレンダリングを修正してHTMLをPDFのように見せるためにこのオプションを有効にします。
このオプションはHTMLへのレンダリング時にサポートされています。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  テキストがHTMLで画像としてレンダリングされる場合、  false  それ以外の場合。

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


ソースからのテキストを HTML で画像としてレンダリングするかどうかを設定します。


このオプションが設定されている場合は
true
, テキストは出力HTMLで画像としてレンダリングされます。
テキストを選択できないようにしたり、文字のレンダリングを修正してHTMLをPDFのように見せるためにこのオプションを有効にします。
このオプションはHTMLへのレンダリング時にサポートされています。


***Note:** The default value is 
false
.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  テキストをHTMLで画像としてレンダリングする場合、  false  それ以外の場合。 |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


ページをレンダリングする際の文字位置決めで最大精度を維持するために、文字のグルーピングが無効になっているかどうかを確認します。
このオプションが有効な場合、文字はグループ化せずにレンダリングされ、最大の精度が保証されます。


***Note:** By default, character grouping is enabled.*
PDFファイルを変換する際、GroupDocs.Viewer はレンダリング性能向上のために個々の文字を単語にグループ化します。文書に象形文字や特殊記号が含まれる場合、より正確なレイアウトを確保するために文字のグループ化を無効にしたいかもしれません。デフォルト値は false です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping)をご覧ください。


**Returns:**
boolean -  true  文字のグループ化が無効な場合、  false  それ以外の場合。

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


ページをレンダリングする際の文字位置決めで最大精度を確保するために、文字のグルーピングを無効にするオプションを設定します。
このオプションは値を設定して有効にした場合、
true
、文字のグループ化が無効になり、最大の精度が保証されます。


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
PDFファイルを変換する際、GroupDocs.Viewer はレンダリング性能向上のために個々の文字を単語にグループ化します。文書に象形文字や特殊記号が含まれる場合、より正確なレイアウトを確保するために文字のグループ化を無効にしたいかもしれません。デフォルト値は false です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true で文字のグループ化を無効にし、 false で有効にします。 |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


HTML にレンダリングする際に、テキストとグラフィックのレンダリングが元の PDF ドキュメントの Z オーダーに従うかどうかを確認します。
このオプションが有効になると、
true
テキストとグラフィックは、元の PDF ドキュメントの Z オーダーに従ってレンダリングされます。


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
デフォルトでは、GroupDocs.Veiewer はテキストとグラフィックを HTML の単一レイヤーとしてレンダリングします。このオプションを使用すると、オブジェクトをソースファイルと同じ順序で配置できます。デフォルト値は false です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering) を参照してください。


**Returns:**
boolean - レイヤー描画が有効な場合は true、そうでない場合は false。

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


HTML にレンダリングする際に、テキストとグラフィックのレンダリングを元の PDF ドキュメントの Z オーダーに従って有効または無効にします。


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
デフォルトでは、GroupDocs.Veiewer はテキストとグラフィックを HTML の単一レイヤーとしてレンダリングします。このオプションを使用すると、オブジェクトをソースファイルと同じ順序で配置できます。デフォルト値は false です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true でレイヤー描画を有効にし、 false で無効にします。 |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


フォントヒンティングが有効かどうかを決定します。フォントヒンティングはアウトラインフォントの表示を調整します。
このオプションは、ソースドキュメントで使用される TrueType (TTF) フォントに対してのみサポートされます。


***Note:** This option is supported when rendering into PNG or JPG formats.*
フォントヒンティングはアウトラインフォントの表示方法を調整します。ソースドキュメントで使用される TTF フォントにのみ適用されます。このオプションは PNG または JPG 形式へのレンダリングで利用可能です。デフォルト値は false です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting) を参照してください。


**Returns:**
boolean - フォントヒンティングが有効な場合は true、そうでない場合は false。

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


フォントヒンティングを有効にします。フォントヒンティングはアウトラインフォントの表示を調整し、ソースドキュメントで使用される TrueType (TTF) フォントに対してのみサポートされます。


***Note:** This option is supported when rendering into PNG or JPG formats.*
フォントヒンティングはアウトラインフォントの表示方法を調整します。ソースドキュメントで使用される TTF フォントにのみ適用されます。このオプションは PNG または JPG 形式へのレンダリングで利用可能です。デフォルト値は false です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true でフォントヒンティングを有効にし、 false で無効にします。 |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


ソース PDF ドキュメントのページサイズと同じピクセルサイズでページのレンダリングを有効にします。


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
デフォルトでは、GroupDocs.Viewer はレンダリング品質向上のために出力画像のページサイズを計算します。このオプションを有効にすると、出力ページがソース PDF ドキュメントのページサイズ（ピクセル単位）と同じになることが保証されます。デフォルト値は false です。
このオプションは PNG または JPG 形式へのレンダリングで利用可能です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages) を参照してください。


**Returns:**
boolean - オプションが有効な場合は true、そうでない場合は false。

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


ソース PDF ドキュメントのページサイズと同じピクセルサイズでページのレンダリングを有効にします。


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
デフォルトでは、GroupDocs.Viewer はレンダリング品質向上のために出力画像のページサイズを計算します。このオプションを有効にすると、出力ページがソース PDF ドキュメントのページサイズ（ピクセル単位）と同じになることが保証されます。デフォルト値は false です。
このオプションは PNG または JPG 形式へのレンダリングで利用可能です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true で元のページサイズでのレンダリングを有効にし、 false で無効にします。 |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


HTML にレンダリングする際の画像リソースの出力画像品質を取得します。デフォルト値は Low です。


このオプションが true に設定されていると、GroupDocs.Viewer は HTML 出力でテキストを画像としてレンダリングします。これによりテキストは選択できず、文字のレンダリングが向上し、HTML で PDF のような外観が保証されます。デフォルト値は false です。
このオプションは HTML へのレンダリングで利用可能です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image) を参照してください。


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


HTML にレンダリングする際の画像リソースの出力画像品質を設定します。デフォルト値は Low です。


このオプションが true に設定されていると、GroupDocs.Viewer は HTML 出力でテキストを画像としてレンダリングします。これによりテキストは選択できず、文字のレンダリングが向上し、HTML で PDF のような外観が保証されます。デフォルト値は false です。
このオプションは HTML へのレンダリングで利用可能です。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | HTML にレンダリングする際の画像リソースの出力画像品質。 |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF は固定フォーマットであるため、すべての要素はページ上に特定の位置を持ちます。
出力された HTML が元の PDF と同じ外観になるように、ドキュメントはデフォルトで固定レイアウトで HTML にレンダリングされます。
固定レイアウトでレンダリングすると、出力 HTML は固定サイズになるため、ウィンドウサイズに関係なく要素は同じ位置に留まります。
流動レイアウトで HTML にレンダリングするには、このプロパティを false に設定します。


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF と EPUB ドキュメントは、元のドキュメントの外観を維持するために、最初に固定レイアウトで HTML にレンダリングされます。この固定レイアウトにより、すべての HTML 要素は設定されたサイズのコンテナ内で正確な位置を持ちます。ブラウザウィンドウのサイズ変更は、ドキュメント内の要素の位置やサイズに影響しません。
このオプションは HTML にレンダリングする場合にのみ利用可能です。デフォルト値は true です。流動レイアウトでレンダリングするには、このプロパティを false に設定します。


使用例:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - 固定レイアウトの場合は true

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF は固定フォーマットであるため、すべての要素はページ上に特定の位置を持ちます。
出力された HTML が元の PDF と同じ外観になるように、ドキュメントはデフォルトで固定レイアウトで HTML にレンダリングされます。
固定レイアウトでレンダリングすると、出力 HTML は固定サイズになるため、ウィンドウサイズに関係なく要素は同じ位置に留まります。
流動レイアウトで HTML にレンダリングするには、このプロパティを false に設定します。


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF と EPUB ドキュメントは、元のドキュメントの外観を維持するために、最初に固定レイアウトで HTML にレンダリングされます。この固定レイアウトにより、すべての HTML 要素は設定されたサイズのコンテナ内で正確な位置を持ちます。ブラウザウィンドウのサイズ変更は、ドキュメント内の要素の位置やサイズに影響しません。
このオプションは HTML にレンダリングする場合にのみ利用可能です。デフォルト値は true です。流動レイアウトでレンダリングするには、このプロパティを false に設定します。


使用例:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fixedLayout | boolean | 固定レイアウトの場合は true |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


出力HTMLドキュメント内の各画像をSVGタグでラップして、出力品質を向上させるためにこのオプションを有効にします。


このオプションは、[PDF とページレイアウト ファイル形式](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) を埋め込みおよび外部リソース付きで HTML にレンダリングする際にサポートされます。


デフォルトでは、PDF とページレイアウト ファイルにレンダリングする際、すべての画像が 1 つの PNG 画像としてレンダリングされます。このレンダリングされた PNG 画像が出力 HTML ドキュメントの背景として使用されます。


詳しく見る:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean - 画像が SVG でラップされている場合は true、そうでない場合は false

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


出力HTMLドキュメント内の各画像をSVGタグでラップして、出力品質を向上させるためにこのオプションを有効にします。


このオプションは、[PDF とページレイアウト ファイル形式](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) を埋め込みおよび外部リソース付きで HTML にレンダリングする際にサポートされます。


デフォルトでは、PDF とページレイアウト ファイルにレンダリングする際、すべての画像が 1 つの PNG 画像としてレンダリングされます。このレンダリングされた PNG 画像が出力 HTML ドキュメントの背景として使用されます。


詳しく見る:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | 画像を SVG でラップする場合は true、そうでない場合は false |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | analyzeFonts | boolean | フォントを表示する場合は true、そうでない場合は false |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。


フォントに関する多くの操作は、そのフォントのライセンスで禁止されている場合、実行できません。
例えば、ライセンス規則で埋め込みが禁止されているフォントは、PDF ドキュメントに埋め込むことができません。
このフラグを使用する際は注意してください。フラグが設定されると、そのフラグを設定した人がすべての責任を負うことを意味します。
自身に対する可能性のあるライセンス/法違反については、自己のリスクで受け入れることになります。このフラグの使用は強く推奨されません
このフラグは、著作権法に違反していないと完全に確信できる場合にのみ使用してください。デフォルトは false です。
コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files) を参照してください。


使用例:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にするフラグを設定します。


フォントに関する多くの操作は、そのフォントのライセンスで禁止されている場合、実行できません。
例えば、ライセンス規則で埋め込みが禁止されているフォントは、PDF ドキュメントに埋め込むことができません。
このフラグを使用する際は注意してください。フラグが設定されると、そのフラグを設定した人がすべての責任を負うことを意味します。
自身に対する可能性のあるライセンス/法違反については、自己のリスクで受け入れることになります。このフラグの使用は強く推奨されません
このフラグは、著作権法に違反していないと完全に確信できる場合にのみ使用してください。デフォルトは false です。
コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files) を参照してください。


使用例:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

