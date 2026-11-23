---
title: "PdfOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "PDF ドキュメントのレンダリングオプションを提供します。"
type: docs
weight: 22
url: /ja/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

PDF ドキュメントのレンダリングオプションを提供します。

PdfOptions クラスは、GroupDocs.Viewer コンポーネントで PDF ドキュメントのレンダリングを制御するために使用できるさまざまな設定とパラメータをカプセル化します。詳細については、[documentation][] を参照してください。

使用例:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | PdfOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | HTML にレンダリングする際にコンテンツのコピー保護をオフにします。 |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | HTML にレンダリングする際にコンテンツのコピー保護をオフにします。 |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | ソースからのテキストが HTML で画像としてレンダリングされるかどうかを決定します。 |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | ソースからのテキストを HTML で画像としてレンダリングするかどうかを設定します。 |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | ページをレンダリングする際の文字位置決めで最大精度を維持するために、文字のグルーピングが無効になっているかどうかを確認します。 |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | ページをレンダリングする際の文字位置決めで最大精度を確保するために、文字のグルーピングを無効にするオプションを設定します。 |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | HTML にレンダリングする際に、テキストとグラフィックのレンダリングが元の PDF ドキュメントの Z オーダーに従うべきかどうかを確認します。 |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | HTML にレンダリングする際に、元の PDF ドキュメントの Z オーダーに従ってテキストとグラフィックのレンダリングを有効または無効にします。 |
| [isEnableFontHinting()](#isEnableFontHinting--) | フォントヒンティングが有効かどうかを決定します。 |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | フォントヒンティングを有効にします。 |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | 元の PDF ドキュメントのページサイズと同じピクセルサイズでページをレンダリングできるようにします。 |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | 元の PDF ドキュメントのページサイズと同じピクセルサイズでページをレンダリングできるようにします。 |
| [getImageQuality()](#getImageQuality--) | HTML にレンダリングする際の画像リソースの出力画像品質を取得します。 |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | HTML にレンダリングする際の画像リソースの出力画像品質を設定します。 |
| [isFixedLayout()](#isFixedLayout--) | PDF は固定フォーマットであるため、すべての要素はページ上の特定の位置に配置されます。 |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF は固定フォーマットであるため、すべての要素はページ上の特定の位置に配置されます。 |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | 出力品質を向上させるために、出力 HTML ドキュメント内の各画像を SVG タグでラップするオプションを有効にします。 |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | 出力品質を向上させるために、出力 HTML ドキュメント内の各画像を SVG タグでラップするオプションを有効にします。 |
| [isFixLinkIssue()](#isFixLinkIssue--) | HTML ページ全体のコンテンツがリンクになる問題を修正しようとします。 |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | HTML ページ全体のコンテンツがリンクになる問題を修正しようとします。 |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。 |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | テキスト内のすべての文字が表示できるように、必要に応じてフォントを置き換えます。 |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | 現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。 |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | 現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にするフラグを設定します。 |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


PdfOptions クラスの新しいインスタンスを初期化します。

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


HTML にレンダリングする際にコンテンツのコピー保護をオフにします。

テキストと画像のコピーから保護された PDF ファイルを HTML にレンダリングする際、GroupDocs.Viewer は HTML の BODY タグに 'inert' 属性を追加します。このオプションのデフォルト値は false です。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


HTML にレンダリングする際にコンテンツのコピー保護をオフにします。

テキストと画像のコピーから保護された PDF ファイルを HTML にレンダリングする際、GroupDocs.Viewer は HTML の BODY タグに 'inert' 属性を追加します。このオプションのデフォルト値は false です。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


ソースからのテキストが HTML で画像としてレンダリングされるかどうかを決定します。

このオプションを true に設定すると、テキストが出力 HTML で画像としてレンダリングされます。このオプションを有効にすると、テキストを選択できなくしたり、文字のレンダリングを修正して HTML を PDF のように見せることができます。このオプションは HTML へのレンダリング時にサポートされます。

***Note:** The default value is  false .*

**Returns:**
boolean - テキストが HTML で画像としてレンダリングされる場合は true、そうでない場合は false。
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


ソースからのテキストを HTML で画像としてレンダリングするかどうかを設定します。

このオプションを true に設定すると、テキストが出力 HTML で画像としてレンダリングされます。このオプションを有効にすると、テキストを選択できなくしたり、文字のレンダリングを修正して HTML を PDF のように見せることができます。このオプションは HTML へのレンダリング時にサポートされます。

***Note:** The default value is  false .*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderTextAsImage | boolean | true: テキストを HTML で画像としてレンダリングする、false: それ以外。 |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


ページをレンダリングする際の文字配置で最大精度を保つために、文字のグルーピングが無効になっているかを確認します。このオプションが有効になると、文字はグルーピングせずにレンダリングされ、最大精度が保証されます。

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean - 文字のグルーピングが無効な場合は true、そうでない場合は false。
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


ページをレンダリングする際の文字配置で最大精度を確保するために、文字のグルーピングを無効にするオプションを設定します。値を true に設定してこのオプションを有効にすると、文字のグルーピングが無効になり、最大精度が保証されます。

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true: 文字のグルーピングを無効にする、false: 有効にする。 |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


HTML にレンダリングする際に、テキストとグラフィックの描画が元の PDF ドキュメントの Z 順序に従うかどうかを確認します。このオプションを true に設定すると、テキストとグラフィックは元の PDF の Z 順序に従って描画されます。

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean - レイヤー描画が有効な場合は true、そうでない場合は false。
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


HTML にレンダリングする際に、元の PDF ドキュメントの Z オーダーに従ってテキストとグラフィックのレンダリングを有効または無効にします。

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true: レイヤー描画を有効にする、false: 無効にする。 |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


フォントヒンティングが有効かどうかを決定します。フォントヒンティングはアウトラインフォントの表示を調整します。このオプションは、ソース文書で使用される TrueType (TTF) フォントにのみ対応しています。

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean - フォントヒンティングが有効な場合は true、そうでない場合は false。
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


フォントヒンティングを有効にします。フォントヒンティングはアウトラインフォントの表示を調整し、ソース文書で使用される TrueType (TTF) フォントにのみ対応しています。

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true: フォントヒンティングを有効にする、false: 無効にする。 |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


元の PDF ドキュメントのページサイズと同じピクセルサイズでページをレンダリングできるようにします。

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean - オプションが有効な場合は true、そうでない場合は false。
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


元の PDF ドキュメントのページサイズと同じピクセルサイズでページをレンダリングできるようにします。

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true: 元のページサイズでのレンダリングを有効にする、false: それ以外。 |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


HTML にレンダリングする際の画像リソースの出力画像品質を取得します。デフォルト値は Low です。

このオプションを true に設定すると、GroupDocs.Viewer は HTML 出力でテキストを画像としてレンダリングします。これによりテキストは選択できなくなり、文字のレンダリングが向上して HTML が PDF のような外観になります。デフォルト値は false です。このオプションは HTML へのレンダリングで利用可能です。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


HTML にレンダリングする際の画像リソースの出力画像品質を設定します。デフォルト値は Low です。

このオプションを true に設定すると、GroupDocs.Viewer は HTML 出力でテキストを画像としてレンダリングします。これによりテキストは選択できなくなり、文字のレンダリングが向上して HTML が PDF のような外観になります。デフォルト値は false です。このオプションは HTML へのレンダリングで利用可能です。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | HTML にレンダリングする際の画像リソースの出力画像品質。 |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF は固定フォーマットであり、すべての要素はページ上の特定の位置にあります。出力 HTML が元の PDF と同じ外観になるように、既定では固定レイアウトで HTML にレンダリングされます。固定レイアウトでレンダリングすると、出力 HTML のサイズは固定されるため、ウィンドウサイズに関係なく要素は同じ位置に留まります。流動レイアウトで HTML にレンダリングするには、このプロパティを false に設定します。

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

使用例:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - 固定レイアウトの場合は true
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF は固定フォーマットであり、すべての要素はページ上の特定の位置にあります。出力 HTML が元の PDF と同じ外観になるように、既定では固定レイアウトで HTML にレンダリングされます。固定レイアウトでレンダリングすると、出力 HTML のサイズは固定されるため、ウィンドウサイズに関係なく要素は同じ位置に留まります。流動レイアウトで HTML にレンダリングするには、このプロパティを false に設定します。

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

使用例:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fixedLayout | boolean | 固定レイアウトの場合は true |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


出力品質を向上させるために、出力 HTML ドキュメント内の各画像を SVG タグでラップするオプションを有効にします。

このオプションは、[PDF and Page Layout file formats][] を埋め込みリソースまたは外部リソース付きで HTML にレンダリングする際にサポートされます。

既定では、PDF およびページレイアウトファイルにレンダリングする際、すべての画像が 1 つの PNG 画像としてレンダリングされます。レンダリングされた PNG 画像は、出力 HTML ドキュメントの背景として使用されます。

詳しくは以下をご覧ください：

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean -  true  画像が SVG でラップされている場合は true、そうでない場合は false。
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


出力品質を向上させるために、出力 HTML ドキュメント内の各画像を SVG タグでラップするオプションを有効にします。

このオプションは、[PDF and Page Layout file formats][] を埋め込みリソースまたは外部リソース付きで HTML にレンダリングする際にサポートされます。

既定では、PDF およびページレイアウトファイルにレンダリングする際、すべての画像が 1 つの PNG 画像としてレンダリングされます。レンダリングされた PNG 画像は、出力 HTML ドキュメントの背景として使用されます。

詳しくは以下をご覧ください：

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true  画像を SVG でラップする場合は true、そうでない場合は false。 |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


HTML ページ全体のコンテンツがリンクである場合の問題を修正しようとします。入力形式が PDF、出力形式が HTML（埋め込みまたは外部リソース付き）の場合にのみ機能します。既定では無効（false）です。このオプションを有効にするのは、何をなぜ行うかを理解している場合に限ります。このオプションを有効にすると、ドキュメントの処理時間が増加します。

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


HTML ページ全体のコンテンツがリンクである場合の問題を修正しようとします。入力形式が PDF、出力形式が HTML（埋め込みまたは外部リソース付き）の場合にのみ機能します。既定では無効（false）です。このオプションを有効にするのは、何をなぜ行うかを理解している場合に限ります。このオプションを有効にすると、ドキュメントの処理時間が増加します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fixLinkIssue | boolean | 問題を修正する場合は true、そうでない場合は false。 |

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
| analyzeFonts | boolean | フォントを表示する場合は true、そうでない場合は false。 |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。

フォントに関する多くの操作は、そのフォントのライセンスで禁止されている場合は実行できません。たとえば、ライセンス条件で埋め込みが禁止されているフォントは PDF 文書に埋め込めません。このフラグを使用する際は注意が必要です。フラグが設定されている場合、設定者がライセンスや法的違反に対する全責任を負うことを意味します。したがって、自己責任で使用してください。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。既定は false です。コード例については、[documentation][] を参照してください。

使用例:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にするフラグを設定します。

フォントに関する多くの操作は、そのフォントのライセンスで禁止されている場合は実行できません。たとえば、ライセンス条件で埋め込みが禁止されているフォントは PDF 文書に埋め込めません。このフラグを使用する際は注意が必要です。フラグが設定されている場合、設定者がライセンスや法的違反に対する全責任を負うことを意味します。したがって、自己責任で使用してください。著作権法に違反していないことに完全に自信がある場合にのみ、このフラグの使用を強く推奨します。既定は false です。コード例については、[documentation][] を参照してください。

使用例:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

