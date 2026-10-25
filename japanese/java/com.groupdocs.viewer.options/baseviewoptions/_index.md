---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "基本的なレンダリングオプションを含みます。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

基本的なレンダリングオプションを含みます。


この
BaseViewOptions
クラスは GroupDocs.Viewer のレンダリングオプションのベースとして機能します。
レンダリング時に、出力される HTML、PDF、PNG、JPEG ファイルのレンダリング動作をカスタマイズできます。
特定のドキュメント形式です。


***Note:** For internal usage.*

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | テキストファイルをページに分割するオプションを取得します。 |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | テキストファイルをページに分割するオプションを設定します。 |
|
|  | [isRenderComments()](#isRenderComments--) | コメントのレンダリングを有効にします。 |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | コメントのレンダリングを有効にします。 |
|
|  | [isRemoveComments()](#isRemoveComments--) | true に設定された場合、コメントのレンダリングを無効にします。 |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | true に設定された場合、コメントのレンダリングを無効にします。 |
|
|  | [isRenderNotes()](#isRenderNotes--) | ノートのレンダリングを有効にします。 |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | ノートのレンダリングを有効にします。 |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | 非表示ページのレンダリングを有効にします。 |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | 非表示ページのレンダリングを有効にします。 |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトフォント。 |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトフォント。 |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | アーカイブファイルの表示オプションを取得します。 |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | アーカイブファイルの表示オプションを設定します。 |
|
|  | [getCadOptions()](#getCadOptions--) | CAD 図面の表示オプションを取得します。 |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | CAD 図面の表示オプションを設定します。 |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | メールメッセージの表示オプションを取得します。 |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | メールメッセージの表示オプションを設定します。 |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | MS Outlook データファイルの表示オプションを取得します。 |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | MS Outlook データファイルの表示オプションを設定します。 |
|
|  | [getPdfOptions()](#getPdfOptions--) | PDF ドキュメントの表示オプションを取得します。 |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | PDF ドキュメントの表示オプションを取得します。 |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Lotus Notes ストレージデータファイルの表示オプションを取得します。 |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Lotus Notes ストレージデータファイルの表示オプションを設定します。 |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | プロジェクト管理ファイルの表示オプションを取得します。 |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | プロジェクト管理ファイルの表示オプションを設定します。 |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | スプレッドシートファイルの表示オプションを取得します。 |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | スプレッドシートファイルの表示オプションを設定します。 |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | ワードプロセッシングファイルの表示オプションです。 |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | ワードプロセッシングファイルの表示オプションです。 |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | ドキュメントを表示する際の Visio ファイル処理用レンダリングオプションを取得します。 |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | ドキュメントを表示する際の Visio ファイル処理用レンダリングオプションを設定します。 |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | プレゼンテーションドキュメントの処理用表示オプションを取得します。 |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | プレゼンテーションドキュメントの処理用表示オプションを設定します。 |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | 出力される HTML/PDF/PNG/JPEG の外観をカスタマイズできるレンダリング オプションを取得します |
Web ドキュメントをレンダリングする際に。
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | 出力される HTML/PDF/PNG/JPEG の外観をカスタマイズできるレンダリング オプションを設定します |
Web ドキュメントをレンダリングする際に。
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


テキストファイルをページに分割するオプションを取得します。


詳細情報とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/) を参照してください。


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


テキストファイルをページに分割するオプションを設定します。


詳細情報とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | テキスト ファイルの分割オプションです。 |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


コメントのレンダリングを有効にします。


既定では、GroupDocs.Viewer はコメントをレンダリングしません。これを有効にするには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments) を参照してください。


**Returns:**
boolean - コメントをレンダリングする場合は true、そうでない場合は false。

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


コメントのレンダリングを有効にします。


既定では、GroupDocs.Viewer はコメントをレンダリングしません。これを有効にするには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | コメントをレンダリングする場合は true、そうでない場合は false。 |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


true に設定するとコメントのレンダリングが無効になります。既定は false で、すべてのコメントが表示されます。


PDF や WordProcessing などの一部のドキュメント形式にはコメントが含まれることがあります。既定では GroupDocs.Viewer がそれらをレンダリングします。このオプションを true に設定すると、結果のドキュメントからコメントが除外される場合があります。
このオプションは、旧式の 'RenderComments' プロパティに代わります。


**Returns:**
boolean - コメントをレンダリングする場合は true、そうでない場合は false。

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


true に設定するとコメントのレンダリングが無効になります。既定は false で、すべてのコメントが表示されます。


PDF や WordProcessing などの一部のドキュメント形式にはコメントが含まれることがあります。既定では GroupDocs.Viewer がそれらをレンダリングします。このオプションを true に設定すると、結果のドキュメントからコメントが除外される場合があります。
このオプションは、旧式の 'RenderComments' プロパティに代わります。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | コメントをレンダリングする場合は true、そうでない場合は false。 |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


ノートのレンダリングを有効にします。


プレゼンテーションや Microsoft Project ファイルなどの一部のファイルにはノートが含まれることがあります。既定では、GroupDocs.Viewer はノートをレンダリングしません。これを有効にするには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes) を参照してください。


**Returns:**
boolean - ノートをレンダリングする場合は true、そうでない場合は false。

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


ノートのレンダリングを有効にします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | ノートをレンダリングする場合は true、そうでない場合は false。 |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


非表示ページのレンダリングを有効にします。


プレゼンテーションやスプレッドシートなどの一部のファイルには非表示ページが含まれることがあります。既定では、GroupDocs.Viewer はこれらのページをレンダリングしません。これを有効にするには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides) を参照してください。


**Returns:**
boolean - 非表示ページをレンダリングする場合は true、そうでない場合は false。

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


非表示ページのレンダリングを有効にします。


プレゼンテーションやスプレッドシートなどの一部のファイルには非表示ページが含まれることがあります。既定では、GroupDocs.Viewer はこれらのページをレンダリングしません。これを有効にするには、このプロパティを true に設定します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | 非表示ページをレンダリングする場合は true、そうでない場合は false。 |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトフォント。


このプロパティを使用して、ドキュメントのデフォルト フォントを設定します。GroupDocs.Viewer は、インストールされていないフォントの代わりにこのフォントをレンダリング時に使用します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/replace-missing-font/) を参照してください。


