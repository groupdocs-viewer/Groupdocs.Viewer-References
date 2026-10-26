---
title: "WordProcessingOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ワードプロセッシングドキュメントのレンダリングオプションを提供します。"
type: docs
weight: 38
url: /ja/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

ワードプロセッシングドキュメントのレンダリングオプションを提供します。

WordProcessingOptions クラスは、GroupDocs.Viewer コンポーネントでワードプロセッシング ドキュメントをレンダリングするためのオプションを提供します。レンダリングプロセスやワードプロセッシング ファイルの出力形式を制御するために使用できる設定とパラメータをカプセル化しています。詳細については、[documentation][] を参照してください。

使用例:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | WordProcessingOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPageSize()](#getPageSize--) | HTM および HTML ファイルのレンダリング用ページサイズを取得します。 |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | HTM および HTML ファイルのレンダリング用ページサイズを設定します。 |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | トラッキングされた変更（リビジョン）のレンダリングが有効かどうかを示します。 |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | トラッキングされた変更（リビジョン）のレンダリングが有効かどうかを設定します。 |
| [getLeftMargin()](#getLeftMargin--) | HTML レンダリング用の左ページ余白を取得します。 |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | HTML レンダリング用の左ページ余白を設定します。 |
| [getRightMargin()](#getRightMargin--) | HTML レンダリング用の右ページ余白を取得します。 |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | HTML レンダリング用の右ページ余白を設定します。 |
| [getTopMargin()](#getTopMargin--) | HTML レンダリング用の上ページ余白を取得します。 |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | HTMLレンダリングのために上部ページ余白を設定します。 |
| [getBottomMargin()](#getBottomMargin--) | 下部ページ余白（HTMLレンダリング専用） |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | HTMLレンダリングのために下部ページ余白を設定します。 |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | このオプションは、アラビア語、ヘブライ語、インド系文字、ラテン系またはキリル系文字をレンダリングする際に、カーニングやその他のOpenType機能を有効にします。 |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | このオプションは、アラビア語、ヘブライ語、インド系文字、ラテン系またはキリル系文字をレンダリングする際に、カーニングやその他のOpenType機能を有効にします。 |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | HTMLまたはPDFへのレンダリング時に目次ナビゲーションを無効にすべきかどうかを示します。 |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | HTMLまたはPDFへのレンダリング時に目次ナビゲーションを無効にするかどうかを設定します。 |
| [isUpdateFields()](#isUpdateFields--) | 入力のWordProcessingドキュメントをHTML、PDF、PNG、またはJPEG出力形式で保存する前に、特定のタイプのフィールドを更新すべきかどうかを決定する値を取得します。 |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | 入力のWordProcessingドキュメントをHTML、PDF、PNG、またはJPEG出力形式で保存する前に、特定のタイプのフィールドを更新すべきかどうかを決定する値を設定します。 |
| [equals(Object o)](#equals-java.lang.Object-) | オプションが変更されたかどうかを確認します。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


WordProcessingOptions クラスの新しいインスタンスを初期化します。ワードプロセッシングドキュメントのレンダリング用オプションを含みます。詳細については、[documentation][]. を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


HTM および HTML ファイルのレンダリング用ページサイズを取得します。

デフォルトのページサイズを使用すると、一部のコンテンツがページ枠に収まらない場合があります。コンテンツを収めるために、[PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) のように、A3 などの大きなページサイズを設定できます。

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


HTM および HTML ファイルのレンダリング用ページサイズを設定します。

デフォルトのページサイズを使用すると、一部のコンテンツがページ枠に収まらない場合があります。コンテンツを収めるために、[PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) のように、A3 などの大きなページサイズを設定できます。

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 出力ページのサイズ。 |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


トラッキングされた変更（リビジョン）のレンダリングが有効かどうかを示します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean - 追跡変更のレンダリングが有効な場合は true、そうでない場合は false。
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


トラッキングされた変更（リビジョン）のレンダリングが有効かどうかを設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true は追跡変更のレンダリングを有効にし、false は無効にします。 |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


HTML レンダリング用の左ページ余白を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 左ページ余白の値。
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


HTML レンダリング用の左ページ余白を設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| leftMargin | java.lang.Double | 設定する左ページ余白の値。 |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


HTML レンダリング用の右ページ余白を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 右ページ余白の値。
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


HTML レンダリング用の右ページ余白を設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rightMargin | java.lang.Double | 設定する右ページ余白の値。 |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


HTML レンダリング用の上ページ余白を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 上部ページ余白。
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


HTMLレンダリングのために上部ページ余白を設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| topMargin | java.lang.Double | 設定する上部ページ余白。 |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


下部ページ余白（HTMLレンダリング専用）

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 下部ページ余白。
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


HTMLレンダリングのために下部ページ余白を設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bottomMargin | java.lang.Double | 設定する下部ページ余白。 |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


このオプションは、アラビア語、ヘブライ語、インド系文字、ラテン系またはキリル系文字をレンダリングする際に、カーニングやその他のOpenType機能を有効にします。

**Returns:**
boolean - OpenType 機能が有効な場合は True、そうでない場合は false。
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


このオプションは、アラビア語、ヘブライ語、インド系文字、ラテン系またはキリル系文字をレンダリングする際に、カーニングやその他のOpenType機能を有効にします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | OpenType 機能を有効にする場合は true、そうでない場合は false。 |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


HTML または PDF にレンダリングする際に目次ナビゲーションを無効にするかどうかを示します。このオプションが true に設定されている場合、HTML レンダリングでは目次からの相対リンクが span タグに置き換えられ、機能は失われますが視覚的な外観は保持されます。PDF レンダリングでは、目次はリンクなしのプレーンテキストとしてレンダリングされます。

**Returns:**
boolean - 目次ナビゲーションが無効化されている場合は true、そうでない場合は false。
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


HTML または PDF にレンダリングする際に目次ナビゲーションを無効にするかどうかを設定します。このオプションが true に設定されている場合、HTML レンダリングでは目次からの相対リンクが span タグに置き換えられ、機能は失われますが視覚的な外観は保持されます。PDF レンダリングでは、目次はリンクなしのプレーンテキストとしてレンダリングされます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| unlinkTableOfContents | boolean | 目次ナビゲーションを無効にするかどうかを示します。 |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


入力の WordProcessing ドキュメントを HTML、PDF、PNG、または JPEG 出力形式で保存する前に、特定のタイプのフィールドを更新すべきかどうかを決定する値を取得します。このプロパティのデフォルト値は true \\u2014 保存前にフィールドが更新されます。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


入力の WordProcessing ドキュメントを HTML、PDF、PNG、または JPEG 出力形式で保存する前に、特定のタイプのフィールドを更新すべきかどうかを決定する値を設定します。このプロパティのデフォルト値は true \\u2014 保存前にフィールドが更新されます。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


オプションが変更されたかどうかを確認します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| o | java.lang.Object | 等価性を比較するオブジェクト。 |

**Returns:**
boolean - オプションが指定されたオブジェクトと等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このオブジェクトのハッシュコード値を計算します。ハッシュコードはオブジェクトの内部状態に基づき、ハッシュマップやハッシュセットなどのハッシュベースのデータ構造で使用されます。

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - このオブジェクトのハッシュコード値。
