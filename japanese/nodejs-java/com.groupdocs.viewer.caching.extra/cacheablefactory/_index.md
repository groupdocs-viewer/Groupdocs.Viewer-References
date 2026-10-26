---
title: "CacheableFactory"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "このクラスはカスタマイズを支援します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

このクラスは [Cache](../../com.groupdocs.viewer.caching/cache) のカスタマイズを支援します。

シリアル化用のカスタムモデルは、このクラスのメソッドをオーバーライドして組み込みのものではなく返すことで実装できます。この目的を達成するには、CacheableFactory を拡張し、カスタムファクトリの新しいインスタンスを [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-) メソッドに渡して有効化します。

使用例:

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

キャッシュのカスタマイズに関する詳細、ガイドライン、例については、[GroupDocs.Viewer documentation][] を参照してください。


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInstance()](#getInstance--) | CacheableFactory のインスタンスを取得し、キャッシュ可能オブジェクトの作成に使用できます。 |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | 使用する CacheableFactory のインスタンスを設定します。 |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | 指定されたファイルタイプとページに対する [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) インターフェイスの実装を作成します。 |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | 指定されたファイルタイプ、ページ、ノート数に対する [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) インターフェイスの実装を作成します。 |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | 指定されたファイルタイプ、ページ、フォルダーに対する [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) インターフェイスの実装を作成します。 |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | 指定された文字、位置、寸法に対する [Character](../../com.groupdocs.viewer.results/character) インターフェイスの実装を作成します。 |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | 指定されたファイルタイプに対する [FileInfo](../../com.groupdocs.viewer.results/fileinfo) インターフェイスの実装を作成します。 |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | 指定された名前と可視性を持つ [Layer](../../com.groupdocs.viewer.results/layer) インターフェイスの実装を作成します。 |
| [newLayer(String name)](#newLayer-java.lang.String-) | 指定された名前を持つ [Layer](../../com.groupdocs.viewer.results/layer) インターフェイスの実装を作成します。 |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | 指定された名前、幅、高さを持つ [Layout](../../com.groupdocs.viewer.results/layout) インターフェイスの実装を作成します。 |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | 指定されたライン、位置、寸法、単語を持つ [Line](../../com.groupdocs.viewer.results/line) インターフェイスの実装を作成します。 |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | [Attachment](../../com.groupdocs.viewer.results/attachment) インターフェイスの実装を作成します。 |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) インターフェイスの実装を作成します。 |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) インターフェイスの実装を作成します。 |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) インターフェイスの実装を作成します。 |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | 指定されたファイルタイプ、ページリスト、フォルダーリストに基づく [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) インターフェイスの実装を作成します。 |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | 指定された番号と可視性を持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。 |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | 指定された番号、名前、可視性を持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。 |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | 指定された番号、名前、可視性、幅、高さを持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。 |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | 指定された番号、可視性、幅、高さを持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。 |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | 指定された番号、名前、可視性、幅、高さ、行を持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。 |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | 指定された番号、可視性、幅、高さ、行を持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。 |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | 指定されたファイルタイプ、ページ、および印刷許可フラグを持つ [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) インターフェイスの実装を作成します。 |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | 指定されたファイルタイプ、ページ、レイヤー、レイアウトを持つ [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) インターフェイスの実装を作成します。 |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | 指定されたファイルタイプ、ページ、開始日、終了日を持つ [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) インターフェイスの実装を作成します。 |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | 指定された値、座標、寸法を持つ [TextElement](../../com.groupdocs.viewer.results/textelement) インターフェイスの実装を作成します。 |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | 指定されたファイルタイプ、ページ、ノート数を持つ MboxViewInfo インターフェイスの実装を作成します。 |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | 指定された単語、座標、寸法、文字を持つ [Word](../../com.groupdocs.viewer.results/word) インターフェイスの実装を作成します。 |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


CacheableFactory のインスタンスを取得し、キャッシュ可能オブジェクトの作成に使用できます。

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


使用する  CacheableFactory  のインスタンスを設定します。これにより、キャッシュ可能なファクトリのカスタム実装が可能になります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | 設定する  CacheableFactory  のインスタンスです。 |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


指定されたファイルタイプとページに対する [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |
| ページ | java.util.List<com.groupdocs.viewer.results.Page> | ドキュメントページを表すページのリストです。 |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


指定されたファイルタイプ、ページ、ノート数に対する [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |
| ページ | java.util.List<com.groupdocs.viewer.results.Page> | ドキュメントページを表すページのリストです。 |
| notesCount | int | ドキュメント内の Lotus Notes の数です。 |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


指定されたファイルタイプ、ページ、フォルダーに対する [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |
| ページ | java.util.List<com.groupdocs.viewer.results.Page> | ドキュメントページを表すページのリストです。 |
| フォルダー | java.util.List<java.lang.String> | アーカイブ内のフォルダーのリストです。 |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


指定された文字、位置、寸法に対する [Character](../../com.groupdocs.viewer.results/character) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 文字 | char | 文字です。 |
| x | double | 文字位置の x 座標です。 |
| y | double | 文字位置の y 座標です。 |
| width | double | 文字の幅。 |
| height | double | 文字の高さ。 |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


指定されたファイルタイプに対する [FileInfo](../../com.groupdocs.viewer.results/fileinfo) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


指定された名前と可視性を持つ [Layer](../../com.groupdocs.viewer.results/layer) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | レイヤーの名前。 |
| visible | boolean | レイヤーの表示状態。 |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


指定された名前を持つ [Layer](../../com.groupdocs.viewer.results/layer) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | レイヤーの名前。 |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


指定された名前、幅、高さを持つ [Layout](../../com.groupdocs.viewer.results/layout) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | レイアウトの名前。 |
| width | double | レイアウトの幅。 |
| height | double | レイアウトの高さ。 |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


指定されたライン、位置、寸法、単語を持つ [Line](../../com.groupdocs.viewer.results/line) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| line | java.lang.String | 行の内容。 |
| x | double | 行を含む矩形の左上点の X 座標。 |
| y | double | 行を含む矩形の左上点の Y 座標。 |
| width | double | 行を含む矩形の幅（ピクセル単位）。 |
| height | double | 行を含む矩形の高さ（ピクセル単位）。 |
| words | java.util.List<com.groupdocs.viewer.results.Word> | 行に含まれる単語。 |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | 添付ファイルの名前。 |
| filePath | java.lang.String | 添付ファイルの相対パス（例: "folder/file.docx"）。ファイルがアーカイブのルート、メールメッセージ、またはデータファイルにある場合は、ファイル名を指定してください。 |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 添付ファイルの ID。 |
| fileName | java.lang.String | 添付ファイルの名前。 |
| filePath | java.lang.String | 添付ファイルの相対パス（例: "folder/file.docx"）。ファイルがアーカイブのルート、メールメッセージ、またはデータファイルにある場合は、ファイル名を指定してください。 |
| size | long | 添付ファイルのサイズ。 |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 添付ファイルの ID。 |
| fileName | java.lang.String | 添付ファイルの名前。 |
| filePath | java.nio.file.Path | 添付ファイルの相対パスまたは絶対パス。 |
| size | long | 添付ファイルのサイズ。 |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment)インターフェイスの実装を作成します。添付ファイルは、ドキュメントまたはメールメッセージに添付されたファイルを表します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 添付ファイルの ID。 |
| fileName | java.lang.String | 添付ファイルの名前。 |
| filePath | java.lang.String | 添付ファイルの相対パスまたは絶対パスです。フォルダー内のファイルパス、またはアーカイブのルート、メールメッセージ、データファイルにファイルがある場合はファイル名そのものでも構いません。 |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 添付ファイルの種類です。 |
| size | long | 添付ファイルのサイズ。 |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


指定されたファイルタイプ、ページリスト、フォルダーリストに基づく [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |
| ページ | java.util.List<com.groupdocs.viewer.results.Page> | ページのリストです。 |
| フォルダー | java.util.List<java.lang.String> | フォルダーのリストです。 |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


指定された番号と可視性を持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | ページ番号です。 |
| visible | boolean | 表示フラグです。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


指定された番号、名前、可視性を持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | ページ番号です。 |
| 名前 | java.lang.String | ページ名です。 |
| visible | boolean | 表示フラグです。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


指定された番号、名前、可視性、幅、高さを持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | ページ番号です。 |
| 名前 | java.lang.String | ページ名です。 |
| visible | boolean | 表示フラグです。 |
| width | int | ページの幅です。 |
| height | int | ページの高さです。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


指定された番号、可視性、幅、高さを持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | ページ番号です。 |
| visible | boolean | 表示フラグです。 |
| width | int | ページの幅です。 |
| height | int | ページの高さです。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


指定された番号、名前、可視性、幅、高さ、行を持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | ページ番号です。 |
| 名前 | java.lang.String | ページ名です。 |
| visible | boolean | 表示フラグです。 |
| width | int | ページの幅です。 |
| height | int | ページの高さです。 |
| 行 | java.util.List<com.groupdocs.viewer.results.Line> | ページに含まれる行です。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


指定された番号、可視性、幅、高さ、行を持つページを表す [Page](../../com.groupdocs.viewer.results/page) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | ページ番号です。 |
| visible | boolean | 表示フラグです。 |
| width | int | ページの幅です。 |
| height | int | ページの高さです。 |
| 行 | java.util.List<com.groupdocs.viewer.results.Line> | ページに含まれる行です。 |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


指定されたファイルタイプ、ページ、および印刷許可フラグを持つ [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |
| ページ | java.util.List<com.groupdocs.viewer.results.Page> | ページのリストです。 |
| printingAllowed | boolean | 印刷が許可されているかどうかを示すフラグです。 |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


指定されたファイルタイプ、ページ、レイヤー、レイアウトを持つ [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |
| ページ | java.util.List<com.groupdocs.viewer.results.Page> | ページのリストです。 |
| レイヤー | java.util.List<com.groupdocs.viewer.results.Layer> | レイヤーのリストです。 |
| レイアウト | java.util.List<com.groupdocs.viewer.results.Layout> | レイアウトのリストです。 |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


指定されたファイルタイプ、ページ、開始日、終了日を持つ [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルタイプです。 |
| ページ | java.util.List<com.groupdocs.viewer.results.Page> | ページのリストです。 |
| startDate | java.util.Date | 開始日です。 |
| endDate | java.util.Date | 終了日です。 |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


指定された値、座標、寸法を持つ [TextElement](../../com.groupdocs.viewer.results/textelement) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T | 値。 |
| x | double | X座標。 |
| y | double | Y座標。 |
| width | double | 幅。 |
| height | double | 高さ。 |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


指定されたファイルタイプ、ページ、ノート数を持つ MboxViewInfo インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | ファイルの種類。 |
| ページ | java.util.List<com.groupdocs.viewer.results.Page> | 表示するページのリスト。 |
| notesCount | int | Lotus データベースストレージファイルに含まれるノート数。 |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - MboxViewInfo 実装の新しいインスタンス。
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


指定された単語、座標、寸法、文字を持つ [Word](../../com.groupdocs.viewer.results/word) インターフェイスの実装を作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 単語 | java.lang.String | 単語。 |
| x | double | 単語を含む矩形が始まるページレイアウト上の最左上点の X 座標。 |
| y | double | 単語を含む矩形が始まるページレイアウト上の最左上点の Y 座標。 |
| width | double | 単語を含む矩形の幅（ピクセル単位）。 |
| height | double | 単語を含む矩形の高さ（ピクセル単位）。 |
| 文字 | java.util.List<com.groupdocs.viewer.results.Character> | 単語に含まれる文字。 |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
