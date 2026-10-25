---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ドキュメントを JPG 形式でレンダリングするオプションを提供します。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

ドキュメントを JPG 形式でレンダリングするオプションを提供します。


JpgViewOptions クラスは、ドキュメントのレンダリングを制御するために使用できる追加の設定やパラメータをカプセル化します。
GroupDocs.Viewer コンポーネントで JPG 形式に変換します。


使用例:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | 新しいインスタンスを初期化します |
JpgViewOptions
クラス。
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | 新しいインスタンスを初期化します |
JpgViewOptions
クラス。
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | 新しいインスタンスを初期化します |
JpgViewOptions
クラス。
|
|  | [JpgViewOptions()](#JpgViewOptions--) | 新しいインスタンスを初期化します |
JpgViewOptions
出力ファイルのファイルパス形式として "p_{0}.jpg" を使用します。
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | 新しいインスタンスを初期化します |
JpgViewOptions
クラス。
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | 新しいインスタンスを初期化します |
JpgViewOptions
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | 出力画像の最大幅（ピクセル単位）を取得します。 |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 出力画像の最大幅（ピクセル）を設定します。 |
|
|  | [getMaxHeight()](#getMaxHeight--) | 出力画像の最大高さ（ピクセル）を取得します。 |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 出力画像の最大高さ（ピクセル）を設定します。 |
|
|  | [getQuality()](#getQuality--) | 出力画像の品質を取得します。 |
|
|  | [setQuality(byte value)](#setQuality-byte-) | 出力画像の品質を設定します。 |
|
|  | [isExtractText()](#isExtractText--) | テキスト抽出を有効にします。 |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | テキスト抽出を有効または無効にします。 |
|
|  | [getWidth()](#getWidth--) | 出力画像の幅（ピクセル）を取得します。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 出力画像の幅（ピクセル）を設定します。 |
|
|  | [getHeight()](#getHeight--) | 出力画像の高さ（ピクセル単位）を取得します。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 出力画像の高さ（ピクセル）を設定します。 |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | 出力ページストリームの作成と解放のメソッドを実装するファクトリを取得します。 |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words または Email ドキュメントの保存進行状況を推定するコールバックを取得します。 |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words または Email ドキュメントの保存進行状況を推定するコールバックを設定します。 |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


新しいインスタンスを初期化します
JpgViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


新しいインスタンスを初期化します
JpgViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream パラメータに渡されたデリゲートに割り当てられたメソッドによって作成されたストリームを解放するメソッドです。 |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


新しいインスタンスを初期化します
JpgViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 出力ページストリームの作成と解放のためのメソッドを実装するファクトリです。 |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


新しいインスタンスを初期化します
JpgViewOptions
出力ファイルのファイルパス形式として "p_{0}.jpg" を使用します。
出力ファイルはアプリケーションの現在の作業ディレクトリに配置されます。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


新しいインスタンスを初期化します
JpgViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | ファイルパスの形式、例: 'page_{0}.jpg'。 |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


新しいインスタンスを初期化します
JpgViewOptions
クラス。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | ファイルパスの形式、例: 'page_{0}.jpg'。 |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


出力画像の最大幅（ピクセル単位）を取得します。


このプロパティを使用して、出力画像の最大幅（ピクセル）を設定します。コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)をご覧ください。
#setWidth(int).setWidth(int) プロパティを設定した場合、このプロパティは無視されます。


**Returns:**
int - 出力画像の最大幅。

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


出力画像の最大幅（ピクセル）を設定します。


このプロパティを使用して、出力画像の最大幅（ピクセル）を設定します。コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)をご覧ください。
#setWidth(int).setWidth(int) プロパティを設定した場合、このプロパティは無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxWidth | int | 出力画像の最大幅です。 |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


出力画像の最大高さ（ピクセル）を取得します。


このプロパティを使用して、出力画像の最大高さ（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)をご覧ください。
#setHeight(int).setHeight(int) プロパティを設定した場合、このプロパティは無視されます。


**Returns:**
int - 出力画像の最大高さ。

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


出力画像の最大高さ（ピクセル）を設定します。


このプロパティを使用して、出力画像の最大高さ（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/)をご覧ください。
#setHeight(int).setHeight(int) プロパティを設定した場合、このプロパティは無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxHeight | int | 出力画像の最大高さです。 |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


出力画像の品質を取得します。


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/) を参照してください。


**Returns:**
byte - 出力画像の品質。

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


出力画像の品質を設定します。


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | byte | 出力画像の品質。 |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


テキスト抽出を有効にします。


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/)をご覧ください。


**Returns:**
boolean - テキスト抽出が有効な場合は true、無効な場合は false。

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


テキスト抽出を有効または無効にします。


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true はテキスト抽出を有効にし、false は無効にします。 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


出力画像の幅（ピクセル）を取得します。


このプロパティを使用して、出力画像の幅（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)をご覧ください。
このプロパティを設定した場合、#setMaxWidth(int).setMaxWidth(int) プロパティは無視されます。


**Returns:**
int - 出力画像の幅。

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


出力画像の幅（ピクセル）を設定します。


このプロパティを使用して、出力画像の幅（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)をご覧ください。
このプロパティを設定した場合、#setMaxWidth(int).setMaxWidth(int) プロパティは無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | int | 出力画像の幅です。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


出力画像の高さ（ピクセル単位）を取得します。


このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)をご覧ください。
このプロパティを設定した場合、#setMaxHeight(int).setMaxHeight(int) プロパティは無視されます。


**Returns:**
int - 出力画像の高さです。

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


出力画像の高さ（ピクセル）を設定します。


このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/)をご覧ください。
このプロパティを設定した場合、#setMaxHeight(int).setMaxHeight(int) プロパティは無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | int | 出力画像の高さです。 |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


出力ページストリームの作成と解放のメソッドを実装するファクトリを取得します。


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words または Email ドキュメントの保存進行状況を推定するコールバックを取得します。


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - ドキュメント保存進行状況を推定するコールバック。

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words または Email ドキュメントの保存進行状況を推定するコールバックを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | ドキュメント保存進行状況を推定するコールバック。 |
|

