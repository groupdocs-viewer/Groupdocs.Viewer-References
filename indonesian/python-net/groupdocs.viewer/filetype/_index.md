---
title: "Kelas FileType"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili tipe file dan menyediakan metode untuk memperoleh daftar semua tipe file yang didukung oleh GroupDocs.Viewer."
type: docs
url: /id/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Mewakili tipe file dan menyediakan metode untuk memperoleh daftar semua tipe file yang didukung oleh GroupDocs.Viewer.

Tipe FileType menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Menginisialisasi instance baru dari [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Menginisialisasi instance FileType baru. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Mendeteksi enkoding file teks TXT, TSV, dan CSV berdasarkan path. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Mencoba mendeteksi enkoding file teks (TXT, TSV, CSV) dari aliran. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Menentukan apakah [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) saat ini sama dengan [`FileType`] yang ditentukan. |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Menentukan apakah [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) saat ini sama dengan objek yang ditentukan. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Memetakan ekstensi file ke tipe file. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Mengekstrak ekstensi file dan memetakannya ke tipe file. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Memetakan tipe media file ke [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (misalnya, 'application/pdf' dipetakan ke [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Mendeteksi tipe file dengan membaca tanda tangan file. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Mendeteksi tipe file dengan membaca tanda tangan file. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Mendeteksi tipe file dengan membaca tanda tangan file. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Mendeteksi tipe file dengan membaca tanda tangan file. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Mengembalikan kode hash untuk objek [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) saat ini. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Mengambil tipe file yang didukung. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Mengembalikan string yang merepresentasikan objek saat ini. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Akhiran nama file (termasuk titik ".") misalnya ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | Nama tipe file misalnya "Microsoft Word Document". |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Mewakili tipe file yang tidak diketahui. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | File Zip (.zip) mewakili arsip yang dapat menyimpan satu atau lebih file atau direktori. Pelajari lebih lanjut tentang format file ini di sini. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Arsip File Unix Terpadu (.tar) adalah arsip yang dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. Pelajari lebih lanjut tentang format file ini di sini. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | File XZ (.xz) adalah arsip yang dikompresi dengan algoritma kompresi rasio tinggi berbasis algoritma LZMA. Pelajari lebih lanjut tentang format file ini di sini. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Arsip File Unix Terpadu (.txz, .tar.xz) adalah arsip yang dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. Pelajari lebih lanjut tentang format file ini di sini. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Arsip File Unix Terpadu (.txz, .tar.xz) adalah arsip yang dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. Pelajari lebih lanjut tentang format file ini di sini. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Arsip File Unix Terpadu (.tgz, .tar.gz) adalah arsip yang dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. Pelajari lebih lanjut tentang format file ini di sini. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Arsip File Unix Terpadu (.tgz, .tar.gz) adalah arsip yang dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. Pelajari lebih lanjut tentang format file ini di sini. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | File Terkompresi Bzip2 (.bz2) adalah file terkompresi yang dihasilkan menggunakan metode kompresi sumber terbuka BZIP2, biasanya pada sistem UNIX atau Linux. Pelajari lebih lanjut tentang format file ini di sini. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) adalah file terkompresi yang dihasilkan menggunakan metode kompresi RAR (WINRAR). Pelajari lebih lanjut tentang format file ini di sini. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) adalah file terkompresi yang dibuat dengan aplikasi kompresi gzip. File ini dapat berisi beberapa file terkompresi dan biasanya digunakan pada sistem UNIX dan Linux. Pelajari lebih lanjut tentang format file ini di sini. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) diperkenalkan sebagai utilitas gratis untuk menggantikan program Compress yang digunakan pada sistem Unix. File semacam itu dapat dibuka dan diekstrak dengan beberapa aplikasi seperti WinZip yang tersedia di Windows maupun MacOS. Pelajari lebih lanjut tentang format file ini di sini. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) adalah pengarsip sumber terbuka gratis dengan kompresi LZMA dan LZMA2. Pelajari lebih lanjut tentang format file ini di sini. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio adalah utilitas pengarsip file umum beserta format file yang terkait. Utilitas ini terutama dipasang pada sistem operasi komputer mirip Unix. Pelajari lebih lanjut tentang format file ini di sini. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | File ZST adalah file terkompresi yang dihasilkan dengan algoritma kompresi Zstandard (zstd). Ini adalah file terkompresi yang dibuat dengan kompresi lossless oleh algoritma tersebut. File ZST dapat digunakan untuk mengompresi berbagai jenis file seperti basis data, sistem file, jaringan, dan permainan. Pelajari lebih lanjut tentang format file ini di sini. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | File TZST (.tar.zst, .tzst) adalah arsip Zstandard (ZST), yang secara internal berisi Consolidated Unix File Archive (Tar), dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | File TZST (.tar.zst, .tzst) adalah arsip Zstandard (ZST), yang secara internal berisi Consolidated Unix File Archive (Tar), dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO optical disc image adalah file gambar disk arsip yang tidak terkompresi yang mewakili seluruh isi data pada disc optik seperti CD atau DVD, berdasarkan standar ISO-9660. Pelajari lebih lanjut tentang format file ini di sini. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA atau LZH adalah utilitas kompresi freeware dan format file yang terkait. Pelajari lebih lanjut tentang format file ini di sini. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (atau CAB) adalah format file arsip untuk Microsoft Windows. Pelajari lebih lanjut tentang format file ini di sini. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) adalah representasi data bertag dari file gambar AutoCAD. Pelajari lebih lanjut tentang format file ini di sini. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) mewakili file biner proprietari yang digunakan untuk menyimpan data desain 2D dan 3D. Seperti DXF, yang merupakan file ASCII, DWG mewakili format file biner untuk gambar CAD (Computer Aided Design). Pelajari lebih lanjut tentang format file ini di sini. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt) adalah file templat gambar AutoCAD yang digunakan sebagai awal untuk membuat gambar yang dapat disimpan sebagai file DWG. Pelajari lebih lanjut tentang format file ini di sini. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl) adalah format file yang dapat dipertukarkan yang mewakili geometri permukaan tiga dimensi. Format file ini digunakan dalam beberapa bidang seperti prototyping cepat, pencetakan 3D, dan manufaktur berbantuan komputer. Pelajari lebih lanjut tentang format file ini di sini. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc) adalah format file yang menetapkan standar internasional untuk mengimpor dan mengekspor objek bangunan serta propertinya. Format file ini menyediakan interoperabilitas antara berbagai aplikasi perangkat lunak. Pelajari lebih lanjut tentang format file ini di sini. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format File (.dwf) mewakili gambar 2D/3D dalam format terkompresi untuk melihat, meninjau, atau mencetak file desain. File ini berisi grafik dan teks sebagai bagian dari data desain serta mengurangi ukuran file karena format terkompresinya. Pelajari lebih lanjut tentang format file ini di sini. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) mewakili format model 3D. Pelajari lebih lanjut tentang format file ini di sini. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) mewakili gambar 2D/3D sebagai dokumen XPS dalam format terkompresi untuk melihat, meninjau, atau mencetak file desain. File ini berisi grafik dan teks sebagai bagian dari data desain serta mengurangi ukuran file karena format terkompresinya. Pelajari lebih lanjut tentang format file ini di sini. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) adalah gambar yang dibuat dan didukung oleh aplikasi CAD seperti MicroStation dan Intergraph Interactive Graphics Design System. Pelajari lebih lanjut tentang format file ini di sini. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) adalah file plotter berbasis vektor yang diperkenalkan oleh Autodesk, Inc. dan berisi informasi untuk file CAD tertentu. Detail plotting memerlukan akurasi dan presisi dalam produksi, dan penggunaan file PLT menjamin hal ini karena semua gambar dicetak menggunakan garis bukan titik. Pelajari lebih lanjut tentang format file ini di sini. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | File Format Umum Pelajari lebih lanjut tentang format file ini di sini. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) adalah file gambar 3D yang diperkenalkan oleh Wavefront Technologies. Pelajari lebih lanjut tentang format file ini di sini. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) adalah gambar yang dibuat dengan aplikasi Microsoft Visio untuk merepresentasikan berbagai objek grafis dan interkoneksi di antaranya. Pelajari lebih lanjut tentang format file ini di sini. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013. Format ini dikembangkan untuk menggantikan format file biner, .VSD, yang didukung oleh versi Microsoft Visio sebelumnya. Pelajari lebih lanjut tentang format file ini di sini. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) adalah file stensil yang dibuat dengan Microsoft Visio 2007 dan versi sebelumnya. File stensil menyediakan objek gambar yang dapat dimasukkan ke dalam gambar Visio .VSD. Pelajari lebih lanjut tentang format file ini di sini. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Format file VSSX dapat dibuka dengan Visio 2013 ke atas. File Visio dikenal untuk merepresentasikan berbagai elemen gambar seperti kumpulan bentuk, konektor, diagram alur, tata letak jaringan, diagram UML. Pelajari lebih lanjut tentang format file ini di sini. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. File VSDM adalah gambar OPC/XML yang mirip dengan VSDX, tetapi juga menyediakan kemampuan menjalankan makro saat file dibuka. Pelajari lebih lanjut tentang format file ini di sini. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) adalah file gambar vektor yang dibuat dengan Microsoft Visio dan berfungsi sebagai templat untuk membuat file selanjutnya. File templat ini berformat biner dan berisi tata letak serta pengaturan default yang digunakan untuk membuat gambar Visio baru. Pelajari lebih lanjut tentang format file ini di sini. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) adalah file templat gambar yang dibuat dengan Microsoft Visio 2013 ke atas. File VSTX ini menyediakan titik awal untuk membuat gambar Visio, disimpan sebagai file .VSDX, dengan tata letak dan pengaturan default. Pelajari lebih lanjut tentang format file ini di sini. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) adalah file templat yang dibuat dengan Microsoft Visio yang mendukung makro. Tidak seperti file VSDX, file yang dibuat dari templat VSTM dapat menjalankan makro yang dikembangkan dalam kode Visual Basic for Applications (VBA). Pelajari lebih lanjut tentang format file ini di sini. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) adalah file Stencil Microsoft Visio yang mendukung makro. File VSSM ketika dibuka memungkinkan menjalankan makro untuk mencapai format dan penempatan bentuk yang diinginkan dalam diagram. Pelajari lebih lanjut tentang format file ini di sini. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) mengacu pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. File VSX disimpan dalam format file XML dan didukung hingga Visio 2013. Pelajari lebih lanjut tentang format file ini di sini. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) adalah templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Templat ini bertujuan menyediakan file dengan pengaturan dasar yang dapat digunakan untuk membuat banyak file Visio dengan pengaturan yang sama. Pelajari lebih lanjut tentang format file ini di sini. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) mewakili format file yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar Web. Pelajari lebih lanjut tentang format file ini di sini. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) mewakili setiap gambar atau diagram yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML dengan ekstensi .VDX. File XML gambar Visio dibuat dalam perangkat lunak Visio, yang dikembangkan oleh Microsoft. Pelajari lebih lanjut tentang format file ini di sini. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub) adalah format file e-book yang menyediakan format publikasi digital standar untuk penerbit dan konsumen. Format ini kini sangat umum sehingga didukung oleh banyak e-reader dan aplikasi perangkat lunak. Pelajari lebih lanjut tentang format file ini di sini. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi) adalah salah satu format file ebook yang paling banyak digunakan. Format ini merupakan peningkatan dari format OEB (Open Ebook Format) lama dan digunakan sebagai format proprietari untuk Mobipocket Reader. Pelajari lebih lanjut tentang format file ini di sini. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) ebook adalah format file digital yang dikembangkan untuk perangkat Amazon Kindle. Format ini merupakan peningkatan dari file AZW lama dan hanya digunakan pada perangkat Kindle Fire dengan kompatibilitas mundur untuk format file leluhur yaitu MOBI dan AZW. Pelajari lebih lanjut tentang format file ini di sini. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya. Pelajari lebih lanjut tentang format file ini di sini. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E-Mail Message (.eml) mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. Hampir semua klien email mendukung format file ini karena kepatuhannya terhadap Standar Format Pesan Internet RFC-822. Pelajari lebih lanjut tentang format file ini di sini. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) Pelajari lebih lanjut tentang format file ini di sini. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) Pelajari lebih lanjut tentang format file ini di sini. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx) diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email. Pelajari lebih lanjut tentang format file ini di sini. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst) mewakili Outlook Personal Storage Files (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna. Pelajari lebih lanjut tentang format file ini di sini. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost) mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini di sini. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) mewakili gambar raster yang ditujukan untuk penggunaan pada berbagai perangkat yang mematuhi standar format file ini. Format ini mampu menggambarkan data gambar blevel, skala abu-abu, palet-warna, dan warna penuh dalam beberapa ruang warna. Pelajari lebih lanjut tentang format file ini di sini. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) mewakili gambar raster yang ditujukan untuk penggunaan pada berbagai perangkat yang mematuhi standar format file ini. Format ini mampu menggambarkan data gambar blevel, skala abu-abu, palet-warna, dan warna penuh dalam beberapa ruang warna. Pelajari lebih lanjut tentang format file ini di sini. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG Image (.jpg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar hasil, sebagai akibat kompresi, merupakan kompromi antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini di sini. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG Image (.jpeg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar hasil, sebagai akibat kompresi, merupakan kompromi antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini di sini. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif) adalah gambar yang dikembangkan untuk pertukaran cepat antar platform. Format ini menggunakan kompresi JPEG. Pelajari lebih lanjut tentang format file ini di sini. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png) adalah jenis format file gambar raster yang menggunakan kompresi lossless. Format file ini dibuat sebagai pengganti Graphics Interchange Format (GIF) dan tidak memiliki batasan hak cipta. Pelajari lebih lanjut tentang format file ini di sini. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format File (.gif) adalah jenis gambar yang sangat terkompresi. Untuk setiap gambar, GIF biasanya memungkinkan hingga 8 bit per piksel dan hingga 256 warna diizinkan di seluruh gambar. Pelajari lebih lanjut tentang format file ini di sini. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng) adalah ekstensi dari format PNG yang mendukung animasi. Pelajari lebih lanjut tentang format file ini di sini. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | File Gambar Bitmap (.bmp) digunakan untuk menyimpan gambar digital bitmap. Gambar ini independen dari adaptor grafis dan juga disebut format file bitmap independen perangkat (DIB). Pelajari lebih lanjut tentang format file ini di sini. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) digunakan untuk menyimpan gambar digital bitmap yang dikembangkan oleh TRUEVISION. Pelajari lebih lanjut tentang format file ini di sini. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | File Ikon (.ico) adalah jenis file gambar yang digunakan sebagai ikon untuk representasi aplikasi pada Microsoft Windows. Pelajari lebih lanjut tentang format file ini di sini. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | File Gambar Inti JPEG 2000 (.jp2) adalah sistem pengkodean gambar dan standar kompresi gambar mutakhir. Pelajari lebih lanjut tentang format file ini di sini. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | File Gambar JPEG 2000 (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | File Gambar JPEG 2000 (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | File Gambar JPEG 2000 (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | Aliran Kode JPEG 2000 (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | Aliran Kode JPEG 2000 (.j2k) adalah gambar yang dikompresi menggunakan kompresi wavelet alih-alih kompresi DCT. Pelajari lebih lanjut tentang format file ini di sini. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | Aliran Kode JPEG 2000 (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | File Bitmap Independen Perangkat (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) mewakili Microsoft Windows Metafile (WMF) untuk menyimpan data gambar format vektor maupun bitmap. Pelajari lebih lanjut tentang format file ini di sini. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) mewakili Microsoft Windows Metafile (WMF) yang dikompresi dalam arsip GZIP - untuk menyimpan data gambar format vektor maupun bitmap. Pelajari lebih lanjut tentang format file ini di sini. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) mewakili gambar grafis secara independen perangkat. Metafile EMF terdiri dari rekaman berukuran variabel dalam urutan kronologis yang dapat menampilkan gambar yang disimpan setelah diparsing pada perangkat keluaran apa pun. Pelajari lebih lanjut tentang format file ini di sini. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile terkompresi (.emz) mewakili gambar grafis secara independen perangkat yang dikompresi oleh GZIP. Metafile EMF terdiri dari rekaman berukuran variabel dalam urutan kronologis yang dapat menampilkan gambar yang disimpan setelah diparsing pada perangkat keluaran apa pun. Pelajari lebih lanjut tentang format file ini di sini. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp) adalah format file gambar raster web modern yang berbasis pada kompresi lossless dan lossy. Ini memberikan kualitas gambar yang sama sambil secara signifikan mengurangi ukuran gambar. Pelajari lebih lanjut tentang format file ini di sini. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Spesifikasi Digital Negative (.dng) adalah format gambar kamera digital yang digunakan untuk penyimpanan file mentah. Format ini dikembangkan oleh Adobe pada September 2004. Pada dasarnya dikembangkan untuk fotografi digital. Pelajari lebih lanjut tentang format file ini di sini. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) adalah file gambar vektor yang secara native dibuat dengan CorelDRAW untuk menyimpan gambar digital yang dikodekan dan dikompresi. File gambar ini berisi teks, garis, bentuk, gambar, warna, dan efek untuk representasi vektor dari konten gambar. Pelajari lebih lanjut tentang format file ini di sini. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) adalah file gambar yang dapat berisi grafik vektor maupun grafik bitmap. Pelajari lebih lanjut tentang format file ini di sini. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) adalah format file grafis yang ditujukan untuk dokumen dan buku yang dipindai, terutama yang mengandung kombinasi teks, gambar, dan foto. Pelajari lebih lanjut tentang format file ini di sini. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) adalah format metafile standar internasional yang gratis, platform-independen untuk menyimpan dan bertukar grafik vektor (2D), grafik raster, dan teks. CGM menggunakan pendekatan berorientasi objek dan banyak fungsi untuk produksi gambar. Pelajari lebih lanjut tentang format file ini di sini. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language Dokumen (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) mewakili format file asli Adobe Photoshop yang digunakan untuk perancangan dan pengembangan grafis. Pelajari lebih lanjut tentang format file ini di sini. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) mewakili Photoshop Large Document Format yang digunakan untuk perancangan dan pengembangan grafis. Pelajari lebih lanjut tentang format file ini di sini. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | Gambar DICOM (.dcm) mewakili gambar digital yang menyimpan informasi medis pasien seperti MRI, pemindaian CT, dan gambar ultrasonik. Pelajari lebih lanjut tentang format file ini di sini. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | File PostScript (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | File Encapsulated PostScript (.eps) menjelaskan program bahasa Encapsulated PostScript yang menggambarkan tampilan satu halaman. Pelajari lebih lanjut tentang format file ini di sini. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | File Grafik OpenDocument (.odg) digunakan oleh aplikasi Draw Apache OpenOffice untuk menyimpan elemen gambar sebagai gambar vektor. Pelajari lebih lanjut tentang format file ini di sini. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Templat ODF XML Datar (.fodg) digunakan oleh aplikasi Draw Apache OpenOffice untuk menyimpan elemen gambar sebagai gambar vektor. Pelajari lebih lanjut tentang format file ini di sini. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | File Scalable Vector Graphics (.svg) adalah file Scalar Vector Graphics yang menggunakan format teks berbasis XML untuk menggambarkan tampilan sebuah gambar. Pelajari lebih lanjut tentang format file ini di sini. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | File Scalable Vector Graphics (.svgz) adalah file Scalar Vector Graphics yang menggunakan format teks berbasis XML, dikompresi dengan GZIP untuk menggambarkan tampilan sebuah gambar. Pelajari lebih lanjut tentang format file ini di sini. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | Templat Grafik OpenDocument (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | File Hypertext Markup Language (.htm) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. Pelajari lebih lanjut tentang format file ini di sini. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | File Hypertext Markup Language (.html) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. Pelajari lebih lanjut tentang format file ini di sini. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | Arsip Web MHTML (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | File MIME HTML (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | File XML (.xml). GroupDocs.Viewer memiliki prosesor khusus untuk menangani file XML, lihat dokumentasi. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | Dokumen OneNote (.one) dibuat oleh aplikasi Microsoft OneNote. OneNote memungkinkan Anda mengumpulkan informasi menggunakan aplikasi tersebut seolah-olah Anda menggunakan buku catatan untuk mencatat. Pelajari lebih lanjut tentang format file ini di sini. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | File Portable Document Format (.pdf) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang format file ini di sini. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | File XML Paper Specification (.xps) mewakili file tata letak halaman yang berbasis pada XML Paper Specifications yang dibuat oleh Microsoft. Format ini dikembangkan oleh Microsoft sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen. Pelajari lebih lanjut tentang format file ini di sini. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | File OpenXPS (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | Dokumen Sumber LaTeX (.tex) adalah bahasa yang mencakup fitur pemrograman serta penandaan, digunakan untuk menyusun dokumen. Pelajari lebih lanjut tentang format file ini di sini. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Format Dokumen Tata Letak Tetap Terbuka (OFD) yang didefinisikan oleh GB/T 33190-2016 bertujuan menggantikan PDF di institusi publik China |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | Presentasi PowerPoint (.ppt) mewakili file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Binary File Format yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini di sini. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | Presentasi Open XML PowerPoint (.pptx) adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Tidak seperti versi sebelumnya dari format file presentasi PPT yang berbentuk biner, format PPTX didasarkan pada format file presentasi open XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini di sini. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | Slide Show PowerPoint (.pps) dibuat menggunakan Microsoft PowerPoint untuk keperluan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini di sini. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | Slide Show Open XML PowerPoint (.ppsx) dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk keperluan Slide Show. Pelajari lebih lanjut tentang format file ini di sini. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | Presentasi OpenDocument (.odp) mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen. Pelajari lebih lanjut tentang format file ini di sini. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | Presentasi OpenDocument (.fodp) mewakili OpenDocument Flat XML Presentation. Pelajari lebih lanjut tentang format file ini di sini. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint Template (.pot) mewakili file templat Microsoft PowerPoint yang dibuat oleh versi PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini di sini. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation adalah file Presentasi yang mendukung makro yang dibuat dengan Microsoft PowerPoint 2007 atau versi yang lebih tinggi. Pelajari lebih lanjut tentang format file ini di sini. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx) mewakili templat presentasi Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 ke atas. Pelajari lebih lanjut tentang format file ini di sini. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) adalah file templat Microsoft PowerPoint dengan dukungan Makro. File POTM dibuat dengan PowerPoint 2007 atau lebih tinggi dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut. Pelajari lebih lanjut tentang format file ini di sini. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) mewakili format file Slide Show yang mendukung makro yang dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini di sini. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp) mewakili file templat presentasi yang dibuat oleh aplikasi dalam format standar OASIS OpenDocument. Pelajari lebih lanjut tentang format file ini di sini. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls) mewakili Format File Biner Excel. File semacam itu dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini di sini. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) mewakili Format File Biner Excel. File semacam itu dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini di sini. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers mewakili Format File Biner mirip Excel. File semacam itu dapat dibuat oleh aplikasi Apple Numbers. Pelajari lebih lanjut tentang format file ini di sini. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) adalah format yang terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft pada rilis Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini di sini. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) adalah jenis file Spreadsheet yang mendukung makro. Pelajari lebih lanjut tentang format file ini di sini. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) menentukan Format File Biner Excel, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini di sini. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. Pelajari lebih lanjut tentang format file ini di sini. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Pelajari lebih lanjut tentang format file ini di sini. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) merupakan format Dokumen Spreadsheet OpenDocument yang dapat diedit oleh pengguna. Data disimpan di dalam file ODF dalam baris dan kolom. Pelajari lebih lanjut tentang format file ini di sini. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm) mewakili file yang dihasilkan oleh Microsoft Excel sebagai file templat yang mendukung makro. File XLTM mirip dengan XLTX dalam struktur kecuali yang terakhir tidak mendukung pembuatan file templat dengan makro. Pelajari lebih lanjut tentang format file ini di sini. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Template (.xlt) adalah file templat yang dibuat dengan Microsoft Excel, yaitu aplikasi spreadsheet yang merupakan bagian dari paket Microsoft Office. Microsoft Office 97-2003 mendukung pembuatan file XLT baru serta membuka file tersebut. Pelajari lebih lanjut tentang format file ini di sini. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Spreadsheet Template (.xltx) mewakili Templat Microsoft Excel yang berbasis pada spesifikasi format file Office OpenXML. Templat ini digunakan untuk membuat file templat standar yang dapat digunakan untuk menghasilkan file XLSX yang memiliki pengaturan yang sama seperti yang ditentukan dalam file XLTX. Pelajari lebih lanjut tentang format file ini di sini. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project File (.mpp) adalah file data Microsoft Project yang menyimpan informasi terkait manajemen proyek secara terintegrasi. Pelajari lebih lanjut tentang format file ini di sini. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project Template (.mpt) berisi informasi dasar dan struktur serta pengaturan dokumen untuk membuat file .MPP. Pelajari lebih lanjut tentang format file ini di sini. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange file (.mpx) adalah format file ASCII untuk mentransfer informasi proyek antara Microsoft Project (MSP) dan aplikasi lain yang mendukung format file MPX seperti Primavera Project Planner, Sciforma, dan Timerline Precision Estimating. Pelajari lebih lanjut tentang format file ini di sini. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | File ActionScript (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | File ActionScript (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | File Kode Sumber Assembly Language (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | File Batch DOS (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | File Kode Sumber C/C++ (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | File Kode Sumber C++ (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | File CMake (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | File Kode Sumber C++ (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C# File Kode Sumber (.cs) adalah file kode sumber untuk bahasa pemrograman C#. Diperkenalkan oleh Microsoft untuk digunakan dengan .NET Framework. Pelajari lebih lanjut tentang format file ini di sini. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic Project Item File (.vb) adalah file kode sumber yang dibuat dalam bahasa Visual Basic yang dikembangkan oleh Microsoft untuk pengembangan aplikasi .NET. Pelajari lebih lanjut tentang format file ini di sini. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Cascading Style Sheet (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | File Kode Sumber C++ (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | File Patch (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby ERB Skrip (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | File Kode Sumber Groovy (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | File Header C/C++/Objective-C (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | File Kode Sumber Haml (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | File Header C++ (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | File Kode Sumber Java (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | File JavaScript (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | File JavaScript Object Notation (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS Lembar Gaya (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | File Log (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | File Implementasi Objective-C (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Skrip Makefile Xcode (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | File Dokumentasi Markdown (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | File Kode Sumber ML (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | File Kode Sumber Objective-C++ (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | File Kode Sumber PHP (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Skrip Perl (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | File Properti Java (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Skrip Python (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Kode Sumber Ruby (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | File reStructuredText (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | File Syntactically Awesome StyleSheets (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | File Kode Sumber Scala (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | File Kode Sumber Scheme (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | File Skrip Generik (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Skrip Bash Shell (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | File Kode Sumber Standard ML (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | File Data Structured Query Language (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | File Pengaturan Vim (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | Dokumen YAML (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word Document (.doc) mewakili dokumen yang dihasilkan oleh Microsoft Word atau program pengolah kata lainnya dalam format berkas biner. Pelajari lebih lanjut tentang format berkas ini di sini. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML Document (.docx) adalah format yang terkenal untuk dokumen Microsoft Word. Diperkenalkan sejak 2007 dengan rilis Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format berkas ini di sini. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help File (.chm) adalah format yang terkenal untuk dokumen HELP (dokumentasi untuk suatu aplikasi). Pelajari lebih lanjut tentang format berkas ini di sini. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML Macro-Enabled Document (.docm) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro. Pelajari lebih lanjut tentang format berkas ini di sini. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word Document Template (.dot) adalah file templat yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOC atau DOCX selanjutnya. Pelajari lebih lanjut tentang format berkas ini di sini. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) adalah file templat yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini di sini. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) merupakan file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru. Pelajari lebih lanjut tentang format file ini di sini. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) merupakan metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini di sini. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) merupakan dokumen teks yang berisi teks polos dalam bentuk baris. Pelajari lebih lanjut tentang format file ini di sini. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format OpenDocument Text File. Pelajari lebih lanjut tentang format file ini di sini. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) merupakan dokumen templat yang dihasilkan oleh aplikasi yang mematuhi format standar OpenDocument milik OASIS. Pelajari lebih lanjut tentang format file ini di sini. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) adalah format file digital untuk menyimpan informasi kontak. Format ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi yang populer. Pelajari lebih lanjut tentang format file ini di sini. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) adalah format file untuk gambar Adobe Illustrator. Pelajari lebih lanjut tentang format file ini di sini. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) adalah format file untuk skrip modul PowerShell. Pelajari lebih lanjut tentang format file ini di sini. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) adalah format file untuk file Cmdlet Windows PowerShell. Pelajari lebih lanjut tentang format file ini di sini. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) adalah format file untuk skrip manifes modul PowerShell. Pelajari lebih lanjut tentang format file ini di sini. |

### Contoh

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Tentukan jenis file (mis., Markdown) saat memuat dokumen
load_options = LoadOptions(FileType.MD)

# Render dokumen ke PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Lihat Juga
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
