---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "このクラスを使用して、出力 PDF ファイルに適用する PDF 最適化オプションを指定します。"
type: docs
weight: 21
url: /ja/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

このクラスを使用して、出力 PDF ファイルに適用する PDF 最適化オプションを指定します。


これらの最適化オプションは、PDFへのエクスポートがサポートされているすべての入力ファイル形式でサポートされます。
詳細とコードサンプルについては、この [page](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) とその子ページをご覧ください。


使用例:

````

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
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | MaxResolution オプションのデフォルト値を 300、ImageQuality オプションのデフォルト値を 100 に設定します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Web ブラウザーでオンライン表示できるように、出力 PDF ファイルの最適化を有効にします。 |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Web ブラウザーでのオンライン閲覧のために出力 PDF を最適化するかどうかを設定します。 |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | 不要な場合、アノテーションは削除できます。 |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | PDF から不要なアノテーションを削除するかどうかを設定します。 |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | PDF ドキュメントに AcroForms が含まれている場合、フォームフィールドをフラット化してファイルサイズを削減しようとします。 |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | PDF からフォームフィールドを削除するかどうかを設定します。 |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF ファイルはテキスト、画像、添付ファイル、アノテーション、グラフなどのオブジェクトで構成されています。 |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | PDF をグレースケールに変換するかどうかを設定します。 |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | ページ上のテキスト表示に使用されるすべてのフォントは、文字グリフのセットを含んでいます。 |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | PDF 内のフォントをサブセット化するかどうかを設定します。 |
|
|  | [isCompressImages()](#isCompressImages--) | 元の PDF ファイルに画像が含まれている場合、画像を圧縮し品質を設定することを検討してください。 |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | PDF 内の画像を圧縮するかどうかを設定します。 |
|
|  | [getImageQuality()](#getImageQuality--) | 元の PDF ファイルに画像が含まれている場合、画像を圧縮し品質を設定することを検討してください。 |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | PDF 内の画像を圧縮する際の画像品質を設定します。 |
|
|  | [isResizeImages()](#isResizeImages--) | CompressImages オプションと組み合わせて、画像を低解像度にリサイズできます。 |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | PDF 内の画像をリサイズするかどうかを設定します。 |
|
|  | [getMaxResolution()](#getMaxResolution--) | CompressImages オプションと組み合わせて、画像を低解像度にリサイズできます。 |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | PDF 内の画像をリサイズする際の最大解像度を設定します。 |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Excel スプレッドシートの罫線とフォントを最適化して、出力ファイルサイズを小さくします。 |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | PDF 内のスプレッドシートを最適化するかどうかを設定します。 |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | true に設定すると、プライベート情報（ページピース情報）を削除します。 |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | PDF からプライベート情報を削除するかどうかを設定します。 |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | ドキュメントが埋め込みフォントを使用している場合、すべてのフォントデータがドキュメントに含まれていることを意味します。 |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | PDF の埋め込みフォントを埋め込み解除するかどうかを設定します。 |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | 文書には同一のリソースストリームが複数含まれることがあります（例: 画像）。 |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | PDF 内の重複ストリームをリンクするかどうかを設定します。 |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | このプロパティが true に設定されている場合、同一ページの最適化時にページコンテンツが再利用されます。 |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | PDF でページコンテンツの再利用を許可するかどうかを設定します。 |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | 文書に未使用のリソースストリームが含まれることがあります。 |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | PDF から未使用のストリームを削除するかどうかを設定します。 |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | PDF 文書には参照されていない PDF オブジェクトが含まれることがあります |
文書内の他のオブジェクトからの参照がありません。
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | PDF から未使用オブジェクトを削除するかどうかを設定します。 |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


MaxResolution オプションのデフォルト値を 300、ImageQuality オプションのデフォルト値を 100 に設定します。


詳細とコードサンプルについては、この [page](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) とその子ページをご覧ください。


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Web ブラウザーでオンライン表示できるように、出力 PDF ファイルの最適化を有効にします。


コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/)をご覧ください。


**Returns:**
boolean - 出力 PDF がオンライン閲覧向けに最適化されている場合は true、そうでない場合は false。

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Web ブラウザーでのオンライン閲覧のために出力 PDF を最適化するかどうかを設定します。


コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | linearize | boolean | true: 出力 PDF をオンライン閲覧向けに最適化、false: それ以外。 |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


不要なアノテーションは削除できます。必要だが追加編集が不要な場合はフラット化できます。これによりファイルサイズが削減されます。


***Note:** The default value is 
false
.*
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/)をご覧ください。


**Returns:**
boolean - アノテーションが削除された場合は true、そうでない場合は false。

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


PDF から不要なアノテーションを削除するかどうかを設定します。


***Note:** The default value is 
false
.*
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | removeAnnotations | boolean | true: 不要なアノテーションを削除、false: それ以外。 |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


PDF ドキュメントに AcroForms が含まれている場合、フォームフィールドをフラット化してファイルサイズを削減しようとします。


***Note:** The default value is 
false
.*
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/)をご覧ください。


**Returns:**
boolean - フィールドが削除された場合は true、そうでない場合は false。

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


PDF からフォームフィールドを削除するかどうかを設定します。


***Note:** The default value is 
false
.*
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | removeFormFields | boolean | true: フィールドを削除、false: それ以外。 |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF ファイルはテキスト、画像、添付ファイル、アノテーション、グラフなどのオブジェクトで構成されています。
PDF を RGB カラースペースからグレースケールに変換する必要がある場合があります。これにより、PDF ファイルの印刷が高速化されます。
また、ファイルをグレースケールに変換すると、文書のサイズも縮小しますが、品質が低下する可能性があります。
現在、この機能はAdobe Acrobatのプレフライト機能でサポートされています。


***Note:** The default value is 
false
.*
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/)をご覧ください。


