---
title: "FileType"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ファイルタイプを表します。GroupDocs.Viewer がサポートするすべてのファイルタイプのリストを取得するメソッドを提供します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer/filetype/
---

## FileType class

ファイルタイプを表します。**GroupDocs.Viewer** がサポートするすべてのファイルタイプの一覧を取得するメソッドを提供します。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FileType](filetype#constructor)() | 新しい [`FileType`](../filetype) クラスのインスタンスを初期化します。 |
| [FileType](filetype#constructor_1)(string, string) | 新しい [`FileType`](../filetype) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; set; } | ファイル名のサフィックス（ピリオド「.」を含む）例: ".doc"。 |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; set; } | ファイルタイプ名 例: "Microsoft Word Document"。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | ファイル拡張子をファイルタイプにマッピングします。 |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | ファイル拡張子を抽出し、ファイルタイプにマッピングします。 |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | ファイルのメディアタイプをファイルタイプにマッピングします。例: 'application/pdf' は [`PDF`](./pdf) にマッピングされます。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | 現在の [`FileType`](../filetype) が指定された [`FileType`](../filetype) オブジェクトと同じかどうかを判定します。 |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | 現在の [`FileType`](../filetype) が指定されたオブジェクトと同じかどうかを判定します。 |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | 現在の [`FileType`](../filetype) オブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding)(Stream) | ストリームでテキスト [`TXT`](./txt)、[`TSV`](./tsv)、[`CSV`](./csv) ファイルのエンコーディングを検出しようとします。 |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding_1)(string) | パスでテキスト [`TXT`](./txt)、[`TSV`](./tsv)、[`CSV`](./csv) ファイルのエンコーディングを検出しようとします。 |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | サポートされているファイルタイプを取得します |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | 2つの [`FileType`](../filetype) オブジェクトが同じかどうかを判定します。 |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | 2つの [`FileType`](../filetype) オブジェクトが異なるかどうかを判定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | Animated Portable Network Graphic（.apng）は、アニメーションをサポートする PNG フォーマットの拡張です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/apng)をご覧ください。 |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | ActionScript ファイル（.as） |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | ActionScript ファイル（.as） |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | アセンブリ言語ソースコードファイル（.asm） |
| static readonly [AZW3](../../groupdocs.viewer/filetype/azw3) | Amazon Kindle Format 8（KF8）電子書籍は、Amazon Kindle デバイス向けに開発されたデジタルファイル形式です。この形式は従来の AZW ファイルを拡張したもので、Kindle Fire デバイスでのみ使用されますが、先行のファイル形式である MOBI および AZW との下位互換性があります。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/ebook/azw3)をご覧ください。 |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | DOS バッチファイル（.bat） |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | Bitmap Image File（.bmp）はビットマップデジタル画像を保存するために使用されます。これらの画像はグラフィックアダプタに依存せず、デバイス非依存ビットマップ（DIB）ファイル形式とも呼ばれます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/bmp)をご覧ください。 |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | Bzip2 圧縮ファイル（.bz2）は、BZIP2 オープンソース圧縮方式を使用して生成された圧縮ファイルで、主に UNIX や Linux システムで使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/compression/bz2)をご覧ください。 |
| static readonly [C](../../groupdocs.viewer/filetype/c) | C/C++ ソースコードファイル（.c） |
| static readonly [Cab](../../groupdocs.viewer/filetype/cab) | Cabinet（または CAB）は、Microsoft Windows 用のアーカイブファイル形式です。このファイル形式の詳細は[こちら](https://en.wikipedia.org/wiki/Cabinet_(file_format))をご覧ください。 |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | C++ ソースコードファイル（.cc） |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw Vector Graphic Drawing（.cdr）は、CorelDRAW でネイティブに作成されるベクタードローイング画像ファイルで、デジタル画像をエンコードおよび圧縮して保存します。このような描画ファイルには、テキスト、線、形状、画像、色、効果が含まれ、画像内容をベクトルで表現します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/cdr)をご覧ください。 |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | Common File Format ファイルです。このファイル形式の詳細は[こちら](https://fileinfo.com/extension/cf2)をご覧ください。 |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | Computer Graphics Metafile（.cgm）は、ベクタグラフィックス（2D）、ラスタグラフィックス、テキストの保存と交換のための、無料でプラットフォームに依存しない国際標準メタファイル形式です。CGM はオブジェクト指向アプローチと多数の機能を利用して画像を生成します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/cgm)をご覧ください。 |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft Compiled HTML Help File（.chm）は、HELP（アプリケーションのドキュメント）文書用のよく知られた形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/web/chm/)をご覧ください。 |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | CMake ファイル (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx) は、ベクターグラフィックとビットマップグラフィックの両方を含む可能性がある描画画像ファイルです。このファイル形式の詳細は、[here](https://wiki.fileformat.com/image/cmx) で確認できます。 |
| static readonly [CPIO](../../groupdocs.viewer/filetype/cpio) | Cpio は、一般的なファイルアーカイバユーティリティおよびそれに関連するファイル形式です。主に Unix 系のコンピュータ OS にインストールされています。このファイル形式の詳細は、[here](https://wiki.fileformat.com/compression/cpio) で確認できます。 |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | C++ ソースコードファイル (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C# ソースコードファイル (.cs) は、C# プログラミング言語用のソースコードファイルです。Microsoft が .NET Framework 用に導入しました。このファイル形式の詳細は、[here](https://wiki.fileformat.com/programming/cs) で確認できます。 |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | カスケーディングスタイルシート (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | Comma Separated Values ファイル (.csv) は、カンマ区切りの値でデータレコードを含むプレーンテキストファイルを表します。このファイル形式の詳細は、[here](https://wiki.fileformat.com/spreadsheet/csv) で確認できます。 |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | C++ ソースコードファイル (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | DICOM 画像 (.dcm) は、MRI、CT スキャン、超音波画像など、患者の医療情報を保存するデジタル画像を表します。このファイル形式の詳細は、[here](https://wiki.fileformat.com/image/dcm) で確認できます。 |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | MicroStation デザインファイル (.dgn) は、MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成・サポートされる図面です。このファイル形式の詳細は、[here](https://wiki.fileformat.com/cad/dgn) で確認できます。 |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | デバイス非依存ビットマップファイル (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | パッチファイル (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu 画像 (.djvu) は、テキスト、図面、画像、写真が組み合わさったスキャン文書や書籍向けのグラフィックファイル形式です。このファイル形式の詳細は、[here](https://wiki.fileformat.com/image/djvu) で確認できます。 |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | Digital Negative Specification (.dng) は、RAW ファイルの保存に使用されるデジタルカメラ画像形式です。2004年9月に Adobe によって開発され、主にデジタル写真撮影向けに作られました。このファイル形式の詳細は、[here](https://wiki.fileformat.com/image/dng) で確認できます。 |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | Microsoft Word ドキュメント (.doc) は、Microsoft Word またはその他のワードプロセッサで生成されたバイナリ形式の文書を表します。このファイル形式の詳細は、[here](https://wiki.fileformat.com/word-processing/doc) で確認できます。 |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | Word Open XML マクロ有効ドキュメント (.docm) は、Microsoft Word 2007 以降で生成され、マクロを実行できる文書です。このファイル形式の詳細は、[here](https://wiki.fileformat.com/word-processing/docm) で確認できます。 |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML ドキュメント (.docx) は、Microsoft Word 文書の代表的な形式です。2007 年に Microsoft Office 2007 がリリースされた際に導入され、従来のバイナリ形式から XML とバイナリファイルの組み合わせに構造が変更されました。このファイル形式の詳細は、[here](https://wiki.fileformat.com/word-processing/docx) で確認できます。 |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | Word ドキュメントテンプレート (.dot) は、Microsoft Word が作成したテンプレートファイルで、今後の DOC または DOCX ファイル生成のために事前に書式設定された設定を持ちます。このファイル形式の詳細は、[here](https://wiki.fileformat.com/word-processing/dot) で確認できます。 |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | Word Open XML マクロ有効ドキュメントテンプレート (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレートファイルです。このファイル形式の詳細は、[here](https://wiki.fileformat.com/word-processing/dotm) で確認できます。 |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML ドキュメントテンプレート (.dotx) は、Microsoft Word が作成したテンプレートファイルで、今後の DOCX ファイル生成のために事前に書式設定された設定を持ちます。このファイル形式の詳細は、[here](https://wiki.fileformat.com/word-processing/dotx) で確認できます。 |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | Design Web Format ファイル (.dwf) は、閲覧、レビュー、印刷用の圧縮形式で 2D/3D 図面を表します。設計データの一部としてグラフィックとテキストを含み、圧縮形式によりファイルサイズが削減されます。このファイル形式の詳細は、[here](https://wiki.fileformat.com/cad/dwf) で確認できます。 |
| static readonly [DWFX](../../groupdocs.viewer/filetype/dwfx) | Design Web Format File XPS (.dwfx) は、閲覧、レビュー、印刷用の圧縮形式で XPS ドキュメントとして 2D/3D 図面を表します。設計データの一部としてグラフィックとテキストを含み、圧縮形式によりファイルサイズが削減されます。このファイル形式の詳細は、[here](https://wiki.fileformat.com/cad/dwfx) で確認できます。 |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | AutoCAD 図面データベースファイル (.dwg) は、2D および 3D 設計データを格納するために使用される独自のバイナリファイルです。ASCII ファイルである DXF と同様に、DWG は CAD（コンピュータ支援設計）図面用のバイナリファイル形式を表します。このファイル形式の詳細は、[here](https://wiki.fileformat.com/cad/dwg) で確認できます。 |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | AutoCAD 図面テンプレート (.dwt) は、DWG ファイルとして保存できる図面作成の出発点として使用される AutoCAD のテンプレートファイルです。このファイル形式の詳細は、[here](https://wiki.fileformat.com/cad/dwt) で確認できます。 |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | Drawing Exchange Format ファイル (.dxf) は、AutoCAD 図面ファイルのタグ付きデータ表現です。このファイル形式の詳細は、[here](https://wiki.fileformat.com/cad/dxf) で確認できます。 |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | Enhanced Windows Metafile (.emf) は、デバイスに依存しない形でグラフィカル画像を表します。EMF のメタファイルは、時間順に並んだ可変長レコードで構成され、任意の出力デバイスで解析後に保存された画像をレンダリングできます。詳細はこのファイル形式について [here](https://wiki.fileformat.com/image/emf) をご覧ください。 |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | E-Mail Message (.eml) は、Outlook やその他の関連アプリケーションで保存されたメールメッセージを表します。ほぼすべてのメールクライアントが RFC-822 インターネットメッセージ形式標準に準拠しているため、このファイル形式をサポートしています。詳細はこのファイル形式について [here](https://wiki.fileformat.com/email/eml) をご覧ください。 |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | Apple Mail Message (.emlx) は Apple により実装・開発されています。Apple Mail アプリケーションはメールのエクスポートに EMLX ファイル形式を使用します。詳細はこのファイル形式について [here](https://wiki.fileformat.com/email/emlx) をご覧ください。 |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | Enhanced Windows Metafile compressed (.emz) は、GZIP によってデバイスに依存しない形で圧縮されたグラフィカル画像を表します。EMF のメタファイルは、時間順に並んだ可変長レコードで構成され、任意の出力デバイスで解析後に保存された画像をレンダリングできます。詳細はこのファイル形式について [here](https://wiki.fileformat.com/image/emz) をご覧ください。 |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | Encapsulated PostScript File (.eps) は、単一ページの外観を記述する Encapsulated PostScript 言語プログラムを表します。詳細はこのファイル形式について [here](https://wiki.fileformat.com/page-description-language/eps) をご覧ください。 |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | Open eBook File (.epub) は、出版社と読者向けに標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。このフォーマットは現在非常に一般的で、多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。詳細はこのファイル形式について [here](https://wiki.fileformat.com/ebook/epub) をご覧ください。 |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | Ruby ERB Script (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML (SpreadsheetML) は、Excel バイナリファイル形式を表します。このようなファイルは Microsoft Excel のほか、OpenOffice Calc や Apple Numbers といった類似のスプレッドシートプログラムでも作成できます。詳細はこのファイル形式について [here](https://wiki.fileformat.com/spreadsheet/xls) をご覧ください。 |
| static readonly [FBX](../../groupdocs.viewer/filetype/fbx) | Autodesk FBX Interchange File (FilmBoX) (.fbx) は、3D モデル形式を表します。詳細はこのファイル形式について [here](https://wiki.fileformat.com/cad/fbx) をご覧ください。 |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | Flat XML ODF Template (.fodg) は、Apache OpenOffice の Draw アプリケーションでベクター画像として描画要素を保存するために使用されます。詳細はこのファイル形式について [here](https://wiki.fileformat.com/image/fodg) をご覧ください。 |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument Presentation (.fodp) は、OpenDocument Flat XML プレゼンテーションを表します。詳細はこのファイル形式について [here](https://fileinfo.com/extension/fodp) をご覧ください。 |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | OpenDocument Flat XML Spreadsheet (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | Graphical Interchange Format File (.gif) は、非常に圧縮された画像の一種です。各 GIF 画像は通常、ピクセルあたり最大 8 ビット、全体で最大 256 色を使用できます。詳細はこのファイル形式について [here](https://wiki.fileformat.com/image/gif) をご覧ください。 |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | Groovy Source Code File (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu Zipped File (.gz) は、gzip 圧縮アプリケーションで作成された圧縮ファイルです。複数の圧縮ファイルを含むことができ、UNIX や Linux システムで一般的に使用されています。詳細はこのファイル形式について [here](https://wiki.fileformat.com/compression/gz) をご覧ください。 |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | Gnu Zipped File (.gzip) は、Unix 系システムで使用されていた Compress プログラムの代替として導入されたフリーユーティリティです。このようなファイルは、Windows と macOS の両方で利用できる WinZip などの多数のアプリケーションで開いたり展開したりできます。詳細はこのファイル形式について [here](https://wiki.fileformat.com/compression/gz) をご覧ください。 |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C/C++/Objective-C Header File (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | Haml Source Code File (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | C++ Header File (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | Hypertext Markup Language File (.htm) は、ブラウザで表示するために作成されたウェブページの拡張子です。詳細はこのファイル形式について [here](https://wiki.fileformat.com/web/html) をご覧ください。 |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | Hypertext Markup Language File (.html) は、ブラウザで表示するために作成されたウェブページの拡張子です。詳細はこのファイル形式について [here](https://wiki.fileformat.com/web/html) をご覧ください。 |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | Icon File (.ico) は、Microsoft Windows 上でアプリケーションを表すアイコンとして使用される画像ファイルタイプです。詳細はこのファイル形式について [here](https://wiki.fileformat.com/image/ico) をご覧ください。 |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | Industry Foundation Classes File (.ifc) は、建築オブジェクトとそのプロパティのインポート・エクスポートのための国際標準を確立するファイル形式です。このファイル形式は、異なるソフトウェアアプリケーション間の相互運用性を提供します。詳細はこのファイル形式について [here](https://wiki.fileformat.com/cad/ifc) をご覧ください。 |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | Initial Graphics Exchange Specification (IGES) (.igs) |
| static readonly [Iso](../../groupdocs.viewer/filetype/iso) | ISO光学ディスクイメージは、CDやDVDなどの光学ディスク上の全データの内容を表す、ISO-9660標準に基づく非圧縮のアーカイブディスクイメージファイルです。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/iso/)で確認できます。 |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | JPEG 2000コードストリーム (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000コードストリーム (.j2k) は、DCT圧縮ではなくウェーブレット圧縮を使用して圧縮された画像です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/j2k)で確認できます。 |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | Javaソースコードファイル (.java) |
| static readonly [JFIF](../../groupdocs.viewer/filetype/jfif) | JPEGファイル交換フォーマット (.jfif) は、プラットフォーム間の高速な画像交換のために開発された画像です。この形式はJPEG圧縮を使用します。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jfif)で確認できます。 |
| static readonly [JLS](../../groupdocs.viewer/filetype/jls) | JPEG-LS (JLS) (.jls) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000コアイメージファイル (.jp2) は、画像符号化システムおよび最先端の画像圧縮標準です。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jp2)で確認できます。 |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | JPEG 2000コードストリーム (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | JPEG画像 (.jpeg) は、非可逆圧縮方式で保存される画像フォーマットの一種です。圧縮の結果として得られる出力画像は、保存サイズと画像品質のトレードオフとなります。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jpeg)で確認できます。 |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | JPEG 2000イメージファイル (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | JPEG画像 (.jpg) は、非可逆圧縮方式で保存される画像フォーマットの一種です。圧縮の結果として得られる出力画像は、保存サイズと画像品質のトレードオフとなります。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/jpeg)で確認できます。 |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | JPEG 2000イメージファイル (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | JPEG 2000イメージファイル (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | JavaScriptファイル (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | JavaScriptオブジェクト表記ファイル (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | LESSスタイルシート (.less) |
| static readonly [Lha](../../groupdocs.viewer/filetype/lha) | LHAまたはLZHは、フリーウェアの圧縮ユーティリティおよび関連するファイル形式です。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/lzh/)で確認できます。 |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | ログファイル (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | Objective-C実装ファイル (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | Xcode Makefileスクリプト (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | メールボックスファイル (.mbox) このファイル形式の詳細は[here](https://fileinfo.com/extension/mbox)で確認できます。 |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | Markdownドキュメントファイル (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | MHTMLウェブアーカイブ (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | MIME HTMLファイル (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | MLソースコードファイル (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | Objective-C++ ソースファイル (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket eBook (.mobi) は、最も広く使用されている電子書籍ファイル形式の一つです。この形式は、古い OEB (Open Ebook Format) 形式を拡張したもので、Mobipocket Reader の独自形式として使用されていました。このファイル形式の詳細は [here](https://wiki.fileformat.com/ebook/mobi) で確認できます。 |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | Microsoft Project File (.mpp) は、Microsoft Project のデータファイルで、プロジェクト管理に関する情報を統合的に保存します。このファイル形式の詳細は [here](https://wiki.fileformat.com/project-management/mpp) で確認できます。 |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft Project Template (.mpt) には、基本情報や構造、.MPP ファイル作成のためのドキュメント設定が含まれています。このファイル形式の詳細は [here](https://wiki.fileformat.com/project-management/mpt) で確認できます。 |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | Microsoft Project Exchange file (.mpx) は、ASCII 形式のファイルで、Microsoft Project (MSP) と、Primavera Project Planner、Sciforma、Timerline Precision Estimating など MPX 形式をサポートする他のアプリケーション間でプロジェクト情報を転送するために使用されます。このファイル形式の詳細は [here](https://wiki.fileformat.com/project-management/mpx) で確認できます。 |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook Mail Message (.msg) は、Microsoft Outlook と Exchange がメールメッセージ、連絡先、予定、その他のタスクを保存するために使用するファイル形式です。このファイル形式の詳細は [here](https://wiki.fileformat.com/email/msg) で確認できます。 |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | Lotus Notes Database (.nsf) このファイル形式の詳細は [here](https://fileinfo.com/extension/nsf) で確認できます。 |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple Numbers は、Excel に似たバイナリファイル形式を表します。このようなファイルは Apple Numbers アプリケーションで作成できます。このファイル形式の詳細は [here](https://fileinfo.com/extension/numbers) で確認できます。 |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D Object File (.obj) は、Wavefront Technologies が導入した 3D 画像ファイルです。このファイル形式の詳細は [here](https://wiki.fileformat.com/3d/obj/) で確認できます。 |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | OpenDocument Graphic File (.odg) は、Apache OpenOffice の Draw アプリケーションで使用され、ベクター画像として描画要素を保存します。このファイル形式の詳細は [here](https://wiki.fileformat.com/image/odg) で確認できます。 |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument Presentation (.odp) は、OpenOffice.org が OASIS Open 標準で使用するプレゼンテーションファイル形式です。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/odp) で確認できます。 |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | OpenDocument Spreadsheet (.ods) は、ユーザーが編集可能な OpenDocument スプレッドシート文書形式を指します。データは ODF ファイル内に行と列として保存されます。このファイル形式の詳細は [here](https://wiki.fileformat.com/spreadsheet/ods) で確認できます。 |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument Text Document (.odt) は、OpenDocument テキストファイル形式に基づくワードプロセッシングアプリケーションで作成される文書タイプです。このファイル形式の詳細は [here](https://wiki.fileformat.com/word-processing/odt) で確認できます。 |
| static readonly [OFD](../../groupdocs.viewer/filetype/ofd) | Open Fixed-layout Document (OFD) 形式は GB/T 33190-2016 によって定義されており、中国の公共機関で PDF に代わることを目指しています。 |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | Outlook Offline Data File (.ost) は、Microsoft Outlook を使用して Exchange Server に登録した際に、ローカルマシン上でオフラインモードのユーザーメールボックスデータを表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/email/ost) で確認できます。 |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | OpenDocument Graphic Template (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | OpenDocument Presentation Template (.otp) は、OASIS OpenDocument 標準形式でアプリケーションが作成するプレゼンテーションテンプレートファイルを表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/presentation/otp) で確認できます。 |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | OpenDocument Spreadsheet Template (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | OpenDocument Document Template (.ott) は、OASIS の OpenDocument 標準形式に準拠したアプリケーションが生成するテンプレート文書を表します。このファイル形式の詳細は [here](https://wiki.fileformat.com/word-processing/ott) で確認できます。 |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | OpenXPS File (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | Printer Command Language Document (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | Portable Document Format File (.pdf) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形で文書や参考資料を表現する標準を導入することでした。このファイル形式の詳細は [here](https://wiki.fileformat.com/view/pdf) で確認できます。 |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | PHP Source Code File (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | Perl Script (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT (HPGL) (.plt) は、Autodesk, Inc. が導入したベクトルベースのプロッターファイルで、特定の CAD ファイルに関する情報を含みます。プロットの詳細は生産において高い精度と正確さが求められ、PLT ファイルはすべての画像を点ではなく線で印刷するため、これを保証します。このファイル形式の詳細は [here](https://wiki.fileformat.com/cad/plt) で確認できます。 |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | Portable Network Graphic (.png) は、ロスレス圧縮を使用するラスタ画像ファイル形式の一種です。このファイル形式は Graphics Interchange Format (GIF) の代替として作成され、著作権制限がありません。このファイル形式の詳細は[here](https://wiki.fileformat.com/image/png)で確認できます。 |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | PowerPoint Template (.pot) は、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint のテンプレートファイルを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pot)で確認できます。 |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) は、マクロに対応した Microsoft PowerPoint のテンプレートファイルです。POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーションファイルを作成する際に使用できる既定設定が含まれています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/potm)で確認できます。 |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) は、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint のテンプレートプレゼンテーションを表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/potx)で確認できます。 |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | PowerPoint Slide Show (.pps) は、スライドショー目的で Microsoft PowerPoint を使用して作成されます。PPS ファイルの読み取りと作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pps)で確認できます。 |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) は、Microsoft PowerPoint 2007 以降で作成されたマクロ対応スライドショーのファイル形式を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppsm)で確認できます。 |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) ファイルは、スライドショー目的で Microsoft PowerPoint 2007 以降を使用して作成されます。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppsx)で確認できます。 |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint Presentation (.ppt) は、スライドショーとして表示するためのスライド集合で構成された PowerPoint ファイルを表します。これは Microsoft PowerPoint 97-2003 で使用されるバイナリファイル形式を指定しています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/ppt)で確認できます。 |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation は、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応プレゼンテーションファイルです。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pptm)で確認できます。 |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) は、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーションファイルです。以前のバイナリ形式の PPT と異なり、PPTX 形式は Microsoft PowerPoint のオープン XML プレゼンテーションファイル形式に基づいています。このファイル形式の詳細は[here](https://wiki.fileformat.com/presentation/pptx)で確認できます。 |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | Java Properties File (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | PostScript File (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | PowerShell script file (.ps1) は、Windows PowerShell Cmdlet ファイル用のファイル形式です。このファイル形式の詳細は[here](https://fileinfo.com/extension/ps1)で確認できます。 |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | PowerShell script module manifest (.psd1) は、PowerShell モジュールマニフェストスクリプト用のファイル形式です。このファイル形式の詳細は[here](https://fileinfo.com/extension/psd1)で確認できます。 |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | PowerShell script module (.psm1) は、PowerShell モジュールスクリプト用のファイル形式です。このファイル形式の詳細は[here](https://fileinfo.com/extension/psm1)で確認できます。 |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | Outlook Personal Information Store File (.pst) は、さまざまなユーザー情報を保存する Outlook Personal Storage Files（Personal Storage Table とも呼ばれる）を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/email/pst)で確認できます。 |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | Python Script (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive (.rar) は、RAR（WINRAR）圧縮方式で生成された圧縮ファイルです。このファイル形式の詳細は[here](https://wiki.fileformat.com/compression/rar)で確認できます。 |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | Ruby Source Code (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | reStructuredText File (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | Rich Text Format File (.rtf) は、アプリケーション内で使用するための書式設定されたテキストとグラフィックをエンコードする方法を表します。このファイル形式の詳細は[here](https://wiki.fileformat.com/word-processing/rtf)で確認できます。 |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | Syntactically Awesome StyleSheets File (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala Source Code File (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | Scheme Source Code File (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | Generic Script File (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z, .7zip) は LZMA と LZMA2 圧縮を備えた無料のオープンソースアーカイバです。このファイル形式の詳細は[こちら](https://docs.fileformat.com/compression/7z/)をご覧ください。 |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash シェルスクリプト (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | Standard ML ソースコードファイル (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | 構造化クエリ言語データファイル (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | Stereolithography ファイル (.stl) は 3 次元表面ジオメトリを表す交換可能なファイル形式です。この形式は高速プロトタイピング、3D プリント、コンピュータ支援製造などのさまざまな分野で使用されています。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/cad/stl)をご覧ください。 |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | Scalable Vector Graphics ファイル (.svg) は、画像の外観を記述するために XML ベースのテキスト形式を使用するベクターグラフィックスファイルです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/svg)をご覧ください。 |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | Scalable Vector Graphics ファイル (.svgz) は、画像の外観を記述するために XML ベースのテキスト形式を使用し、GZIP で圧縮されたベクターグラフィックスファイルです。このファイル形式の詳細は[こちら](https://fileinfo.com/extension/svgz)をご覧ください。 |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | StarOffice Calc スプレッドシート (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | Consolidated Unix File Archive (.tar) は、1 つまたは複数のファイルをまとめるために Unix 系ユーティリティで作成されたアーカイブです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/compression/tar)をご覧ください。 |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | Consolidated Unix File Archive (.tgz, .tar.gz) は、1 つまたは複数のファイルをまとめるために Unix 系ユーティリティで作成されたアーカイブです。このファイル形式の詳細は[こちら](https://fileinfo.com/extension/tgz)をご覧ください。 |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | Consolidated Unix File Archive (.txz, .tar.xz) は、1 つまたは複数のファイルをまとめるために Unix 系ユーティリティで作成されたアーカイブです。このファイル形式の詳細は[こちら](https://fileinfo.com/extension/txz)をご覧ください。 |
| static readonly [TarZst](../../groupdocs.viewer/filetype/tarzst) | TZST ファイル (.tar.zst, .tzst) は Zstandard アーカイブ (ZST) で、内部に Consolidated Unix File Archive (Tar) を含み、Unix 系ユーティリティで作成された 1 つまたは複数のファイルをまとめるためのものです。 |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | LaTeX ソースドキュメント (.tex) は、プログラミング機能とマークアップ機能を備えた言語で、文書の組版に使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/page-description-language/tex)をご覧ください。 |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) は、TRUEVISION が開発したビットマップデジタル画像を保存するために使用されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/tga)をご覧ください。 |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | Consolidated Unix File Archive (.tgz, .tar.gz) は、1 つまたは複数のファイルをまとめるために Unix 系ユーティリティで作成されたアーカイブです。このファイル形式の詳細は[こちら](https://fileinfo.com/extension/tgz)をご覧ください。 |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | Tagged Image File (.tif) は、このファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。二値、グレースケール、パレットカラー、フルカラーの画像データを複数のカラースペースで記述できます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/tiff)をご覧ください。 |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | Tagged Image File Format (.tiff) は、このファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。二値、グレースケール、パレットカラー、フルカラーの画像データを複数のカラースペースで記述できます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/tiff)をご覧ください。 |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | Tab Separated Values ファイル (.tsv) は、タブで区切られたプレーンテキスト形式のデータを表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/spreadsheet/tsv)をご覧ください。 |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | プレーンテキストファイル (.txt) は、行単位のプレーンテキストを含む文書を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/word-processing/txt)をご覧ください。 |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | Consolidated Unix File Archive (.txz, .tar.xz) は、1 つまたは複数のファイルをまとめるために Unix 系ユーティリティで作成されたアーカイブです。このファイル形式の詳細は[こちら](https://fileinfo.com/extension/txz)をご覧ください。 |
| static readonly [Tzst](../../groupdocs.viewer/filetype/tzst) | TZST ファイル (.tar.zst, .tzst) は Zstandard アーカイブ (ZST) で、内部に Consolidated Unix File Archive (Tar) を含み、Unix 系ユーティリティで作成された 1 つまたは複数のファイルをまとめるためのものです。 |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | 不明なファイルタイプを表します。 |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | Visual Basic プロジェクトアイテムファイル (.vb) は、Microsoft が .NET アプリケーション開発のために作成した Visual Basic 言語のソースコードファイルです。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/programming/vb)をご覧ください。 |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | vCard ファイル (.vcf) は、連絡先情報を保存するデジタルファイル形式です。この形式は、一般的な情報交換アプリケーション間でのデータ交換に広く使用されています。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/email/vcf)をご覧ください。 |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | Visio Web Drawing (.vdw) は、Web 図面のレンダリングに必要なストリームとストレージを指定するファイル形式を表します。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/web/vdw)をご覧ください。 |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | Visio Drawing XML ファイル (.vdx) は、Microsoft Visio で作成された任意の図面やチャートで、XML 形式で保存されたもの（拡張子は .VDX）を表します。Visio の XML 図面ファイルは、Microsoft が開発した Visio ソフトウェアで作成されます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/vdx)をご覧ください。 |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | Vim 設定ファイル (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | Visio Drawing ファイル (.vsd) は、Microsoft Visio アプリケーションで作成された、さまざまなグラフィックオブジェクトとそれらの相互接続を表す図面です。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/image/vsd)をご覧ください。 |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) は、マクロをサポートする Microsoft Visio アプリケーションで作成された図面ファイルです。VSDM ファイルは OPC/XML 図面で、VSDX に似ていますが、ファイルを開くとマクロを実行できる機能も提供します。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vsdm) でご確認ください。 |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | Visio Drawing (.vsdx) は、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式を表します。これは、従来のバイナリ形式 .VSD（以前の Microsoft Visio がサポート）に代わるものとして開発されました。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vsdx) でご確認ください。 |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | Visio Stencil File(.vss) は、Microsoft Visio 2007 以前で作成されたステンシルファイルです。ステンシルファイルは、.VSD Visio 図面に組み込むことができる描画オブジェクトを提供します。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vss) でご確認ください。 |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) は、マクロをサポートする Microsoft Visio のステンシルファイルです。VSSM ファイルを開くと、マクロを実行して図表内の形状の書式設定や配置を行うことができます。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vssm) でご確認ください。 |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | Visio Stencil File (.vssx) は、Microsoft Visio 2013 以降で作成された描画ステンシルです。VSSX ファイル形式は Visio 2013 以降で開くことができます。Visio ファイルは、形状のコレクション、コネクタ、フローチャート、ネットワークレイアウト、UML 図など、さまざまな描画要素を表現できることで知られています。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vssx) でご確認ください。 |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio Drawing Template (.vst) は、Microsoft Visio で作成されたベクター画像ファイルで、以降のファイル作成のテンプレートとして機能します。これらのテンプレートファイルはバイナリ形式で、新しい Visio 図面の作成に使用されるデフォルトのレイアウトと設定が含まれています。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vst) でご確認ください。 |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) は、マクロをサポートする Microsoft Visio で作成されたテンプレートファイルです。VSDX ファイルとは異なり、VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで作成されたマクロを実行できます。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vstm) でご確認ください。 |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | Visio Drawing Template (.vstx) は、Microsoft Visio 2013 以降で作成された描画テンプレートファイルです。これらの VSTX ファイルは、デフォルトのレイアウトと設定を持つ .VSDX ファイルとして保存される Visio 図面作成の出発点を提供します。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vstx) でご確認ください。 |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | Visio Stencil XML File (.vsx) は、Microsoft Visio で図表作成に使用される描画や形状からなるステンシルを指します。VSX ファイルは XML 形式で保存され、Visio 2013 までサポートされていました。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vsx) でご確認ください。 |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio Template XML File (.vtx) は、XML 形式でディスクに保存される Microsoft Visio の図面テンプレートです。このテンプレートは、同一設定の Visio ファイルを複数作成するための基本設定を提供することを目的としています。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/vtx) でご確認ください。 |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP Image (.webp) は、可逆圧縮と非可逆圧縮に基づく最新のラスタウェブ画像ファイル形式です。画像サイズを大幅に削減しながら、同等の画質を提供します。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/webp) でご確認ください。 |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | Windows Metafile (.wmf) は、ベクターおよびビットマップ形式の画像データを保存するための Microsoft Windows Metafile (WMF) を表します。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/image/wmf) でご確認ください。 |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | Compressed Windows Metafile (.wmz) は、GZIP アーカイブで圧縮された Microsoft Windows Metafile (WMF) を表し、ベクターおよびビットマップ形式の画像データを保存します。このファイル形式の詳細は、[こちら](https://fileinfo.com/extension/wmz#compressed_windows_metafile) でご確認ください。 |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | Microsoft Excel アドイン (.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | Excel Spreadsheet (.xls) は、Excel バイナリファイル形式を表します。このようなファイルは、Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシートプログラムでも作成できます。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/spreadsheet/xls) でご確認ください。 |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) は、Excel バイナリファイル形式を指定します。この形式は、Excel ブックの内容を示すレコードと構造の集合です。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/spreadsheet/xlsb) でご確認ください。 |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) は、マクロをサポートするスプレッドシートファイルの一種です。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/spreadsheet/xlsm) でご確認ください。 |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) は、Microsoft Office 2007 のリリースとともに Microsoft が導入した、Microsoft Excel ドキュメントの広く知られた形式です。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/spreadsheet/xlsx) でご確認ください。 |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel Template (.xlt) は、Microsoft Office スイートの一部であるスプレッドシートアプリケーション Microsoft Excel で作成されたテンプレートファイルです。Microsoft Office 97-2003 は新規 XLT ファイルの作成と開くことをサポートしていました。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/spreadsheet/xlt) でご確認ください。 |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel Macro-Enabled Template (.xltm) は、Microsoft Excel がマクロ対応テンプレートファイルとして生成するファイルを表します。XLTM ファイルは構造が XLTX と似ていますが、後者はマクロ付きテンプレートの作成をサポートしていません。このファイル形式の詳細は、[こちら](https://wiki.fileformat.com/spreadsheet/xltm) でご確認ください。 |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx) は、Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレートを表します。これは、XLTX ファイルで指定された同じ設定を持つ XLSX ファイルを生成するために利用できる標準テンプレートファイルを作成するために使用されます。詳しくはこのファイル形式について [こちら](https://wiki.fileformat.com/spreadsheet/xltx) をご覧ください。 |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML File (.xml). GroupDocs.Viewer は XML ファイルを処理するための特別なプロセッサを備えています。詳細は [ドキュメント](https://docs.groupdocs.com/viewer/net/render-xml-documents/) をご覧ください。 |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML Paper Specification File (.xps) は、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。この形式は Microsoft によって EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、ドキュメントのレイアウト、外観、印刷情報に XML を使用します。詳しくはこのファイル形式について [こちら](https://wiki.fileformat.com/page-description-language/xps) をご覧ください。 |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ file (.xz) は、LZMA アルゴリズムに基づく高圧縮率の圧縮アルゴリズムを使用したアーカイブです。詳しくはこのファイル形式について [こちら](https://fileinfo.com/extension/xz) をご覧ください。 |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | YAML ドキュメント (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | Zipped File (.zip) は、1 つまたは複数のファイルやディレクトリを保持できるアーカイブを表します。詳しくはこのファイル形式について [こちら](https://wiki.fileformat.com/compression/zip) をご覧ください。 |
| static readonly [Zstandard](../../groupdocs.viewer/filetype/zstandard) | ZST file は、Zstandard (zstd) 圧縮アルゴリズムで生成された圧縮ファイルです。これは、アルゴリズムによるロスレス圧縮で作成された圧縮ファイルです。ZST ファイルは、データベース、ファイルシステム、ネットワーク、ゲームなど、さまざまな種類のファイルを圧縮するために使用できます。詳しくはこのファイル形式について [こちら](https://docs.fileformat.com/compression/zst/) をご覧ください。 |

### 関連項目

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
