---
title: "Viewer"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ドキュメントのレンダリングプロセスを制御するメインクラスを表します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

ドキュメントのレンダリングプロセスを制御するメインクラスを表します。


Viewer クラスは、GroupDocs.Viewer コンポーネントを使用して文書をレンダリングするためのエントリーポイントです。
さまざまなソースから文書をロードし、レンダリングプロセスをカスタマイズし、異なる形式でレンダリングされた出力を取得するためのメソッドとオプションを提供します。


使用例:

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer クラスの新しいインスタンスを初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | ビューおよび文書固有の情報を返します。 |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | ビューおよび文書固有の情報を返します。 |
|
|  | [getAttachments()](#getAttachments--) | 文書に含まれる添付ファイルを返します。 |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | 文書に含まれる添付ファイルを返します。 |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | 添付ファイルを宛先ストリームに保存します。 |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | 添付ファイルを宛先ストリームに保存します。 |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | すべての文書ページのビューを作成します。 |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | すべての文書ページのビューを作成します。 |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | 特定の文書ページのビューを作成します。 |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | 特定の文書ページ群のビューを作成します。 |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | 特定の文書ページ群のビューを作成します。 |
|
|  | [getAllFonts()](#getAllFonts--) | ロードされた文書で使用されているすべてのフォントを返します。文書自体に埋め込まれたフォントと、OS にインストールされ文書で使用されているシステムフォントを含みます。 |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | 提供されたオプションに従って、読み込まれたドキュメント内でテキスト検索を実行し、（見つかった場合）一致箇所をハイライトします。 |
|
|  | [getFileInfo()](#getFileInfo--) | ファイルタイプやファイルが暗号化されているかを示すフラグなど、ファイルに関する情報を返します。 |
|
|  | [close()](#close--) | ファイルストリームと管理された内部リソースを解放します。 |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Viewer クラスの新しいインスタンスを初期化します。


GroupDocs.Viewer がサポートするファイルタイプの詳細:
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 読み取り可能なストリームを返すメソッドです。 |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | ファイルストリームです。 |
|
|  | leaveOpen | boolean | Viewer オブジェクトが破棄された後もストリームを開いたままにする場合は true、そうでない場合は false。 |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | 読み取り可能なストリームです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | ファイルストリームです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|
|  | leaveOpen | boolean | Viewer オブジェクトが破棄された後もストリームを開いたままにする場合は true、そうでない場合は false。 |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | ファイルストリームです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | ファイルストリームです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|
|  | leaveOpen | boolean | Viewer オブジェクトが破棄された後もストリームを開いたままにする場合は true、そうでない場合は false。 |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | ファイルストリームです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | ファイルストリームです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|
|  | leaveOpen | boolean | Viewer オブジェクトが破棄された後もストリームを開いたままにする場合は true、そうでない場合は false。 |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Viewer クラスの新しいインスタンスを初期化します。


GroupDocs.Viewer がサポートするファイルタイプの詳細: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | url | java.net.URL | Viewer に読み込むべきファイルの URL です。 |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | url | java.net.URL | Viewer に読み込むべきファイルの URL です。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | url | java.net.URL | Viewer に読み込むべきファイルの URL です。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | url | java.net.URL | Viewer に読み込むべきファイルの URL です。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。


このコンストラクタを使用すると、指定された [ViewerSettings](../../com.groupdocs.viewer/viewersettings) を使用して、[FileReader](../../com.groupdocs.viewer.interfaces/filereader) からドキュメントを表示する Viewer オブジェクトを作成できます。
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Viewer に読み込むドキュメントを含む [FileReader](../../com.groupdocs.viewer.interfaces/filereader)。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer に適用される [ViewerSettings](../../com.groupdocs.viewer/viewersettings)。 |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。


GroupDocs.Viewer を使用してドキュメントをロードおよび表示する機能を提供します。


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | ファイルリーダーです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ロードオプションです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | レンダリングするファイルへのパスです。 |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | レンダリングするファイルへのパスです。 |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | レンダリングするファイルへのパスです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | レンダリングするファイルへのパスです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | レンダリングするファイルへのパスです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | レンダリングするファイルへのパスです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | レンダリングするファイルへのパスです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer クラスの新しいインスタンスを初期化します。
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | レンダリングするファイルへのパスです。 |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | ドキュメントのロードオプションです。 |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer の設定です。 |
|

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


ビューおよび文書固有の情報を返します。
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | ビュー情報オプションです。 |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


ビューおよび文書固有の情報を返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | ビュー情報オプションです。 |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | 操作をキャンセルするためのキャンセルトークンです。 |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


文書に含まれる添付ファイルを返します。
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - ドキュメントに含まれる添付ファイルです。

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


文書に含まれる添付ファイルを返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | 操作をキャンセルするためのキャンセルトークンです。 |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - ドキュメントに含まれる添付ファイルです。

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


添付ファイルを宛先ストリームに保存します。
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | 添付ファイルです。 |
|
|  | 宛先 | java.io.OutputStream | 書き込み可能なストリームです。 |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


添付ファイルを宛先ストリームに保存します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | 添付ファイルです。 |
|
|  | 宛先 | java.io.OutputStream | 書き込み可能なストリームです。 |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | 操作をキャンセルするためのキャンセルトークンです。 |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


すべての文書ページのビューを作成します。
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 表示オプションです。 |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


すべての文書ページのビューを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 表示オプションです。 |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | レンダリングプロセスをキャンセルするためのキャンセルトークンです。 |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


特定の文書ページのビューを作成します。
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 表示オプションです。 |
|
|  | pageNumber | int | 表示するページ番号です。 |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


特定の文書ページ群のビューを作成します。
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 表示オプションです。 |
|
|  | pageNumbers | int[] | 表示するページ番号の一覧です。 |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


特定の文書ページ群のビューを作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 表示オプションです。 |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | レンダリングプロセスをキャンセルするためのキャンセルトークンです。 |
|
|  | pageNumbers | int[] | 表示するページ番号の一覧です。 |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


ロードされた文書で使用されているすべてのフォントを返します。文書自体に埋め込まれたフォントと、OS にインストールされ文書で使用されているシステムフォントを含みます。

詳細については、以下をご覧ください
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - この [Viewer](../../com.groupdocs.viewer/viewer) インスタンスにロードされたドキュメントで使用されるすべてのフォントの非 null リストです。

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


提供されたオプションに従って、読み込まれたドキュメント内でテキスト検索を実行し、（見つかった場合）一致箇所をハイライトします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | オプション | com.groupdocs.viewer.options.SearchHighlightOptions | 検索およびハイライトオプションで、検索するテキストフレーズを含みます。null にできません。 |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


ファイルタイプやファイルが暗号化されているかを示すフラグなど、ファイルに関する情報を返します。
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


ファイルストリームと管理された内部リソースを解放します。


