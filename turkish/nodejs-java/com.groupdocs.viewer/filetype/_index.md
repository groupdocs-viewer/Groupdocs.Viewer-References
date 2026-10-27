---
title: "FileType"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Dosya türünü temsil eder."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Dosya tipini temsil eder. GroupDocs.Viewer bileşeni tarafından desteklenen tüm dosya tiplerinin listesini elde etmek için yöntemler sağlar.

FileType enum'ı, GroupDocs.Viewer bileşeni tarafından desteklenen farklı dosya tiplerini temsil eden sabitler sağlar. Bu enum'daki yöntemleri kullanarak tüm desteklenen dosya tiplerinin listesini alabilir veya belirli bir dosya tipinin desteklenip desteklenmediğini kontrol edebilirsiniz.

Örnek kullanım:

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
## Fields

| Field | Açıklama |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Bilinmeyen bir dosya tipini temsil eder. |
| [ZIP](#ZIP) | Bir veya daha fazla dosya veya dizin içerebilen sıkıştırılmış bir dosya (.zip) temsil eder. |
| [TAR](#TAR) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivi (.tar) temsil eder. |
| [XZ](#XZ) | LZMA algoritmasına dayalı yüksek oranlı sıkıştırma algoritması kullanılarak sıkıştırılmış bir XZ dosyası (.xz) temsil eder. |
| [TXZ](#TXZ) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivi (.txz, .tar.xz) temsil eder. |
| [TARXZ](#TARXZ) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivi (.txz, .tar.xz) temsil eder. |
| [TGZ](#TGZ) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivi (.tgz, .tar.gz) temsil eder. |
| [TARGZ](#TARGZ) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivi (.tgz, .tar.gz) temsil eder. |
| [BZ_2](#BZ-2) | BZIP2 açık kaynaklı sıkıştırma yöntemi kullanılarak oluşturulmuş bir Bzip2 sıkıştırılmış dosya (.bz2) temsil eder. |
| [RAR](#RAR) | RAR (WINRAR sürüm 4) sıkıştırma yöntemi kullanılarak oluşturulmuş bir Roshal Arşivi (.rar) sıkıştırılmış dosya temsil eder. |
| [GZ](#GZ) | gzip sıkıştırma uygulamasıyla oluşturulmuş bir Gnu Zipped File (.gz) sıkıştırılmış dosya temsil eder. |
| [GZIP](#GZIP) | Unix sistemlerinde kullanılan Compress programının yerine geçen ücretsiz bir yardımcı program olarak tanıtılan Gnu Zipped Dosya (.gzip) sıkıştırılmış dosyasını temsil eder. |
| [SEVEN_ZIP](#SEVEN-ZIP) | LZMA ve LZMA2 sıkıştırmasıyla ücretsiz açık kaynaklı bir arşivleyici olan 7Zip (.7z, .7zip) dosyasını temsil eder. |
| [CPIO](#CPIO) | Cpio, genel bir dosya arşivleme yardımcı programı ve ilişkili dosya biçimidir. |
| [ZSTANDARD](#ZSTANDARD) | ZST dosyası, Zstandard (zstd) sıkıştırma algoritmasıyla oluşturulan bir sıkıştırılmış dosyadır. |
| [TZST](#TZST) | TZST dosyaları (.tar.zst, .tzst), içinde birleştirilmiş Unix Dosya Arşivi (Tar) bulunan Zstandard arşivleridir (ZST) ve bir veya daha fazla dosyayı toplamak için Unix tabanlı bir yardımcı programla oluşturulmuştur. |
| [TAR_ZST](#TAR-ZST) | TZST dosyaları (.tar.zst, .tzst), içinde birleştirilmiş Unix Dosya Arşivi (Tar) bulunan Zstandard arşivleridir (ZST) ve bir veya daha fazla dosyayı toplamak için Unix tabanlı bir yardımcı programla oluşturulmuştur. |
| [ISO](#ISO) | ISO optik disk görüntüsü, CD veya DVD gibi bir optik diskin üzerindeki tüm verilerin içeriğini temsil eden, ISO-9660 standardına dayalı sıkıştırılmamış bir arşiv disk görüntü dosyasıdır. |
| [LHA](#LHA) | LHA veya LZH, ücretsiz bir sıkıştırma yardımcı programı ve ilişkili dosya biçimidir. |
| [CAB](#CAB) | Cabinet (veya CAB), Microsoft Windows için bir arşiv dosyası biçimidir. |
| [DXF](#DXF) | AutoCAD çizim dosyasının etiketli veri temsili olan Çizim Değişim Formatı Dosyası (.dxf)'i temsil eder. |
| [DWG](#DWG) | 2D ve 3D tasarım verilerini içeren özel ikili dosyaları temsil eden AutoCAD Çizim Veritabanı Dosyası (.dwg)'yi temsil eder. |
| [DWT](#DWT) | DWG dosyaları olarak kaydedilebilen çizimler oluşturmak için başlangıç olarak kullanılan AutoCAD çizim şablonu dosyası (.dwt) temsil eder. |
| [STL](#STL) | 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatı olan Stereolithography Dosyası (.stl)'yi temsil eder. |
| [IFC](#IFC) | Bina nesneleri ve özelliklerinin içe ve dışa aktarımı için uluslararası standartlar belirleyen bir dosya formatı olan Industry Foundation Classes Dosyası (.ifc)'yi temsil eder. |
| [DWF](#DWF) | 2D/3D çizimleri görüntüleme, inceleme veya yazdırma için sıkıştırılmış bir dosya formatı olan Design Web Format Dosyası (.dwf)'yi temsil eder. |
| [FBX](#FBX) | 3D model formatı olan Autodesk FBX Interchange Dosyası (FilmBoX) (.fbx)'yi temsil eder. |
| [DWFX](#DWFX) | 2D/3D çizimleri XPS belgesi olarak görüntüleme, inceleme veya yazdırma için sıkıştırılmış bir format olan Design Web Format Dosyası XPS (.dwfx)'yi temsil eder. |
| [DGN](#DGN) | MicroStation ve Intergraph Interactive Graphics Design System gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimler olan MicroStation Tasarım Dosyası (.dgn)'yi temsil eder. |
| [PLT](#PLT) | Autodesk, Inc. tarafından tanıtılan vektör tabanlı bir plotter dosyası olan PLT (HPGL) Dosyası (.plt)'yi temsil eder. |
| [CF2](#CF2) | Common File Format Dosyasını (.cf2) temsil eder. |
| [OBJ](#OBJ) | Wavefront Technologies tarafından tanıtılan 3D görüntü dosyası olan Wavefront 3D Nesne Dosyası (.obj)'yi temsil eder. |
| [HPG](#HPG) | PLT (HPGL) Dosyası (.hpg)'yi temsil eder. |
| [IGS](#IGS) | Initial Graphics Exchange Specification (IGES) Dosyasını (.igs) temsil eder. |
| [VSD](#VSD) | Microsoft Visio uygulamasıyla çeşitli grafik nesneleri ve bunların bağlantılarını temsil eden çizimler oluşturulan Visio Çizim Dosyası (.vsd)'yi temsil eder. |
| [VSDX](#VSDX) | Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eden Visio Çizim Dosyası (.vsdx)'yi temsil eder. |
| [VSS](#VSS) | Microsoft Visio 2007 ve öncesi sürümlerle oluşturulan şablon dosyaları olan Visio Şablon Dosyası (.vss)'yi temsil eder. |
| [VSSX](#VSSX) | Microsoft Visio 2013 ve üzeri ile oluşturulan çizim şablonları olan bir Visio Şablon Dosyası (.vssx) temsil eder. |
| [VSDM](#VSDM) | Makroları destekleyen Microsoft Visio uygulaması ile oluşturulan çizim dosyaları olan bir Visio Makro‑Destekli Çizim (.vsdm) temsil eder. |
| [VST](#VST) | Microsoft Visio ile oluşturulan vektör görüntü dosyaları olan bir Visio Çizim Şablonu (.vst) temsil eder. |
| [VSTX](#VSTX) | Microsoft Visio 2013 ve üzeri ile oluşturulan çizim şablonu dosyaları olan bir Visio Çizim Şablonu (.vstx) temsil eder. |
| [VSTM](#VSTM) | Makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyaları olan bir Visio Makro‑Destekli Çizim Şablonu (.vstm) temsil eder. |
| [VSSM](#VSSM) | Makroları destekleyen Microsoft Visio Şablon dosyaları olan bir Visio Makro‑Destekli Şablon Dosyası (.vssm) temsil eder. |
| [VSX](#VSX) | Microsoft Visio'da diyagram oluşturmak için kullanılan çizimler ve şekillerden oluşan şablonları ifade eden bir Visio Şablon XML Dosyası (.vsx) temsil eder. |
| [VTX](#VTX) | Diskte XML dosya formatında kaydedilen bir Microsoft Visio çizim şablonu olan Visio Şablon XML Dosyası (.vtx) temsil eder. |
| [VDW](#VDW) | Web çizimi oluşturmak için gereken akışları ve depolamaları belirten bir Visio Web Çizimi (.vdw) temsil eder. |
| [VDX](#VDX) | Microsoft Visio'da oluşturulan ve .VDX uzantılı XML formatında kaydedilen herhangi bir çizim veya tabloyu temsil eden bir Visio Çizim XML Dosyası (.vdx). |
| [EPUB](#EPUB) | Standart bir dijital yayın formatı sağlayan bir e-kitap dosyası formatı olan Open eBook Dosyası (.epub) temsil eder. |
| [MOBI](#MOBI) | En yaygın kullanılan e-kitap dosya formatlarından biri olan bir Mobipocket eKitap (.mobi) temsil eder. |
| [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) e‑kitap, Amazon Kindle cihazları için geliştirilen dijital dosya formatıdır. |
| [MSG](#MSG) | E-posta mesajları, kişiler, randevular veya diğer görevleri depolamak için Microsoft Outlook ve Exchange tarafından kullanılan bir dosya formatı olan Outlook Mail Mesajı (.msg) temsil eder. |
| [EML](#EML) | Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eden bir E‑Posta Mesajı (.eml). |
| [EMLX](#EMLX) | Apple tarafından uygulanıp geliştirilen bir Apple Mail Mesajı (.emlx) temsil eder. |
| [PST](#PST) | Outlook Kişisel Bilgi Depolama Dosyası (.pst), çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyaları (Personal Storage Table olarak da bilinir) temsil eder. |
| [OST](#OST) | Kullanıcının posta kutusu verilerini yerel makinede çevrim dışı modda depolayan bir Outlook Çevrim Dışı Veri Dosyası (.ost) temsil eder. |
| [TIF](#TIF) | Çeşitli cihazlarda kullanılmak üzere tasarlanmış raster görüntüleri içeren bir Etiketli Görüntü Dosyası (.tif) temsil eder. |
| [TIFF](#TIFF) | Çeşitli cihazlarda kullanılmak üzere tasarlanmış raster görüntüleri içeren bir Etiketli Görüntü Dosya Formatı (.tiff) temsil eder. |
| [JPG](#JPG) | Kayıp sıkıştırma yöntemiyle kaydedilen bir görüntü formatı türü olan JPEG Görüntüsü (.jpg) temsil eder. |
| [JPEG](#JPEG) | Kayıp sıkıştırma yöntemiyle kaydedilen bir görüntü formatı türü olan JPEG Görüntüsü (.jpeg) temsil eder. |
| [JFIF](#JFIF) | Platformlar arasında hızlı değişim için geliştirilen bir görüntü olan JPEG Dosya Değişim Formatı (.jfif). |
| [PNG](#PNG) | Kayıpsız sıkıştırma kullanan bir raster görüntü dosya formatı türü olan Taşınabilir Ağ Grafiği (.png) temsil eder. |
| [GIF](#GIF) | Yüksek sıkıştırmalı bir görüntü türü olan Grafik Değişim Formatı Dosyası (.gif) temsil eder. |
| [APNG](#APNG) | Animated Portable Network Graphic (.apng) temsil eder, bu PNG formatının animasyonu destekleyen bir uzantısıdır. |
| [BMP](#BMP) | Bitmap Image File (.bmp) temsil eder, bu bitmap dijital görüntüleri depolamak için kullanılır. |
| [ICO](#ICO) | Icon File (.ico) temsil eder, bu bir görüntü dosyası türüdür ve Microsoft Windows'ta bir uygulamanın simgesi olarak kullanılır. |
| [TGA](#TGA) | Truevision TGA (TARGA) dosyası temsil eder, bu TRUEVISION tarafından geliştirilen bitmap dijital görüntüleri depolamak için kullanılır. |
| [JP_2](#JP-2) | JPEG 2000 Core Image File (.jp2) temsil eder, bu bir görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardıdır. |
| [JPF](#JPF) | JPEG 2000 Image File (.jpf) temsil eder. |
| [JPX](#JPX) | JPEG 2000 Image File (.jpx) temsil eder. |
| [JPM](#JPM) | JPEG 2000 Image File (.jpm) temsil eder. |
| [J2C](#J2C) | JPEG 2000 Code InputStream (.j2c) temsil eder. |
| [J2K](#J2K) | JPEG 2000 Code Stream (.j2k) temsil eder, bu DCT sıkıştırması yerine dalgacık sıkıştırması kullanılan bir görüntüdür. |
| [JPC](#JPC) | JPEG 2000 Code Stream (.jpc) temsil eder. |
| [JLS](#JLS) | JPEG-LS (JLS) dosyası (.jls) temsil eder. |
| [DIB](#DIB) | Device Independent Bitmap File (.dib) temsil eder. |
| [WMF](#WMF) | Windows Metafile (.wmf) temsil eder, bu Microsoft Windows Metafile (WMF) olarak vektör ve bitmap formatındaki görüntü verilerini depolamak için kullanılır. |
| [WMZ](#WMZ) | Compressed Windows Metafile (.wmz) temsil eder, bu GZIP arşivinde sıkıştırılmış Microsoft Windows Metafile (WMF) olarak vektör ve bitmap formatındaki görüntü verilerini depolamak için kullanılır. |
| [EMF](#EMF) | Enhanced Windows Metafile (.emf) temsil eder, bu grafik görüntüleri cihazdan bağımsız olarak temsil eder. |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) temsil eder, bu grafik görüntüleri cihazdan bağımsız olarak GZIP ile sıkıştırılmış şekilde temsil eder. |
| [WEBP](#WEBP) | WebP Image (.webp) temsil eder, bu kayıpsız ve kayıplı sıkıştırma tabanlı modern bir raster web görüntü dosyası formatıdır. |
| [DNG](#DNG) | Digital Negative Specification (.dng) temsil eder, bu ham dosyaların depolanması için kullanılan bir dijital kamera görüntü formatıdır. |
| [CDR](#CDR) | CorelDraw Vector Graphic Drawing (.cdr) temsil eder, bu CorelDRAW ile yerel olarak oluşturulan vektör çizim görüntü dosyasıdır ve dijital olarak kodlanmış ve sıkıştırılmış görüntüleri depolar. |
| [CMX](#CMX) | Corel Exchange (.cmx) temsil eder, bu vektör grafiklerin yanı sıra bitmap grafikler de içerebilen bir çizim görüntü dosyasıdır. |
| [DJVU](#DJVU) | DjVu Image (.djvu) temsil eder, bu özellikle metin, çizim, görüntü ve fotoğraf kombinasyonları içeren taranmış belgeler ve kitaplar için tasarlanmış bir grafik dosya formatıdır. |
| [CGM](#CGM) | Computer Graphics Metafile (.cgm) temsil eder, bu vektör grafik (2D), raster grafik ve metin depolamak ve değiştirmek için ücretsiz, platform bağımsız, uluslararası bir standart metafile formatıdır. |
| [PCL](#PCL) | Printer Command Language Document (.pcl) temsil eder. |
| [PSD](#PSD) | Adobe Photoshop Document (.psd) temsil eder, bu Adobe Photoshop'un grafik tasarım ve geliştirme için kullanılan yerel dosya formatıdır. |
| [PSB](#PSB) | Adobe Photoshop'ta grafik tasarımı ve geliştirme için kullanılan Photoshop Large Document Format (.psb) dosyasını temsil eder. |
| [DCM](#DCM) | DICOM Görüntüsü (.dcm)'yi temsil eder; bu, MRİ'ler, BT taramaları ve ultrason görüntüleri gibi hastaların tıbbi bilgilerini depolayan dijital bir görüntüdür. |
| [PS](#PS) | PostScript Dosyasını (.ps) temsil eder. |
| [EPS](#EPS) | Encapsulated PostScript Dosyasını (.eps) temsil eder; bu, tek bir sayfanın görünümünü tanımlayan Encapsulated PostScript dil programını açıklar. |
| [ODG](#ODG) | OpenDocument Grafik Dosyasını (.odg) temsil eder; bu, Apache OpenOffice Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır. |
| [FODG](#FODG) | Düz XML ODF Şablonunu (.fodg) temsil eder; bu, Apache OpenOffice Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır. |
| [SVG](#SVG) | Scalable Vector Graphics Dosyasını (.svg) temsil eder; bu, bir görüntünün görünümünü tanımlamak için XML tabanlı metin formatı kullanan bir Scalable Vector Graphics dosyasıdır. |
| [SVGZ](#SVGZ) | Sıkıştırılmış Scalable Vector Graphics Dosyasını (.svgz) temsil eder; bu, bir görüntünün görünümünü tanımlamak için XML tabanlı metin formatı kullanan ve GZIP ile sıkıştırılmış bir Scalable Vector Graphics dosyasıdır. |
| [OTG](#OTG) | OpenDocument Grafik Şablonunu (.otg) temsil eder. |
| [HTM](#HTM) | Hypertext Markup Language Dosyasını (.htm) temsil eder; bu, tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. |
| [HTML](#HTML) | Hypertext Markup Language Dosyasını (.html) temsil eder; bu, tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. |
| [MHT](#MHT) | MHTML Web Arşivini (.mht) temsil eder. |
| [NSF](#NSF) | Lotus Notes Veritabanını (.nsf) temsil eder. |
| [MBOX](#MBOX) | E-posta Posta Kutusu Dosyasını (.mbox) temsil eder. |
| [MHTML](#MHTML) | MIME HTML Dosyasını (.mhtml) temsil eder. |
| [XML](#XML) | XML Dosyasını (.xml) temsil eder. |
| [ONE](#ONE) | Microsoft OneNote uygulaması tarafından oluşturulan OneNote Belgesini (.one) temsil eder. |
| [PDF](#PDF) | Portable Document Format Dosyasını (.pdf) temsil eder; bu, Adobe tarafından 1990'larda oluşturulan bir belge türüdür. |
| [XPS](#XPS) | XML Paper Specification Dosyasını (.xps) temsil eder; bu, Microsoft tarafından oluşturulan XML Paper Specification tabanlı sayfa düzeni dosyalarını temsil eder. |
| [OXPS](#OXPS) | OpenXPS Dosyasını (.oxps) temsil eder. |
| [TEX](#TEX) | LaTeX Kaynak Belgesini (.tex) temsil eder; bu, belgeleri biçimlendirmek için programlama ve işaretleme özelliklerini içeren bir dildir. |
| [PPT](#PPT) | PowerPoint Sunumunu (.ppt) temsil eder; bu, slayt gösterisi olarak görüntülenmek üzere bir dizi slayttan oluşan bir PowerPoint dosyasıdır. |
| [PPTX](#PPTX) | PowerPoint Open XML Sunumunu (.pptx) temsil eder; bu, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. |
| [PPS](#PPS) | PowerPoint Slayt Gösterisini (.pps) temsil eder; bu, Microsoft PowerPoint kullanılarak Slayt Gösterisi amaçları için oluşturulan dosyalardır. |
| [PPSX](#PPSX) | PowerPoint Open XML Slayt Gösterisi (.ppsx) dosyalarını temsil eder; bu, Microsoft PowerPoint 2007 ve üzeri sürümlerle Slayt Gösterisi amaçları için oluşturulan dosyalardır. |
| [ODP](#ODP) | OpenDocument Sunum (.odp) temsil eder, bu da OpenOffice.org tarafından OASISOpen standardında kullanılan bir sunum dosya formatını temsil eder. |
| [FODP](#FODP) | OpenDocument Sunum (.fodp) temsil eder, bu da OpenDocument Düz XML Sunumu temsil eder. |
| [POT](#POT) | PowerPoint Şablonu (.pot) temsil eder, bu da PowerPoint 97-2003 sürümleri tarafından oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. |
| [PPTM](#PPTM) | PowerPoint Open XML Makro Etkin Sunum (.pptm) temsil eder, bu da Microsoft PowerPoint 2007 veya daha yeni sürümlerle oluşturulan makro etkin sunum dosyalarıdır. |
| [POTX](#POTX) | PowerPoint Open XML Sunum Şablonu (.potx) temsil eder, bu da Microsoft PowerPoint 2007 ve üzeri sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. |
| [POTM](#POTM) | PowerPoint Open XML Makro Etkin Sunum Şablonu (.potm) temsil eder, bu da makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. |
| [PPSM](#PPSM) | PowerPoint Open XML Makro Etkin Slayt (.ppsm) temsil eder, bu da Microsoft PowerPoint 2007 veya daha yeni sürümlerle oluşturulan makro etkin slayt gösterisi dosya formatını temsil eder. |
| [OTP](#OTP) | OpenDocument Sunum Şablonu (.otp) temsil eder, bu da OASIS OpenDocument standart formatındaki uygulamalar tarafından oluşturulan sunum şablonu dosyalarını temsil eder. |
| [XLS](#XLS) | Excel Çalışma Sayfası (.xls) temsil eder, bu da Excel İkili Dosya Formatını temsil eder. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Excel 2003 XML (SpreadsheetML) (.xml) temsil eder, bu da Excel İkili Dosya Formatını temsil eder. |
| [NUMBERS](#NUMBERS) | Apple Numbers (.numbers) temsil eder, bu da Excel benzeri bir İkili Dosya Formatını temsil eder. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Çalışma Sayfası (.xlsx) temsil eder, bu da Microsoft Office 2007 sürümüyle Microsoft tarafından tanıtılan Microsoft Excel belgeleri için yaygın bir formattır. |
| [XLSM](#XLSM) | Excel Open XML Makro Etkin Çalışma Sayfası (.xlsm) temsil eder, bu da makroları destekleyen bir çalışma sayfası dosyası türüdür. |
| [XLSB](#XLSB) | Excel İkili Çalışma Sayfası (.xlsb) temsil eder, bu da Excel İkili Dosya Formatını belirtir. |
| [CSV](#CSV) | Virgülle Ayrılmış Değerler Dosyası (.csv) temsil eder, bu da virgülle ayrılmış değerler içeren veri kayıtlarını barındıran düz metin dosyalarını temsil eder. |
| [TSV](#TSV) | Sekme Ayrılmış Değerler Dosyası (.tsv) temsil eder, bu da sekmelerle ayrılmış verileri içeren düz metin formatındaki dosyaları temsil eder. |
| [ODS](#ODS) | OpenDocument Çalışma Sayfası (.ods) temsil eder, bu da kullanıcının düzenleyebileceği OpenDocument Çalışma Sayfası Belgesi formatını ifade eder. |
| [FODS](#FODS) | OpenDocument Düz XML Çalışma Sayfası (.fods) temsil eder. |
| [OTS](#OTS) | OpenDocument Çalışma Sayfası Şablonu (.ots) temsil eder. |
| [XLAM](#XLAM) | Microsoft Excel Eklentisi (.xlam) temsil eder. |
| [XLTM](#XLTM) | Microsoft Excel Makro Etkin Şablonu (.xltm) temsil eder, bu da Microsoft Excel tarafından makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. |
| [XLT](#XLT) | Microsoft Excel Şablonu (.xlt) temsil eder, bu da Microsoft Office paketinin bir parçası olan bir hesap tablosu uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. |
| [XLTX](#XLTX) | Excel Open XML Çalışma Sayfası Şablonu (.xltx) temsil eder, bu da Office OpenXML dosya formatı özelliklerine dayanan Microsoft Excel Şablonlarını temsil eder. |
| [SXC](#SXC) | StarOffice Calc Çalışma Sayfası (.sxc) temsil eder. |
| [MPP](#MPP) | Microsoft Project Dosyası (.mpp) temsil eder, bu da proje yönetimiyle ilgili bilgileri bütünleşik bir şekilde depolayan Microsoft Project veri dosyasıdır. |
| [MPT](#MPT) | Microsoft Project Şablonu (.mpt) temsil eder; temel bilgi ve yapıyı, .MPP dosyaları oluşturmak için belge ayarlarıyla birlikte içerir. |
| [MPX](#MPX) | Microsoft Project Exchange dosyası (.mpx) temsil eder; bu, Microsoft Project (MSP) ile MPX dosya formatını destekleyen Primavera Project Planner, Sciforma ve Timerline Precision Estimating gibi diğer uygulamalar arasında proje bilgisi aktarımı için kullanılan bir ASCII dosya formatıdır. |
| [AS](#AS) | ActionScript Dosyası (.as) temsil eder. |
| [AS_3](#AS-3) | ActionScript Dosyası (.as3) temsil eder. |
| [ASM](#ASM) | Assembly Dili Kaynak Kodu Dosyası (.asm) temsil eder. |
| [BAT](#BAT) | DOS Toplu İş Dosyası (.bat) temsil eder. |
| [C](#C) | C/C++ Kaynak Kodu Dosyası (.c) temsil eder. |
| [CC](#CC) | C++ Kaynak Kodu Dosyası (.cc) temsil eder. |
| [CMAKE](#CMAKE) | CMake Dosyası (.cmake) temsil eder. |
| [CPP](#CPP) | C++ Kaynak Kodu Dosyası (.cpp) temsil eder. |
| [CS](#CS) | C\# Kaynak Kodu Dosyası (.cs) temsil eder, C\# programlama dili için bir kaynak kod dosyasıdır. |
| [VB](#VB) | Visual Basic Proje Öğesi Dosyası (.vb) temsil eder; bu, Visual Basic dilinde oluşturulan bir kaynak kod dosyasıdır. |
| [CSS](#CSS) | Cascading Style Sheet (.css) dosyası temsil eder. |
| [CXX](#CXX) | C++ Kaynak Kodu Dosyası (.cxx) temsil eder. |
| [DIFF](#DIFF) | Yama Dosyası (.diff) temsil eder. |
| [ERB](#ERB) | Ruby ERB Betiği (.erb) temsil eder. |
| [GROOVY](#GROOVY) | Groovy Kaynak Kodu Dosyası (.groovy) temsil eder. |
| [H](#H) | C/C++/Objective-C Başlık Dosyası (.h) temsil eder. |
| [HAML](#HAML) | Haml Kaynak Kodu Dosyası (.haml) temsil eder. |
| [HH](#HH) | C++ Başlık Dosyası (.hh) temsil eder. |
| [JAVA](#JAVA) | Java Kaynak Kodu Dosyası (.java) temsil eder. |
| [JS](#JS) | JavaScript Dosyası (.js) temsil eder. |
| [JSON](#JSON) | JavaScript Object Notation Dosyası (.json) temsil eder. |
| [LESS](#LESS) | LESS Stil Sayfası (.less) dosyası temsil eder. |
| [LOG](#LOG) | Kayıt Dosyası (.log) temsil eder. |
| [M](#M) | Objective-C Uygulama Dosyasını (.m) temsil eder. |
| [MAKE](#MAKE) | Xcode Makefile Betiğini (.make) temsil eder. |
| [MD](#MD) | Markdown Dokümantasyon Dosyasını (.md) temsil eder. |
| [ML](#ML) | ML Kaynak Kod Dosyasını (.ml) temsil eder. |
| [MM](#MM) | Objective-C++ Kaynak Dosyasını (.mm) temsil eder. |
| [PHP](#PHP) | PHP Kaynak Kod Dosyasını (.php) temsil eder. |
| [PL](#PL) | Perl Betiğini (.pl) temsil eder. |
| [PROPERTIES](#PROPERTIES) | Java Özellik Dosyasını (.properties) temsil eder. |
| [PY](#PY) | Python Betiğini (.py) temsil eder. |
| [RB](#RB) | Ruby Kaynak Kod (.rb) dosyasını temsil eder. |
| [RST](#RST) | reStructuredText Dosyasını (.rst) temsil eder. |
| [SASS](#SASS) | Syntactically Awesome StyleSheets Dosyasını (.sass) temsil eder. |
| [SCALA](#SCALA) | Scala Kaynak Kod Dosyasını (.scala) temsil eder. |
| [SCM](#SCM) | Scheme Kaynak Kod Dosyasını (.scm) temsil eder. |
| [SCRIPT](#SCRIPT) | Genel Betik Dosyasını (.script) temsil eder. |
| [SH](#SH) | Bash Kabuk Betiğini (.sh) temsil eder. |
| [SML](#SML) | Standard ML Kaynak Kod Dosyasını (.sml) temsil eder. |
| [SQL](#SQL) | Structured Query Language Veri Dosyasını (.sql) temsil eder. |
| [VIM](#VIM) | Vim Ayar Dosyasını (.vim) temsil eder. |
| [YAML](#YAML) | YAML Belgesini (.yaml) temsil eder. |
| [DOC](#DOC) | Microsoft Word Belgesini (.doc) dosyasını temsil eder. |
| [DOCX](#DOCX) | Microsoft Word Open XML Belgesini (.docx) dosyasını temsil eder. |
| [CHM](#CHM) | Microsoft Derlenmiş HTML Yardım Dosyasını (.chm) temsil eder. |
| [DOCM](#DOCM) | Word Open XML Makro Etkin Belgesini (.docm) dosyasını temsil eder. |
| [DOT](#DOT) | Word Belge Şablonunu (.dot) dosyasını temsil eder. |
| [DOTX](#DOTX) | Word Open XML Document Template (.dotx) dosyasını temsil eder. |
| [DOTM](#DOTM) | Word Open XML Macro-Enabled Document Template (.dotm) dosyasını temsil eder. |
| [RTF](#RTF) | Rich Text Format Dosyasını (.rtf) temsil eder. |
| [TXT](#TXT) | Plain Text Dosyasını (.txt) temsil eder. |
| [ODT](#ODT) | OpenDocument Text Document (.odt) dosyasını temsil eder. |
| [OTT](#OTT) | OpenDocument Document Template (.ott) dosyasını temsil eder. |
| [VCF](#VCF) | vCard Dosyasını (.vcf) temsil eder, ki bu iletişim bilgilerini depolamak için kullanılan dijital bir dosya formatıdır. |
| [AI](#AI) | Adobe Illustrator dosyasını (.ai) temsil eder, ki bu Adobe Illustrator çizimleri için bir dosya formatıdır. |
| [PSM1](#PSM1) | PowerShell script module dosyasını (.psm1) temsil eder. |
| [PS1](#PS1) | PowerShell script dosyasını (.ps1) temsil eder. |
| [PSD1](#PSD1) | PowerShell script module manifest dosyasını (.psd1) temsil eder. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Bir dosya uzantısını bir dosya türüne eşler. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Bir dosya adından veya dosya yolundan dosya uzantısını çıkarır ve onu bir dosya türüne eşler. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Bir dosya medya türünü bir dosya türüne eşler. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Dosya imzasını okuyarak dosya türünü algılar. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Dosya imzasını okuyarak dosya türünü algılar. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Dosya imzasını okuyarak dosya türünü algılar. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Dosya imzasını okuyarak dosya türünü algılar. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Desteklenen dosya türlerini alır. |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Yol üzerinden [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) ve [CSV](../../com.groupdocs.viewer/filetype\#CSV) dosyalarının karakter kümesini tespit etmeye çalışır. |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Akış üzerinden [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) ve [CSV](../../com.groupdocs.viewer/filetype\#CSV) dosyasının karakter kümesini tespit etmeye çalışır. |
| [getFileFormat()](#getFileFormat--) | Dosya formatının adını alır, ör. "Microsoft Word Document". |
| [getExtension()](#getExtension--) | Dosya uzantısı soneki (nokta "." dahil) alır, ör. ".doc". |
| [toString()](#toString--) | Geçerli nesnenin string temsilini döndürür. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Bilinmeyen bir dosya tipini temsil eder.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Birden fazla dosya veya dizin tutabilen sıkıştırılmış dosyayı (.zip) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Birden fazla dosya toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tar) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


LZMA algoritmasına dayalı yüksek oranlı sıkıştırma algoritmasıyla sıkıştırılmış XZ dosyasını (.xz) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Birden fazla dosya toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.txz, .tar.xz) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Birden fazla dosya toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.txz, .tar.xz) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Birden fazla dosya toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tgz, .tar.gz) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Birden fazla dosya toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tgz, .tar.gz) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


BZIP2 açık kaynak sıkıştırma yöntemi kullanılarak oluşturulan bir Bzip2 sıkıştırılmış dosyayı (.bz2) temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


RAR (WINRAR sürüm 4) sıkıştırma yöntemi kullanılarak oluşturulan bir Roshal Arşivi (.rar) sıkıştırılmış dosyayı temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


gzip sıkıştırma uygulamasıyla oluşturulan bir Gnu Zipped File (.gz) sıkıştırılmış dosyayı temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Unix sistemlerinde kullanılan Compress programının yerine ücretsiz bir yardımcı program olarak tanıtılan bir Gnu Zipped File (.gzip) sıkıştırılmış dosyayı temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


LZMA ve LZMA2 sıkıştırmasıyla ücretsiz açık kaynak arşivleyici olan bir 7Zip (.7z, .7zip) dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio, genel bir dosya arşivleme yardımcı programı ve ilişkili dosya formatıdır. Öncelikle Unix benzeri bilgisayar işletim sistemlerine kurulur. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST dosyası, Zstandard (zstd) sıkıştırma algoritmasıyla oluşturulan bir sıkıştırılmış dosyadır. Algoritma tarafından kayıpsız sıkıştırma ile yaratılan bir dosyadır. ZST dosyaları, veritabanları, dosya sistemleri, ağlar ve oyunlar gibi farklı dosya türlerini sıkıştırmak için kullanılabilir. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


TZST dosyaları (.tar.zst, .tzst), içinde birleştirilmiş Unix Dosya Arşivi (Tar) bulunan Zstandard arşivleridir (ZST) ve bir veya daha fazla dosyayı toplamak için Unix tabanlı bir yardımcı programla oluşturulmuştur.

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST dosyaları (.tar.zst, .tzst), içinde birleştirilmiş Unix Dosya Arşivi (Tar) bulunan Zstandard arşivleridir (ZST) ve bir veya daha fazla dosyayı toplamak için Unix tabanlı bir yardımcı programla oluşturulmuştur.

### ISO {#ISO}
```
public static final FileType ISO
```


ISO optik disk görüntüsü, CD veya DVD gibi bir optik diskin tüm verilerini temsil eden, ISO-9660 standardına dayalı sıkıştırılmamış bir arşiv disk görüntü dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA veya LZH, ücretsiz bir sıkıştırma yardımcı programı ve ilişkili dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (veya CAB), Microsoft Windows için bir arşiv dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


Drawing Exchange Format File (.dxf) dosyasını temsil eder, bu dosya AutoCAD çizim dosyasının etiketli veri temsili olarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


AutoCAD Drawing Database File (.dwg) dosyasını temsil eder; bu dosya 2D ve 3D tasarım verilerini içeren özel ikili dosyalardır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


AutoCAD Drawing Template (.dwt) dosyasını temsil eder; bu, DWG dosyaları olarak kaydedilebilecek çizimler oluşturmak için başlangıç olarak kullanılan bir AutoCAD çizim şablonu dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Stereolithography File (.stl) dosyasını temsil eder; bu, üç boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatıdır. Hızlı prototipleme, 3D baskı ve bilgisayar destekli imalatta yaygın olarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Industry Foundation Classes File (.ifc) dosyasını temsil eder; bu, bina nesneleri ve özelliklerinin içe ve dışa aktarımı için uluslararası standartlar belirleyen bir dosya formatıdır. Farklı yazılım uygulamaları arasında birlikte çalışabilirliği sağlar. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Design Web Format File (.dwf) dosyasını temsil eder; bu, 2D/3D çizimleri görüntüleme, inceleme veya yazdırma için sıkıştırılmış bir dosya formatıdır. Tasarım verisinin bir parçası olarak grafik ve metin içerir ve sıkıştırma sayesinde dosya boyutunu azaltır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Autodesk FBX Interchange File (FilmBoX) (.fbx) dosyasını temsil eder; bu bir 3D model formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Design Web Format File XPS (.dwfx) dosyasını temsil eder; bu, 2D/3D çizimleri XPS belgesi olarak görüntüleme, inceleme veya yazdırma için sıkıştırılmış bir formattır. Tasarım verisinin bir parçası olarak grafik ve metin içerir ve sıkıştırma sayesinde dosya boyutunu azaltır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


MicroStation Design File (.dgn) dosyasını temsil eder; bu, MicroStation ve Intergraph Interactive Graphics Design System gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Autodesk, Inc. tarafından tanıtılan vektör tabanlı bir plotter dosyası olan PLT (HPGL) Dosyasını (.plt) temsil eder. Belirli bir CAD dosyası için bilgi içerir ve tüm görüntüler noktalar yerine çizgilerle basılır, üretimde doğruluk ve hassasiyet sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Common File Format Dosyasını (.cf2) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Wavefront Technologies tarafından tanıtılan 3D görüntü dosyası olan Wavefront 3D Object Dosyasını (.obj) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


PLT (HPGL) Dosyasını (.hpg) temsil eder. HP Graphics Language (HPGL) içinde plotter dosyaları için kullanılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Initial Graphics Exchange Specification (IGES) Dosyasını (.igs) temsil eder.

### VSD {#VSD}
```
public static final FileType VSD
```


Microsoft Visio uygulamasıyla oluşturulan ve çeşitli grafik nesneleri ile bunların bağlantılarını temsil eden çizimler olan Visio Drawing Dosyasını (.vsd) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eden Visio Drawing Dosyasını (.vsdx) temsil eder. Önceki Visio sürümlerinin desteklediği ikili dosya formatı (.VSD) yerine geçmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Microsoft Visio 2007 ve öncesi sürümlerle oluşturulan şablon dosyaları olan Visio Stencil Dosyasını (.vss) temsil eder. Şablon dosyaları, .VSD Visio çizimine eklenebilen çizim nesneleri sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablonları olan Visio Stencil Dosyasını (.vssx) temsil eder. VSSX dosya formatı Visio 2013 ve üzeri sürümlerle açılabilir. Visio dosyaları şekiller, bağlayıcılar, akış şemaları, ağ düzeni, UML diyagramları vb. gibi çeşitli çizim öğelerini temsil etmesiyle bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyaları olan Visio Macro-Enabled Drawing (.vsdm) dosyasını temsil eder. VSDM dosyaları VSDX'e benzer OPC/XML çizimleridir, ancak dosya açıldığında makroların çalıştırılmasını da sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Microsoft Visio ile oluşturulan vektör görüntü dosyaları olan Visio Drawing Template (.vst) dosyasını temsil eder. Daha sonraki dosyalar oluşturmak için şablon görevi görür ve yeni Visio çizimleri oluşturmak için kullanılan varsayılan düzen ve ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablon dosyaları olan Visio Drawing Template (.vstx) dosyasını temsil eder. Bu VSTX dosyaları, .VSDX dosyaları olarak kaydedilen Visio çizimleri oluşturmak için varsayılan düzen ve ayarlarla bir başlangıç noktası sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyaları olan Visio Macro-Enabled Drawing Template (.vstm) dosyasını temsil eder. VSTM şablonlarından oluşturulan dosyalar, Visual Basic for Applications (VBA) kodunda geliştirilen makroları çalıştırabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Makroları destekleyen Microsoft Visio Stencil dosyaları olan Visio Macro-Enabled Stencil File (.vssm) dosyasını temsil eder. Bir VSSM dosyası açıldığında, diyagramdaki şekillerin istenen biçimlendirilmesi ve yerleştirilmesi için makrolar çalıştırılabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Microsoft Visio'da diyagram oluşturmak için kullanılan çizimler ve şekillerden oluşan şablonları ifade eden Visio Stencil XML Dosyasını (.vsx) temsil eder. VSX dosyaları XML dosya formatında kaydedilir ve Visio 2013'e kadar desteklenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonu olan Visio Template XML Dosyasını (.vtx) temsil eder. Şablon, aynı ayarlarla birden fazla Visio dosyası oluşturmak için temel ayarları sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Web çiziminin renderlanması için gereken akışları ve depolamaları belirten Visio Web Drawing (.vdw) dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Çizim XML Dosyası (.vdx) temsil eder, bu dosya Microsoft Visio'da oluşturulan ve .VDX uzantısıyla XML formatında kaydedilen herhangi bir çizim veya grafiği temsil eder. Bir Visio çizim XML dosyası, Microsoft tarafından geliştirilen Visio yazılımında oluşturulur. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook Dosyası (.epub) temsil eder, bu e-kitap dosya formatı yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlar. Format birçok e-okuyucu ve yazılım uygulaması tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket eBook (.mobi) temsil eder, bu en yaygın kullanılan e-kitap dosya formatlarından biridir. Format, eski OEB (Open Ebook Format) formatının bir geliştirmesidir ve Mobipocket Reader için özel bir format olarak kullanılmıştır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) e-kitap, Amazon Kindle cihazları için geliştirilen dijital dosya formatıdır. Format, eski AZW dosyalarının bir geliştirmesidir ve yalnızca Kindle Fire cihazlarında, önceki dosya formatı olan MOBI ve AZW ile geriye dönük uyumluluk sağlayarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Outlook Mail Message (.msg) temsil eder, bu Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişiler, randevular veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


E-Mail Message (.eml) temsil eder, bu Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. Neredeyse tüm e-posta istemcileri, RFC-822 Internet Message Format Standardına uyumu nedeniyle bu dosya formatını destekler. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail Message (.emlx) temsil eder, bu Apple tarafından uygulanıp geliştirilen bir formattır. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya formatını kullanır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Outlook Personal Information Store File (.pst) temsil eder, bu Outlook Kişisel Depolama Dosyalarını (Personal Storage Table olarak da adlandırılır) temsil eder ve çeşitli kullanıcı bilgilerini depolar. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Outlook Offline Data File (.ost) temsil eder, bu Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel bir makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Tagged Image File (.tif) temsil eder, bu dosya formatı standardına uyan çeşitli cihazlarda kullanılmak üzere raster görüntüleri temsil eder. Birkaç renk uzayında iki seviyeli, gri tonlamalı, palet renkli ve tam renkli görüntü verilerini tanımlayabilir. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Tagged Image File Format (.tiff) temsil eder, bu dosya formatı standardına uyan çeşitli cihazlarda kullanılmak üzere raster görüntüleri temsil eder. Birkaç renk uzayında iki seviyeli, gri tonlamalı, palet renkli ve tam renkli görüntü verilerini tanımlayabilir. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG Image (.jpg) temsil eder, bu kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatıdır. Sıkıştırma sonucunda ortaya çıkan çıktı görüntüsü, depolama boyutu ile görüntü kalitesi arasında bir denge sağlar. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) temsil eder, bu kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatıdır. Sıkıştırma sonucunda ortaya çıkan çıktı görüntüsü, depolama boyutu ile görüntü kalitesi arasında bir denge sağlar. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG File Interchange Format (.jfif), platformlar arasında hızlı değişim için geliştirilen bir görüntüdür. Bu format JPEG sıkıştırması kullanır. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) temsil eder, bu kayıpsız sıkıştırma kullanan bir raster görüntü dosya formatıdır. Bu dosya formatı, Graphics Interchange Format (GIF) yerine geçecek şekilde oluşturulmuş ve telif hakkı sınırlamaları yoktur. Bu dosya formatı hakkında daha fazla bilgi için [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Grafik Değişim Formatı Dosyasını (.gif) temsil eder, bu yüksek sıkıştırmalı bir görüntü türüdür. Her görüntü için GIF tipik olarak piksel başına en fazla 8 bit ve görüntü genelinde en fazla 256 renk izin verir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Animasyonlu Taşınabilir Ağ Grafiği (.apng) dosyasını temsil eder, bu PNG formatının animasyonu destekleyen bir uzantısıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Görüntü Dosyasını (.bmp) temsil eder, bu bitmap dijital görüntüleri depolamak için kullanılır. Bu görüntüler grafik adaptöründen bağımsızdır ve cihaz bağımsız bitmap (DIB) dosya formatı olarak da adlandırılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Simge Dosyasını (.ico) temsil eder, bu Microsoft Windows'ta bir uygulamanın temsili için simge olarak kullanılan bir görüntü dosyası türüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Truevision TGA (TARGA) dosyasını temsil eder, bu TRUEVISION tarafından geliştirilen bitmap dijital görüntüleri depolamak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


JPEG 2000 Çekirdek Görüntü Dosyasını (.jp2) temsil eder, bu bir görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


JPEG 2000 Görüntü Dosyasını (.jpf) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


JPEG 2000 Görüntü Dosyasını (.jpx) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


JPEG 2000 Görüntü Dosyasını (.jpm) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


JPEG 2000 Kod Giriş Akışını (.j2c) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


JPEG 2000 Kod Akışını (.j2k) temsil eder, bu DCT sıkıştırması yerine dalgacık sıkıştırması kullanılan bir görüntüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


JPEG 2000 Kod Akışını (.jpc) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


JPEG-LS (JLS) dosyasını (.jls) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Cihaz Bağımsız Bitmap Dosyasını (.dib) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Windows Metafile'ını (.wmf) temsil eder, bu Microsoft Windows Metafile (WMF) olarak vektör ve bitmap formatındaki görüntü verilerini depolamak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Sıkıştırılmış Windows Metafile'ını (.wmz) temsil eder, bu GZIP arşivinde sıkıştırılmış Microsoft Windows Metafile (WMF) olup vektör ve bitmap formatındaki görüntü verilerini depolar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Gelişmiş Windows Metafile'ını (.emf) temsil eder, bu grafik görüntüleri cihaz bağımsız şekilde temsil eder. EMF metafile'ları, saklanan görüntüyü herhangi bir çıktı cihazında ayrıştırdıktan sonra render edebilen, kronolojik sırada değişken uzunlukta kayıtlar içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows Sıkıştırılmış Gelişmiş Metafile'ını (.emz) temsil eder, bu GZIP ile sıkıştırılmış cihaz bağımsız grafik görüntülerdir. EMF metafile'ları, saklanan görüntüyü herhangi bir çıktı cihazında ayrıştırdıktan sonra render edebilen, kronolojik sırada değişken uzunlukta kayıtlar içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


WebP Görüntüsünü (.webp) temsil eder, bu kayıpsız ve kayıplı sıkıştırmaya dayalı modern bir raster web görüntü dosya formatıdır. Görüntü kalitesini korurken dosya boyutunu önemli ölçüde azaltır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Digital Negative Specification'ı (.dng) temsil eder, bu ham dosyaların depolanması için kullanılan bir dijital kamera görüntü formatıdır. Adobe tarafından Eylül 2004'te geliştirilmiş olup öncelikle dijital fotoğrafçılıkta kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


CorelDraw Vektör Grafik Çizimini (.cdr) temsil eder, bu CorelDRAW ile yerel olarak oluşturulan ve dijital olarak kodlanmış ve sıkıştırılmış görüntüleri depolamak için kullanılan bir vektör çizim dosyasıdır. Bir CDR çizim dosyası, metin, çizgiler, şekiller, görüntüler, renkler ve vektör temsili için efektler içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Corel Exchange'i (.cmx) temsil eder, bu vektör grafiklerin yanı sıra bitmap grafikler de içerebilen bir çizim görüntü dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


DjVu Görüntüsü (.djvu) temsil eder, bu, taranmış belgeler ve kitaplar için tasarlanmış bir grafik dosya formatıdır, özellikle metin, çizimler, görüntüler ve fotoğrafların bir kombinasyonunu içerenler. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Bilgisayar Grafik Metadosyası (.cgm) temsil eder, bu, vektör grafikler (2D), raster grafikler ve metinleri depolamak ve değiştirmek için ücretsiz, platform bağımsız, uluslararası standart bir metafile formatıdır. CGM nesne yönelimli bir yaklaşım kullanır ve görüntü üretimi için birçok işlev sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Yazıcı Komut Dili Belgesi (.pcl) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Adobe Photoshop Belgesi (.psd) temsil eder, bu Adobe Photoshop'un grafik tasarımı ve geliştirme için kullandığı yerel dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Photoshop Büyük Belge Formatı (.psb) temsil eder, bu Adobe Photoshop'ta grafik tasarımı ve geliştirme için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


DICOM Görüntüsü (.dcm) temsil eder, bu, MR, BT taramaları ve ultrason görüntüleri gibi hastaların tıbbi bilgilerini depolayan dijital bir görüntüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


PostScript Dosyası (.ps) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Encapsulated PostScript Dosyası (.eps) temsil eder, bu, tek bir sayfanın görünümünü tanımlayan bir Encapsulated PostScript dil programını açıklar. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


OpenDocument Grafik Dosyası (.odg) temsil eder, bu Apache OpenOffice'un Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Düz XML ODF Şablonu (.fodg) temsil eder, bu Apache OpenOffice'un Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Scalable Vector Graphics Dosyası (.svg) temsil eder, bu, bir görüntünün görünümünü tanımlamak için XML tabanlı metin formatı kullanan bir Scalable Vector Graphics dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Sıkıştırılmış Scalable Vector Graphics Dosyası (.svgz) temsil eder, bu, bir görüntünün görünümünü tanımlamak için XML tabanlı metin formatı kullanan ve GZIP ile sıkıştırılmış bir Scalable Vector Graphics dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


OpenDocument Grafik Şablonu (.otg) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Hypertext Markup Language Dosyası (.htm) temsil eder, bu, tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language Dosyası (.html) temsil eder, bu, tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Arşivi (.mht) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Lotus Notes Veritabanı (.nsf) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


E-posta Posta Kutusu Dosyası (.mbox) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML Dosyası (.mhtml) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


XML Dosyası (.xml) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote uygulaması tarafından oluşturulan OneNote Belgesi (.one) temsil eder. OneNote, uygulamayı not almak için bir taslak defteri gibi kullanarak bilgi toplamanıza olanak tanır. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Taşınabilir Belge Formatı Dosyası (.pdf) temsil eder, bu, 1990'larda Adobe tarafından oluşturulan bir belge türüdür. Bu dosya formatının amacı, uygulama yazılımı, donanım ve işletim sistemlerinden bağımsız bir formatta belgeler ve diğer referans materyallerinin temsil edilmesi için bir standart getirmekti. Bu dosya formatı hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Microsoft tarafından oluşturulan XML Paper Specification (XML Kağıt Özellikleri) tabanlı sayfa düzeni dosyalarını temsil eden bir XML Paper Specification Dosyası (.xps) temsil eder. Bu format, Microsoft tarafından EMF dosya formatının yerine geliştirilmiş olup PDF dosya formatına benzer, ancak bir belgenin düzen, görünüm ve baskı bilgilerinde XML kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


Bir OpenXPS Dosyasını (.oxps) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


Bir LaTeX Kaynak Belgesini (.tex) temsil eder; bu, belgeleri biçimlendirmek için programlama ve işaretleme özelliklerini içeren bir dildir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Bir PowerPoint Sunumunu (.ppt) temsil eder; bu, slayt gösterisi olarak görüntülenmek üzere bir dizi slayttan oluşan bir PowerPoint dosyasını temsil eder. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Formatını belirtir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Bir PowerPoint Open XML Sunumunu (.pptx) temsil eder; bu, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. Önceki PPT sunum dosyası formatının ikili olmasının aksine, PPTX formatı Microsoft PowerPoint Open XML sunum dosyası formatına dayanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Bir PowerPoint Slayt Gösterisini (.pps) temsil eder; bu, Microsoft PowerPoint kullanılarak Slayt Gösterisi amaçları için oluşturulur. PPS dosya okuma ve oluşturma Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Microsoft PowerPoint 2007 ve üzeri kullanılarak Slayt Gösterisi amaçları için oluşturulan PowerPoint Open XML Slayt Gösterisi (.ppsx) dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Sunumunu (.odp) temsil eder; bu, OpenOffice.org tarafından OASISOpen standardında kullanılan bir sunum dosyası formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


OpenDocument Sunumunu (.fodp) temsil eder; bu, OpenDocument Düz XML Sunumu anlamına gelir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


PowerPoint Şablonunu (.pot) temsil eder; bu, PowerPoint 97-2003 sürümleriyle oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


PowerPoint Open XML Makro Etkin Sunumunu (.pptm) temsil eder; bu, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan makro etkin sunum dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


PowerPoint Open XML Sunum Şablonunu (.potx) temsil eder; bu, Microsoft PowerPoint 2007 ve üzeri sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


PowerPoint Open XML Makro Etkin Sunum Şablonunu (.potm) temsil eder; bu, makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM dosyaları PowerPoint 2007 veya üzeri sürümlerle oluşturulur ve daha fazla sunum dosyası oluşturmak için kullanılabilecek varsayılan ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


PowerPoint Open XML Makro Etkin Slaytı (.ppsm) temsil eder; bu, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan makro etkin slayt gösterisi dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Sunum Şablonunu (.otp) temsil eder; bu, OASIS OpenDocument standart formatındaki uygulamalar tarafından oluşturulan sunum şablon dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Çalışma Sayfasını (.xls) temsil eder; bu, Excel İkili Dosya Formatını temsil eder. Bu tür dosyalar Microsoft Excel ve OpenOffice Calc veya Apple Numbers gibi benzer elektronik tablo programlarıyla oluşturulabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Excel 2003 XML (SpreadsheetML) (.xml) dosyasını temsil eder; bu, Excel İkili Dosya Formatını temsil eder. Bu tür dosyalar Microsoft Excel ve OpenOffice Calc veya Apple Numbers gibi benzer elektronik tablo programlarıyla oluşturulabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Apple Numbers (.numbers) temsil eder, bu da Excel benzeri bir İkili Dosya Biçimini temsil eder. Bu dosyalar Apple Numbers uygulamasıyla oluşturulabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) temsil eder, bu da Microsoft Office 2007 sürümüyle Microsoft tarafından tanıtılan Microsoft Excel belgeleri için iyi bilinen bir biçimdir. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) temsil eder, bu da makroları destekleyen bir elektronik tablo dosyası türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) temsil eder, bu da Excel Binary File Format'ı tanımlar. Bu, Excel çalışma kitabı içeriğini belirten kayıtlar ve yapılar koleksiyonudur. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv) temsil eder, bu da virgülle ayrılmış değerlerle veri kayıtları içeren düz metin dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv) temsil eder, bu da sekmelerle ayrılmış verileri düz metin biçiminde temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods) temsil eder, bu da kullanıcının düzenleyebileceği OpenDocument Spreadsheet Document formatını ifade eder. Veriler ODF dosyalarında satır ve sütunlar halinde depolanır. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


OpenDocument Flat XML Spreadsheet (.fods) temsil eder. Bu, OpenOffice ve LibreOffice tarafından kullanılan XML tabanlı bir elektronik tablo belge formatıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


OpenDocument Spreadsheet Template (.ots) temsil eder. Bu, OpenOffice ve LibreOffice tarafından elektronik tablolar için kullanılan bir şablon belge formatıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Microsoft Excel Add-in (.xlam) temsil eder. Bu, Microsoft Excel tarafından özel işlevsellik sağlayan eklentiler oluşturmak için kullanılan bir dosya biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel Macro-Enabled Template (.xltm) temsil eder, bu da Microsoft Excel tarafından makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları yapısal olarak XLTX'ye benzer, ancak ikincisi makrolu şablon dosyaları oluşturmayı desteklemez. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel Template (.xlt) temsil eder, bu da Microsoft Office paketinin bir parçası olan elektronik tablo uygulaması Microsoft Excel ile oluşturulan şablon dosyalarıdır. Microsoft Office 97-2003 yeni XLT dosyaları oluşturmayı ve açmayı desteklemiştir. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) temsil eder, bu da Office OpenXML dosya formatı spesifikasyonlarına dayalı Microsoft Excel Şablonlarını temsil eder. Bu, XLTX dosyasında belirtilen aynı ayarlarla XLSX dosyaları oluşturmak için kullanılabilecek standart bir şablon dosyası yaratmak amacıyla kullanılır. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


StarOffice Calc Spreadsheet (.sxc) temsil eder. Bu, bir elektronik tablo programı olan StarOffice Calc ile oluşturulan bir elektronik tablo belgesidir. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Microsoft Project File (.mpp) temsil eder, bu da proje yönetimiyle ilgili bilgileri bütünleşik bir şekilde depolayan bir Microsoft Project veri dosyasıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Microsoft Project Template (.mpt) temsil eder, bu da .MPP dosyaları oluşturmak için temel bilgi ve yapı ile belge ayarlarını içerir. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Microsoft Project Exchange file (.mpx) temsil eder, bu da Microsoft Project (MSP) ile MPX dosya formatını destekleyen diğer uygulamalar (örneğin Primavera Project Planner, Sciforma ve Timerline Precision Estimating) arasında proje bilgisi aktarımı için kullanılan bir ASCII dosya formatıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


ActionScript File (.as) temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


ActionScript File (.as3) temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


Assembly Dili Kaynak Kodu Dosyasını (.asm) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


DOS Toplu İş Dosyasını (.bat) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


C/C++ Kaynak Kodu Dosyasını (.c) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


C++ Kaynak Kodu Dosyasını (.cc) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


CMake Dosyasını (.cmake) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


C++ Kaynak Kodu Dosyasını (.cpp) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


C\# Kaynak Kodu Dosyasını (.cs) temsil eder, bu dosya C\# programlama dili için bir kaynak kod dosyasıdır. Microsoft tarafından .NET Framework ile kullanılmak üzere tanıtılmıştır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Visual Basic Proje Öğesi Dosyasını (.vb) temsil eder, bu dosya Visual Basic dilinde oluşturulmuş bir kaynak kod dosyasıdır. Microsoft tarafından .NET uygulamaları geliştirmek için oluşturulmuştur. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Cascading Style Sheet (.css) dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


C++ Kaynak Kodu Dosyasını (.cxx) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Yama Dosyasını (.diff) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Ruby ERB Betiğini (.erb) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy Kaynak Kodu Dosyasını (.groovy) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


C/C++/Objective-C Başlık Dosyasını (.h) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Haml Kaynak Kodu Dosyasını (.haml) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


C++ Başlık Dosyasını (.hh) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java Kaynak Kodu Dosyasını (.java) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


JavaScript Dosyasını (.js) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


JavaScript Object Notation Dosyasını (.json) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


LESS Stil Sayfası (.less) dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


Log Dosyasını (.log) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Objective-C Uygulama Dosyasını (.m) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Xcode Makefile Betiğini (.make) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Markdown Dokümantasyon Dosyasını (.md) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


ML Kaynak Kodu Dosyasını (.ml) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Objective-C++ Kaynak Dosyasını (.mm) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


PHP Kaynak Kod Dosyasını (.php) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Perl Betiğini (.pl) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Java Özellikleri Dosyasını (.properties) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Python Betiğini (.py) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Ruby Kaynak Kod Dosyasını (.rb) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


reStructuredText Dosyasını (.rst) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Syntactically Awesome StyleSheets Dosyasını (.sass) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala Kaynak Kod Dosyasını (.scala) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Scheme Kaynak Kod Dosyasını (.scm) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Genel Betik Dosyasını (.script) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Bash Kabuk Betiğini (.sh) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Standard ML Kaynak Kod Dosyasını (.sml) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language Veri Dosyasını (.sql) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Vim Ayarları Dosyasını (.vim) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


YAML Belgesini (.yaml) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Belgesini (.doc) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Belgesini (.docx) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Microsoft Derlenmiş HTML Yardım Dosyasını (.chm) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Makro Etkin Belgesini (.docm) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Belge Şablonunu (.dot) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Belge Şablonunu (.dotx) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Makro Etkin Belge Şablonunu (.dotm) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format Dosyasını (.rtf) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Düz Metin Dosyasını (.txt) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Metin Belgesi (.odt) temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [buraya][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Belge Şablonu (.ott) temsil eder. OASIS'in OpenDocument standart formatına uygun olarak oluşturulmuş bir şablon belgedir. Bu dosya formatı hakkında daha fazla bilgi için [buraya][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


vCard Dosyası (.vcf) temsil eder; bu, iletişim bilgilerini depolamak için kullanılan dijital bir dosya formatıdır. Popüler bilgi değişim uygulamaları arasında veri alışverişi için yaygın olarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi için [buraya][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Adobe Illustrator dosyası (.ai) temsil eder; bu, Adobe Illustrator çizimleri için bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [buraya][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


PowerShell betik modülü dosyası (.psm1) temsil eder. PowerShell modül betikleri için bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [buraya][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


PowerShell betik dosyası (.ps1) temsil eder. Windows PowerShell Cmdlet dosyaları için bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [buraya][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


PowerShell betik modülü manifest dosyası (.psd1) temsil eder. PowerShell modül manifest betikleri için bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [buraya][].


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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Bir dosya uzantısını bir dosya türüne eşler.

Bu yöntem, dosya uzantısını nokta "." ile birlikte ya da olmadan alır ve destekleniyorsa karşılık gelen dosya türünü döndürür. Dosya türü desteklenmiyorsa, varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) dosya türünü döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| extension | java.lang.String | Nokta "." ile birlikte ya da olmadan dosya uzantısı. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Bir dosya adından veya dosya yolundan dosya uzantısını çıkarır ve onu bir dosya türüne eşler.

Dosya türü destekleniyorsa, yöntem karşılık gelen FileType'ı döndürür, aksi takdirde varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) dosya türünü döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya adı veya dosya yolu. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Bir dosya medya türünü dosya türüne eşler. Örneğin, 'application/pdf' [PDF](../../com.groupdocs.viewer/filetype\#PDF) türüne eşlenecektir.

Bu yöntem, dosya medya türünü girdi olarak alır ve karşılık gelen FileType'a eşler. Medya türü destekleniyorsa, yöntem karşılık gelen dosya türünü döndürür. Medya türü desteklenmiyorsa, varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) dosya türünü döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mediaType | java.lang.String | Dosya medya türü, ör. 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Dosya imzasını okuyarak dosya türünü algılar.

Bu yöntem, bir dosyayı temsil eden giriş akışını alır ve dosya imzasını analiz ederek dosya türünü tespit etmeye çalışır. Dosya imzası, dosyanın başında bulunan ve dosya türünü gösteren benzersiz bir bayt dizisidir. Yöntem, dosya imzasını giriş akışından okur ve desteklenen dosya türlerinin bilinen imzalarıyla eşleştirir. Eşleşme bulunursa, yöntem karşılık gelen dosya türünü döndürür. Eşleşme bulunmazsa, varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) dosya türünü döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Dosyayı temsil eden giriş akışı. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Dosya imzasını okuyarak dosya türünü algılar.

Bu yöntem, dosyanın başındaki benzersiz bayt dizisi olan dosya imzasını analiz ederek dosya türünü belirler. Sağlanan giriş akışından dosya imzasını okur ve desteklenen dosya türlerinin bilinen imzalarıyla eşleştirir. Eşleşme bulunursa, yöntem karşılık gelen dosya türünü döndürür. Eşleşme bulunmazsa, varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) dosya türünü döndürür.

Dosya şifrelenmiş ve açmak için bir şifre gerektiriyorsa, şifre bu yönteme parametre olarak sağlanmalıdır. Şifre, dosyayı çözmek ve dosya türünü belirlemek için imzasını analiz etmek amacıyla kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Dosyayı temsil eden giriş akışı. |
| password | java.lang.String | Dosyayı açmak için şifre. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Dosya imzasını okuyarak dosya türünü algılar.

Bu yöntem, dosyanın başındaki benzersiz bayt dizisi olan dosya imzasını analiz ederek dosya türünü belirler. Sağlanan giriş akışından dosya imzasını okur ve desteklenen dosya türlerinin bilinen imzalarıyla eşleştirir. Eşleşme bulunursa, yöntem karşılık gelen dosya türünü döndürür. Eşleşme bulunmazsa, varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) dosya türünü döndürür.

Dosya türü tespit süreci sırasında ilgili bilgi veya hataları kaydetmek için bir logger sağlanabilir. Logger, ILogger arayüzünü uygulamalıdır. Eğer bir logger sağlanmazsa, tespit süreci herhangi bir log çıktısı üretmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Dosyayı temsil eden giriş akışı. |
| logger | com.groupdocs.foundation.logging.ILogger | Bilgi veya hataları kaydetmek için logger. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Dosya imzasını okuyarak dosya türünü algılar.

Bu yöntem, dosyanın başındaki benzersiz bayt dizisi olan dosya imzasını analiz ederek dosya türünü belirler. Sağlanan giriş akışından dosya imzasını okur ve desteklenen dosya türlerinin bilinen imzalarıyla eşleştirir. Eşleşme bulunursa, yöntem karşılık gelen dosya türünü döndürür. Eşleşme bulunmazsa, varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) dosya türünü döndürür.

Dosya şifrelenmiş veya korunmuşsa bir şifre sağlanabilir. Şifre, dosya imzasını analiz etmeden önce dosyayı açmak için kullanılacaktır. Dosyanın şifre gerektirmemesi durumunda bu parametre null olarak ayarlanabilir.

Dosya türü tespit süreci sırasında ilgili bilgi veya hataları kaydetmek için bir logger sağlanabilir. Logger, ILogger arayüzünü uygulamalıdır. Eğer bir logger sağlanmazsa, tespit süreci herhangi bir log çıktısı üretmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Dosyayı temsil eden giriş akışı. |
| password | java.lang.String | Dosyayı açmak için şifre. |
| logger | com.groupdocs.foundation.logging.ILogger | Bilgi veya hataları kaydetmek için logger. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Desteklenen dosya türlerini alır.

Bu yöntem, sistem tarafından desteklenen tüm dosya türlerinin bir dizisini döndürür. Dosya türleri, sistem tarafından işlenebilen veya tanınabilen çeşitli belge formatlarını temsil eder.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - desteklenen dosya türlerinin bir dizisi.
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Yol üzerinden [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) ve [CSV](../../com.groupdocs.viewer/filetype\#CSV) dosyalarının karakter kümesini tespit etmeye çalışır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya adı veya dosya yolu. |

**Returns:**
java.nio.charset.Charset - Charset veya dosya karakter kümesi tespit edilemediğinde null.

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Akış üzerinden [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) ve [CSV](../../com.groupdocs.viewer/filetype\#CSV) dosyasının karakter kümesini tespit etmeye çalışır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Dosya akışı. |

**Returns:**
java.nio.charset.Charset - Charset veya dosya karakter kümesi tespit edilemediğinde null.

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Dosya formatının adını alır, ör. "Microsoft Word Document".

**Returns:**
java.lang.String - dosya formatının adı.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Dosya uzantısı soneki (nokta "." dahil) alır, ör. ".doc".

**Returns:**
java.lang.String - dosya uzantısı eki.
### toString() {#toString--}
```
public String toString()
```


Geçerli nesnenin string temsilini döndürür.

**Returns:**
java.lang.String - geçerli nesnenin string temsili.
