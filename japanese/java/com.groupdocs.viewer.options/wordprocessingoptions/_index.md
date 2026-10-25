---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ワードプロセッシングドキュメントのレンダリングオプションを提供します。"
type: docs
weight: 38
url: /ja/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

ワードプロセッシングドキュメントのレンダリングオプションを提供します。


WordProcessingOptions クラスは、ワードプロセッシング ドキュメントのレンダリング用オプションを提供します
GroupDocs.Viewer コンポーネント内です。使用できる設定とパラメーターをカプセル化します
レンダリングプロセスとワードプロセッシング ファイルの出力形式を制御します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/) を参照してください。


使用例:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | 新しいインスタンスを初期化します |
WordProcessingOptions
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | HTM および HTML ファイルのレンダリング用ページサイズを取得します。 |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | HTM および HTML ファイルのレンダリング用ページサイズを設定します。 |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | トラッキングされた変更（リビジョン）のレンダリングが有効かどうかを示します。 |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | トラッキングされた変更（リビジョン）のレンダリングが有効かどうかを設定します。 |
|
|  | [getLeftMargin()](#getLeftMargin--) | HTML レンダリングの左ページ余白を取得します。 |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | HTML レンダリングの左ページ余白を設定します。 |
|
|  | [getRightMargin()](#getRightMargin--) | HTML レンダリングの右ページ余白を取得します。 |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | HTML レンダリングの右ページ余白を設定します。 |
|
|  | [getTopMargin()](#getTopMargin--) | HTML レンダリングの上ページ余白を取得します。 |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | HTML レンダリングの上ページ余白を設定します。 |
|
|  | [getBottomMargin()](#getBottomMargin--) | 下ページ余白（HTML レンダリング専用） |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | HTML レンダリングの下ページ余白を設定します。 |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | このオプションは、アラビア語、ヘブライ語、インド系文字、ラテン系またはキリル系スクリプトをレンダリングする際に、カーニングやその他の OpenType 機能を有効にします。 |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | このオプションは、アラビア語、ヘブライ語、インド系文字、ラテン系またはキリル系スクリプトをレンダリングする際に、カーニングやその他の OpenType 機能を有効にします。 |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | HTML または PDF にレンダリングする際に、目次ナビゲーションを無効にするかどうかを示します。 |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | HTML または PDF にレンダリングする際に、目次ナビゲーションを無効にするかどうかを設定します。 |
|
|  | [isUpdateFields()](#isUpdateFields--) | 入力の WordProcessing ドキュメントを HTML、PDF、PNG、または JPEG の出力形式で保存する前に、特定のタイプのフィールドを更新すべきかどうかを決定する値を取得します。 |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | 入力の WordProcessing ドキュメントを HTML、PDF、PNG、または JPEG の出力形式で保存する前に、特定のタイプのフィールドを更新すべきかどうかを決定する値を設定します。 |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 生成された画像の水平解像度（dpi）を取得します。 |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | 生成された画像の水平解像度（dpi）を設定します。 |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 生成された画像の垂直解像度（dpi）を取得します。 |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | 生成された画像の垂直解像度（dpi）を設定します。 |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | ロードされた WordProcessing ドキュメントにページ番号付けを強制的に適用できるようにします。 |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | ロードされた WordProcessing ドキュメントにページ番号付けを強制的に適用できるようにします。 |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | オプションが変更されたかどうかを確認します。 |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


新しいインスタンスを初期化します
WordProcessingOptions
クラス。
ワードプロセッシング ドキュメントのレンダリングオプションを含みます。詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) を参照してください。


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


HTM および HTML ファイルのレンダリング用ページサイズを取得します。


デフォルトのページサイズを使用すると、一部のコンテンツがページ枠に収まらない場合があります。
コンテンツを収めるために、[PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) のように、より大きなページサイズ（例: A3）を設定できます。


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


HTM および HTML ファイルのレンダリング用ページサイズを設定します。


デフォルトのページサイズを使用すると、一部のコンテンツがページ枠に収まらない場合があります。
コンテンツを収めるために、[PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) のように、より大きなページサイズ（例: A3）を設定できます。


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 出力ページのサイズです。 |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


トラッキングされた変更（リビジョン）のレンダリングが有効かどうかを示します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) を参照してください。


**Returns:**
boolean -  true  トラッキング変更のレンダリングが有効な場合、  false  それ以外の場合。

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


トラッキングされた変更（リビジョン）のレンダリングが有効かどうかを設定します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true  トラッキング変更のレンダリングを有効にし、  false  無効にします。 |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


HTML レンダリングの左ページ余白を取得します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) を参照してください。


**Returns:**
java.lang.Double - 左ページ余白の値です。

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


HTML レンダリングの左ページ余白を設定します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | 設定する左ページ余白の値です。 |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


HTML レンダリングの右ページ余白を取得します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) を参照してください。


**Returns:**
java.lang.Double - 右ページ余白の値です。

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


HTML レンダリングの右ページ余白を設定します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | 設定する右ページ余白の値です。 |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


HTML レンダリングの上ページ余白を取得します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) を参照してください。


