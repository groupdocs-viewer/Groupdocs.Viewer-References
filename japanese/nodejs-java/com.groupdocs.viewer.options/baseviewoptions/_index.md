---
title: "BaseViewOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "基本的なレンダリングオプションを含みます。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

基本的なレンダリングオプションを含みます。

BaseViewOptions クラスは GroupDocs.Viewer のレンダリングオプションの基底として機能します。特定のドキュメント形式をレンダリングする際に、出力 HTML、PDF、PNG、JPEG ファイルのレンダリング動作をカスタマイズできます。

***Note:** For internal usage.*
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextOptions()](#getTextOptions--) | テキストファイルをページに分割するオプションを取得します。 |
| [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | テキストファイルをページに分割するオプションを設定します。 |
| [isRenderComments()](#isRenderComments--) | コメントのレンダリングを有効にします。 |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | コメントのレンダリングを有効にします。 |
| [isRemoveComments()](#isRemoveComments--) | true に設定するとコメントのレンダリングが無効になります。 |
| [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | true に設定するとコメントのレンダリングが無効になります。 |
| [isRenderNotes()](#isRenderNotes--) | ノートのレンダリングを有効にします。 |
| [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | ノートのレンダリングを有効にします。 |
| [isRenderHiddenPages()](#isRenderHiddenPages--) | 非表示ページのレンダリングを有効にします。 |
| [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | 非表示ページのレンダリングを有効にします。 |
| [getDefaultFontName()](#getDefaultFontName--) | ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトフォントです。 |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトフォントです。 |
| [getArchiveOptions()](#getArchiveOptions--) | アーカイブファイルの表示オプションを取得します。 |
| [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | アーカイブファイルの表示オプションを設定します。 |
| [getCadOptions()](#getCadOptions--) | CAD 図面の表示オプションを取得します。 |
| [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | CAD 図面の表示オプションを設定します。 |
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
| [getEmailOptions()](#getEmailOptions--) | メールメッセージの表示オプションを取得します。 |
| [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | メールメッセージの表示オプションを設定します。 |
| [getOutlookOptions()](#getOutlookOptions--) | MS Outlook データファイルの表示オプションを取得します。 |
| [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | MS Outlook データファイルの表示オプションを設定します。 |
| [getPdfOptions()](#getPdfOptions--) | PDF ドキュメントのビューオプションを取得します。 |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | PDF ドキュメントのビューオプションを取得します。 |
| [getMailStorageOptions()](#getMailStorageOptions--) | Lotus Notes ストレージデータファイルのビューオプションを取得します。 |
| [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Lotus Notes ストレージデータファイルのビューオプションを設定します。 |
| [getProjectManagementOptions()](#getProjectManagementOptions--) | プロジェクト管理ファイルのビューオプションを取得します。 |
| [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | プロジェクト管理ファイルのビューオプションを設定します。 |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | スプレッドシートファイルのビューオプションを取得します。 |
| [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | スプレッドシートファイルのビューオプションを設定します。 |
| [getWordProcessingOptions()](#getWordProcessingOptions--) | Word 処理ファイルのビューオプションです。 |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Word 処理ファイルのビューオプションです。 |
| [getVisioRenderingOptions()](#getVisioRenderingOptions--) | ドキュメントを表示する際の Visio ファイル処理用レンダリングオプションを取得します。 |
| [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | ドキュメントを表示する際の Visio ファイル処理用レンダリングオプションを設定します。 |
| [getPresentationOptions()](#getPresentationOptions--) | プレゼンテーションドキュメントの処理用ビューオプションを取得します。 |
| [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | プレゼンテーションドキュメントの処理用ビューオプションを設定します。 |
| [getWebDocumentOptions()](#getWebDocumentOptions--) | Web ドキュメントをレンダリングする際に、出力 HTML/PDF/PNG/JPEG の外観をカスタマイズできるレンダリングオプションを取得します。 |
| [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Web ドキュメントをレンダリングする際に、出力 HTML/PDF/PNG/JPEG の外観をカスタマイズできるレンダリングオプションを設定します。 |
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


テキストファイルをページに分割するオプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


テキストファイルをページに分割するオプションを設定します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | テキストファイル分割オプションです。 |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


コメントのレンダリングを有効にします。

デフォルトでは、GroupDocs.Viewer はコメントをレンダリングしません。これを有効にするには、このプロパティを true に設定します。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Returns:**
boolean - コメントがレンダリングされる場合は true、そうでない場合は false。
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


コメントのレンダリングを有効にします。

デフォルトでは、GroupDocs.Viewer はコメントをレンダリングしません。これを有効にするには、このプロパティを true に設定します。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true  コメントがレンダリングされる場合、false  それ以外。 |

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


true に設定するとコメントのレンダリングが無効になります。デフォルトは false \u2014 すべてのコメントが表示されます。

PDF や WordProcessing などの一部のドキュメント形式にはコメントが含まれることがあります。デフォルトでは GroupDocs.Viewer がそれらをレンダリングします。このオプションを true に設定すると、結果のドキュメントからコメントが除外される可能性があります。このオプションは、旧式の 'RenderComments' プロパティに取って代わります。

**Returns:**
boolean - コメントがレンダリングされる場合は true、そうでない場合は false。
### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


true に設定するとコメントのレンダリングが無効になります。デフォルトは false \u2014 すべてのコメントが表示されます。

PDF や WordProcessing などの一部のドキュメント形式にはコメントが含まれることがあります。デフォルトでは GroupDocs.Viewer がそれらをレンダリングします。このオプションを true に設定すると、結果のドキュメントからコメントが除外される可能性があります。このオプションは、旧式の 'RenderComments' プロパティに取って代わります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true  コメントがレンダリングされる場合、false  それ以外。 |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


ノートのレンダリングを有効にします。

プレゼンテーションや Microsoft Project ファイルなどの一部のファイルにはノートが含まれることがあります。デフォルトでは GroupDocs.Viewer はノートをレンダリングしません。これを有効にするには、このプロパティを true に設定します。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes

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
| value | boolean | true  ノートがレンダリングされる場合、false  それ以外。 |

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


非表示ページのレンダリングを有効にします。

プレゼンテーションやスプレッドシートなどの一部のファイルには非表示ページが含まれることがあります。デフォルトでは GroupDocs.Viewer はこれらのページをレンダリングしません。これを有効にするには、このプロパティを true に設定します。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Returns:**
boolean - 隠しページをレンダリングする場合は true、そうでない場合は false。
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


非表示ページのレンダリングを有効にします。

プレゼンテーションやスプレッドシートなどの一部のファイルには非表示ページが含まれることがあります。デフォルトでは GroupDocs.Viewer はこれらのページをレンダリングしません。これを有効にするには、このプロパティを true に設定します。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | 隠しページをレンダリングする場合は true、そうでない場合は false。 |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトフォントです。

このプロパティを使用してドキュメントのデフォルトフォントを設定します。GroupDocs.Viewer はレンダリング時に、インストールされていないフォントの代わりにこのフォントを使用します。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Returns:**
java.lang.String - デフォルトフォントの名前。
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトフォントです。

このプロパティを使用してドキュメントのデフォルトフォントを設定します。GroupDocs.Viewer はレンダリング時に、インストールされていないフォントの代わりにこのフォントを使用します。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | デフォルトフォントの名前。 |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


アーカイブファイルの表示オプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


アーカイブファイルの表示オプションを設定します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | アーカイブファイルの表示オプション。 |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


CAD 図面の表示オプションを取得します。

詳細情報とコード例については、[Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] と [Specify rendering options for CAD files][] を参照してください。


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


CAD 図面の表示オプションを設定します。

詳細情報とコード例については、[Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] と [Specify rendering options for CAD files][] を参照してください。


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | CAD 図面の表示オプション。 |

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

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


メールメッセージの表示オプションを設定します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | メールメッセージの表示オプション。 |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


MS Outlook データファイルの表示オプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


MS Outlook データファイルの表示オプションを設定します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | 設定する MS Outlook データファイルの表示オプション。 |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


PDF ドキュメントのビューオプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


PDF ドキュメントのビューオプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | PDF ドキュメントの表示オプション。 |

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Lotus Notes ストレージデータファイルのビューオプションを取得します。

**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.
### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Lotus Notes ストレージデータファイルのビューオプションを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Lotus Notes ストレージデータファイルの表示オプション。 |

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


プロジェクト管理ファイルのビューオプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


プロジェクト管理ファイルのビューオプションを設定します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | 設定するプロジェクト管理ファイルの表示オプション。 |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


スプレッドシートファイルのビューオプションを取得します。

詳細情報とコード例については、[Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]、[Split a worksheet into pages][]、および [Specify spreadsheet rendering options][] を参照してください。


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


スプレッドシートファイルのビューオプションを設定します。

詳細情報とコード例については、[Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]、[Split a worksheet into pages][]、および [Specify spreadsheet rendering options][] を参照してください。


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | スプレッドシートファイルの表示オプション。 |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Word 処理ファイルのビューオプションです。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Word 処理ファイルのビューオプションです。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Word ドキュメントをレンダリングするためのワードプロセッシングオプション。 |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


ドキュメントを表示する際の Visio ファイル処理用レンダリングオプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


ドキュメントを表示する際の Visio ファイル処理用レンダリングオプションを設定します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Visio ファイルを処理するための Visio レンダリングオプション。 |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


プレゼンテーションドキュメントの処理用ビューオプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Returns:**
com.groupdocs.viewer.options.PresentationOptions - プレゼンテーションドキュメントを処理するためのプレゼンテーション表示オプション。
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


プレゼンテーションドキュメントの処理用ビューオプションを設定します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions | プレゼンテーションドキュメントを処理するためのプレゼンテーション表示オプション。 |

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Web ドキュメントをレンダリングする際に、出力 HTML/PDF/PNG/JPEG の外観をカスタマイズできるレンダリングオプションを取得します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - レンダリングオプションをカスタマイズするための WebDocumentOptions オブジェクト。
### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Web ドキュメントをレンダリングする際に、出力 HTML/PDF/PNG/JPEG の外観をカスタマイズできるレンダリングオプションを設定します。

詳細情報とコード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | レンダリングオプションをカスタマイズするための WebDocumentOptions オブジェクト。 |

