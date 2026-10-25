---
title: "FileType"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Dosya türünü temsil eder."
type: docs
weight: 14
url: /tr/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Dosya tipini temsil eder. GroupDocs.Viewer bileşeni tarafından desteklenen tüm dosya tiplerinin bir listesini elde etmek için yöntemler sağlar.


FileType enum'ı, GroupDocs.Viewer bileşeni tarafından desteklenen farklı dosya tiplerini temsil eden sabitler sağlar.
Bu enum'daki yöntemleri kullanarak tüm desteklenen dosya tiplerinin bir listesini alabilir veya belirli bir dosya tipinin desteklenip desteklenmediğini kontrol edebilirsiniz.


Örnek kullanım:

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


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | Bilinmeyen bir dosya tipini temsil eder. |
|
|  | [ZIP](#ZIP) | Bir veya daha fazla dosya veya dizin içerebilen sıkıştırılmış bir dosyayı (.zip) temsil eder. |
|
|  | [TAR](#TAR) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tar) temsil eder. |
|
|  | [XZ](#XZ) | LZMA algoritmasına dayalı yüksek oranlı bir sıkıştırma algoritmasıyla sıkıştırılmış bir XZ dosyasını (.xz) temsil eder. |
|
|  | [TXZ](#TXZ) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.txz, .tar.xz) temsil eder. |
|
|  | [TARXZ](#TARXZ) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.txz, .tar.xz) temsil eder. |
|
|  | [TGZ](#TGZ) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tgz, .tar.gz) temsil eder. |
|
|  | [TARGZ](#TARGZ) | Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tgz, .tar.gz) temsil eder. |
|
|  | [BZ_2](#BZ-2) | BZIP2 açık kaynaklı sıkıştırma yöntemi kullanılarak oluşturulmuş bir Bzip2 sıkıştırılmış dosyayı (.bz2) temsil eder. |
|
|  | [RAR](#RAR) | RAR (WINRAR sürüm 4) sıkıştırma yöntemi kullanılarak oluşturulmuş bir Roshal Arşivi (.rar) sıkıştırılmış dosyayı temsil eder. |
|
|  | [GZ](#GZ) | gzip sıkıştırma uygulamasıyla oluşturulmuş bir Gnu Zipped File (.gz) sıkıştırılmış dosyayı temsil eder. |
|
|  | [GZIP](#GZIP) | Unix sistemlerinde kullanılan Compress programının yerine ücretsiz bir yardımcı program olarak sunulan bir Gnu Zipped File (.gzip) sıkıştırılmış dosyayı temsil eder. |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | LZMA ve LZMA2 sıkıştırmasıyla ücretsiz açık kaynaklı bir arşivleyici olan 7Zip (.7z, .7zip) dosyasını temsil eder. |
|
|  | [CPIO](#CPIO) | Cpio, genel bir dosya arşivleme yardımcı programı ve ilişkili dosya formatıdır. |
|
|  | [ZSTANDARD](#ZSTANDARD) | ZST dosyası, Zstandard (zstd) sıkıştırma algoritmasıyla oluşturulan sıkıştırılmış bir dosyadır. |
|
|  | [TZST](#TZST) | TZST dosyaları (.tar.zst, .tzst), Zstandard arşivleridir (ZST) ve içinde Unix tabanlı bir yardımcı programla bir veya daha fazla dosyayı toplamak için oluşturulan Konsolide Unix Dosya Arşivi (Tar) bulunur. |
|
|  | [TAR_ZST](#TAR-ZST) | TZST dosyaları (.tar.zst, .tzst), Zstandard arşivleridir (ZST) ve içinde Unix tabanlı bir yardımcı programla bir veya daha fazla dosyayı toplamak için oluşturulan Konsolide Unix Dosya Arşivi (Tar) bulunur. |
|
|  | [ISO](#ISO) | ISO optik disk görüntüsü, CD veya DVD gibi bir optik diskteki tüm verinin içeriğini temsil eden, ISO-9660 standardına dayalı sıkıştırılmamış bir arşiv disk görüntü dosyasıdır. |
|
|  | [LHA](#LHA) | LHA veya LZH, ücretsiz bir sıkıştırma yardımcı programı ve ilişkili dosya formatıdır. |
|
|  | [CAB](#CAB) | Cabinet (veya CAB), Microsoft Windows için bir arşiv dosya formatıdır. |
|
|  | [DXF](#DXF) | Drawing Exchange Format Dosyası (.dxf), AutoCAD çizim dosyasının etiketli veri temsili olan bir dosyayı temsil eder. |
|
|  | [DWG](#DWG) | AutoCAD Çizim Veritabanı Dosyası (.dwg), 2D ve 3D tasarım verilerini içeren özel ikili dosyaları temsil eder. |
|
|  | [DWT](#DWT) | AutoCAD Çizim Şablonu (.dwt), DWG dosyaları olarak kaydedilebilecek çizimler oluşturmak için başlangıç olarak kullanılan bir AutoCAD çizim şablonu dosyasını temsil eder. |
|
|  | [STL](#STL) | Stereolithography Dosyası (.stl), 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatını temsil eder. |
|
|  | [IFC](#IFC) | Industry Foundation Classes Dosyası (.ifc), bina nesneleri ve özelliklerinin içe ve dışa aktarımı için uluslararası standartlar belirleyen bir dosya formatını temsil eder. |
|
|  | [DWF](#DWF) | Design Web Format Dosyası (.dwf), 2D/3D çizimleri görüntüleme, inceleme veya yazdırma için sıkıştırılmış bir dosya formatını temsil eder. |
|
|  | [FBX](#FBX) | Autodesk FBX Interchange Dosyası (FilmBoX) (.fbx), 3D model formatını temsil eder. |
|
|  | [DWFX](#DWFX) | Design Web Format Dosyası XPS (.dwfx), 2D/3D çizimleri XPS belgesi olarak görüntüleme, inceleme veya yazdırma için sıkıştırılmış bir formatı temsil eder. |
|
|  | [DGN](#DGN) | MicroStation Tasarım Dosyası (.dgn), MicroStation ve Intergraph Interactive Graphics Design System gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimleri temsil eder. |
|
|  | [PLT](#PLT) | PLT (HPGL) Dosyası (.plt), Autodesk, Inc. tarafından tanıtılan vektör tabanlı bir plotter dosyasını temsil eder. |
|
|  | [CF2](#CF2) | Common File Format Dosyasını (.cf2) temsil eder. |
|
|  | [OBJ](#OBJ) | Wavefront 3D Nesne Dosyası (.obj), Wavefront Technologies tarafından tanıtılan bir 3D görüntü dosyasını temsil eder. |
|
|  | [HPG](#HPG) | PLT (HPGL) Dosyasını (.hpg) temsil eder. |
|
|  | [IGS](#IGS) | Initial Graphics Exchange Specification (IGES) Dosyasını (.igs) temsil eder. |
|
|  | [VSD](#VSD) | Visio Çizim Dosyası (.vsd), çeşitli grafik nesneleri ve bunların bağlantılarını temsil etmek için Microsoft Visio uygulamasıyla oluşturulan çizimleri temsil eder. |
|
|  | [VSDX](#VSDX) | Visio Çizim Dosyası (.vsdx), Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eder. |
|
|  | [VSS](#VSS) | Visio Şablon Dosyası (.vss), Microsoft Visio 2007 ve öncesiyle oluşturulan şablon dosyalarını temsil eder. |
|
|  | [VSSX](#VSSX) | Visio Şablon Dosyası (.vssx), Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablonlarını temsil eder. |
|
|  | [VSDM](#VSDM) | Visio Makro Etkin Çizimi (.vsdm), makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarını temsil eder. |
|
|  | [VST](#VST) | Visio Çizim Şablonu (.vst), Microsoft Visio ile oluşturulan vektör görüntü dosyalarıdır. |
|
|  | [VSTX](#VSTX) | Visio Çizim Şablonu (.vstx), Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablonu dosyalarıdır. |
|
|  | [VSTM](#VSTM) | Visio Makro Destekli Çizim Şablonu (.vstm), makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. |
|
|  | [VSSM](#VSSM) | Visio Makro Destekli Şablon Dosyası (.vssm), makroları destekleyen Microsoft Visio Şablon dosyalarıdır. |
|
|  | [VSX](#VSX) | Visio Şablon XML Dosyası (.vsx), Microsoft Visio'da diyagram oluşturmak için kullanılan çizimler ve şekillerden oluşan şablonları ifade eder. |
|
|  | [VTX](#VTX) | Visio Şablon XML Dosyası (.vtx), diske XML dosya formatında kaydedilen bir Microsoft Visio çizim şablonudur. |
|
|  | [VDW](#VDW) | Visio Web Çizimi (.vdw), bir web çiziminin işlenmesi için gereken akışları ve depolamaları belirler. |
|
|  | [VDX](#VDX) | Visio Çizim XML Dosyası (.vdx), Microsoft Visio'da oluşturulan ve .VDX uzantısıyla XML formatında kaydedilen herhangi bir çizim veya grafiği temsil eder. |
|
|  | [EPUB](#EPUB) | Open eKitap Dosyası (.epub), yayıncılar ve tüketiciler için standart bir dijital yayın formatı sunan bir e-kitap dosya formatıdır. |
|
|  | [MOBI](#MOBI) | Mobipocket eKitap (.mobi), en yaygın kullanılan e-kitap dosya formatlarından biridir. |
|
|  | [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) e-kitap, Amazon Kindle cihazları için geliştirilen dijital dosya formatıdır. |
|
|  | [MSG](#MSG) | Outlook Mail Mesajı (.msg), Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişiler, randevular veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. |
|
|  | [EML](#EML) | E-Posta Mesajı (.eml), Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. |
|
|  | [EMLX](#EMLX) | Apple Mail Mesajı (.emlx), Apple tarafından uygulanıp geliştirilmiştir. |
|
|  | [PST](#PST) | Outlook Kişisel Bilgi Deposu Dosyası (.pst), çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyaları (aynı zamanda Kişisel Depolama Tablosu olarak da bilinir) temsil eder. |
|
|  | [OST](#OST) | Outlook Çevrim Dışı Veri Dosyası (.ost), Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. |
|
|  | [TIF](#TIF) | Etiketli Görüntü Dosyası (.tif), bu dosya formatı standardına uyan çeşitli cihazlarda kullanılmak üzere tasarlanmış raster görüntüleri temsil eder. |
|
|  | [TIFF](#TIFF) | Etiketli Görüntü Dosyası Formatı (.tiff), bu dosya formatı standardına uyan çeşitli cihazlarda kullanılmak üzere tasarlanmış raster görüntüleri temsil eder. |
|
|  | [JPG](#JPG) | JPEG Görüntüsü (.jpg), kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatı türüdür. |
|
|  | [JPEG](#JPEG) | JPEG Görüntüsü (.jpeg), kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatı türüdür. |
|
|  | [JFIF](#JFIF) | JPEG Dosya Değişim Formatı (.jfif), platformlar arasında hızlı değişim için geliştirilen bir görüntüdür. |
|
|  | [PNG](#PNG) | Taşınabilir Ağ Grafiği (.png), kayıpsız sıkıştırma kullanan bir raster görüntü dosya formatı türüdür. |
|
|  | [GIF](#GIF) | Grafik Değişim Formatı Dosyası (.gif), yüksek sıkıştırmalı bir görüntü türüdür. |
|
|  | [APNG](#APNG) | Animasyonlu Taşınabilir Ağ Grafiği (.apng), animasyonu destekleyen PNG formatının bir uzantısıdır. |
|
|  | [BMP](#BMP) | Bitmap Görüntü Dosyası (.bmp), bitmap dijital görüntüleri depolamak için kullanılır. |
|
|  | [ICO](#ICO) | Microsoft Windows'ta bir uygulamanın temsili için simge olarak kullanılan bir görüntü dosyası türü olan Icon Dosyasını (.ico) temsil eder. |
|
|  | [TGA](#TGA) | TRUEVISION tarafından geliştirilen bitmap dijital görüntüleri depolamak için kullanılan bir Truevision TGA (TARGA) dosyasını temsil eder. |
|
|  | [JP_2](#JP-2) | Görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardı olan JPEG 2000 Core Image Dosyasını (.jp2) temsil eder. |
|
|  | [JPF](#JPF) | JPEG 2000 Görüntü Dosyasını (.jpf) temsil eder. |
|
|  | [JPX](#JPX) | JPEG 2000 Görüntü Dosyasını (.jpx) temsil eder. |
|
|  | [JPM](#JPM) | JPEG 2000 Görüntü Dosyasını (.jpm) temsil eder. |
|
|  | [J2C](#J2C) | JPEG 2000 Kod Giriş Akışını (.j2c) temsil eder. |
|
|  | [J2K](#J2K) | DCT sıkıştırması yerine dalgacık sıkıştırması kullanılarak sıkıştırılmış bir görüntü olan JPEG 2000 Kod Akışını (.j2k) temsil eder. |
|
|  | [JPC](#JPC) | JPEG 2000 Kod Akışını (.jpc) temsil eder. |
|
|  | [JLS](#JLS) | JPEG-LS (JLS) dosyasını (.jls) temsil eder. |
|
|  | [DIB](#DIB) | Cihaz Bağımsız Bitmap Dosyasını (.dib) temsil eder. |
|
|  | [WMF](#WMF) | Vektör ve bitmap formatındaki görüntü verilerini depolamak için Microsoft Windows Metafile (WMF) temsil eden bir Windows Metafile (.wmf) dosyasını temsil eder. |
|
|  | [WMZ](#WMZ) | Vektör ve bitmap formatındaki görüntü verilerini depolamak için GZIP arşivinde sıkıştırılmış Microsoft Windows Metafile (WMF) temsil eden bir Sıkıştırılmış Windows Metafile (.wmz) dosyasını temsil eder. |
|
|  | [EMF](#EMF) | Grafik görüntüleri cihaz bağımsız olarak temsil eden bir Gelişmiş Windows Metafile (.emf) dosyasını temsil eder. |
|
|  | [EMZ](#EMZ) | Grafik görüntüleri cihaz bağımsız olarak GZIP ile sıkıştırılmış bir Windows Sıkıştırılmış Gelişmiş Metafile (.emz) dosyasını temsil eder. |
|
|  | [WEBP](#WEBP) | Kayıpsız ve kayıplı sıkıştırmaya dayalı modern raster web görüntü dosyası formatı olan bir WebP Görüntüsünü (.webp) temsil eder. |
|
|  | [DNG](#DNG) | Raw dosyaların depolanması için kullanılan bir dijital kamera görüntü formatı olan Digital Negative Specification (.dng) dosyasını temsil eder. |
|
|  | [CDR](#CDR) | Dijital olarak kodlanmış ve sıkıştırılmış görüntüleri depolamak için CorelDRAW ile doğal olarak oluşturulan bir vektör çizim görüntü dosyası olan CorelDraw Vektör Grafik Çizimini (.cdr) temsil eder. |
|
|  | [CMX](#CMX) | Vektör grafiklerin yanı sıra bitmap grafikler de içerebilen bir çizim görüntü dosyası olan Corel Exchange (.cmx) dosyasını temsil eder. |
|
|  | [DJVU](#DJVU) | Metin, çizimler, görüntüler ve fotoğrafların bir kombinasyonunu içeren taranmış belgeler ve kitaplar için tasarlanmış bir grafik dosya formatı olan DjVu Görüntüsünü (.djvu) temsil eder. |
|
|  | [CGM](#CGM) | Vektör grafikler (2D), raster grafikler ve metinleri depolamak ve değiş tokuş etmek için ücretsiz, platform bağımsız, uluslararası standart bir metafile formatı olan Computer Graphics Metafile (.cgm) dosyasını temsil eder. |
|
|  | [PCL](#PCL) | Printer Command Language Belgesini (.pcl) temsil eder. |
|
|  | [PSD](#PSD) | Grafik tasarımı ve geliştirme için Adobe Photoshop'un yerel dosya formatı olan Adobe Photoshop Belgesini (.psd) temsil eder. |
|
|  | [PSB](#PSB) | Adobe Photoshop'ta grafik tasarımı ve geliştirme için kullanılan Photoshop Large Document Format (.psb) dosyasını temsil eder. |
|
|  | [DCM](#DCM) | MRİ, BT taramaları ve ultrason görüntüleri gibi hastaların tıbbi bilgilerini depolayan bir dijital görüntüyü temsil eden DICOM Görüntüsünü (.dcm) temsil eder. |
|
|  | [PS](#PS) | PostScript Dosyasını (.ps) temsil eder. |
|
|  | [EPS](#EPS) | Encapsulated PostScript Dosyasını (.eps) temsil eder, bu dosya tek bir sayfanın görünümünü tanımlayan bir Encapsulated PostScript dil programını açıklar. |
|
|  | [ODG](#ODG) | OpenDocument Grafik Dosyasını (.odg) temsil eder, bu dosya Apache OpenOffice Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır. |
|
|  | [FODG](#FODG) | Düz XML ODF Şablonunu (.fodg) temsil eder, bu şablon Apache OpenOffice Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır. |
|
|  | [SVG](#SVG) | Scalable Vector Graphics Dosyasını (.svg) temsil eder, bu dosya bir Scalable Vector Graphics dosyasıdır ve bir görüntünün görünümünü tanımlamak için XML tabanlı metin formatı kullanır. |
|
|  | [SVGZ](#SVGZ) | Sıkıştırılmış Scalable Vector Graphics Dosyasını (.svgz) temsil eder, bu dosya bir Scalable Vector Graphics dosyasıdır, XML tabanlı metin formatını kullanır ve GZIP ile sıkıştırılarak bir görüntünün görünümünü tanımlar. |
|
|  | [OTG](#OTG) | OpenDocument Grafik Şablonunu (.otg) temsil eder. |
|
|  | [HTM](#HTM) | Hypertext Markup Language Dosyasını (.htm) temsil eder, bu uzantı tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları içindir. |
|
|  | [HTML](#HTML) | Hypertext Markup Language Dosyasını (.html) temsil eder, bu uzantı tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları içindir. |
|
|  | [MHT](#MHT) | MHTML Web Arşivini (.mht) temsil eder. |
|
|  | [NSF](#NSF) | Lotus Notes Veritabanını (.nsf) temsil eder. |
|
|  | [MBOX](#MBOX) | E-posta Posta Kutusu Dosyasını (.mbox) temsil eder. |
|
|  | [MHTML](#MHTML) | MIME HTML Dosyasını (.mhtml) temsil eder. |
|
|  | [XML](#XML) | XML Dosyasını (.xml) temsil eder. |
|
|  | [ONE](#ONE) | Microsoft OneNote uygulaması tarafından oluşturulan OneNote Belgesini (.one) temsil eder. |
|
|  | [PDF](#PDF) | Portable Document Format Dosyasını (.pdf) temsil eder, bu belge 1990'larda Adobe tarafından oluşturulan bir belge türüdür. |
|
|  | [XPS](#XPS) | XML Paper Specification Dosyasını (.xps) temsil eder, bu dosya Microsoft tarafından oluşturulan XML Paper Specification tabanlı sayfa düzeni dosyalarını temsil eder. |
|
|  | [OXPS](#OXPS) | OpenXPS Dosyasını (.oxps) temsil eder. |
|
|  | [TEX](#TEX) | LaTeX Kaynak Belgesini (.tex) temsil eder, bu dil belge biçimlendirmek için programlama ve işaretleme özelliklerini içerir. |
|
|  | [OFD](#OFD) | GB/T 33190-2016 tarafından tanımlanan Açık Sabit Düzen Belgesi (OFD) formatı, Çin kamu kurumlarında PDF'yi değiştirmeyi hedeflemektedir. |
|
|  | [PPT](#PPT) | PowerPoint Sunumunu (.ppt) temsil eder, bu dosya slayt gösterisi olarak görüntülenmek üzere bir dizi slayttan oluşan bir PowerPoint dosyasını temsil eder. |
|
|  | [PPTX](#PPTX) | PowerPoint Open XML Sunumunu (.pptx) temsil eder, bu dosyalar popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. |
|
|  | [PPS](#PPS) | PowerPoint Slayt Gösterisini (.pps) temsil eder, bu dosyalar Slayt Gösterisi amaçlarıyla Microsoft PowerPoint kullanılarak oluşturulur. |
|
|  | [PPSX](#PPSX) | PowerPoint Open XML Slayt Gösterisi (.ppsx) dosyalarını temsil eder, bu dosyalar Microsoft PowerPoint 2007 ve üzeri sürümlerle Slayt Gösterisi amaçları için oluşturulur. |
|
|  | [ODP](#ODP) | OpenDocument Sunumunu (.odp) temsil eder, bu dosya OpenOffice.org tarafından OASISOpen standardında kullanılan bir sunum dosya formatını temsil eder. |
|
|  | [FODP](#FODP) | OpenDocument Presentation (.fodp) temsil eder, bu da OpenDocument Flat XML Presentation'ı temsil eder. |
|
|  | [POT](#POT) | PowerPoint Şablonunu (.pot) temsil eder, bu da PowerPoint 97-2003 sürümleriyle oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. |
|
|  | [PPTM](#PPTM) | PowerPoint Open XML Makro‑Destekli Sunumu (.pptm) temsil eder, bu da Microsoft PowerPoint 2007 veya daha yeni sürümlerle oluşturulan makro‑destekli sunum dosyalarını temsil eder. |
|
|  | [POTX](#POTX) | PowerPoint Open XML Sunum Şablonunu (.potx) temsil eder, bu da Microsoft PowerPoint 2007 ve üzeri sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. |
|
|  | [POTM](#POTM) | PowerPoint Open XML Makro‑Destekli Sunum Şablonunu (.potm) temsil eder, bu da makroları destekleyen Microsoft PowerPoint şablon dosyalarını ifade eder. |
|
|  | [PPSM](#PPSM) | PowerPoint Open XML Makro‑Destekli Slaytı (.ppsm) temsil eder, bu da Microsoft PowerPoint 2007 veya daha yeni sürümlerle oluşturulan makro‑destekli slayt gösterisi dosya formatını temsil eder. |
|
|  | [OTP](#OTP) | OpenDocument Sunum Şablonunu (.otp) temsil eder, bu da OASIS OpenDocument standart formatındaki uygulamalar tarafından oluşturulan sunum şablonu dosyalarını temsil eder. |
|
|  | [XLS](#XLS) | Excel Çalışma Sayfasını (.xls) temsil eder, bu da Excel İkili Dosya Formatını temsil eder. |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Excel 2003 XML (SpreadsheetML) (.xml) dosyasını temsil eder, bu da Excel İkili Dosya Formatını temsil eder. |
|
|  | [NUMBERS](#NUMBERS) | Apple Numbers (.numbers) dosyasını temsil eder, bu da Excel benzeri bir İkili Dosya Formatını temsil eder. |
|
|  | [XLSX](#XLSX) | Microsoft Excel Open XML Çalışma Sayfasını (.xlsx) temsil eder, bu, Microsoft Office 2007 sürümüyle tanıtılan Microsoft Excel belgeleri için yaygın bir formattır. |
|
|  | [XLSM](#XLSM) | Excel Open XML Makro‑Destekli Çalışma Sayfasını (.xlsm) temsil eder, bu, makroları destekleyen bir çalışma sayfası dosyası türüdür. |
|
|  | [XLSB](#XLSB) | Excel İkili Çalışma Sayfasını (.xlsb) temsil eder, bu Excel İkili Dosya Formatını belirtir. |
|
|  | [CSV](#CSV) | Virgülle Ayrılmış Değerler Dosyasını (.csv) temsil eder, bu da virgülle ayrılmış değerler içeren düz metin dosyalarını temsil eder. |
|
|  | [TSV](#TSV) | Sekme Ayrılmış Değerler Dosyasını (.tsv) temsil eder, bu da sekmelerle ayrılmış verileri düz metin formatında temsil eder. |
|
|  | [ODS](#ODS) | OpenDocument Çalışma Sayfasını (.ods) temsil eder, bu, kullanıcının düzenleyebileceği OpenDocument Çalışma Sayfası Belgesi formatını ifade eder. |
|
|  | [FODS](#FODS) | OpenDocument Düz XML Çalışma Sayfasını (.fods) temsil eder. |
|
|  | [OTS](#OTS) | OpenDocument Çalışma Sayfası Şablonunu (.ots) temsil eder. |
|
|  | [XLAM](#XLAM) | Microsoft Excel Eklentisini (.xlam) temsil eder. |
|
|  | [XLTM](#XLTM) | Microsoft Excel Makro‑Destekli Şablonunu (.xltm) temsil eder, bu da Microsoft Excel tarafından makro‑destekli şablon dosyaları olarak oluşturulan dosyaları temsil eder. |
|
|  | [XLT](#XLT) | Microsoft Excel Şablonunu (.xlt) temsil eder, bu da Microsoft Office paketinin bir parçası olan Microsoft Excel ile oluşturulan şablon dosyalarıdır. |
|
|  | [XLTX](#XLTX) | Excel Open XML Çalışma Sayfası Şablonunu (.xltx) temsil eder, bu da Office OpenXML dosya formatı özelliklerine dayanan Microsoft Excel Şablonlarını temsil eder. |
|
|  | [SXC](#SXC) | StarOffice Calc Çalışma Sayfasını (.sxc) temsil eder. |
|
|  | [MPP](#MPP) | Microsoft Project Dosyasını (.mpp) temsil eder, bu, proje yönetimiyle ilgili bilgileri bütünleşik bir şekilde depolayan bir Microsoft Project veri dosyasıdır. |
|
|  | [MPT](#MPT) | Microsoft Project Şablonunu (.mpt) temsil eder, bu .MPP dosyaları oluşturmak için temel bilgi ve yapı ile belge ayarlarını içerir. |
|
|  | [MPX](#MPX) | Microsoft Project Exchange dosyasını (.mpx) temsil eder, bu dosya Microsoft Project (MSP) ile MPX dosya formatını destekleyen Primavera Project Planner, Sciforma ve Timerline Precision Estimating gibi diğer uygulamalar arasında proje bilgilerini aktarmak için kullanılan bir ASCII dosya formatıdır. |
|
|  | [AS](#AS) | ActionScript dosyasını (.as) temsil eder. |
|
|  | [AS_3](#AS-3) | ActionScript dosyasını (.as3) temsil eder. |
|
|  | [ASM](#ASM) | Assembly Language kaynak kod dosyasını (.asm) temsil eder. |
|
|  | [BAT](#BAT) | DOS toplu iş dosyasını (.bat) temsil eder. |
|
|  | [C](#C) | C/C++ kaynak kod dosyasını (.c) temsil eder. |
|
|  | [CC](#CC) | C++ kaynak kod dosyasını (.cc) temsil eder. |
|
|  | [CMAKE](#CMAKE) | CMake dosyasını (.cmake) temsil eder. |
|
|  | [CPP](#CPP) | C++ kaynak kod dosyasını (.cpp) temsil eder. |
|
|  | [CS](#CS) | C# kaynak kod dosyasını (.cs) temsil eder, bu dosya C# programlama dili için bir kaynak kod dosyasıdır. |
|
|  | [VB](#VB) | Visual Basic Proje Öğesi dosyasını (.vb) temsil eder, bu dosya Visual Basic dilinde oluşturulmuş bir kaynak kod dosyasıdır. |
|
|  | [CSS](#CSS) | Cascading Style Sheet (.css) dosyasını temsil eder. |
|
|  | [CXX](#CXX) | C++ kaynak kod dosyasını (.cxx) temsil eder. |
|
|  | [DIFF](#DIFF) | Yama dosyasını (.diff) temsil eder. |
|
|  | [ERB](#ERB) | Ruby ERB betiğini (.erb) temsil eder. |
|
|  | [GROOVY](#GROOVY) | Groovy kaynak kod dosyasını (.groovy) temsil eder. |
|
|  | [H](#H) | C/C++/Objective-C başlık dosyasını (.h) temsil eder. |
|
|  | [HAML](#HAML) | Haml kaynak kod dosyasını (.haml) temsil eder. |
|
|  | [HH](#HH) | C++ başlık dosyasını (.hh) temsil eder. |
|
|  | [JAVA](#JAVA) | Java kaynak kod dosyasını (.java) temsil eder. |
|
|  | [JS](#JS) | JavaScript dosyasını (.js) temsil eder. |
|
|  | [JSON](#JSON) | JavaScript Object Notation dosyasını (.json) temsil eder. |
|
|  | [LESS](#LESS) | LESS Stil Sayfası (.less) dosyasını temsil eder. |
|
|  | [LOG](#LOG) | Kayıt dosyasını (.log) temsil eder. |
|
|  | [M](#M) | Objective-C uygulama dosyasını (.m) temsil eder. |
|
|  | [MAKE](#MAKE) | Xcode Makefile Script (.make) dosyasını temsil eder. |
|
|  | [MD](#MD) | Markdown Documentation File (.md) dosyasını temsil eder. |
|
|  | [ML](#ML) | ML Source Code File (.ml) dosyasını temsil eder. |
|
|  | [MM](#MM) | Objective-C++ Source File (.mm) dosyasını temsil eder. |
|
|  | [PHP](#PHP) | PHP Source Code File (.php) dosyasını temsil eder. |
|
|  | [PL](#PL) | Perl Script (.pl) dosyasını temsil eder. |
|
|  | [PROPERTIES](#PROPERTIES) | Java Properties File (.properties) dosyasını temsil eder. |
|
|  | [PY](#PY) | Python Script (.py) dosyasını temsil eder. |
|
|  | [RB](#RB) | Ruby Source Code (.rb) dosyasını temsil eder. |
|
|  | [RST](#RST) | reStructuredText File (.rst) dosyasını temsil eder. |
|
|  | [SASS](#SASS) | Syntactically Awesome StyleSheets File (.sass) dosyasını temsil eder. |
|
|  | [SCALA](#SCALA) | Scala Source Code File (.scala) dosyasını temsil eder. |
|
|  | [SCM](#SCM) | Scheme Source Code File (.scm) dosyasını temsil eder. |
|
|  | [SCRIPT](#SCRIPT) | Generic Script File (.script) dosyasını temsil eder. |
|
|  | [SH](#SH) | Bash Shell Script (.sh) dosyasını temsil eder. |
|
|  | [SML](#SML) | Standard ML Source Code File (.sml) dosyasını temsil eder. |
|
|  | [SQL](#SQL) | Structured Query Language Data File (.sql) dosyasını temsil eder. |
|
|  | [VIM](#VIM) | Vim Settings File (.vim) dosyasını temsil eder. |
|
|  | [YAML](#YAML) | YAML Document (.yaml) dosyasını temsil eder. |
|
|  | [DOC](#DOC) | Microsoft Word Document (.doc) dosyasını temsil eder. |
|
|  | [DOCX](#DOCX) | Microsoft Word Open XML Document (.docx) dosyasını temsil eder. |
|
|  | [CHM](#CHM) | Microsoft Compiled HTML Help File (.chm) dosyasını temsil eder. |
|
|  | [DOCM](#DOCM) | Word Open XML Macro-Enabled Document (.docm) dosyasını temsil eder. |
|
|  | [DOT](#DOT) | Word Document Template (.dot) dosyasını temsil eder. |
|
|  | [DOTX](#DOTX) | Word Open XML Document Template (.dotx) dosyasını temsil eder. |
|
|  | [DOTM](#DOTM) | Word Open XML Macro-Enabled Document Template (.dotm) dosyasını temsil eder. |
|
|  | [RTF](#RTF) | Rich Text Format dosyasını (.rtf) temsil eder. |
|
|  | [TXT](#TXT) | Düz Metin dosyasını (.txt) temsil eder. |
|
|  | [ODT](#ODT) | OpenDocument Metin Belgesini (.odt) temsil eder. |
|
|  | [OTT](#OTT) | OpenDocument Belge Şablonunu (.ott) temsil eder. |
|
|  | [VCF](#VCF) | vCard dosyasını (.vcf) temsil eder, ki bu iletişim bilgilerini depolamak için bir dijital dosya formatıdır. |
|
|  | [AI](#AI) | Adobe Illustrator dosyasını (.ai) temsil eder, ki bu Adobe Illustrator çizimleri için bir dosya formatıdır. |
|
|  | [PSM1](#PSM1) | PowerShell betik modülü dosyasını (.psm1) temsil eder. |
|
|  | [PS1](#PS1) | PowerShell betik dosyasını (.ps1) temsil eder. |
|
|  | [PSD1](#PSD1) | PowerShell betik modülü manifest dosyasını (.psd1) temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Bir dosya uzantısını bir dosya türüne eşler. |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Bir dosya adından veya dosya yolundan dosya uzantısını çıkarır ve bunu bir dosya türüne eşler. |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Bir dosya medya türünü bir dosya türüne eşler. |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Dosya imzasını okuyarak dosya türünü algılar. |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Dosya imzasını okuyarak dosya türünü algılar. |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Dosya imzasını okuyarak dosya türünü algılar. |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Dosya imzasını okuyarak dosya türünü algılar. |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | Desteklenen dosya türlerini alır. |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Yol üzerinden metin [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) ve [CSV](../../com.groupdocs.viewer/filetype#CSV) dosyalarının karakter kümesini algılamaya çalışır. |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Akış üzerinden metin [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) ve [CSV](../../com.groupdocs.viewer/filetype#CSV) dosyasının karakter kümesini algılamaya çalışır. |
|
|  | [getFileFormat()](#getFileFormat--) | Dosya formatının adını alır, ör. "Microsoft Word Document". |
|
|  | [getExtension()](#getExtension--) | Dosya uzantısı son ekini (nokta "." dahil) alır, ör. ".doc". |
|
|  | [toString()](#toString--) | Geçerli nesnenin dize temsili döndürür. |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Bilinmeyen bir dosya tipini temsil eder.


### ZIP {#ZIP}
```
public static final FileType ZIP
```


Bir veya daha fazla dosya veya dizin içerebilen sıkıştırılmış bir dosyayı (.zip) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/compression/zip).


### TAR {#TAR}
```
public static final FileType TAR
```


Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tar) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/compression/tar).


### XZ {#XZ}
```
public static final FileType XZ
```


LZMA algoritmasına dayalı yüksek oranlı bir sıkıştırma algoritmasıyla sıkıştırılmış bir XZ dosyasını (.xz) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/xz).


### TXZ {#TXZ}
```
public static final FileType TXZ
```


Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.txz, .tar.xz) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/txz).


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.txz, .tar.xz) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/txz).


### TGZ {#TGZ}
```
public static final FileType TGZ
```


Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tgz, .tar.gz) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/tgz).


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Bir veya daha fazla dosyayı toplamak için oluşturulmuş birleştirilmiş Unix dosya arşivini (.tgz, .tar.gz) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/tgz).


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


BZIP2 açık kaynaklı sıkıştırma yöntemi kullanılarak oluşturulmuş bir Bzip2 sıkıştırılmış dosyayı (.bz2) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/compression/bz2).


### RAR {#RAR}
```
public static final FileType RAR
```


RAR (WINRAR sürüm 4) sıkıştırma yöntemi kullanılarak oluşturulmuş bir Roshal Arşivi (.rar) sıkıştırılmış dosyayı temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/compression/rar).


### GZ {#GZ}
```
public static final FileType GZ
```


gzip sıkıştırma uygulamasıyla oluşturulmuş bir Gnu Zipped File (.gz) sıkıştırılmış dosyayı temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/compression/gz).


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Unix sistemlerinde kullanılan Compress programının yerine ücretsiz bir yardımcı program olarak sunulan bir Gnu Zipped File (.gzip) sıkıştırılmış dosyayı temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/compression/gz).


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


LZMA ve LZMA2 sıkıştırmasıyla ücretsiz açık kaynaklı bir arşivleyici olan 7Zip (.7z, .7zip) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/compression/7z/).


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio, genel bir dosya arşivleme yardımcı programı ve ilişkili dosya formatıdır. Öncelikle Unix benzeri bilgisayar işletim sistemlerine kurulur. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/compression/cpio).


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST dosyası, Zstandard (zstd) sıkıştırma algoritmasıyla oluşturulan bir sıkıştırılmış dosyadır. Algoritma tarafından kayıpsız sıkıştırma ile oluşturulan bir sıkıştırılmış dosyadır. ZST dosyaları, veritabanları, dosya sistemleri, ağlar ve oyunlar gibi farklı dosya türlerini sıkıştırmak için kullanılabilir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/compression/zst/).


### TZST {#TZST}
```
public static final FileType TZST
```


TZST dosyaları (.tar.zst, .tzst), Zstandard arşivleridir (ZST) ve içinde Unix tabanlı bir yardımcı programla bir veya daha fazla dosyayı toplamak için oluşturulan Konsolide Unix Dosya Arşivi (Tar) bulunur.


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST dosyaları (.tar.zst, .tzst), Zstandard arşivleridir (ZST) ve içinde Unix tabanlı bir yardımcı programla bir veya daha fazla dosyayı toplamak için oluşturulan Konsolide Unix Dosya Arşivi (Tar) bulunur.


### ISO {#ISO}
```
public static final FileType ISO
```


ISO optik disk görüntüsü, CD veya DVD gibi bir optik diskteki tüm verinin içeriğini temsil eden, ISO-9660 standardına dayalı sıkıştırılmamış bir arşiv disk görüntü dosyasıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/compression/iso/).


### LHA {#LHA}
```
public static final FileType LHA
```


LHA veya LZH, ücretsiz bir sıkıştırma yardımcı programı ve ilişkili dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/compression/lzh/).


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (veya CAB), Microsoft Windows için bir arşiv dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://en.wikipedia.org/wiki/Cabinet_(file_format)).


### DXF {#DXF}
```
public static final FileType DXF
```


Drawing Exchange Format Dosyası (.dxf), AutoCAD çizim dosyasının etiketli veri temsili olan bir dosyayı temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/dxf).


### DWG {#DWG}
```
public static final FileType DWG
```


AutoCAD Çizim Veritabanı Dosyası (.dwg), 2D ve 3D tasarım verilerini içeren özel ikili dosyaları temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/dwg).


### DWT {#DWT}
```
public static final FileType DWT
```


AutoCAD Çizim Şablonu (.dwt), DWG dosyaları olarak kaydedilebilecek çizimler oluşturmak için başlangıç olarak kullanılan bir AutoCAD çizim şablonu dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/dwt).


### STL {#STL}
```
public static final FileType STL
```


Stereolithography Dosyasını (.stl) temsil eder; bu, 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatıdır. Hızlı prototipleme, 3D baskı ve bilgisayar destekli imalatta yaygın olarak kullanılır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/stl).


### IFC {#IFC}
```
public static final FileType IFC
```


Industry Foundation Classes Dosyasını (.ifc) temsil eder; bu, bina nesnelerini ve özelliklerini içe ve dışa aktarmak için uluslararası standartlar belirleyen bir dosya formatıdır. Farklı yazılım uygulamaları arasında birlikte çalışabilirliği sağlar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/ifc).


### DWF {#DWF}
```
public static final FileType DWF
```


Design Web Format Dosyasını (.dwf) temsil eder; bu, 2D/3D çizimleri görüntüleme, inceleme veya yazdırma için sıkıştırılmış bir dosya formatıdır. Tasarım verisinin bir parçası olarak grafik ve metin içerir ve sıkıştırma sayesinde dosya boyutunu azaltır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/dwf).


### FBX {#FBX}
```
public static final FileType FBX
```


Autodesk FBX Interchange Dosyası (FilmBoX) (.fbx), 3D model formatını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/fbx).


### DWFX {#DWFX}
```
public static final FileType DWFX
```


Design Web Format Dosyasını XPS (.dwfx) temsil eder; bu, 2D/3D çizimleri XPS belgesi olarak görüntüleme, inceleme veya yazdırma için sıkıştırılmış bir formattır. Tasarım verisinin bir parçası olarak grafik ve metin içerir ve sıkıştırma sayesinde dosya boyutunu azaltır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/dwfx).


### DGN {#DGN}
```
public static final FileType DGN
```


MicroStation Tasarım Dosyası (.dgn), MicroStation ve Intergraph Interactive Graphics Design System gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimleri temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/dgn).


### PLT {#PLT}
```
public static final FileType PLT
```


PLT (HPGL) Dosyasını (.plt) temsil eder; bu, Autodesk, Inc. tarafından tanıtılan vektör tabanlı bir plotter dosyasıdır. Belirli bir CAD dosyası için bilgi içerir ve tüm görüntüler noktalar yerine çizgilerle basılır, bu da üretimde doğruluk ve hassasiyet sağlar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/cad/plt).


### CF2 {#CF2}
```
public static final FileType CF2
```


Common File Format Dosyasını (.cf2) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/cf2).


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Wavefront 3D Nesne Dosyası (.obj), Wavefront Technologies tarafından tanıtılan bir 3D görüntü dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/3d/obj/).


### HPG {#HPG}
```
public static final FileType HPG
```


PLT (HPGL) Dosyasını (.hpg) temsil eder.
HP Grafik Dili (HPGL) içinde plotter dosyaları için kullanılan bir dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/hpg).


### IGS {#IGS}
```
public static final FileType IGS
```


Initial Graphics Exchange Specification (IGES) Dosyasını (.igs) temsil eder.


### VSD {#VSD}
```
public static final FileType VSD
```


Visio Çizim Dosyası (.vsd), çeşitli grafik nesneleri ve bunların bağlantılarını temsil etmek için Microsoft Visio uygulamasıyla oluşturulan çizimleri temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vsd).


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Çizim Dosyasını (.vsdx) temsil eder; bu, Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatıdır. Daha önceki Microsoft Visio sürümlerinin desteklediği ikili dosya formatı (.VSD) yerine geçmiştir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vsdx).


### VSS {#VSS}
```
public static final FileType VSS
```


Visio Şablon Dosyasını (.vss) temsil eder; bu, Microsoft Visio 2007 ve öncesiyle oluşturulan şablon dosyalarıdır. Şablon dosyaları, bir .VSD Visio çizimine dahil edilebilecek çizim nesneleri sağlar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vss).


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio Şablon Dosyasını (.vssx) temsil eder; bu, Microsoft Visio 2013 ve üzeriyle oluşturulan çizim şablonlarıdır. VSSX dosya formatı Visio 2013 ve üzeriyle açılabilir. Visio dosyaları, şekiller, bağlayıcılar, akış şemaları, ağ düzeni, UML diyagramları vb. gibi çeşitli çizim öğelerini temsil etmesiyle bilinir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vssx).


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Makro‑Destekli Çizim (.vsdm) dosyasını temsil eder; bu, makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. VSDM dosyaları, VSDX'e benzer OPC/XML çizimleridir, ancak dosya açıldığında makroların çalıştırılmasını da sağlar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vsdm).


### VST {#VST}
```
public static final FileType VST
```


Visio Çizim Şablonunu (.vst) temsil eder; bu, Microsoft Visio ile oluşturulan vektör görüntü dosyalarıdır. Yeni Visio çizimleri oluşturmak için şablon olarak kullanılır ve yeni çizimler için varsayılan düzen ve ayarları içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vst).


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Çizim Şablonunu (.vstx) temsil eder; bu, Microsoft Visio 2013 ve üzeriyle oluşturulan çizim şablonu dosyalarıdır. Bu VSTX dosyaları, .VSDX dosyaları olarak kaydedilen Visio çizimleri oluşturmak için varsayılan düzen ve ayarlarla bir başlangıç noktası sağlar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vstx).


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Makro‑Destekli Çizim Şablonunu (.vstm) temsil eder; bu, makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. VSTM şablonlarından oluşturulan dosyalar, Visual Basic for Applications (VBA) kodunda geliştirilen makroları çalıştırabilir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vstm).


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Makro‑Destekli Şablon Dosyasını (.vssm) temsil eder; bu, makroları destekleyen Microsoft Visio Şablon dosyalarıdır. Bir VSSM dosyası açıldığında, şekillerin istenen biçimlendirilmesi ve diyagramda yerleştirilmesi için makrolar çalıştırılabilir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vssm).


### VSX {#VSX}
```
public static final FileType VSX
```


Visio Şablon XML Dosyasını (.vsx) temsil eder; bu, Microsoft Visio'da diyagramlar oluşturmak için kullanılan çizimler ve şekiller içeren şablonları ifade eder. VSX dosyaları XML dosya formatında kaydedilir ve Visio 2013'e kadar desteklenmiştir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vsx).


### VTX {#VTX}
```
public static final FileType VTX
```


Visio Şablon XML Dosyasını (.vtx) temsil eder; bu, XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonudur. Şablon, aynı ayarlarla birden fazla Visio dosyası oluşturmak için temel ayarları sağlar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/vtx).


### VDW {#VDW}
```
public static final FileType VDW
```


Visio Web Çizimi (.vdw), bir web çiziminin işlenmesi için gereken akışları ve depolamaları belirler.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/web/vdw).


### VDX {#VDX}
```
public static final FileType VDX
```


Visio Çizim XML Dosyası (.vdx) temsil eder, bu dosya Microsoft Visio'da oluşturulan ve .VDX uzantısıyla XML formatında kaydedilen herhangi bir çizim veya grafiği temsil eder. Visio çizim XML dosyası, Microsoft tarafından geliştirilen Visio yazılımında oluşturulur.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/image/vdx) tıklayın.


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eKitap Dosyası (.epub) temsil eder, bu dosya yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır. Format, birçok e-okuyucu ve yazılım uygulaması tarafından desteklenir.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/ebook/epub) tıklayın.


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket eKitap (.mobi) temsil eder, bu en yaygın kullanılan e-kitap dosya formatlarından biridir. Format, eski OEB (Open Ebook Format) formatının bir geliştirmesidir ve Mobipocket Reader için sahipli bir format olarak kullanılmıştır.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/ebook/mobi) tıklayın.


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8 (KF8) e-kitap, Amazon Kindle cihazları için geliştirilen dijital dosya formatıdır. Format, eski AZW dosyalarının bir geliştirmesidir ve yalnızca Kindle Fire cihazlarında, üst format olan MOBI ve AZW ile geriye dönük uyumluluk sağlanarak kullanılır.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/ebook/azw3) tıklayın.


### MSG {#MSG}
```
public static final FileType MSG
```


Outlook Mail Mesajı (.msg), Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişiler, randevular veya diğer görevleri depolamak için kullanılan bir dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/email/msg) tıklayın.


### EML {#EML}
```
public static final FileType EML
```


E-Posta Mesajı (.eml) temsil eder, bu Outlook ve diğer ilgili uygulamalar kullanılarak kaydedilen e-posta mesajlarını temsil eder. RFC-822 Internet Message Format Standardına uyumu sayesinde neredeyse tüm e-posta istemcileri bu dosya formatını destekler.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/email/eml) tıklayın.


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail Mesajı (.emlx) temsil eder, bu Apple tarafından uygulanıp geliştirilen bir formattır. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya formatını kullanır.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/email/emlx) tıklayın.


### PST {#PST}
```
public static final FileType PST
```


Outlook Kişisel Bilgi Deposu Dosyası (.pst), çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyaları (aynı zamanda Kişisel Depolama Tablosu olarak da bilinir) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/email/pst) tıklayın.


### OST {#OST}
```
public static final FileType OST
```


Outlook Çevrim Dışı Veri Dosyası (.ost), Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/email/ost) tıklayın.


### TIF {#TIF}
```
public static final FileType TIF
```


Tagged Image File (.tif) temsil eder, bu dosya çeşitli cihazlarda kullanılmak üzere tasarlanmış raster görüntüleri temsil eder ve bu dosya formatı standardına uyar. Birkaç renk uzayında ikili seviye, gri tonlamalı, palet renkli ve tam renkli görüntü verilerini tanımlayabilir.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/image/tiff) tıklayın.


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Tagged Image File Format (.tiff) temsil eder, bu dosya çeşitli cihazlarda kullanılmak üzere tasarlanmış raster görüntüleri temsil eder ve bu dosya formatı standardına uyar. Birkaç renk uzayında ikili seviye, gri tonlamalı, palet renkli ve tam renkli görüntü verilerini tanımlayabilir.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/image/tiff) tıklayın.


### JPG {#JPG}
```
public static final FileType JPG
```


JPEG Görüntüsü (.jpg) temsil eder, bu kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatıdır. Sıkıştırma sonucu ortaya çıkan çıktı görüntüsü, depolama boyutu ile görüntü kalitesi arasında bir denge sağlar.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/image/jpeg) tıklayın.


### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Görüntüsü (.jpeg) temsil eder, bu kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatıdır. Sıkıştırma sonucu ortaya çıkan çıktı görüntüsü, depolama boyutu ile görüntü kalitesi arasında bir denge sağlar.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/image/jpeg) tıklayın.


### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG Dosya Değişim Formatı (.jfif) hızlı platformlar arası değişim için geliştirilmiş bir görüntüdür. Bu format JPEG sıkıştırması kullanır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/image/jfif) tıklayın.


### PNG {#PNG}
```
public static final FileType PNG
```


Taşınabilir Ağ Grafiği (.png) temsil eder, bu kayıpsız sıkıştırma kullanan bir raster görüntü dosya formatıdır. Bu dosya formatı, Grafik Değişim Formatı (GIF) yerine oluşturulmuş ve telif hakkı sınırlamaları içermez.
Bu dosya formatı hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/image/png) tıklayın.


### GIF {#GIF}
```
public static final FileType GIF
```


Grafik Değişim Formatı Dosyasını (.gif) temsil eder, bu yüksek sıkıştırmalı bir görüntü türüdür. Her görüntü için GIF tipik olarak piksel başına en fazla 8 bit ve görüntü genelinde en fazla 256 renk izin verir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/gif).


### APNG {#APNG}
```
public static final FileType APNG
```


Animasyonlu Taşınabilir Ağ Grafiği (.apng), animasyonu destekleyen PNG formatının bir uzantısıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/apng).


### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Görüntü Dosyasını (.bmp) temsil eder, bu bitmap dijital görüntüleri depolamak için kullanılır. Bu görüntüler grafik adaptöründen bağımsızdır ve cihaz bağımsız bitmap (DIB) dosya formatı olarak da adlandırılır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/bmp).


### ICO {#ICO}
```
public static final FileType ICO
```


Microsoft Windows'ta bir uygulamanın temsili için simge olarak kullanılan bir görüntü dosyası türü olan Icon Dosyasını (.ico) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/ico).


### TGA {#TGA}
```
public static final FileType TGA
```


TRUEVISION tarafından geliştirilen bitmap dijital görüntüleri depolamak için kullanılan bir Truevision TGA (TARGA) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/tga).


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardı olan JPEG 2000 Core Image Dosyasını (.jp2) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/jp2).


### JPF {#JPF}
```
public static final FileType JPF
```


JPEG 2000 Görüntü Dosyasını (.jpf) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/image/jpf).


### JPX {#JPX}
```
public static final FileType JPX
```


JPEG 2000 Görüntü Dosyasını (.jpx) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/jpx).


### JPM {#JPM}
```
public static final FileType JPM
```


JPEG 2000 Görüntü Dosyasını (.jpm) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/jpm).


### J2C {#J2C}
```
public static final FileType J2C
```


JPEG 2000 Kod Giriş Akışını (.j2c) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/j2c).


### J2K {#J2K}
```
public static final FileType J2K
```


DCT sıkıştırması yerine dalgacık sıkıştırması kullanılarak sıkıştırılmış bir görüntü olan JPEG 2000 Kod Akışını (.j2k) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/j2k).


### JPC {#JPC}
```
public static final FileType JPC
```


JPEG 2000 Kod Akışını (.jpc) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/jpc).


### JLS {#JLS}
```
public static final FileType JLS
```


JPEG-LS (JLS) dosyasını (.jls) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/jls).


### DIB {#DIB}
```
public static final FileType DIB
```


Cihaz Bağımsız Bitmap Dosyasını (.dib) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/dib).


### WMF {#WMF}
```
public static final FileType WMF
```


Vektör ve bitmap formatındaki görüntü verilerini depolamak için Microsoft Windows Metafile (WMF) temsil eden bir Windows Metafile (.wmf) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/wmf).


### WMZ {#WMZ}
```
public static final FileType WMZ
```


Vektör ve bitmap formatındaki görüntü verilerini depolamak için GZIP arşivinde sıkıştırılmış Microsoft Windows Metafile (WMF) temsil eden bir Sıkıştırılmış Windows Metafile (.wmz) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/wmz#compressed_windows_metafile).


### EMF {#EMF}
```
public static final FileType EMF
```


Gelişmiş Windows Metafile'ını (.emf) temsil eder, bu grafik görüntüleri cihazdan bağımsız olarak temsil eder. EMF metafile'ları, saklanan görüntüyü herhangi bir çıkış cihazında ayrıştırdıktan sonra oluşturabilen, kronolojik sırada değişken uzunlukta kayıtlar içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/emf).


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows Sıkıştırılmış Gelişmiş Metafile'ı (.emz) temsil eder, bu grafik görüntüleri GZIP ile cihazdan bağımsız olarak sıkıştırılmış şekilde temsil eder. EMF metafile'ları, saklanan görüntüyü herhangi bir çıkış cihazında ayrıştırdıktan sonra oluşturabilen, kronolojik sırada değişken uzunlukta kayıtlar içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/emz).


### WEBP {#WEBP}
```
public static final FileType WEBP
```


WebP Görüntüsünü (.webp) temsil eder, bu kayıpsız ve kayıplı sıkıştırmaya dayalı modern bir raster web görüntü dosya formatıdır. Görüntü kalitesini aynı tutarken görüntü boyutunu önemli ölçüde azaltır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/webp).


### DNG {#DNG}
```
public static final FileType DNG
```


Digital Negative Specification'ı (.dng) temsil eder, bu ham dosyaların depolanması için kullanılan bir dijital kamera görüntü formatıdır. Adobe tarafından Eylül 2004'te geliştirilmiş ve öncelikle dijital fotoğrafçılıkta kullanılır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/dng).


### CDR {#CDR}
```
public static final FileType CDR
```


CorelDraw Vektör Grafik Çizimi (.cdr) temsil eder; bu, CorelDRAW ile yerel olarak oluşturulan, dijital olarak kodlanmış ve sıkıştırılmış görüntüleri depolamak için kullanılan bir vektör çizim dosyasıdır. Bir CDR çizim dosyası, görüntü içeriğinin vektör temsili için metin, çizgiler, şekiller, görüntüler, renkler ve efektler içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/cdr).


### CMX {#CMX}
```
public static final FileType CMX
```


Vektör grafiklerin yanı sıra bitmap grafikler de içerebilen bir çizim görüntü dosyası olan Corel Exchange (.cmx) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/cmx).


### DJVU {#DJVU}
```
public static final FileType DJVU
```


Metin, çizimler, görüntüler ve fotoğrafların bir kombinasyonunu içeren taranmış belgeler ve kitaplar için tasarlanmış bir grafik dosya formatı olan DjVu Görüntüsünü (.djvu) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/djvu).


### CGM {#CGM}
```
public static final FileType CGM
```


Bilgisayar Grafik Metadosyası (.cgm) temsil eder; bu, vektör grafikler (2D), raster grafikler ve metinleri depolamak ve değiştirmek için ücretsiz, platform bağımsız, uluslararası standart bir metafile formatıdır. CGM, nesne yönelimli bir yaklaşım kullanır ve görüntü üretimi için birçok işlev sunar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/page-description-language/cgm).


### PCL {#PCL}
```
public static final FileType PCL
```


Printer Command Language Belgesini (.pcl) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/page-description-language/pcl).


### PSD {#PSD}
```
public static final FileType PSD
```


Grafik tasarımı ve geliştirme için Adobe Photoshop'un yerel dosya formatı olan Adobe Photoshop Belgesini (.psd) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/psd).


### PSB {#PSB}
```
public static final FileType PSB
```


Adobe Photoshop'ta grafik tasarımı ve geliştirme için kullanılan Photoshop Large Document Format (.psb) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/psb).


### DCM {#DCM}
```
public static final FileType DCM
```


MRİ, BT taramaları ve ultrason görüntüleri gibi hastaların tıbbi bilgilerini depolayan bir dijital görüntüyü temsil eden DICOM Görüntüsünü (.dcm) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/dcm).


### PS {#PS}
```
public static final FileType PS
```


PostScript Dosyasını (.ps) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/page-description-language/ps).


### EPS {#EPS}
```
public static final FileType EPS
```


Encapsulated PostScript Dosyasını (.eps) temsil eder, bu dosya tek bir sayfanın görünümünü tanımlayan bir Encapsulated PostScript dil programını açıklar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/page-description-language/eps).


### ODG {#ODG}
```
public static final FileType ODG
```


OpenDocument Grafik Dosyasını (.odg) temsil eder, bu dosya Apache OpenOffice Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/odg).


### FODG {#FODG}
```
public static final FileType FODG
```


Düz XML ODF Şablonunu (.fodg) temsil eder, bu şablon Apache OpenOffice Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/image/fodg).


### SVG {#SVG}
```
public static final FileType SVG
```


Scalable Vector Graphics Dosyasını (.svg) temsil eder, bu dosya bir Scalable Vector Graphics dosyasıdır ve bir görüntünün görünümünü tanımlamak için XML tabanlı metin formatı kullanır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/page-description-language/svg).


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Sıkıştırılmış Scalable Vector Graphics Dosyasını (.svgz) temsil eder, bu dosya bir Scalable Vector Graphics dosyasıdır, XML tabanlı metin formatını kullanır ve GZIP ile sıkıştırılarak bir görüntünün görünümünü tanımlar.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/svgz).


### OTG {#OTG}
```
public static final FileType OTG
```


OpenDocument Grafik Şablonunu (.otg) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/image/otg).


### HTM {#HTM}
```
public static final FileType HTM
```


Hypertext Markup Language Dosyasını (.htm) temsil eder, bu uzantı tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları içindir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/web/html).


### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language Dosyasını (.html) temsil eder, bu uzantı tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları içindir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/web/html).


### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Arşivini (.mht) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/web/mht).


### NSF {#NSF}
```
public static final FileType NSF
```


Lotus Notes Veritabanını (.nsf) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/nsf).


### MBOX {#MBOX}
```
public static final FileType MBOX
```


E-posta Posta Kutusu Dosyasını (.mbox) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/mbox).


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML Dosyasını (.mhtml) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/web/mhtml).


### XML {#XML}
```
public static final FileType XML
```


XML Dosyasını (.xml) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/web/xml).


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote uygulaması tarafından oluşturulan bir OneNote Belgesi (.one) temsil eder. OneNote, not alırken taslak defterinizi kullandığınız gibi uygulamayı kullanarak bilgi toplamanıza olanak tanır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/note-taking/one).


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe tarafından 1990'larda oluşturulan bir belge türü olan Portable Document Format Dosyasını (.pdf) temsil eder. Bu dosya formatının amacı, belgelerin ve diğer referans materyallerinin uygulama yazılımı, donanım ve işletim sistemlerinden bağımsız bir formatta temsil edilmesi için bir standart getirmekti.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/view/pdf).


### XPS {#XPS}
```
public static final FileType XPS
```


Microsoft tarafından oluşturulan XML Paper Specification'lara dayalı sayfa düzeni dosyalarını temsil eden bir XML Paper Specification Dosyasını (.xps) temsil eder. Bu format, Microsoft tarafından EMF dosya formatının yerine geliştirilmiş olup PDF dosya formatına benzer, ancak bir belgenin düzen, görünüm ve baskı bilgilerinde XML kullanır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/page-description-language/xps).


### OXPS {#OXPS}
```
public static final FileType OXPS
```


OpenXPS Dosyasını (.oxps) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/page-description-language/oxps).


### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Kaynak Belgesini (.tex) temsil eder, bu dil belge biçimlendirmek için programlama ve işaretleme özelliklerini içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/page-description-language/tex).


### OFD {#OFD}
```
public static final FileType OFD
```


GB/T 33190-2016 tarafından tanımlanan Açık Sabit Düzen Belgesi (OFD) formatı, Çin kamu kurumlarında PDF'yi değiştirmeyi hedeflemektedir.


### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Slayt Gösterisi (.ppt) dosyasını temsil eder; bu, slayt koleksiyonundan oluşan ve slayt gösterisi olarak görüntülenmek üzere kullanılan bir PowerPoint dosyasıdır. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Formatını belirtir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/ppt).


### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Sunumu (.pptx) dosyasını temsil eder; bu, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. İkili olan önceki PPT sunum dosya formatının aksine, PPTX formatı Microsoft PowerPoint Open XML sunum dosya formatına dayanır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/pptx).


### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slayt Gösterisi (.pps) dosyasını temsil eder; bu, Microsoft PowerPoint kullanılarak Slayt Gösterisi amaçlarıyla oluşturulur. PPS dosyalarının okunması ve oluşturulması Microsoft PowerPoint 97-2003 tarafından desteklenir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/pps).


### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML Slayt Gösterisi (.ppsx) dosyalarını temsil eder, bu dosyalar Microsoft PowerPoint 2007 ve üzeri sürümlerle Slayt Gösterisi amaçları için oluşturulur.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/ppsx).


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Sunumunu (.odp) temsil eder, bu dosya OpenOffice.org tarafından OASISOpen standardında kullanılan bir sunum dosya formatını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/odp).


### FODP {#FODP}
```
public static final FileType FODP
```


OpenDocument Presentation (.fodp) temsil eder, bu da OpenDocument Flat XML Presentation'ı temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/fodp).


### POT {#POT}
```
public static final FileType POT
```


PowerPoint Şablonunu (.pot) temsil eder, bu da PowerPoint 97-2003 sürümleriyle oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/pot).


### PPTM {#PPTM}
```
public static final FileType PPTM
```


PowerPoint Open XML Makro‑Destekli Sunumu (.pptm) temsil eder, bu da Microsoft PowerPoint 2007 veya daha yeni sürümlerle oluşturulan makro‑destekli sunum dosyalarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/pptm).


### POTX {#POTX}
```
public static final FileType POTX
```


PowerPoint Open XML Sunum Şablonunu (.potx) temsil eder, bu da Microsoft PowerPoint 2007 ve üzeri sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/potx).


### POTM {#POTM}
```
public static final FileType POTM
```


PowerPoint Open XML Makro Etkin Sunum Şablonu (.potm) dosyasını temsil eder; bu, makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM dosyaları PowerPoint 2007 veya daha yeni sürümlerle oluşturulur ve ek sunum dosyaları oluşturmak için kullanılabilecek varsayılan ayarları içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/potm).


### PPSM {#PPSM}
```
public static final FileType PPSM
```


PowerPoint Open XML Makro‑Destekli Slaytı (.ppsm) temsil eder, bu da Microsoft PowerPoint 2007 veya daha yeni sürümlerle oluşturulan makro‑destekli slayt gösterisi dosya formatını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/ppsm).


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Sunum Şablonunu (.otp) temsil eder, bu da OASIS OpenDocument standart formatındaki uygulamalar tarafından oluşturulan sunum şablonu dosyalarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/presentation/otp).


### XLS {#XLS}
```
public static final FileType XLS
```


Excel Çalışma Sayfasını (.xls) temsil eder; bu, Excel İkili Dosya Formatını temsil eder. Bu tür dosyalar Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi benzer elektronik tablo programlarıyla da oluşturulabilir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xls).


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Excel 2003 XML (SpreadsheetML) (.xml) dosyasını temsil eder, bu dosya Excel İkili Dosya Biçimini temsil eder. Bu tür dosyalar Microsoft Excel tarafından ve OpenOffice Calc veya Apple Numbers gibi benzer elektronik tablo programları tarafından oluşturulabilir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xls).


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Apple Numbers (.numbers) dosyasını temsil eder, bu dosya Excel benzeri bir İkili Dosya Biçimini temsil eder. Bu tür dosyalar Apple Numbers uygulamasıyla oluşturulabilir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/numbers).


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Çalışma Sayfasını (.xlsx) temsil eder, bu, Microsoft Office 2007 sürümüyle tanıtılan Microsoft Excel belgeleri için yaygın bir formattır.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xlsx).


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Makro‑Destekli Çalışma Sayfasını (.xlsm) temsil eder, bu, makroları destekleyen bir çalışma sayfası dosyası türüdür.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xlsm).


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) dosyasını temsil eder, bu dosya Excel İkili Dosya Biçimini belirtir. Bu, Excel çalışma kitabı içeriğini belirten kayıtlar ve yapılar koleksiyonudur.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xlsb).


### CSV {#CSV}
```
public static final FileType CSV
```


Virgülle Ayrılmış Değerler Dosyasını (.csv) temsil eder, bu da virgülle ayrılmış değerler içeren düz metin dosyalarını temsil eder.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/csv).


### TSV {#TSV}
```
public static final FileType TSV
```


Sekme Ayrılmış Değerler Dosyasını (.tsv) temsil eder, bu da sekmelerle ayrılmış verileri düz metin formatında temsil eder.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/tsv).


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods) dosyasını temsil eder, bu kullanıcı tarafından düzenlenebilir OpenDocument Spreadsheet Belge biçimini ifade eder. Veriler ODF dosyaları içinde satır ve sütunlar halinde depolanır.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/ods).


### FODS {#FODS}
```
public static final FileType FODS
```


OpenDocument Düz XML Çalışma Sayfasını (.fods) temsil eder.
Bu, OpenOffice ve LibreOffice tarafından kullanılan XML tabanlı bir elektronik tablo belge biçimidir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/fods).


### OTS {#OTS}
```
public static final FileType OTS
```


OpenDocument Çalışma Sayfası Şablonunu (.ots) temsil eder.
Bu, OpenOffice ve LibreOffice tarafından elektronik tablolar için kullanılan bir şablon belge biçimidir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/ots).


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Microsoft Excel Eklentisini (.xlam) temsil eder.
Bu, Microsoft Excel tarafından özel işlevselliğe sahip eklentiler oluşturmak için kullanılan bir dosya biçimidir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/xlam).


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel Macro-Enabled Template (.xltm) dosyasını temsil eder, bu dosyalar Microsoft Excel tarafından Makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları yapısal olarak XLTX dosyalarına benzer, ancak ikincisi makrolu şablon dosyaları oluşturmayı desteklemez.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xltm).


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel Template (.xlt) dosyasını temsil eder, bu dosyalar Microsoft Excel ile oluşturulan şablon dosyalarıdır; Microsoft Office paketinin bir parçası olan bir elektronik tablo uygulamasıdır. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bunları açmayı desteklemiştir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) dosyasını temsil eder, bu dosya Office OpenXML dosya formatı spesifikasyonlarına dayalı Microsoft Excel Şablonlarını temsil eder. Aynı ayarların XLTX dosyasında belirtildiği XLSX dosyalarını oluşturmak için kullanılabilecek standart bir şablon dosyası oluşturmak amacıyla kullanılır.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


StarOffice Calc Çalışma Sayfasını (.sxc) temsil eder.
Bu, bir elektronik tablo programı olan StarOffice Calc ile oluşturulmuş bir elektronik tablo belgesidir.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


Microsoft Project Dosyasını (.mpp) temsil eder, bu, proje yönetimiyle ilgili bilgileri bütünleşik bir şekilde depolayan bir Microsoft Project veri dosyasıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


Microsoft Project Şablonunu (.mpt) temsil eder, bu .MPP dosyaları oluşturmak için temel bilgi ve yapı ile belge ayarlarını içerir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


Microsoft Project Exchange dosyasını (.mpx) temsil eder, bu dosya Microsoft Project (MSP) ile MPX dosya formatını destekleyen Primavera Project Planner, Sciforma ve Timerline Precision Estimating gibi diğer uygulamalar arasında proje bilgilerini aktarmak için kullanılan bir ASCII dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


ActionScript dosyasını (.as) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


ActionScript dosyasını (.as3) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


Assembly Language kaynak kod dosyasını (.asm) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


DOS toplu iş dosyasını (.bat) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


C/C++ kaynak kod dosyasını (.c) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


C++ kaynak kod dosyasını (.cc) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


CMake dosyasını (.cmake) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


C++ kaynak kod dosyasını (.cpp) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


C# Kaynak Kodu Dosyası (.cs) temsil eder, bu dosya C# programlama dili için bir kaynak kod dosyasıdır. Microsoft tarafından .NET Framework ile kullanım için tanıtılmıştır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


Visual Basic Proje Öğesi Dosyası (.vb) temsil eder, bu dosya Visual Basic dilinde oluşturulmuş bir kaynak kod dosyasıdır. Microsoft tarafından .NET uygulamaları geliştirmek için oluşturulmuştur.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


Cascading Style Sheet (.css) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


C++ kaynak kod dosyasını (.cxx) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


Yama dosyasını (.diff) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby ERB betiğini (.erb) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy kaynak kod dosyasını (.groovy) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


C/C++/Objective-C başlık dosyasını (.h) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


Haml kaynak kod dosyasını (.haml) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


C++ başlık dosyasını (.hh) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java kaynak kod dosyasını (.java) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


JavaScript dosyasını (.js) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


JavaScript Object Notation dosyasını (.json) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


LESS Stil Sayfası (.less) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


Kayıt dosyasını (.log) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


Objective-C uygulama dosyasını (.m) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Xcode Makefile Script (.make) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


Markdown Documentation File (.md) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


ML Source Code File (.ml) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


Objective-C++ Source File (.mm) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


PHP Source Code File (.php) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


Perl Script (.pl) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Java Properties File (.properties) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


Python Script (.py) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


Ruby Source Code (.rb) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


reStructuredText File (.rst) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


Syntactically Awesome StyleSheets File (.sass) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala Source Code File (.scala) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


Scheme Source Code File (.scm) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Generic Script File (.script) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


Bash Shell Script (.sh) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


Standard ML Source Code File (.sml) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/sml).


### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language Data File (.sql) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/database/sql).


### VIM {#VIM}
```
public static final FileType VIM
```


Vim Settings File (.vim) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/vim).


### YAML {#YAML}
```
public static final FileType YAML
```


YAML Document (.yaml) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/programming/yaml).


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/doc).


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/docx).


### CHM {#CHM}
```
public static final FileType CHM
```


Microsoft Compiled HTML Help File (.chm) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/web/chm).


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/docm).


### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/dot).


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/dotx).


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) dosyasını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/dotm).


### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format dosyasını (.rtf) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/rtf).


### TXT {#TXT}
```
public static final FileType TXT
```


Düz Metin dosyasını (.txt) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/txt).


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Metin Belgesini (.odt) temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/odt).


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Belge Şablonunu (.ott) temsil eder.
Bu, OASIS'ın OpenDocument standart formatına uygun olarak oluşturulmuş bir şablon belgedir.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/word-processing/ott).


### VCF {#VCF}
```
public static final FileType VCF
```


vCard dosyasını (.vcf) temsil eder, ki bu iletişim bilgilerini depolamak için bir dijital dosya formatıdır.
Popüler bilgi alışverişi uygulamaları arasında veri değişimi için yaygın olarak kullanılır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/email/vcf).


### AI {#AI}
```
public static final FileType AI
```


Adobe Illustrator dosyasını (.ai) temsil eder, ki bu Adobe Illustrator çizimleri için bir dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://docs.fileformat.com/image/ai).


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


PowerShell betik modülü dosyasını (.psm1) temsil eder.
Bu, PowerShell modül betikleri için bir dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/psm1).


### PS1 {#PS1}
```
public static final FileType PS1
```


PowerShell betik dosyasını (.ps1) temsil eder.
Bu, Windows PowerShell Cmdlet dosyaları için bir dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/ps1).


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


PowerShell betik modülü manifest dosyasını (.psd1) temsil eder.
Bu, PowerShell modül manifest betikleri için bir dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin [burada](../https://fileinfo.com/extension/psd1).


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


Bu yöntem, nokta "." ile ya da noktasız bir dosya uzantısı alır ve destekleniyorsa karşılık gelen dosya tipini döndürür.
Dosya tipi desteklenmiyorsa, varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) dosya tipini döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | extension | java.lang.String | Nokta "." ile ya da noktasız dosya uzantısı. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Bir dosya adından veya dosya yolundan dosya uzantısını çıkarır ve bunu bir dosya türüne eşler.


Dosya tipi destekleniyorsa, yöntem karşılık geleni döndürür
FileType
,
aksi takdirde varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) dosya türünü döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosya adı veya dosya yolu. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Bir dosya medya türünü dosya türüne eşler. Örneğin, 'application/pdf' [PDF](../../com.groupdocs.viewer/filetype#PDF) olarak eşlenecektir.


Bu yöntem bir dosya medya türünü girdi olarak alır ve ilgili
FileType
. Eğer medya türü
destekleniyorsa, yöntem ilgili dosya türünü döndürür. Medya türü desteklenmiyorsa, varsayılanı döndürür
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mediaType | java.lang.String | Dosya medya türü, ör. 'application/pdf'. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Dosya imzasını okuyarak dosya türünü algılar.


Bu yöntem bir dosyayı temsil eden bir giriş akışı alır ve dosya imzasını analiz ederek dosya türünü tespit etmeye çalışır. Bu
dosya imzası, dosyanın başında bulunan ve dosya türünü gösteren benzersiz bir bayt dizisidir. Yöntem
dosya imzasını giriş akışından okur ve desteklenen dosya türlerinin bilinen dosya imzalarıyla karşılaştırır.
Eğer bir eşleşme bulunursa, yöntem ilgili dosya türünü döndürür. Eşleşme bulunmazsa, varsayılanı döndürür
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | java.io.InputStream | Dosyayı temsil eden giriş akışı. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Dosya imzasını okuyarak dosya türünü algılar.


Bu yöntem dosya imzasını analiz eder, ki bu dosyanın başında bulunan benzersiz bir bayt dizisidir, belirlemek için
dosya türünü. Sağlanan giriş akışından dosya imzasını okur ve bilinen dosya imzalarıyla karşılaştırır
desteklenen dosya türlerinin. Eşleşme bulunursa, yöntem ilgili dosya türünü döndürür. Eşleşme bulunmazsa,
varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) dosya türünü döndürür.


Dosya şifrelenmişse ve açmak için bir şifre gerekiyorsa, şifre bu yönteme bir parametre olarak sağlanmalıdır
yöntem. Şifre, dosyayı çözmek ve dosya türünü belirlemek için imzasını analiz etmek amacıyla kullanılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | java.io.InputStream | Dosyayı temsil eden giriş akışı. |
|
|  | password | java.lang.String | Dosyayı açmak için şifre. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Dosya imzasını okuyarak dosya türünü algılar.


Bu yöntem dosya imzasını analiz eder, ki bu dosyanın başında bulunan benzersiz bir bayt dizisidir, belirlemek için
dosya türünü. Sağlanan giriş akışından dosya imzasını okur ve bilinen dosya imzalarıyla karşılaştırır
desteklenen dosya türlerinin. Eşleşme bulunursa, yöntem ilgili dosya türünü döndürür. Eşleşme bulunmazsa,
varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) dosya türünü döndürür.


Dosya türü tespit süreci sırasında ilgili bilgileri veya hataları kaydetmek için bir logger sağlanabilir. Logger
ILogger arayüzünü uygulamalıdır. Eğer bir logger sağlanmazsa, tespit süreci hiçbir şey üretmez
günlük çıktısı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | java.io.InputStream | Dosyayı temsil eden giriş akışı. |
|
|  | günlükleyici | com.groupdocs.foundation.logging.ILogger | Bilgi veya hataları kaydetmek için logger. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Dosya imzasını okuyarak dosya türünü algılar.


Bu yöntem dosya imzasını analiz eder, ki bu dosyanın başında bulunan benzersiz bir bayt dizisidir, belirlemek için
dosya türünü. Sağlanan giriş akışından dosya imzasını okur ve bilinen dosya imzalarıyla karşılaştırır
desteklenen dosya türlerinin. Eşleşme bulunursa, yöntem ilgili dosya türünü döndürür. Eşleşme bulunmazsa,
varsayılan [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) dosya türünü döndürür.


Dosya şifrelenmiş veya korunmuşsa bir şifre sağlanabilir. Şifre, dosyayı açmadan önce kullanılacaktır
dosya imzasını analiz ederken. Dosya şifre gerektirmiyorsa, bu parametre null olarak ayarlanabilir.


Dosya türü tespit süreci sırasında ilgili bilgileri veya hataları kaydetmek için bir logger sağlanabilir. Logger
ILogger arayüzünü uygulamalıdır. Eğer bir logger sağlanmazsa, tespit süreci hiçbir şey üretmez
günlük çıktısı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | java.io.InputStream | Dosyayı temsil eden giriş akışı. |
|
|  | password | java.lang.String | Dosyayı açmak için şifre. |
|
|  | günlükleyici | com.groupdocs.foundation.logging.ILogger | Bilgi veya hataları kaydetmek için logger. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Desteklenen dosya türlerini alır.


Bu yöntem, sistem tarafından desteklenen tüm dosya türlerinin bir dizisini döndürür. Dosya türleri çeşitli
sistem tarafından işlenebilen veya tanınabilen belge formatlarını temsil eder.
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - desteklenen dosya türlerinin bir dizisi.

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Yol üzerinden metin [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) ve [CSV](../../com.groupdocs.viewer/filetype#CSV) dosyalarının karakter kümesini algılamaya çalışır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosya adı veya dosya yolu. |
|

**Returns:**
java.nio.charset.Charset - Charset veya dosya karakter kümesi tespit edilemediğinde null.

**Example:**


Charset charset = FileType.detectCharset("message.txt");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Akış üzerinden metin [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV) ve [CSV](../../com.groupdocs.viewer/filetype#CSV) dosyasının karakter kümesini algılamaya çalışır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | java.io.InputStream | Dosya akışı. |
|

**Returns:**
java.nio.charset.Charset - Charset veya dosya karakter kümesi tespit edilemediğinde null.

**Example:**


InputStream stream = new FileInputStream("message.txt");
Charset charset = FileType.detectCharset(stream);
     

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


Dosya uzantısı son ekini (nokta "." dahil) alır, ör. ".doc".


**Returns:**
java.lang.String - dosya uzantısı son eki.

### toString() {#toString--}
```
public String toString()
```


Geçerli nesnenin dize temsili döndürür.


**Returns:**
java.lang.String - geçerli nesnenin dize temsili.

