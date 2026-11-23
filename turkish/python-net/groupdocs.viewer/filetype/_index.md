---
title: "FileType sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir dosya türünü temsil eder ve GroupDocs.Viewer tarafından desteklenen tüm dosya türlerinin listesini elde etmek için yöntemler sağlar."
type: docs
url: /tr/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Bir dosya türünü temsil eder ve GroupDocs.Viewer tarafından desteklenen tüm dosya türlerinin listesini elde etmek için yöntemler sağlar.

FileType türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Yeni bir [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Yeni bir FileType örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Metin TXT, TSV ve CSV dosyalarının kodlamasını yol üzerinden algılar. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Metin dosyalarının (TXT, TSV, CSV) kodlamasını bir akıştan algılamaya çalışır. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Mevcut [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) öğesinin belirtilen [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) ile aynı olup olmadığını belirler. |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Mevcut [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) öğesinin belirtilen nesne ile aynı olup olmadığını belirler. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Dosya uzantısını dosya türüne eşler. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Dosya uzantısını çıkarır ve bir dosya türüne eşler. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Bir dosya medya türünü bir [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) öğesine eşler (ör. 'application/pdf' , [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/) ile eşlenir). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Dosya imzasını okuyarak dosya türünü algılar. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Dosya imzasını okuyarak dosya türünü algılar. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Dosya imzasını okuyarak dosya türünü algılar. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Dosya imzasını okuyarak dosya türünü algılar. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Mevcut [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) nesnesi için hash kodunu döndürür. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Desteklenen dosya türlerini alır. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Mevcut nesneyi temsil eden bir str döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Dosya adı son eki (nokta "." dahil) ör. ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | Dosya türü adı ör. "Microsoft Word Document". |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Bilinmeyen dosya türünü temsil eder. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Zipped File (.zip), bir veya daha fazla dosya ya da dizin içerebilen arşivleri temsil eder. Bu dosya formatı hakkında daha fazla bilgiyi burada öğrenin. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Consolidated Unix File Archive (.tar), bir veya daha fazla dosyayı toplamak için Unix tabanlı araçla oluşturulan arşivlerdir. Bu dosya formatı hakkında daha fazla bilgiyi burada öğrenin. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | XZ file (.xz), LZMA algoritmasına dayalı yüksek oranlı bir sıkıştırma algoritmasıyla sıkıştırılmış bir arşivdir. Bu dosya formatı hakkında daha fazla bilgiyi burada öğrenin. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Consolidated Unix File Archive (.txz, .tar.xz), bir veya daha fazla dosyayı toplamak için Unix tabanlı araçla oluşturulan arşivlerdir. Bu dosya formatı hakkında daha fazla bilgiyi burada öğrenin. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Consolidated Unix File Archive (.txz, .tar.xz), bir veya daha fazla dosyayı toplamak için Unix tabanlı araçla oluşturulan arşivlerdir. Bu dosya formatı hakkında daha fazla bilgiyi burada öğrenin. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Consolidated Unix File Archive (.tgz, .tar.gz), bir veya daha fazla dosyayı toplamak için Unix tabanlı araçla oluşturulan arşivlerdir. Bu dosya formatı hakkında daha fazla bilgiyi burada öğrenin. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Consolidated Unix File Archive (.tgz, .tar.gz), bir veya daha fazla dosyayı toplamak için Unix tabanlı araçla oluşturulan arşivlerdir. Bu dosya formatı hakkında daha fazla bilgiyi burada öğrenin. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Bzip2 Compressed File (.bz2), çoğunlukla UNIX veya Linux sistemlerinde kullanılan BZIP2 açık kaynaklı sıkıştırma yöntemiyle oluşturulan sıkıştırılmış dosyalardır. Bu dosya formatı hakkında daha fazla bilgiyi burada öğrenin. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar), RAR (WINRAR) sıkıştırma yöntemi kullanılarak oluşturulan sıkıştırılmış dosyalardır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz), gzip sıkıştırma uygulamasıyla oluşturulan sıkıştırılmış dosyalardır. Birden fazla sıkıştırılmış dosya içerebilir ve genellikle UNIX ve Linux sistemlerinde kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip), Unix sistemlerinde kullanılan Compress programının yerine ücretsiz bir yardımcı program olarak tanıtıldı. Bu tür dosyalar, Windows ve macOS'ta bulunan WinZip gibi çeşitli uygulamalarla açılabilir ve çıkarılabilir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip), LZMA ve LZMA2 sıkıştırmasıyla ücretsiz açık kaynak arşivleyicidir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio, genel bir dosya arşivleme yardımcı programı ve ilişkili dosya formatıdır. Çoğunlukla Unix benzeri bilgisayar işletim sistemlerine kurulur. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST dosyası, Zstandard (zstd) sıkıştırma algoritmasıyla oluşturulan bir sıkıştırılmış dosyadır. Algoritma tarafından kayıpsız sıkıştırma ile yaratılan bir dosyadır. ZST dosyaları, veritabanları, dosya sistemleri, ağlar ve oyunlar gibi farklı dosya türlerini sıkıştırmak için kullanılabilir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST dosyaları (.tar.zst, .tzst), içinde birleştirilmiş Unix Dosya Arşivi (Tar) barındıran Zstandard arşivleridir (ZST) ve bir veya daha fazla dosyayı toplamak için Unix tabanlı bir yardımcı programla oluşturulmuştur. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST dosyaları (.tar.zst, .tzst), içinde birleştirilmiş Unix Dosya Arşivi (Tar) barındıran Zstandard arşivleridir (ZST) ve bir veya daha fazla dosyayı toplamak için Unix tabanlı bir yardımcı programla oluşturulmuştur. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO optik disk görüntüsü, CD veya DVD gibi bir optik diskteki tüm verinin içeriğini temsil eden, ISO-9660 standardına dayalı sıkıştırılmamış bir arşiv disk görüntü dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA veya LZH, ücretsiz bir sıkıştırma yardımcı programı ve ilişkili dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (veya CAB), Microsoft Windows için bir arşiv dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format Dosyası (.dxf), AutoCAD çizim dosyasının etiketli veri temsiliidir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database Dosyası (.dwg), 2D ve 3D tasarım verilerini içeren tescilli ikili dosyaları temsil eder. ASCII dosyalar olan DXF gibi, DWG de CAD (Computer Aided Design) çizimleri için ikili dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt), DWG dosyaları olarak kaydedilebilecek çizimler oluşturmak için başlangıç olarak kullanılan bir AutoCAD çizim şablonu dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography Dosyası (.stl), 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatıdır. Bu dosya formatı, hızlı prototipleme, 3D baskı ve bilgisayar destekli imalat gibi çeşitli alanlarda kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes Dosyası (.ifc), bina nesnelerini ve özelliklerini içe ve dışa aktarmak için uluslararası standartlar belirleyen bir dosya formatıdır. Bu dosya formatı, farklı yazılım uygulamaları arasında birlikte çalışabilirlik sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format Dosyası (.dwf), tasarım dosyalarını görüntüleme, inceleme veya yazdırma için sıkıştırılmış formatta 2D/3D çizimleri temsil eder. Tasarım verisinin bir parçası olarak grafik ve metin içerir ve sıkıştırılmış formatı sayesinde dosya boyutunu azaltır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange Dosyası (FilmBoX) (.fbx), 3D model formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format Dosyası XPS (.dwfx), tasarım dosyalarını görüntüleme, inceleme veya yazdırma için sıkıştırılmış formatta XPS belgesi olarak 2D/3D çizimleri temsil eder. Tasarım verisinin bir parçası olarak grafik ve metin içerir ve sıkıştırılmış formatı sayesinde dosya boyutunu azaltır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design Dosyası (.dgn), MicroStation ve Intergraph Interactive Graphics Design System gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt), Autodesk, Inc. tarafından tanıtılan vektör tabanlı bir plotter dosyasıdır ve belirli bir CAD dosyası için bilgi içerir. Çizim detayları üretimde doğruluk ve hassasiyet gerektirir ve PLT dosyasının kullanımı, tüm görüntülerin nokta yerine çizgiyle basılması sayesinde bunu garanti eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Common File Format Dosyası Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj), Wavefront Technologies tarafından tanıtılan 3D görüntü dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd), Microsoft Visio uygulamasıyla oluşturulan ve çeşitli grafik nesneleri ile bunların birbirleriyle bağlantılarını temsil eden çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx), Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eder. Önceki Microsoft Visio sürümlerinde desteklenen ikili dosya formatı .VSD'nin yerini alacak şekilde geliştirilmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File (.vss), Microsoft Visio 2007 ve önceki sürümlerle oluşturulan şablon dosyalarıdır. Şablon dosyaları, bir .VSD Visio çizimine eklenebilen çizim nesneleri sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx), Microsoft Visio 2013 ve sonraki sürümlerle oluşturulan çizim şablonlarıdır. VSSX dosya formatı Visio 2013 ve üzeri sürümlerle açılabilir. Visio dosyaları, şekil koleksiyonları, bağlayıcılar, akış şemaları, ağ düzeni, UML diyagramları gibi çeşitli çizim öğelerinin temsil edilmesiyle bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm), makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. VSDM dosyaları, VSDX'e benzer OPC/XML çizimleridir, ancak dosya açıldığında makroların çalıştırılmasını da sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst), Microsoft Visio ile oluşturulan ve sonraki dosyalar için şablon görevi gören vektör görüntü dosyalarıdır. Bu şablon dosyaları ikili dosya formatındadır ve yeni Visio çizimleri oluşturulurken kullanılan varsayılan düzen ve ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx), Microsoft Visio 2013 ve üzeri sürümlerle oluşturulan çizim şablon dosyalarıdır. Bu VSTX dosyaları, .VSDX dosyaları olarak kaydedilen Visio çizimleri için varsayılan düzen ve ayarlarla bir başlangıç noktası sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm), makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. VSDX dosyalarından farklı olarak, VSTM şablonlarından oluşturulan dosyalar Visual Basic for Applications (VBA) kodunda geliştirilen makroları çalıştırabilir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm), makroları destekleyen Microsoft Visio Şablon dosyalarıdır. Bir VSSM dosyası açıldığında, diyagramdaki şekillerin istenen biçimlendirilmesi ve yerleştirilmesi için makroların çalıştırılmasına izin verir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx), Microsoft Visio'da diyagram oluşturmak için kullanılan çizimler ve şekillerden oluşan şablonları ifade eder. VSX dosyaları XML dosya formatında kaydedilir ve Visio 2013'e kadar desteklenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx), XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonudur. Şablon, aynı ayarlarla birden fazla Visio dosyası oluşturmak için kullanılabilecek temel ayarları içeren bir dosya sağlamayı amaçlar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw), bir Web çiziminin renderlanması için gereken akışları ve depolamaları belirten dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx), Microsoft Visio'da oluşturulan ve XML formatında .VDX uzantısıyla kaydedilen herhangi bir çizim veya grafiği temsil eder. Visio çizim XML dosyası, Microsoft tarafından geliştirilen Visio yazılımında oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook Dosyası (.epub), yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır. Bu format artık o kadar yaygın ki birçok e-okuyucu ve yazılım uygulaması tarafından desteklenmektedir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi), en yaygın kullanılan e-kitap dosya formatlarından biridir. Bu format, eski OEB (Open Ebook Format) formatının bir geliştirmesidir ve Mobipocket Reader için özel bir format olarak kullanılmıştır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) e-kitabı, Amazon Kindle cihazları için geliştirilen dijital dosya formatıdır. Bu format, eski AZW dosyalarının bir geliştirmesidir ve yalnızca Kindle Fire cihazlarında, önceki dosya formatları olan MOBI ve AZW ile geriye dönük uyumluluk sağlayarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg), Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişiler, randevular veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E-Mail Message (.eml), Outlook ve diğer ilgili uygulamalarla kaydedilen e-posta mesajlarını temsil eder. Neredeyse tüm e-posta istemcileri, RFC-822 Internet Message Format Standardına uyumu nedeniyle bu dosya formatını destekler. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx), Apple tarafından uygulanmış ve geliştirilmiştir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya formatını kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst), çeşitli kullanıcı bilgilerini depolayan Outlook Personal Storage Files (aynı zamanda Personal Storage Table olarak da adlandırılır) dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost), Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif), bu dosya formatı standardına uyan çeşitli cihazlarda kullanılmak üzere tasarlanmış raster görüntüleri temsil eder. Birden fazla renk uzayında ikili seviye, gri tonlamalı, palet renkli ve tam renkli görüntü verilerini tanımlayabilir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff), bu dosya formatı standardına uyan çeşitli cihazlarda kullanılmak üzere tasarlanmış raster görüntüleri temsil eder. Birden fazla renk uzayında ikili seviye, gri tonlamalı, palet renkli ve tam renkli görüntü verilerini tanımlayabilir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG Image (.jpg), kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatıdır. Sıkıştırmanın sonucu olarak elde edilen çıktı görüntüsü, depolama boyutu ile görüntü kalitesi arasında bir denge sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG Image (.jpeg), kayıplı sıkıştırma yöntemiyle kaydedilen bir görüntü formatıdır. Sıkıştırmanın sonucu olarak elde edilen çıktı görüntüsü, depolama boyutu ile görüntü kalitesi arasında bir denge sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif), platformlar arasında hızlı değişim için geliştirilen bir görüntüdür. Bu format JPEG sıkıştırması kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png), kayıpsız sıkıştırma kullanan bir raster görüntü dosya formatıdır. Bu dosya formatı, Graphics Interchange Format (GIF) yerine oluşturulmuş ve telif hakkı sınırlamaları yoktur. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format File (.gif), yüksek sıkıştırmalı bir görüntü türüdür. Her bir GIF görüntüsü tipik olarak piksel başına 8 bit ve toplamda 256 renk izin verir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng), animasyonu destekleyen PNG formatının bir uzantısıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Bitmap Image File (.bmp), bitmap dijital görüntüleri depolamak için kullanılır. Bu görüntüler grafik adaptöründen bağımsızdır ve aynı zamanda cihaz bağımsız bitmap (DIB) dosya formatı olarak da adlandırılır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA), TRUEVISION tarafından geliştirilen bitmap dijital görüntüleri depolamak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Icon File (.ico), Microsoft Windows'ta bir uygulamanın temsilinde simge olarak kullanılan görüntü dosyası türleridir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image File (.jp2), bir görüntü kodlama sistemi ve son teknoloji görüntü sıkıştırma standardıdır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | JPEG 2000 Image File (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | JPEG 2000 Image File (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | JPEG 2000 Image File (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | JPEG 2000 Code Stream (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 Code Stream (.j2k), DCT sıkıştırması yerine dalgacık sıkıştırması kullanılarak sıkıştırılan bir görüntüdür. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | JPEG 2000 Code Stream (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Device Independent Bitmap File (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf), vektör ve bitmap formatındaki görüntü verilerini depolamak için Microsoft Windows Metafile (WMF) dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz), vektör ve bitmap formatındaki görüntü verilerini depolamak için GZIP arşivinde sıkıştırılmış Microsoft Windows Metafile (WMF) dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf), grafik görüntüleri cihaz bağımsız olarak temsil eder. EMF metafile'ları, saklanan görüntüyü herhangi bir çıkış cihazında ayrıştırdıktan sonra oluşturabilen, kronolojik sırada değişken uzunlukta kayıtlar içerir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz), GZIP ile sıkıştırılmış cihaz bağımsız grafik görüntüleri temsil eder. EMF metafile'ları, saklanan görüntüyü herhangi bir çıkış cihazında ayrıştırdıktan sonra oluşturabilen, kronolojik sırada değişken uzunlukta kayıtlar içerir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp), kayıpsız ve kayıplı sıkıştırmaya dayalı modern bir raster web görüntü dosya formatıdır. Görüntü boyutunu önemli ölçüde azaltırken aynı görüntü kalitesini sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng), ham dosyaların depolanması için kullanılan bir dijital kamera görüntü formatıdır. Eylül 2004'te Adobe tarafından geliştirilmiştir. Temelde dijital fotoğrafçılık için geliştirilmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr), dijital görüntüyü kodlamak ve sıkıştırmak için CorelDRAW ile yerel olarak oluşturulan bir vektör çizim dosyasıdır. Böyle bir çizim dosyası, görüntü içeriğinin vektör temsili için metin, çizgiler, şekiller, görüntüler, renkler ve efektler içerir. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx), vektör grafiklerin yanı sıra bitmap grafikler de içerebilen bir çizim görüntü dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu), özellikle metin, çizim, görüntü ve fotoğraf kombinasyonunu içeren taranmış belgeler ve kitaplar için tasarlanmış bir grafik dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm), vektör grafikler (2D), raster grafikler ve metinlerin depolanması ve değiş tokuşu için ücretsiz, platform bağımsız, uluslararası bir standart metafile formatıdır. CGM, görüntü üretimi için nesne yönelimli yaklaşım ve birçok işlev sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language Document (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd), grafik tasarımı ve geliştirme için kullanılan Adobe Photoshop'un yerel dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb), grafik tasarımı ve geliştirme için kullanılan Photoshop Large Document Format'ı temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin burada. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | DICOM Image (.dcm) dijital bir görüntüyü temsil eder ve hastaların MRİ, BT taramaları ve ultrason görüntüleri gibi tıbbi bilgilerini depolar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | PostScript Dosyası (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Encapsulated PostScript File (.eps), tek bir sayfanın görünümünü tanımlayan bir Encapsulated PostScript dil programını açıklar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | OpenDocument Graphic File (.odg), Apache OpenOffice'un Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Flat XML ODF Template (.fodg), Apache OpenOffice'un Draw uygulaması tarafından çizim öğelerini vektör görüntü olarak depolamak için kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Scalable Vector Graphics File (.svg), bir görüntünün görünümünü tanımlamak için XML tabanlı metin formatı kullanan bir Scalable Vector Graphics dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Scalable Vector Graphics File (.svgz), bir görüntünün görünümünü tanımlamak için XML tabanlı metin formatı kullanan ve GZIP ile sıkıştırılmış bir Scalable Vector Graphics dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | OpenDocument Graphic Şablonu (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Hypertext Markup Language File (.htm), tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları için uzantıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Hypertext Markup Language File (.html), tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları için uzantıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | MHTML Web Arşivi (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | MIME HTML Dosyası (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | XML File (.xml). GroupDocs.Viewer, XML dosyalarını işlemek için özel bir işlemciye sahiptir, belgeleri inceleyin. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | OneNote Document (.one), Microsoft OneNote uygulaması tarafından oluşturulur. OneNote, not alırken taslak defterinizi kullanıyormuş gibi uygulamayı kullanarak bilgi toplamanıza olanak tanır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Portable Document Format File (.pdf), 1990'larda Adobe tarafından oluşturulan bir belge türüdür. Bu dosya formatının amacı, belgelerin ve diğer referans materyallerinin uygulama yazılımı, donanım ve işletim sisteminden bağımsız bir formatta temsil edilmesi için bir standart getirmekti. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | XML Paper Specification File (.xps), Microsoft tarafından oluşturulan XML Paper Specification temelli sayfa düzeni dosyalarını temsil eder. Bu format, EMF dosya formatının yerine Microsoft tarafından geliştirilmiş olup PDF dosya formatına benzer, ancak bir belgenin düzen, görünüm ve baskı bilgileri için XML kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | OpenXPS Dosyası (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | LaTeX Source Document (.tex), programlama ve işaretleme özelliklerini içeren, belgeleri biçimlendirmek için kullanılan bir dildir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | GB/T 33190-2016 tarafından tanımlanan Open Fixed-layout Document (OFD) formatı, Çin kamu kurumlarında PDF'nin yerini almayı hedeflemektedir. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | PowerPoint Presentation (.ppt), slayt gösterisi olarak görüntülenmek üzere bir dizi slayt içeren PowerPoint dosyasını temsil eder. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Formatını belirtir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | PowerPoint Open XML Presentation (.pptx), popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. Önceki ikili PPT formatının aksine, PPTX formatı Microsoft PowerPoint açık XML sunum dosya formatına dayanır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | PowerPoint Slide Show (.pps), Microsoft PowerPoint kullanılarak slayt gösterisi amacıyla oluşturulur. PPS dosyalarının okunması ve oluşturulması Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | PowerPoint Open XML Slide Show (.ppsx) dosyaları, Microsoft PowerPoint 2007 ve üzeri sürümlerle slayt gösterisi amacıyla oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | OpenDocument Presentation (.odp), OpenOffice.org tarafından OASISOpen standardında kullanılan sunum dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | OpenDocument Presentation (.fodp), OpenDocument Düz XML Sunumu'nu temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint Şablonu (.pot) Microsoft PowerPoint 97-2003 sürümleri tarafından oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Makro Etkin Sunum, Microsoft PowerPoint 2007 veya daha yeni sürümlerle oluşturulan makro etkin sunum dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Sunum Şablonu (.potx) Microsoft PowerPoint 2007 ve üzeri sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Makro Etkin Sunum Şablonu (.potm) makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM dosyaları PowerPoint 2007 veya üzeri sürümlerle oluşturulur ve sonraki sunum dosyalarını oluşturmak için kullanılabilecek varsayılan ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Makro Etkin Slayt (.ppsm) Microsoft PowerPoint 2007 veya üzeri sürümlerle oluşturulan makro etkin slayt gösterisi dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Sunum Şablonu (.otp) OASIS OpenDocument standart formatında uygulamalar tarafından oluşturulan sunum şablonu dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Çalışma Sayfası (.xls) Excel İkili Dosya Formatını temsil eder. Bu dosyalar Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi benzer tablo programlarıyla da oluşturulabilir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) Excel İkili Dosya Formatını temsil eder. Bu dosyalar Microsoft Excel'in yanı sıra OpenOffice Calc veya Apple Numbers gibi benzer tablo programlarıyla da oluşturulabilir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers, Excel benzeri bir İkili Dosya Formatını temsil eder. Bu dosyalar Apple Numbers uygulamasıyla oluşturulabilir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Çalışma Sayfası (.xlsx) Microsoft Office 2007 sürümüyle Microsoft tarafından tanıtılan Microsoft Excel belgeleri için yaygın bir formattır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Makro Etkin Çalışma Sayfası (.xlsm) makroları destekleyen bir tür çalışma sayfası dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel İkili Çalışma Sayfası (.xlsb) Excel çalışma kitabı içeriğini belirleyen kayıt ve yapılar koleksiyonunu içeren Excel İkili Dosya Formatını tanımlar. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Virgülle Ayrılmış Değerler Dosyası (.csv) virgülle ayrılmış değerler içeren veri kayıtlarını barındıran düz metin dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Sekme Ayrılmış Değerler Dosyası (.tsv) sekmelerle ayrılmış verileri içeren düz metin formatındaki dosyaları temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Çalışma Sayfası (.ods) kullanıcı tarafından düzenlenebilen OpenDocument Çalışma Sayfası belge formatını ifade eder. Veriler ODF dosyası içinde satır ve sütunlar halinde depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Düz XML Çalışma Sayfası (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Çalışma Sayfası Şablonu (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Eklentisi (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Makro Etkin Şablonu (.xltm) Microsoft Excel tarafından makro etkin şablon dosyaları olarak oluşturulan dosyaları temsil eder. XLTM dosyaları, yapısal olarak XLTX dosyalarına benzer, ancak XLTX makrolu şablon dosyaları oluşturmayı desteklemez. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Şablonu (.xlt) Microsoft Office paketinin bir parçası olan bir tablo uygulaması olan Microsoft Excel ile oluşturulan şablon dosyalarıdır. Microsoft Office 97-2003, yeni XLT dosyaları oluşturmayı ve bu dosyaları açmayı desteklemiştir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Çalışma Sayfası Şablonu (.xltx) Office OpenXML dosya formatı spesifikasyonlarına dayanan Microsoft Excel Şablonlarını temsil eder. Bu, XLTX dosyasında belirtilen aynı ayarları gösteren XLSX dosyaları oluşturmak için kullanılabilecek standart bir şablon dosyası yaratmak amacıyla kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Çalışma Sayfası (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project Dosyası (.mpp), proje yönetimiyle ilgili bilgileri bütünleşik bir şekilde depolayan Microsoft Project veri dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project Şablonu (.mpt), .MPP dosyaları oluşturmak için temel bilgi ve yapıyı belge ayarlarıyla birlikte içerir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange dosyası (.mpx), Microsoft Project (MSP) ile Primavera Project Planner, Sciforma ve Timerline Precision Estimating gibi MPX dosya formatını destekleyen diğer uygulamalar arasında proje bilgilerini aktarmak için kullanılan bir ASCII dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ActionScript Dosyası (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ActionScript Dosyası (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Assembly Dili Kaynak Kodu Dosyası (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | DOS Toplu İş Dosyası (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | C/C++ Kaynak Kodu Dosyası (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | C++ Kaynak Kodu Dosyası (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | CMake Dosyası (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | C++ Kaynak Kodu Dosyası (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C# Kaynak Kodu Dosyası (.cs), C# programlama dili için bir kaynak kod dosyasıdır. Microsoft tarafından .NET Framework ile kullanım için tanıtılmıştır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic Proje Öğesi Dosyası (.vb), Microsoft tarafından .NET uygulamaları geliştirmek için oluşturulan Visual Basic dilinde bir kaynak kod dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Katmanlı Stil Sayfası (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | C++ Kaynak Kodu Dosyası (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | Yama Dosyası (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby ERB Betiği (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Groovy Kaynak Kodu Dosyası (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | C/C++/Objective-C Başlık Dosyası (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Haml Kaynak Kodu Dosyası (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | C++ Başlık Dosyası (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Java Kaynak Kodu Dosyası (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | JavaScript Dosyası (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | JavaScript Nesne Gösterimi Dosyası (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS Stil Sayfası (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | Günlük Dosyası (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Objective-C Uygulama Dosyası (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Xcode Makefile Betiği (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Markdown Dokümantasyon Dosyası (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ML Kaynak Kodu Dosyası (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Objective-C++ Kaynak Dosyası (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | PHP Kaynak Kodu Dosyası (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Perl Betiği (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Java Özellik Dosyası (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Python Betiği (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Ruby Kaynak Kodu (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | reStructuredText Dosyası (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Syntactically Awesome StyleSheets Dosyası (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Scala Kaynak Kodu Dosyası (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Scheme Kaynak Kodu Dosyası (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | Genel Betik Dosyası (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Bash Kabuk Betiği (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Standard ML Kaynak Kodu Dosyası (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Structured Query Language Veri Dosyası (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Vim Ayar Dosyası (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | YAML Belgesi (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word Belgesi (.doc) Microsoft Word veya diğer kelime işlemci programları tarafından ikili dosya biçiminde oluşturulan belgeleri temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML Belgesi (.docx) Microsoft Word belgeleri için yaygın bir formattır. 2007'de Microsoft Office 2007'in yayınlanmasıyla tanıtılan bu yeni Belge formatının yapısı, düz ikili dosyadan XML ve ikili dosyaların bir kombinasyonuna değiştirildi. Bu dosya biçimi hakkında daha fazla bilgi edinin. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Derlenmiş HTML Yardım Dosyası (.chm) HELP (bazı uygulamalar için dokümantasyon) belgeleri için yaygın bir formattır. Bu dosya biçimi hakkında daha fazla bilgi edinin. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML Makro Etkin Belgesi (.docm) makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan belgelerdir. Bu dosya biçimi hakkında daha fazla bilgi edinin. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word Belge Şablonu (.dot) Microsoft Word tarafından daha sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip şablon dosyaları olarak oluşturulur. Bu dosya biçimi hakkında daha fazla bilgi edinin. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx), Microsoft Word tarafından oluşturulan ve sonraki DOCX dosyalarının üretilmesi için önceden biçimlendirilmiş ayarlara sahip şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm), Microsoft Word 2007 veya daha yeni bir sürümle oluşturulan şablon dosyasını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemi olarak temsil edilir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt), satırlar şeklinde düz metin içeren bir metin belgesini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt), OpenDocument Metin Dosyası formatına dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott), OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgelerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf), iletişim bilgilerini depolamak için kullanılan dijital bir dosya formatıdır. Bu format, popüler bilgi alışverişi uygulamaları arasında veri değişimi için yaygın olarak kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai), Adobe Illustrator çizimleri için bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1), PowerShell modül betikleri için bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1), Windows PowerShell Cmdlet dosyaları için bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1), PowerShell modül manifest betikleri için bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin. |

### Örnek

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Belgeyi yüklerken dosya türünü (ör. Markdown) belirtin
load_options = LoadOptions(FileType.MD)

# Belgeyi PDF olarak oluştur
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