**Returns:**
boolean - PDFがグレースケールに変換された場合は true、そうでない場合は false。

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


PDF をグレースケールに変換するかどうかを設定します。


***Note:** The default value is 
false
.*
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true は PDF をグレースケールに変換し、false はそれ以外です。 |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


ページ上のテキスト表示に使用されるすべてのフォントは、文字グリフのセットを含んでいます。
PDF 仕様は「フォントサブセット」をサポートしており、使用されたグリフのみを含むフォントです。
テキストを更新する必要がある場合（必要なグリフがフォントに存在しない可能性があるため）問題が発生することがありますが、変更予定のないドキュメントではサイズを削減できます。


***Note:** The default value is 
false
.*
ファイルが埋め込みフォントを使用している場合、すべてのフォントデータが含まれます。GroupDocs.Viewer は埋め込みフォントをサブセット化してファイルサイズを削減できます。コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/)をご覧ください。


**Returns:**
boolean - フォントがサブセット化された場合は true、そうでない場合は false。

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


PDF 内のフォントをサブセット化するかどうかを設定します。


***Note:** The default value is 
false
.*
ファイルが埋め込みフォントを使用している場合、すべてのフォントデータが含まれます。GroupDocs.Viewer は埋め込みフォントをサブセット化してファイルサイズを削減できます。コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | subsetFonts | boolean | true はフォントをサブセット化し、false はそれ以外です。 |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


元の PDF ファイルに画像が含まれている場合、画像を圧縮し品質を設定することを検討してください。
画像圧縮を有効にするには、このオプションを true に設定してください。ドキュメント内のすべての画像が再圧縮されます。
圧縮は ImageQuality プロパティで定義され、品質をパーセンテージで指定します。
100% は品質が変わらないことを意味します。画像品質を下げるには、ImageQuality プロパティを 100 未満に設定してください。


***Note:** The default value is 
false
.*
このオプションを使用して、他の圧縮オプション（#setImageQuality(int).setImageQuality(int) と .）を有効にします。コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)をご覧ください。


**Returns:**
boolean - 画像が圧縮された場合は true、そうでない場合は false。

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


PDF 内の画像を圧縮するかどうかを設定します。


***Note:** The default value is 
false
.*
このオプションを使用して、他の圧縮オプション（#setImageQuality(int).setImageQuality(int) と .）を有効にします。コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | compressImages | boolean | true は画像を圧縮し、false はそれ以外です。 |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


ソース PDF ファイルに画像が含まれている場合、画像を圧縮し品質を設定することを検討してください。画像圧縮を有効にするには、CompressImages オプションを true に設定します。ドキュメント内のすべての画像が再圧縮されます。圧縮は ImageQuality プロパティで定義され、品質をパーセンテージで指定します。100% は品質が変わらないことを意味します。画像品質を下げるには、CompressImages オプションを true にし、ImageQuality プロパティを 100 未満に設定してください。

<br />


***Note:** The default value is 
100
.*
画像品質を変更するには、まず #setCompressImages(boolean).setCompressImages(boolean) プロパティを true に設定してください。コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)をご覧ください。


**Returns:**
int - 画像品質（1 から 100 の値）。

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


PDF 内の画像を圧縮する際の画像品質を設定します。


***Note:** The default value is 
100
.*
画像品質を変更するには、まず #setCompressImages(boolean).setCompressImages(boolean) プロパティを true に設定してください。コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | imageQuality | int | 画像品質（1 から 100 の値）。 |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


CompressImages オプションと組み合わせて、画像を低解像度にリサイズできます。
この場合、CompressImage を true に、ResizeImages を true に、そして MaxResolution を適切な値に設定すべきです。


***Note:** The default value is 
false
.*
このオプションを有効にするには、プロパティを true に設定します。このオプションはプロパティの設定を可能にします。コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)をご覧ください。


**Returns:**
boolean -  true  画像がリサイズされた場合、  false  それ以外の場合。

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


PDF 内の画像をリサイズするかどうかを設定します。


***Note:** The default value is 
false
.*
このオプションを有効にするには、プロパティを true に設定します。このオプションはプロパティの設定を可能にします。コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | resizeImages | boolean | true  画像をリサイズする場合、  false  それ以外の場合。 |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


