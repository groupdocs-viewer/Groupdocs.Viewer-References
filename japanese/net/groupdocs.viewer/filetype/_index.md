---
title: FileType
second_title: GroupDocs.Viewer for .NET API リファレンス
description: ファイルの種類を表しますでサポートされているすべてのファイル タイプのリストを取得するメソッドを提供しますGroupDocs.Viewer.
type: docs
weight: 70
url: /ja/net/groupdocs.viewer/filetype/
---
## FileType class

ファイルの種類を表します。でサポートされているすべてのファイル タイプのリストを取得するメソッドを提供します。**GroupDocs.Viewer**.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [FileType](filetype#constructor)() | の新しいインスタンスを初期化します[`FileType`](../filetype)class. |
| [FileType](filetype#constructor_1)(string, string) | の新しいインスタンスを初期化します[`FileType`](../filetype)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; set; } | ファイル名のサフィックス (ピリオド "." を含む) 例: ".doc". |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; set; } | ファイルの種類名 (例: "Microsoft Word ドキュメント". |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | ファイル拡張子をファイル タイプにマップします。 |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | ファイル拡張子を抽出し、ファイル タイプにマップします。 |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | ファイル メディア タイプをファイル タイプにマップします。たとえば、「application/pdf」がマップされます。[`PDF`](./pdf). |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | ファイルの署名を読み取ってファイルの種類を検出します。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | ファイルの署名を読み取ってファイルの種類を検出します。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | ファイルの署名を読み取ってファイルの種類を検出します。 |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | ファイルの署名を読み取ってファイルの種類を検出します。 |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | 現在の[`FileType`](../filetype)指定と同じです[`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | 現在の[`FileType`](../filetype)指定されたオブジェクトと同じです. |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | 現在のハッシュ コードを返します。[`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding)(Stream) | テキストの検出を試みます[`TXT`](./txt)、[`TSV`](./tsv) 、 と[`CSV`](./csv) stream. によるファイルのエンコード |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding_1)(string) | テキストの検出を試みます[`TXT`](./txt)、[`TSV`](./tsv) 、 と[`CSV`](./csv)パスでエンコードされたファイル. |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | サポートされているファイル タイプを取得します |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | 2 つの[`FileType`](../filetype)オブジェクトは同じです. |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | 2 つの[`FileType`](../filetype)オブジェクトは同じではありません. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [AI](../../groupdocs.viewer/filetype/ai) | Adobe Illustrator (.ai) は、Adobe Illustrator 図面のファイル形式です。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/ai#adobe_illustrator_file) |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | Animated Portable Network Graphic (.apng) は、アニメーションをサポートする PNG 形式の拡張です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/apng) |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | ActionScript ファイル (.as) |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | ActionScript ファイル (.as) |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | アセンブリ言語ソース コード ファイル (.asm) |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | DOS バッチ ファイル (.bat) |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | ビットマップ イメージ ファイル (.bmp) は、ビットマップ デジタル イメージの保存に使用されます。これらの画像はグラフィックス アダプターに依存せず、デバイスに依存しないビットマップ (DIB) ファイル形式とも呼ばれます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/bmp) |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | Bzip2 圧縮ファイル (.bz2) は、BZIP2 オープン ソース圧縮方式を使用して生成された圧縮ファイルで、主に UNIX または Linux システムで使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/compression/bz2) |
| static readonly [C](../../groupdocs.viewer/filetype/c) | C/C++ ソース コード ファイル (.c) |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | C++ ソース コード ファイル (.cc) |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw ベクター グラフィック ドローイング (.cdr) は、エンコードおよび圧縮されたデジタル画像を保存するために CorelDRAW でネイティブに作成されるベクター描画画像ファイルです。このような図面ファイルには、テキスト、線、図形、画像、色、および画像コンテンツのベクトル表現用の効果が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/cdr) |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | 一般的なファイル形式 File このファイル形式の詳細[ここ](https://fileinfo.com/extension/cf2). |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | コンピューター グラフィックス メタファイル (.cgm) は、ベクター グラフィックス (2D)、ラスター グラフィックス、およびテキストを格納および交換するための、プラットフォームに依存しない無料の国際標準メタファイル形式です。 CGM は、オブジェクト指向のアプローチと、画像生成のための多くの機能規定を使用します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/cgm) |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft コンパイル済み HTML ヘルプ ファイル (.chm) は、HELP (一部のアプリケーションのドキュメント) ドキュメントのよく知られた形式です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/web/chm/) |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | CMake ファイル (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx) は、ベクター グラフィックとビットマップ グラフィックを含む可能性のある描画イメージ ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/cmx) |
| static readonly [CPIO](../../groupdocs.viewer/filetype/cpio) | Cpio は、一般的なファイル アーカイバ ユーティリティとそれに関連するファイル形式です。主に Unix 系のコンピューター オペレーティング システムにインストールされます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/compression/cpio). |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | C++ ソース コード ファイル (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C# ソース コード ファイル (.cs) は、C# プログラミング言語のソース コード ファイルです。 .NET Framework で使用するために Microsoft によって導入されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/programming/cs) |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | カスケード スタイル シート (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | カンマ区切り値ファイル (.csv) は、カンマ区切りの値を持つデータのレコードを含むプレーン テキスト ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/csv) |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | C++ ソース コード ファイル (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | DICOM 画像 (.dcm) は、MRI、CT スキャン、超音波画像などの患者の医療情報を格納するデジタル画像を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/dcm) |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | MicroStation デザイン ファイル (.dgn) は、MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成およびサポートされている図面です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/dgn) |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | デバイスに依存しないビットマップ ファイル (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | パッチ ファイル (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu 画像 (.djvu) は、スキャンした文書や書籍、特にテキスト、図、画像、写真の組み合わせを含むものを対象としたグラフィック ファイル形式です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/djvu) |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | Digital Negative Specification (.dng) は、RAW ファイルの保存に使用されるデジタル カメラの画像形式です。 2004 年 9 月に Adobe によって開発されました。基本的にはデジタル写真用に開発されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/dng) |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | Microsoft Word ドキュメント (.doc) は、Microsoft Word またはその他のワープロ ドキュメントによって生成されたドキュメントをバイナリ ファイル形式で表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/doc) |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | Word Open XML マクロ有効ドキュメント (.docm) は、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docm) |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML ドキュメント (.docx) は、Microsoft Word ドキュメントのよく知られた形式です。 2007 年の Microsoft Office 2007 のリリースで導入されたこの新しいドキュメント形式の構造は、プレーン バイナリから XML とバイナリ ファイルの組み合わせに変更されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/docx) |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | Word ドキュメント テンプレート (.dot) は、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOC または DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dot) |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | Word Open XML マクロ有効ドキュメント テンプレート (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotm) |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML ドキュメント テンプレート (.dotx) は、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/dotx) |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | Design Web Format File (.dwf) は、デザイン ファイルを表示、レビュー、または印刷するための圧縮形式の 2D/3D 図面を表します。設計データの一部としてグラフィックスとテキストが含まれており、その圧縮形式によりファイルのサイズが縮小されています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/dwf). |
| static readonly [DWFX](../../groupdocs.viewer/filetype/dwfx) | デザイン Web 形式ファイル XPS (.dwfx) は、2D/3D 図面を、デザイン ファイルの表示、レビュー、または印刷用の圧縮形式の XPS ドキュメントとして表します。設計データの一部としてグラフィックスとテキストが含まれており、その圧縮形式によりファイルのサイズが縮小されています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/dwfx). |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | AutoCAD Drawing Database File (.dwg) は、2D および 3D 設計データを格納するために使用される独自のバイナリ ファイルを表します。 ASCII ファイルである DXF と同様に、DWG は CAD (Computer Aided Design) 図面のバイナリ ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/dwg). |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | AutoCAD Drawing Template (.dwt) は、DWG ファイルとして保存できる図面を作成するためのスターターとして使用される AutoCAD 図面テンプレート ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/dwt) |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | Drawing Exchange Format File (.dxf) は、AutoCAD 図面ファイルのタグ付きデータ表現です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/dxf) |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | 拡張 Windows メタファイル (.emf) は、デバイスに依存しないグラフィック イメージを表します。 EMF のメタファイルは、任意の出力デバイスでの解析後に格納されたイメージをレンダリングできる、時系列の可変長レコードで構成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/emf) |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | 電子メール メッセージ (.eml) は、Outlook およびその他の関連アプリケーションを使用して保存された電子メール メッセージを表します。ほとんどすべての電子メール クライアントは、RFC-822 Internet Message Format Standard に準拠するために、このファイル形式をサポートしています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/eml) |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | Apple メール メッセージ (.emlx) は、Apple によって実装および開発されています。 Apple Mail アプリケーションは、メールのエクスポートに EMLX ファイル形式を使用します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/emlx) |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | 拡張 Windows メタファイル圧縮 (.emz) は、GZIP によってデバイスに依存せずに圧縮されたグラフィック イメージを表します。 EMF のメタファイルは、任意の出力デバイスでの解析後に格納されたイメージをレンダリングできる、時系列の可変長レコードで構成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/emz) |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | Encapsulated PostScript ファイル (.eps) は、単一ページの外観を記述する Encapsulated PostScript 言語プログラムを記述します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/eps) |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | Open eBook ファイル (.epub) は、発行者と消費者に標準のデジタル出版形式を提供する電子書籍ファイル形式です。この形式は現在非常に一般的であるため、多くの電子書籍リーダーやソフトウェア アプリケーションでサポートされています. このファイル形式の詳細[ここ](https://wiki.fileformat.com/ebook/epub) |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | Ruby ERB スクリプト (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML (SpreadsheetML) は、Excel Binary File Format を表します。このようなファイルは、Microsoft Excel だけでなく、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムでも作成できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [FBX](../../groupdocs.viewer/filetype/fbx) | Autodesk FBX Interchange File (FilmBoX) (.fbx) は、3D モデル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/fbx). |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | フラット XML ODF テンプレート (.fodg) は、Apache OpenOffice の Draw アプリケーションで描画要素をベクター イメージとして保存するために使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/fodg) |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument プレゼンテーション (.fodp) は、OpenDocument フラット XML プレゼンテーションを表します。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/fodp) |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | OpenDocument フラット XML スプレッドシート (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | Graphical Interchange Format File (.gif) は、高度に圧縮されたイメージの一種です。各画像の GIF では通常、1 ピクセルあたり最大 8 ビットが許可され、画像全体で最大 256 色が許可されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/gif) |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | Groovy ソース コード ファイル (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu Zipped File (.gz) は、gzip 圧縮アプリケーションで作成された圧縮ファイルです。複数の圧縮ファイルを含めることができ、UNIX および Linux システムで一般的に使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/compression/gz) |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | Gnu Zipped File (.gzip) は、Unix システムで使用される Compress プログラムを置き換える無料のユーティリティとして導入されました。このようなファイルは、Windows と MacOS の両方で利用できる WinZip などのいくつかのアプリケーションで開いて抽出できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/compression/gz). |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C/C++/Objective-C ヘッダー ファイル (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | Haml ソース コード ファイル (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | C++ ヘッダー ファイル (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | ハイパーテキスト マークアップ言語ファイル (.htm) は、ブラウザーで表示するために作成された Web ページの拡張子です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/web/html) |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | ハイパーテキスト マークアップ言語ファイル (.html) は、ブラウザーで表示するために作成された Web ページの拡張子です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/web/html) |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | アイコン ファイル (.ico) は、Microsoft Windows でアプリケーションを表すアイコンとして使用される画像ファイル タイプです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/ico) |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | Industry Foundation Classes ファイル (.ifc) は、建物オブジェクトとそのプロパティをインポートおよびエクスポートするための国際標準を確立するファイル形式です。このファイル形式は、異なるソフトウェア アプリケーション間の相互運用性を提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/ifc). |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | Initial Graphics Exchange Specification (IGES) (.igs) |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | JPEG 2000 コード ストリーム (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000 コード ストリーム (.j2k) は、DCT 圧縮ではなくウェーブレット圧縮を使用して圧縮された画像です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/j2k) |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | Java ソース コード ファイル (.java) |
| static readonly [JLS](../../groupdocs.viewer/filetype/jls) | JPEG-LS (JLS) (.jls) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000 Core Image File (.jp2) は、画像コーディング システムであり、最先端の画像圧縮規格です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/jp2) |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | JPEG 2000 コード ストリーム (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | JPEG 画像 (.jpeg) は、非可逆圧縮方式を使用して保存される画像形式の一種です。圧縮の結果としての出力画像は、ストレージ サイズと画質のトレードオフになります。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/jpeg) |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | JPEG 2000 画像ファイル (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | JPEG 画像 (.jpg) は、非可逆圧縮方式を使用して保存される画像形式の一種です。圧縮の結果としての出力画像は、ストレージ サイズと画質のトレードオフになります。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/jpeg) |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | JPEG 2000 画像ファイル (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | JPEG 2000 画像ファイル (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | JavaScript ファイル (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | JavaScript オブジェクト表記ファイル (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | LESS スタイル シート (.less) |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | ログ ファイル (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | Objective-C 実装ファイル (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | Xcode Makefile スクリプト (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | 電子メール メールボックス ファイル (.mbox) このファイル形式の詳細[ここ](https://fileinfo.com/extension/mbox) |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | マークダウン ドキュメント ファイル (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | MHTML Web アーカイブ (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | MIME HTML ファイル (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | ML ソース コード ファイル (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | Objective-C++ ソース ファイル (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket eBook (.mobi) は、最も広く使用されている電子ブック ファイル形式の 1 つです。この形式は古い OEB (Open Ebook Format) 形式を拡張したもので、Mobipocket Reader の独自の形式として使用されていました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/ebook/mobi) |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | Microsoft Project ファイル (.mpp) は、プロジェクト管理に関連する情報を統合的に格納する Microsoft Project のデータ ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/project-management/mpp) |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft Project テンプレート (.mpt) には、基本的な情報と構造、および .MPP ファイルを作成するためのドキュメント設定が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/project-management/mpt) |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | Microsoft Project Exchange ファイル (.mpx) は、Microsoft Project (MSP) と、Primavera Project Planner、Sciforma、Timerline Precision Estimating などの MPX ファイル形式をサポートする他のアプリケーションとの間でプロジェクト情報を転送するための ASCII ファイル形式です。 詳しくはこちらこのファイル形式[ここ](https://wiki.fileformat.com/project-management/mpx) |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook メール メッセージ (.msg) は、電子メール メッセージ、連絡先、予定、またはその他のタスクを保存するために Microsoft Outlook および Exchange で使用されるファイル形式です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/msg) |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | Lotus Notes データベース (.nsf) このファイル形式の詳細[ここ](https://fileinfo.com/extension/nsf) |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple の数字は Excel のような Binary File Format を表します。このようなファイルは、Apple 番号アプリケーションで作成できます。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/numbers) |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D オブジェクト ファイル (.obj) は、Wavefront Technologies によって導入された 3D イメージ ファイルです このファイル形式の詳細[ここ](https://wiki.fileformat.com/3d/obj/). |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | OpenDocument グラフィック ファイル (.odg) は、Apache OpenOffice の Draw アプリケーションで描画要素をベクター イメージとして保存するために使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/odg) |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument プレゼンテーション (.odp) は、OASISOpen 標準で OpenOffice.org が使用するプレゼンテーション ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/odp) |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | OpenDocument スプレッドシート (.ods) は、ユーザーが編集できる OpenDocument スプレッドシート ドキュメント形式を表します。データは ODF ファイル内に行と列に保存されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument テキスト ドキュメント (.odt) は、OpenDocument テキスト ファイル形式に基づくワード プロセッシング アプリケーションで作成されたドキュメントのタイプです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/odt) |
| static readonly [ONE](../../groupdocs.viewer/filetype/one) | OneNote ドキュメント (.one) は、Microsoft OneNote アプリケーションによって作成されます。 OneNote を使用すると、下書き帳を使用してメモを取っているかのように、アプリケーションを使用して情報を収集できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/note-taking/one) |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | Outlook オフライン データ ファイル (.ost) は、Microsoft Outlook を使用して Exchange Server に登録したときに、ローカル マシン上のオフライン モードでのユーザーのメールボックス データを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/ost) |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | OpenDocument グラフィック テンプレート (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | OpenDocument プレゼンテーション テンプレート (.otp) は、OASIS OpenDocument 標準形式のアプリケーションによって作成されたプレゼンテーション テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/otp) |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | OpenDocument スプレッドシート テンプレート (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | OpenDocument ドキュメント テンプレート (.ott) は、OASIS の OpenDocument 標準形式に準拠したアプリケーションによって生成されたテンプレート ドキュメントを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/ott) |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | OpenXPS ファイル (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | プリンター コマンド言語ドキュメント (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | Portable Document Format File (.pdf) は、1990 年代に Adobe によって作成されたドキュメントの一種です。このファイル形式の目的は、ドキュメントやその他の参考資料を、アプリケーション ソフトウェア、ハードウェア、およびオペレーティング システムに依存しない形式で表現するための標準を導入することでした。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/view/pdf) |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | PHP ソース コード ファイル (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | Perl スクリプト (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT (HPGL) (.plt) は、Autodesk, Inc. によって導入されたベクトル ベースのプロッタ ファイルで、特定の CAD ファイルに関する情報が含まれています。詳細をプロットするには、製造時に正確さと精度が必要です。PLT ファイルを使用すると、すべての画像が点ではなく線を使用して印刷されるため、これが保証されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/plt). |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | Portable Network Graphic (.png) は、ロスレス圧縮を使用するラスター イメージ ファイル形式の一種です。このファイル形式は、Graphics Interchange Format (GIF) の代替として作成されたもので、著作権の制限はありません。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/png) |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | PowerPoint テンプレート (.pot) は、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pot) |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | PowerPoint Open XML マクロ対応プレゼンテーション テンプレート (.potm) は、マクロをサポートする Microsoft PowerPoint テンプレート ファイルです。 POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーション ファイルを作成するために使用できる既定の設定が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potm) |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML プレゼンテーション テンプレート (.potx) は、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーションを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potx) |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | PowerPoint スライド ショー (.pps) は、スライド ショー用に Microsoft PowerPoint を使用して作成されます。 PPS ファイルの読み取りと作成は、Microsoft PowerPoint 97-2003 でサポートされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pps) |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML マクロ有効スライド (.ppsm) は、Microsoft PowerPoint 2007 以降で作成されたマクロ有効スライド ショー ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | PowerPoint Open XML スライド ショー (.ppsx) ファイルは、スライド ショー用に Microsoft PowerPoint 2007 以降を使用して作成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint プレゼンテーション (.ppt) は、スライドショーとして表示するスライドのコレクションで構成される PowerPoint ファイルを表します。 Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppt) |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML マクロ有効プレゼンテーションは、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ有効プレゼンテーション ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML プレゼンテーション (.pptx) は、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。バイナリであった以前のバージョンのプレゼンテーション ファイル形式 PPT とは異なり、PPTX 形式は Microsoft PowerPoint オープン XML プレゼンテーション ファイル形式に基づいています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptx) |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | Java プロパティ ファイル (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | PostScript ファイル (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | PowerShell スクリプト ファイル (.ps1) Windows PowerShell コマンドレット ファイルのファイル形式。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/ps1) |
| static readonly [PSB](../../groupdocs.viewer/filetype/psb) | Photoshop ラージ ドキュメント フォーマット (.psb) は、グラフィックのデザインと開発に使用される Photoshop ラージ ドキュメント フォーマットを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/psb) |
| static readonly [PSD](../../groupdocs.viewer/filetype/psd) | Adobe Photoshop ドキュメント (.psd) は、グラフィックのデザインと開発に使用される Adobe Photoshop のネイティブ ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/psd) |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | PowerShell スクリプト モジュール マニフェスト (.psd1) PowerShell モジュール マニフェスト スクリプトのファイル形式。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/psd1) |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | PowerShell スクリプト モジュール (.psm1) PowerShell モジュール スクリプトのファイル形式。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/psm1) |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | Outlook パーソナル インフォメーション ストア ファイル (.pst) は、さまざまなユーザー情報を格納する Outlook パーソナル ストレージ ファイル (パーソナル ストレージ テーブルとも呼ばれます) を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/pst) |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | Python スクリプト (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive (.rar) は、RAR (WINRAR) 圧縮方式を使用して生成された圧縮ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/compression/rar) |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | Ruby ソースコード (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | reStructuredText ファイル (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | リッチ テキスト形式ファイル (.rtf) は、アプリケーション内で使用するために書式設定されたテキストとグラフィックスをエンコードする方法を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/rtf) |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | 構文的に優れた StyleSheets ファイル (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala ソース コード ファイル (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | スキーム ソース コード ファイル (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | 汎用スクリプト ファイル (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z、.7zip) は、LZMA および LZMA2 圧縮を備えた無料のオープン ソース アーカイバです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/7z/). |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash シェル スクリプト (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | 標準 ML ソース コード ファイル (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | 構造化照会言語データ ファイル (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | Stereolithography ファイル (.stl) は、3 次元の表面形状を表す交換可能なファイル形式です。このファイル形式は、ラピッド プロトタイピング、3D 印刷、コンピューター支援製造など、いくつかの分野で使用されています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/cad/stl). |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | スケーラブル ベクター グラフィックス ファイル (.svg) は、画像の外観を記述するために XML ベースのテキスト形式を使用するスカラー ベクター グラフィックス ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/svg) |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | スケーラブル ベクター グラフィックス ファイル (.svgz) は、XML ベースのテキスト形式を使用するスカラー ベクター グラフィックス ファイルで、画像の外観を記述するために GZIP で圧縮されています。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/svgz) |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | StarOffice Calc スプレッドシート (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | Consolidated Unix File Archive (.tar) は、1 つまたは複数のファイルを収集するための Unix ベースのユーティリティで作成されたアーカイブです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/compression/tar) |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | 統合 Unix ファイル アーカイブ (.tgz、.tar.gz) は、1 つまたは複数のファイルを収集するための Unix ベースのユーティリティで作成されたアーカイブです。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/tgz) |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | 統合 Unix ファイル アーカイブ (.txz、.tar.xz) は、1 つ以上のファイルを収集するための Unix ベースのユーティリティで作成されたアーカイブです。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/txz) |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | LaTeX ソース ドキュメント (.tex) は、ドキュメントのタイプセットに使用される、プログラミング機能とマークアップ機能で構成される言語です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/tex) |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) は、TRUEVISION によって開発されたビットマップ デジタル画像の保存に使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/tga) |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | 統合 Unix ファイル アーカイブ (.tgz、.tar.gz) は、1 つまたは複数のファイルを収集するための Unix ベースのユーティリティで作成されたアーカイブです。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/tgz) |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | タグ付きイメージ ファイル (.tif) は、このファイル形式標準に準拠するさまざまなデバイスで使用するためのラスター イメージを表します。 2 値、グレースケール、パレット カラー、フルカラーの画像データを複数の色空間で表現できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/tiff) |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | Tagged Image File Format (.tiff) は、このファイル形式標準に準拠するさまざまなデバイスで使用するためのラスター イメージを表します。 2 値、グレースケール、パレット カラー、フルカラーの画像データを複数の色空間で表現できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/tiff) |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | タブ区切り値ファイル (.tsv) は、プレーン テキスト形式のタブで区切られたデータを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/tsv) |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | プレーン テキスト ファイル (.txt) は、行形式のプレーン テキストを含むテキスト ドキュメントを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/word-processing/txt) |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | 統合 Unix ファイル アーカイブ (.txz、.tar.xz) は、1 つ以上のファイルを収集するための Unix ベースのユーティリティで作成されたアーカイブです。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/txz) |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | 不明なファイル タイプを表します。 |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | Visual Basic Project Item File (.vb) は、Microsoft が .NET アプリケーションの開発用に作成した Visual Basic 言語で作成されたソース コード ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/programming/vb) |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | vCard ファイル (.vcf) は、連絡先情報を保存するためのデジタル ファイル形式です。この形式は、一般的な情報交換アプリケーション間のデータ交換に広く使用されています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/email/vcf) |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | Visio Web 図面 (.vdw) は、Web 図面のレンダリングに必要なストリームとストレージを指定するファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/web/vdw). |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | Visio 図面 XML ファイル (.vdx) は、Microsoft Visio で作成された任意の図面またはグラフを表しますが、XML 形式で保存され、.VDX 拡張子が付きます。 Visio 図面 XML ファイルは、Microsoft が開発した Visio ソフトウェアで作成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vdx). |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | Vim 設定ファイル (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | Visio 図面ファイル (.vsd) は、Microsoft Visio アプリケーションで作成された図面で、さまざまなグラフィカル オブジェクトとこれらの間の相互接続を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vsd). |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | Visio マクロ対応図面 (.vsdm) は、マクロをサポートする Microsoft Visio アプリケーションで作成された図面ファイルです。 VSDM ファイルは、VSDX に似た OPC/XML 図面ですが、ファイルを開いたときにマクロを実行する機能も提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | Visio Drawing (.vsdx) は、Microsoft Office 2013 以降で導入された Microsoft Visio ファイル形式を表します。これは、以前のバージョンの Microsoft Visio でサポートされていたバイナリ ファイル形式 .VSD を置き換えるために開発されました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | Visio ステンシル ファイル (.vss) は、Microsoft Visio 2007 以前で作成されたステンシル ファイルです。ステンシル ファイルは、.VSD Visio 図面に含めることができる図面オブジェクトを提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vss). |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | Visio マクロ対応ステンシル ファイル (.vssm) は、マクロをサポートする Microsoft Visio ステンシル ファイルです。 VSSM ファイルを開くと、マクロを実行して、ダイアグラム内の図形の目的の書式設定と配置を実現できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | Visio ステンシル ファイル (.vssx) は、Microsoft Visio 2013 以降で作成された図面ステンシルです。 VSSX ファイル形式は、Visio 2013 以降で開くことができます。 Visio ファイルは、図形のコレクション、コネクタ、フローチャート、ネットワーク レイアウト、UML ダイアグラム、 など、さまざまな描画要素の表現で知られています。このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio Drawing Template (.vst) は、Microsoft Visio で作成されたベクター画像ファイルで、さらにファイルを作成するためのテンプレートとして機能します。これらのテンプレート ファイルはバイナリ ファイル形式であり、新しい Visio 図面の作成に使用される既定のレイアウトと設定が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vst). |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | Visio マクロ有効図面テンプレート (.vstm) は、マクロをサポートする Microsoft Visio で作成されたテンプレート ファイルです。 VSDX ファイルとは異なり、VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで開発されたマクロを実行できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | Visio Drawing Template (.vstx) は、Microsoft Visio 2013 以降で作成された図面テンプレート ファイルです。これらの VSTX ファイルは、既定のレイアウトと設定を使用して、.VSDX ファイルとして保存された Visio 図面を作成するための開始点を提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | Visio ステンシル XML ファイル (.vsx) は、Microsoft Visio で図を作成するために使用される図面と図形で構成されるステンシルを指します。 VSX ファイルは XML ファイル形式で保存され、Visio 2013 までサポートされていました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio テンプレート XML ファイル (.vtx) は、XML ファイル形式でディスクに保存される Microsoft Visio 図面テンプレートです。このテンプレートは、同じ設定の複数の Visio ファイルを作成するために使用できる基本設定を含むファイルを提供することを目的としています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/vtx). |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP 画像 (.webp) は、可逆圧縮と非可逆圧縮に基づく最新のラスター Web 画像ファイル形式です。画像サイズを大幅に縮小しながら、同じ画質を提供します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/webp) |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | Windows メタファイル (.wmf) は、ベクターおよびビットマップ形式の画像データを格納するための Microsoft Windows メタファイル (WMF) を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/image/wmf) |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | 圧縮 Windows メタファイル (.wmz) は、GZIP アーカイブで圧縮された Microsoft Windows メタファイル (WMF) を表し、ベクターおよびビットマップ形式の画像データを格納します。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/wmz#compressed_windows_metafile) |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | Microsoft Excel アドイン (.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | Excel スプレッドシート (.xls) は、Excel バイナリ ファイル形式を表します。このようなファイルは、Microsoft Excel だけでなく、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムでも作成できます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel バイナリ スプレッドシート (.xlsb) は、Excel ブックのコンテンツを指定するレコードと構造のコレクションである Excel バイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML マクロ対応スプレッドシート (.xlsm) は、マクロをサポートするスプレッドシート ファイルの一種です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML スプレッドシート (.xlsx) は、Microsoft Office 2007 のリリースで Microsoft によって導入された Microsoft Excel ドキュメントのよく知られた形式です。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel テンプレート (.xlt) は、Microsoft Office スイートの一部として提供されるスプレッドシート アプリケーションである Microsoft Excel で作成されたテンプレート ファイルです。 Microsoft Office 97-2003 では、新しい XLT ファイルの作成と開くことがサポートされていました。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel マクロ有効テンプレート (.xltm) は、Microsoft Excel によってマクロ有効テンプレート ファイルとして生成されるファイルを表します。 XLTM ファイルの構造は XLTX に似ていますが、XLTX はマクロを使用したテンプレート ファイルの作成をサポートしていません。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xltm) |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML スプレッドシート テンプレート (.xltx) は、Office OpenXML ファイル形式の仕様に基づく Microsoft Excel テンプレートを表します。 XLTX ファイルで指定されたものと同じ設定を示す XLSX ファイルを生成するために利用できる標準テンプレート ファイルを作成するために使用されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/spreadsheet/xltx) |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML ファイル (.xml) |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML Paper Specification File (.xps) は、Microsoft によって作成された XML Paper Specifications に基づくページ レイアウト ファイルを表します。この形式は、Microsoft が EMF ファイル形式の代替として開発したもので、PDF ファイル形式に似ていますが、ドキュメントのレイアウト、外観、および印刷情報に XML を使用します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/page-description-language/xps) |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ ファイル (.xz) は、LZMA アルゴリズムに基づく高比率圧縮アルゴリズムで圧縮されたアーカイブです。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/xz) |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | YAML ドキュメント (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | 圧縮ファイル (.zip) は、1 つ以上のファイルまたはディレクトリを保持できるアーカイブを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/compression/zip) |

### 関連項目

* 名前空間 [GroupDocs.Viewer](../../groupdocs.viewer)
* 組み立て [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
