---
title: "LoadOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ファイルを開くために使用されるオプションを提供します。"
type: docs
weight: 18
url: /ja/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

ファイルを開くために使用されるオプションを提供します。

LoadOptions クラスは、ファイルを GroupDocs.Viewer コンポーネントでどのように開き、ロードするかを指定するために使用できるさまざまな設定とパラメーターをカプセル化します。詳細については、この[ページ][] とその子ページを参照してください。

使用例:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/loading/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | LoadOptions クラスの新しいインスタンスを初期化します。 |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | LoadOptions クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | 有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的な破損を修復しようとします。 |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | 有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的な破損を修復しようとします。 |
| [getFileType()](#getFileType--) | 開くファイルのタイプを取得します。 |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | 開くファイルのタイプを設定します。 |
| [getPassword()](#getPassword--) | 暗号化されたファイルを開くためのパスワードを取得します。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 暗号化されたファイルを開くためのパスワードを設定します。 |
| [getCharset()](#getCharset--) | [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV)、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、および[FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) などのテキストベースのファイルやメールメッセージを開く際に使用される文字セットです。 |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV)、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、および[FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) などのテキストベースのファイルやメールメッセージを開く際に使用される文字セットです。 |
| [isDetectCharset()](#isDetectCharset--) | このオプションは、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV)、および[FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) ファイルの文字セット検出を有効にします。 |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | このオプションは、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV)、および[FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) ファイルの文字セット検出を有効にします。 |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | 外部リソースの読み込みタイムアウトを取得します。 |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | グラフィックなどの外部リソースの読み込みタイムアウトを設定します。 |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | java.net.URL を使用してドキュメントをロードするための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の接続タイムアウトを取得します。 |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | java.net.URL を使用してドキュメントをロードするための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の接続タイムアウトを設定します。 |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | java.net.URL を使用してドキュメントをロードするための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の読み取りタイムアウトを取得します。 |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | java.net.URL を使用してドキュメントをロードするための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の読み取りタイムアウトを設定します。 |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | アーカイブの抽出プロセスを制御するためのセキュリティオプションを取得します。 |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | アーカイブ抽出プロセスを制御するためのセキュリティオプションを設定します。 |
| [isSkipExternalResources()](#isSkipExternalResources--) | true に設定された場合、画像などのすべての外部リソースは \#getWhitelistedResources().getWhitelistedResources() を除いてロードされません。 |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | true に設定された場合、画像などのすべての外部リソースは \#getWhitelistedResources().getWhitelistedResources() を除いてロードされません。 |
| [getWhitelistedResources()](#getWhitelistedResources--) | `true` に設定されたときにロードすべき外部リソースに対応する URL フラグメントのリストは \#isSkipExternalResources().isSkipExternalResources() です。 |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | `true` に設定されたときにロードすべき外部リソースに対応する URL フラグメントのリストを設定します。 |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


LoadOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 開くファイルのタイプです。 |

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### _tryRepair {#-tryRepair}
```
public boolean _tryRepair
```


### isTryRepair() {#isTryRepair--}
```
public boolean isTryRepair()
```


有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的破損を修復しようとします。デフォルト値は false です。

この機能は PDF ドキュメントの次の問題に対処します：

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的破損を修復しようとします。デフォルト値は false です。

この機能は PDF ドキュメントの次の問題に対処します：

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


開くファイルのタイプを取得します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


開くファイルのタイプを設定します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


暗号化されたファイルを開くためのパスワードを取得します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String - ファイルを開くためのパスワードです。
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


暗号化されたファイルを開くためのパスワードを設定します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | ファイルを開くためのパスワードです。 |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


[FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV)、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、および[FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) などのテキストベースのファイルやメールメッセージを開く際に使用される文字セットです。

デフォルト値は java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8 です。コード例については、[documentation][] を参照してください。

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


[FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV)、[FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、および[FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) などのテキストベースのファイルやメールメッセージを開く際に使用される文字セットです。

デフォルト値は java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8 です。コード例については、[documentation][] を参照してください。

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


このオプションは [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV)、および [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) ファイルの文字セット検出を有効にします。文字セットが検出できない場合は、デフォルトの [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) が使用されます。

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

エンコーディングが検出できない場合、デフォルトが使用されます。コード例については、[documentation][] を参照してください。

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


このオプションは [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV)、および [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) ファイルの文字セット検出を有効にします。文字セットが検出できない場合は、デフォルトの [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) が使用されます。

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

エンコーディングが検出できない場合、デフォルトが使用されます。コード例については、[documentation][] を参照してください。

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


外部リソースの読み込みタイムアウトを取得します。

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

デフォルト値は 30 秒です。コード例については、[documentation][] を参照してください。

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setResourceLoadingTimeout(5000); // Set resource loading timeout to 5 seconds

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


グラフィックなどの外部リソースの読み込みタイムアウトを設定します。

***Note:** The default value is 30 seconds.*

このオプションは外部リソースを含む Word 処理ドキュメントでサポートされます。デフォルト値は 30 秒です。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceLoadingTimeout | int | ロードタイムアウト（ミリ秒）です。 |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


java.net.URL を使用してドキュメントをロードするための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の接続タイムアウトを取得します。

***Note:** The default value is 5 seconds.*

**Returns:**
int - 接続タイムアウトです。
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


java.net.URL を使用してドキュメントをロードするための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の接続タイムアウトを設定します。

***Note:** The default value is 5 seconds.*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| urlConnectTimeout | int | 接続タイムアウトです。 |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


java.net.URL を使用してドキュメントをロードするための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の読み取りタイムアウトを取得します。

***Note:** The default value is 30 seconds.*

**Returns:**
int - 読み取りタイムアウトです。
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


java.net.URL を使用してドキュメントをロードするための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の読み取りタイムアウトを設定します。

***Note:** The default value is 30 seconds.*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| urlReadTimeout | int | 読み取りタイムアウト。 |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


アーカイブの抽出プロセスを制御するためのセキュリティオプションを取得します。

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - アーカイブ抽出プロセスを構成するためのオプションオブジェクトです。
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


アーカイブ抽出プロセスを制御するためのセキュリティオプションを設定します。

***Note:** Not each archive type supports all options.*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | アーカイブ抽出プロセスを構成するためのオプションオブジェクトです。 |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


true に設定された場合、画像などのすべての外部リソースは \#getWhitelistedResources().getWhitelistedResources() を除いてロードされません。

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


true に設定された場合、画像などのすべての外部リソースは \#getWhitelistedResources().getWhitelistedResources() を除いてロードされません。

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| skipExternalResources | boolean | 外部リソースの読み込みを有効または無効にするフラグです。 |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


`true` に設定されたときにロードすべき外部リソースに対応する URL フラグメントのリストは \#isSkipExternalResources().isSkipExternalResources() です。

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


`true` に設定されたときにロードすべき外部リソースに対応する URL フラグメントのリストを設定します。

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | 読み込むべき外部リソースに対応する URL フラグメントのリストです。 |

