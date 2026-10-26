---
title: "FileType"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ファイルタイプを表します。"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

ファイルタイプを表します。GroupDocs.Viewer コンポーネントがサポートするすべてのファイルタイプの一覧を取得するメソッドを提供します。

FileType 列挙型は、GroupDocs.Viewer コンポーネントがサポートするさまざまなファイルタイプを表す定数を提供します。この列挙型のメソッドを使用して、サポートされているすべてのファイルタイプの一覧を取得したり、特定のファイルタイプがサポートされているかどうかを確認したりできます。

使用例:

```

 // Try to detect file type using stream
 final FileType fileTypeFromStream = FileType.fromStream(new FileInputStream("document.pdf"));
 // Detect file type by extension
 final FileType fileTypeFromExtension = FileType.fromExtension(".png");
 // Iterate all supported file types
 for (FileType supportedFileType : FileType.getSupportedFileTypes()) {
     System.out.println("File type: " + supportedFileType);
 }
 final LoadOptions loadOptions = new LoadOptions(fileTypeFromExtension);
 // Usage of loadOptions
 
```
## フィールド

| フィールド | 説明 |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | 不明なファイルタイプを表します。 |
| [ZIP](#ZIP) | .zip ファイル（1 つ以上のファイルまたはディレクトリを格納できる）を表します。 |
| [TAR](#TAR) | .tar アーカイブ（1 つ以上のファイルをまとめて収集するために作成された統合 Unix ファイルアーカイブ）を表します。 |
| [XZ](#XZ) | .xz ファイル（LZMA アルゴリズムに基づく高圧縮率アルゴリズムで圧縮された XZ ファイル）を表します。 |
| [TXZ](#TXZ) | .txz、.tar.xz アーカイブ（1 つ以上のファイルをまとめて収集するために作成された統合 Unix ファイルアーカイブ）を表します。 |
| [TARXZ](#TARXZ) | .txz、.tar.xz アーカイブ（1 つ以上のファイルをまとめて収集するために作成された統合 Unix ファイルアーカイブ）を表します。 |
| [TGZ](#TGZ) | .tgz、.tar.gz アーカイブ（1 つ以上のファイルをまとめて収集するために作成された統合 Unix ファイルアーカイブ）を表します。 |
| [TARGZ](#TARGZ) | .tgz、.tar.gz アーカイブ（1 つ以上のファイルをまとめて収集するために作成された統合 Unix ファイルアーカイブ）を表します。 |
| [BZ_2](#BZ-2) | .bz2 ファイル（BZIP2 オープンソース圧縮方式で生成された Bzip2 圧縮ファイル）を表します。 |
| [RAR](#RAR) | .rar ファイル（RAR（WINRAR バージョン 4）圧縮方式で生成された Roshal アーカイブ）を表します。 |
| [GZ](#GZ) | .gz ファイル（gzip 圧縮アプリケーションで作成された Gnu Zipped File）を表します。 |
| [GZIP](#GZIP) | Unixシステムで使用されていた Compress プログラムの代替として導入されたフリーユーティリティによる Gnu Zipped File (.gzip) 圧縮ファイルを表します。 |
| [SEVEN_ZIP](#SEVEN-ZIP) | LZMA と LZMA2 圧縮を備えたフリーのオープンソースアーカイバである 7Zip (.7z, .7zip) ファイルを表します。 |
| [CPIO](#CPIO) | Cpio は汎用のファイルアーカイバユーティリティおよびそれに関連するファイル形式です。 |
| [ZSTANDARD](#ZSTANDARD) | ZST ファイルは Zstandard (zstd) 圧縮アルゴリズムで生成された圧縮ファイルです。 |
| [TZST](#TZST) | TZST ファイル (.tar.zst, .tzst) は Zstandard アーカイブ (ZST) で、内部に Unix ベースのユーティリティで作成された Consolidated Unix File Archive (Tar) を含み、1 つまたは複数のファイルを収集します。 |
| [TAR_ZST](#TAR-ZST) | TZST ファイル (.tar.zst, .tzst) は Zstandard アーカイブ (ZST) で、内部に Unix ベースのユーティリティで作成された Consolidated Unix File Archive (Tar) を含み、1 つまたは複数のファイルを収集します。 |
| [ISO](#ISO) | ISO 光学ディスクイメージは、CD や DVD などの光学ディスク上の全データ内容を表す、ISO-9660 標準に基づく非圧縮アーカイブディスクイメージファイルです。 |
| [LHA](#LHA) | LHA または LZH はフリーウェアの圧縮ユーティリティおよび関連ファイル形式です。 |
| [CAB](#CAB) | Cabinet (または CAB) は Microsoft Windows 用のアーカイブファイル形式です。 |
| [DXF](#DXF) | Drawing Exchange Format File (.dxf) は、AutoCAD 図面ファイルのタグ付けデータ表現を表します。 |
| [DWG](#DWG) | AutoCAD Drawing Database File (.dwg) は、2D および 3D 設計データを格納するための独自のバイナリファイルを表します。 |
| [DWT](#DWT) | AutoCAD Drawing Template (.dwt) は、DWG ファイルとして保存できる図面を作成するための開始テンプレートとして使用される AutoCAD 図面テンプレートファイルを表します。 |
| [STL](#STL) | Stereolithography File (.stl) は、3 次元表面ジオメトリを表す交換可能なファイル形式です。 |
| [IFC](#IFC) | Industry Foundation Classes File (.ifc) は、建築オブジェクトとそのプロパティのインポートおよびエクスポートのための国際標準を確立するファイル形式です。 |
| [DWF](#DWF) | Design Web Format File (.dwf) は、2D/3D 図面の閲覧、レビュー、印刷のための圧縮ファイル形式です。 |
| [FBX](#FBX) | Autodesk FBX Interchange File (FilmBoX) (.fbx) は、3D モデル形式です。 |
| [DWFX](#DWFX) | Design Web Format File XPS (.dwfx) は、2D/3D 図面を XPS ドキュメントとして閲覧、レビュー、印刷するための圧縮形式です。 |
| [DGN](#DGN) | MicroStation Design File (.dgn) は、MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成・サポートされる図面です。 |
| [PLT](#PLT) | PLT (HPGL) File (.plt) は、Autodesk, Inc. が導入したベクトルベースのプロッタファイルです。 |
| [CF2](#CF2) | Common File Format File (.cf2) を表します。 |
| [OBJ](#OBJ) | Wavefront 3D Object File (.obj) は、Wavefront Technologies が導入した 3D 画像ファイルです。 |
| [HPG](#HPG) | PLT (HPGL) File (.hpg) を表します。 |
| [IGS](#IGS) | Initial Graphics Exchange Specification (IGES) File (.igs) を表します。 |
| [VSD](#VSD) | Visio Drawing File (.vsd) は、Microsoft Visio アプリケーションで作成され、さまざまなグラフィックオブジェクトとその相互接続を表す図面です。 |
| [VSDX](#VSDX) | Visio Drawing File (.vsdx) は、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式を表します。 |
| [VSS](#VSS) | Visio Stencil File (.vss) は、Microsoft Visio 2007 以前で作成されたステンシルファイルです。 |
| [VSSX](#VSSX) | Visio ステンシル ファイル (.vssx) は、Microsoft Visio 2013 以降で作成された描画ステンシルを表します。 |
| [VSDM](#VSDM) | Visio マクロ対応描画 (.vsdm) は、マクロをサポートする Microsoft Visio アプリケーションで作成された描画ファイルを表します。 |
| [VST](#VST) | Visio 描画テンプレート (.vst) は、Microsoft Visio で作成されたベクター画像ファイルを表します。 |
| [VSTX](#VSTX) | Visio 描画テンプレート (.vstx) は、Microsoft Visio 2013 以降で作成された描画テンプレートファイルを表します。 |
| [VSTM](#VSTM) | Visio マクロ対応描画テンプレート (.vstm) は、マクロをサポートする Microsoft Visio で作成されたテンプレートファイルを表します。 |
| [VSSM](#VSSM) | Visio マクロ対応ステンシル ファイル (.vssm) は、マクロをサポートする Microsoft Visio ステンシル ファイルを表します。 |
| [VSX](#VSX) | Visio ステンシル XML ファイル (.vsx) は、Microsoft Visio で作成された図形や描画を含むステンシルを指します。 |
| [VTX](#VTX) | Visio テンプレート XML ファイル (.vtx) は、XML ファイル形式でディスクに保存された Microsoft Visio の描画テンプレートを表します。 |
| [VDW](#VDW) | Visio Web 描画 (.vdw) は、Web 描画のレンダリングに必要なストリームとストレージを指定します。 |
| [VDX](#VDX) | Visio 描画 XML ファイル (.vdx) は、Microsoft Visio で作成された任意の描画やチャートを .VDX 拡張子の XML 形式で保存したものを表します。 |
| [EPUB](#EPUB) | Open eBook ファイル (.epub) は、出版社と読者向けに標準的なデジタル出版形式を提供する電子書籍ファイル形式です。 |
| [MOBI](#MOBI) | Mobipocket 電子書籍 (.mobi) は、最も広く使用されている電子書籍ファイル形式の一つです。 |
| [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) 電子書籍は、Amazon Kindle デバイス向けに開発されたデジタルファイル形式です。 |
| [MSG](#MSG) | Outlook メール メッセージ (.msg) は、Microsoft Outlook および Exchange がメール、連絡先、予定、タスクなどを保存するために使用するファイル形式です。 |
| [EML](#EML) | E‑Mail メッセージ (.eml) は、Outlook やその他の関連アプリケーションで保存されたメールメッセージを表します。 |
| [EMLX](#EMLX) | Apple Mail メッセージ (.emlx) は、Apple によって実装・開発された形式です。 |
| [PST](#PST) | Outlook 個人情報ストア ファイル (.pst) は、Outlook の個人用ストレージ ファイル（Personal Storage Table）で、さまざまなユーザー情報を保存します。 |
| [OST](#OST) | Outlook オフライン データ ファイル (.ost) は、Microsoft Outlook を使用して Exchange Server に登録した際に、ローカルマシン上でオフラインモードのメールボックス データを表します。 |
| [TIF](#TIF) | Tagged Image File (.tif) は、このファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。 |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) は、このファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。 |
| [JPG](#JPG) | JPEG 画像 (.jpg) は、非可逆圧縮方式で保存される画像形式の一種です。 |
| [JPEG](#JPEG) | JPEG 画像 (.jpeg) は、非可逆圧縮方式で保存される画像形式の一種です。 |
| [JFIF](#JFIF) | JPEG File Interchange Format (.jfif) は、プラットフォーム間の高速な画像交換のために開発された画像です。 |
| [PNG](#PNG) | Portable Network Graphic (.png) は、可逆圧縮を使用するラスタ画像ファイル形式の一種です。 |
| [GIF](#GIF) | Graphical Interchange Format File (.gif) は、非常に高圧縮された画像の一種です。 |
| [APNG](#APNG) | Animated Portable Network Graphic (.apng) を表します。これは、アニメーションをサポートする PNG 形式の拡張です。 |
| [BMP](#BMP) | Bitmap Image File (.bmp) を表します。これは、ビットマップデジタル画像を保存するために使用されます。 |
| [ICO](#ICO) | Icon File (.ico) を表します。これは、Microsoft Windows 上でアプリケーションのアイコンとして使用される画像ファイルタイプです。 |
| [TGA](#TGA) | Truevision TGA (TARGA) ファイルを表します。これは、TRUEVISION が開発したビットマップデジタル画像を保存するために使用されます。 |
| [JP_2](#JP-2) | JPEG 2000 Core Image File (.jp2) を表します。これは、画像符号化システムであり、最先端の画像圧縮標準です。 |
| [JPF](#JPF) | JPEG 2000 Image File (.jpf) を表します。 |
| [JPX](#JPX) | JPEG 2000 Image File (.jpx) を表します。 |
| [JPM](#JPM) | JPEG 2000 Image File (.jpm) を表します。 |
| [J2C](#J2C) | JPEG 2000 Code InputStream (.j2c) を表します。 |
| [J2K](#J2K) | JPEG 2000 Code Stream (.j2k) を表します。これは、DCT 圧縮ではなくウェーブレット圧縮を使用して圧縮された画像です。 |
| [JPC](#JPC) | JPEG 2000 Code Stream (.jpc) を表します。 |
| [JLS](#JLS) | JPEG-LS (JLS) ファイル (.jls) を表します。 |
| [DIB](#DIB) | Device Independent Bitmap File (.dib) を表します。 |
| [WMF](#WMF) | Windows Metafile (.wmf) を表します。これは、ベクターおよびビットマップ形式の画像データを保存するための Microsoft Windows Metafile (WMF) です。 |
| [WMZ](#WMZ) | Compressed Windows Metafile (.wmz) を表します。これは、ベクターおよびビットマップ形式の画像データを保存するために GZIP アーカイブで圧縮された Microsoft Windows Metafile (WMF) です。 |
| [EMF](#EMF) | Enhanced Windows Metafile (.emf) を表します。これは、デバイスに依存しない形でグラフィック画像を表します。 |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) を表します。これは、GZIP によって圧縮されたデバイスに依存しないグラフィック画像です。 |
| [WEBP](#WEBP) | WebP Image (.webp) を表します。これは、ロスレスおよびロッシー圧縮に基づく最新のラスタウェブ画像ファイル形式です。 |
| [DNG](#DNG) | Digital Negative Specification (.dng) を表します。これは、RAW ファイルの保存に使用されるデジタルカメラ画像形式です。 |
| [CDR](#CDR) | CorelDraw Vector Graphic Drawing (.cdr) を表します。これは、CorelDRAW でネイティブに作成され、デジタルでエンコードおよび圧縮された画像を保存するためのベクタードローイング画像ファイルです。 |
| [CMX](#CMX) | Corel Exchange (.cmx) を表します。これは、ベクターグラフィックとビットマップグラフィックの両方を含む可能性がある描画画像ファイルです。 |
| [DJVU](#DJVU) | DjVu Image (.djvu) を表します。これは、テキスト、図面、画像、写真の組み合わせを含むスキャン文書や書籍向けに設計されたグラフィックファイル形式です。 |
| [CGM](#CGM) | Computer Graphics Metafile (.cgm) を表します。これは、ベクターグラフィック（2D）、ラスタグラフィック、テキストを保存および交換するための無料でプラットフォームに依存しない国際標準メタファイル形式です。 |
| [PCL](#PCL) | Printer Command Language Document (.pcl) を表します。 |
| [PSD](#PSD) | Adobe Photoshop Document (.psd) を表します。これは、Adobe Photoshop のグラフィック設計および開発に使用されるネイティブファイル形式です。 |
| [PSB](#PSB) | Photoshop Large Document Format（.psb）を表し、Adobe Photoshop でのグラフィック設計および開発に使用されます。 |
| [DCM](#DCM) | DICOM 画像（.dcm）を表し、MRI、CT スキャン、超音波画像など、患者の医療情報を保存するデジタル画像を示します。 |
| [PS](#PS) | PostScript ファイル（.ps）を表します。 |
| [EPS](#EPS) | Encapsulated PostScript ファイル（.eps）を表し、単一ページの外観を定義する Encapsulated PostScript 言語プログラムを記述します。 |
| [ODG](#ODG) | OpenDocument グラフィック ファイル（.odg）を表し、Apache OpenOffice の Draw アプリケーションでベクター画像として描画要素を保存するために使用されます。 |
| [FODG](#FODG) | Flat XML ODF テンプレート（.fodg）を表し、Apache OpenOffice の Draw アプリケーションでベクター画像として描画要素を保存するために使用されます。 |
| [SVG](#SVG) | Scalable Vector Graphics ファイル（.svg）を表し、画像の外観を記述するために XML ベースのテキスト形式を使用するベクターグラフィックスファイルです。 |
| [SVGZ](#SVGZ) | 圧縮 Scalable Vector Graphics ファイル（.svgz）を表し、XML ベースのテキスト形式を使用し、GZIP で圧縮されたベクターグラフィックスファイルで、画像の外観を記述します。 |
| [OTG](#OTG) | OpenDocument グラフィック テンプレート（.otg）を表します。 |
| [HTM](#HTM) | Hypertext Markup Language ファイル（.htm）を表し、ブラウザで表示するために作成されたウェブページの拡張子です。 |
| [HTML](#HTML) | Hypertext Markup Language ファイル（.html）を表し、ブラウザで表示するために作成されたウェブページの拡張子です。 |
| [MHT](#MHT) | MHTML Web アーカイブ（.mht）を表します。 |
| [NSF](#NSF) | Lotus Notes データベース（.nsf）を表します。 |
| [MBOX](#MBOX) | メールボックス ファイル（.mbox）を表します。 |
| [MHTML](#MHTML) | MIME HTML ファイル（.mhtml）を表します。 |
| [XML](#XML) | XML ファイル（.xml）を表します。 |
| [ONE](#ONE) | Microsoft OneNote アプリケーションで作成された OneNote ドキュメント（.one）を表します。 |
| [PDF](#PDF) | Portable Document Format ファイル（.pdf）を表し、1990 年代に Adobe が作成した文書タイプです。 |
| [XPS](#XPS) | XML Paper Specification ファイル（.xps）を表し、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを示します。 |
| [OXPS](#OXPS) | OpenXPS ファイル（.oxps）を表します。 |
| [TEX](#TEX) | LaTeX ソースドキュメント（.tex）を表し、文書の組版に使用されるプログラミング機能とマークアップ機能を備えた言語です。 |
| [PPT](#PPT) | PowerPoint プレゼンテーション（.ppt）を表し、スライドショーとして表示するスライドのコレクションで構成された PowerPoint ファイルを示します。 |
| [PPTX](#PPTX) | PowerPoint Open XML プレゼンテーション（.pptx）を表し、人気のある Microsoft PowerPoint アプリケーションで作成されたプレゼンテーションファイルです。 |
| [PPS](#PPS) | PowerPoint スライドショー（.pps）を表し、Microsoft PowerPoint を使用してスライドショー目的で作成されたものです。 |
| [PPSX](#PPSX) | PowerPoint Open XML スライドショー（.ppsx）ファイルを表し、Microsoft PowerPoint 2007 以降でスライドショー目的に作成されたものです。 |
| [ODP](#ODP) | OpenDocument Presentation (.odp) を表し、OpenOffice.org が OASISOpen 標準で使用するプレゼンテーション ファイル形式を表します。 |
| [FODP](#FODP) | OpenDocument Presentation (.fodp) を表し、OpenDocument Flat XML Presentation を表します。 |
| [POT](#POT) | PowerPoint テンプレート (.pot) を表し、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。 |
| [PPTM](#PPTM) | PowerPoint Open XML マクロ有効プレゼンテーション (.pptm) を表し、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ有効プレゼンテーション ファイルです。 |
| [POTX](#POTX) | PowerPoint Open XML プレゼンテーション テンプレート (.potx) を表し、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーション を表します。 |
| [POTM](#POTM) | PowerPoint Open XML マクロ有効プレゼンテーション テンプレート (.potm) を表し、マクロに対応した Microsoft PowerPoint テンプレート ファイルです。 |
| [PPSM](#PPSM) | PowerPoint Open XML マクロ有効スライド (.ppsm) を表し、Microsoft PowerPoint 2007 以降で作成されたマクロ有効スライドショー ファイル形式を表します。 |
| [OTP](#OTP) | OpenDocument プレゼンテーション テンプレート (.otp) を表し、OASIS OpenDocument 標準形式のアプリケーションで作成されたプレゼンテーション テンプレート ファイルを表します。 |
| [XLS](#XLS) | Excel スプレッドシート (.xls) を表し、Excel バイナリ ファイル形式を表します。 |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Excel 2003 XML (SpreadsheetML) (.xml) を表し、Excel バイナリ ファイル形式を表します。 |
| [NUMBERS](#NUMBERS) | Apple Numbers (.numbers) を表し、Excel に似たバイナリ ファイル形式を表します。 |
| [XLSX](#XLSX) | Microsoft Excel Open XML スプレッドシート (.xlsx) を表し、Microsoft Office 2007 のリリースとともに Microsoft が導入した、Microsoft Excel ドキュメントのよく知られた形式です。 |
| [XLSM](#XLSM) | Excel Open XML マクロ有効スプレッドシート (.xlsm) を表し、マクロをサポートするスプレッドシート ファイルの一種です。 |
| [XLSB](#XLSB) | Excel バイナリ スプレッドシート (.xlsb) を表し、Excel バイナリ ファイル形式を指定します。 |
| [CSV](#CSV) | カンマ区切り値ファイル (.csv) を表し、カンマで区切られた値を含むデータレコードのプレーンテキスト ファイルを表します。 |
| [TSV](#TSV) | タブ区切り値ファイル (.tsv) を表し、タブで区切られたデータをプレーンテキスト形式で表します。 |
| [ODS](#ODS) | OpenDocument スプレッドシート (.ods) を表し、ユーザーが編集可能な OpenDocument スプレッドシート ドキュメント形式を指します。 |
| [FODS](#FODS) | OpenDocument Flat XML スプレッドシート (.fods) を表します。 |
| [OTS](#OTS) | OpenDocument スプレッドシート テンプレート (.ots) を表します。 |
| [XLAM](#XLAM) | Microsoft Excel アドイン (.xlam) を表します。 |
| [XLTM](#XLTM) | Microsoft Excel マクロ有効テンプレート (.xltm) を表し、Microsoft Excel がマクロ有効テンプレート ファイルとして生成するファイルを表します。 |
| [XLT](#XLT) | Microsoft Excel テンプレート (.xlt) を表し、Microsoft Office スイートの一部として提供されるスプレッドシート アプリケーション Microsoft Excel で作成されたテンプレート ファイルです。 |
| [XLTX](#XLTX) | Excel Open XML スプレッドシート テンプレート (.xltx) を表し、Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレート を表します。 |
| [SXC](#SXC) | StarOffice Calc スプレッドシート (.sxc) を表します。 |
| [MPP](#MPP) | Microsoft Project ファイル (.mpp) を表し、プロジェクト管理に関する情報を統合的に保存する Microsoft Project データ ファイルです。 |
| [MPT](#MPT) | Microsoft Project テンプレート (.mpt) を表し、.MPP ファイルを作成するための基本情報と構造、およびドキュメント設定を含みます。 |
| [MPX](#MPX) | Microsoft Project Exchange ファイル (.mpx) を表し、これは Microsoft Project (MSP) と MPX ファイル形式をサポートする他のアプリケーション（Primavera Project Planner、Sciforma、Timerline Precision Estimating など）間でプロジェクト情報を転送するための ASCII ファイル形式です。 |
| [AS](#AS) | ActionScript ファイル (.as) を表します。 |
| [AS_3](#AS-3) | ActionScript ファイル (.as3) を表します。 |
| [ASM](#ASM) | アセンブリ言語ソースコードファイル (.asm) を表します。 |
| [BAT](#BAT) | DOS バッチファイル (.bat) を表します。 |
| [C](#C) | C/C++ ソースコードファイル (.c) を表します。 |
| [CC](#CC) | C++ ソースコードファイル (.cc) を表します。 |
| [CMAKE](#CMAKE) | CMake ファイル (.cmake) を表します。 |
| [CPP](#CPP) | C++ ソースコードファイル (.cpp) を表します。 |
| [CS](#CS) | C\# ソースコードファイル (.cs) を表し、これは C\# プログラミング言語用のソースコードファイルです。 |
| [VB](#VB) | Visual Basic プロジェクト アイテム ファイル (.vb) を表し、これは Visual Basic 言語で作成されたソースコードファイルです。 |
| [CSS](#CSS) | Cascading Style Sheet (.css) ファイルを表します。 |
| [CXX](#CXX) | C++ ソースコードファイル (.cxx) を表します。 |
| [DIFF](#DIFF) | パッチファイル (.diff) を表します。 |
| [ERB](#ERB) | Ruby ERB スクリプト (.erb) を表します。 |
| [GROOVY](#GROOVY) | Groovy ソースコードファイル (.groovy) を表します。 |
| [H](#H) | C/C++/Objective-C ヘッダーファイル (.h) を表します。 |
| [HAML](#HAML) | Haml ソースコードファイル (.haml) を表します。 |
| [HH](#HH) | C++ ヘッダーファイル (.hh) を表します。 |
| [JAVA](#JAVA) | Java ソースコードファイル (.java) を表します。 |
| [JS](#JS) | JavaScript ファイル (.js) を表します。 |
| [JSON](#JSON) | JavaScript Object Notation ファイル (.json) を表します。 |
| [LESS](#LESS) | LESS スタイルシート (.less) ファイルを表します。 |
| [LOG](#LOG) | ログファイル (.log) を表します。 |
| [M](#M) | Objective-C 実装ファイル (.m) を表します。 |
| [MAKE](#MAKE) | Xcode Makefile スクリプト (.make) を表します。 |
| [MD](#MD) | Markdown ドキュメントファイル (.md) を表します。 |
| [ML](#ML) | ML ソースコードファイル (.ml) を表します。 |
| [MM](#MM) | Objective-C++ ソースファイル (.mm) を表します。 |
| [PHP](#PHP) | PHP ソースコードファイル (.php) を表します。 |
| [PL](#PL) | Perl スクリプト (.pl) を表します。 |
| [PROPERTIES](#PROPERTIES) | Java プロパティファイル (.properties) を表します。 |
| [PY](#PY) | Python スクリプト (.py) を表します。 |
| [RB](#RB) | Ruby ソースコード (.rb) ファイルを表します。 |
| [RST](#RST) | reStructuredText ファイル (.rst) を表します。 |
| [SASS](#SASS) | Syntactically Awesome StyleSheets ファイル (.sass) を表します。 |
| [SCALA](#SCALA) | Scala ソースコードファイル (.scala) を表します。 |
| [SCM](#SCM) | Scheme ソースコードファイル (.scm) を表します。 |
| [SCRIPT](#SCRIPT) | 汎用スクリプトファイル (.script) を表します。 |
| [SH](#SH) | Bash シェルスクリプト (.sh) を表します。 |
| [SML](#SML) | Standard ML ソースコードファイル (.sml) を表します。 |
| [SQL](#SQL) | SQL データファイル (.sql) を表します。 |
| [VIM](#VIM) | Vim 設定ファイル (.vim) を表します。 |
| [YAML](#YAML) | YAML ドキュメント (.yaml) を表します。 |
| [DOC](#DOC) | Microsoft Word ドキュメント (.doc) ファイルを表します。 |
| [DOCX](#DOCX) | Microsoft Word Open XML ドキュメント (.docx) ファイルを表します。 |
| [CHM](#CHM) | Microsoft Compiled HTML Help ファイル (.chm) を表します。 |
| [DOCM](#DOCM) | Word Open XML マクロ有効ドキュメント (.docm) ファイルを表します。 |
| [DOT](#DOT) | Word ドキュメントテンプレート (.dot) ファイルを表します。 |
| [DOTX](#DOTX) | Word Open XML ドキュメントテンプレート (.dotx) ファイルを表します。 |
| [DOTM](#DOTM) | Word Open XML マクロ有効ドキュメントテンプレート (.dotm) ファイルを表します。 |
| [RTF](#RTF) | リッチテキスト形式ファイル (.rtf) を表します。 |
| [TXT](#TXT) | プレーンテキストファイル (.txt) を表します。 |
| [ODT](#ODT) | OpenDocument テキストドキュメント (.odt) を表します。 |
| [OTT](#OTT) | OpenDocument ドキュメントテンプレート (.ott) を表します。 |
| [VCF](#VCF) | vCard ファイル (.vcf) を表します。これは連絡先情報を保存するためのデジタルファイル形式です。 |
| [AI](#AI) | Adobe Illustrator ファイル (.ai) を表します。これは Adobe Illustrator の図面用ファイル形式です。 |
| [PSM1](#PSM1) | PowerShell スクリプトモジュールファイル (.psm1) を表します。 |
| [PS1](#PS1) | PowerShell スクリプトファイル (.ps1) を表します。 |
| [PSD1](#PSD1) | PowerShell スクリプトモジュールマニフェストファイル (.psd1) を表します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | ファイル拡張子をファイルタイプにマップします。 |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | ファイル名またはファイルパスから拡張子を抽出し、ファイルタイプにマップします。 |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | ファイルのメディアタイプをファイルタイプにマップします。 |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | サポートされているファイルタイプを取得します。 |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | パスに基づいてテキスト [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV), および [CSV](../../com.groupdocs.viewer/filetype\#CSV) ファイルの文字セットを検出しようとします。 |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | ストリームに基づいてテキスト [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV), および [CSV](../../com.groupdocs.viewer/filetype\#CSV) ファイルの文字セットを検出しようとします。 |
| [getFileFormat()](#getFileFormat--) | ファイル形式の名前を取得します（例: "Microsoft Word Document"）。 |
| [getExtension()](#getExtension--) | ファイル拡張子サフィックス（ピリオド「.」を含む）を取得します（例: ".doc"）。 |
| [toString()](#toString--) | 現在のオブジェクトの文字列表現を返します。 |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


不明なファイルタイプを表します。

### ZIP {#ZIP}
```
public static final FileType ZIP
```


圧縮ファイル (.zip) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


1 つ以上のファイルを収集するために作成された統合 Unix ファイルアーカイブ (.tar) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


LZMA アルゴリズムに基づく高圧縮率アルゴリズムで圧縮された XZ ファイル (.xz) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


1 つ以上のファイルを収集するために作成された統合 Unix ファイルアーカイブ (.txz, .tar.xz) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


1 つ以上のファイルを収集するために作成された統合 Unix ファイルアーカイブ (.txz, .tar.xz) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


1 つ以上のファイルを収集するために作成された統合 Unix ファイルアーカイブ (.tgz, .tar.gz) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


1 つ以上のファイルを収集するために作成された統合 Unix ファイルアーカイブ (.tgz, .tar.gz) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


BZIP2 オープンソース圧縮方式を使用して生成された Bzip2 圧縮ファイル (.bz2) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


RAR (WINRAR バージョン 4) 圧縮方式を使用して生成された Roshal Archive (.rar) 圧縮ファイルを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


gzip 圧縮アプリケーションで作成された Gnu Zipped File (.gz) 圧縮ファイルを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Unix システムで使用されていた Compress プログラムの代替として導入されたフリーユーティリティによる Gnu Zipped File (.gzip) 圧縮ファイルを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


LZMA および LZMA2 圧縮を備えたフリーのオープンソースアーカイバである 7Zip (.7z, .7zip) ファイルを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio は一般的なファイルアーカイバユーティリティおよびそれに関連するファイル形式です。主に Unix 系 OS にインストールされています。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST ファイルは Zstandard (zstd) 圧縮アルゴリズムで生成された圧縮ファイルです。アルゴリズムによるロスレス圧縮で作成された圧縮ファイルであり、データベース、ファイルシステム、ネットワーク、ゲームなどさまざまな種類のファイルを圧縮するために使用できます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


TZST ファイル (.tar.zst, .tzst) は Zstandard アーカイブ (ZST) で、内部に Unix ベースのユーティリティで作成された Consolidated Unix File Archive (Tar) を含み、1 つまたは複数のファイルを収集します。

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST ファイル (.tar.zst, .tzst) は Zstandard アーカイブ (ZST) で、内部に Unix ベースのユーティリティで作成された Consolidated Unix File Archive (Tar) を含み、1 つまたは複数のファイルを収集します。

### ISO {#ISO}
```
public static final FileType ISO
```


ISO 光ディスクイメージは、CD や DVD などの光学ディスク上の全データ内容を表す、ISO-9660 標準に基づく非圧縮アーカイブディスクイメージファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA または LZH はフリーウェアの圧縮ユーティリティおよび関連するファイル形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (または CAB) は Microsoft Windows 用のアーカイブファイル形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD 図面ファイルのタグ付きデータ表現である Drawing Exchange Format File (.dxf) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


2D および 3D 設計データを格納するために使用される独自のバイナリファイルである AutoCAD Drawing Database File (.dwg) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


DWG ファイルとして保存できる図面作成の出発点として使用される AutoCAD Drawing Template (.dwt) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


3 次元表面ジオメトリを表す交換可能なファイル形式である Stereolithography File (.stl) を表します。高速プロトタイピング、3D プリント、コンピュータ支援製造で一般的に使用されます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


建築オブジェクトとそのプロパティのインポート/エクスポートの国際標準を確立するファイル形式である Industry Foundation Classes File (.ifc) を表します。異なるソフトウェア間の相互運用性を可能にします。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


2D/3D 図面の閲覧、レビュー、印刷のための圧縮ファイル形式である Design Web Format File (.dwf) を表します。デザインデータの一部としてグラフィックとテキストを含み、圧縮によりファイルサイズが削減されます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


3D モデル形式である Autodesk FBX Interchange File (FilmBoX) (.fbx) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


2D/3D 図面を XPS ドキュメントとして閲覧、レビュー、印刷するための圧縮形式である Design Web Format File XPS (.dwfx) を表します。デザインデータの一部としてグラフィックとテキストを含み、圧縮によりファイルサイズが削減されます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成・サポートされる図面である MicroStation Design File (.dgn) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Autodesk, Inc. が導入したベクターベースのプロッタファイルである PLT (HPGL) File (.plt) を表します。特定の CAD ファイルの情報を含み、すべての画像がドットではなく線で印刷されるため、生産時の精度と正確性が確保されます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Common File Format File (.cf2) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Wavefront Technologies が導入した 3D 画像ファイルである Wavefront 3D Object File (.obj) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


HP Graphics Language (HPGL) で使用されるプロッタファイル用のファイル形式である PLT (HPGL) File (.hpg) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Initial Graphics Exchange Specification (IGES) File (.igs) を表します。

### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio アプリケーションで作成され、さまざまなグラフィックオブジェクトとその相互接続を表す図面である Visio Drawing File (.vsd) を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式である Visio Drawing File (.vsdx) を表します。以前のバージョンでサポートされていたバイナリ形式 (.VSD) に取って代わりました。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Visio ステンシル ファイル (.vss) を表します。これは Microsoft Visio 2007 以前で作成されたステンシル ファイルです。ステンシル ファイルは .VSD Visio 図面に含めることができる描画オブジェクトを提供します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio ステンシル ファイル (.vssx) を表します。これは Microsoft Visio 2013 以降で作成された描画ステンシルです。VSSX ファイル形式は Visio 2013 以降で開くことができます。Visio ファイルは、図形、コネクタ、フローチャート、ネットワークレイアウト、UML 図など、さまざまな描画要素を表すことで知られています。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio マクロ有効図面 (.vsdm) を表します。これはマクロをサポートする Microsoft Visio アプリケーションで作成された描画ファイルです。VSDM ファイルは VSDX に似た OPC/XML 図面で、ファイルを開く際にマクロを実行できる機能も提供します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Visio 図面テンプレート (.vst) を表します。これは Microsoft Visio で作成されたベクター画像ファイルです。新しいファイルを作成するためのテンプレートとして機能し、新しい Visio 図面の作成に使用されるデフォルトのレイアウトと設定を含みます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio 図面テンプレート (.vstx) を表します。これは Microsoft Visio 2013 以降で作成された描画テンプレート ファイルです。これらの VSTX ファイルは、デフォルトのレイアウトと設定を備えた .VSDX ファイルとして保存される Visio 図面を作成するための出発点を提供します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio マクロ有効図面テンプレート (.vstm) を表します。これはマクロをサポートする Microsoft Visio で作成されたテンプレート ファイルです。VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで開発されたマクロを実行できます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio マクロ有効ステンシル ファイル (.vssm) を表します。これはマクロをサポートする Microsoft Visio ステンシル ファイルです。VSSM ファイルを開くと、マクロを実行して図中の図形の書式設定や配置を行うことができます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio ステンシル XML ファイル (.vsx) を表します。これは Microsoft Visio で図表作成に使用される描画や図形からなるステンシルを指します。VSX ファイルは XML 形式で保存され、Visio 2013 までサポートされていました。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio テンプレート XML ファイル (.vtx) を表します。これは Microsoft Visio の図面テンプレートが XML 形式でディスクに保存されたものです。このテンプレートは同じ設定で複数の Visio ファイルを作成するための基本設定を提供します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Visio Web 図面 (.vdw) を表します。これは Web 図面のレンダリングに必要なストリームとストレージを指定します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Visio 図面 XML ファイル (.vdx) を表します。これは Microsoft Visio で作成された任意の図面やチャートを .VDX 拡張子の XML 形式で保存したものです。Visio 図面 XML ファイルは Microsoft が開発した Visio ソフトウェアで作成されます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook ファイル (.epub) を表します。これは出版社と読者向けに標準的なデジタル出版形式を提供する e ブック ファイル形式です。この形式は多くの電子書籍リーダーやソフトウェアでサポートされています。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket eBook (.mobi) を表します。これは最も広く使用されている e ブック ファイル形式の一つです。この形式は古い OEB (Open Ebook Format) の拡張版で、Mobipocket Reader の独自形式として使用されていました。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) eBook は Amazon Kindle デバイス向けに開発されたデジタルファイル形式です。この形式は従来の AZW ファイルの拡張版で、Kindle Fire デバイスでのみ使用され、先行するファイル形式である MOBI と AZW との下位互換性を持ちます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Outlook メール メッセージ (.msg) を表します。これは Microsoft Outlook と Exchange がメール メッセージ、連絡先、予定、その他のタスクを保存するために使用するファイル形式です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


E-Mail メッセージ (.eml) を表します。これは Outlook やその他の関連アプリケーションで保存されたメール メッセージを指します。RFC-822 インターネット メッセージ形式標準に準拠しているため、ほぼすべてのメールクライアントがこのファイル形式をサポートしています。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail メッセージ (.emlx) を表します。これは Apple が実装・開発したものです。Apple Mail アプリケーションはメールのエクスポートに EMLX ファイル形式を使用します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Outlook 個人情報ストア ファイル (.pst) を表します。これは Outlook の個人用ストレージ ファイル（Personal Storage Table とも呼ばれる）で、さまざまなユーザー情報を保存します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Outlook オフライン データ ファイル (.ost) を表します。これは Microsoft Outlook を使用して Exchange Server に登録した際に、ローカルマシン上でオフラインモードのユーザーのメールボックス データを表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


タグ付き画像ファイル (.tif) を表します。これはこのファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。二値、グレースケール、パレットカラー、フルカラーの画像データを複数の色空間で記述できます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


タグ付き画像ファイル形式 (.tiff) を表します。これはこのファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。二値、グレースケール、パレットカラー、フルカラーの画像データを複数の色空間で記述できます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG 画像 (.jpg) を表します。これは非可逆圧縮方式で保存される画像形式の一種です。圧縮の結果として得られる出力画像は、保存サイズと画像品質のトレードオフとなります。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG 画像 (.jpeg) を表します。これは、非可逆圧縮方式で保存される画像フォーマットの一種です。圧縮の結果として得られる出力画像は、保存サイズと画像品質のトレードオフとなります。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG ファイル交換フォーマット (.jfif) は、プラットフォーム間の高速な交換を目的として開発された画像です。このフォーマットは JPEG 圧縮を使用します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) を表します。これは、可逆圧縮を使用するラスタ画像ファイルフォーマットの一種です。このフォーマットは Graphics Interchange Format (GIF) の代替として作成され、著作権制限がありません。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Graphical Interchange Format ファイル (.gif) を表します。これは高度に圧縮された画像の一種です。GIF は通常、1 ピクセルあたり最大 8 ビット、画像全体で最大 256 色をサポートします。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Animated Portable Network Graphic (.apng) を表します。これは PNG フォーマットの拡張で、アニメーションをサポートします。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp) を表します。これはビットマップデジタル画像を保存するために使用されます。これらの画像はグラフィックアダプタに依存せず、デバイス非依存ビットマップ (DIB) ファイルフォーマットとも呼ばれます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Icon File (.ico) を表します。これは Microsoft Windows 上でアプリケーションを表すアイコンとして使用される画像ファイルタイプです。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Truevision TGA (TARGA) ファイルを表します。これは TRUEVISION によって開発されたビットマップデジタル画像の保存に使用されます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


JPEG 2000 Core Image File (.jp2) を表します。これは画像符号化システムであり、最先端の画像圧縮標準です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


JPEG 2000 Image File (.jpf) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


JPEG 2000 Image File (.jpx) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


JPEG 2000 Image File (.jpm) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


JPEG 2000 Code InputStream (.j2c) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


JPEG 2000 Code Stream (.j2k) を表します。これは DCT 圧縮ではなくウェーブレット圧縮を使用して圧縮された画像です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


JPEG 2000 Code Stream (.jpc) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


JPEG-LS (JLS) ファイル (.jls) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Device Independent Bitmap File (.dib) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Windows Metafile (.wmf) を表します。これはベクターおよびビットマップ形式の画像データを保存するための Microsoft Windows Metafile (WMF) です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Compressed Windows Metafile (.wmz) を表します。これはベクターおよびビットマップ形式の画像データを保存するために GZIP アーカイブで圧縮された Microsoft Windows Metafile (WMF) です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Enhanced Windows Metafile (.emf) を表します。これはデバイスに依存しない形でグラフィック画像を表現します。EMF のメタファイルは可変長レコードを時系列で構成しており、任意の出力デバイスで解析後に保存された画像を描画できます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows Compressed Enhanced Metafile (.emz) を表します。これは GZIP で圧縮されたデバイス非依存のグラフィック画像を表します。EMF のメタファイルは可変長レコードを時系列で構成しており、任意の出力デバイスで解析後に保存された画像を描画できます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


WebP Image (.webp) を表します。これは可逆圧縮と非可逆圧縮の両方に基づく最新のラスタウェブ画像ファイルフォーマットです。同等の画像品質を保ちつつ、画像サイズを大幅に削減します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Digital Negative Specification (.dng) を表します。これは RAW ファイルの保存に使用されるデジタルカメラ画像フォーマットです。2004 年 9 月に Adobe によって開発され、主にデジタル写真撮影で使用されます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


CorelDraw Vector Graphic Drawing (.cdr) を表します。これは CorelDRAW でネイティブに作成され、デジタルでエンコードおよび圧縮された画像を保存するベクタードローイング画像ファイルです。CDR ドローイングファイルはテキスト、線、形状、画像、色、エフェクトを含み、画像内容をベクトルで表現します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Corel Exchange (.cmx) を表します。これはベクターグラフィックとビットマップグラフィックの両方を含む可能性のあるドローイング画像ファイルです。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


DjVu 画像 (.djvu) を表します。これは、テキスト、図面、画像、写真を組み合わせたスキャン文書や書籍向けに設計されたグラフィックファイル形式です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Computer Graphics Metafile (.cgm) を表します。これは、ベクタ画像（2D）、ラスタ画像、テキストを保存・交換するための、無料でプラットフォームに依存しない国際標準メタファイル形式です。CGM はオブジェクト指向アプローチを採用し、画像生成のための多くの機能を提供します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Printer Command Language Document (.pcl) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Adobe Photoshop Document (.psd) を表します。これは、Adobe Photoshop のグラフィック設計・開発に使用されるネイティブファイル形式です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Photoshop Large Document Format (.psb) を表します。これは、Adobe Photoshop におけるグラフィック設計・開発に使用される形式です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


DICOM Image (.dcm) を表します。これは、MRI、CT スキャン、超音波画像など、患者の医療情報を保存するデジタル画像です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


PostScript File (.ps) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Encapsulated PostScript File (.eps) を表します。これは、単一ページの外観を定義する Encapsulated PostScript 言語プログラムを記述したものです。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


OpenDocument Graphic File (.odg) を表します。これは、Apache OpenOffice の Draw アプリケーションでベクタ画像として描画要素を保存するために使用されます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Flat XML ODF Template (.fodg) を表します。これは、Apache OpenOffice の Draw アプリケーションでベクタ画像として描画要素を保存するために使用されます。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Scalable Vector Graphics File (.svg) を表します。これは、画像の外観を記述するために XML ベースのテキスト形式を使用するスケーラブルベクタ画像ファイルです。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Compressed Scalable Vector Graphics File (.svgz) を表します。これは、XML ベースのテキスト形式で記述されたスケーラブルベクタ画像ファイルを GZIP で圧縮したものです。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


OpenDocument Graphic Template (.otg) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Hypertext Markup Language File (.htm) を表します。これは、ブラウザで表示するために作成されたウェブページの拡張子です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) を表します。これは、ブラウザで表示するために作成されたウェブページの拡張子です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Lotus Notes Database (.nsf) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Email Mailbox File (.mbox) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


XML File (.xml) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote Document (.one) を表します。これは、Microsoft OneNote アプリケーションで作成されたドキュメントです。OneNote は、下書きノートを取るかのように情報を収集できるアプリケーションです。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format File (.pdf) を表します。これは、1990 年代に Adobe が作成した文書タイプです。このファイル形式の目的は、アプリケーションソフトウェア、ハードウェア、OS に依存しない形式で文書や参照資料を表現する標準を導入することでした。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification File (.xps) を表します。これは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルです。この形式は Microsoft によって EMF ファイル形式の代替として開発され、PDF に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


OpenXPS File (.oxps) を表します。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Source Document (.tex) を表します。これは、文書の組版に使用されるプログラミング機能とマークアップ機能を備えた言語です。このファイル形式の詳細は[here][]でご覧ください。


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint プレゼンテーション (.ppt) を表し、スライドショーとして表示するためのスライドのコレクションで構成された PowerPoint ファイルを示します。Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定しています。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML プレゼンテーション (.pptx) を表し、Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。従来のバイナリ形式 PPT とは異なり、PPTX 形式は Microsoft PowerPoint Open XML プレゼンテーション ファイル形式に基づいています。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint スライドショー (.pps) を表し、Microsoft PowerPoint を使用してスライドショー目的で作成されたファイルです。PPS ファイルの読み取りおよび作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML スライドショー (.ppsx) ファイルを表し、Microsoft PowerPoint 2007 以降でスライドショー目的に作成されたものです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument プレゼンテーション (.odp) を表し、OpenOffice.org が OASIS Open 標準で使用するプレゼンテーション ファイル形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


OpenDocument プレゼンテーション (.fodp) を表し、OpenDocument フラット XML プレゼンテーションです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


PowerPoint テンプレート (.pot) を表し、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


PowerPoint Open XML マクロ有効プレゼンテーション (.pptm) を表し、Microsoft PowerPoint 2007 以降で作成されたマクロ有効プレゼンテーション ファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


PowerPoint Open XML プレゼンテーション テンプレート (.potx) を表し、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーションです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


PowerPoint Open XML マクロ有効プレゼンテーション テンプレート (.potm) を表し、マクロをサポートする Microsoft PowerPoint テンプレート ファイルです。POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーション ファイルを作成するための既定設定を含みます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


PowerPoint Open XML マクロ有効スライド (.ppsm) を表し、Microsoft PowerPoint 2007 以降で作成されたマクロ有効スライドショー ファイル形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument プレゼンテーション テンプレート (.otp) を表し、OASIS OpenDocument 標準形式のアプリケーションで作成されたプレゼンテーション テンプレート ファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel スプレッドシート (.xls) を表し、Excel バイナリ ファイル形式です。このようなファイルは Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシート プログラムでも作成できます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Excel 2003 XML (SpreadsheetML) (.xml) を表し、Excel バイナリ ファイル形式です。このようなファイルは Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシート プログラムでも作成できます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Apple Numbers (.numbers) を表し、Excel に似たバイナリ ファイル形式です。このようなファイルは Apple Numbers アプリケーションで作成できます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML スプレッドシート (.xlsx) を表し、Microsoft Office 2007 のリリース時に Microsoft が導入した、Microsoft Excel ドキュメントの広く知られた形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML マクロ有効スプレッドシート (.xlsm) を表し、マクロをサポートするスプレッドシート ファイルの一種です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel バイナリ スプレッドシート (.xlsb) を表し、Excel バイナリ ファイル形式を指定しています。これは、Excel ブックの内容を示すレコードと構造のコレクションです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


カンマ区切り値ファイル (.csv) を表し、カンマで区切られた値のレコードを含むプレーンテキスト ファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


タブ区切り値ファイル (.tsv) を表し、タブで区切られたデータを含むプレーンテキスト形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument スプレッドシート (.ods) を表し、ユーザーが編集可能な OpenDocument スプレッドシート ドキュメント形式です。データは ODF ファイル内の行と列に格納されます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


OpenDocument フラット XML スプレッドシート (.fods) を表し、OpenOffice と LibreOffice が使用する XML ベースのスプレッドシート ドキュメント形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


OpenDocument スプレッドシート テンプレート (.ots) を表し、OpenOffice と LibreOffice がスプレッドシート用に使用するテンプレート ドキュメント形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Microsoft Excel アドイン (.xlam) を表し、Microsoft Excel がカスタム機能を持つアドインを作成するために使用するファイル形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel マクロ有効テンプレート (.xltm) を表し、Microsoft Excel がマクロ有効テンプレート ファイルとして生成するファイルです。XLTM ファイルは構造が XLTX と似ていますが、後者はマクロ付きテンプレートの作成をサポートしません。このファイル形式の詳細は [here][] で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel テンプレート (.xlt) を表します。これは、Microsoft Office スイートの一部として提供されるスプレッドシートアプリケーション Microsoft Excel で作成されたテンプレート ファイルです。Microsoft Office 97-2003 は新しい XLT ファイルの作成と開くことをサポートしていました。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML スプレッドシートテンプレート (.xltx) を表します。これは、Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレートです。XLTX ファイルで指定された同じ設定を使用して XLSX ファイルを生成できる標準テンプレート ファイルの作成に使用されます。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


StarOffice Calc スプレッドシート (.sxc) を表します。これは、スプレッドシート プログラムである StarOffice Calc で作成されたスプレッドシート ドキュメントです。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Microsoft Project ファイル (.mpp) を表します。これは、プロジェクト管理に関する情報を統合的に保存する Microsoft Project データ ファイルです。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Microsoft Project テンプレート (.mpt) を表します。これは、.MPP ファイルを作成するための基本情報と構造、およびドキュメント設定を含んでいます。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Microsoft Project Exchange ファイル (.mpx) を表します。これは、Microsoft Project (MSP) と、Primavera Project Planner、Sciforma、Timerline Precision Estimating など MPX ファイル形式をサポートする他のアプリケーション間でプロジェクト情報を転送するための ASCII ファイル形式です。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


ActionScript ファイル (.as) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


ActionScript ファイル (.as3) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


アセンブリ言語ソースコード ファイル (.asm) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


DOS バッチ ファイル (.bat) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


C/C++ ソースコード ファイル (.c) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


C++ ソースコード ファイル (.cc) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


CMake ファイル (.cmake) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


C++ ソースコード ファイル (.cpp) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


C\# ソースコード ファイル (.cs) を表します。これは C\# プログラミング言語用のソースコード ファイルです。Microsoft が .NET Framework で使用するために導入しました。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Visual Basic プロジェクト アイテム ファイル (.vb) を表します。これは Visual Basic 言語で作成されたソースコード ファイルです。Microsoft が .NET アプリケーションの開発用に作成しました。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Cascading Style Sheet (.css) ファイルを表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


C++ ソースコード ファイル (.cxx) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


パッチ ファイル (.diff) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Ruby ERB スクリプト (.erb) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy ソースコード ファイル (.groovy) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


C/C++/Objective-C ヘッダー ファイル (.h) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Haml ソースコード ファイル (.haml) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


C++ ヘッダー ファイル (.hh) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java ソースコード ファイル (.java) を表します。このファイル形式の詳細は[here][]で確認してください。


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


JavaScript ファイル (.js) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


JavaScript Object Notation ファイル (.json) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


LESS スタイルシート (.less) ファイルを表します。このファイル形式の詳細は[こちら][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


ログ ファイル (.log) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Objective-C 実装ファイル (.m) を表します。このファイル形式の詳細は[こちら][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Xcode Makefile スクリプト (.make) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Markdown ドキュメンテーション ファイル (.md) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


ML ソースコード ファイル (.ml) を表します。このファイル形式の詳細は[こちら][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Objective-C++ ソースファイル (.mm) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


PHP ソースコード ファイル (.php) を表します。このファイル形式の詳細は[こちら][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Perl スクリプト (.pl) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Java プロパティ ファイル (.properties) を表します。このファイル形式の詳細は[こちら][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Python スクリプト (.py) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Ruby ソースコード (.rb) ファイルを表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


reStructuredText ファイル (.rst) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Syntactically Awesome StyleSheets ファイル (.sass) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala ソースコード ファイル (.scala) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Scheme ソースコード ファイル (.scm) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


汎用スクリプト ファイル (.script) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Bash シェルスクリプト (.sh) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Standard ML ソースコード ファイル (.sml) を表します。このファイル形式の詳細は[こちら][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


構造化問い合わせ言語 データファイル (.sql) を表します。このファイル形式の詳細は[こちら][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Vim 設定ファイル (.vim) を表します。このファイル形式の詳細は[こちら][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


YAML ドキュメント (.yaml) を表します。このファイル形式の詳細は[こちら][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word ドキュメント (.doc) ファイルを表します。このファイル形式の詳細は[こちら][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML ドキュメント (.docx) ファイルを表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Microsoft Compiled HTML Help ファイル (.chm) を表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML マクロ有効ドキュメント (.docm) ファイルを表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word ドキュメントテンプレート (.dot) ファイルを表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML ドキュメントテンプレート (.dotx) ファイルを表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML マクロ有効ドキュメントテンプレート (.dotm) ファイルを表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


リッチテキスト形式ファイル (.rtf) を表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


プレーンテキストファイル (.txt) を表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument テキストドキュメント (.odt) を表します。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument ドキュメントテンプレート (.ott) を表します。これは OASIS の OpenDocument 標準フォーマットに準拠して生成されたテンプレートドキュメントです。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


vCard ファイル (.vcf) を表します。これは連絡先情報を保存するためのデジタルファイル形式です。人気のある情報交換アプリケーション間でのデータ交換に広く使用されています。このファイル形式の詳細は [here][] で確認できます。


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Adobe Illustrator ファイル (.ai) を表します。これは Adobe Illustrator の図面用ファイル形式です。このファイル形式の詳細は [here][] で確認できます。


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


PowerShell スクリプトモジュールファイル (.psm1) を表します。これは PowerShell モジュールスクリプト用のファイル形式です。このファイル形式の詳細は [here][] で確認できます。


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


PowerShell スクリプトファイル (.ps1) を表します。これは Windows PowerShell Cmdlet ファイル用のファイル形式です。このファイル形式の詳細は [here][] で確認できます。


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


PowerShell スクリプトモジュールマニフェストファイル (.psd1) を表します。これは PowerShell モジュールマニフェストスクリプト用のファイル形式です。このファイル形式の詳細は [here][] で確認できます。


[here]: https://fileinfo.com/extension/psd1

### values() {#values--}
```
public static FileType[] values()
```




**Returns:**
com.groupdocs.viewer.FileType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static FileType valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


ファイル拡張子をファイルタイプにマップします。

このメソッドは、ピリオド「.」の有無にかかわらずファイル拡張子を受け取り、サポートされている場合は対応するファイルタイプを返します。サポートされていない場合は、デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) ファイルタイプを返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| extension | java.lang.String | ピリオド「.」の有無にかかわらずのファイル拡張子。 |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


ファイル名またはファイルパスから拡張子を抽出し、ファイルタイプにマップします。

ファイルタイプがサポートされている場合、メソッドは対応する FileType を返し、そうでない場合はデフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) ファイルタイプを返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ファイル名またはファイルパス。 |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


ファイルメディアタイプをファイルタイプにマッピングします。たとえば、'application/pdf' は [PDF](../../com.groupdocs.viewer/filetype\#PDF) にマッピングされます。

このメソッドは、ファイルメディアタイプを入力として受け取り、対応する FileType にマッピングします。メディアタイプがサポートされている場合、メソッドは対応するファイルタイプを返します。サポートされていない場合は、デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) ファイルタイプを返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mediaType | java.lang.String | ファイルメディアタイプ、例: 'application/pdf'。 |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


ファイルシグネチャを読み取ってファイルタイプを検出します。

このメソッドは、ファイルを表す入力ストリームを受け取り、ファイルシグネチャを解析してファイルタイプを検出しようとします。ファイルシグネチャは、ファイルの先頭にある固有のバイト列で、ファイルタイプを示します。メソッドは入力ストリームからファイルシグネチャを読み取り、サポートされているファイルタイプの既知のシグネチャと照合します。一致が見つかった場合、メソッドは対応するファイルタイプを返します。一致が見つからない場合、デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) ファイルタイプを返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ファイルを表す入力ストリームです。 |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


ファイルシグネチャを読み取ってファイルタイプを検出します。

このメソッドは、ファイルの先頭にあるユニークなバイト列であるファイルシグネチャを解析し、ファイルタイプを判定します。提供された入力ストリームからファイルシグネチャを読み取り、サポートされているファイルタイプの既知のシグネチャと照合します。マッチが見つかった場合、対応するファイルタイプを返します。マッチが見つからない場合、デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) ファイルタイプを返します。

ファイルが暗号化されていて開くのにパスワードが必要な場合は、パスワードをこのメソッドのパラメータとして提供してください。パスワードはファイルの復号化に使用され、シグネチャを解析してファイルタイプを判定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ファイルを表す入力ストリームです。 |
| パスワード | java.lang.String | ファイルを開くためのパスワードです。 |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


ファイルシグネチャを読み取ってファイルタイプを検出します。

このメソッドは、ファイルの先頭にあるユニークなバイト列であるファイルシグネチャを解析し、ファイルタイプを判定します。提供された入力ストリームからファイルシグネチャを読み取り、サポートされているファイルタイプの既知のシグネチャと照合します。マッチが見つかった場合、対応するファイルタイプを返します。マッチが見つからない場合、デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) ファイルタイプを返します。

ファイルタイプ検出プロセス中の関連情報やエラーを記録するためにロガーを提供できます。ロガーは ILogger インターフェイスを実装する必要があります。ロガーが提供されない場合、検出プロセスはログ出力を行いません。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ファイルを表す入力ストリームです。 |
| ロガー | com.groupdocs.foundation.logging.ILogger | 情報やエラーを記録するためのロガーです。 |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


ファイルシグネチャを読み取ってファイルタイプを検出します。

このメソッドは、ファイルの先頭にあるユニークなバイト列であるファイルシグネチャを解析し、ファイルタイプを判定します。提供された入力ストリームからファイルシグネチャを読み取り、サポートされているファイルタイプの既知のシグネチャと照合します。マッチが見つかった場合、対応するファイルタイプを返します。マッチが見つからない場合、デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) ファイルタイプを返します。

ファイルが暗号化または保護されている場合、パスワードを提供できます。パスワードはファイルシグネチャを解析する前にファイルを開くために使用されます。ファイルがパスワードを必要としない場合、このパラメータは null に設定できます。

ファイルタイプ検出プロセス中の関連情報やエラーを記録するためにロガーを提供できます。ロガーは ILogger インターフェイスを実装する必要があります。ロガーが提供されない場合、検出プロセスはログ出力を行いません。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ファイルを表す入力ストリームです。 |
| パスワード | java.lang.String | ファイルを開くためのパスワードです。 |
| ロガー | com.groupdocs.foundation.logging.ILogger | 情報やエラーを記録するためのロガーです。 |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


サポートされているファイルタイプを取得します。

このメソッドは、システムがサポートするすべてのファイルタイプのシーケンスを返します。ファイルタイプは、システムで処理または認識できるさまざまなドキュメント形式を表します。

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - サポートされているファイルタイプのシーケンスです。
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


パスに基づいてテキスト [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV), および [CSV](../../com.groupdocs.viewer/filetype\#CSV) ファイルの文字セットを検出しようとします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | ファイル名またはファイルパス。 |

**Returns:**
java.nio.charset.Charset - 文字セット、またはファイルの文字セット検出に失敗した場合は null です。

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


ストリームに基づいてテキスト [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV), および [CSV](../../com.groupdocs.viewer/filetype\#CSV) ファイルの文字セットを検出しようとします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ファイルストリームです。 |

**Returns:**
java.nio.charset.Charset - 文字セット、またはファイルの文字セット検出に失敗した場合は null です。

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


ファイル形式の名前を取得します（例: "Microsoft Word Document"）。

**Returns:**
java.lang.String - ファイル形式の名前です。
### getExtension() {#getExtension--}
```
public final String getExtension()
```


ファイル拡張子サフィックス（ピリオド「.」を含む）を取得します（例: ".doc"）。

**Returns:**
java.lang.String - ファイル拡張子のサフィックスです。
### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトの文字列表現を返します。

**Returns:**
java.lang.String - 現在のオブジェクトの文字列表現。
