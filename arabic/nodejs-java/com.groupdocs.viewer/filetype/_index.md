---
title: "FileType"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل نوع الملف."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل مكوّن GroupDocs.Viewer.

توفّر تعداد FileType ثوابت تمثل أنواع ملفات مختلفة مدعومة من قبل مكوّن GroupDocs.Viewer. يمكنك استخدام الطرق في هذا التعداد للحصول على قائمة بجميع أنواع الملفات المدعومة أو للتحقق مما إذا كان نوع ملف معين مدعومًا.

مثال على الاستخدام:

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
## الحقول

| حقل | الوصف |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | يمثل نوع ملف غير معروف. |
| [ZIP](#ZIP) | يمثل ملفًا مضغوطًا (.zip) يمكنه احتواء ملف أو أكثر أو أدلة. |
| [TAR](#TAR) | يمثل أرشيف Unix موحد (.tar) تم إنشاؤه لجمع ملف أو أكثر. |
| [XZ](#XZ) | يمثل ملف XZ (.xz) مضغوط باستخدام خوارزمية ضغط عالية النسبة تعتمد على خوارزمية LZMA. |
| [TXZ](#TXZ) | يمثل أرشيف Unix موحد (.txz، .tar.xz) تم إنشاؤه لجمع ملف أو أكثر. |
| [TARXZ](#TARXZ) | يمثل أرشيف Unix موحد (.txz، .tar.xz) تم إنشاؤه لجمع ملف أو أكثر. |
| [TGZ](#TGZ) | يمثل أرشيف Unix موحد (.tgz، .tar.gz) تم إنشاؤه لجمع ملف أو أكثر. |
| [TARGZ](#TARGZ) | يمثل أرشيف Unix موحد (.tgz، .tar.gz) تم إنشاؤه لجمع ملف أو أكثر. |
| [BZ_2](#BZ-2) | يمثل ملفًا مضغوطًا بتقنية Bzip2 (.bz2) تم إنشاؤه باستخدام طريقة الضغط المفتوحة المصدر BZIP2. |
| [RAR](#RAR) | يمثل ملف أرشيف روسال (.rar) مضغوط تم إنشاؤه باستخدام طريقة الضغط RAR (الإصدار 4 من WINRAR). |
| [GZ](#GZ) | يمثل ملف Gnu مضغوط (.gz) تم إنشاؤه باستخدام تطبيق الضغط gzip. |
| [GZIP](#GZIP) | يمثل ملف Gnu Zipped (.gzip) مضغوط تم تقديمه كأداة مجانية لاستبدال برنامج Compress المستخدم في أنظمة Unix. |
| [SEVEN_ZIP](#SEVEN-ZIP) | يمثل ملف 7Zip (.7z, .7zip)، وهو أرشيف مجاني مفتوح المصدر يستخدم ضغط LZMA و LZMA2. |
| [CPIO](#CPIO) | Cpio هو أداة أرشفة ملفات عامة وتنسيق الملف المرتبط بها. |
| [ZSTANDARD](#ZSTANDARD) | ملف ZST هو ملف مضغوط يتم إنشاؤه باستخدام خوارزمية الضغط Zstandard (zstd). |
| [TZST](#TZST) | ملفات TZST (.tar.zst, .tzst) هي أرشيفات Zstandard (ZST)، والتي تحتوي داخليًا على أرشيف ملفات Unix موحد (Tar)، تم إنشاؤه بأداة تعتمد على Unix لجمع ملف واحد أو أكثر. |
| [TAR_ZST](#TAR-ZST) | ملفات TZST (.tar.zst, .tzst) هي أرشيفات Zstandard (ZST)، والتي تحتوي داخليًا على أرشيف ملفات Unix موحد (Tar)، تم إنشاؤه بأداة تعتمد على Unix لجمع ملف واحد أو أكثر. |
| [ISO](#ISO) | صورة قرص بصري ISO هي ملف صورة قرص أرشيف غير مضغوط يمثل محتويات البيانات الكاملة على قرص بصري مثل CD أو DVD، بناءً على معيار ISO-9660. |
| [LHA](#LHA) | LHA أو LZH هي أداة ضغط مجانية وتنسيق ملف مرتبط. |
| [CAB](#CAB) | Cabinet (أو CAB) هو تنسيق ملف أرشيف لنظام Microsoft Windows. |
| [DXF](#DXF) | يمثل ملف Drawing Exchange Format (.dxf)، وهو تمثيل بيانات معلمة لملف رسم AutoCAD. |
| [DWG](#DWG) | يمثل ملف قاعدة بيانات رسم AutoCAD (.dwg)، وهو ملفات ثنائية مملوكة تستخدم لتخزين بيانات التصميم ثنائية وثلاثية الأبعاد. |
| [DWT](#DWT) | يمثل قالب رسم AutoCAD (.dwt)، وهو ملف قالب رسم AutoCAD يُستخدم كنقطة بداية لإنشاء رسومات يمكن حفظها كملفات DWG. |
| [STL](#STL) | يمثل ملف Stereolithography (.stl)، وهو تنسيق ملف قابل للتبادل يمثل الهندسة السطحية ثلاثية الأبعاد. |
| [IFC](#IFC) | يمثل ملف Industry Foundation Classes (.ifc)، وهو تنسيق ملف يضع معايير دولية لاستيراد وتصدير كائنات المباني وخصائصها. |
| [DWF](#DWF) | يمثل ملف Design Web Format (.dwf)، وهو تنسيق ملف مضغوط لعرض أو مراجعة أو طباعة الرسومات ثنائية أو ثلاثية الأبعاد. |
| [FBX](#FBX) | يمثل ملف Autodesk FBX Interchange (FilmBoX) (.fbx)، وهو تنسيق نموذج ثلاثي الأبعاد. |
| [DWFX](#DWFX) | يمثل ملف Design Web Format XPS (.dwfx)، وهو تنسيق مضغوط لعرض أو مراجعة أو طباعة الرسومات ثنائية أو ثلاثية الأبعاد كوثيقة XPS. |
| [DGN](#DGN) | يمثل ملف تصميم MicroStation (.dgn)، وهو رسومات تم إنشاؤها ودعمها بواسطة تطبيقات CAD مثل MicroStation و Intergraph Interactive Graphics Design System. |
| [PLT](#PLT) | يمثل ملف PLT (HPGL) (.plt)، وهو ملف رسام متجه تم تقديمه من قبل Autodesk, Inc. |
| [CF2](#CF2) | يمثل ملف Common File Format (.cf2). |
| [OBJ](#OBJ) | يمثل ملف Wavefront 3D Object (.obj)، وهو ملف صورة ثلاثية الأبعاد تم تقديمه من قبل Wavefront Technologies. |
| [HPG](#HPG) | يمثل ملف PLT (HPGL) (.hpg). |
| [IGS](#IGS) | يمثل ملف Initial Graphics Exchange Specification (IGES) (.igs). |
| [VSD](#VSD) | يمثل ملف Visio Drawing (.vsd)، وهو رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية وروابطها. |
| [VSDX](#VSDX) | يمثل ملف Visio Drawing (.vsdx)، وهو تنسيق ملف Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. |
| [VSS](#VSS) | يمثل ملف Visio Stencil (.vss)، وهو ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio 2007 والإصدارات السابقة. |
| [VSSX](#VSSX) | يمثل ملف قالب Visio (.vssx)، وهو قالب رسومات تم إنشاؤه باستخدام Microsoft Visio 2013 وما فوق. |
| [VSDM](#VSDM) | يمثل رسمًا مدعومًا بالماكرو في Visio (.vsdm)، وهو ملف رسم تم إنشاؤه باستخدام تطبيق Microsoft Visio الذي يدعم الماكرو. |
| [VST](#VST) | يمثل قالب رسم Visio (.vst)، وهو ملف صورة متجهة تم إنشاؤه باستخدام Microsoft Visio. |
| [VSTX](#VSTX) | يمثل قالب رسم Visio (.vstx)، وهو ملف قالب رسم تم إنشاؤه باستخدام Microsoft Visio 2013 وما فوق. |
| [VSTM](#VSTM) | يمثل قالب رسم مدعوم بالماكرو في Visio (.vstm)، وهو ملف قالب تم إنشاؤه باستخدام Microsoft Visio الذي يدعم الماكرو. |
| [VSSM](#VSSM) | يمثل ملف قالب Visio مدعوم بالماكرو (.vssm)، وهو ملف قالب Microsoft Visio يدعم الماكرو. |
| [VSX](#VSX) | يمثل ملف قالب Visio XML (.vsx)، وهو يشير إلى القوالب التي تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. |
| [VTX](#VTX) | يمثل ملف قالب Visio XML (.vtx)، وهو قالب رسم Microsoft Visio يُحفظ على القرص بصيغة ملف XML. |
| [VDW](#VDW) | يمثل رسم Visio ويب (.vdw)، وهو يحدد التدفقات والتخزينات المطلوبة لتصيير رسم ويب. |
| [VDX](#VDX) | يمثل ملف رسم Visio XML (.vdx)، وهو يمثل أي رسم أو مخطط تم إنشاؤه في Microsoft Visio لكنه محفوظ بصيغة XML بامتداد .VDX. |
| [EPUB](#EPUB) | يمثل ملف كتاب إلكتروني مفتوح (.epub)، وهو تنسيق ملف كتاب إلكتروني يوفر صيغة نشر رقمية قياسية للناشرين والمستهلكين. |
| [MOBI](#MOBI) | يمثل كتابًا إلكترونيًا من نوع Mobipocket (.mobi)، وهو أحد أكثر تنسيقات الكتب الإلكترونية استخدامًا. |
| [AZW_3](#AZW-3) | كتاب إلكتروني بتنسيق Amazon Kindle Format 8 (KF8) هو تنسيق ملف رقمي تم تطويره لأجهزة Amazon Kindle. |
| [MSG](#MSG) | يمثل رسالة بريد Outlook (.msg)، وهو تنسيق ملف يستخدمه Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. |
| [EML](#EML) | يمثل رسالة بريد إلكتروني (.eml)، وهو يمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. |
| [EMLX](#EMLX) | يمثل رسالة بريد Apple Mail (.emlx)، وهو تم تنفيذها وتطويرها من قبل Apple. |
| [PST](#PST) | يمثل ملف مخزن المعلومات الشخصية في Outlook (.pst)، وهو يمثل ملفات تخزين شخصية في Outlook (تُعرف أيضًا بجدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم. |
| [OST](#OST) | يمثل ملف بيانات Outlook غير المتصل (.ost)، وهو يمثل بيانات صندوق بريد المستخدم في وضع غير متصل على جهاز محلي عند التسجيل في خادم Exchange باستخدام Microsoft Outlook. |
| [TIF](#TIF) | يمثل ملف صورة موسومة (.tif)، وهو يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. |
| [TIFF](#TIFF) | يمثل تنسيق ملف صورة موسومة (.tiff)، وهو يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. |
| [JPG](#JPG) | يمثل صورة JPEG (.jpg)، وهو نوع من تنسيقات الصور التي تُحفظ باستخدام طريقة الضغط الفاقد. |
| [JPEG](#JPEG) | يمثل صورة JPEG (.jpeg)، وهو نوع من تنسيقات الصور التي تُحفظ باستخدام طريقة الضغط الفاقد. |
| [JFIF](#JFIF) | تنسيق تبادل ملفات JPEG (.jfif) هو صورة تم تطويرها لتبادل سريع بين منصات الأنظمة والأجهزة المختلفة. |
| [PNG](#PNG) | يمثل صورة شبكة محمولة (.png)، وهو نوع من تنسيقات ملفات الصور النقطية التي تستخدم ضغطًا غير فقدان للبيانات. |
| [GIF](#GIF) | يمثل ملف تنسيق تبادل رسومي (.gif)، وهو نوع من الصور ذات ضغط عالي. |
| [APNG](#APNG) | يمثل تنسيق Animated Portable Network Graphic (.apng)، وهو امتداد لتنسيق PNG يدعم الرسوم المتحركة. |
| [BMP](#BMP) | يمثل ملف صورة نقطية (Bitmap Image File) (.bmp)، يُستخدم لتخزين الصور الرقمية النقطية. |
| [ICO](#ICO) | يمثل ملف أيقونة (.ico)، وهو نوع ملف صورة يُستخدم كأيقونة لتمثيل تطبيق على نظام Microsoft Windows. |
| [TGA](#TGA) | يمثل ملف Truevision TGA (TARGA)، يُستخدم لتخزين الصور الرقمية النقطية التي طورتها شركة TRUEVISION. |
| [JP_2](#JP-2) | يمثل ملف صورة JPEG 2000 Core Image (.jp2)، وهو نظام ترميز صور ومعيار ضغط صور متقدم. |
| [JPF](#JPF) | يمثل ملف صورة JPEG 2000 (.jpf). |
| [JPX](#JPX) | يمثل ملف صورة JPEG 2000 (.jpx). |
| [JPM](#JPM) | يمثل ملف صورة JPEG 2000 (.jpm). |
| [J2C](#J2C) | يمثل تدفق إدخال شفرة JPEG 2000 (.j2c). |
| [J2K](#J2K) | يمثل تدفق شفرة JPEG 2000 (.j2k)، وهو صورة مضغوطة باستخدام ضغط الموجات بدلاً من ضغط DCT. |
| [JPC](#JPC) | يمثل تدفق شفرة JPEG 2000 (.jpc). |
| [JLS](#JLS) | يمثل ملف JPEG-LS (JLS) (.jls). |
| [DIB](#DIB) | يمثل ملف صورة نقطية غير معتمد على الجهاز (.dib). |
| [WMF](#WMF) | يمثل ملف Windows Metafile (.wmf)، وهو ملف Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهة وكذلك النقطية. |
| [WMZ](#WMZ) | يمثل ملف Windows Metafile مضغوط (.wmz)، وهو ملف Microsoft Windows Metafile (WMF) مضغوط في أرشيف GZIP لتخزين بيانات الصور المتجهة والنقطية. |
| [EMF](#EMF) | يمثل ملف Enhanced Windows Metafile (.emf)، وهو يمثل الصور الرسومية بشكل غير معتمد على الجهاز. |
| [EMZ](#EMZ) | يمثل ملف Enhanced Metafile مضغوط لنظام Windows (.emz)، وهو يمثل الصور الرسومية غير المعتمدة على الجهاز ومضغوطة بواسطة GZIP. |
| [WEBP](#WEBP) | يمثل صورة WebP (.webp)، وهو تنسيق ملف صورة نقطية حديث للويب يعتمد على ضغط غير فقداني وفاقد. |
| [DNG](#DNG) | يمثل مواصفة Digital Negative (.dng)، وهو تنسيق صورة كاميرا رقمية يُستخدم لتخزين الملفات الخام. |
| [CDR](#CDR) | يمثل رسم رسومي متجه CorelDraw (.cdr)، وهو ملف صورة رسم متجه تم إنشاؤه أصلاً باستخدام CorelDRAW لتخزين الصور المشفرة رقمياً والمضغوطة. |
| [CMX](#CMX) | يمثل ملف Corel Exchange (.cmx)، وهو ملف صورة رسم قد يحتوي على رسومات متجهة وكذلك رسومات نقطية. |
| [DJVU](#DJVU) | يمثل صورة DjVu (.djvu)، وهو تنسيق ملف رسومي مخصص للمستندات والكتب الممسوحة ضوئياً، خاصة تلك التي تحتوي على مزيج من النصوص والرسومات والصور والفوتوغرافات. |
| [CGM](#CGM) | يمثل ملف Computer Graphics Metafile (.cgm)، وهو تنسيق ملف ميتا مجاني غير معتمد على المنصة، معيار دولي لتخزين وتبادل الرسومات المتجهة (2D) والرسومات النقطية والنص. |
| [PCL](#PCL) | يمثل مستند Printer Command Language (.pcl). |
| [PSD](#PSD) | يمثل مستند Adobe Photoshop (.psd)، وهو تنسيق الملف الأصلي لبرنامج Adobe Photoshop يُستخدم لتصميم وتطوير الرسومات. |
| [PSB](#PSB) | يمثل تنسيق مستند فوتوشوب كبير (.psb)، والذي يُستخدم لتصميم وتطوير الرسومات في Adobe Photoshop. |
| [DCM](#DCM) | يمثل صورة DICOM (.dcm)، والتي تمثل صورة رقمية تخزن المعلومات الطبية للمرضى مثل صور الرنين المغناطيسي، والمسحات المقطعية، وصور الموجات فوق الصوتية. |
| [PS](#PS) | يمثل ملف PostScript (.ps). |
| [EPS](#EPS) | يمثل ملف Encapsulated PostScript (.eps)، والذي يصف برنامج لغة Encapsulated PostScript يحدد مظهر صفحة واحدة. |
| [ODG](#ODG) | يمثل ملف رسومي OpenDocument (.odg)، والذي يستخدمه تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. |
| [FODG](#FODG) | يمثل قالب XML ODF مسطح (.fodg)، والذي يستخدمه تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. |
| [SVG](#SVG) | يمثل ملف رسومات متجهة قابلة للتوسع (.svg)، وهو ملف رسومات متجهة يستخدم تنسيق نصي قائم على XML لوصف مظهر الصورة. |
| [SVGZ](#SVGZ) | يمثل ملف رسومات متجهة قابلة للتوسع مضغوط (.svgz)، وهو ملف رسومات متجهة يستخدم تنسيق نصي قائم على XML، مضغوط بـ GZIP، لوصف مظهر الصورة. |
| [OTG](#OTG) | يمثل قالب رسومي OpenDocument (.otg). |
| [HTM](#HTM) | يمثل ملف لغة ترميز النص الفائق (.htm)، وهو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات. |
| [HTML](#HTML) | يمثل ملف لغة ترميز النص الفائق (.html)، وهو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات. |
| [MHT](#MHT) | يمثل أرشيف ويب MHTML (.mht). |
| [NSF](#NSF) | يمثل قاعدة بيانات Lotus Notes (.nsf). |
| [MBOX](#MBOX) | يمثل ملف صندوق بريد البريد الإلكتروني (.mbox). |
| [MHTML](#MHTML) | يمثل ملف MIME HTML (.mhtml). |
| [XML](#XML) | يمثل ملف XML (.xml). |
| [ONE](#ONE) | يمثل مستند OneNote (.one) تم إنشاؤه بواسطة تطبيق Microsoft OneNote. |
| [PDF](#PDF) | يمثل ملف تنسيق المستند المحمول (.pdf)، وهو نوع من المستندات تم إنشاؤه بواسطة Adobe في التسعينيات. |
| [XPS](#XPS) | يمثل ملف مواصفات ورق XML (.xps)، والذي يمثل ملفات تخطيط الصفحات المستندة إلى مواصفات ورق XML التي أنشأتها Microsoft. |
| [OXPS](#OXPS) | يمثل ملف OpenXPS (.oxps). |
| [TEX](#TEX) | يمثل مستند مصدر LaTeX (.tex)، وهو لغة تشمل البرمجة بالإضافة إلى ميزات الترميز المستخدمة لتنسيق المستندات. |
| [PPT](#PPT) | يمثل عرض PowerPoint (.ppt)، والذي يمثل ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض شرائح. |
| [PPTX](#PPTX) | يمثل عرض PowerPoint Open XML (.pptx)، وهي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. |
| [PPS](#PPS) | يمثل عرض شرائح PowerPoint (.pps)، والذي يتم إنشاؤه باستخدام Microsoft PowerPoint لأغراض عرض الشرائح. |
| [PPSX](#PPSX) | يمثل ملفات عرض شرائح PowerPoint Open XML (.ppsx)، والتي يتم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق لأغراض عرض الشرائح. |
| [ODP](#ODP) | يمثل عرض OpenDocument (.odp)، وهو تنسيق ملف عرض يُستخدم بواسطة OpenOffice.org في معيار OASISOpen. |
| [FODP](#FODP) | يمثل عرض OpenDocument (.fodp)، وهو عرض OpenDocument Flat XML. |
| [POT](#POT) | يمثل قالب PowerPoint (.pot)، وهو ملفات قوالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. |
| [PPTM](#PPTM) | يمثل عرض PowerPoint Open XML مع تمكين الماكرو (.pptm)، وهو ملفات عرض مُمكَّنة للماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. |
| [POTX](#POTX) | يمثل قالب عرض PowerPoint Open XML (.potx)، وهو عروض قوالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق. |
| [POTM](#POTM) | يمثل قالب عرض PowerPoint Open XML مع تمكين الماكرو (.potm)، وهو ملفات قوالب Microsoft PowerPoint التي تدعم الماكرو. |
| [PPSM](#PPSM) | يمثل شريحة PowerPoint Open XML مع تمكين الماكرو (.ppsm)، وهو تنسيق ملف عرض شرائح مُمكَّن للماكرو تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. |
| [OTP](#OTP) | يمثل قالب عرض OpenDocument (.otp)، وهو ملفات قوالب العرض التي تم إنشاؤها بواسطة التطبيقات وفق تنسيق معيار OASIS OpenDocument. |
| [XLS](#XLS) | يمثل جدول بيانات Excel (.xls)، وهو تنسيق ملف Excel الثنائي. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | يمثل Excel 2003 XML (SpreadsheetML) (.xml)، وهو تنسيق ملف Excel الثنائي. |
| [NUMBERS](#NUMBERS) | يمثل Apple Numbers (.numbers)، وهو تنسيق ملف ثنائي يشبه Excel. |
| [XLSX](#XLSX) | يمثل جدول بيانات Microsoft Excel Open XML (.xlsx)، وهو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. |
| [XLSM](#XLSM) | يمثل جدول بيانات Excel Open XML مع تمكين الماكرو (.xlsm)، وهو نوع من ملفات الجداول التي تدعم الماكرو. |
| [XLSB](#XLSB) | يمثل جدول بيانات Excel الثنائي (.xlsb)، وهو يحدد تنسيق ملف Excel الثنائي. |
| [CSV](#CSV) | يمثل ملف قيم مفصولة بفواصل (.csv)، وهو ملفات نصية عادية تحتوي على سجلات بيانات بقيم مفصولة بفواصل. |
| [TSV](#TSV) | يمثل ملف قيم مفصولة بجدولة (.tsv)، وهو بيانات مفصولة بعلامات جدولة في تنسيق نص عادي. |
| [ODS](#ODS) | يمثل جدول بيانات OpenDocument (.ods)، وهو اختصار لتنسيق مستند جدول بيانات OpenDocument القابل للتحرير من قبل المستخدم. |
| [FODS](#FODS) | يمثل جدول بيانات OpenDocument Flat XML (.fods). |
| [OTS](#OTS) | يمثل قالب جدول بيانات OpenDocument (.ots). |
| [XLAM](#XLAM) | يمثل إضافة Microsoft Excel (.xlam). |
| [XLTM](#XLTM) | يمثل قالب Microsoft Excel مع تمكين الماكرو (.xltm)، وهو ملفات تم إنشاؤها بواسطة Microsoft Excel كقوالب مُمكَّنة للماكرو. |
| [XLT](#XLT) | يمثل قالب Microsoft Excel (.xlt)، وهو ملفات قوالب تم إنشاؤها باستخدام Microsoft Excel، وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. |
| [XLTX](#XLTX) | يمثل قالب جدول بيانات Excel Open XML (.xltx)، وهو قوالب Microsoft Excel المستندة إلى مواصفات تنسيق ملف Office OpenXML. |
| [SXC](#SXC) | يمثل جدول بيانات StarOffice Calc (.sxc). |
| [MPP](#MPP) | يمثل ملف Microsoft Project (.mpp)، وهو ملف بيانات Microsoft Project يخزن معلومات متعلقة بإدارة المشاريع بطريقة متكاملة. |
| [MPT](#MPT) | يمثل قالب Microsoft Project (.mpt)، والذي يحتوي على معلومات أساسية وبنية بالإضافة إلى إعدادات المستند لإنشاء ملفات .MPP. |
| [MPX](#MPX) | يمثل ملف Microsoft Project Exchange (.mpx)، وهو تنسيق ملف ASCII لنقل معلومات المشروع بين Microsoft Project (MSP) وتطبيقات أخرى تدعم تنسيق MPX، مثل Primavera Project Planner وSciforma وTimerline Precision Estimating. |
| [AS](#AS) | يمثل ملف ActionScript (.as). |
| [AS_3](#AS-3) | يمثل ملف ActionScript (.as3). |
| [ASM](#ASM) | يمثل ملف شفرة مصدر بلغة التجميع (.asm). |
| [BAT](#BAT) | يمثل ملف دفعة DOS (.bat). |
| [C](#C) | يمثل ملف شفرة مصدر C/C++ (.c). |
| [CC](#CC) | يمثل ملف شفرة مصدر C++ (.cc). |
| [CMAKE](#CMAKE) | يمثل ملف CMake (.cmake). |
| [CPP](#CPP) | يمثل ملف شفرة مصدر C++ (.cpp). |
| [CS](#CS) | يمثل ملف شفرة مصدر C\# (.cs)، وهو ملف شفرة مصدر للغة البرمجة C\#. |
| [VB](#VB) | يمثل ملف عنصر مشروع Visual Basic (.vb)، وهو ملف شفرة مصدر تم إنشاؤه بلغة Visual Basic. |
| [CSS](#CSS) | يمثل ملف ورقة الأنماط المتتالية (.css). |
| [CXX](#CXX) | يمثل ملف شفرة مصدر C++ (.cxx). |
| [DIFF](#DIFF) | يمثل ملف تصحيح (.diff). |
| [ERB](#ERB) | يمثل سكريبت Ruby ERB (.erb). |
| [GROOVY](#GROOVY) | يمثل ملف شفرة مصدر Groovy (.groovy). |
| [H](#H) | يمثل ملف رأس C/C++/Objective-C (.h). |
| [HAML](#HAML) | يمثل ملف شفرة مصدر Haml (.haml). |
| [HH](#HH) | يمثل ملف رأس C++ (.hh). |
| [JAVA](#JAVA) | يمثل ملف شفرة مصدر Java (.java). |
| [JS](#JS) | يمثل ملف JavaScript (.js). |
| [JSON](#JSON) | يمثل ملف JavaScript Object Notation (.json). |
| [LESS](#LESS) | يمثل ملف ورقة أنماط LESS (.less). |
| [LOG](#LOG) | يمثل ملف سجل (.log). |
| [M](#M) | يمثل ملف تنفيذ Objective-C (.m). |
| [MAKE](#MAKE) | يمثل سكريبت Makefile Xcode (.make). |
| [MD](#MD) | يمثل ملف توثيق Markdown (.md). |
| [ML](#ML) | يمثل ملف شفرة مصدر ML (.ml). |
| [MM](#MM) | يمثل ملف مصدر Objective-C++ (.mm). |
| [PHP](#PHP) | يمثل ملف شفرة مصدر PHP (.php). |
| [PL](#PL) | يمثل سكريبت Perl (.pl). |
| [PROPERTIES](#PROPERTIES) | يمثل ملف خصائص Java (.properties). |
| [PY](#PY) | يمثل سكريبت Python (.py). |
| [RB](#RB) | يمثل ملف شفرة مصدر Ruby (.rb). |
| [RST](#RST) | يمثل ملف reStructuredText (.rst). |
| [SASS](#SASS) | يمثل ملف Syntactically Awesome StyleSheets (.sass). |
| [SCALA](#SCALA) | يمثل ملف شفرة مصدر Scala (.scala). |
| [SCM](#SCM) | يمثل ملف شفرة مصدر Scheme (.scm). |
| [SCRIPT](#SCRIPT) | يمثل ملف سكريبت عام (.script). |
| [SH](#SH) | يمثل سكريبت Bash Shell (.sh). |
| [SML](#SML) | يمثل ملف شفرة مصدر Standard ML (.sml). |
| [SQL](#SQL) | يمثل ملف بيانات Structured Query Language (.sql). |
| [VIM](#VIM) | يمثل ملف إعدادات Vim (.vim). |
| [YAML](#YAML) | يمثل مستند YAML (.yaml). |
| [DOC](#DOC) | يمثل ملف Microsoft Word (.doc). |
| [DOCX](#DOCX) | يمثل ملف Microsoft Word Open XML (.docx). |
| [CHM](#CHM) | يمثل ملف Microsoft Compiled HTML Help (.chm). |
| [DOCM](#DOCM) | يمثل مستند Word Open XML Macro-Enabled (.docm). |
| [DOT](#DOT) | يمثل قالب مستند Word (.dot). |
| [DOTX](#DOTX) | يمثل ملف قالب مستند Word Open XML (.dotx). |
| [DOTM](#DOTM) | يمثل ملف قالب مستند Word Open XML مع تمكين الماكرو (.dotm). |
| [RTF](#RTF) | يمثل ملف تنسيق النص الغني (.rtf). |
| [TXT](#TXT) | يمثل ملف نص عادي (.txt). |
| [ODT](#ODT) | يمثل مستند نص OpenDocument (.odt). |
| [OTT](#OTT) | يمثل قالب مستند OpenDocument (.ott). |
| [VCF](#VCF) | يمثل ملف vCard (.vcf)، وهو تنسيق ملف رقمي لتخزين معلومات الاتصال. |
| [AI](#AI) | يمثل ملف Adobe Illustrator (.ai)، وهو تنسيق ملف لرسومات Adobe Illustrator. |
| [PSM1](#PSM1) | يمثل ملف وحدة سكريبت PowerShell (.psm1). |
| [PS1](#PS1) | يمثل ملف سكريبت PowerShell (.ps1). |
| [PSD1](#PSD1) | يمثل ملف بيان وحدة سكريبت PowerShell (.psd1). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | يربط امتداد الملف بنوع الملف. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | يستخرج امتداد الملف من اسم الملف أو مسار الملف ويربطه بنوع الملف. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | يربط نوع وسائط الملف بنوع الملف. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | يكشف عن نوع الملف بقراءة توقيع الملف. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | يكشف عن نوع الملف بقراءة توقيع الملف. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | يكشف عن نوع الملف بقراءة توقيع الملف. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | يكشف عن نوع الملف بقراءة توقيع الملف. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | يسترجع أنواع الملفات المدعومة. |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | يحاول اكتشاف مجموعة أحرف ملفات النص [TXT](../../com.groupdocs.viewer/filetype\#TXT)، [TSV](../../com.groupdocs.viewer/filetype\#TSV) و[CSV](../../com.groupdocs.viewer/filetype\#CSV) حسب المسار. |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | يحاول اكتشاف مجموعة أحرف ملف النص [TXT](../../com.groupdocs.viewer/filetype\#TXT)، [TSV](../../com.groupdocs.viewer/filetype\#TSV) و[CSV](../../com.groupdocs.viewer/filetype\#CSV) حسب التدفق. |
| [getFileFormat()](#getFileFormat--) | يحصل على اسم تنسيق الملف، على سبيل المثال، "Microsoft Word Document". |
| [getExtension()](#getExtension--) | يحصل على لاحقة امتداد الملف (بما في ذلك النقطة "."), على سبيل المثال، ".doc". |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا للكائن الحالي. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


يمثل نوع ملف غير معروف.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


يمثل ملف مضغوط (.zip) يمكنه احتواء ملف أو أكثر أو أدلة. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


يمثل أرشيف ملف Unix موحد (.tar) تم إنشاؤه لجمع ملف أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


يمثل ملف XZ (.xz) مضغوط باستخدام خوارزمية ضغط عالية النسبة تعتمد على خوارزمية LZMA. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


يمثل أرشيف ملف Unix موحد (.txz، .tar.xz) تم إنشاؤه لجمع ملف أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


يمثل أرشيف ملف Unix موحد (.txz، .tar.xz) تم إنشاؤه لجمع ملف أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


يمثل أرشيف ملف Unix موحد (.tgz، .tar.gz) تم إنشاؤه لجمع ملف أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


يمثل أرشيف ملف Unix موحد (.tgz، .tar.gz) تم إنشاؤه لجمع ملف أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


يمثل ملفًا مضغوطًا بتقنية Bzip2 (.bz2) تم إنشاؤه باستخدام طريقة الضغط المفتوحة المصدر BZIP2. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


يمثل ملف أرشيف روسيال (.rar) مضغوط تم إنشاؤه باستخدام طريقة الضغط RAR (WINRAR الإصدار 4). تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


يمثل ملفًا مضغوطًا بصيغة Gnu Zipped (.gz) تم إنشاؤه باستخدام تطبيق الضغط gzip. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


يمثل ملفًا مضغوطًا بصيغة Gnu Zipped (.gzip) تم تقديمه كأداة مجانية لاستبدال برنامج Compress المستخدم في أنظمة Unix. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


يمثل ملفًا بصيغة 7Zip (.7z, .7zip)، وهو أداة أرشفة مجانية مفتوحة المصدر تدعم ضغط LZMA وLZMA2. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio هو أداة أرشفة ملفات عامة وتنسيق الملف المرتبط بها. يتم تثبيتها أساسًا على أنظمة تشغيل الحواسيب الشبيهة بـ Unix. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ملف ZST هو ملف مضغوط يتم إنشاؤه باستخدام خوارزمية الضغط Zstandard (zstd). وهو ملف مضغوط يتم إنشاؤه بضغط غير فقدان للبيانات عبر الخوارزمية. يمكن استخدام ملفات ZST لضغط أنواع مختلفة من الملفات مثل قواعد البيانات، أنظمة الملفات، الشبكات، والألعاب. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


ملفات TZST (.tar.zst, .tzst) هي أرشيفات Zstandard (ZST)، والتي تحتوي داخليًا على أرشيف ملفات Unix موحد (Tar)، تم إنشاؤه بأداة تعتمد على Unix لجمع ملف واحد أو أكثر.

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


ملفات TZST (.tar.zst, .tzst) هي أرشيفات Zstandard (ZST)، والتي تحتوي داخليًا على أرشيف ملفات Unix موحد (Tar)، تم إنشاؤه بأداة تعتمد على Unix لجمع ملف واحد أو أكثر.

### ISO {#ISO}
```
public static final FileType ISO
```


صورة قرص بصري ISO هي ملف صورة أرشيف غير مضغوط يمثل محتويات البيانات الكاملة على قرص بصري مثل CD أو DVD، بناءً على معيار ISO-9660. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


LHA أو LZH هي أداة ضغط مجانية وتنسيق ملف مرتبط بها. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet (أو CAB) هو تنسيق ملف أرشيف لنظام Microsoft Windows. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


يمثل ملف تنسيق تبادل الرسومات (.dxf)، وهو تمثيل بيانات معلمة لملف رسم AutoCAD. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


يمثل ملف قاعدة بيانات رسومات AutoCAD (.dwg)، وهو ملفات ثنائية مملوكة تُستخدم لتخزين بيانات التصميم ثنائية وثلاثية الأبعاد. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


يمثل قالب رسم AutoCAD (.dwt)، وهو ملف قالب رسم AutoCAD يُستخدم كنقطة بداية لإنشاء رسومات يمكن حفظها كملفات DWG. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


يمثل ملف ستييريوليثوغرافي (.stl)، وهو تنسيق ملف قابل للتبادل يمثل هندسة سطح ثلاثية الأبعاد. يُستخدم عادةً في النمذجة السريعة، الطباعة ثلاثية الأبعاد، والتصنيع بمساعدة الحاسوب. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


يمثل ملف فئات الأساس الصناعي (.ifc)، وهو تنسيق ملف يضع معايير دولية لاستيراد وتصدير كائنات المباني وخصائصها. يتيح التوافق بين تطبيقات البرمجيات المختلفة. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


يمثل ملف تنسيق الويب للتصميم (.dwf)، وهو تنسيق ملف مضغوط لعرض أو مراجعة أو طباعة رسومات ثنائية أو ثلاثية الأبعاد. يحتوي على رسومات ونص كجزء من بيانات التصميم ويقلل حجم الملف بفضل الضغط. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


يمثل ملف تبادل Autodesk FBX (FilmBoX) (.fbx)، وهو تنسيق نموذج ثلاثي الأبعاد. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


يمثل ملف تنسيق الويب للتصميم XPS (.dwfx)، وهو تنسيق مضغوط لعرض أو مراجعة أو طباعة رسومات ثنائية أو ثلاثية الأبعاد كوثيقة XPS. يحتوي على رسومات ونص كجزء من بيانات التصميم ويقلل حجم الملف بفضل الضغط. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


يمثل ملف تصميم MicroStation (.dgn)، وهو رسومات تم إنشاؤها ودعمها بواسطة تطبيقات CAD مثل MicroStation وIntergraph Interactive Graphics Design System. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


يمثل ملف PLT (HPGL) (.plt)، وهو ملف رسام متجه تم تقديمه من قبل Autodesk, Inc. يحتوي على معلومات لملف CAD معين، وتُطبع جميع الصور باستخدام الخطوط بدلاً من النقاط، مما يضمن الدقة والضبط في الإنتاج. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


يمثل ملف Common File Format (.cf2). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


يمثل ملف Wavefront 3D Object (.obj)، وهو ملف صورة ثلاثية الأبعاد تم تقديمه من قبل Wavefront Technologies. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


يمثل ملف PLT (HPGL) (.hpg). وهو تنسيق ملف يُستخدم لملفات الرسام في لغة رسومات HP (HPGL). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


يمثل ملف Initial Graphics Exchange Specification (IGES) (.igs).

### VSD {#VSD}
```
public static final FileType VSD
```


يمثل ملف رسم Visio (.vsd)، وهي رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية وروابطها. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


يمثل ملف رسم Visio (.vsdx)، وهو تنسيق ملف Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. استبدل تنسيق الملف الثنائي (.VSD) المدعوم من الإصدارات السابقة من Microsoft Visio. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


يمثل ملف قالب Visio (.vss)، وهي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio 2007 والإصدارات الأقدم. توفر ملفات القوالب كائنات رسم يمكن تضمينها في رسم Visio بامتداد .VSD. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


يمثل ملف قالب Visio (.vssx)، وهي قوالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما بعده. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل الأشكال، والموصلات، ومخططات التدفق، وتخطيط الشبكات، ومخططات UML، إلخ. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


يمثل ملف رسم Visio مدعوم بالماكرو (.vsdm)، وهي ملفات رسم تم إنشاؤها باستخدام تطبيق Microsoft Visio وتدعم الماكرو. ملفات VSDM هي رسومات OPC/XML مشابهة لملفات VSDX، لكنها توفر أيضًا إمكانية تشغيل الماكرو عند فتح الملف. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


يمثل قالب رسم Visio (.vst)، وهي ملفات صورة متجهة تم إنشاؤها باستخدام Microsoft Visio. تعمل كقوالب لإنشاء ملفات أخرى وتحتوي على التخطيط والإعدادات الافتراضية المستخدمة لإنشاء رسومات Visio جديدة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


يمثل قالب رسم Visio (.vstx)، وهي ملفات قالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. توفر ملفات VSTX نقطة انطلاق لإنشاء رسومات Visio تُحفظ كملفات .VSDX، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


يمثل قالب رسم Visio مدعوم بالماكرو (.vstm)، وهي ملفات قالب تم إنشاؤها باستخدام Microsoft Visio وتدعم الماكرو. يمكن للملفات التي تُنشأ من قوالب VSTM تشغيل ماكرو تم تطويره بلغة Visual Basic for Applications (VBA). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


يمثل ملف قالب Visio مدعوم بالماكرو (.vssm)، وهي ملفات قوالب Microsoft Visio التي تدعم الماكرو. عند فتح ملف VSSM، يمكن تشغيل الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في المخطط. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


يمثل ملف قوالب Visio XML (.vsx)، وهو يشير إلى القوالب التي تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. تُحفظ ملفات VSX بتنسيق XML وكانت مدعومة حتى Visio 2013. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


يمثل ملف قالب Visio XML (.vtx)، وهو قالب رسم Microsoft Visio يُحفظ على القرص بتنسيق XML. يوفر القالب إعدادات أساسية لإنشاء ملفات Visio متعددة بنفس الإعدادات. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


يمثل رسم Visio ويب (.vdw)، وهو يحدد التدفقات والتخزينات المطلوبة لعرض رسم ويب. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


يمثل ملف Visio Drawing XML (.vdx)، والذي يمثل أي رسم أو مخطط تم إنشاؤه في Microsoft Visio ولكن تم حفظه بتنسيق XML بامتداد .VDX. يتم إنشاء ملف Visio Drawing XML في برنامج Visio الذي طورته Microsoft. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


يمثل ملف Open eBook (.epub)، وهو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. يدعم العديد من القارئات الإلكترونية وتطبيقات البرمجيات هذا التنسيق. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


يمثل كتاب Mobipocket الإلكتروني (.mobi)، وهو أحد أكثر تنسيقات ملفات الكتب الإلكترونية استخدامًا. يُعد هذا التنسيق تحسينًا لتنسيق OEB (Open Ebook Format) القديم وكان يُستخدم كتنسيق مملوك لتطبيق Mobipocket Reader. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


كتاب Amazon Kindle Format 8 (KF8) هو تنسيق ملف رقمي تم تطويره لأجهزة Amazon Kindle. يُعد هذا التنسيق تحسينًا لملفات AZW القديمة ويُستخدم على أجهزة Kindle Fire فقط مع توافق رجعي مع تنسيق الملف الأصلي أي MOBI و AZW. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


يمثل رسالة بريد Outlook (.msg)، وهو تنسيق ملف يستخدمه Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


يمثل رسالة بريد إلكتروني (.eml)، وهو يمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. يدعم تقريبًا جميع عملاء البريد هذا التنسيق بسبب توافقه مع معيار RFC-822 لتنسيق الرسائل على الإنترنت. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


يمثل رسالة Apple Mail (.emlx)، والتي تم تنفيذها وتطويرها من قبل Apple. يستخدم تطبيق Apple Mail تنسيق ملف EMLX لتصدير الرسائل الإلكترونية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


يمثل ملف Outlook Personal Information Store (.pst)، وهو يمثل ملفات تخزين معلومات Outlook الشخصية (المعروفة أيضًا باسم Personal Storage Table) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


يمثل ملف Outlook Offline Data (.ost)، وهو يمثل بيانات صندوق بريد المستخدم في وضع عدم الاتصال على جهاز محلي بعد التسجيل في خادم Exchange باستخدام Microsoft Outlook. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


يمثل ملف Tagged Image (.tif)، وهو يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. يمكنه وصف بيانات الصورة ذات المستوى الثنائي، والدرجات الرمادية، وألوان اللوحة، والألوان الكاملة في عدة فضاءات لونية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


يمثل تنسيق ملف Tagged Image (.tiff)، وهو يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. يمكنه وصف بيانات الصورة ذات المستوى الثنائي، والدرجات الرمادية، وألوان اللوحة، والألوان الكاملة في عدة فضاءات لونية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


يمثل صورة JPEG (.jpg)، وهو نوع من تنسيقات الصور يُحفظ باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، تمثل موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


يمثل صورة JPEG (.jpeg)، وهو نوع من تنسيقات الصور يُحفظ باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، تمثل موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


تنسيق تبادل ملفات JPEG (.jfif) هو صورة تم تطويرها لتبادل سريع بين المنصات. يستخدم هذا التنسيق ضغط JPEG. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


يمثل صورة Portable Network Graphic (.png)، وهو نوع من تنسيقات ملفات الصور النقطية يستخدم ضغطًا غير فقدان للبيانات. تم إنشاء هذا التنسيق كبديل لتنسيق Graphics Interchange Format (GIF) ولا يحتوي على قيود حقوق نشر. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


يمثل ملف تنسيق تبادل رسومي (.gif)، وهو نوع من الصور المضغوطة بشكل عالي. لكل صورة، عادةً يسمح GIF بما يصل إلى 8 بت لكل بكسل، ويسمح بما يصل إلى 256 لونًا عبر الصورة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


يمثل ملف رسومي محمول متحرك (.apng)، وهو امتداد لتنسيق PNG يدعم الرسوم المتحركة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


يمثل ملف صورة نقطية (.bmp)، يُستخدم لتخزين الصور الرقمية النقطية. هذه الصور مستقلة عن محول الرسومات وتُعرف أيضًا بتنسيق ملف الصورة النقطية المستقلة عن الجهاز (DIB). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


يمثل ملف أيقونة (.ico)، وهو نوع ملف صورة يُستخدم كأيقونة لتمثيل تطبيق على نظام Microsoft Windows. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


يمثل ملف Truevision TGA (TARGA)، يُستخدم لتخزين الصور الرقمية النقطية التي طورتها شركة TRUEVISION. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


يمثل ملف صورة أساسي JPEG 2000 (.jp2)، وهو نظام ترميز صور ومعيار ضغط صور متقدم. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


يمثل ملف صورة JPEG 2000 (.jpf). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


يمثل ملف صورة JPEG 2000 (.jpx). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


يمثل ملف صورة JPEG 2000 (.jpm). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


يمثل تدفق إدخال شفرة JPEG 2000 (.j2c). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


يمثل تدفق شفرة JPEG 2000 (.j2k)، وهو صورة مضغوطة باستخدام ضغط الموجة بدلاً من ضغط DCT. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


يمثل تدفق شفرة JPEG 2000 (.jpc). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


يمثل ملف JPEG-LS (JLS) (.jls). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


يمثل ملف صورة نقطية مستقلة عن الجهاز (.dib). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


يمثل ملف Windows Metafile (.wmf)، وهو ملف Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهية وكذلك النقطية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


يمثل ملف Windows Metafile مضغوط (.wmz)، وهو ملف Microsoft Windows Metafile (WMF) مضغوط بأرشيف GZIP لتخزين بيانات الصور المتجهية والنقطية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


يمثل ملف Enhanced Windows Metafile (.emf)، وهو يمثل صورًا رسومية مستقلة عن الجهاز. تتألف ملفات الميتا EMF من سجلات بطول متغير بترتيب زمني يمكنها عرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


يمثل ملف Enhanced Metafile مضغوط لنظام Windows (.emz)، وهو يمثل صورًا رسومية مستقلة عن الجهاز ومضغوطة بواسطة GZIP. تتألف ملفات الميتا EMF من سجلات بطول متغير بترتيب زمني يمكنها عرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


يمثل صورة WebP (.webp)، وهو تنسيق ملف صورة نقطية حديث للويب يعتمد على الضغط غير الفاقد والفقدان. يوفر نفس جودة الصورة مع تقليل الحجم بشكل كبير. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


يمثل مواصفة Digital Negative (.dng)، وهو تنسيق صورة كاميرا رقمية يُستخدم لتخزين ملفات RAW. تم تطويره بواسطة Adobe في سبتمبر 2004 ويُستخدم أساسًا في التصوير الفوتوغرافي الرقمي. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


يمثل رسمًا متجهيًا CorelDraw (.cdr)، وهو ملف صورة رسم متجه تم إنشاؤه أصلاً باستخدام CorelDRAW لتخزين الصور المشفرة رقمياً والمضغوطة. يحتوي ملف رسم CDR على نصوص وخطوط وأشكال وصور وألوان وتأثيرات لتمثيل محتوى الصورة بشكل متجهي. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


يمثل ملف Corel Exchange (.cmx)، وهو ملف صورة رسم قد يحتوي على رسومات متجهية وكذلك رسومات نقطية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


يمثل صورة DjVu (.djvu)، وهو تنسيق ملف رسومي مخصص للمستندات والكتب الممسوحة ضوئياً، خاصةً تلك التي تحتوي على مزيج من النصوص والرسومات والصور واللقطات الفوتوغرافية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


يمثل ملف تعريف رسومات الحاسوب (.cgm)، وهو تنسيق ملف ميتا مجاني، غير معتمد على منصة، ومعيار دولي لتخزين وتبادل الرسومات المتجهية (2D)، الرسومات النقطية، والنص. يستخدم CGM نهجًا كائنيًا ويوفر العديد من الوظائف لإنتاج الصور. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


يمثل مستند لغة أوامر الطابعة (.pcl). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


يمثل مستند Adobe Photoshop (.psd)، وهو تنسيق الملف الأصلي لبرنامج Adobe Photoshop المستخدم في تصميم وتطوير الرسومات. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


يمثل تنسيق مستند Photoshop كبير (.psb)، والذي يُستخدم في تصميم وتطوير الرسومات في Adobe Photoshop. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


يمثل صورة DICOM (.dcm)، وهي صورة رقمية تخزن المعلومات الطبية للمرضى مثل صور الرنين المغناطيسي (MRI)، والمسحات المقطعية (CT)، وصور الموجات فوق الصوتية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


يمثل ملف PostScript (.ps). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


يمثل ملف Encapsulated PostScript (.eps)، الذي يصف برنامج لغة Encapsulated PostScript الذي يحدد مظهر صفحة واحدة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


يمثل ملف رسومات OpenDocument (.odg)، والذي يُستخدم بواسطة تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


يمثل قالب XML مسطح ODF (.fodg)، والذي يُستخدم بواسطة تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


يمثل ملف رسومات متجهة قابلة للتوسع (.svg)، وهو ملف رسومات متجهة يستخدم تنسيق نصي مبني على XML لوصف مظهر الصورة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


يمثل ملف رسومات متجهة قابلة للتوسع مضغوط (.svgz)، وهو ملف رسومات متجهة يستخدم تنسيق نصي مبني على XML، مضغوط بواسطة GZIP، لوصف مظهر الصورة. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


يمثل قالب رسومات OpenDocument (.otg). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


يمثل ملف لغة توصيف النص الفائق (.htm)، وهو الامتداد الخاص بصفحات الويب التي تُنشأ للعرض في المتصفحات. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


يمثل ملف لغة توصيف النص الفائق (.html)، وهو الامتداد الخاص بصفحات الويب التي تُنشأ للعرض في المتصفحات. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


يمثل أرشيف ويب MHTML (.mht). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


يمثل قاعدة بيانات Lotus Notes (.nsf). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


يمثل ملف صندوق بريد البريد الإلكتروني (.mbox). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


يمثل ملف MIME HTML (.mhtml). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


يمثل ملف XML (.xml). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


يمثل مستند OneNote (.one) تم إنشاؤه بواسطة تطبيق Microsoft OneNote. يتيح لك OneNote جمع المعلومات باستخدام التطبيق كما لو كنت تستخدم دفتر مسوداتك لتدوين الملاحظات. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


يمثل ملف تنسيق المستندات القابلة للنقل (.pdf)، وهو نوع من المستندات أنشأته شركة Adobe في التسعينيات. كان هدف هذا التنسيق تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى في صيغة مستقلة عن برامج التطبيقات، الأجهزة، وأنظمة التشغيل. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


يمثل ملف مواصفات ورق XML (.xps)، وهو يمثل ملفات تخطيط الصفحات المستندة إلى مواصفات ورق XML التي أنشأتها مايكروسوفت. تم تطوير هذا التنسيق بواسطة مايكروسوفت كبديل لتنسيق ملف EMF وهو مشابه لتنسيق ملف PDF، لكنه يستخدم XML في تخطيط ومظهر ومعلومات الطباعة للمستند. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


يمثل ملف OpenXPS (.oxps). تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


يمثل مستند مصدر LaTeX (.tex)، وهو لغة تشمل البرمجة بالإضافة إلى ميزات الترميز المستخدمة لتنسيق المستندات. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


يمثل عرض PowerPoint (.ppt)، وهو ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض شرائح. يحدد تنسيق الملف الثنائي المستخدم من قبل Microsoft PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


يمثل عرض PowerPoint Open XML (.pptx)، وهي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس النسخة السابقة من تنسيق ملف العرض PPT الذي كان ثنائيًا، يعتمد تنسيق PPTX على تنسيق ملف عرض Microsoft PowerPoint Open XML. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


يمثل عرض شرائح PowerPoint (.pps)، والذي يتم إنشاؤه باستخدام Microsoft PowerPoint لأغراض عرض الشرائح. يدعم Microsoft PowerPoint 97-2003 قراءة وإنشاء ملفات PPS. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


يمثل عرض شرائح PowerPoint Open XML (.ppsx)، وهي ملفات تُنشأ باستخدام Microsoft PowerPoint 2007 وما فوق لأغراض عرض الشرائح. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


يمثل عرض OpenDocument (.odp)، وهو تنسيق ملف عرض يستخدمه OpenOffice.org في معيار OASISOpen. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


يمثل عرض OpenDocument (.fodp)، وهو عرض OpenDocument Flat XML. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


يمثل قالب PowerPoint (.pot)، وهو ملفات قالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


يمثل عرض PowerPoint Open XML مع تمكين الماكرو (.pptm)، وهو ملفات عرض مفعلة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


يمثل قالب عرض PowerPoint Open XML (.potx)، وهو عروض قالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


يمثل قالب عرض PowerPoint Open XML مع تمكين الماكرو (.potm)، وهو ملفات قالب Microsoft PowerPoint التي تدعم الماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو أحدث وتحتوي على إعدادات افتراضية يمكن استخدامها لإنشاء ملفات عرض إضافية. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


يمثل شريحة PowerPoint Open XML مع تمكين الماكرو (.ppsm)، وهو تنسيق ملف عرض شرائح مفعّل بالماكرو تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أعلى. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


يمثل قالب عرض OpenDocument (.otp)، وهو ملفات قالب عرض تم إنشاؤها بواسطة التطبيقات في تنسيق معيار OASIS OpenDocument. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


يمثل جدول بيانات Excel (.xls)، وهو تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج جداول البيانات المماثلة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


يمثل Excel 2003 XML (SpreadsheetML) (.xml)، وهو تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج جداول البيانات المماثلة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول هذا التنسيق [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


يمثل Apple Numbers (.numbers)، وهو يمثل تنسيق ملف ثنائي شبيه بـ Excel. يمكن إنشاء مثل هذه الملفات بواسطة تطبيق Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


يمثل Microsoft Excel Open XML Spreadsheet (.xlsx)، وهو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


يمثل Excel Open XML Macro-Enabled Spreadsheet (.xlsm)، وهو نوع من ملفات الجداول يدعم الماكرو. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


يمثل Excel Binary Spreadsheet (.xlsb)، الذي يحدد تنسيق ملف Excel الثنائي. وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


يمثل ملف القيم المفصولة بفواصل (.csv)، وهو يمثل ملفات نصية عادية تحتوي على سجلات بيانات ذات قيم مفصولة بفواصل. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


يمثل ملف القيم المفصولة بعلامات جدولة (.tsv)، وهو يمثل بيانات مفصولة بعلامات جدولة في تنسيق نص عادي. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


يمثل OpenDocument Spreadsheet (.ods)، وهو اختصار لتنسيق مستند جدول OpenDocument القابل للتحرير من قبل المستخدم. يتم تخزين البيانات داخل ملفات ODF في صفوف وأعمدة. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


يمثل OpenDocument Flat XML Spreadsheet (.fods). وهو تنسيق مستند جدول يعتمد على XML يُستخدم في OpenOffice وLibreOffice. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


يمثل OpenDocument Spreadsheet Template (.ots). وهو تنسيق مستند قالب يُستخدم في OpenOffice وLibreOffice للجداول. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


يمثل Microsoft Excel Add-in (.xlam). وهو تنسيق ملف يستخدمه Microsoft Excel لإنشاء إضافات بوظائف مخصصة. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


يمثل Microsoft Excel Macro-Enabled Template (.xltm)، وهو يمثل ملفات تُنشئها Microsoft Excel كقوالب مُمكّنة للماكرو. ملفات XLTM مشابهة لملفات XLTX في البنية باستثناء أن الأخيرة لا تدعم إنشاء قوالب بملفات ماكرو. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


يمثل Microsoft Excel Template (.xlt)، وهي ملفات قالب تم إنشاؤها باستخدام Microsoft Excel، وهو تطبيق جدول يمتد ضمن مجموعة Microsoft Office. كان Microsoft Office 97-2003 يدعم إنشاء ملفات XLT جديدة وكذلك فتحها. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


يمثل Excel Open XML Spreadsheet Template (.xltx)، وهو يمثل قوالب Microsoft Excel المستندة إلى مواصفات تنسيق ملف Office OpenXML. يُستخدم لإنشاء ملف قالب قياسي يمكن الاستفادة منه لإنشاء ملفات XLSX بنفس الإعدادات المحددة في ملف XLTX. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


يمثل StarOffice Calc Spreadsheet (.sxc). وهو مستند جدول تم إنشاؤه باستخدام StarOffice Calc، وهو برنامج جدول. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


يمثل Microsoft Project File (.mpp)، وهو ملف بيانات Microsoft Project يخزن معلومات متعلقة بإدارة المشاريع بطريقة متكاملة. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


يمثل Microsoft Project Template (.mpt)، والذي يحتوي على معلومات أساسية وبنية بالإضافة إلى إعدادات المستند لإنشاء ملفات .MPP. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


يمثل Microsoft Project Exchange file (.mpx)، وهو تنسيق ملف ASCII لنقل معلومات المشروع بين Microsoft Project (MSP) وتطبيقات أخرى تدعم تنسيق ملف MPX، مثل Primavera Project Planner وSciforma وTimerline Precision Estimating. تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


يمثل ملف ActionScript (.as). تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


يمثل ملف ActionScript (.as3). تعرف على المزيد حول تنسيق الملف هذا [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


يمثل ملف مصدر بلغة التجميع (.asm). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


يمثل ملف دفعة DOS (.bat). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


يمثل ملف مصدر C/C++ (.c). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


يمثل ملف مصدر C++ (.cc). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


يمثل ملف CMake (.cmake). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


يمثل ملف مصدر C++ (.cpp). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


يمثل ملف مصدر C\# (.cs)، وهو ملف مصدر للغة البرمجة C\#. تم تقديمه من قبل Microsoft للاستخدام مع إطار عمل .NET. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


يمثل ملف عنصر مشروع Visual Basic (.vb)، وهو ملف مصدر تم إنشاؤه بلغة Visual Basic. تم إنشاؤه من قبل Microsoft لتطوير تطبيقات .NET. تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


يمثل ملف ورقة أنماط متتالية (.css). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


يمثل ملف مصدر C++ (.cxx). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


يمثل ملف تصحيح (.diff). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


يمثل سكريبت Ruby ERB (.erb). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


يمثل ملف مصدر Groovy (.groovy). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


يمثل ملف رأس C/C++/Objective-C (.h). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


يمثل ملف مصدر Haml (.haml). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


يمثل ملف رأس C++ (.hh). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


يمثل ملف مصدر Java (.java). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


يمثل ملف JavaScript (.js). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


يمثل ملف JavaScript Object Notation (.json). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


يمثل ملف ورقة أنماط LESS (.less). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


يمثل ملف سجل (.log). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


يمثل ملف تنفيذ Objective-C (.m). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


يمثل سكريبت Xcode Makefile (.make). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


يمثل ملف توثيق Markdown (.md). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


يمثل ملف مصدر ML (.ml). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


يمثل ملف مصدر Objective-C++ (.mm). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


يمثل ملف مصدر PHP (.php). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


يمثل سكريبت Perl (.pl). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


يمثل ملف خصائص Java (.properties). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


يمثل سكريبت Python (.py). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


يمثل ملف مصدر Ruby (.rb). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


يمثل ملف reStructuredText (.rst). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


يمثل ملف Syntactically Awesome StyleSheets (.sass). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


يمثل ملف مصدر Scala (.scala). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


يمثل ملف مصدر Scheme (.scm). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


يمثل ملف سكريبت عام (.script). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


يمثل سكريبت Bash Shell (.sh). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


يمثل ملف مصدر Standard ML (.sml). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


يمثل ملف بيانات Structured Query Language (.sql). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


يمثل ملف إعدادات Vim (.vim). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


يمثل مستند YAML (.yaml). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


يمثل مستند Microsoft Word (.doc). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


يمثل مستند Microsoft Word Open XML (.docx). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


يمثل ملف مساعدة HTML المدمج من Microsoft (.chm). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


يمثل مستند Word Open XML مع تمكين الماكرو (.docm). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


يمثل قالب مستند Word (.dot). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


يمثل قالب مستند Word Open XML (.dotx). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


يمثل قالب مستند Word Open XML مع تمكين الماكرو (.dotm). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


يمثل ملف Rich Text Format (.rtf). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


يمثل ملف نص عادي (.txt). تعرف على المزيد حول تنسيق هذا الملف [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


يمثل مستند نص OpenDocument (.odt). تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


يمثل قالب مستند OpenDocument (.ott). هو مستند قالب تم إنشاؤه وفقًا لتنسيق معيار OpenDocument الخاص بـ OASIS. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


يمثل ملف vCard (.vcf)، وهو تنسيق ملف رقمي لتخزين معلومات الاتصال. يُستخدم على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشهيرة. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


يمثل ملف Adobe Illustrator (.ai)، وهو تنسيق ملف لرسومات Adobe Illustrator. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


يمثل ملف وحدة سكريبت PowerShell (.psm1). هو تنسيق ملف لسكريبتات وحدات PowerShell. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


يمثل ملف سكريبت PowerShell (.ps1). هو تنسيق ملف لملفات Cmdlet الخاصة بـ Windows PowerShell. تعرف على المزيد حول هذا التنسيق [هنا][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


يمثل ملف بيان وحدة سكريبت PowerShell (.psd1). هو تنسيق ملف لسكريبتات بيان وحدة PowerShell. تعرف على المزيد حول هذا التنسيق [هنا][].


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
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


يربط امتداد الملف بنوع الملف.

تأخذ هذه الطريقة امتداد ملف، مع أو بدون النقطة "."، وتعيد نوع الملف المقابل إذا كان مدعومًا. إذا لم يكن نوع الملف مدعومًا، فإنها تُعيد نوع الملف الافتراضي [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الامتداد | java.lang.String | امتداد الملف مع أو بدون النقطة ".". |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


يستخرج امتداد الملف من اسم الملف أو مسار الملف ويربطه بنوع الملف.

إذا كان نوع الملف مدعومًا، تُعيد الطريقة نوع FileType المقابل، وإلا تُعيد نوع الملف الافتراضي [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | اسم الملف أو مسار الملف. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


يقوم بربط نوع وسائط الملف بنوع الملف. على سبيل المثال، سيتم ربط 'application/pdf' بـ [PDF](../../com.groupdocs.viewer/filetype\#PDF).

تأخذ هذه الطريقة نوع وسائط الملف كمدخل وتربطه بنوع FileType المقابل. إذا كان نوع الوسائط مدعومًا، تُعيد الطريقة نوع الملف المقابل. إذا لم يكن نوع الوسائط مدعومًا، فإنها تُعيد نوع الملف الافتراضي [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mediaType | java.lang.String | نوع وسائط الملف، مثال: 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


يكشف عن نوع الملف بقراءة توقيع الملف.

تأخذ هذه الطريقة تدفق إدخال يمثل ملفًا وتحاول اكتشاف نوع الملف عن طريق تحليل توقيع الملف. توقيع الملف هو تسلسل فريد من البايتات في بداية الملف يحدد نوعه. تقوم الطريقة بقراءة توقيع الملف من تدفق الإدخال ومقارنته بتواقيع الملفات المعروفة للأنواع المدعومة. إذا تم العثور على تطابق، تُعيد الطريقة نوع الملف المقابل. إذا لم يُعثر على أي تطابق، تُعيد نوع الملف الافتراضي [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال الذي يمثل الملف. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


يكشف عن نوع الملف بقراءة توقيع الملف.

تحلل هذه الطريقة توقيع الملف، وهو تسلسل فريد من البايتات في بداية الملف، لتحديد نوع الملف. تقرأ توقيع الملف من تدفق الإدخال المقدم وتقارنها بتواقيع الملفات المعروفة للأنواع المدعومة. إذا تم العثور على تطابق، تُعيد الطريقة نوع الملف المقابل. إذا لم يُعثر على أي تطابق، تُعيد نوع الملف الافتراضي [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

إذا كان الملف مشفرًا ويتطلب كلمة مرور للفتح، يجب تمرير كلمة المرور كمعامل لهذه الطريقة. ستُستخدم كلمة المرور لفك تشفير الملف وتحليل توقيعه لتحديد نوع الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال الذي يمثل الملف. |
| password | java.lang.String | كلمة المرور لفتح الملف. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


يكشف عن نوع الملف بقراءة توقيع الملف.

تحلل هذه الطريقة توقيع الملف، وهو تسلسل فريد من البايتات في بداية الملف، لتحديد نوع الملف. تقرأ توقيع الملف من تدفق الإدخال المقدم وتقارنها بتواقيع الملفات المعروفة للأنواع المدعومة. إذا تم العثور على تطابق، تُعيد الطريقة نوع الملف المقابل. إذا لم يُعثر على أي تطابق، تُعيد نوع الملف الافتراضي [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

يمكن توفير مسجل (logger) لتسجيل أي معلومات ذات صلة أو أخطاء أثناء عملية اكتشاف نوع الملف. يجب أن ينفذ المسجل واجهة ILogger. إذا لم يتم توفير مسجل، فلن ينتج عن عملية الاكتشاف أي مخرجات سجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال الذي يمثل الملف. |
| logger | com.groupdocs.foundation.logging.ILogger | المسجل لتسجيل المعلومات أو الأخطاء. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


يكشف عن نوع الملف بقراءة توقيع الملف.

تحلل هذه الطريقة توقيع الملف، وهو تسلسل فريد من البايتات في بداية الملف، لتحديد نوع الملف. تقرأ توقيع الملف من تدفق الإدخال المقدم وتقارنها بتواقيع الملفات المعروفة للأنواع المدعومة. إذا تم العثور على تطابق، تُعيد الطريقة نوع الملف المقابل. إذا لم يُعثر على أي تطابق، تُعيد نوع الملف الافتراضي [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

يمكن توفير كلمة مرور إذا كان الملف مشفرًا أو محميًا. سيتم استخدام كلمة المرور لفتح الملف قبل تحليل توقيع الملف. إذا لم يتطلب الملف كلمة مرور، يمكن تعيين هذه المعلمة إلى null.

يمكن توفير مسجل (logger) لتسجيل أي معلومات ذات صلة أو أخطاء أثناء عملية اكتشاف نوع الملف. يجب أن ينفذ المسجل واجهة ILogger. إذا لم يتم توفير مسجل، فلن ينتج عن عملية الاكتشاف أي مخرجات سجل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال الذي يمثل الملف. |
| password | java.lang.String | كلمة المرور لفتح الملف. |
| logger | com.groupdocs.foundation.logging.ILogger | المسجل لتسجيل المعلومات أو الأخطاء. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


يسترجع أنواع الملفات المدعومة.

تعيد هذه الطريقة تسلسلًا لجميع أنواع الملفات المدعومة من قبل النظام. تمثل أنواع الملفات صيغ المستندات المختلفة التي يمكن معالجتها أو التعرف عليها بواسطة النظام.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - تسلسل لأنواع الملفات المدعومة.
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


يحاول اكتشاف مجموعة أحرف ملفات النص [TXT](../../com.groupdocs.viewer/filetype\#TXT)، [TSV](../../com.groupdocs.viewer/filetype\#TSV) و[CSV](../../com.groupdocs.viewer/filetype\#CSV) حسب المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | اسم الملف أو مسار الملف. |

**Returns:**
java.nio.charset.Charset - مجموعة الأحرف أو null عند فشل اكتشاف مجموعة أحرف الملف.

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


يحاول اكتشاف مجموعة أحرف ملف النص [TXT](../../com.groupdocs.viewer/filetype\#TXT)، [TSV](../../com.groupdocs.viewer/filetype\#TSV) و[CSV](../../com.groupdocs.viewer/filetype\#CSV) حسب التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | دفق الملف. |

**Returns:**
java.nio.charset.Charset - مجموعة الأحرف أو null عند فشل اكتشاف مجموعة أحرف الملف.

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


يحصل على اسم تنسيق الملف، على سبيل المثال، "Microsoft Word Document".

**Returns:**
java.lang.String - اسم صيغة الملف.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


يحصل على لاحقة امتداد الملف (بما في ذلك النقطة "."), على سبيل المثال، ".doc".

**Returns:**
java.lang.String - لاحقة امتداد الملف.
### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا للكائن الحالي.

**Returns:**
java.lang.String - تمثيل نصي للكائن الحالي.