**Returns:**
java.lang.Double - 上部ページ余白です。

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


HTML レンダリングの上ページ余白を設定します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | topMargin | java.lang.Double | 設定する上部ページ余白です。 |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


下ページ余白（HTML レンダリング専用）
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) を参照してください。


**Returns:**
java.lang.Double - 下部ページ余白です。

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


HTML レンダリングの下ページ余白を設定します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | 設定する下部ページ余白です。 |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


このオプションは、アラビア語、ヘブライ語、インド系文字、ラテン系またはキリル系スクリプトをレンダリングする際に、カーニングやその他の OpenType 機能を有効にします。


**Returns:**
boolean - True OpenType 機能が有効な場合、 false それ以外の場合。

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


このオプションは、アラビア語、ヘブライ語、インド系文字、ラテン系またはキリル系スクリプトをレンダリングする際に、カーニングやその他の OpenType 機能を有効にします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | OpenType 機能を有効にする場合は True、そうでない場合は false。 |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


HTML または PDF にレンダリングする際に、目次ナビゲーションを無効にするかどうかを示します。このオプションが true に設定されている場合、HTML レンダリングでは目次の相対リンクが span タグに置き換えられ、機能は失われますが視覚的な外観は保持されます。PDF レンダリングの場合、目次はリンクなしのプレーンテキストとしてレンダリングされます。


**Returns:**
boolean - 目次ナビゲーションが無効な場合は True、そうでない場合は false。

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


HTML または PDF にレンダリングする際に、目次ナビゲーションを無効にするかどうかを設定します。このオプションが true に設定されている場合、HTML レンダリングでは目次の相対リンクが span タグに置き換えられ、機能は失われますが視覚的な外観は保持されます。PDF レンダリングの場合、目次はリンクなしのプレーンテキストとしてレンダリングされます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | 目次ナビゲーションを無効にするかどうかを示します。 |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


入力の WordProcessing ドキュメントを HTML、PDF、PNG、または JPEG 出力形式で保存する前に、特定のタイプのフィールドを更新するかどうかを決定する値を取得します。このプロパティのデフォルト値は true \u2014 保存前にフィールドが更新されます。


詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving) を参照してください。


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


入力の WordProcessing ドキュメントを HTML、PDF、PNG、または JPEG 出力形式で保存する前に、特定のタイプのフィールドを更新するかどうかを決定する値を設定します。このプロパティのデフォルト値は true \u2014 保存前にフィールドが更新されます。


詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


生成された画像の水平解像度（dpi）を取得します。このオプションは WordProcessing ドキュメントを PNG または JPEG 形式にレンダリングする場合にのみ使用されます。


既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。
ユーザーが指定した値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。


**Returns:**
int - 水平解像度（DPI）です。

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


生成された画像の水平解像度（dpi）を設定します。このオプションは WordProcessing ドキュメントを PNG または JPEG 形式にレンダリングする場合にのみ使用されます。


既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。
ユーザーが指定した値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | horizontalResolution | int | 水平解像度（DPI）です。 |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


生成された画像の垂直解像度（dpi）を取得します。このオプションは WordProcessing ドキュメントを PNG または JPEG 形式にレンダリングする場合にのみ使用されます。


既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。
ユーザーが指定した値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。


**Returns:**
int - 垂直解像度（DPI）です。

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


生成された画像の垂直解像度（dpi）を設定します。このオプションは WordProcessing ドキュメントを PNG または JPEG 形式にレンダリングする場合にのみ使用されます。


既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。
ユーザーが指定した値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | verticalResolution | int | 垂直解像度（DPI）です。 |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


読み込まれた WordProcessing ドキュメントにページ番号付けを強制的に適用できるようにします。デフォルトは [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \u2014 ドキュメントはそのままです。


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


読み込まれた WordProcessing ドキュメントにページ番号付けを強制的に適用できるようにします。デフォルトは [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \u2014 ドキュメントはそのままです。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | ページ番号の位置。 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


オプションが変更されたかどうかを確認します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | o | java.lang.Object | 等価性を比較するオブジェクト。 |
|

**Returns:**
boolean - オプションが指定されたオブジェクトと等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


このオブジェクトのハッシュコード値を計算します。ハッシュコードは
オブジェクトの内部状態に基づき、ハッシュベースのデータ構造で使用されます
ハッシュマップやハッシュセットなどです。
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - このオブジェクトのハッシュコード値。

