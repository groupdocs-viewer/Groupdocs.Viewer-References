---
title: "LoadOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ファイルを開く際に使用されるオプションを提供します。"
type: docs
weight: 18
url: /ja/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

ファイルを開く際に使用されるオプションを提供します。


LoadOptions クラスは、使用できるさまざまな設定とパラメーターをカプセル化します
ファイルをどのように開き、GroupDocs.Viewer コンポーネントにロードすべきかを指定します。
詳細については、この [page](../https://docs.groupdocs.com/viewer/java/loading/) とその子ページを参照してください。


使用例:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | 新しいインスタンスを初期化します |
LoadOptions
クラス。
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | 新しいインスタンスを初期化します |
LoadOptions
クラス。
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | 有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的破損を修復しようとします。 |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | 有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的破損を修復しようとします。 |
|
|  | [getFileType()](#getFileType--) | 開くファイルのタイプを取得します。 |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | 開くファイルのタイプを設定します。 |
|
|  | [getPassword()](#getPassword--) | 暗号化されたファイルを開くためのパスワードを取得します。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 暗号化されたファイルを開くためのパスワードを設定します。 |
|
|  | [getCharset()](#getCharset--) | テキストベースのファイルやメールメッセージを開く際に使用される文字セットは、例えば |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
および [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG)。
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | テキストベースのファイルやメールメッセージを開く際に使用される文字セットは、例えば |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
および [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG)。
|
|  | [isDetectCharset()](#isDetectCharset--) | このオプションは、[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype#TSV)、および [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) ファイルの文字セット検出を有効にします。 |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | このオプションは、[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype#TSV)、および [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) ファイルの文字セット検出を有効にします。 |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | 外部リソースの読み込みタイムアウトを取得します。 |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | 画像などの外部リソースの読み込みタイムアウトを設定します。 |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | java.net.URL を使用してドキュメントを読み込むための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の接続タイムアウトを取得します。 |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | java.net.URL を使用してドキュメントを読み込むための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の接続タイムアウトを設定します。 |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | java.net.URL を使用してドキュメントを読み込むための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の読み取りタイムアウトを取得します。 |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | java.net.URL を使用してドキュメントを読み込むための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の読み取りタイムアウトを設定します。 |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | アーカイブの抽出プロセスを制御するセキュリティオプションを取得します。 |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | アーカイブの抽出プロセスを制御するセキュリティオプションを設定します。 |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | true に設定すると、画像などのすべての外部リソースは #getWhitelistedResources().getWhitelistedResources() で許可されたものを除き、ロードされません。 |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | true に設定すると、画像などのすべての外部リソースは #getWhitelistedResources().getWhitelistedResources() で許可されたものを除き、ロードされません。 |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | #isSkipExternalResources().isSkipExternalResources() が `true` に設定されている場合にロードすべき外部リソースに対応する URL フラグメントの一覧です。 |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | #isSkipExternalResources().isSkipExternalResources() が `true` に設定されている場合にロードすべき外部リソースに対応する URL フラグメントの一覧を設定します。 |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


新しいインスタンスを初期化します
LoadOptions
クラス。


コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/) を参照してください。


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


新しいインスタンスを初期化します
LoadOptions
クラス。


コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | 開くファイルのタイプです。 |
|

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

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的破損を修復しようとします。デフォルト値は false です。


この機能は PDF ドキュメントの次の問題に対処します：

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


開くファイルのタイプを取得します。


コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/) を参照してください。


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


開くファイルのタイプを設定します。


コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


暗号化されたファイルを開くためのパスワードを取得します。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/) を参照してください。


**Returns:**
java.lang.String - ファイルを開くためのパスワード。

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


暗号化されたファイルを開くためのパスワードを設定します。


コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.lang.String | ファイルを開くためのパスワードです。 |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


テキストベースのファイルやメールメッセージを開く際に使用される文字セットは、例えば
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
および [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG)。
デフォルト値は java.nio.charset.StandardCharsets#UTF_8.UTF_8 です。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/) を参照してください。

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // 文字セットを設定

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


テキストベースのファイルやメールメッセージを開く際に使用される文字セットは、例えば
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
および [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG)。
デフォルト値は java.nio.charset.StandardCharsets#UTF_8.UTF_8 です。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/) を参照してください。

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // 文字セットを設定

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


このオプションは、[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype#TSV)、および [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) ファイルの文字セット検出を有効にします。文字セットが検出できない場合は、デフォルトの [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) が使用されます。

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


エンコーディングが検出できない場合、デフォルトが使用されます。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/) を参照してください。

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // エンコーディング検出を有効化

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


このオプションは、[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT)、[FileType.TSV](../../com.groupdocs.viewer/filetype#TSV)、および [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) ファイルの文字セット検出を有効にします。文字セットが検出できない場合は、デフォルトの [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) が使用されます。

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


エンコーディングが検出できない場合、デフォルトが使用されます。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/) を参照してください。

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // エンコーディング検出を有効化

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


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

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


デフォルト値は30秒です。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents) を参照してください。

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // リソース読み込みタイムアウトを5秒に設定

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


画像などの外部リソースの読み込みタイムアウトを設定します。


***Note:** The default value is 30 seconds.*


このオプションは、外部リソースを含む Word Processing ドキュメントでサポートされています。
デフォルト値は30秒です。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | 読み込みタイムアウト（ミリ秒）。 |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


java.net.URL を使用してドキュメントを読み込むための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の接続タイムアウトを取得します。


***Note:** The default value is 5 seconds.*


**Returns:**
int - 接続タイムアウト。

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


java.net.URL を使用してドキュメントを読み込むための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の接続タイムアウトを設定します。


***Note:** The default value is 5 seconds.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | urlConnectTimeout | int | 接続タイムアウトです。 |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


java.net.URL を使用してドキュメントを読み込むための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の読み取りタイムアウトを取得します。


***Note:** The default value is 30 seconds.*


**Returns:**
int - 読み取りタイムアウト。

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


java.net.URL を使用してドキュメントを読み込むための [Viewer](../../com.groupdocs.viewer/viewer) 作成時の読み取りタイムアウトを設定します。


***Note:** The default value is 30 seconds.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | urlReadTimeout | int | 読み取りタイムアウトです。 |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


アーカイブの抽出プロセスを制御するセキュリティオプションを取得します。


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - アーカイブ抽出プロセスを構成するためのオプション オブジェクトです。

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


アーカイブの抽出プロセスを制御するセキュリティオプションを設定します。


***Note:** Not each archive type supports all options.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | アーカイブ抽出プロセスを構成するためのオプション オブジェクトです。 |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


true に設定すると、画像などのすべての外部リソースは #getWhitelistedResources().getWhitelistedResources() で許可されたものを除き、ロードされません。

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // 外部リソースの読み込みをスキップします

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


true に設定すると、画像などのすべての外部リソースは #getWhitelistedResources().getWhitelistedResources() で許可されたものを除き、ロードされません。

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // 外部リソースの読み込みをスキップします

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | skipExternalResources | boolean | 外部リソースの読み込みを有効または無効にするフラグです。 |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


#isSkipExternalResources().isSkipExternalResources() が `true` に設定されている場合にロードすべき外部リソースに対応する URL フラグメントの一覧です。

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // 外部リソースの読み込みをスキップします
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // リソース URL に 'avatars.githubusercontent.com' フラグメントが含まれる外部リソースの読み込みを有効にします
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


#isSkipExternalResources().isSkipExternalResources() が `true` に設定されている場合にロードすべき外部リソースに対応する URL フラグメントの一覧を設定します。

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // 外部リソースの読み込みをスキップします
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // リソース URL に 'avatars.githubusercontent.com' フラグメントが含まれる外部リソースの読み込みを有効にします
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | 読み込むべき外部リソースに対応する URL フラグメントの一覧です。 |
|

