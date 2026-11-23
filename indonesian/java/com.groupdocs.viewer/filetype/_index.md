---
title: "FileType"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili tipe file."
type: docs
weight: 14
url: /id/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Mewakili tipe file. Menyediakan metode untuk memperoleh daftar semua tipe file yang didukung oleh komponen GroupDocs.Viewer.


Enum FileType menyediakan konstanta yang mewakili berbagai tipe file yang didukung oleh komponen GroupDocs.Viewer.
Anda dapat menggunakan metode dalam enum ini untuk memperoleh daftar semua tipe file yang didukung atau memeriksa apakah tipe file tertentu didukung.


Contoh penggunaan:

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


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Mewakili tipe file yang tidak diketahui. |
|
|  | [ZIP](#ZIP) | Mewakili file zip (.zip) yang dapat berisi satu atau lebih file atau direktori. |
|
|  | [TAR](#TAR) | Mewakili arsip file Unix terkompresi (.tar) yang dibuat untuk mengumpulkan satu atau lebih file. |
|
|  | [XZ](#XZ) | Mewakili file XZ (.xz) yang dikompresi menggunakan algoritma kompresi rasio tinggi berbasis algoritma LZMA. |
|
|  | [TXZ](#TXZ) | Mewakili arsip file Unix terintegrasi (.txz, .tar.xz) yang dibuat untuk mengumpulkan satu atau lebih file. |
|
|  | [TARXZ](#TARXZ) | Mewakili arsip file Unix terintegrasi (.txz, .tar.xz) yang dibuat untuk mengumpulkan satu atau lebih file. |
|
|  | [TGZ](#TGZ) | Mewakili arsip file Unix terintegrasi (.tgz, .tar.gz) yang dibuat untuk mengumpulkan satu atau lebih file. |
|
|  | [TARGZ](#TARGZ) | Mewakili arsip file Unix terintegrasi (.tgz, .tar.gz) yang dibuat untuk mengumpulkan satu atau lebih file. |
|
|  | [BZ_2](#BZ-2) | Mewakili file terkompresi Bzip2 (.bz2) yang dihasilkan menggunakan metode kompresi sumber terbuka BZIP2. |
|
|  | [RAR](#RAR) | Mewakili file terkompresi Roshal Archive (.rar) yang dihasilkan menggunakan metode kompresi RAR (WINRAR versi 4). |
|
|  | [GZ](#GZ) | Mewakili file Gnu Zipped (.gz) yang terkompresi dibuat dengan aplikasi kompresi gzip. |
|
|  | [GZIP](#GZIP) | Mewakili file Gnu Zipped (.gzip) yang terkompresi diperkenalkan sebagai utilitas gratis untuk menggantikan program Compress yang digunakan di sistem Unix. |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | Mewakili file 7Zip (.7z, .7zip), yang merupakan pengarsip sumber terbuka gratis dengan kompresi LZMA dan LZMA2. |
|
|  | [CPIO](#CPIO) | Cpio adalah utilitas pengarsip file umum dan format file yang terkait. |
|
|  | [ZSTANDARD](#ZSTANDARD) | File ZST adalah file terkompresi yang dihasilkan dengan algoritma kompresi Zstandard (zstd). |
|
|  | [TZST](#TZST) | File TZST (.tar.zst, .tzst) adalah arsip Zstandard (ZST), yang secara internal berisi Consolidated Unix File Archive (Tar), dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. |
|
|  | [TAR_ZST](#TAR-ZST) | File TZST (.tar.zst, .tzst) adalah arsip Zstandard (ZST), yang secara internal berisi Consolidated Unix File Archive (Tar), dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file. |
|
|  | [ISO](#ISO) | Citra disk optik ISO adalah file gambar disk arsip yang tidak terkompresi yang mewakili isi seluruh data pada disk optik seperti CD atau DVD, berdasarkan standar ISO-9660. |
|
|  | [LHA](#LHA) | LHA atau LZH adalah utilitas kompresi freeware dan format file yang terkait. |
|
|  | [CAB](#CAB) | Cabinet (atau CAB) adalah format file arsip untuk Microsoft Windows. |
|
|  | [DXF](#DXF) | Mewakili File Drawing Exchange Format (.dxf), yang merupakan representasi data bertag dari file gambar AutoCAD. |
|
|  | [DWG](#DWG) | Mewakili File Database Gambar AutoCAD (.dwg), yang mewakili file biner proprietari yang digunakan untuk menyimpan data desain 2D dan 3D. |
|
|  | [DWT](#DWT) | Mewakili Template Gambar AutoCAD (.dwt), yang merupakan file template gambar AutoCAD yang digunakan sebagai awalan untuk membuat gambar yang dapat disimpan sebagai file DWG. |
|
|  | [STL](#STL) | Mewakili File Stereolithography (.stl), yang merupakan format file dapat dipertukarkan yang mewakili geometri permukaan tiga dimensi. |
|
|  | [IFC](#IFC) | Mewakili File Industry Foundation Classes (.ifc), yang merupakan format file yang menetapkan standar internasional untuk mengimpor dan mengekspor objek bangunan serta propertinya. |
|
|  | [DWF](#DWF) | Mewakili File Design Web Format (.dwf), yang merupakan format file terkompresi untuk melihat, meninjau, atau mencetak gambar 2D/3D. |
|
|  | [FBX](#FBX) | Mewakili File Pertukaran Autodesk FBX (FilmBoX) (.fbx), yang merupakan format model 3D. |
|
|  | [DWFX](#DWFX) | Mewakili File Design Web Format XPS (.dwfx), yang merupakan format terkompresi untuk melihat, meninjau, atau mencetak gambar 2D/3D sebagai dokumen XPS. |
|
|  | [DGN](#DGN) | Mewakili File Desain MicroStation (.dgn), yang merupakan gambar yang dibuat dan didukung oleh aplikasi CAD seperti MicroStation dan Intergraph Interactive Graphics Design System. |
|
|  | [PLT](#PLT) | Mewakili File PLT (HPGL) (.plt), yang merupakan file plotter berbasis vektor yang diperkenalkan oleh Autodesk, Inc. |
|
|  | [CF2](#CF2) | Mewakili File Common File Format (.cf2). |
|
|  | [OBJ](#OBJ) | Mewakili File Objek 3D Wavefront (.obj), yang merupakan file gambar 3D yang diperkenalkan oleh Wavefront Technologies. |
|
|  | [HPG](#HPG) | Mewakili File PLT (HPGL) (.hpg). |
|
|  | [IGS](#IGS) | Mewakili File Initial Graphics Exchange Specification (IGES) (.igs). |
|
|  | [VSD](#VSD) | Mewakili File Gambar Visio (.vsd), yang merupakan gambar yang dibuat dengan aplikasi Microsoft Visio untuk merepresentasikan berbagai objek grafis dan keterkaitan di antara mereka. |
|
|  | [VSDX](#VSDX) | Mewakili File Gambar Visio (.vsdx), yang mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013. |
|
|  | [VSS](#VSS) | Mewakili File Stensil Visio (.vss), yang merupakan file stensil yang dibuat dengan Microsoft Visio 2007 dan sebelumnya. |
|
|  | [VSSX](#VSSX) | Mewakili File Stensil Visio (.vssx), yang merupakan stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. |
|
|  | [VSDM](#VSDM) | Mewakili File Gambar Visio yang Mendukung Makro (.vsdm), yang merupakan file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. |
|
|  | [VST](#VST) | Mewakili Template Gambar Visio (.vst), yang merupakan file gambar vektor yang dibuat dengan Microsoft Visio. |
|
|  | [VSTX](#VSTX) | Mewakili Template Gambar Visio (.vstx), yang merupakan file template gambar yang dibuat dengan Microsoft Visio 2013 ke atas. |
|
|  | [VSTM](#VSTM) | Mewakili Template Gambar Visio yang Mendukung Makro (.vstm), yang merupakan file template yang dibuat dengan Microsoft Visio yang mendukung makro. |
|
|  | [VSSM](#VSSM) | Mewakili File Stensil Visio yang Mendukung Makro (.vssm), yang merupakan file Stensil Microsoft Visio yang mendukung makro. |
|
|  | [VSX](#VSX) | Mewakili File Stensil XML Visio (.vsx), yang merujuk pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. |
|
|  | [VTX](#VTX) | Mewakili File Template XML Visio (.vtx), yang merupakan template gambar Microsoft Visio yang disimpan ke disk dalam format file XML. |
|
|  | [VDW](#VDW) | Mewakili Gambar Web Visio (.vdw), yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar web. |
|
|  | [VDX](#VDX) | Mewakili File Gambar XML Visio (.vdx), yang mewakili setiap gambar atau diagram yang dibuat di Microsoft Visio tetapi disimpan dalam format XML dengan ekstensi .VDX. |
|
|  | [EPUB](#EPUB) | Mewakili File Open eBook (.epub), yang merupakan format file e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen. |
|
|  | [MOBI](#MOBI) | Mewakili eBook Mobipocket (.mobi), yang merupakan salah satu format file ebook yang paling banyak digunakan. |
|
|  | [AZW_3](#AZW-3) | eBook Amazon Kindle Format 8 (KF8) adalah format file digital yang dikembangkan untuk perangkat Amazon Kindle. |
|
|  | [MSG](#MSG) | Mewakili Pesan Mail Outlook (.msg), yang merupakan format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya. |
|
|  | [EML](#EML) | Mewakili Pesan Email (.eml), yang mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. |
|
|  | [EMLX](#EMLX) | Mewakili Pesan Mail Apple (.emlx), yang diimplementasikan dan dikembangkan oleh Apple. |
|
|  | [PST](#PST) | Mewakili File Outlook Personal Information Store (.pst), yang mewakili File Penyimpanan Pribadi Outlook (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna. |
|
|  | [OST](#OST) | Mewakili File Data Offline Outlook (.ost), yang mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook. |
|
|  | [TIF](#TIF) | Mewakili File Gambar Bertanda (.tif), yang mewakili gambar raster yang dimaksudkan untuk digunakan pada berbagai perangkat yang mematuhi standar format file ini. |
|
|  | [TIFF](#TIFF) | Mewakili Format File Gambar Bertanda (.tiff), yang mewakili gambar raster yang dimaksudkan untuk digunakan pada berbagai perangkat yang mematuhi standar format file ini. |
|
|  | [JPG](#JPG) | Mewakili Gambar JPEG (.jpg), yang merupakan jenis format gambar yang disimpan menggunakan metode kompresi lossy. |
|
|  | [JPEG](#JPEG) | Mewakili Gambar JPEG (.jpeg), yang merupakan jenis format gambar yang disimpan menggunakan metode kompresi lossy. |
|
|  | [JFIF](#JFIF) | JPEG File Interchange Format (.jfif) adalah gambar yang dikembangkan untuk pertukaran cepat antar platform. |
|
|  | [PNG](#PNG) | Mewakili Portable Network Graphic (.png), yang merupakan jenis format file gambar raster yang menggunakan kompresi lossless. |
|
|  | [GIF](#GIF) | Mewakili Graphical Interchange Format File (.gif), yang merupakan jenis gambar yang sangat terkompresi. |
|
|  | [APNG](#APNG) | Mewakili Animated Portable Network Graphic (.apng), yang merupakan ekstensi dari format PNG yang mendukung animasi. |
|
|  | [BMP](#BMP) | Mewakili Bitmap Image File (.bmp), yang digunakan untuk menyimpan gambar digital bitmap. |
|
|  | [ICO](#ICO) | Mewakili Icon File (.ico), yang merupakan jenis file gambar yang digunakan sebagai ikon untuk representasi aplikasi pada Microsoft Windows. |
|
|  | [TGA](#TGA) | Mewakili file Truevision TGA (TARGA), yang digunakan untuk menyimpan gambar digital bitmap yang dikembangkan oleh TRUEVISION. |
|
|  | [JP_2](#JP-2) | Mewakili JPEG 2000 Core Image File (.jp2), yang merupakan sistem pengkodean gambar dan standar kompresi gambar mutakhir. |
|
|  | [JPF](#JPF) | Mewakili JPEG 2000 Image File (.jpf). |
|
|  | [JPX](#JPX) | Mewakili JPEG 2000 Image File (.jpx). |
|
|  | [JPM](#JPM) | Mewakili JPEG 2000 Image File (.jpm). |
|
|  | [J2C](#J2C) | Mewakili JPEG 2000 Code InputStream (.j2c). |
|
|  | [J2K](#J2K) | Mewakili JPEG 2000 Code Stream (.j2k), yang merupakan gambar yang dikompresi menggunakan kompresi wavelet alih-alih kompresi DCT. |
|
|  | [JPC](#JPC) | Mewakili JPEG 2000 Code Stream (.jpc). |
|
|  | [JLS](#JLS) | Mewakili file JPEG-LS (JLS) (.jls). |
|
|  | [DIB](#DIB) | Mewakili Device Independent Bitmap File (.dib). |
|
|  | [WMF](#WMF) | Mewakili Windows Metafile (.wmf), yang mewakili Microsoft Windows Metafile (WMF) untuk menyimpan data gambar format vektor maupun bitmap. |
|
|  | [WMZ](#WMZ) | Mewakili Compressed Windows Metafile (.wmz), yang mewakili Microsoft Windows Metafile (WMF) yang dikompresi dalam arsip GZIP untuk menyimpan data gambar format vektor maupun bitmap. |
|
|  | [EMF](#EMF) | Mewakili Enhanced Windows Metafile (.emf), yang mewakili gambar grafis secara independen terhadap perangkat. |
|
|  | [EMZ](#EMZ) | Mewakili Windows Compressed Enhanced Metafile (.emz), yang mewakili gambar grafis secara independen terhadap perangkat yang dikompresi oleh GZIP. |
|
|  | [WEBP](#WEBP) | Mewakili WebP Image (.webp), yang merupakan format file gambar raster web modern yang berbasis kompresi lossless dan lossy. |
|
|  | [DNG](#DNG) | Mewakili Digital Negative Specification (.dng), yang merupakan format gambar kamera digital yang digunakan untuk penyimpanan file mentah. |
|
|  | [CDR](#CDR) | Mewakili CorelDraw Vector Graphic Drawing (.cdr), yang merupakan file gambar vektor yang secara native dibuat dengan CorelDRAW untuk menyimpan gambar yang dikodekan secara digital dan terkompresi. |
|
|  | [CMX](#CMX) | Mewakili Corel Exchange (.cmx), yang merupakan file gambar yang dapat berisi grafik vektor maupun bitmap. |
|
|  | [DJVU](#DJVU) | Mewakili Gambar DjVu (.djvu), yang merupakan format file grafis yang ditujukan untuk dokumen dan buku yang dipindai, khususnya yang berisi kombinasi teks, gambar, foto, dan ilustrasi. |
|
|  | [CGM](#CGM) | Mewakili Computer Graphics Metafile (.cgm), yang merupakan format metafile standar internasional yang gratis, lintas platform, untuk menyimpan dan menukar grafik vektor (2D), grafik raster, dan teks. |
|
|  | [PCL](#PCL) | Mewakili Dokumen Printer Command Language (.pcl). |
|
|  | [PSD](#PSD) | Mewakili Adobe Photoshop Document (.psd), yang merupakan format file asli Adobe Photoshop yang digunakan untuk perancangan dan pengembangan grafis. |
|
|  | [PSB](#PSB) | Mewakili Photoshop Large Document Format (.psb), yang digunakan untuk perancangan dan pengembangan grafis di Adobe Photoshop. |
|
|  | [DCM](#DCM) | Mewakili Gambar DICOM (.dcm), yang merupakan gambar digital yang menyimpan informasi medis pasien seperti MRI, CT scan, dan gambar ultrasonik. |
|
|  | [PS](#PS) | Mewakili File PostScript (.ps). |
|
|  | [EPS](#EPS) | Mewakili File Encapsulated PostScript (.eps), yang mendeskripsikan program bahasa Encapsulated PostScript yang menentukan tampilan satu halaman. |
|
|  | [ODG](#ODG) | Mewakili File OpenDocument Graphic (.odg), yang digunakan oleh aplikasi Draw Apache OpenOffice untuk menyimpan elemen gambar sebagai gambar vektor. |
|
|  | [FODG](#FODG) | Mewakili Template Flat XML ODF (.fodg), yang digunakan oleh aplikasi Draw Apache OpenOffice untuk menyimpan elemen gambar sebagai gambar vektor. |
|
|  | [SVG](#SVG) | Mewakili File Scalable Vector Graphics (.svg), yang merupakan file Scalable Vector Graphics yang menggunakan format teks berbasis XML untuk mendeskripsikan tampilan sebuah gambar. |
|
|  | [SVGZ](#SVGZ) | Mewakili File Compressed Scalable Vector Graphics (.svgz), yang merupakan file Scalable Vector Graphics yang menggunakan format teks berbasis XML, dikompresi dengan GZIP, untuk mendeskripsikan tampilan sebuah gambar. |
|
|  | [OTG](#OTG) | Mewakili Template OpenDocument Graphic (.otg). |
|
|  | [HTM](#HTM) | Mewakili File Hypertext Markup Language (.htm), yang merupakan ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. |
|
|  | [HTML](#HTML) | Mewakili File Hypertext Markup Language (.html), yang merupakan ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. |
|
|  | [MHT](#MHT) | Mewakili Arsip Web MHTML (.mht). |
|
|  | [NSF](#NSF) | Mewakili Database Lotus Notes (.nsf). |
|
|  | [MBOX](#MBOX) | Mewakili File Kotak Surat Email (.mbox). |
|
|  | [MHTML](#MHTML) | Mewakili File MIME HTML (.mhtml). |
|
|  | [XML](#XML) | Mewakili File XML (.xml). |
|
|  | [ONE](#ONE) | Mewakili Dokumen OneNote (.one) yang dibuat oleh aplikasi Microsoft OneNote. |
|
|  | [PDF](#PDF) | Mewakili File Portable Document Format (.pdf), yang merupakan jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. |
|
|  | [XPS](#XPS) | Mewakili File XML Paper Specification (.xps), yang merupakan file tata letak halaman berbasis XML Paper Specification yang dibuat oleh Microsoft. |
|
|  | [OXPS](#OXPS) | Mewakili File OpenXPS (.oxps). |
|
|  | [TEX](#TEX) | Mewakili Dokumen Sumber LaTeX (.tex), yang merupakan bahasa yang mencakup pemrograman serta fitur penanda yang digunakan untuk menyusun dokumen. |
|
|  | [OFD](#OFD) | Format Open Fixed-layout Document (OFD) yang didefinisikan oleh GB/T 33190-2016 bertujuan menggantikan PDF di institusi publik China. |
|
|  | [PPT](#PPT) | Mewakili Presentasi PowerPoint (.ppt), yang merupakan file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai slideshow. |
|
|  | [PPTX](#PPTX) | Mewakili Presentasi PowerPoint Open XML (.pptx), yang merupakan file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. |
|
|  | [PPS](#PPS) | Mewakili Slide Show PowerPoint (.pps), yang dibuat menggunakan Microsoft PowerPoint untuk keperluan Slide Show. |
|
|  | [PPSX](#PPSX) | Mewakili file Slide Show PowerPoint Open XML (.ppsx), yang dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk keperluan Slide Show. |
|
|  | [ODP](#ODP) | Mewakili Presentasi OpenDocument (.odp), yang merupakan format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen. |
|
|  | [FODP](#FODP) | Mewakili Presentasi OpenDocument (.fodp), yang merupakan Presentasi OpenDocument Flat XML. |
|
|  | [POT](#POT) | Mewakili Template PowerPoint (.pot), yang merupakan file template Microsoft PowerPoint yang dibuat oleh versi PowerPoint 97-2003. |
|
|  | [PPTM](#PPTM) | Mewakili Presentasi PowerPoint Open XML yang Mendukung Makro (.pptm), yang merupakan file presentasi yang mendukung makro dan dibuat dengan Microsoft PowerPoint 2007 atau versi lebih tinggi. |
|
|  | [POTX](#POTX) | Mewakili Template Presentasi PowerPoint Open XML (.potx), yang merupakan presentasi template Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 ke atas. |
|
|  | [POTM](#POTM) | Mewakili Template Presentasi PowerPoint Open XML yang Mendukung Makro (.potm), yang merupakan file template Microsoft PowerPoint dengan dukungan makro. |
|
|  | [PPSM](#PPSM) | Mewakili Slide PowerPoint Open XML yang Mendukung Makro (.ppsm), yang merupakan format file slide show yang mendukung makro dan dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi. |
|
|  | [OTP](#OTP) | Mewakili Template Presentasi OpenDocument (.otp), yang merupakan file template presentasi yang dibuat oleh aplikasi dalam format standar OASIS OpenDocument. |
|
|  | [XLS](#XLS) | Mewakili Spreadsheet Excel (.xls), yang merupakan Format File Biner Excel. |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Mewakili Excel 2003 XML (SpreadsheetML) (.xml), yang merupakan Format File Biner Excel. |
|
|  | [NUMBERS](#NUMBERS) | Mewakili Apple Numbers (.numbers), yang merupakan Format File Biner mirip Excel. |
|
|  | [XLSX](#XLSX) | Mewakili Spreadsheet Microsoft Excel Open XML (.xlsx), yang merupakan format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft pada rilis Microsoft Office 2007. |
|
|  | [XLSM](#XLSM) | Mewakili Spreadsheet Excel Open XML yang Mendukung Makro (.xlsm), yang merupakan jenis file spreadsheet yang mendukung makro. |
|
|  | [XLSB](#XLSB) | Mewakili Spreadsheet Biner Excel (.xlsb), yang menentukan Format File Biner Excel. |
|
|  | [CSV](#CSV) | Mewakili File Nilai Dipisahkan Koma (.csv), yang merupakan file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. |
|
|  | [TSV](#TSV) | Mewakili File Nilai Dipisahkan Tab (.tsv), yang merupakan data yang dipisahkan dengan tab dalam format teks biasa. |
|
|  | [ODS](#ODS) | Mewakili Spreadsheet OpenDocument (.ods), yang merupakan format Dokumen Spreadsheet OpenDocument yang dapat diedit oleh pengguna. |
|
|  | [FODS](#FODS) | Mewakili Spreadsheet OpenDocument Flat XML (.fods). |
|
|  | [OTS](#OTS) | Mewakili Template Spreadsheet OpenDocument (.ots). |
|
|  | [XLAM](#XLAM) | Mewakili Add-in Microsoft Excel (.xlam). |
|
|  | [XLTM](#XLTM) | Mewakili Template Microsoft Excel yang Diaktifkan Makro (.xltm), yang mewakili file yang dihasilkan oleh Microsoft Excel sebagai file template yang diaktifkan makro. |
|
|  | [XLT](#XLT) | Mewakili Template Microsoft Excel (.xlt), yang merupakan file template yang dibuat dengan Microsoft Excel, aplikasi spreadsheet yang merupakan bagian dari paket Microsoft Office. |
|
|  | [XLTX](#XLTX) | Mewakili Template Spreadsheet Excel Open XML (.xltx), yang mewakili Template Microsoft Excel berdasarkan spesifikasi format file Office OpenXML. |
|
|  | [SXC](#SXC) | Mewakili Spreadsheet StarOffice Calc (.sxc). |
|
|  | [MPP](#MPP) | Mewakili File Microsoft Project (.mpp), yang merupakan file data Microsoft Project yang menyimpan informasi terkait manajemen proyek secara terintegrasi. |
|
|  | [MPT](#MPT) | Mewakili Template Microsoft Project (.mpt), yang berisi informasi dasar dan struktur serta pengaturan dokumen untuk membuat file .MPP. |
|
|  | [MPX](#MPX) | Mewakili file Microsoft Project Exchange (.mpx), yang merupakan format file ASCII untuk mentransfer informasi proyek antara Microsoft Project (MSP) dan aplikasi lain yang mendukung format file MPX, seperti Primavera Project Planner, Sciforma, dan Timerline Precision Estimating. |
|
|  | [AS](#AS) | Mewakili File ActionScript (.as). |
|
|  | [AS_3](#AS-3) | Mewakili File ActionScript (.as3). |
|
|  | [ASM](#ASM) | Mewakili File Kode Sumber Bahasa Assembly (.asm). |
|
|  | [BAT](#BAT) | Mewakili File Batch DOS (.bat). |
|
|  | [C](#C) | Mewakili File Kode Sumber C/C++ (.c). |
|
|  | [CC](#CC) | Mewakili File Kode Sumber C++ (.cc). |
|
|  | [CMAKE](#CMAKE) | Mewakili File CMake (.cmake). |
|
|  | [CPP](#CPP) | Mewakili File Kode Sumber C++ (.cpp). |
|
|  | [CS](#CS) | Mewakili File Kode Sumber C# (.cs), yang merupakan file kode sumber untuk bahasa pemrograman C#. |
|
|  | [VB](#VB) | Mewakili File Item Proyek Visual Basic (.vb), yang merupakan file kode sumber yang dibuat dalam bahasa Visual Basic. |
|
|  | [CSS](#CSS) | Mewakili file Cascading Style Sheet (.css). |
|
|  | [CXX](#CXX) | Mewakili File Kode Sumber C++ (.cxx). |
|
|  | [DIFF](#DIFF) | Mewakili File Patch (.diff). |
|
|  | [ERB](#ERB) | Mewakili Skrip Ruby ERB (.erb). |
|
|  | [GROOVY](#GROOVY) | Mewakili File Kode Sumber Groovy (.groovy). |
|
|  | [H](#H) | Mewakili File Header C/C++/Objective-C (.h). |
|
|  | [HAML](#HAML) | Mewakili File Kode Sumber Haml (.haml). |
|
|  | [HH](#HH) | Mewakili file Header C++ (.hh). |
|
|  | [JAVA](#JAVA) | Mewakili file Kode Sumber Java (.java). |
|
|  | [JS](#JS) | Mewakili file JavaScript (.js). |
|
|  | [JSON](#JSON) | Mewakili file Notasi Objek JavaScript (.json). |
|
|  | [LESS](#LESS) | Mewakili file lembar gaya LESS (.less). |
|
|  | [LOG](#LOG) | Mewakili file Log (.log). |
|
|  | [M](#M) | Mewakili file Implementasi Objective-C (.m). |
|
|  | [MAKE](#MAKE) | Mewakili skrip Makefile Xcode (.make). |
|
|  | [MD](#MD) | Mewakili file Dokumentasi Markdown (.md). |
|
|  | [ML](#ML) | Mewakili file Kode Sumber ML (.ml). |
|
|  | [MM](#MM) | Mewakili file Sumber Objective-C++ (.mm). |
|
|  | [PHP](#PHP) | Mewakili file Kode Sumber PHP (.php). |
|
|  | [PL](#PL) | Mewakili skrip Perl (.pl). |
|
|  | [PROPERTIES](#PROPERTIES) | Mewakili file Properti Java (.properties). |
|
|  | [PY](#PY) | Mewakili skrip Python (.py). |
|
|  | [RB](#RB) | Mewakili file Kode Sumber Ruby (.rb). |
|
|  | [RST](#RST) | Mewakili file reStructuredText (.rst). |
|
|  | [SASS](#SASS) | Mewakili file Syntactically Awesome StyleSheets (.sass). |
|
|  | [SCALA](#SCALA) | Mewakili file Kode Sumber Scala (.scala). |
|
|  | [SCM](#SCM) | Mewakili file Kode Sumber Scheme (.scm). |
|
|  | [SCRIPT](#SCRIPT) | Mewakili file Skrip Generik (.script). |
|
|  | [SH](#SH) | Mewakili skrip Bash Shell (.sh). |
|
|  | [SML](#SML) | Mewakili file Kode Sumber Standard ML (.sml). |
|
|  | [SQL](#SQL) | Mewakili file Data Structured Query Language (.sql). |
|
|  | [VIM](#VIM) | Mewakili file Pengaturan Vim (.vim). |
|
|  | [YAML](#YAML) | Mewakili Dokumen YAML (.yaml). |
|
|  | [DOC](#DOC) | Mewakili file Dokumen Microsoft Word (.doc). |
|
|  | [DOCX](#DOCX) | Mewakili file Dokumen Microsoft Word Open XML (.docx). |
|
|  | [CHM](#CHM) | Mewakili File Bantuan HTML Terkompilasi Microsoft (.chm). |
|
|  | [DOCM](#DOCM) | Mewakili file Dokumen Word Open XML yang Mendukung Makro (.docm). |
|
|  | [DOT](#DOT) | Mewakili file Template Dokumen Word (.dot). |
|
|  | [DOTX](#DOTX) | Mewakili file Template Dokumen Word Open XML (.dotx). |
|
|  | [DOTM](#DOTM) | Mewakili file Template Dokumen Word Open XML yang Mendukung Makro (.dotm). |
|
|  | [RTF](#RTF) | Mewakili File Rich Text Format (.rtf). |
|
|  | [TXT](#TXT) | Mewakili File Teks Biasa (.txt). |
|
|  | [ODT](#ODT) | Mewakili Dokumen Teks OpenDocument (.odt). |
|
|  | [OTT](#OTT) | Mewakili Template Dokumen OpenDocument (.ott). |
|
|  | [VCF](#VCF) | Mewakili File vCard (.vcf), yang merupakan format file digital untuk menyimpan informasi kontak. |
|
|  | [AI](#AI) | Mewakili file Adobe Illustrator (.ai), yang merupakan format file untuk gambar Adobe Illustrator. |
|
|  | [PSM1](#PSM1) | Mewakili file modul skrip PowerShell (.psm1). |
|
|  | [PS1](#PS1) | Mewakili file skrip PowerShell (.ps1). |
|
|  | [PSD1](#PSD1) | Mewakili file manifes modul skrip PowerShell (.psd1). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Memetakan ekstensi file ke tipe file. |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Mengekstrak ekstensi file dari nama file atau jalur file dan memetakannya ke tipe file. |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Memetakan tipe media file ke tipe file. |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Mendeteksi tipe file dengan membaca tanda tangan file. |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Mendeteksi tipe file dengan membaca tanda tangan file. |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Mendeteksi tipe file dengan membaca tanda tangan file. |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Mendeteksi tipe file dengan membaca tanda tangan file. |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Mengambil tipe file yang didukung. |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Mencoba mendeteksi set karakter file teks [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), dan [CSV](../../com.groupdocs.viewer/filetype#CSV) berdasarkan jalur. |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Mencoba mendeteksi set karakter file teks [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), dan [CSV](../../com.groupdocs.viewer/filetype#CSV) berdasarkan aliran. |
|
|  | [getFileFormat()](#getFileFormat--) | Mendapatkan nama format file, misalnya "Microsoft Word Document". |
|
|  | [getExtension()](#getExtension--) | Mendapatkan akhiran ekstensi file (termasuk titik "."), misalnya ".doc". |
|
|  | [toString()](#toString--) | Mengembalikan representasi string dari objek saat ini. |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Mewakili tipe file yang tidak diketahui.


### ZIP {#ZIP}
```
public static final FileType ZIP
```


Mewakili file zip (.zip) yang dapat berisi satu atau lebih file atau direktori.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/compression/zip).


### TAR {#TAR}
```
public static final FileType TAR
```


Mewakili arsip file Unix terkompresi (.tar) yang dibuat untuk mengumpulkan satu atau lebih file.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/compression/tar).


### XZ {#XZ}
```
public static final FileType XZ
```


Mewakili file XZ (.xz) yang dikompresi menggunakan algoritma kompresi rasio tinggi berbasis algoritma LZMA.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/xz).


### TXZ {#TXZ}
```
public static final FileType TXZ
```


Mewakili arsip file Unix terintegrasi (.txz, .tar.xz) yang dibuat untuk mengumpulkan satu atau lebih file.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/txz).


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Mewakili arsip file Unix terintegrasi (.txz, .tar.xz) yang dibuat untuk mengumpulkan satu atau lebih file.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/txz).


### TGZ {#TGZ}
```
public static final FileType TGZ
```


Mewakili arsip file Unix terintegrasi (.tgz, .tar.gz) yang dibuat untuk mengumpulkan satu atau lebih file.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/tgz).


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Mewakili arsip file Unix terintegrasi (.tgz, .tar.gz) yang dibuat untuk mengumpulkan satu atau lebih file.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/tgz).


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Mewakili file terkompresi Bzip2 (.bz2) yang dihasilkan menggunakan metode kompresi sumber terbuka BZIP2.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/compression/bz2).


### RAR {#RAR}
```
public static final FileType RAR
```


Mewakili file terkompresi Roshal Archive (.rar) yang dihasilkan menggunakan metode kompresi RAR (WINRAR versi 4).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/compression/rar).


### GZ {#GZ}
```
public static final FileType GZ
```


Mewakili file Gnu Zipped (.gz) yang terkompresi dibuat dengan aplikasi kompresi gzip.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/compression/gz).


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Mewakili file Gnu Zipped (.gzip) yang terkompresi diperkenalkan sebagai utilitas gratis untuk menggantikan program Compress yang digunakan di sistem Unix.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/compression/gz).


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Mewakili file 7Zip (.7z, .7zip), yang merupakan pengarsip sumber terbuka gratis dengan kompresi LZMA dan LZMA2.
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/compression/7z/).


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio adalah utilitas pengarsip file umum dan format file terkait. Ini terutama diinstal pada sistem operasi komputer mirip Unix. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/compression/cpio).


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


File ZST adalah file terkompresi yang dihasilkan dengan algoritma kompresi Zstandard (zstd). Ini adalah file terkompresi yang dibuat dengan kompresi lossless oleh algoritma tersebut. File ZST dapat digunakan untuk mengompresi berbagai jenis file seperti basis data, sistem file, jaringan, dan permainan.
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/compression/zst/).


### TZST {#TZST}
```
public static final FileType TZST
```


File TZST (.tar.zst, .tzst) adalah arsip Zstandard (ZST), yang secara internal berisi Consolidated Unix File Archive (Tar), dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file.


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


File TZST (.tar.zst, .tzst) adalah arsip Zstandard (ZST), yang secara internal berisi Consolidated Unix File Archive (Tar), dibuat dengan utilitas berbasis Unix untuk mengumpulkan satu atau lebih file.


### ISO {#ISO}
```
public static final FileType ISO
```


Citra disk optik ISO adalah file gambar disk arsip yang tidak terkompresi yang mewakili isi seluruh data pada disk optik seperti CD atau DVD, berdasarkan standar ISO-9660.
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/compression/iso/).


### LHA {#LHA}
```
public static final FileType LHA
```


LHA atau LZH adalah utilitas kompresi freeware dan format file yang terkait.
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/compression/lzh/).


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (atau CAB) adalah format file arsip untuk Microsoft Windows.
Pelajari lebih lanjut tentang format file ini [di sini](../https://en.wikipedia.org/wiki/Cabinet_(file_format)).


### DXF {#DXF}
```
public static final FileType DXF
```


Mewakili File Drawing Exchange Format (.dxf), yang merupakan representasi data bertag dari file gambar AutoCAD.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dxf).


### DWG {#DWG}
```
public static final FileType DWG
```


Mewakili File Database Gambar AutoCAD (.dwg), yang mewakili file biner proprietari yang digunakan untuk menyimpan data desain 2D dan 3D.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dwg).


### DWT {#DWT}
```
public static final FileType DWT
```


Mewakili Template Gambar AutoCAD (.dwt), yang merupakan file template gambar AutoCAD yang digunakan sebagai awalan untuk membuat gambar yang dapat disimpan sebagai file DWG.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dwt).


### STL {#STL}
```
public static final FileType STL
```


Mewakili File Stereolitografi (.stl), yang merupakan format file dapat dipertukarkan yang menggambarkan geometri permukaan tiga dimensi. Format ini umum digunakan dalam prototipe cepat, pencetakan 3D, dan manufaktur berbantuan komputer.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/stl).


### IFC {#IFC}
```
public static final FileType IFC
```


Mewakili File Industry Foundation Classes (.ifc), yang merupakan format file yang menetapkan standar internasional untuk mengimpor dan mengekspor objek bangunan serta propertinya. Ini memungkinkan interoperabilitas antara berbagai aplikasi perangkat lunak.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/ifc).


### DWF {#DWF}
```
public static final FileType DWF
```


Mewakili File Design Web Format (.dwf), yang merupakan format file terkompresi untuk melihat, meninjau, atau mencetak gambar 2D/3D. File ini berisi grafik dan teks sebagai bagian dari data desain dan mengurangi ukuran file karena kompresi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dwf).


### FBX {#FBX}
```
public static final FileType FBX
```


Mewakili File Pertukaran Autodesk FBX (FilmBoX) (.fbx), yang merupakan format model 3D.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/fbx).


### DWFX {#DWFX}
```
public static final FileType DWFX
```


Mewakili File Design Web Format XPS (.dwfx), yang merupakan format terkompresi untuk melihat, meninjau, atau mencetak gambar 2D/3D sebagai dokumen XPS. Ini berisi grafik dan teks sebagai bagian dari data desain dan mengurangi ukuran file karena kompresi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dwfx).


### DGN {#DGN}
```
public static final FileType DGN
```


Mewakili File Desain MicroStation (.dgn), yang merupakan gambar yang dibuat dan didukung oleh aplikasi CAD seperti MicroStation dan Intergraph Interactive Graphics Design System.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dgn).


### PLT {#PLT}
```
public static final FileType PLT
```


Mewakili File PLT (HPGL) (.plt), yang merupakan file plotter berbasis vektor yang diperkenalkan oleh Autodesk, Inc. Ini berisi informasi untuk file CAD tertentu, dan semua gambar dicetak menggunakan garis alih-alih titik, memastikan akurasi dan presisi dalam produksi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/plt).


### CF2 {#CF2}
```
public static final FileType CF2
```


Mewakili File Common File Format (.cf2).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/cf2).


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Mewakili File Objek 3D Wavefront (.obj), yang merupakan file gambar 3D yang diperkenalkan oleh Wavefront Technologies.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/3d/obj/).


### HPG {#HPG}
```
public static final FileType HPG
```


Mewakili File PLT (HPGL) (.hpg).
Ini adalah format file yang digunakan untuk file plotter dalam HP Graphics Language (HPGL).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/hpg).


### IGS {#IGS}
```
public static final FileType IGS
```


Mewakili File Initial Graphics Exchange Specification (IGES) (.igs).


### VSD {#VSD}
```
public static final FileType VSD
```


Mewakili File Gambar Visio (.vsd), yang merupakan gambar yang dibuat dengan aplikasi Microsoft Visio untuk merepresentasikan berbagai objek grafis dan keterkaitan di antara mereka.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vsd).


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Mewakili File Gambar Visio (.vsdx), yang merupakan format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013. Ini menggantikan format file biner (.VSD) yang didukung oleh versi Microsoft Visio sebelumnya.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vsdx).


### VSS {#VSS}
```
public static final FileType VSS
```


Mewakili File Stencil Visio (.vss), yang merupakan file stencil yang dibuat dengan Microsoft Visio 2007 dan sebelumnya. File stencil menyediakan objek gambar yang dapat dimasukkan ke dalam gambar Visio .VSD.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vss).


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Mewakili File Stencil Visio (.vssx), yang merupakan stencil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Format file VSSX dapat dibuka dengan Visio 2013 ke atas. File Visio dikenal karena mewakili berbagai elemen gambar seperti bentuk, konektor, diagram alur, tata letak jaringan, diagram UML, dll.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vssx).


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Mewakili Gambar Visio yang Mendukung Makro (.vsdm), yang merupakan file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. File VSDM adalah gambar OPC/XML yang mirip dengan VSDX, tetapi juga menyediakan kemampuan untuk menjalankan makro saat file dibuka.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vsdm).


### VST {#VST}
```
public static final FileType VST
```


Mewakili Template Gambar Visio (.vst), yang merupakan file gambar vektor yang dibuat dengan Microsoft Visio. Mereka berfungsi sebagai templat untuk membuat file lebih lanjut dan berisi tata letak serta pengaturan default yang digunakan untuk membuat gambar Visio baru.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vst).


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Mewakili Template Gambar Visio (.vstx), yang merupakan file template gambar yang dibuat dengan Microsoft Visio 2013 ke atas. File VSTX ini menyediakan titik awal untuk membuat gambar Visio yang disimpan sebagai file .VSDX, dengan tata letak dan pengaturan default.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vstx).


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Mewakili Template Gambar Visio yang Mendukung Makro (.vstm), yang merupakan file template yang dibuat dengan Microsoft Visio yang mendukung makro. File yang dibuat dari template VSTM dapat menjalankan makro yang dikembangkan dalam kode Visual Basic for Applications (VBA).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vstm).


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Mewakili File Stencil Visio yang Mendukung Makro (.vssm), yang merupakan file Stencil Microsoft Visio yang mendukung makro. Ketika file VSSM dibuka, makro dapat dijalankan untuk mencapai pemformatan dan penempatan bentuk yang diinginkan dalam diagram.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vssm).


### VSX {#VSX}
```
public static final FileType VSX
```


Mewakili File Stencil XML Visio (.vsx), yang merujuk pada stencil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. File VSX disimpan dalam format file XML dan didukung hingga Visio 2013.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vsx).


### VTX {#VTX}
```
public static final FileType VTX
```


Mewakili File Template XML Visio (.vtx), yang merupakan templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Templat ini menyediakan pengaturan dasar untuk membuat beberapa file Visio dengan pengaturan yang sama.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vtx).


### VDW {#VDW}
```
public static final FileType VDW
```


Mewakili Gambar Web Visio (.vdw), yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar web.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/vdw).


### VDX {#VDX}
```
public static final FileType VDX
```


Mewakili File Gambar XML Visio (.vdx), yang mewakili setiap gambar atau diagram yang dibuat di Microsoft Visio tetapi disimpan dalam format XML dengan ekstensi .VDX. File gambar XML Visio dibuat dalam perangkat lunak Visio yang dikembangkan oleh Microsoft.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vdx).


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Mewakili File eBook Terbuka (.epub), yang merupakan format file e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen. Format ini didukung oleh banyak e-reader dan aplikasi perangkat lunak.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/ebook/epub).


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mewakili eBook Mobipocket (.mobi), yang merupakan salah satu format file ebook yang paling banyak digunakan. Format ini merupakan peningkatan dari format OEB (Open Ebook Format) lama dan digunakan sebagai format proprietari untuk Mobipocket Reader.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/ebook/mobi).


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


eBook Amazon Kindle Format 8 (KF8) adalah format file digital yang dikembangkan untuk perangkat Amazon Kindle. Format ini merupakan peningkatan dari file AZW lama dan hanya digunakan pada perangkat Kindle Fire dengan kompatibilitas mundur untuk format file nenek moyang yaitu MOBI dan AZW.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/ebook/azw3).


### MSG {#MSG}
```
public static final FileType MSG
```


Mewakili Pesan Mail Outlook (.msg), yang merupakan format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/msg).


### EML {#EML}
```
public static final FileType EML
```


Mewakili Pesan E-Mail (.eml), yang mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. Hampir semua klien email mendukung format file ini karena kepatuhannya terhadap Standar Format Pesan Internet RFC-822.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/eml).


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Mewakili Pesan Apple Mail (.emlx), yang diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/emlx).


### PST {#PST}
```
public static final FileType PST
```


Mewakili File Outlook Personal Information Store (.pst), yang mewakili File Penyimpanan Pribadi Outlook (juga disebut Personal Storage Table) yang menyimpan berbagai informasi pengguna.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/pst).


### OST {#OST}
```
public static final FileType OST
```


Mewakili File Data Offline Outlook (.ost), yang mewakili data kotak surat pengguna dalam mode offline pada mesin lokal setelah pendaftaran dengan Exchange Server menggunakan Microsoft Outlook.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/ost).


### TIF {#TIF}
```
public static final FileType TIF
```


Mewakili File Gambar Bertanda (.tif), yang mewakili gambar raster yang ditujukan untuk penggunaan pada berbagai perangkat yang mematuhi standar format file ini. File ini mampu menggambarkan data gambar tingkat dua, skala abu-abu, palet-warna, dan warna penuh dalam beberapa ruang warna.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/tiff).


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Mewakili Format File Gambar Bertanda (.tiff), yang mewakili gambar raster yang ditujukan untuk penggunaan pada berbagai perangkat yang mematuhi standar format file ini. File ini mampu menggambarkan data gambar tingkat dua, skala abu-abu, palet-warna, dan warna penuh dalam beberapa ruang warna.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/tiff).


### JPG {#JPG}
```
public static final FileType JPG
```


Mewakili Gambar JPEG (.jpg), yang merupakan jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar output, sebagai hasil kompresi, merupakan kompromi antara ukuran penyimpanan dan kualitas gambar.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/jpeg).


### JPEG {#JPEG}
```
public static final FileType JPEG
```


Mewakili Gambar JPEG (.jpeg), yang merupakan jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar output, sebagai hasil kompresi, merupakan kompromi antara ukuran penyimpanan dan kualitas gambar.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/jpeg).


### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG File Interchange Format (.jfif) adalah gambar yang dikembangkan untuk pertukaran cepat antar platform. Format ini menggunakan kompresi JPEG. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/jfif).


### PNG {#PNG}
```
public static final FileType PNG
```


Mewakili Portable Network Graphic (.png), yang merupakan jenis format file gambar raster yang menggunakan kompresi lossless. Format file ini dibuat sebagai pengganti Graphics Interchange Format (GIF) dan tidak memiliki batasan hak cipta.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/png).


### GIF {#GIF}
```
public static final FileType GIF
```


Mewakili Graphical Interchange Format File (.gif), yang merupakan jenis gambar yang sangat terkompresi. Untuk setiap gambar, GIF biasanya memungkinkan hingga 8 bit per piksel, dan hingga 256 warna diizinkan di seluruh gambar.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/gif).


### APNG {#APNG}
```
public static final FileType APNG
```


Mewakili Animated Portable Network Graphic (.apng), yang merupakan ekstensi dari format PNG yang mendukung animasi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/apng).


### BMP {#BMP}
```
public static final FileType BMP
```


Mewakili Bitmap Image File (.bmp), yang digunakan untuk menyimpan gambar digital bitmap. Gambar-gambar ini independen dari adaptor grafis dan juga disebut format file device independent bitmap (DIB).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/bmp).


### ICO {#ICO}
```
public static final FileType ICO
```


Mewakili Icon File (.ico), yang merupakan jenis file gambar yang digunakan sebagai ikon untuk representasi aplikasi pada Microsoft Windows.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/ico).


### TGA {#TGA}
```
public static final FileType TGA
```


Mewakili file Truevision TGA (TARGA), yang digunakan untuk menyimpan gambar digital bitmap yang dikembangkan oleh TRUEVISION.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/tga).


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Mewakili JPEG 2000 Core Image File (.jp2), yang merupakan sistem pengkodean gambar dan standar kompresi gambar mutakhir.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/jp2).


### JPF {#JPF}
```
public static final FileType JPF
```


Mewakili JPEG 2000 Image File (.jpf).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/image/jpf).


### JPX {#JPX}
```
public static final FileType JPX
```


Mewakili JPEG 2000 Image File (.jpx).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/jpx).


### JPM {#JPM}
```
public static final FileType JPM
```


Mewakili JPEG 2000 Image File (.jpm).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/jpm).


### J2C {#J2C}
```
public static final FileType J2C
```


Mewakili JPEG 2000 Code InputStream (.j2c).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/j2c).


### J2K {#J2K}
```
public static final FileType J2K
```


Mewakili JPEG 2000 Code Stream (.j2k), yang merupakan gambar yang dikompresi menggunakan kompresi wavelet alih-alih kompresi DCT.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/j2k).


### JPC {#JPC}
```
public static final FileType JPC
```


Mewakili JPEG 2000 Code Stream (.jpc).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/jpc).


### JLS {#JLS}
```
public static final FileType JLS
```


Mewakili file JPEG-LS (JLS) (.jls).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/jls).


### DIB {#DIB}
```
public static final FileType DIB
```


Mewakili Device Independent Bitmap File (.dib).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/dib).


### WMF {#WMF}
```
public static final FileType WMF
```


Mewakili Windows Metafile (.wmf), yang mewakili Microsoft Windows Metafile (WMF) untuk menyimpan data gambar format vektor maupun bitmap.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/wmf).


### WMZ {#WMZ}
```
public static final FileType WMZ
```


Mewakili Compressed Windows Metafile (.wmz), yang mewakili Microsoft Windows Metafile (WMF) yang dikompresi dalam arsip GZIP untuk menyimpan data gambar format vektor maupun bitmap.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/wmz#compressed_windows_metafile).


### EMF {#EMF}
```
public static final FileType EMF
```


Mewakili Enhanced Windows Metafile (.emf), yang merepresentasikan gambar grafis secara device-independen. Metafile EMF terdiri dari catatan berukuran variabel dalam urutan kronologis yang dapat merender gambar yang disimpan setelah parsing pada perangkat output apa pun.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/emf).


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Mewakili Windows Compressed Enhanced Metafile (.emz), yang mewakili gambar grafis yang dikompresi secara independen dari perangkat oleh GZIP. Metafile EMF terdiri dari catatan dengan panjang variabel dalam urutan kronologis yang dapat menampilkan gambar yang disimpan setelah diparsing pada perangkat output apa pun.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/emz).


### WEBP {#WEBP}
```
public static final FileType WEBP
```


Mewakili Gambar WebP (.webp), yang merupakan format file gambar raster web modern berbasis kompresi lossless dan lossy. Ini memberikan kualitas gambar yang sama sekaligus secara signifikan mengurangi ukuran gambar.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/webp).


### DNG {#DNG}
```
public static final FileType DNG
```


Mewakili Spesifikasi Digital Negative (.dng), yang merupakan format gambar kamera digital yang digunakan untuk penyimpanan file mentah. Format ini dikembangkan oleh Adobe pada September 2004 dan terutama digunakan untuk fotografi digital.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/dng).


### CDR {#CDR}
```
public static final FileType CDR
```


Mewakili CorelDraw Vector Graphic Drawing (.cdr), yang merupakan file gambar vektor yang secara asli dibuat dengan CorelDRAW untuk menyimpan gambar yang dikodekan secara digital dan terkompresi. File gambar CDR berisi teks, garis, bentuk, gambar, warna, dan efek untuk representasi vektor dari konten gambar.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/cdr).


### CMX {#CMX}
```
public static final FileType CMX
```


Mewakili Corel Exchange (.cmx), yang merupakan file gambar yang dapat berisi grafik vektor maupun bitmap.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/cmx).


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Mewakili Gambar DjVu (.djvu), yang merupakan format file grafis yang ditujukan untuk dokumen dan buku yang dipindai, khususnya yang berisi kombinasi teks, gambar, foto, dan ilustrasi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/djvu).


### CGM {#CGM}
```
public static final FileType CGM
```


Mewakili Computer Graphics Metafile (.cgm), yang merupakan format metafile standar internasional yang gratis, platform-independen untuk menyimpan dan menukar grafik vektor (2D), grafik raster, dan teks. CGM menggunakan pendekatan berorientasi objek dan menyediakan banyak fungsi untuk produksi gambar.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/page-description-language/cgm).


### PCL {#PCL}
```
public static final FileType PCL
```


Mewakili Dokumen Printer Command Language (.pcl).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/page-description-language/pcl).


### PSD {#PSD}
```
public static final FileType PSD
```


Mewakili Adobe Photoshop Document (.psd), yang merupakan format file asli Adobe Photoshop yang digunakan untuk perancangan dan pengembangan grafis.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/psd).


### PSB {#PSB}
```
public static final FileType PSB
```


Mewakili Photoshop Large Document Format (.psb), yang digunakan untuk perancangan dan pengembangan grafis di Adobe Photoshop.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/psb).


### DCM {#DCM}
```
public static final FileType DCM
```


Mewakili Gambar DICOM (.dcm), yang merupakan gambar digital yang menyimpan informasi medis pasien seperti MRI, CT scan, dan gambar ultrasonik.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/dcm).


### PS {#PS}
```
public static final FileType PS
```


Mewakili File PostScript (.ps).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/page-description-language/ps).


### EPS {#EPS}
```
public static final FileType EPS
```


Mewakili File Encapsulated PostScript (.eps), yang mendeskripsikan program bahasa Encapsulated PostScript yang menentukan tampilan satu halaman.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/page-description-language/eps).


### ODG {#ODG}
```
public static final FileType ODG
```


Mewakili File OpenDocument Graphic (.odg), yang digunakan oleh aplikasi Draw Apache OpenOffice untuk menyimpan elemen gambar sebagai gambar vektor.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/odg).


### FODG {#FODG}
```
public static final FileType FODG
```


Mewakili Template Flat XML ODF (.fodg), yang digunakan oleh aplikasi Draw Apache OpenOffice untuk menyimpan elemen gambar sebagai gambar vektor.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/fodg).


### SVG {#SVG}
```
public static final FileType SVG
```


Mewakili File Scalable Vector Graphics (.svg), yang merupakan file Scalable Vector Graphics yang menggunakan format teks berbasis XML untuk mendeskripsikan tampilan sebuah gambar.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/page-description-language/svg).


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Mewakili File Compressed Scalable Vector Graphics (.svgz), yang merupakan file Scalable Vector Graphics yang menggunakan format teks berbasis XML, dikompresi dengan GZIP, untuk mendeskripsikan tampilan sebuah gambar.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/svgz).


### OTG {#OTG}
```
public static final FileType OTG
```


Mewakili Template OpenDocument Graphic (.otg).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/image/otg).


### HTM {#HTM}
```
public static final FileType HTM
```


Mewakili File Hypertext Markup Language (.htm), yang merupakan ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/html).


### HTML {#HTML}
```
public static final FileType HTML
```


Mewakili File Hypertext Markup Language (.html), yang merupakan ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/html).


### MHT {#MHT}
```
public static final FileType MHT
```


Mewakili Arsip Web MHTML (.mht).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/mht).


### NSF {#NSF}
```
public static final FileType NSF
```


Mewakili Database Lotus Notes (.nsf).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/nsf).


### MBOX {#MBOX}
```
public static final FileType MBOX
```


Mewakili File Kotak Surat Email (.mbox).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/mbox).


### MHTML {#MHTML}
```
public static final FileType MHTML
```


Mewakili File MIME HTML (.mhtml).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/mhtml).


### XML {#XML}
```
public static final FileType XML
```


Mewakili File XML (.xml).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/web/xml).


### ONE {#ONE}
```
public static final FileType ONE
```


Mewakili Dokumen OneNote (.one) yang dibuat oleh aplikasi Microsoft OneNote. OneNote memungkinkan Anda mengumpulkan informasi menggunakan aplikasi seolah-olah Anda menggunakan papan draf untuk mencatat.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/note-taking/one).


### PDF {#PDF}
```
public static final FileType PDF
```


Mewakili File Format Dokumen Portabel (.pdf), yang merupakan jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, dan sistem operasi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/view/pdf).


### XPS {#XPS}
```
public static final FileType XPS
```


Mewakili File Spesifikasi Kertas XML (.xps), yang merupakan file tata letak halaman berbasis Spesifikasi Kertas XML yang dibuat oleh Microsoft. Format ini dikembangkan oleh Microsoft sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/page-description-language/xps).


### OXPS {#OXPS}
```
public static final FileType OXPS
```


Mewakili File OpenXPS (.oxps).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/page-description-language/oxps).


### TEX {#TEX}
```
public static final FileType TEX
```


Mewakili Dokumen Sumber LaTeX (.tex), yang merupakan bahasa yang mencakup pemrograman serta fitur penanda yang digunakan untuk menyusun dokumen.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/page-description-language/tex).


### OFD {#OFD}
```
public static final FileType OFD
```


Format Open Fixed-layout Document (OFD) yang didefinisikan oleh GB/T 33190-2016 bertujuan menggantikan PDF di institusi publik China.


### PPT {#PPT}
```
public static final FileType PPT
```


Mewakili Presentasi PowerPoint (.ppt), yang merupakan file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai slideshow. Ini menentukan Format File Biner yang digunakan oleh Microsoft PowerPoint 97-2003.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/ppt).


### PPTX {#PPTX}
```
public static final FileType PPTX
```


Mewakili Presentasi PowerPoint Open XML (.pptx), yang merupakan file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Tidak seperti versi sebelumnya dari format file presentasi PPT yang bersifat biner, format PPTX berbasis pada format file presentasi Microsoft PowerPoint Open XML.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/pptx).


### PPS {#PPS}
```
public static final FileType PPS
```


Mewakili Slide Show PowerPoint (.pps), yang dibuat menggunakan Microsoft PowerPoint untuk keperluan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/pps).


### PPSX {#PPSX}
```
public static final FileType PPSX
```


Mewakili file Slide Show PowerPoint Open XML (.ppsx), yang dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk keperluan Slide Show.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/ppsx).


### ODP {#ODP}
```
public static final FileType ODP
```


Mewakili Presentasi OpenDocument (.odp), yang merupakan format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/odp).


### FODP {#FODP}
```
public static final FileType FODP
```


Mewakili Presentasi OpenDocument (.fodp), yang merupakan Presentasi OpenDocument Flat XML.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/fodp).


### POT {#POT}
```
public static final FileType POT
```


Mewakili Template PowerPoint (.pot), yang merupakan file template Microsoft PowerPoint yang dibuat oleh versi PowerPoint 97-2003.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/pot).


### PPTM {#PPTM}
```
public static final FileType PPTM
```


Mewakili Presentasi PowerPoint Open XML yang Mendukung Makro (.pptm), yang merupakan file presentasi yang mendukung makro dan dibuat dengan Microsoft PowerPoint 2007 atau versi lebih tinggi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/pptm).


### POTX {#POTX}
```
public static final FileType POTX
```


Mewakili Template Presentasi PowerPoint Open XML (.potx), yang merupakan presentasi template Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 ke atas.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/potx).


### POTM {#POTM}
```
public static final FileType POTM
```


Mewakili Template Presentasi PowerPoint Open XML yang Mendukung Makro (.potm), yang merupakan file template Microsoft PowerPoint dengan dukungan makro. File POTM dibuat dengan PowerPoint 2007 atau lebih baru dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/potm).


### PPSM {#PPSM}
```
public static final FileType PPSM
```


Mewakili Slide PowerPoint Open XML yang Mendukung Makro (.ppsm), yang merupakan format file slide show yang mendukung makro dan dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/ppsm).


### OTP {#OTP}
```
public static final FileType OTP
```


Mewakili Template Presentasi OpenDocument (.otp), yang merupakan file template presentasi yang dibuat oleh aplikasi dalam format standar OASIS OpenDocument.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/otp).


### XLS {#XLS}
```
public static final FileType XLS
```


Mewakili Spreadsheet Excel (.xls), yang merupakan Format File Biner Excel. File semacam itu dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xls).


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Mewakili Excel 2003 XML (SpreadsheetML) (.xml), yang merupakan Format File Biner Excel. File semacam itu dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xls).


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Mewakili Apple Numbers (.numbers), yang merupakan Format File Biner mirip Excel. File semacam itu dapat dibuat oleh aplikasi Apple Numbers.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/numbers).


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Mewakili Spreadsheet Microsoft Excel Open XML (.xlsx), yang merupakan format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft pada rilis Microsoft Office 2007.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xlsx).


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Mewakili Spreadsheet Excel Open XML yang Mendukung Makro (.xlsm), yang merupakan jenis file spreadsheet yang mendukung makro.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xlsm).


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Mewakili Spreadsheet Biner Excel (.xlsb), yang menentukan Format File Biner Excel. Ini adalah kumpulan catatan dan struktur yang menentukan konten buku kerja Excel.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xlsb).


### CSV {#CSV}
```
public static final FileType CSV
```


Mewakili File Nilai Dipisahkan Koma (.csv), yang merupakan file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/csv).


### TSV {#TSV}
```
public static final FileType TSV
```


Mewakili File Nilai Dipisahkan Tab (.tsv), yang merupakan data yang dipisahkan dengan tab dalam format teks biasa.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/tsv).


### ODS {#ODS}
```
public static final FileType ODS
```


Mewakili OpenDocument Spreadsheet (.ods), yang merupakan format Dokumen Spreadsheet OpenDocument yang dapat diedit oleh pengguna. Data disimpan dalam file ODF dalam baris dan kolom.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/ods).


### FODS {#FODS}
```
public static final FileType FODS
```


Mewakili Spreadsheet OpenDocument Flat XML (.fods).
Ini adalah format dokumen spreadsheet berbasis XML yang digunakan oleh OpenOffice dan LibreOffice.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/fods).


### OTS {#OTS}
```
public static final FileType OTS
```


Mewakili Template Spreadsheet OpenDocument (.ots).
Ini adalah format dokumen templat yang digunakan oleh OpenOffice dan LibreOffice untuk spreadsheet.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/ots).


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Mewakili Add-in Microsoft Excel (.xlam).
Ini adalah format file yang digunakan oleh Microsoft Excel untuk membuat add-in dengan fungsionalitas khusus.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/xlam).


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Mewakili Template Microsoft Excel yang Mendukung Makro (.xltm), yang merupakan file yang dihasilkan oleh Microsoft Excel sebagai file template yang mendukung makro. File XLTM mirip dengan XLTX dalam struktur kecuali yang terakhir tidak mendukung pembuatan file template dengan makro.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/spreadsheet/xltm).


### XLT {#XLT}
```
public static final FileType XLT
```


Mewakili templat Microsoft Excel (.xlt), yang merupakan file templat yang dibuat dengan Microsoft Excel, sebuah aplikasi spreadsheet yang merupakan bagian dari paket Microsoft Office. Microsoft Office 97‑2003 mendukung pembuatan file XLT baru serta membuka file tersebut.
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Mewakili Templat Spreadsheet Excel Open XML (.xltx), yang mewakili Templat Microsoft Excel berdasarkan spesifikasi format file Office OpenXML. Ini digunakan untuk membuat file templat standar yang dapat dimanfaatkan untuk menghasilkan file XLSX dengan pengaturan yang sama seperti yang ditentukan dalam file XLTX.
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


Mewakili Spreadsheet StarOffice Calc (.sxc).
Ini adalah dokumen spreadsheet yang dibuat dengan StarOffice Calc, sebuah program spreadsheet.
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


Mewakili File Microsoft Project (.mpp), yang merupakan file data Microsoft Project yang menyimpan informasi terkait manajemen proyek secara terintegrasi.
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


Mewakili Template Microsoft Project (.mpt), yang berisi informasi dasar dan struktur serta pengaturan dokumen untuk membuat file .MPP.
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


Mewakili file Microsoft Project Exchange (.mpx), yang merupakan format file ASCII untuk mentransfer informasi proyek antara Microsoft Project (MSP) dan aplikasi lain yang mendukung format file MPX, seperti Primavera Project Planner, Sciforma, dan Timerline Precision Estimating.
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


Mewakili File ActionScript (.as).
Pelajari lebih lanjut tentang format file ini [here](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Mewakili File ActionScript (.as3).
Pelajari lebih lanjut tentang format file ini [here](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


Mewakili File Kode Sumber Bahasa Assembly (.asm).
Pelajari lebih lanjut tentang format file ini [here](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


Mewakili File Batch DOS (.bat).
Pelajari lebih lanjut tentang format file ini [here](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


Mewakili File Kode Sumber C/C++ (.c).
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


Mewakili File Kode Sumber C++ (.cc).
Pelajari lebih lanjut tentang format file ini [here](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Mewakili File CMake (.cmake).
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


Mewakili File Kode Sumber C++ (.cpp).
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


Mewakili File Kode Sumber C# (.cs), yang merupakan file kode sumber untuk bahasa pemrograman C#. File ini diperkenalkan oleh Microsoft untuk digunakan dengan .NET Framework.
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


Mewakili File Item Proyek Visual Basic (.vb), yang merupakan file kode sumber yang dibuat dalam bahasa Visual Basic. File ini dibuat oleh Microsoft untuk pengembangan aplikasi .NET.
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


Mewakili file Cascading Style Sheet (.css).
Pelajari lebih lanjut tentang format file ini [here](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


Mewakili File Kode Sumber C++ (.cxx).
Pelajari lebih lanjut tentang format file ini [here](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Mewakili File Patch (.diff).
Pelajari lebih lanjut tentang format file ini [here](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


Mewakili Skrip Ruby ERB (.erb).
Pelajari lebih lanjut tentang format file ini [here](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Mewakili File Kode Sumber Groovy (.groovy).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


Mewakili File Header C/C++/Objective-C (.h).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


Mewakili File Kode Sumber Haml (.haml).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


Mewakili file Header C++ (.hh).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Mewakili file Kode Sumber Java (.java).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


Mewakili file JavaScript (.js).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


Mewakili file Notasi Objek JavaScript (.json).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


Mewakili file lembar gaya LESS (.less).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


Mewakili file Log (.log).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


Mewakili file Implementasi Objective-C (.m).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Mewakili skrip Makefile Xcode (.make).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


Mewakili file Dokumentasi Markdown (.md).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


Mewakili file Kode Sumber ML (.ml).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


Mewakili file Sumber Objective-C++ (.mm).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


Mewakili file Kode Sumber PHP (.php).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


Mewakili skrip Perl (.pl).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Mewakili file Properti Java (.properties).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


Mewakili skrip Python (.py).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


Mewakili file Kode Sumber Ruby (.rb).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


Mewakili file reStructuredText (.rst).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


Mewakili file Syntactically Awesome StyleSheets (.sass).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Mewakili file Kode Sumber Scala (.scala).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


Mewakili file Kode Sumber Scheme (.scm).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Mewakili file Skrip Generik (.script).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


Mewakili skrip Bash Shell (.sh).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


Mewakili file Kode Sumber Standard ML (.sml).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/sml).


### SQL {#SQL}
```
public static final FileType SQL
```


Mewakili file Data Structured Query Language (.sql).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/database/sql).


### VIM {#VIM}
```
public static final FileType VIM
```


Mewakili file Pengaturan Vim (.vim).
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/vim).


### YAML {#YAML}
```
public static final FileType YAML
```


Mewakili Dokumen YAML (.yaml).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/programming/yaml).


### DOC {#DOC}
```
public static final FileType DOC
```


Mewakili file Dokumen Microsoft Word (.doc).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/doc).


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Mewakili file Dokumen Microsoft Word Open XML (.docx).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/docx).


### CHM {#CHM}
```
public static final FileType CHM
```


Mewakili File Bantuan HTML Terkompilasi Microsoft (.chm).
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/web/chm).


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Mewakili file Dokumen Word Open XML yang Mendukung Makro (.docm).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/docm).


### DOT {#DOT}
```
public static final FileType DOT
```


Mewakili file Template Dokumen Word (.dot).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/dot).


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Mewakili file Template Dokumen Word Open XML (.dotx).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/dotx).


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Mewakili file Template Dokumen Word Open XML yang Mendukung Makro (.dotm).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/dotm).


### RTF {#RTF}
```
public static final FileType RTF
```


Mewakili File Rich Text Format (.rtf).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/rtf).


### TXT {#TXT}
```
public static final FileType TXT
```


Mewakili File Teks Biasa (.txt).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/txt).


### ODT {#ODT}
```
public static final FileType ODT
```


Mewakili Dokumen Teks OpenDocument (.odt).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/odt).


### OTT {#OTT}
```
public static final FileType OTT
```


Mewakili Template Dokumen OpenDocument (.ott).
Ini adalah dokumen templat yang dihasilkan sesuai dengan standar format OpenDocument milik OASIS.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/word-processing/ott).


### VCF {#VCF}
```
public static final FileType VCF
```


Mewakili File vCard (.vcf), yang merupakan format file digital untuk menyimpan informasi kontak.
Ini banyak digunakan untuk pertukaran data di antara aplikasi pertukaran informasi yang populer.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/email/vcf).


### AI {#AI}
```
public static final FileType AI
```


Mewakili file Adobe Illustrator (.ai), yang merupakan format file untuk gambar Adobe Illustrator.
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/image/ai).


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Mewakili file modul skrip PowerShell (.psm1).
Ini adalah format file untuk skrip modul PowerShell.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/psm1).


### PS1 {#PS1}
```
public static final FileType PS1
```


Mewakili file skrip PowerShell (.ps1).
Ini adalah format file untuk file Cmdlet Windows PowerShell.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/ps1).


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Mewakili file manifes modul skrip PowerShell (.psd1).
Ini adalah format file untuk skrip manifes modul PowerShell.
Pelajari lebih lanjut tentang format file ini [di sini](../https://fileinfo.com/extension/psd1).


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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Memetakan ekstensi file ke tipe file.


Metode ini menerima ekstensi file, dengan atau tanpa titik ".", dan mengembalikan tipe file yang sesuai jika didukung.
Jika tipe file tidak didukung, ia mengembalikan tipe file default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Ekstensi file dengan atau tanpa titik ".". |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Mengekstrak ekstensi file dari nama file atau jalur file dan memetakannya ke tipe file.


Jika tipe file didukung, metode mengembalikan yang sesuai
FileType
,
sebaliknya ia mengembalikan tipe file default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Nama file atau jalur file. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Memetakan tipe media file ke tipe file. Misalnya, 'application/pdf' akan dipetakan ke [PDF](../../com.groupdocs.viewer/filetype#PDF).


Metode ini menerima tipe media file sebagai input dan memetakannya ke yang sesuai
FileType
. Jika tipe media adalah
didukung, metode mengembalikan tipe file yang sesuai. Jika tipe media tidak didukung, ia mengembalikan default
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | mediaType | java.lang.String | Tipe media file, misalnya 'application/pdf'. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Mendeteksi tipe file dengan membaca tanda tangan file.


Metode ini menerima aliran input yang mewakili file dan mencoba mendeteksi tipe file-nya dengan menganalisis tanda tangan file. Tanda
tanda tangan file adalah urutan unik byte di awal file yang menunjukkan tipe file-nya. Metode
membaca tanda tangan file dari aliran input dan mencocokkannya dengan tanda tangan file yang dikenal dari tipe file yang didukung.
Jika cocok ditemukan, metode mengembalikan tipe file yang sesuai. Jika tidak ada cocok, ia mengembalikan default
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | java.io.InputStream | Aliran input yang mewakili file. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Mendeteksi tipe file dengan membaca tanda tangan file.


Metode ini menganalisis tanda tangan file, yang merupakan urutan unik byte di awal file, untuk menentukan
tipe file. Ia membaca tanda tangan file dari aliran input yang disediakan dan mencocokkannya dengan tanda tangan file yang dikenal
dari tipe file yang didukung. Jika cocok ditemukan, metode mengembalikan tipe file yang sesuai. Jika tidak ada cocok, ia
mengembalikan tipe file default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Jika file dienkripsi dan memerlukan kata sandi untuk dibuka, kata sandi harus disediakan sebagai parameter ke ini
metode. Kata sandi akan digunakan untuk mendekripsi file dan menganalisis tanda tangannya untuk menentukan jenis file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | java.io.InputStream | Aliran input yang mewakili file. |
|
|  | kata sandi | java.lang.String | Kata sandi untuk membuka file. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Mendeteksi tipe file dengan membaca tanda tangan file.


Metode ini menganalisis tanda tangan file, yang merupakan urutan unik byte di awal file, untuk menentukan
tipe file. Ia membaca tanda tangan file dari aliran input yang disediakan dan mencocokkannya dengan tanda tangan file yang dikenal
dari tipe file yang didukung. Jika cocok ditemukan, metode mengembalikan tipe file yang sesuai. Jika tidak ada cocok, ia
mengembalikan tipe file default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Logger dapat disediakan untuk mencatat informasi relevan atau kesalahan selama proses deteksi jenis file. Logger
harus mengimplementasikan antarmuka ILogger. Jika tidak ada logger yang disediakan, proses deteksi tidak akan menghasilkan apa pun
output log.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | java.io.InputStream | Aliran input yang mewakili file. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Logger untuk mencatat informasi atau kesalahan. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Mendeteksi tipe file dengan membaca tanda tangan file.


Metode ini menganalisis tanda tangan file, yang merupakan urutan unik byte di awal file, untuk menentukan
tipe file. Ia membaca tanda tangan file dari aliran input yang disediakan dan mencocokkannya dengan tanda tangan file yang dikenal
dari tipe file yang didukung. Jika cocok ditemukan, metode mengembalikan tipe file yang sesuai. Jika tidak ada cocok, ia
mengembalikan tipe file default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN).


Kata sandi dapat disediakan jika file dienkripsi atau dilindungi. Kata sandi akan digunakan untuk membuka file sebelum
menganalisis tanda tangan file. Jika file tidak memerlukan kata sandi, parameter ini dapat diatur ke null.


Logger dapat disediakan untuk mencatat informasi relevan atau kesalahan selama proses deteksi jenis file. Logger
harus mengimplementasikan antarmuka ILogger. Jika tidak ada logger yang disediakan, proses deteksi tidak akan menghasilkan apa pun
output log.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | java.io.InputStream | Aliran input yang mewakili file. |
|
|  | kata sandi | java.lang.String | Kata sandi untuk membuka file. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Logger untuk mencatat informasi atau kesalahan. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Mengambil tipe file yang didukung.


Metode ini mengembalikan urutan semua jenis file yang didukung oleh sistem. Jenis file mewakili berbagai
format dokumen yang dapat diproses atau dikenali oleh sistem.
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - sebuah urutan jenis file yang didukung.

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Mencoba mendeteksi set karakter file teks [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), dan [CSV](../../com.groupdocs.viewer/filetype#CSV) berdasarkan jalur.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Nama file atau jalur file. |
|

**Returns:**
java.nio.charset.Charset - Charset atau null ketika gagal mendeteksi charset file.

**Example:**


Charset charset = FileType.detectCharset(\"message.txt\");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Mencoba mendeteksi set karakter file teks [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), dan [CSV](../../com.groupdocs.viewer/filetype#CSV) berdasarkan aliran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | java.io.InputStream | Aliran file. |
|

**Returns:**
java.nio.charset.Charset - Charset atau null ketika gagal mendeteksi charset file.

**Example:**


InputStream stream = new FileInputStream(\"message.txt\");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Mendapatkan nama format file, misalnya "Microsoft Word Document".


**Returns:**
java.lang.String - nama format file.

### getExtension() {#getExtension--}
```
public final String getExtension()
```


Mendapatkan akhiran ekstensi file (termasuk titik "."), misalnya ".doc".


**Returns:**
java.lang.String - akhiran ekstensi file.

### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string dari objek saat ini.


**Returns:**
java.lang.String - representasi string dari objek saat ini.

