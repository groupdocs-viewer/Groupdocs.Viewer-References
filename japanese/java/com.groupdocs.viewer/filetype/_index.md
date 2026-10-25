---
title: "FileType"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "ファイルタイプを表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

ファイルタイプを表します。GroupDocs.Viewer コンポーネントがサポートするすべてのファイルタイプの一覧を取得するメソッドを提供します。


FileType 列挙型は、GroupDocs.Viewer コンポーネントがサポートするさまざまなファイルタイプを表す定数を提供します。
この列挙型のメソッドを使用して、サポートされているすべてのファイルタイプの一覧を取得したり、特定のファイルタイプがサポートされているか確認したりできます。


使用例:

````

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
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | 不明なファイルタイプを表します。 |
|
|  | [ZIP](#ZIP) | 複数のファイルまたはディレクトリを格納できる圧縮ファイル (.zip) を表します。 |
|
|  | [TAR](#TAR) | 複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.tar) を表します。 |
|
|  | [XZ](#XZ) | LZMA アルゴリズムに基づく高圧縮率アルゴリズムで圧縮された XZ ファイル (.xz) を表します。 |
|
|  | [TXZ](#TXZ) | 複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.txz、.tar.xz) を表します。 |
|
|  | [TARXZ](#TARXZ) | 複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.txz、.tar.xz) を表します。 |
|
|  | [TGZ](#TGZ) | 複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.tgz、.tar.gz) を表します。 |
|
|  | [TARGZ](#TARGZ) | 複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.tgz、.tar.gz) を表します。 |
|
|  | [BZ_2](#BZ-2) | BZIP2 オープンソース圧縮方式で生成された Bzip2 圧縮ファイル (.bz2) を表します。 |
|
|  | [RAR](#RAR) | RAR (WINRAR バージョン 4) 圧縮方式で生成された Roshal アーカイブ (.rar) 圧縮ファイルを表します。 |
|
|  | [GZ](#GZ) | gzip 圧縮アプリケーションで作成された Gnu 圧縮ファイル (.gz) を表します。 |
|
|  | [GZIP](#GZIP) | Unix システムで使用される Compress プログラムの代替として導入された無料ユーティリティで作成された Gnu 圧縮ファイル (.gzip) を表します。 |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | LZMA および LZMA2 圧縮を備えた無料のオープンソースアーカイバである 7Zip (.7z、.7zip) ファイルを表します。 |
|
|  | [CPIO](#CPIO) | Cpio は一般的なファイルアーカイバユーティリティおよびそれに関連するファイル形式です。 |
|
|  | [ZSTANDARD](#ZSTANDARD) | ZST ファイルは Zstandard (zstd) 圧縮アルゴリズムで生成される圧縮ファイルです。 |
|
|  | [TZST](#TZST) | TZST ファイル（.tar.zst、.tzst）は Zstandard アーカイブ（ZST）であり、内部には Unix ベースのユーティリティで作成された Consolidated Unix File Archive（Tar）が含まれ、1 つまたは複数のファイルを収集します。 |
|
|  | [TAR_ZST](#TAR-ZST) | TZST ファイル（.tar.zst、.tzst）は Zstandard アーカイブ（ZST）であり、内部には Unix ベースのユーティリティで作成された Consolidated Unix File Archive（Tar）が含まれ、1 つまたは複数のファイルを収集します。 |
|
|  | [ISO](#ISO) | ISO 光学ディスクイメージは、CD や DVD などの光学ディスク上の全データの内容を表す、ISO-9660 標準に基づく非圧縮アーカイブディスクイメージファイルです。 |
|
|  | [LHA](#LHA) | LHA または LZH はフリーウェアの圧縮ユーティリティおよびそれに関連するファイル形式です。 |
|
|  | [CAB](#CAB) | Cabinet（または CAB）は Microsoft Windows 用のアーカイブファイル形式です。 |
|
|  | [DXF](#DXF) | Drawing Exchange Format ファイル（.dxf）を表し、これは AutoCAD 図面ファイルのタグ付きデータ表現です。 |
|
|  | [DWG](#DWG) | AutoCAD Drawing Database ファイル（.dwg）を表し、2D および 3D 設計データを格納するために使用される独自のバイナリファイルです。 |
|
|  | [DWT](#DWT) | AutoCAD Drawing Template（.dwt）を表し、DWG ファイルとして保存できる図面を作成するための開始テンプレートとして使用される AutoCAD 図面テンプレートファイルです。 |
|
|  | [STL](#STL) | Stereolithography ファイル（.stl）を表し、3 次元表面ジオメトリを表す交換可能なファイル形式です。 |
|
|  | [IFC](#IFC) | Industry Foundation Classes ファイル（.ifc）を表し、建築オブジェクトとそのプロパティのインポートおよびエクスポートのための国際標準を確立するファイル形式です。 |
|
|  | [DWF](#DWF) | Design Web Format ファイル（.dwf）を表し、2D/3D 図面の閲覧、レビュー、印刷のための圧縮ファイル形式です。 |
|
|  | [FBX](#FBX) | Autodesk FBX Interchange ファイル（FilmBoX）（.fbx）を表し、3D モデル形式です。 |
|
|  | [DWFX](#DWFX) | Design Web Format File XPS（.dwfx）を表し、2D/3D 図面を XPS ドキュメントとして閲覧、レビュー、印刷するための圧縮形式です。 |
|
|  | [DGN](#DGN) | MicroStation Design ファイル（.dgn）を表し、MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成・サポートされる図面です。 |
|
|  | [PLT](#PLT) | PLT（HPGL）ファイル（.plt）を表し、Autodesk, Inc. が導入したベクターベースのプロッタファイルです。 |
|
|  | [CF2](#CF2) | Common File Format ファイル（.cf2）を表します。 |
|
|  | [OBJ](#OBJ) | Wavefront 3D Object ファイル（.obj）を表し、Wavefront Technologies が導入した 3D 画像ファイルです。 |
|
|  | [HPG](#HPG) | PLT（HPGL）ファイル（.hpg）を表します。 |
|
|  | [IGS](#IGS) | Initial Graphics Exchange Specification（IGES）ファイル（.igs）を表します。 |
|
|  | [VSD](#VSD) | Visio Drawing ファイル（.vsd）を表し、Microsoft Visio アプリケーションで作成され、さまざまなグラフィックオブジェクトとその相互接続を表す図面です。 |
|
|  | [VSDX](#VSDX) | Visio Drawing ファイル（.vsdx）を表し、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式です。 |
|
|  | [VSS](#VSS) | Visio Stencil ファイル（.vss）を表し、Microsoft Visio 2007 以前で作成されたステンシルファイルです。 |
|
|  | [VSSX](#VSSX) | Visio Stencil ファイル（.vssx）を表し、Microsoft Visio 2013 以降で作成された描画ステンシルです。 |
|
|  | [VSDM](#VSDM) | Visio Macro-Enabled Drawing（.vsdm）を表し、マクロをサポートする Microsoft Visio アプリケーションで作成された図面ファイルです。 |
|
|  | [VST](#VST) | Visio Drawing Template (.vst) は、Microsoft Visio で作成されたベクター画像ファイルを表します。 |
|
|  | [VSTX](#VSTX) | Visio Drawing Template (.vstx) は、Microsoft Visio 2013 以降で作成された図面テンプレートファイルを表します。 |
|
|  | [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) は、マクロに対応した Microsoft Visio で作成されたテンプレートファイルを表します。 |
|
|  | [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) は、マクロに対応した Microsoft Visio のステンシルファイルを表します。 |
|
|  | [VSX](#VSX) | Visio Stencil XML File (.vsx) は、Microsoft Visio で図表作成に使用される図面やシェイプからなるステンシルを指します。 |
|
|  | [VTX](#VTX) | Visio Template XML File (.vtx) は、XML ファイル形式でディスクに保存された Microsoft Visio の図面テンプレートを表します。 |
|
|  | [VDW](#VDW) | Visio Web Drawing (.vdw) は、Web 図面のレンダリングに必要なストリームとストレージを指定します。 |
|
|  | [VDX](#VDX) | Visio Drawing XML File (.vdx) は、Microsoft Visio で作成された任意の図面やチャートを、.VDX 拡張子の XML 形式で保存したものを表します。 |
|
|  | [EPUB](#EPUB) | Open eBook File (.epub) は、出版社と読者向けに標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式を表します。 |
|
|  | [MOBI](#MOBI) | Mobipocket eBook (.mobi) は、最も広く使用されている電子書籍ファイル形式の一つを表します。 |
|
|  | [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) 電子書籍は、Amazon Kindle デバイス向けに開発されたデジタルファイル形式です。 |
|
|  | [MSG](#MSG) | Outlook Mail Message (.msg) は、Microsoft Outlook および Exchange がメール、連絡先、予定、その他のタスクを保存するために使用するファイル形式を表します。 |
|
|  | [EML](#EML) | E-Mail Message (.eml) は、Outlook やその他の関連アプリケーションで保存されたメールメッセージを表します。 |
|
|  | [EMLX](#EMLX) | Apple Mail Message (.emlx) は、Apple によって実装・開発されたものです。 |
|
|  | [PST](#PST) | Outlook Personal Information Store File (.pst) は、さまざまなユーザー情報を保存する Outlook の個人情報ストアファイル（Personal Storage Table とも呼ばれる）を表します。 |
|
|  | [OST](#OST) | Outlook Offline Data File (.ost) は、Microsoft Outlook を使用して Exchange Server に登録した際に、ローカルマシン上でオフラインモードのユーザーのメールボックスデータを表します。 |
|
|  | [TIF](#TIF) | Tagged Image File (.tif) は、このファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。 |
|
|  | [TIFF](#TIFF) | Tagged Image File Format (.tiff) は、このファイル形式標準に準拠したさまざまなデバイスで使用されるラスタ画像を表します。 |
|
|  | [JPG](#JPG) | JPEG Image (.jpg) は、非可逆圧縮方式で保存される画像形式の一種を表します。 |
|
|  | [JPEG](#JPEG) | JPEG Image (.jpeg) は、非可逆圧縮方式で保存される画像形式の一種を表します。 |
|
|  | [JFIF](#JFIF) | JPEG File Interchange Format (.jfif) は、プラットフォーム間の高速な画像交換のために開発された画像形式です。 |
|
|  | [PNG](#PNG) | Portable Network Graphic (.png) は、可逆圧縮を使用するラスタ画像ファイル形式の一種を表します。 |
|
|  | [GIF](#GIF) | Graphical Interchange Format File (.gif) は、高度に圧縮された画像の一種を表します。 |
|
|  | [APNG](#APNG) | Animated Portable Network Graphic (.apng) は、アニメーションをサポートする PNG 形式の拡張版を表します。 |
|
|  | [BMP](#BMP) | Bitmap Image File (.bmp) は、ビットマップデジタル画像を保存するために使用されます。 |
|
|  | [ICO](#ICO) | Microsoft Windows 上でアプリケーションの表現用アイコンとして使用される画像ファイルタイプであるアイコンファイル (.ico) を表します。 |
|
|  | [TGA](#TGA) | TRUEVISION が開発したビットマップデジタル画像を保存するために使用される Truevision TGA (TARGA) ファイルを表します。 |
|
|  | [JP_2](#JP-2) | 画像符号化システムおよび最先端の画像圧縮標準である JPEG 2000 Core Image File (.jp2) を表します。 |
|
|  | [JPF](#JPF) | JPEG 2000 Image File (.jpf) を表します。 |
|
|  | [JPX](#JPX) | JPEG 2000 Image File (.jpx) を表します。 |
|
|  | [JPM](#JPM) | JPEG 2000 Image File (.jpm) を表します。 |
|
|  | [J2C](#J2C) | JPEG 2000 Code InputStream (.j2c) を表します。 |
|
|  | [J2K](#J2K) | DCT 圧縮ではなくウェーブレット圧縮を使用して圧縮された画像である JPEG 2000 Code Stream (.j2k) を表します。 |
|
|  | [JPC](#JPC) | JPEG 2000 Code Stream (.jpc) を表します。 |
|
|  | [JLS](#JLS) | JPEG-LS (JLS) ファイル (.jls) を表します。 |
|
|  | [DIB](#DIB) | Device Independent Bitmap File (.dib) を表します。 |
|
|  | [WMF](#WMF) | ベクターおよびビットマップ形式の画像データを保存するための Microsoft Windows Metafile (WMF) を表す Windows Metafile (.wmf) を表します。 |
|
|  | [WMZ](#WMZ) | ベクターおよびビットマップ形式の画像データを保存するために GZIP アーカイブで圧縮された Microsoft Windows Metafile (WMF) を表す圧縮 Windows Metafile (.wmz) を表します。 |
|
|  | [EMF](#EMF) | デバイスに依存しない形でグラフィカル画像を表す拡張 Windows Metafile (.emf) を表します。 |
|
|  | [EMZ](#EMZ) | GZIP で圧縮された、デバイスに依存しない形でグラフィカル画像を表す Windows 圧縮拡張 Metafile (.emz) を表します。 |
|
|  | [WEBP](#WEBP) | 可逆圧縮と非可逆圧縮に基づく最新のラスターベースのウェブ画像ファイル形式である WebP Image (.webp) を表します。 |
|
|  | [DNG](#DNG) | RAW ファイルの保存に使用されるデジタルカメラ画像形式である Digital Negative Specification (.dng) を表します。 |
|
|  | [CDR](#CDR) | デジタルでエンコードおよび圧縮された画像を保存するために CorelDRAW でネイティブに作成されたベクタードローイング画像ファイルである CorelDraw Vector Graphic Drawing (.cdr) を表します。 |
|
|  | [CMX](#CMX) | ベクターグラフィックとビットマップグラフィックの両方を含む可能性がある描画画像ファイルである Corel Exchange (.cmx) を表します。 |
|
|  | [DJVU](#DJVU) | テキスト、図面、画像、写真の組み合わせを含むスキャン文書や書籍向けに設計されたグラフィックファイル形式である DjVu Image (.djvu) を表します。 |
|
|  | [CGM](#CGM) | ベクターグラフィック（2D）、ラスタグラフィック、テキストを保存および交換するための、無料でプラットフォームに依存しない国際標準メタファイル形式である Computer Graphics Metafile (.cgm) を表します。 |
|
|  | [PCL](#PCL) | Printer Command Language Document (.pcl) を表します。 |
|
|  | [PSD](#PSD) | グラフィックの設計と開発に使用される Adobe Photoshop のネイティブファイル形式である Adobe Photoshop Document (.psd) を表します。 |
|
|  | [PSB](#PSB) | Adobe Photoshop におけるグラフィックの設計と開発に使用される Photoshop Large Document Format (.psb) を表します。 |
|
|  | [DCM](#DCM) | MRI、CT スキャン、超音波画像など患者の医療情報を保存するデジタル画像を表す DICOM Image (.dcm) を表します。 |
|
|  | [PS](#PS) | PostScript ファイル (.ps) を表します。 |
|
|  | [EPS](#EPS) | Encapsulated PostScript ファイル (.eps) を表します。これは、単一ページの外観を定義する Encapsulated PostScript 言語プログラムを記述します。 |
|
|  | [ODG](#ODG) | OpenDocument グラフィック ファイル (.odg) を表します。これは、Apache OpenOffice の Draw アプリケーションで描画要素をベクター画像として保存するために使用されます。 |
|
|  | [FODG](#FODG) | Flat XML ODF テンプレート (.fodg) を表します。これは、Apache OpenOffice の Draw アプリケーションで描画要素をベクター画像として保存するために使用されます。 |
|
|  | [SVG](#SVG) | Scalable Vector Graphics ファイル (.svg) を表します。これは、画像の外観を記述するために XML ベースのテキスト形式を使用するスケーラブルベクターグラフィックス ファイルです。 |
|
|  | [SVGZ](#SVGZ) | 圧縮 Scalable Vector Graphics ファイル (.svgz) を表します。これは、XML ベースのテキスト形式を使用し、GZIP で圧縮されたスケーラブルベクターグラフィックス ファイルで、画像の外観を記述します。 |
|
|  | [OTG](#OTG) | OpenDocument グラフィック テンプレート (.otg) を表します。 |
|
|  | [HTM](#HTM) | Hypertext Markup Language ファイル (.htm) を表します。これは、ブラウザで表示するために作成されたウェブページの拡張子です。 |
|
|  | [HTML](#HTML) | Hypertext Markup Language ファイル (.html) を表します。これは、ブラウザで表示するために作成されたウェブページの拡張子です。 |
|
|  | [MHT](#MHT) | MHTML Web アーカイブ (.mht) を表します。 |
|
|  | [NSF](#NSF) | Lotus Notes データベース (.nsf) を表します。 |
|
|  | [MBOX](#MBOX) | メールボックス ファイル (.mbox) を表します。 |
|
|  | [MHTML](#MHTML) | MIME HTML ファイル (.mhtml) を表します。 |
|
|  | [XML](#XML) | XML ファイル (.xml) を表します。 |
|
|  | [ONE](#ONE) | Microsoft OneNote アプリケーションで作成された OneNote ドキュメント (.one) を表します。 |
|
|  | [PDF](#PDF) | Portable Document Format ファイル (.pdf) を表します。これは、1990 年代に Adobe が作成した文書タイプです。 |
|
|  | [XPS](#XPS) | XML Paper Specification ファイル (.xps) を表します。これは、Microsoft が作成した XML Paper Specification に基づくページレイアウト ファイルを表します。 |
|
|  | [OXPS](#OXPS) | OpenXPS ファイル (.oxps) を表します。 |
|
|  | [TEX](#TEX) | LaTeX ソース ドキュメント (.tex) を表します。これは、文書の組版に使用されるプログラミング機能とマークアップ機能を備えた言語です。 |
|
|  | [OFD](#OFD) | GB/T 33190-2016 で定義されたオープン固定レイアウト文書 (OFD) フォーマットは、中国の公共機関で PDF に代わることを目的としています。 |
|
|  | [PPT](#PPT) | PowerPoint プレゼンテーション (.ppt) を表します。これは、スライドショーとして表示するためのスライドのコレクションで構成された PowerPoint ファイルを表します。 |
|
|  | [PPTX](#PPTX) | PowerPoint Open XML プレゼンテーション (.pptx) を表します。これは、人気のある Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。 |
|
|  | [PPS](#PPS) | PowerPoint スライドショー (.pps) を表します。これは、Microsoft PowerPoint を使用してスライドショー目的で作成されたものです。 |
|
|  | [PPSX](#PPSX) | PowerPoint Open XML スライドショー (.ppsx) ファイルを表します。これは、Microsoft PowerPoint 2007 以降を使用してスライドショー目的で作成されたものです。 |
|
|  | [ODP](#ODP) | OpenDocument プレゼンテーション (.odp) を表します。これは、OpenOffice.org が OASISOpen 標準で使用するプレゼンテーション ファイル形式を表します。 |
|
|  | [FODP](#FODP) | OpenDocument Presentation (.fodp) を表します。これは OpenDocument Flat XML Presentation を表します。 |
|
|  | [POT](#POT) | PowerPoint Template (.pot) を表します。これは PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。 |
|
|  | [PPTM](#PPTM) | PowerPoint Open XML Macro-Enabled Presentation (.pptm) を表します。これは Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応プレゼンテーション ファイルを表します。 |
|
|  | [POTX](#POTX) | PowerPoint Open XML Presentation Template (.potx) を表します。これは Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーション を表します。 |
|
|  | [POTM](#POTM) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) を表します。これはマクロをサポートする Microsoft PowerPoint テンプレート ファイルを表します。 |
|
|  | [PPSM](#PPSM) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) を表します。これは Microsoft PowerPoint 2007 以降で作成されたマクロ対応スライドショー ファイル形式を表します。 |
|
|  | [OTP](#OTP) | OpenDocument Presentation Template (.otp) を表します。これは OASIS OpenDocument 標準形式のアプリケーションで作成されたプレゼンテーション テンプレート ファイルを表します。 |
|
|  | [XLS](#XLS) | Excel Spreadsheet (.xls) を表します。これは Excel バイナリ ファイル形式 を表します。 |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Excel 2003 XML (SpreadsheetML) (.xml) を表します。これは Excel バイナリ ファイル形式 を表します。 |
|
|  | [NUMBERS](#NUMBERS) | Apple Numbers (.numbers) を表します。これは Excel に似たバイナリ ファイル形式 を表します。 |
|
|  | [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet (.xlsx) を表します。これは Microsoft Office 2007 のリリース時に Microsoft が導入した、Microsoft Excel ドキュメントのよく知られた形式です。 |
|
|  | [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) を表します。これはマクロをサポートするスプレッドシート ファイルの一種です。 |
|
|  | [XLSB](#XLSB) | Excel Binary Spreadsheet (.xlsb) を表します。これは Excel バイナリ ファイル形式 を指定します。 |
|
|  | [CSV](#CSV) | Comma Separated Values File (.csv) を表します。これはカンマ区切りの値を含むレコードを持つプレーンテキスト ファイル を表します。 |
|
|  | [TSV](#TSV) | Tab Separated Values File (.tsv) を表します。これはタブで区切られたデータをプレーンテキスト形式で表します。 |
|
|  | [ODS](#ODS) | OpenDocument Spreadsheet (.ods) を表します。これはユーザーが編集可能な OpenDocument Spreadsheet Document 形式を表します。 |
|
|  | [FODS](#FODS) | OpenDocument Flat XML Spreadsheet (.fods) を表します。 |
|
|  | [OTS](#OTS) | OpenDocument Spreadsheet Template (.ots) を表します。 |
|
|  | [XLAM](#XLAM) | Microsoft Excel Add-in (.xlam) を表します。 |
|
|  | [XLTM](#XLTM) | Microsoft Excel Macro-Enabled Template (.xltm) を表します。これは Microsoft Excel がマクロ対応テンプレート ファイルとして生成するファイルを表します。 |
|
|  | [XLT](#XLT) | Microsoft Excel Template (.xlt) を表します。これは Microsoft Office スイートの一部であるスプレッドシート アプリケーション Microsoft Excel で作成されたテンプレート ファイルです。 |
|
|  | [XLTX](#XLTX) | Excel Open XML Spreadsheet Template (.xltx) を表します。これは Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレート を表します。 |
|
|  | [SXC](#SXC) | StarOffice Calc Spreadsheet (.sxc) を表します。 |
|
|  | [MPP](#MPP) | Microsoft Project File (.mpp) を表します。これはプロジェクト管理に関連する情報を統合的に保存する Microsoft Project データ ファイルです。 |
|
|  | [MPT](#MPT) | Microsoft Project Template (.mpt) を表します。これは .MPP ファイル作成のための基本情報と構造、およびドキュメント設定を含みます。 |
|
|  | [MPX](#MPX) | Microsoft Project Exchange ファイル (.mpx) を表します。このファイルは、Microsoft Project (MSP) と MPX ファイル形式をサポートする他のアプリケーション（Primavera Project Planner、Sciforma、Timerline Precision Estimating など）間でプロジェクト情報を転送するための ASCII ファイル形式です。 |
|
|  | [AS](#AS) | ActionScript ファイル (.as) を表します。 |
|
|  | [AS_3](#AS-3) | ActionScript ファイル (.as3) を表します。 |
|
|  | [ASM](#ASM) | アセンブリ言語ソースコードファイル (.asm) を表します。 |
|
|  | [BAT](#BAT) | DOS バッチファイル (.bat) を表します。 |
|
|  | [C](#C) | C/C++ ソースコードファイル (.c) を表します。 |
|
|  | [CC](#CC) | C++ ソースコードファイル (.cc) を表します。 |
|
|  | [CMAKE](#CMAKE) | CMake ファイル (.cmake) を表します。 |
|
|  | [CPP](#CPP) | C++ ソースコードファイル (.cpp) を表します。 |
|
|  | [CS](#CS) | C# ソースコードファイル (.cs) を表します。このファイルは C# プログラミング言語用のソースコードファイルです。 |
|
|  | [VB](#VB) | Visual Basic プロジェクトアイテムファイル (.vb) を表します。このファイルは Visual Basic 言語で作成されたソースコードファイルです。 |
|
|  | [CSS](#CSS) | Cascading Style Sheet (.css) ファイルを表します。 |
|
|  | [CXX](#CXX) | C++ ソースコードファイル (.cxx) を表します。 |
|
|  | [DIFF](#DIFF) | パッチファイル (.diff) を表します。 |
|
|  | [ERB](#ERB) | Ruby ERB スクリプト (.erb) を表します。 |
|
|  | [GROOVY](#GROOVY) | Groovy ソースコードファイル (.groovy) を表します。 |
|
|  | [H](#H) | C/C++/Objective-C ヘッダーファイル (.h) を表します。 |
|
|  | [HAML](#HAML) | Haml ソースコードファイル (.haml) を表します。 |
|
|  | [HH](#HH) | C++ ヘッダーファイル (.hh) を表します。 |
|
|  | [JAVA](#JAVA) | Java ソースコードファイル (.java) を表します。 |
|
|  | [JS](#JS) | JavaScript ファイル (.js) を表します。 |
|
|  | [JSON](#JSON) | JavaScript Object Notation ファイル (.json) を表します。 |
|
|  | [LESS](#LESS) | LESS スタイルシート (.less) ファイルを表します。 |
|
|  | [LOG](#LOG) | ログファイル (.log) を表します。 |
|
|  | [M](#M) | Objective-C 実装ファイル (.m) を表します。 |
|
|  | [MAKE](#MAKE) | Xcode Makefile Script (.make) を表します。 |
|
|  | [MD](#MD) | Markdown Documentation File (.md) を表します。 |
|
|  | [ML](#ML) | ML Source Code File (.ml) を表します。 |
|
|  | [MM](#MM) | Objective-C++ Source File (.mm) を表します。 |
|
|  | [PHP](#PHP) | PHP Source Code File (.php) を表します。 |
|
|  | [PL](#PL) | Perl Script (.pl) を表します。 |
|
|  | [PROPERTIES](#PROPERTIES) | Java Properties File (.properties) を表します。 |
|
|  | [PY](#PY) | Python Script (.py) を表します。 |
|
|  | [RB](#RB) | Ruby Source Code (.rb) ファイルを表します。 |
|
|  | [RST](#RST) | reStructuredText File (.rst) を表します。 |
|
|  | [SASS](#SASS) | Syntactically Awesome StyleSheets File (.sass) を表します。 |
|
|  | [SCALA](#SCALA) | Scala Source Code File (.scala) を表します。 |
|
|  | [SCM](#SCM) | Scheme Source Code File (.scm) を表します。 |
|
|  | [SCRIPT](#SCRIPT) | Generic Script File (.script) を表します。 |
|
|  | [SH](#SH) | Bash Shell Script (.sh) を表します。 |
|
|  | [SML](#SML) | Standard ML Source Code File (.sml) を表します。 |
|
|  | [SQL](#SQL) | Structured Query Language Data File (.sql) を表します。 |
|
|  | [VIM](#VIM) | Vim Settings File (.vim) を表します。 |
|
|  | [YAML](#YAML) | YAML Document (.yaml) を表します。 |
|
|  | [DOC](#DOC) | Microsoft Word Document (.doc) ファイルを表します。 |
|
|  | [DOCX](#DOCX) | Microsoft Word Open XML Document (.docx) ファイルを表します。 |
|
|  | [CHM](#CHM) | Microsoft Compiled HTML Help File (.chm) を表します。 |
|
|  | [DOCM](#DOCM) | Word Open XML Macro-Enabled Document (.docm) ファイルを表します。 |
|
|  | [DOT](#DOT) | Word Document Template (.dot) ファイルを表します。 |
|
|  | [DOTX](#DOTX) | Word Open XML Document Template (.dotx) ファイルを表します。 |
|
|  | [DOTM](#DOTM) | Word Open XML マクロ有効ドキュメントテンプレート (.dotm) ファイルを表します。 |
|
|  | [RTF](#RTF) | リッチテキスト形式ファイル (.rtf) を表します。 |
|
|  | [TXT](#TXT) | プレーンテキストファイル (.txt) を表します。 |
|
|  | [ODT](#ODT) | OpenDocument テキストドキュメント (.odt) を表します。 |
|
|  | [OTT](#OTT) | OpenDocument ドキュメントテンプレート (.ott) を表します。 |
|
|  | [VCF](#VCF) | vCard ファイル (.vcf) を表します。これは連絡先情報を保存するためのデジタルファイル形式です。 |
|
|  | [AI](#AI) | Adobe Illustrator ファイル (.ai) を表します。これは Adobe Illustrator の図面用ファイル形式です。 |
|
|  | [PSM1](#PSM1) | PowerShell スクリプトモジュールファイル (.psm1) を表します。 |
|
|  | [PS1](#PS1) | PowerShell スクリプトファイル (.ps1) を表します。 |
|
|  | [PSD1](#PSD1) | PowerShell スクリプトモジュールマニフェストファイル (.psd1) を表します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | ファイル拡張子をファイルタイプにマッピングします。 |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | ファイル名またはファイルパスから拡張子を抽出し、ファイルタイプにマッピングします。 |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | ファイルのメディアタイプをファイルタイプにマッピングします。 |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | サポートされているファイルタイプを取得します。 |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | パスに基づいてテキスト [TXT](../../com.groupdocs.viewer/filetype#TXT)、[TSV](../../com.groupdocs.viewer/filetype#TSV)、[CSV](../../com.groupdocs.viewer/filetype#CSV) ファイルの文字セットを検出しようとします。 |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | ストリームに基づいてテキスト [TXT](../../com.groupdocs.viewer/filetype#TXT)、[TSV](../../com.groupdocs.viewer/filetype#TSV)、[CSV](../../com.groupdocs.viewer/filetype#CSV) ファイルの文字セットを検出しようとします。 |
|
|  | [getFileFormat()](#getFileFormat--) | ファイル形式の名前を取得します。例: "Microsoft Word Document"。 |
|
|  | [getExtension()](#getExtension--) | ファイル拡張子サフィックス（ピリオド「.」を含む）を取得します。例: ".doc"。 |
|
|  | [toString()](#toString--) | 現在のオブジェクトの文字列表現を返します。 |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


不明なファイルタイプを表します。


### ZIP {#ZIP}
```
public static final FileType ZIP
```


複数のファイルまたはディレクトリを格納できる圧縮ファイル (.zip) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/compression/zip)をご覧ください。


### TAR {#TAR}
```
public static final FileType TAR
```


複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.tar) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/compression/tar)をご覧ください。


### XZ {#XZ}
```
public static final FileType XZ
```


LZMA アルゴリズムに基づく高圧縮率アルゴリズムで圧縮された XZ ファイル (.xz) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/xz)をご覧ください。


### TXZ {#TXZ}
```
public static final FileType TXZ
```


複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.txz、.tar.xz) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/txz)をご覧ください。


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.txz、.tar.xz) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/txz)をご覧ください。


### TGZ {#TGZ}
```
public static final FileType TGZ
```


複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.tgz、.tar.gz) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/tgz)をご覧ください。


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


複数のファイルをまとめて収集するために作成された統合 Unix アーカイブ (.tgz、.tar.gz) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/tgz)をご覧ください。


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


BZIP2 オープンソース圧縮方式で生成された Bzip2 圧縮ファイル (.bz2) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/compression/bz2)をご覧ください。


### RAR {#RAR}
```
public static final FileType RAR
```


RAR (WINRAR バージョン 4) 圧縮方式で生成された Roshal アーカイブ (.rar) 圧縮ファイルを表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/compression/rar)をご覧ください。


### GZ {#GZ}
```
public static final FileType GZ
```


gzip 圧縮アプリケーションで作成された Gnu 圧縮ファイル (.gz) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/compression/gz)をご覧ください。


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Unix システムで使用される Compress プログラムの代替として導入された無料ユーティリティで作成された Gnu 圧縮ファイル (.gzip) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/compression/gz)をご覧ください。


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


LZMA および LZMA2 圧縮を備えた無料のオープンソースアーカイバである 7Zip (.7z、.7zip) ファイルを表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/compression/7z/)をご覧ください。


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio は一般的なファイルアーカイバユーティリティおよびそれに関連するファイル形式です。主に Unix 系のコンピュータオペレーティングシステムにインストールされています。このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/compression/cpio)をご覧ください。


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST ファイルは Zstandard (zstd) 圧縮アルゴリズムで生成される圧縮ファイルです。アルゴリズムによるロスレス圧縮で作成された圧縮ファイルです。ZST ファイルはデータベース、ファイルシステム、ネットワーク、ゲームなど、さまざまな種類のファイルを圧縮するために使用できます。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/compression/zst/)をご覧ください。


### TZST {#TZST}
```
public static final FileType TZST
```


TZST ファイル（.tar.zst、.tzst）は Zstandard アーカイブ（ZST）であり、内部には Unix ベースのユーティリティで作成された Consolidated Unix File Archive（Tar）が含まれ、1 つまたは複数のファイルを収集します。


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST ファイル（.tar.zst、.tzst）は Zstandard アーカイブ（ZST）であり、内部には Unix ベースのユーティリティで作成された Consolidated Unix File Archive（Tar）が含まれ、1 つまたは複数のファイルを収集します。


### ISO {#ISO}
```
public static final FileType ISO
```


ISO 光学ディスクイメージは、CD や DVD などの光学ディスク上の全データの内容を表す、ISO-9660 標準に基づく非圧縮アーカイブディスクイメージファイルです。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/compression/iso/)をご覧ください。


### LHA {#LHA}
```
public static final FileType LHA
```


LHA または LZH はフリーウェアの圧縮ユーティリティおよびそれに関連するファイル形式です。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/compression/lzh/)をご覧ください。


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet（または CAB）は Microsoft Windows 用のアーカイブファイル形式です。
このファイル形式の詳細は[こちら](../https://en.wikipedia.org/wiki/Cabinet_(file_format))をご覧ください。


### DXF {#DXF}
```
public static final FileType DXF
```


Drawing Exchange Format ファイル（.dxf）を表し、これは AutoCAD 図面ファイルのタグ付きデータ表現です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/dxf)をご覧ください。


### DWG {#DWG}
```
public static final FileType DWG
```


AutoCAD Drawing Database ファイル（.dwg）を表し、2D および 3D 設計データを格納するために使用される独自のバイナリファイルです。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/dwg)をご覧ください。


### DWT {#DWT}
```
public static final FileType DWT
```


AutoCAD Drawing Template（.dwt）を表し、DWG ファイルとして保存できる図面を作成するための開始テンプレートとして使用される AutoCAD 図面テンプレートファイルです。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/dwt)をご覧ください。


### STL {#STL}
```
public static final FileType STL
```


Stereolithography ファイル (.stl) は、3 次元表面ジオメトリを表す交換可能なファイル形式です。高速プロトタイピング、3D 印刷、コンピュータ支援製造で一般的に使用されます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/stl)をご覧ください。


### IFC {#IFC}
```
public static final FileType IFC
```


Industry Foundation Classes ファイル (.ifc) は、建築オブジェクトとそのプロパティのインポートおよびエクスポートのための国際標準を確立するファイル形式です。異なるソフトウェアアプリケーション間の相互運用性を可能にします。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/ifc)をご覧ください。


### DWF {#DWF}
```
public static final FileType DWF
```


Design Web Format ファイル (.dwf) は、2D/3D 図面の閲覧、レビュー、印刷のための圧縮ファイル形式です。デザインデータの一部としてグラフィックとテキストを含み、圧縮によりファイルサイズを削減します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/dwf)をご覧ください。


### FBX {#FBX}
```
public static final FileType FBX
```


Autodesk FBX Interchange ファイル（FilmBoX）（.fbx）を表し、3D モデル形式です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/fbx)をご覧ください。


### DWFX {#DWFX}
```
public static final FileType DWFX
```


Design Web Format File XPS (.dwfx) は、2D/3D 図面を XPS ドキュメントとして閲覧、レビュー、印刷するための圧縮形式です。デザインデータの一部としてグラフィックとテキストを含み、圧縮によりファイルサイズを削減します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/dwfx)をご覧ください。


### DGN {#DGN}
```
public static final FileType DGN
```


MicroStation Design ファイル（.dgn）を表し、MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成・サポートされる図面です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/dgn)をご覧ください。


### PLT {#PLT}
```
public static final FileType PLT
```


PLT (HPGL) ファイル (.plt) は、Autodesk 社が導入したベクターベースのプロッタファイルです。特定の CAD ファイルに関する情報を含み、すべての画像はドットではなく線で印刷されるため、生産時の精度と正確性が保証されます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/cad/plt)をご覧ください。


### CF2 {#CF2}
```
public static final FileType CF2
```


Common File Format ファイル（.cf2）を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/cf2)をご覧ください。


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Wavefront 3D Object ファイル（.obj）を表し、Wavefront Technologies が導入した 3D 画像ファイルです。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/3d/obj/)をご覧ください。


### HPG {#HPG}
```
public static final FileType HPG
```


PLT（HPGL）ファイル（.hpg）を表します。
これは HP Graphics Language (HPGL) のプロッターファイルで使用されるファイル形式です。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/hpg)をご覧ください。


### IGS {#IGS}
```
public static final FileType IGS
```


Initial Graphics Exchange Specification（IGES）ファイル（.igs）を表します。


### VSD {#VSD}
```
public static final FileType VSD
```


Visio Drawing ファイル（.vsd）を表し、Microsoft Visio アプリケーションで作成され、さまざまなグラフィックオブジェクトとその相互接続を表す図面です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vsd)をご覧ください。


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing File (.vsdx) を表し、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式です。以前のバージョンでサポートされていたバイナリ形式 (.VSD) に取って代わりました。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vsdx)をご覧ください。


### VSS {#VSS}
```
public static final FileType VSS
```


Visio Stencil File (.vss) を表し、Microsoft Visio 2007 以前で作成されたステンシルファイルです。ステンシルファイルは .VSD Visio 図面に組み込める描画オブジェクトを提供します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vss)をご覧ください。


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio Stencil File (.vssx) を表し、Microsoft Visio 2013 以降で作成された描画ステンシルです。VSSX ファイル形式は Visio 2013 以降で開くことができます。Visio ファイルは、図形、コネクタ、フローチャート、ネットワークレイアウト、UML 図など、さまざまな描画要素を表すことで知られています。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vssx)をご覧ください。


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm) を表し、マクロに対応した Microsoft Visio アプリケーションで作成された描画ファイルです。VSDM ファイルは VSDX に似た OPC/XML 形式の描画で、ファイルを開く際にマクロを実行できる機能も提供します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vsdm)をご覧ください。


### VST {#VST}
```
public static final FileType VST
```


Visio Drawing Template (.vst) を表し、Microsoft Visio で作成されたベクター画像ファイルです。これらは新しいファイルを作成するためのテンプレートとして機能し、新規 Visio 図面の作成に使用されるデフォルトのレイアウトと設定が含まれています。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vst)をご覧ください。


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx) を表し、Microsoft Visio 2013 以降で作成された描画テンプレートファイルです。これらの VSTX ファイルは、.VSDX ファイルとして保存される Visio 図面を作成するための出発点を提供し、デフォルトのレイアウトと設定が含まれています。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vstx)をご覧ください。


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm) を表し、マクロに対応した Microsoft Visio で作成されたテンプレートファイルです。VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで開発されたマクロを実行できます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vstm)をご覧ください。


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm) を表し、マクロに対応した Microsoft Visio Stencil ファイルです。VSSM ファイルを開くと、マクロを実行して図の形状の書式設定や配置を希望通りに行うことができます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vssm)をご覧ください。


### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx) を表し、Microsoft Visio で図表作成に使用される描画や形状からなるステンシルを指します。VSX ファイルは XML 形式で保存され、Visio 2013 までサポートされていました。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vsx)をご覧ください。


### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx) を表し、XML 形式でディスクに保存された Microsoft Visio の描画テンプレートです。このテンプレートは、同じ設定で複数の Visio ファイルを作成するための基本設定を提供します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vtx)をご覧ください。


### VDW {#VDW}
```
public static final FileType VDW
```


Visio Web Drawing (.vdw) は、Web 図面のレンダリングに必要なストリームとストレージを指定します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/web/vdw)をご覧ください。


### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML ファイル (.vdx) を表し、Microsoft Visio で作成された任意の図面やチャートを XML 形式で保存したものです。拡張子は .VDX です。Visio の描画 XML ファイルは、Microsoft が開発した Visio ソフトウェアで作成されます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/vdx)をご覧ください。


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook ファイル (.epub) を表し、出版社や読者向けに標準的なデジタル出版フォーマットを提供する e ブック形式です。この形式は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/ebook/epub)をご覧ください。


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket eBook (.mobi) を表し、最も広く使用されている ebook ファイル形式のひとつです。この形式は古い OEB (Open Ebook Format) 形式の拡張版で、Mobipocket Reader の独自フォーマットとして使用されていました。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/ebook/mobi)をご覧ください。


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) ebook は、Amazon Kindle デバイス向けに開発されたデジタルファイル形式です。この形式は古い AZW ファイルの拡張版で、Kindle Fire デバイスでのみ使用され、先行フォーマットである MOBI および AZW との下位互換性を持ちます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/ebook/azw3)をご覧ください。


### MSG {#MSG}
```
public static final FileType MSG
```


Outlook Mail Message (.msg) は、Microsoft Outlook および Exchange がメール、連絡先、予定、その他のタスクを保存するために使用するファイル形式を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/email/msg)をご覧ください。


### EML {#EML}
```
public static final FileType EML
```


E-Mail メッセージ (.eml) を表し、Outlook などの関連アプリケーションで保存されたメールメッセージです。RFC-822 Internet Message Format Standard に準拠しているため、ほぼすべてのメールクライアントがこのファイル形式をサポートしています。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/email/eml)をご覧ください。


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail メッセージ (.emlx) を表し、Apple によって実装・開発されています。Apple Mail アプリケーションはメールのエクスポートに EMLX ファイル形式を使用します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/email/emlx)をご覧ください。


### PST {#PST}
```
public static final FileType PST
```


Outlook Personal Information Store File (.pst) は、さまざまなユーザー情報を保存する Outlook の個人情報ストアファイル（Personal Storage Table とも呼ばれる）を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/email/pst)をご覧ください。


### OST {#OST}
```
public static final FileType OST
```


Outlook Offline Data File (.ost) は、Microsoft Outlook を使用して Exchange Server に登録した際に、ローカルマシン上でオフラインモードのユーザーのメールボックスデータを表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/email/ost)をご覧ください。


### TIF {#TIF}
```
public static final FileType TIF
```


Tagged Image File (.tif) を表し、さまざまなデバイスで使用できるラスタ画像を表すファイル形式です。この形式は二値、グレースケール、パレットカラー、フルカラーの画像データを複数のカラースペースで記述できます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/tiff)をご覧ください。


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Tagged Image File Format (.tiff) を表し、さまざまなデバイスで使用できるラスタ画像を表すファイル形式です。この形式は二値、グレースケール、パレットカラー、フルカラーの画像データを複数のカラースペースで記述できます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/tiff)をご覧ください。


### JPG {#JPG}
```
public static final FileType JPG
```


JPEG Image (.jpg) を表し、非可逆圧縮方式で保存される画像形式です。圧縮の結果として得られる画像は、保存サイズと画質のトレードオフとなります。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/jpeg)をご覧ください。


### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) を表し、非可逆圧縮方式で保存される画像形式です。圧縮の結果として得られる画像は、保存サイズと画質のトレードオフとなります。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/jpeg)をご覧ください。


### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG File Interchange Format (.jfif) は、プラットフォーム間の高速な画像交換のために開発された画像です。この形式は JPEG 圧縮を使用します。このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/jfif)をご覧ください。


### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) を表し、ロスレス圧縮を使用するラスタ画像ファイル形式です。このファイル形式は Graphics Interchange Format (GIF) の代替として作成され、著作権上の制限がありません。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/png)をご覧ください。


### GIF {#GIF}
```
public static final FileType GIF
```


Graphical Interchange Format File (.gif) を表し、高度に圧縮された画像形式です。各画像は通常、ピクセルあたり最大 8 ビット、全体で最大 256 色が使用可能です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/gif)をご覧ください。


### APNG {#APNG}
```
public static final FileType APNG
```


Animated Portable Network Graphic (.apng) は、アニメーションをサポートする PNG 形式の拡張版を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/apng)をご覧ください。


### BMP {#BMP}
```
public static final FileType BMP
```


ビットマップ画像ファイル (.bmp) を表します。この形式はビットマップデジタル画像の保存に使用されます。これらの画像はグラフィックアダプタに依存せず、デバイス非依存ビットマップ (DIB) ファイル形式とも呼ばれます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/bmp)をご覧ください。


### ICO {#ICO}
```
public static final FileType ICO
```


Microsoft Windows 上でアプリケーションの表現用アイコンとして使用される画像ファイルタイプであるアイコンファイル (.ico) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/ico)をご覧ください。


### TGA {#TGA}
```
public static final FileType TGA
```


TRUEVISION が開発したビットマップデジタル画像を保存するために使用される Truevision TGA (TARGA) ファイルを表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/tga)をご覧ください。


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


画像符号化システムおよび最先端の画像圧縮標準である JPEG 2000 Core Image File (.jp2) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/jp2)をご覧ください。


### JPF {#JPF}
```
public static final FileType JPF
```


JPEG 2000 Image File (.jpf) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/image/jpf)をご覧ください。


### JPX {#JPX}
```
public static final FileType JPX
```


JPEG 2000 Image File (.jpx) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/jpx)をご覧ください。


### JPM {#JPM}
```
public static final FileType JPM
```


JPEG 2000 Image File (.jpm) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/jpm)をご覧ください。


### J2C {#J2C}
```
public static final FileType J2C
```


JPEG 2000 Code InputStream (.j2c) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/j2c)をご覧ください。


### J2K {#J2K}
```
public static final FileType J2K
```


DCT 圧縮ではなくウェーブレット圧縮を使用して圧縮された画像である JPEG 2000 Code Stream (.j2k) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/j2k)をご覧ください。


### JPC {#JPC}
```
public static final FileType JPC
```


JPEG 2000 Code Stream (.jpc) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/jpc)をご覧ください。


### JLS {#JLS}
```
public static final FileType JLS
```


JPEG-LS (JLS) ファイル (.jls) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/jls)をご覧ください。


### DIB {#DIB}
```
public static final FileType DIB
```


Device Independent Bitmap File (.dib) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/dib)をご覧ください。


### WMF {#WMF}
```
public static final FileType WMF
```


ベクターおよびビットマップ形式の画像データを保存するための Microsoft Windows Metafile (WMF) を表す Windows Metafile (.wmf) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/wmf)をご覧ください。


### WMZ {#WMZ}
```
public static final FileType WMZ
```


ベクターおよびビットマップ形式の画像データを保存するために GZIP アーカイブで圧縮された Microsoft Windows Metafile (WMF) を表す圧縮 Windows Metafile (.wmz) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/wmz#compressed_windows_metafile)をご覧ください。


### EMF {#EMF}
```
public static final FileType EMF
```


拡張 Windows メタファイル (.emf) を表します。この形式はデバイスに依存せずにグラフィカル画像を表現します。EMF のメタファイルは可変長レコードを時系列で構成しており、任意の出力デバイスで解析後に保存された画像を描画できます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/emf)をご覧ください。


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows 圧縮拡張メタファイル (.emz) を表します。この形式は GZIP で圧縮されたデバイス非依存のグラフィカル画像を表現します。EMF のメタファイルは可変長レコードを時系列で構成しており、任意の出力デバイスで解析後に保存された画像を描画できます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/emz)をご覧ください。


### WEBP {#WEBP}
```
public static final FileType WEBP
```


WebP 画像 (.webp) を表します。これはロスレスおよびロッシー圧縮に基づく最新のラスタウェブ画像ファイル形式です。画像品質を同等に保ちつつ、画像サイズを大幅に削減します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/webp)をご覧ください。


### DNG {#DNG}
```
public static final FileType DNG
```


デジタルネガティブ仕様 (.dng) を表します。これは RAW ファイルの保存に使用されるデジタルカメラ画像形式です。2004 年 9 月に Adobe によって開発され、主にデジタル写真撮影で使用されます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/dng)をご覧ください。


### CDR {#CDR}
```
public static final FileType CDR
```


CorelDrawベクターグラフィック描画（.cdr）を表します。これは、CorelDRAWでネイティブに作成されたベクタードローイング画像ファイルで、デジタルでエンコードおよび圧縮された画像を保存します。CDR描画ファイルには、テキスト、線、形状、画像、色、および画像内容のベクトル表現のためのエフェクトが含まれます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/cdr)をご覧ください。


### CMX {#CMX}
```
public static final FileType CMX
```


ベクターグラフィックとビットマップグラフィックの両方を含む可能性がある描画画像ファイルである Corel Exchange (.cmx) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/cmx)をご覧ください。


### DJVU {#DJVU}
```
public static final FileType DJVU
```


テキスト、図面、画像、写真の組み合わせを含むスキャン文書や書籍向けに設計されたグラフィックファイル形式である DjVu Image (.djvu) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/djvu)をご覧ください。


### CGM {#CGM}
```
public static final FileType CGM
```


Computer Graphics Metafile（.cgm）を表します。これは、ベクターグラフィック（2D）、ラスタグラフィック、テキストの保存と交換のための、無料でプラットフォームに依存しない国際標準メタファイル形式です。CGMはオブジェクト指向のアプローチを使用し、画像生成のための多くの機能を提供します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/page-description-language/cgm)をご覧ください。


### PCL {#PCL}
```
public static final FileType PCL
```


Printer Command Language Document (.pcl) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/page-description-language/pcl)をご覧ください。


### PSD {#PSD}
```
public static final FileType PSD
```


グラフィックの設計と開発に使用される Adobe Photoshop のネイティブファイル形式である Adobe Photoshop Document (.psd) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/psd)をご覧ください。


### PSB {#PSB}
```
public static final FileType PSB
```


Adobe Photoshop におけるグラフィックの設計と開発に使用される Photoshop Large Document Format (.psb) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/psb)をご覧ください。


### DCM {#DCM}
```
public static final FileType DCM
```


MRI、CT スキャン、超音波画像など患者の医療情報を保存するデジタル画像を表す DICOM Image (.dcm) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/dcm)をご覧ください。


### PS {#PS}
```
public static final FileType PS
```


PostScript ファイル (.ps) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/page-description-language/ps)をご覧ください。


### EPS {#EPS}
```
public static final FileType EPS
```


Encapsulated PostScript ファイル (.eps) を表します。これは、単一ページの外観を定義する Encapsulated PostScript 言語プログラムを記述します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/page-description-language/eps)をご覧ください。


### ODG {#ODG}
```
public static final FileType ODG
```


OpenDocument グラフィック ファイル (.odg) を表します。これは、Apache OpenOffice の Draw アプリケーションで描画要素をベクター画像として保存するために使用されます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/odg)をご覧ください。


### FODG {#FODG}
```
public static final FileType FODG
```


Flat XML ODF テンプレート (.fodg) を表します。これは、Apache OpenOffice の Draw アプリケーションで描画要素をベクター画像として保存するために使用されます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/image/fodg)をご覧ください。


### SVG {#SVG}
```
public static final FileType SVG
```


Scalable Vector Graphics ファイル (.svg) を表します。これは、画像の外観を記述するために XML ベースのテキスト形式を使用するスケーラブルベクターグラフィックス ファイルです。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/page-description-language/svg)をご覧ください。


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


圧縮 Scalable Vector Graphics ファイル (.svgz) を表します。これは、XML ベースのテキスト形式を使用し、GZIP で圧縮されたスケーラブルベクターグラフィックス ファイルで、画像の外観を記述します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/svgz)をご覧ください。


### OTG {#OTG}
```
public static final FileType OTG
```


OpenDocument グラフィック テンプレート (.otg) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/image/otg)をご覧ください。


### HTM {#HTM}
```
public static final FileType HTM
```


Hypertext Markup Language ファイル (.htm) を表します。これは、ブラウザで表示するために作成されたウェブページの拡張子です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/web/html)をご覧ください。


### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language ファイル (.html) を表します。これは、ブラウザで表示するために作成されたウェブページの拡張子です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/web/html)をご覧ください。


### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web アーカイブ (.mht) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/web/mht)をご覧ください。


### NSF {#NSF}
```
public static final FileType NSF
```


Lotus Notes データベース (.nsf) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/nsf)をご覧ください。


### MBOX {#MBOX}
```
public static final FileType MBOX
```


メールボックス ファイル (.mbox) を表します。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/mbox)をご覧ください。


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML ファイル (.mhtml) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/web/mhtml)をご覧ください。


### XML {#XML}
```
public static final FileType XML
```


XML ファイル (.xml) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/web/xml)をご覧ください。


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNoteアプリケーションで作成されたOneNoteドキュメント（.one）を表します。OneNoteは、ノートを取るための下書きパッドのようにアプリケーションを使用して情報を収集できるようにします。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/note-taking/one)をご覧ください。


### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format File（.pdf）を表します。これは1990年代にAdobeが作成した文書の一種です。このファイル形式の目的は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形式で文書やその他の参照資料を表現する標準を導入することでした。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/view/pdf)です。


### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification File（.xps）を表します。これはMicrosoftが作成したXML Paper Specificationに基づくページレイアウトファイルです。この形式はEMFファイル形式の代替としてMicrosoftが開発したもので、PDFファイル形式に似ていますが、文書のレイアウト、外観、印刷情報にXMLを使用しています。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/page-description-language/xps)です。


### OXPS {#OXPS}
```
public static final FileType OXPS
```


OpenXPS ファイル (.oxps) を表します。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/page-description-language/oxps)です。


### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX ソース ドキュメント (.tex) を表します。これは、文書の組版に使用されるプログラミング機能とマークアップ機能を備えた言語です。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/page-description-language/tex)です。


### OFD {#OFD}
```
public static final FileType OFD
```


GB/T 33190-2016 で定義されたオープン固定レイアウト文書 (OFD) フォーマットは、中国の公共機関で PDF に代わることを目的としています。


### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Presentation（.ppt）を表します。これはスライドのコレクションで構成され、スライドショーとして表示されるPowerPointファイルです。Microsoft PowerPoint 97-2003で使用されるバイナリファイル形式を指定しています。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/ppt)です。


### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Presentation（.pptx）を表します。これは人気のMicrosoft PowerPointアプリケーションで作成されたプレゼンテーションファイルです。以前のバイナリ形式のPPTとは異なり、PPTX形式はMicrosoft PowerPoint Open XMLプレゼンテーションファイル形式に基づいています。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/pptx)です。


### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slide Show（.pps）を表します。これはスライドショー目的でMicrosoft PowerPointを使用して作成されます。PPSファイルの読み取りと作成はMicrosoft PowerPoint 97-2003でサポートされています。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/pps)です。


### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML スライドショー (.ppsx) ファイルを表します。これは、Microsoft PowerPoint 2007 以降を使用してスライドショー目的で作成されたものです。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/ppsx)です。


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument プレゼンテーション (.odp) を表します。これは、OpenOffice.org が OASISOpen 標準で使用するプレゼンテーション ファイル形式を表します。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/odp)です。


### FODP {#FODP}
```
public static final FileType FODP
```


OpenDocument Presentation (.fodp) を表します。これは OpenDocument Flat XML Presentation を表します。
このファイル形式の詳細は[here](../https://fileinfo.com/extension/fodp)です。


### POT {#POT}
```
public static final FileType POT
```


PowerPoint Template (.pot) を表します。これは PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/pot)です。


### PPTM {#PPTM}
```
public static final FileType PPTM
```


PowerPoint Open XML Macro-Enabled Presentation (.pptm) を表します。これは Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応プレゼンテーション ファイルを表します。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/pptm)です。


### POTX {#POTX}
```
public static final FileType POTX
```


PowerPoint Open XML Presentation Template (.potx) を表します。これは Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーション を表します。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/potx)です。


### POTM {#POTM}
```
public static final FileType POTM
```


PowerPoint Open XML Macro-Enabled Presentation Template（.potm）を表します。これはマクロをサポートするMicrosoft PowerPointのテンプレートファイルです。POTMファイルはPowerPoint 2007以降で作成され、さらなるプレゼンテーションファイルを作成するために使用できる既定の設定が含まれています。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/potm)です。


### PPSM {#PPSM}
```
public static final FileType PPSM
```


PowerPoint Open XML Macro-Enabled Slide (.ppsm) を表します。これは Microsoft PowerPoint 2007 以降で作成されたマクロ対応スライドショー ファイル形式を表します。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/ppsm)です。


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp) を表します。これは OASIS OpenDocument 標準形式のアプリケーションで作成されたプレゼンテーション テンプレート ファイルを表します。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/presentation/otp)です。


### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet（.xls）を表します。これはExcelバイナリファイル形式です。このようなファイルはMicrosoft Excelだけでなく、OpenOffice CalcやApple Numbersなどの類似スプレッドシートプログラムでも作成できます。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/spreadsheet/xls)です。


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Excel 2003 XML（SpreadsheetML）（.xml）を表します。これはExcelバイナリファイル形式です。このようなファイルはMicrosoft Excelだけでなく、OpenOffice CalcやApple Numbersなどの類似スプレッドシートプログラムでも作成できます。
このファイル形式の詳細は[here](../https://wiki.fileformat.com/spreadsheet/xls)です。


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Apple Numbers (.numbers) を表し、Excel のようなバイナリファイル形式を表します。このようなファイルは Apple Numbers アプリケーションで作成できます。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/numbers)をご覧ください。


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) を表します。これは Microsoft Office 2007 のリリース時に Microsoft が導入した、Microsoft Excel ドキュメントのよく知られた形式です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/xlsx)をご覧ください。


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) を表します。これはマクロをサポートするスプレッドシート ファイルの一種です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/xlsm)をご覧ください。


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) を表し、Excel バイナリファイル形式を指定します。これは Excel ワークブックの内容を指定するレコードと構造のコレクションです。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/xlsb)をご覧ください。


### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv) を表します。これはカンマ区切りの値を含むレコードを持つプレーンテキスト ファイル を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/csv)をご覧ください。


### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv) を表します。これはタブで区切られたデータをプレーンテキスト形式で表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/tsv)をご覧ください。


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods) を表し、ユーザーが編集可能な OpenDocument スプレッドシートドキュメント形式を指します。データは ODF ファイル内に行と列で保存されます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/ods)をご覧ください。


### FODS {#FODS}
```
public static final FileType FODS
```


OpenDocument Flat XML Spreadsheet (.fods) を表します。
これは OpenOffice と LibreOffice が使用する XML ベースのスプレッドシートドキュメント形式です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/fods)をご覧ください。


### OTS {#OTS}
```
public static final FileType OTS
```


OpenDocument Spreadsheet Template (.ots) を表します。
これは OpenOffice と LibreOffice がスプレッドシート用に使用するテンプレートドキュメント形式です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/ots)をご覧ください。


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Microsoft Excel Add-in (.xlam) を表します。
これは Microsoft Excel がカスタム機能を持つアドインを作成するために使用するファイル形式です。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/xlam)をご覧ください。


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel Macro-Enabled Template (.xltm) を表し、Microsoft Excel がマクロ対応テンプレートファイルとして生成するファイルを指します。XLTM ファイルは構造が XLTX と似ていますが、後者はマクロ付きテンプレートファイルの作成をサポートしていません。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/xltm)をご覧ください。


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel Template (.xlt) を表し、Microsoft Office スイートの一部であるスプレッドシートアプリケーション Microsoft Excel で作成されたテンプレートファイルです。Microsoft Office 97-2003 は新しい XLT ファイルの作成と開くことをサポートしていました。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/xlt)をご覧ください。


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) を表し、Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレートを指します。これは XLTX ファイルで指定された同じ設定で XLSX ファイルを生成できる標準テンプレートファイルを作成するために使用されます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/xltx)をご覧ください。


### SXC {#SXC}
```
public static final FileType SXC
```


StarOffice Calc Spreadsheet (.sxc) を表します。
これはスプレッドシートプログラムである StarOffice Calc で作成されたスプレッドシートドキュメントです。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/spreadsheet/sxc)をご覧ください。


### MPP {#MPP}
```
public static final FileType MPP
```


Microsoft Project File (.mpp) を表します。これはプロジェクト管理に関連する情報を統合的に保存する Microsoft Project データ ファイルです。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/project-management/mpp)をご覧ください。


### MPT {#MPT}
```
public static final FileType MPT
```


Microsoft Project Template (.mpt) を表します。これは .MPP ファイル作成のための基本情報と構造、およびドキュメント設定を含みます。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/project-management/mpt)をご覧ください。


### MPX {#MPX}
```
public static final FileType MPX
```


Microsoft Project Exchange ファイル (.mpx) を表します。このファイルは、Microsoft Project (MSP) と MPX ファイル形式をサポートする他のアプリケーション（Primavera Project Planner、Sciforma、Timerline Precision Estimating など）間でプロジェクト情報を転送するための ASCII ファイル形式です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/project-management/mpx)をご覧ください。


### AS {#AS}
```
public static final FileType AS
```


ActionScript ファイル (.as) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/programming/as)をご覧ください。


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


ActionScript ファイル (.as3) を表します。
このファイル形式の詳細は[こちら](../https://datatypes.net/open-as3-files)をご覧ください。


### ASM {#ASM}
```
public static final FileType ASM
```


アセンブリ言語ソースコードファイル (.asm) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/cad/asm)をご覧ください。


### BAT {#BAT}
```
public static final FileType BAT
```


DOS バッチファイル (.bat) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/executable/bat)をご覧ください。


### C {#C}
```
public static final FileType C
```


C/C++ ソースコードファイル (.c) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/programming/c)をご覧ください。


### CC {#CC}
```
public static final FileType CC
```


C++ ソースコードファイル (.cc) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/programming/cc)をご覧ください。


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


CMake ファイル (.cmake) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/programming/cmake)をご覧ください。


### CPP {#CPP}
```
public static final FileType CPP
```


C++ ソースコードファイル (.cpp) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/programming/cpp)をご覧ください。


### CS {#CS}
```
public static final FileType CS
```


C# ソースコードファイル (.cs) を表します。これは C# プログラミング言語のソースコードファイルです。Microsoft が .NET Framework 用に導入しました。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/programming/cs)をご覧ください。


### VB {#VB}
```
public static final FileType VB
```


Visual Basic プロジェクト アイテム ファイル (.vb) を表します。これは Visual Basic 言語で作成されたソースコードファイルです。Microsoft が .NET アプリケーションの開発用に作成しました。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/programming/vb)をご覧ください。


### CSS {#CSS}
```
public static final FileType CSS
```


Cascading Style Sheet (.css) ファイルを表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/web/css)をご覧ください。


### CXX {#CXX}
```
public static final FileType CXX
```


C++ ソースコードファイル (.cxx) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/programming/cxx)をご覧ください。


### DIFF {#DIFF}
```
public static final FileType DIFF
```


パッチファイル (.diff) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/programming/diff)をご覧ください。


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby ERB スクリプト (.erb) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/programming/erb)をご覧ください。


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy ソースコードファイル (.groovy) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/programming/groovy)をご覧ください。


### H {#H}
```
public static final FileType H
```


C/C++/Objective-C ヘッダーファイル (.h) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/programming/h)をご覧ください。


### HAML {#HAML}
```
public static final FileType HAML
```


Haml ソースコードファイル (.haml) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/programming/haml)をご覧ください。


### HH {#HH}
```
public static final FileType HH
```


C++ ヘッダーファイル (.hh) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/programming/hh)をご覧ください。


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java ソースコードファイル (.java) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/programming/java)をご覧ください。


### JS {#JS}
```
public static final FileType JS
```


JavaScript ファイル (.js) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/web/js)をご覧ください。


### JSON {#JSON}
```
public static final FileType JSON
```


JavaScript Object Notation ファイル (.json) を表します。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/web/json)をご覧ください。


### LESS {#LESS}
```
public static final FileType LESS
```


LESS スタイルシート (.less) ファイルを表します。
このファイル形式について詳しくは[here](../https://wiki.fileformat.com/web/less)をご覧ください。


### LOG {#LOG}
```
public static final FileType LOG
```


ログファイル (.log) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/database/log)をご覧ください。


### M {#M}
```
public static final FileType M
```


Objective-C 実装ファイル (.m) を表します。
このファイル形式について詳しくは[here](../https://fileinfo.com/extension/m)をご覧ください。


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Xcode Makefile Script (.make) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/make)をご覧ください。


### MD {#MD}
```
public static final FileType MD
```


Markdown Documentation File (.md) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/word-processing/md)をご覧ください。


### ML {#ML}
```
public static final FileType ML
```


ML Source Code File (.ml) を表します。
このファイル形式について詳しくは[here](../https://wiki.fileformat.com/programming/ml)をご覧ください。


### MM {#MM}
```
public static final FileType MM
```


Objective-C++ Source File (.mm) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/mm)をご覧ください。


### PHP {#PHP}
```
public static final FileType PHP
```


PHP Source Code File (.php) を表します。
このファイル形式について詳しくは[here](../https://wiki.fileformat.com/programming/php)をご覧ください。


### PL {#PL}
```
public static final FileType PL
```


Perl Script (.pl) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/pl)をご覧ください。


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Java Properties File (.properties) を表します。
このファイル形式について詳しくは[here](../https://fileinfo.com/extension/properties)をご覧ください。


### PY {#PY}
```
public static final FileType PY
```


Python Script (.py) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/py)をご覧ください。


### RB {#RB}
```
public static final FileType RB
```


Ruby Source Code (.rb) ファイルを表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/rb)をご覧ください。


### RST {#RST}
```
public static final FileType RST
```


reStructuredText File (.rst) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/rst)をご覧ください。


### SASS {#SASS}
```
public static final FileType SASS
```


Syntactically Awesome StyleSheets File (.sass) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/web/sass)をご覧ください。


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala Source Code File (.scala) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/scala)をご覧ください。


### SCM {#SCM}
```
public static final FileType SCM
```


Scheme Source Code File (.scm) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/scm)をご覧ください。


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Generic Script File (.script) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/script)をご覧ください。


### SH {#SH}
```
public static final FileType SH
```


Bash Shell Script (.sh) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/cs/programming/sh)をご覧ください。


### SML {#SML}
```
public static final FileType SML
```


Standard ML Source Code File (.sml) を表します。
このファイル形式について詳しくは[here](../https://fileinfo.com/extension/sml)をご覧ください。


### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language Data File (.sql) を表します。
このファイル形式について詳しくは[here](../https://wiki.fileformat.com/database/sql)をご覧ください。


### VIM {#VIM}
```
public static final FileType VIM
```


Vim Settings File (.vim) を表します。
このファイル形式について詳しくは[here](../https://fileinfo.com/extension/vim)をご覧ください。


### YAML {#YAML}
```
public static final FileType YAML
```


YAML Document (.yaml) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/programming/yaml)をご覧ください。


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) ファイルを表します。
このファイル形式について詳しくは[here](../https://wiki.fileformat.com/word-processing/doc)をご覧ください。


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) ファイルを表します。
このファイル形式について詳しくは[here](../https://wiki.fileformat.com/word-processing/docx)をご覧ください。


### CHM {#CHM}
```
public static final FileType CHM
```


Microsoft Compiled HTML Help File (.chm) を表します。
このファイル形式について詳しくは[here](../https://docs.fileformat.com/web/chm)をご覧ください。


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) ファイルを表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/word-processing/docm)をご覧ください。


### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) ファイルを表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/word-processing/dot)をご覧ください。


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) ファイルを表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/word-processing/dotx)をご覧ください。


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML マクロ有効ドキュメントテンプレート (.dotm) ファイルを表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/word-processing/dotm)をご覧ください。


### RTF {#RTF}
```
public static final FileType RTF
```


リッチテキスト形式ファイル (.rtf) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/word-processing/rtf)をご覧ください。


### TXT {#TXT}
```
public static final FileType TXT
```


プレーンテキストファイル (.txt) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/word-processing/txt)をご覧ください。


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument テキストドキュメント (.odt) を表します。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/word-processing/odt)をご覧ください。


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument ドキュメントテンプレート (.ott) を表します。
これは、OASIS の OpenDocument 標準形式に準拠して生成されたテンプレート文書です。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/word-processing/ott)をご覧ください。


### VCF {#VCF}
```
public static final FileType VCF
```


vCard ファイル (.vcf) を表します。これは連絡先情報を保存するためのデジタルファイル形式です。
これは、一般的な情報交換アプリケーション間でのデータ交換に広く使用されています。
このファイル形式の詳細は[こちら](../https://wiki.fileformat.com/email/vcf)をご覧ください。


### AI {#AI}
```
public static final FileType AI
```


Adobe Illustrator ファイル (.ai) を表します。これは Adobe Illustrator の図面用ファイル形式です。
このファイル形式の詳細は[こちら](../https://docs.fileformat.com/image/ai)をご覧ください。


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


PowerShell スクリプトモジュールファイル (.psm1) を表します。
これは、PowerShell モジュールスクリプト用のファイル形式です。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/psm1)をご覧ください。


### PS1 {#PS1}
```
public static final FileType PS1
```


PowerShell スクリプトファイル (.ps1) を表します。
これは、Windows PowerShell Cmdlet ファイル用のファイル形式です。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/ps1)をご覧ください。


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


PowerShell スクリプトモジュールマニフェストファイル (.psd1) を表します。
これは、PowerShell モジュールマニフェストスクリプト用のファイル形式です。
このファイル形式の詳細は[こちら](../https://fileinfo.com/extension/psd1)をご覧ください。


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


ファイル拡張子をファイルタイプにマッピングします。


このメソッドは、ピリオド「.」の有無にかかわらずファイル拡張子を受け取り、サポートされている場合は対応するファイルタイプを返します。
ファイルタイプがサポートされていない場合、デフォルトの[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) ファイルタイプを返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | extension | java.lang.String | ピリオド「.」の有無にかかわらずファイル拡張子です。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


ファイル名またはファイルパスから拡張子を抽出し、ファイルタイプにマッピングします。


ファイルタイプがサポートされている場合、メソッドは対応するものを返します
FileType
,
それ以外の場合は、デフォルトの[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) ファイルタイプを返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ファイル名またはファイルパスです。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


ファイルのメディアタイプをファイルタイプにマッピングします。たとえば、'application/pdf' は [PDF](../../com.groupdocs.viewer/filetype#PDF) にマッピングされます。


このメソッドはファイルのメディアタイプを入力として受け取り、対応するものにマッピングします
FileType
。メディアタイプが
サポートされている場合、メソッドは対応するファイルタイプを返します。メディアタイプがサポートされていない場合、デフォルトを返します
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | mediaType | java.lang.String | ファイルのメディアタイプ（例：'application/pdf'）です。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


ファイルシグネチャを読み取ってファイルタイプを検出します。


このメソッドはファイルを表す入力ストリームを受け取り、ファイルシグネチャを解析してファイルタイプを検出しようとします。
ファイルシグネチャは、ファイルの先頭にある固有のバイト列で、ファイルタイプを示します。メソッドは
入力ストリームからファイルシグネチャを読み取り、サポートされているファイルタイプの既知のシグネチャと照合します。
一致が見つかった場合、メソッドは対応するファイルタイプを返します。一致が見つからない場合、デフォルトを返します
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | stream | java.io.InputStream | ファイルを表す入力ストリームです。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


ファイルシグネチャを読み取ってファイルタイプを検出します。


このメソッドは、ファイルの先頭にある固有のバイト列であるファイルシグネチャを解析し、
ファイルタイプを決定します。提供された入力ストリームからファイルシグネチャを読み取り、既知のファイルシグネチャと照合します
サポートされているファイルタイプのものです。一致が見つかった場合、メソッドは対応するファイルタイプを返します。一致が見つからない場合、
デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) ファイルタイプを返します。


ファイルが暗号化されていて開くのにパスワードが必要な場合、パスワードはこのメソッドへのパラメータとして提供すべきです。
メソッドです。パスワードはファイルを復号し、シグネチャを解析してファイルタイプを決定するために使用されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | stream | java.io.InputStream | ファイルを表す入力ストリームです。 |
|
|  | password | java.lang.String | ファイルを開くためのパスワードです。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


ファイルシグネチャを読み取ってファイルタイプを検出します。


このメソッドは、ファイルの先頭にある固有のバイト列であるファイルシグネチャを解析し、
ファイルタイプを決定します。提供された入力ストリームからファイルシグネチャを読み取り、既知のファイルシグネチャと照合します
サポートされているファイルタイプのものです。一致が見つかった場合、メソッドは対応するファイルタイプを返します。一致が見つからない場合、
デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) ファイルタイプを返します。


ファイルタイプ検出プロセス中に関連情報やエラーを記録するためにロガーを提供できます。ロガーは
ILogger インターフェイスを実装すべきです。ロガーが提供されない場合、検出プロセスは何も出力しません。
ログ出力です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | stream | java.io.InputStream | ファイルを表す入力ストリームです。 |
|
|  | ロガー | com.groupdocs.foundation.logging.ILogger | 情報やエラーを記録するためのロガーです。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


ファイルシグネチャを読み取ってファイルタイプを検出します。


このメソッドは、ファイルの先頭にある固有のバイト列であるファイルシグネチャを解析し、
ファイルタイプを決定します。提供された入力ストリームからファイルシグネチャを読み取り、既知のファイルシグネチャと照合します
サポートされているファイルタイプのものです。一致が見つかった場合、メソッドは対応するファイルタイプを返します。一致が見つからない場合、
デフォルトの [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) ファイルタイプを返します。


ファイルが暗号化または保護されている場合、パスワードを指定できます。パスワードはファイルを開く前に使用されます。
ファイル署名を解析します。ファイルがパスワードを必要としない場合、このパラメーターは null に設定できます。


ファイルタイプ検出プロセス中に関連情報やエラーを記録するためにロガーを提供できます。ロガーは
ILogger インターフェイスを実装すべきです。ロガーが提供されない場合、検出プロセスは何も出力しません。
ログ出力です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | stream | java.io.InputStream | ファイルを表す入力ストリームです。 |
|
|  | password | java.lang.String | ファイルを開くためのパスワードです。 |
|
|  | ロガー | com.groupdocs.foundation.logging.ILogger | 情報やエラーを記録するためのロガーです。 |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


サポートされているファイルタイプを取得します。


このメソッドは、システムがサポートするすべてのファイルタイプのシーケンスを返します。ファイルタイプはさまざまな
システムで処理または認識できる文書フォーマットを表します。
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - サポートされているファイルタイプのシーケンスです。

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


パスに基づいてテキスト [TXT](../../com.groupdocs.viewer/filetype#TXT)、[TSV](../../com.groupdocs.viewer/filetype#TSV)、[CSV](../../com.groupdocs.viewer/filetype#CSV) ファイルの文字セットを検出しようとします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | filePath | java.lang.String | ファイル名またはファイルパスです。 |
|

**Returns:**
java.nio.charset.Charset - ファイルの文字セット検出に失敗した場合の Charset または null です。

**Example:**


Charset charset = FileType.detectCharset(\"message.txt\");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


ストリームに基づいてテキスト [TXT](../../com.groupdocs.viewer/filetype#TXT)、[TSV](../../com.groupdocs.viewer/filetype#TSV)、[CSV](../../com.groupdocs.viewer/filetype#CSV) ファイルの文字セットを検出しようとします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | stream | java.io.InputStream | ファイルストリームです。 |
|

**Returns:**
java.nio.charset.Charset - ファイルの文字セット検出に失敗した場合の Charset または null です。

**Example:**


InputStream stream = new FileInputStream(\"message.txt\");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


ファイル形式の名前を取得します。例: "Microsoft Word Document"。


**Returns:**
java.lang.String - ファイル形式の名前です。

### getExtension() {#getExtension--}
```
public final String getExtension()
```


ファイル拡張子サフィックス（ピリオド「.」を含む）を取得します。例: ".doc"。


**Returns:**
java.lang.String - ファイル拡張子のサフィックスです。

### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトの文字列表現を返します。


**Returns:**
java.lang.String - 現在のオブジェクトの文字列表現。

