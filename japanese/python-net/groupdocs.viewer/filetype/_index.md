---
title: "FileType クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイルタイプを表し、GroupDocs.Viewer がサポートするすべてのファイルタイプのリストを取得するメソッドを提供します。"
type: docs
url: /ja/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

ファイルタイプを表し、GroupDocs.Viewer がサポートするすべてのファイルタイプのリストを取得するメソッドを提供します。

FileType 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | 新しいインスタンスを初期化します [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)。 |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | 新しい FileType インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | パスでテキスト TXT、TSV、CSV ファイルのエンコーディングを検出します。 |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | ストリームからテキストファイル（TXT、TSV、CSV）のエンコーディングを検出しようとします。 |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | 現在の [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) が指定された [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) と同じかどうかを判断します。 |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | 現在の [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) が指定されたオブジェクトと同じかどうかを判断します。 |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | ファイル拡張子をファイルタイプにマッピングします。 |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | ファイル拡張子を抽出し、ファイルタイプにマッピングします。 |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | ファイルのメディアタイプを [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) にマッピングします（例: 'application/pdf' は [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/) にマップされます）。 |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | ファイルシグネチャを読み取ってファイルタイプを検出します。 |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | 現在の [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) オブジェクトのハッシュコードを返します。 |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | サポートされているファイルタイプを取得します。 |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | 現在のオブジェクトを表す文字列を返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | ファイル名のサフィックス（ピリオド「.」を含む）例: ".doc"。 |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | ファイルタイプ名（例: "Microsoft Word Document"）。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | 不明なファイルタイプを表します。 |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Zipped File（.zip）は、1つ以上のファイルやディレクトリを保持できるアーカイブを表します。こちらでこのファイル形式の詳細をご覧ください。 |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Consolidated Unix File Archive（.tar）は、1つ以上のファイルを収集するために Unix ベースのユーティリティで作成されたアーカイブです。こちらでこのファイル形式の詳細をご覧ください。 |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | XZ file（.xz）は、LZMA アルゴリズムに基づく高圧縮率の圧縮アルゴリズムで圧縮されたアーカイブです。こちらでこのファイル形式の詳細をご覧ください。 |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Consolidated Unix File Archive（.txz、.tar.xz）は、1つ以上のファイルを収集するために Unix ベースのユーティリティで作成されたアーカイブです。こちらでこのファイル形式の詳細をご覧ください。 |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Consolidated Unix File Archive（.txz、.tar.xz）は、1つ以上のファイルを収集するために Unix ベースのユーティリティで作成されたアーカイブです。こちらでこのファイル形式の詳細をご覧ください。 |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Consolidated Unix File Archive（.tgz、.tar.gz）は、1つ以上のファイルを収集するために Unix ベースのユーティリティで作成されたアーカイブです。こちらでこのファイル形式の詳細をご覧ください。 |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Consolidated Unix File Archive（.tgz、.tar.gz）は、1つ以上のファイルを収集するために Unix ベースのユーティリティで作成されたアーカイブです。こちらでこのファイル形式の詳細をご覧ください。 |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Bzip2 Compressed File（.bz2）は、主に UNIX または Linux システムで使用される BZIP2 オープンソース圧縮方式で生成された圧縮ファイルです。こちらでこのファイル形式の詳細をご覧ください。 |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) は、RAR (WINRAR) 圧縮方式を使用して生成された圧縮ファイルです。このファイル形式の詳細については、こちらをご覧ください。 |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) は、gzip 圧縮アプリケーションで作成された圧縮ファイルです。複数の圧縮ファイルを含むことができ、UNIX や Linux システムで一般的に使用されます。このファイル形式の詳細については、こちらをご覧ください。 |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) は、Unix システムで使用されていた Compress プログラムの代替として導入されたフリーユーティリティです。このようなファイルは、Windows と macOS の両方で利用できる WinZip などの複数のアプリケーションで開いたり展開したりできます。このファイル形式の詳細については、こちらをご覧ください。 |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) は、LZMA および LZMA2 圧縮を備えた無料のオープンソースアーカイバです。このファイル形式の詳細については、こちらをご覧ください。 |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio は、一般的なファイルアーカイバユーティリティおよびそれに関連するファイル形式です。主に Unix 系のコンピュータ OS にインストールされています。このファイル形式の詳細については、こちらをご覧ください。 |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST ファイルは、Zstandard (zstd) 圧縮アルゴリズムで生成された圧縮ファイルです。アルゴリズムによるロスレス圧縮で作成されます。ZST ファイルは、データベース、ファイルシステム、ネットワーク、ゲームなど、さまざまな種類のファイルを圧縮するために使用できます。このファイル形式の詳細については、こちらをご覧ください。 |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST ファイル (.tar.zst, .tzst) は Zstandard アーカイブ (ZST) で、内部に Unix 系ユーティリティで作成された統合 Unix ファイルアーカイブ (Tar) を含み、1 つまたは複数のファイルを収集します。 |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST ファイル (.tar.zst, .tzst) は Zstandard アーカイブ (ZST) で、内部に Unix 系ユーティリティで作成された統合 Unix ファイルアーカイブ (Tar) を含み、1 つまたは複数のファイルを収集します。 |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO 光ディスクイメージは、CD や DVD などの光ディスク上の全データ内容を表す、ISO-9660 標準に基づく非圧縮アーカイブディスクイメージファイルです。このファイル形式の詳細については、こちらをご覧ください。 |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA または LZH は、フリーウェアの圧縮ユーティリティおよび関連するファイル形式です。このファイル形式の詳細については、こちらをご覧ください。 |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (または CAB) は、Microsoft Windows 用のアーカイブファイル形式です。このファイル形式の詳細については、こちらをご覧ください。 |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) は、AutoCAD 図面ファイルのタグ付きデータ表現です。このファイル形式の詳細については、こちらをご覧ください。 |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) は、2D および 3D 設計データを格納するために使用される独自のバイナリファイルを表します。ASCII ファイルである DXF と同様に、DWG は CAD (Computer Aided Design) 図面のバイナリファイル形式です。このファイル形式の詳細については、こちらをご覧ください。 |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt) は、DWG ファイルとして保存できる図面を作成する際の開始点として使用される AutoCAD の図面テンプレートファイルです。このファイル形式の詳細については、こちらをご覧ください。 |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl) は、3 次元表面ジオメトリを表す汎用ファイル形式です。このファイル形式は、ラピッドプロトタイピング、3D プリント、コンピュータ支援製造など、さまざまな分野で利用されています。このファイル形式の詳細については、こちらをご覧ください。 |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc) は、建築オブジェクトとそのプロパティのインポート・エクスポートのための国際標準を確立するファイル形式です。このファイル形式は、異なるソフトウェア間の相互運用性を提供します。このファイル形式の詳細については、こちらをご覧ください。 |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format File (.dwf) は、設計ファイルの閲覧、レビュー、印刷のために圧縮形式で表現された 2D/3D 図面です。デザインデータの一部としてグラフィックとテキストを含み、圧縮形式によりファイルサイズを削減します。このファイル形式の詳細については、こちらをご覧ください。 |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) は、3D モデル形式を表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) は、閲覧、レビュー、印刷用に圧縮形式の XPS ドキュメントとして表現された 2D/3D 図面です。デザインデータの一部としてグラフィックとテキストを含み、圧縮形式によりファイルサイズを削減します。このファイル形式の詳細については、こちらをご覧ください。 |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) は、MicroStation や Intergraph Interactive Graphics Design System などの CAD アプリケーションで作成・サポートされる図面です。このファイル形式の詳細については、こちらをご覧ください。 |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) は、Autodesk, Inc. が導入したベクターベースのプロッターファイルで、特定の CAD ファイルに関する情報を含みます。プロットの詳細は生産において正確さと精度が求められ、PLT ファイルはすべての画像をドットではなく線で印刷するため、これを保証します。このファイル形式の詳細については、こちらをご覧ください。 |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Common File Format File は、このファイル形式の詳細については、こちらをご覧ください。 |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) は、Wavefront Technologies が導入した 3D 画像ファイルです。このファイル形式の詳細については、こちらをご覧ください。 |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) は、Microsoft Visio アプリケーションで作成された、さまざまなグラフィックオブジェクトとそれらの相互接続を表す図面です。このファイル形式の詳細については、こちらをご覧ください。 |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) は、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式を表します。これは、以前のバージョンの Microsoft Visio がサポートしていたバイナリ形式 .VSD に代わるものとして開発されました。このファイル形式の詳細については、こちらをご覧ください。 |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) は、Microsoft Visio 2007 以前で作成されたステンシルファイルです。ステンシルファイルは、.VSD Visio 図面に組み込むことができる描画オブジェクトを提供します。このファイル形式の詳細については、こちらをご覧ください。 |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) は、Microsoft Visio 2013 以降で作成された描画ステンシルです。VSSX ファイル形式は Visio 2013 以降で開くことができます。Visio ファイルは、図形のコレクション、コネクタ、フローチャート、ネットワークレイアウト、UML 図など、さまざまな描画要素を表現できることで知られています。このファイル形式の詳細については、こちらをご覧ください。 |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) は、マクロをサポートする Microsoft Visio アプリケーションで作成された描画ファイルです。VSDM ファイルは VSDX と類似した OPC/XML 形式の図面ですが、ファイルを開く際にマクロを実行できる機能も備えています。このファイル形式の詳細については、こちらをご覧ください。 |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) は、Microsoft Visio で作成されたベクター画像ファイルで、以降のファイル作成のテンプレートとして機能します。これらのテンプレートファイルはバイナリ形式で、新しい Visio 図面の作成に使用される既定のレイアウトと設定が含まれています。このファイル形式の詳細については、こちらをご覧ください。 |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) は、Microsoft Visio 2013 以降で作成された描画テンプレートファイルです。これらの VSTX ファイルは、デフォルトのレイアウトと設定を備えた .VSDX ファイルとして保存できる Visio 図面作成の出発点を提供します。このファイル形式の詳細については、こちらをご覧ください。 |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) は、マクロをサポートする Microsoft Visio で作成されたテンプレートファイルです。VSDX ファイルとは異なり、VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで開発されたマクロを実行できます。このファイル形式の詳細については、こちらをご覧ください。 |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) は、マクロをサポートする Microsoft Visio ステンシルファイルです。VSSM ファイルを開くと、マクロを実行して図中の形状の書式設定や配置を行うことができます。このファイル形式の詳細については、こちらをご覧ください。 |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) は、Microsoft Visio で図表作成に使用される描画や形状からなるステンシルを指します。VSX ファイルは XML 形式で保存され、Visio 2013 までサポートされていました。このファイル形式の詳細については、こちらをご覧ください。 |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) は、XML 形式でディスクに保存される Microsoft Visio の描画テンプレートです。このテンプレートは、同一の設定を持つ複数の Visio ファイルを作成するための基本設定を提供することを目的としています。このファイル形式の詳細については、こちらをご覧ください。 |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) は、Web 図面のレンダリングに必要なストリームとストレージを指定するファイル形式です。このファイル形式の詳細については、こちらをご覧ください。 |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) は、Microsoft Visio で作成された任意の図面やチャートを表し、XML 形式で保存されたものは .VDX 拡張子を持ちます。Visio の XML 図面ファイルは、Microsoft が開発した Visio ソフトウェアで作成されます。このファイル形式の詳細については、こちらをご覧ください。 |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub) は、出版社と読者向けに標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。このフォーマットは現在非常に一般的で、多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。このファイル形式の詳細については、こちらをご覧ください。 |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi) は、最も広く使用されている電子書籍ファイル形式の一つです。この形式は古い OEB（Open Ebook Format）形式を拡張したもので、Mobipocket Reader の独自フォーマットとして使用されていました。このファイル形式の詳細については、こちらをご覧ください。 |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) 電子書籍は、Amazon Kindle デバイス向けに開発されたデジタルファイル形式です。この形式は従来の AZW ファイルを拡張したもので、Kindle Fire デバイスでのみ使用され、先行する MOBI および AZW 形式との下位互換性を備えています。このファイル形式の詳細については、こちらをご覧ください。 |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) は、Microsoft Outlook と Exchange がメールメッセージ、連絡先、予定、その他のタスクを保存するために使用するファイル形式です。このファイル形式の詳細については、こちらをご覧ください。 |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E-Mail Message (.eml) は、Outlook やその他の関連アプリケーションで保存されたメールメッセージを表します。ほぼすべてのメールクライアントが、RFC-822 インターネットメッセージ形式標準に準拠しているためこのファイル形式をサポートしています。このファイル形式の詳細については、こちらをご覧ください。 |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) このファイル形式の詳細については、こちらをご覧ください。 |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) このファイル形式の詳細については、こちらをご覧ください。 |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx) は Apple によって実装・開発されたものです。Apple Mail アプリケーションはメールのエクスポートに EMLX ファイル形式を使用します。このファイル形式の詳細については、こちらをご覧ください。 |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst) は、Outlook の個人用ストレージファイル（Personal Storage Table とも呼ばれる）を表し、さまざまなユーザー情報を保存します。このファイル形式の詳細については、こちらをご覧ください。 |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost) は、Microsoft Outlook を使用して Exchange Server に登録した際に、ローカルマシン上でオフラインモードのユーザーメールボックスデータを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) は、このファイル形式標準に準拠したさまざまなデバイスでの使用を想定したラスタ画像を表します。二値、グレースケール、パレットカラー、フルカラーの画像データを複数のカラースペースで記述できる機能があります。このファイル形式の詳細については、こちらをご覧ください。 |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) は、このファイル形式標準に準拠したさまざまなデバイスでの使用を想定したラスタ画像を表します。二値、グレースケール、パレットカラー、フルカラーの画像データを複数のカラースペースで記述できる機能があります。このファイル形式の詳細については、こちらをご覧ください。 |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG Image (.jpg) は、非可逆圧縮方式で保存される画像フォーマットの一種です。圧縮の結果として得られる出力画像は、保存サイズと画像品質のトレードオフとなります。このファイル形式の詳細はここで確認できます。 |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG Image (.jpeg) は、非可逆圧縮方式で保存される画像フォーマットの一種です。圧縮の結果として得られる出力画像は、保存サイズと画像品質のトレードオフとなります。このファイル形式の詳細はここで確認できます。 |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif) は、プラットフォーム間の高速な画像交換のために開発された画像です。このフォーマットは JPEG 圧縮を使用します。このファイル形式の詳細はここで確認できます。 |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png) は、ロスレス圧縮を使用するラスタ画像ファイルフォーマットの一種です。このフォーマットは Graphics Interchange Format (GIF) の代替として作成され、著作権制限がありません。このファイル形式の詳細はここで確認できます。 |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format File (.gif) は、高度に圧縮された画像の一種です。GIF は通常、1 ピクセルあたり最大 8 ビット、画像全体で最大 256 色を許容します。このファイル形式の詳細はここで確認できます。 |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng) は、アニメーションをサポートする PNG フォーマットの拡張です。このファイル形式の詳細はここで確認できます。 |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Bitmap Image File (.bmp) は、ビットマップデジタル画像を保存するために使用されます。これらの画像はグラフィックアダプタに依存せず、デバイス非依存ビットマップ (DIB) ファイルフォーマットとも呼ばれます。このファイル形式の詳細はここで確認できます。 |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) は、TRUEVISION が開発したビットマップデジタル画像を保存するために使用されます。このファイル形式の詳細はここで確認できます。 |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Icon File (.ico) は、Microsoft Windows 上でアプリケーションを表すアイコンとして使用される画像ファイルタイプです。このファイル形式の詳細はここで確認できます。 |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image File (.jp2) は、画像符号化システムおよび最先端の画像圧縮標準です。このファイル形式の詳細はここで確認できます。 |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | JPEG 2000 Image File (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | JPEG 2000 Image File (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | JPEG 2000 Image File (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | JPEG 2000 Code Stream (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 Code Stream (.j2k) は、DCT 圧縮ではなくウェーブレット圧縮を使用して圧縮された画像です。このファイル形式の詳細はここで確認できます。 |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | JPEG 2000 Code Stream (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Device Independent Bitmap File (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) は、ベクターおよびビットマップ形式の画像データを保存するための Microsoft Windows Metafile (WMF) を表します。このファイル形式の詳細はここで確認できます。 |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) は、ベクターおよびビットマップ形式の画像データを保存するために GZIP で圧縮された Microsoft Windows Metafile (WMF) を表します。このファイル形式の詳細はここで確認できます。 |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) は、デバイスに依存しない形でグラフィカル画像を表します。EMF のメタファイルは、任意の出力デバイスで解析後に保存された画像を描画できる可変長レコードを時系列で構成しています。このファイル形式の詳細はここで確認できます。 |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz) は、GZIP によって圧縮されたデバイス非依存のグラフィカル画像を表します。EMF のメタファイルは、任意の出力デバイスで解析後に保存された画像を描画できる可変長レコードを時系列で構成しています。このファイル形式の詳細はここで確認できます。 |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp) は、ロスレスおよび非可逆圧縮に基づく最新のラスタウェブ画像ファイルフォーマットです。画像サイズを大幅に削減しながら同等の画像品質を提供します。このファイル形式の詳細はここで確認できます。 |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng) は、RAW ファイルの保存に使用されるデジタルカメラ画像フォーマットです。2004 年 9 月に Adobe によって開発されました。主にデジタル写真撮影のために開発されました。このファイル形式の詳細はここで確認できます。 |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) は、CorelDRAW でネイティブに作成され、エンコードおよび圧縮されたデジタル画像を保存するベクタ描画画像ファイルです。このような描画ファイルは、テキスト、線、形状、画像、色、エフェクトを含み、画像コンテンツをベクタで表現します。このファイル形式の詳細はここで確認できます。 |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) は、ベクターグラフィックとビットマップグラフィックの両方を含む可能性がある図面画像ファイルです。このファイル形式の詳細はここで確認できます。 |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) は、テキスト、図面、画像、写真の組み合わせを含むスキャンされた文書や書籍向けに設計されたグラフィックファイル形式です。このファイル形式の詳細はここで確認できます。 |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) は、ベクターグラフィック（2D）、ラスタグラフィック、テキストの保存と交換のための無料でプラットフォームに依存しない国際標準メタファイル形式です。CGM はオブジェクト指向アプローチと多数の機能を備えて画像生成を行います。このファイル形式の詳細はここで確認できます。 |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language Document (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) は、グラフィックの設計と開発に使用される Adobe Photoshop のネイティブファイル形式です。このファイル形式の詳細はここで確認できます。 |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) は、グラフィックの設計と開発に使用される Photoshop Large Document Format を表します。このファイル形式の詳細はここで確認できます。 |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | DICOM Image (.dcm) は、MRI、CT スキャン、超音波画像など、患者の医療情報を保存するデジタル画像を表します。このファイル形式の詳細はここで確認できます。 |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | PostScript File (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Encapsulated PostScript File (.eps) は、単一ページの外観を記述する Encapsulated PostScript 言語プログラムを表します。このファイル形式の詳細はここで確認できます。 |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | OpenDocument Graphic File (.odg) は、Apache OpenOffice の Draw アプリケーションで描画要素をベクター画像として保存するために使用されます。このファイル形式の詳細はここで確認できます。 |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Flat XML ODF Template (.fodg) は、Apache OpenOffice の Draw アプリケーションで描画要素をベクター画像として保存するために使用されます。このファイル形式の詳細はここで確認できます。 |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Scalable Vector Graphics File (.svg) は、画像の外観を記述するために XML ベースのテキスト形式を使用する Scalable Vector Graphics ファイルです。このファイル形式の詳細はここで確認できます。 |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Scalable Vector Graphics File (.svgz) は、XML ベースのテキスト形式を使用し、GZIP で圧縮された Scalable Vector Graphics ファイルで、画像の外観を記述します。このファイル形式の詳細はここで確認できます。 |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | OpenDocument Graphic Template (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Hypertext Markup Language File (.htm) は、ブラウザで表示するために作成されたウェブページの拡張子です。このファイル形式の詳細はここで確認できます。 |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Hypertext Markup Language File (.html) は、ブラウザで表示するために作成されたウェブページの拡張子です。このファイル形式の詳細はここで確認できます。 |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | MHTML Web Archive (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | MIME HTML File (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | XML File (.xml)。GroupDocs.Viewer には XML ファイルを処理するための特別なプロセッサがあり、ドキュメントをご参照ください。 |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | OneNote Document (.one) は Microsoft OneNote アプリケーションで作成されます。OneNote は、メモを取るためのドラフトパッドのように情報を収集できるようにします。このファイル形式の詳細はここで確認できます。 |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Portable Document Format File (.pdf) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形で文書やその他の参照資料を表現する標準を導入することでした。このファイル形式の詳細はここで確認できます。 |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | XML Paper Specification File (.xps) は、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。この形式は Microsoft によって EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。このファイル形式の詳細はここで確認できます。 |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | OpenXPS File (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | LaTeX Source Document (.tex) は、プログラミング機能とマークアップ機能を備えた言語で、文書の組版に使用されます。このファイル形式の詳細はここで確認できます。 |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | GB/T 33190-2016 で定義された Open Fixed-layout Document (OFD) 形式は、中国の公共機関において PDF の代替を目指しています。 |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | PowerPoint プレゼンテーション (.ppt) は、スライドショーとして表示するためのスライドのコレクションで構成される PowerPoint ファイルを表します。Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定しています。このファイル形式の詳細については、こちらをご覧ください。 |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | PowerPoint Open XML プレゼンテーション (.pptx) は、人気のある Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。以前のバイナリ形式の PPT と異なり、PPTX 形式は Microsoft PowerPoint のオープン XML プレゼンテーション ファイル形式に基づいています。このファイル形式の詳細については、こちらをご覧ください。 |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | PowerPoint スライドショー (.pps) は、スライドショー目的で Microsoft PowerPoint を使用して作成されます。PPS ファイルの読み取りと作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細については、こちらをご覧ください。 |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | PowerPoint Open XML スライドショー (.ppsx) ファイルは、Microsoft PowerPoint 2007 以降でスライドショー目的に作成されます。このファイル形式の詳細については、こちらをご覧ください。 |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | OpenDocument プレゼンテーション (.odp) は、OpenOffice.org が OASIS Open 標準で使用するプレゼンテーション ファイル形式を表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | OpenDocument プレゼンテーション (.fodp) は、OpenDocument フラット XML プレゼンテーションを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint テンプレート (.pot) は、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML マクロ有効プレゼンテーションは、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ対応プレゼンテーション ファイルです。このファイル形式の詳細については、こちらをご覧ください。 |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML プレゼンテーション テンプレート (.potx) は、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーションを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML マクロ有効プレゼンテーション テンプレート (.potm) は、マクロをサポートする Microsoft PowerPoint テンプレート ファイルです。POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーション ファイルを作成するために使用できる既定設定が含まれています。このファイル形式の詳細については、こちらをご覧ください。 |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML マクロ有効スライド (.ppsm) は、Microsoft PowerPoint 2007 以降で作成されたマクロ対応スライドショー ファイル形式を表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument プレゼンテーション テンプレート (.otp) は、OASIS OpenDocument 標準形式のアプリケーションで作成されたプレゼンテーション テンプレート ファイルを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel スプレッドシート (.xls) は、Excel バイナリ ファイル形式を表します。このようなファイルは、Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシート プログラムでも作成できます。このファイル形式の詳細については、こちらをご覧ください。 |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) は、Excel バイナリ ファイル形式を表します。このようなファイルは、Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシート プログラムでも作成できます。このファイル形式の詳細については、こちらをご覧ください。 |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers は、Excel に似たバイナリ ファイル形式を表します。このようなファイルは Apple Numbers アプリケーションで作成できます。このファイル形式の詳細については、こちらをご覧ください。 |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML スプレッドシート (.xlsx) は、Microsoft Office 2007 のリリースとともに Microsoft が導入した、Microsoft Excel ドキュメント向けの広く知られた形式です。このファイル形式の詳細については、こちらをご覧ください。 |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML マクロ有効スプレッドシート (.xlsm) は、マクロをサポートするスプレッドシート ファイルの一種です。このファイル形式の詳細については、こちらをご覧ください。 |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel バイナリ スプレッドシート (.xlsb) は、Excel バイナリ ファイル形式を指定します。この形式は、Excel ブックの内容を定義するレコードと構造のコレクションです。このファイル形式の詳細については、こちらをご覧ください。 |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | カンマ区切り値ファイル (.csv) は、カンマで区切られた値を持つデータレコードを含むプレーンテキスト ファイルを表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | タブ区切り値ファイル (.tsv) は、タブで区切られたデータを含むプレーンテキスト形式を表します。このファイル形式の詳細については、こちらをご覧ください。 |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument スプレッドシート (.ods) は、ユーザーが編集可能な OpenDocument スプレッドシート ドキュメント形式を指します。データは ODF ファイル内に行と列として格納されます。このファイル形式の詳細については、こちらをご覧ください。 |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument フラット XML スプレッドシート (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument スプレッドシート テンプレート (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel アドイン (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel マクロ有効テンプレート (.xltm) は、Microsoft Excel がマクロ対応テンプレート ファイルとして生成するファイルを表します。XLTM ファイルは構造上 XLTX と類似していますが、後者はマクロ付きテンプレート ファイルの作成をサポートしていません。このファイル形式の詳細については、こちらをご覧ください。 |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel テンプレート (.xlt) は、Microsoft Excel で作成されたテンプレート ファイルです。Microsoft Excel は、Microsoft Office スイートの一部であるスプレッドシート アプリケーションです。Microsoft Office 97-2003 は、新しい XLT ファイルの作成とこれらのファイルの開封をサポートしていました。このファイル形式の詳細については、こちらをご覧ください。 |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML スプレッドシート テンプレート (.xltx) は、Office OpenXML ファイル形式仕様に基づく Microsoft Excel テンプレートを表します。これは、XLTX ファイルで指定された設定と同じ設定を持つ XLSX ファイルを生成するために使用できる標準テンプレート ファイルを作成するために使用されます。このファイル形式の詳細については、こちらをご覧ください。 |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc スプレッドシート (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project ファイル (.mpp) は、プロジェクト管理に関する情報を統合的に保存する Microsoft Project データ ファイルです。このファイル形式の詳細については、こちらをご覧ください。 |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project テンプレート (.mpt) には、.MPP ファイルを作成するための基本情報と構造、およびドキュメント設定が含まれています。このファイル形式の詳細については、こちらをご覧ください。 |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange ファイル (.mpx) は、Microsoft Project (MSP) と、Primavera Project Planner、Sciforma、Timerline Precision Estimating など MPX ファイル形式をサポートする他のアプリケーション間でプロジェクト情報を転送するための ASCII ファイル形式です。このファイル形式の詳細については、こちらをご覧ください。 |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ActionScript ファイル (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ActionScript ファイル (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | アセンブリ言語 ソースコード ファイル (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | DOS バッチ ファイル (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | C/C++ ソースコード ファイル (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | C++ ソースコード ファイル (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | CMake ファイル (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | C++ ソースコード ファイル (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C# ソースコード ファイル (.cs) は、C# プログラミング言語用のソースコード ファイルです。Microsoft が .NET Framework での使用のために導入しました。このファイル形式の詳細については、こちらをご覧ください。 |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic プロジェクト アイテム ファイル (.vb) は、Microsoft が .NET アプリケーションの開発用に作成した Visual Basic 言語で作成されたソースコード ファイルです。このファイル形式の詳細については、こちらをご覧ください。 |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | カスケーディング スタイル シート (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | C++ ソースコード ファイル (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | パッチ ファイル (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby ERB スクリプト (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Groovy ソースコード ファイル (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | C/C++/Objective-C ヘッダー ファイル (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Haml ソースコード ファイル (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | C++ ヘッダー ファイル (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Java ソースコード ファイル (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | JavaScript ファイル (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | JavaScript オブジェクト表記ファイル (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS スタイルシート (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | ログファイル (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Objective-C 実装ファイル (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Xcode Makefile スクリプト (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Markdown ドキュメントファイル (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ML ソースコードファイル (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Objective-C++ ソースファイル (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | PHP ソースコードファイル (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Perl スクリプト (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Java プロパティファイル (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Python スクリプト (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Ruby ソースコード (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | reStructuredText ファイル (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Syntactically Awesome StyleSheets ファイル (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Scala ソースコードファイル (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Scheme ソースコードファイル (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | 汎用スクリプトファイル (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Bash シェルスクリプト (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Standard ML ソースコードファイル (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Structured Query Language データファイル (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Vim 設定ファイル (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | YAML ドキュメント (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word ドキュメント (.doc) は、Microsoft Word または他のワードプロセッシングソフトで生成された文書をバイナリファイル形式で表します。こちらでこのファイル形式の詳細をご確認ください。 |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML ドキュメント (.docx) は、Microsoft Word 文書のよく知られた形式です。2007 年に Microsoft Office 2007 がリリースされた際に導入され、この新しいドキュメント形式の構造は、従来のバイナリ形式から XML とバイナリファイルの組み合わせに変更されました。こちらでこのファイル形式の詳細をご覧ください。 |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help File (.chm) は、HELP（アプリケーションのドキュメント）文書に使用されるよく知られた形式です。このファイル形式の詳細は、こちらで確認できます。 |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML Macro-Enabled Document (.docm) は、Microsoft Word 2007 以降で作成された、マクロを実行できる文書です。このファイル形式の詳細は、こちらで確認できます。 |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word Document Template (.dot) は、Microsoft Word が作成するテンプレートファイルで、今後生成される DOC または DOCX ファイルのために事前に書式設定された設定を保持します。このファイル形式の詳細は、こちらで確認できます。 |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) は、Microsoft Word が作成するテンプレートファイルで、今後生成される DOCX ファイルのために事前に書式設定された設定を保持します。このファイル形式の詳細は、こちらで確認できます。 |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。このファイル形式の詳細は、こちらで確認できます。 |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) は、アプリケーション内で使用するための書式設定されたテキストとグラフィックをエンコードする方法を表します。このファイル形式の詳細は、こちらで確認できます。 |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) は、行単位のプレーンテキストを含むテキスト文書を表します。このファイル形式の詳細は、こちらで確認できます。 |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) は、OpenDocument Text File 形式に基づくワードプロセッシングアプリケーションで作成される文書のタイプです。このファイル形式の詳細は、こちらで確認できます。 |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) は、OASIS の OpenDocument 標準形式に準拠したアプリケーションによって生成されるテンプレート文書を表します。このファイル形式の詳細は、こちらで確認できます。 |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) は、連絡先情報を保存するためのデジタルファイル形式です。この形式は、一般的な情報交換アプリケーション間でのデータ交換に広く使用されています。このファイル形式の詳細は、こちらで確認できます。 |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) は、Adobe Illustrator の図面用ファイル形式です。このファイル形式の詳細は、こちらで確認できます。 |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) は、PowerShell モジュールスクリプト用のファイル形式です。このファイル形式の詳細は、こちらで確認できます。 |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) は、Windows PowerShell Cmdlet ファイル用のファイル形式です。このファイル形式の詳細は、こちらで確認できます。 |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) は、PowerShell モジュールマニフェストスクリプト用のファイル形式です。このファイル形式の詳細は、こちらで確認できます。 |

### 例

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# ドキュメントを読み込む際にファイルタイプ（例: Markdown）を指定してください
load_options = LoadOptions(FileType.MD)

# ドキュメントを PDF にレンダリングする
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### 参照
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