**Returns:**
java.lang.String - デフォルト フォントの名前です。

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトフォント。


このプロパティを使用して、ドキュメントのデフォルト フォントを設定します。GroupDocs.Viewer は、インストールされていないフォントの代わりにこのフォントをレンダリング時に使用します。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/replace-missing-font/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.lang.String | デフォルト フォントの名前です。 |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


アーカイブファイルの表示オプションを取得します。


詳細情報とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/) を参照してください。


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


アーカイブファイルの表示オプションを設定します。


詳細情報とコード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | アーカイブ ファイルの表示オプションです。 |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


CAD 図面の表示オプションを取得します。


詳細情報とコード例については、[CAD 図面とモデルを HTML、PDF、画像ファイルとしてレンダリング](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) と [CAD ファイルのレンダリング オプションを指定](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/) を参照してください。


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


CAD 図面の表示オプションを設定します。


詳細情報とコード例については、[CAD 図面とモデルを HTML、PDF、画像ファイルとしてレンダリング](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) と [CAD ファイルのレンダリング オプションを指定](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | CAD 図面の表示オプションです。 |
|

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


メールメッセージの表示オプションを取得します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-email-messages/) を参照してください。


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


メールメッセージの表示オプションを設定します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-email-messages/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | メールメッセージの表示オプションです。 |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


MS Outlook データファイルの表示オプションを取得します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/) を参照してください。


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


MS Outlook データファイルの表示オプションを設定します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | 設定する MS Outlook データファイルの表示オプションです。 |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


PDF ドキュメントの表示オプションを取得します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/) を参照してください。


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


PDF ドキュメントの表示オプションを取得します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | PDF ドキュメントの表示オプションです。 |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Lotus Notes ストレージデータファイルの表示オプションを取得します。


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Lotus Notes ストレージデータファイルの表示オプションを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Lotus Notes ストレージ データファイルの表示オプションです。 |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


プロジェクト管理ファイルの表示オプションを取得します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/) を参照してください。


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


プロジェクト管理ファイルの表示オプションを設定します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | 設定するプロジェクト管理ファイルの表示オプションです。 |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


スプレッドシートファイルの表示オプションを取得します。


詳細情報とコード例については、[Excel と Apple Numbers のスプレッドシートを HTML、PDF、画像ファイルとしてレンダリング](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)、[ワークシートをページに分割](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/)、および [スプレッドシートのレンダリング オプションを指定](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/) を参照してください。


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


スプレッドシートファイルの表示オプションを設定します。


詳細情報とコード例については、[Excel と Apple Numbers のスプレッドシートを HTML、PDF、画像ファイルとしてレンダリング](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)、[ワークシートをページに分割](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/)、および [スプレッドシートのレンダリング オプションを指定](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | スプレッドシート ファイルの表示オプションです。 |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


ワードプロセッシングファイルの表示オプションです。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-word-documents/) を参照してください。


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


ワードプロセッシングファイルの表示オプションです。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-word-documents/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Word 文書のレンダリング用ワード処理オプションです。 |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


ドキュメントを表示する際の Visio ファイル処理用レンダリングオプションを取得します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-visio-documents/) を参照してください。


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


ドキュメントを表示する際の Visio ファイル処理用レンダリングオプションを設定します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-visio-documents/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Visio ファイルを処理するための Visio レンダリング オプションです。 |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


プレゼンテーションドキュメントの処理用表示オプションを取得します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-presentations/) を参照してください。


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - プレゼンテーション ドキュメントを処理するためのプレゼンテーション表示オプションです。

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


プレゼンテーションドキュメントの処理用表示オプションを設定します。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-presentations/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | プレゼンテーション ドキュメントを処理するためのプレゼンテーション表示オプションです。 |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


出力される HTML/PDF/PNG/JPEG の外観をカスタマイズできるレンダリング オプションを取得します
Web ドキュメントをレンダリングする際に。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-web-documents/) を参照してください。


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - レンダリング オプションをカスタマイズするための WebDocumentOptions オブジェクトです。

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


出力される HTML/PDF/PNG/JPEG の外観をカスタマイズできるレンダリング オプションを設定します
Web ドキュメントをレンダリングする際に。


詳細情報とコード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-web-documents/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | WebDocumentOptions オブジェクトは、レンダリング オプションをカスタマイズするためのものです。 |
|

