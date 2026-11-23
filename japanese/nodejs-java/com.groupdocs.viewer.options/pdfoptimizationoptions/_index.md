---
title: "PdfOptimizationOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "このクラスを使用して、出力 PDF ファイルに適用する PDF 最適化オプションを指定します。"
type: docs
weight: 21
url: /ja/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

このクラスを使用して、出力 PDF ファイルに適用する PDF 最適化オプションを指定します。

これらの最適化オプションは、PDF へのエクスポートがサポートされているすべての入力ファイル形式で使用できます。詳細やコードサンプルについては、この [page][] とその子ページを参照してください。

使用例:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | MaxResolution オプションのデフォルト値を 300、ImageQuality オプションのデフォルト値を 100 に設定します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isLinearize()](#isLinearize--) | Web ブラウザーでオンライン閲覧できるように、出力 PDF ファイルの最適化を有効にします。 |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Web ブラウザーでのオンライン閲覧用に出力 PDF を最適化するかどうかを設定します。 |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | 不要な場合、注釈を削除できます。 |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | PDF から不要な注釈を削除するかどうかを設定します。 |
| [isRemoveFormFields()](#isRemoveFormFields--) | PDF 文書に AcroForms が含まれている場合、フォームフィールドをフラット化してファイルサイズを削減できる可能性があります。 |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | PDF からフォームフィールドを削除するかどうかを設定します。 |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF ファイルはテキスト、画像、添付ファイル、注釈、グラフなどのオブジェクトで構成されています。 |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | PDF をグレースケールに変換するかどうかを設定します。 |
| [isSubsetFonts()](#isSubsetFonts--) | ページ上のテキスト表示に使用されるすべてのフォントは、文字グリフのセットを含んでいます。 |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | PDF 内のフォントをサブセット化するかどうかを設定します。 |
| [isCompressImages()](#isCompressImages--) | 元の PDF ファイルに画像が含まれている場合、画像を圧縮し品質を設定することを検討してください。 |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | PDF 内の画像を圧縮するかどうかを設定します。 |
| [getImageQuality()](#getImageQuality--) | 元の PDF ファイルに画像が含まれている場合、画像を圧縮し品質を設定することを検討してください。 |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | PDF 内の画像を圧縮する際の画像品質を設定します。 |
| [isResizeImages()](#isResizeImages--) | CompressImages オプションと組み合わせて、画像を低解像度にリサイズすることができます。 |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | PDF 内の画像をリサイズするかどうかを設定します。 |
| [getMaxResolution()](#getMaxResolution--) | CompressImages オプションと組み合わせて、画像を低解像度にリサイズすることができます。 |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | PDF 内の画像をリサイズする際の最大解像度を設定します。 |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Excel スプレッドシートの罫線とフォントを最適化して、出力ファイルサイズを小さくします。 |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | PDF 内のスプレッドシートを最適化するかどうかを設定します。 |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | true に設定すると、プライベート情報（ページピース情報）を削除します。 |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | PDF からプライベート情報を削除するかどうかを設定します。 |
| [isUnembedFonts()](#isUnembedFonts--) | 文書が埋め込みフォントを使用している場合、すべてのフォントデータが文書内に配置されていることを意味します。 |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | PDF 内の埋め込みフォントを埋め込み解除するかどうかを設定します。 |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | 文書には同一のリソースストリームが複数含まれることがあります（例：画像）。 |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | PDF 内の重複ストリームをリンクするかどうかを設定します。 |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | このプロパティが true に設定されている場合、同一ページの最適化時にページコンテンツが再利用されます。 |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | PDFでページコンテンツの再利用を許可するかどうかを設定します。 |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | 文書に未使用のリソースストリームが含まれることがあります。 |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | PDFから未使用のストリームを削除するかどうかを設定します。 |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | PDF文書には、文書内の他のオブジェクトから参照されていない PDF オブジェクトが含まれることがあります。 |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | PDFから未使用のオブジェクトを削除するかどうかを設定します。 |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


MaxResolution オプションのデフォルト値を 300、ImageQuality オプションのデフォルト値を 100 に設定します。

詳細とコードサンプルについては、この [page][] とその子ページをご覧ください。


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Web ブラウザーでオンライン閲覧できるように、出力 PDF ファイルの最適化を有効にします。

コード例については、この [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  出力 PDF がオンライン閲覧向けに最適化されている場合、  false  それ以外の場合。
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Web ブラウザーでのオンライン閲覧用に出力 PDF を最適化するかどうかを設定します。

コード例については、この [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| linearize | boolean | true  出力 PDF をオンライン閲覧向けに最適化する場合、  false  それ以外の場合。 |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


不要な場合はアノテーションを削除できます。必要だが追加編集が不要な場合はフラット化できます。これによりファイルサイズが削減されます。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  アノテーションが削除された場合、  false  それ以外の場合。
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


PDF から不要な注釈を削除するかどうかを設定します。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| removeAnnotations | boolean | true  不要なアノテーションを削除する場合、  false  それ以外の場合。 |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


PDF 文書に AcroForms が含まれている場合、フォームフィールドをフラット化してファイルサイズを削減できる可能性があります。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  フォームフィールドが削除された場合、  false  それ以外の場合。
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


PDF からフォームフィールドを削除するかどうかを設定します。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| removeFormFields | boolean | true  フォームフィールドを削除する場合、  false  それ以外の場合。 |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF ファイルはテキスト、画像、添付ファイル、アノテーション、グラフなどのオブジェクトで構成されています。PDF を RGB カラースペースからグレースケールに変換する必要がある場合があります。これにより印刷時の速度が向上します。また、グレースケールに変換すると文書のサイズも縮小しますが、品質が低下する可能性があります。現在、この機能は Adobe Acrobat のプリフライト機能でサポートされています。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  PDF がグレースケールに変換された場合、  false  それ以外の場合。
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


PDF をグレースケールに変換するかどうかを設定します。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertToGrayScale | boolean | true  PDF をグレースケールに変換する場合、  false  それ以外の場合。 |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


ページ上のテキスト表示に使用されるすべてのフォントは、文字グリフの集合を含んでいます。PDF 仕様は "font subset"（使用されているグリフのみを含むフォント） をサポートしています。これにより、テキストを更新する必要がある場合（必要なグリフがフォントに存在しない可能性がある）に問題が生じることがありますが、変更予定のない文書ではサイズ削減が可能になります。

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  フォントがサブセット化された場合、  false  それ以外の場合。
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


PDF 内のフォントをサブセット化するかどうかを設定します。

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| subsetFonts | boolean | true  フォントをサブセット化する場合、  false  それ以外の場合。 |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


ソースPDFファイルに画像が含まれている場合、画像を圧縮し品質を設定することを検討してください。画像圧縮を有効にするには、このオプションを true に設定します。ドキュメント内のすべての画像が再圧縮されます。圧縮は ImageQuality プロパティで定義され、品質のパーセンテージ値です。100% は品質が変わりません。画像品質を下げるには、ImageQuality プロパティを 100 未満に設定します。

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  画像が圧縮されている場合、  false  それ以外の場合。
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


PDF 内の画像を圧縮するかどうかを設定します。

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| compressImages | boolean | true  画像を圧縮する場合、  false  それ以外の場合。 |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


ソースPDFファイルに画像が含まれている場合、画像を圧縮し品質を設定することを検討してください。画像圧縮を有効にするには、CompressImages オプションを true に設定します。ドキュメント内のすべての画像が再圧縮されます。圧縮は ImageQuality プロパティで定義され、品質のパーセンテージ値です。100% は品質が変わりません。画像品質を下げるには、CompressImages オプションを true にし、ImageQuality プロパティを 100 未満に設定します。

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - 画像品質 (1 から 100 の値)。
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


PDF 内の画像を圧縮する際の画像品質を設定します。

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageQuality | int | 画像品質 (1 から 100 の値)。 |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


CompressImages オプションと組み合わせて使用でき、画像を低解像度にリサイズできます。この場合、CompressImage を true に、ResizeImages を true に、そして MaxResolution を適切な値に設定する必要があります。

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  画像がリサイズされている場合、  false  それ以外の場合。
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


PDF 内の画像をリサイズするかどうかを設定します。

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resizeImages | boolean | true  画像をリサイズする場合、  false  それ以外の場合。 |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


CompressImages オプションと組み合わせて使用でき、画像を低解像度にリサイズできます。この場合、CompressImage を true に、ResizeImages を true に、そして MaxResolution を適切な値に設定する必要があります。

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - 画像の最大解像度。
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


PDF 内の画像をリサイズする際の最大解像度を設定します。

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxResolution | int | 画像の最大解像度。 |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Excel スプレッドシートの罫線とフォントを最適化して、出力ファイルサイズを小さくします。

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  スプレッドシートが最適化されている場合、  false  それ以外の場合。
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


PDF 内のスプレッドシートを最適化するかどうかを設定します。

コード例については、この [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  スプレッドシートを最適化する場合、  false  それ以外の場合。 |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


true に設定すると、プライベート情報（ページピース情報）を削除します。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  個人情報が削除されている場合、  false  それ以外の場合。
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


PDF からプライベート情報を削除するかどうかを設定します。

***Note:** The default value is  false .*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| removePrivateInfo | boolean | true  個人情報を削除する場合、  false  それ以外の場合。 |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


ドキュメントで埋め込みフォントが使用されている場合、すべてのフォントデータがドキュメント内に配置されます。利点は、フォントがユーザー\\u2019s のマシンにインストールされていなくてもドキュメントが表示可能になることです。しかし、フォントを埋め込むとドキュメントが大きくなります。unembed fonts メソッドはすべての埋め込みフォントを削除します。これによりドキュメントサイズは減少しますが、正しいフォントがインストールされていない場合、ドキュメントが読めなくなる可能性があります。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  埋め込みフォントが解除された場合、  false  それ以外の場合。
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


PDF 内の埋め込みフォントを埋め込み解除するかどうかを設定します。

***Note:** The default value is  false .*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| unembedFonts | boolean | true  埋め込みフォントを解除する場合、  false  それ以外の場合。 |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


時々、ドキュメントにいくつかの同一のリソースストリーム（例：画像）が含まれることがあります。これは、ドキュメントが自分自身と連結された場合などに起こります。出力ドキュメントには同じリソースストリームの独立したコピーが二つ含まれます。すべてのリソースストリームを解析し比較します。ストリームが重複している場合はマージされ、1つのコピーだけが残り、参照が適切に変更され、オブジェクトのコピーは削除されます。時々、これによりドキュメントサイズが減少します。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  重複したストリームがリンクされている場合、  false  それ以外の場合。
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


PDF 内の重複ストリームをリンクするかどうかを設定します。

***Note:** The default value is  false .*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  重複したストリームをリンクする場合、  false  それ以外の場合。 |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


このプロパティが true に設定されている場合、同一ページの最適化時にページコンテンツが再利用されます。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  ページコンテンツが再利用される場合、  false  それ以外の場合。
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


PDFでページコンテンツの再利用を許可するかどうかを設定します。

***Note:** The default value is  false .*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| allowReusePageContent | boolean | true  ページコンテンツの再利用を許可する場合、  false  それ以外の場合。 |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


時々、ドキュメントに未使用のリソースストリームが含まれます。これらのストリームは、ページのリソース辞書から参照されているため、\u201c未使用オブジェクト\u201dではありません。画像がページから削除されたがページリソースからは削除されていない場合などに起こります。また、ドキュメントからページが抽出され、ドキュメントページが\u201c共通\u201dリソース、すなわち同じResourcesオブジェクトを持つ場合にも頻繁に発生します。ページコンテンツを解析し、リソースストリームが使用されているかどうかを判断します。未使用のストリームは削除されます。時々、これによりドキュメントサイズが減少します。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  未使用のストリームが削除される場合、  false  それ以外の場合。
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


PDFから未使用のストリームを削除するかどうかを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  未使用のストリームを削除する場合、  false  それ以外の場合。 |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


PDFドキュメントには、ドキュメント内の他のオブジェクトから参照されていないPDFオブジェクトが含まれることがあります。例えば、ページがドキュメントのページツリーから削除されたが、ページオブジェクト自体が\u2019削除されていない場合などに起こります。これらのオブジェクトを削除してもドキュメントが無効になるわけではなく、むしろサイズが縮小します。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  未使用のオブジェクトが削除される場合、  false  それ以外の場合。
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


PDFから未使用のオブジェクトを削除するかどうかを設定します。

***Note:** The default value is  false .*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  未使用のオブジェクトを削除する場合、  false  それ以外の場合。 |