このオプションは CompressImages オプションと組み合わせて、低解像度で画像をリサイズするために使用できます。この場合、CompressImage を true に、ResizeImages を true に、そして MaxResolution を適切な値に設定する必要があります。


***Note:** The default value is 
300
.*
このオプションを有効にするには、#setCompressImages(boolean).setCompressImages(boolean) と #setMaxResolution(int).setMaxResolution(int) プロパティを true に設定します。
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)をご覧ください。


**Returns:**
int - 画像の最大解像度。

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


PDF 内の画像をリサイズする際の最大解像度を設定します。


***Note:** The default value is 
300
.*
このオプションを有効にするには、#setCompressImages(boolean).setCompressImages(boolean) と #setMaxResolution(int).setMaxResolution(int) プロパティを true に設定します。
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxResolution | int | 画像の最大解像度。 |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Excel スプレッドシートの罫線とフォントを最適化して、出力ファイルサイズを小さくします。


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/)をご覧ください。


**Returns:**
boolean -  true  スプレッドシートが最適化された場合、  false  それ以外の場合。

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


PDF 内のスプレッドシートを最適化するかどうかを設定します。


コード例については、こちらの[ドキュメント](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  スプレッドシートを最適化する場合、  false  それ以外の場合。 |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


true に設定すると、プライベート情報（ページピース情報）を削除します。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  個人情報が削除された場合、  false  それ以外の場合。

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


PDF からプライベート情報を削除するかどうかを設定します。


***Note:** The default value is 
false
.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  個人情報を削除する場合、  false  それ以外の場合。 |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


ドキュメントが埋め込みフォントを使用している場合、すべてのフォントデータがドキュメントに含まれていることを意味します。
この利点は、ユーザーのマシンにフォントがインストールされているかどうかに関係なく、ドキュメントを閲覧できることです。ただし、フォントを埋め込むとドキュメントのサイズが大きくなります。
フォントの埋め込み解除メソッドは、すべての埋め込まれたフォントを削除します。これによりドキュメントのサイズは減少しますが、正しいフォントがインストールされていない場合、ドキュメントが読めなくなる可能性があります。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  埋め込まれたフォントが解除された場合、  false  それ以外の場合。

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


PDF の埋め込みフォントを埋め込み解除するかどうかを設定します。


***Note:** The default value is 
false
.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | unembedFonts | boolean | true  埋め込まれたフォントを解除する場合、  false  それ以外の場合。 |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


文書には同一のリソースストリームが複数含まれることがあります（例: 画像）。
たとえば、ドキュメントが自分自身と連結される場合にこのようなことが起こる可能性があります。
出力ドキュメントには、同じリソースストリームの独立したコピーが2つ含まれています。
すべてのリソースストリームを解析し比較します。ストリームが重複している場合はマージされ、1つのコピーだけが残り、参照が適切に変更され、オブジェクトのコピーは削除されます。
場合によっては、これによりドキュメントのサイズが縮小します。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  重複したストリームがリンクされている場合、  false  それ以外の場合。

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


PDF 内の重複ストリームをリンクするかどうかを設定します。


***Note:** The default value is 
false
.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  重複したストリームをリンクする場合、  false  それ以外の場合。 |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


このプロパティが true に設定されている場合、同一ページの最適化時にページコンテンツが再利用されます。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  ページコンテンツが再利用される場合、  false  それ以外の場合。

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


PDF でページコンテンツの再利用を許可するかどうかを設定します。


***Note:** The default value is 
false
.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  ページコンテンツの再利用を許可する場合、  false  それ以外の場合。 |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


文書に未使用のリソースストリームが含まれることがあります。
これらのストリームは、page\\\\u2019sリソース辞書から参照されているため、\\\\u201c未使用オブジェクト\\\\u201dではありません。
画像がページから削除されたが、ページのリソースからは削除されていない場合に発生することがあります。
また、ドキュメントからページが抽出され、ドキュメントページが\\\\u201c共通\\\\u201dリソースを持つ場合にこの状況は頻繁に発生します、
つまり、同じ Resources オブジェクトです。リソースストリームかどうかを判断するために、ページ内容が解析されます
使用されているかどうかを判定します。未使用のストリームは削除されます。場合によっては、これによりドキュメントのサイズが縮小します。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  未使用ストリームが削除される場合、  false  それ以外の場合。

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


PDF から未使用のストリームを削除するかどうかを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  未使用ストリームを削除する場合、  false  それ以外の場合。 |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


PDF 文書には参照されていない PDF オブジェクトが含まれることがあります
ドキュメント内の他のオブジェクトから。例えば、次のような場合に発生することがあります、
ページがドキュメントのページツリーから削除されても、ページオブジェクト自体が isn\\\\u2019t 削除されない場合。
これらのオブジェクトを削除してもドキュメントが無効になるわけではなく、むしろ\\\\u201c縮小\\\\u201dします。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  未使用オブジェクトが削除される場合、  false  それ以外の場合。

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


PDF から未使用オブジェクトを削除するかどうかを設定します。


***Note:** The default value is 
false
.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  未使用オブジェクトを削除する場合、  false  それ以外の場合。 |
|

