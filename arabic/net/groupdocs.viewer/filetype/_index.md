---
title: FileType
second_title: GroupDocs.Viewer لمرجع .NET API
description: يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات التي يدعمهاعارض GroupDocs. .
type: docs
weight: 70
url: /ar/net/groupdocs.viewer/filetype/
---
## FileType class

يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات التي يدعمها**عارض GroupDocs.** .

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; } | لاحقة اسم الملف (بما في ذلك النقطة ".") مثل ".doc" . |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; } | اسم نوع الملف ، مثل "مستند Microsoft Word". |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | امتداد ملف الخرائط لنوع الملف. |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | استخراج امتداد الملف وتعيينه إلى نوع الملف. |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | نوع وسائط ملف الخرائط إلى نوع الملف ، على سبيل المثال ، سيتم تعيين "application / pdf" إلى[`PDF`](./pdf) . |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | يكتشف نوع الملف من خلال قراءة توقيع الملف. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | يكتشف نوع الملف من خلال قراءة توقيع الملف. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | يكتشف نوع الملف من خلال قراءة توقيع الملف. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | يكتشف نوع الملف من خلال قراءة توقيع الملف. |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | يحدد ما إذا كان التيار[`FileType`](../filetype)هو نفسه كما هو محدد[`FileType`](../filetype) الكائن . |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | يحدد ما إذا كان التيار[`FileType`](../filetype) هو نفس الكائن المحدد. |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | إرجاع كود التجزئة الحالي[`FileType`](../filetype) الكائن . |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | استرداد أنواع الملفات المدعومة |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | تحديد ما إذا كان اثنان[`FileType`](../filetype) الكائنات هي نفسها. |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | تحديد ما إذا كان اثنان[`FileType`](../filetype) الكائنات ليست هي نفسها. |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [AI](../../groupdocs.viewer/filetype/ai) | Adobe Illustrator (.ai) هو تنسيق ملف لرسومات Adobe Illustrator . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/ai#adobe_illustrator_file) . |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | Animated Portable Network Graphic (.apng) هو امتداد لتنسيق PNG يدعم الرسوم المتحركة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/apng) . |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | ملف ActionScript (.as) |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | ملف ActionScript (.as) |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | ملف رمز مصدر لغة التجميع (.asm) |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | ملف دفعي DOS (.bat) |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | ملف الصورة النقطية (.bmp) يُستخدم لتخزين الصور الرقمية للصور النقطية. هذه الصور مستقلة عن محول الرسومات وتسمى أيضًا تنسيق ملف الصورة النقطية المستقلة عن الجهاز (DIB) . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/bmp) . |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | الملف المضغوط Bzip2 (.bz2) عبارة عن ملفات مضغوطة تم إنشاؤها باستخدام طريقة ضغط المصدر المفتوح BZIP2 ، ومعظمها على نظام UNIX أو Linux. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/compression/bz2) . |
| static readonly [C](../../groupdocs.viewer/filetype/c) | ملف التعليمات البرمجية المصدر C / C ++ (.c) |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | ملف التعليمات البرمجية المصدر C ++ (.cc) |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) هو ملف صورة رسم متجه تم إنشاؤه أصلاً باستخدام CorelDRAW لتخزين الصور الرقمية المشفرة والمضغوطة. يحتوي ملف الرسم هذا على نص وخطوط وأشكال وصور وألوان وتأثيرات للتمثيل المتجه لمحتويات الصورة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | ملف تنسيق الملف العام تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/cf2) . |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | Computer Graphics Metafile (.cgm) هو تنسيق ملف تعريف قياسي دولي مجاني ومستقل عن النظام الأساسي لتخزين وتبادل الرسومات المتجهة (2D) والرسومات النقطية والنص. يستخدم CGM نهجًا موجهًا للكائنات والعديد من أحكام الوظائف لإنتاج الصور. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft Compiled HTML Help File (.chm) هو تنسيق معروف لمستندات HELP (وثائق بعض التطبيقات) . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/web/chm/) . |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | ملف CMake (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx) هو ملف صورة رسم قد يحتوي على رسومات متجهة بالإضافة إلى رسومات نقطية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/cmx) . |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | ملف التعليمات البرمجية المصدر C ++ (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C # Source Code File (.cs) هو ملف شفرة مصدر للغة البرمجة C #. مقدمة من Microsoft للاستخدام مع .NET Framework . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/programming/cs) . |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | ورقة الأنماط المتتالية (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | يمثل ملف القيم المفصولة بفواصل (.csv) ملفات نصية عادية تحتوي على سجلات بيانات بقيم مفصولة بفواصل . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | ملف التعليمات البرمجية المصدر C ++ (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | صورة DICOM (.dcm) تمثل الصورة الرقمية التي تخزن المعلومات الطبية للمرضى مثل التصوير بالرنين المغناطيسي والأشعة المقطعية وصور الموجات فوق الصوتية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | ملف تصميم MicroStation (.dgn) عبارة عن رسومات تم إنشاؤها بواسطة تطبيقات CAD ودعمها مثل MicroStation و Intergraph Interactive Graphics Design System. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | ملف الصور النقطية المستقل عن الجهاز (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | ملف التصحيح (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu Image (.djvu) هو تنسيق ملف رسومي مخصص للمستندات والكتب الممسوحة ضوئيًا وخاصة تلك التي تحتوي على مجموعة من النصوص والرسومات والصور والصور الفوتوغرافية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | المواصفات السلبية الرقمية (.dng) هي تنسيق صورة كاميرا رقمية يُستخدم لتخزين الملفات الأولية. تم تطويره بواسطة Adobe في سبتمبر 2004. تم تطويره بشكل أساسي للتصوير الرقمي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/dng) . |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | يمثل مستند Microsoft Word (.doc) المستندات التي تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة النصوص الأخرى بتنسيق ملف ثنائي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | مستند Word Open XML Macro-Enabled (.docm) هو مستند Microsoft Word 2007 أو إصدار أحدث مع إمكانية تشغيل وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML Document (.docx) هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه من عام 2007 مع إصدار Microsoft Office 2007 ، تم تغيير هيكل تنسيق المستند الجديد هذا من ثنائي عادي إلى مجموعة من ملفات XML والملفات الثنائية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | قالب مستند Word (.dot) عبارة عن ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات مهيأة مسبقًا لإنشاء ملفات DOC أو DOCX أخرى. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | قالب مستند Word Open XML ممكّن بماكرو (.dotm) يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML Document Template (.dotx) عبارة عن ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات منسقة مسبقًا لإنشاء ملفات DOCX أخرى. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | يمثل Design Web Format File (.dwf) رسمًا ثنائي الأبعاد / ثلاثي الأبعاد بتنسيق مضغوط لعرض ملفات التصميم أو مراجعتها أو طباعتها. يحتوي على رسومات ونصوص كجزء من بيانات التصميم وتقليل حجم الملف بسبب تنسيقه المضغوط . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | ملف قاعدة بيانات رسم AutoCAD (.dwg) يمثل الملفات الثنائية الخاصة المستخدمة لاحتواء بيانات التصميم ثنائية وثلاثية الأبعاد. مثل DXF ، وهي ملفات ASCII ، تمثل DWG تنسيق الملف الثنائي لرسومات CAD (التصميم بمساعدة الكمبيوتر). تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | قالب رسم AutoCAD (.dwt) هو ملف قالب رسم AutoCAD يُستخدم كبداية لإنشاء رسومات يمكن حفظها كملفات DWG . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | ملف تنسيق تبادل الرسم (.dxf) هو تمثيل بيانات ذو علامات لملف رسم AutoCAD . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | يمثل ملف تعريف Windows المحسّن (.emf) الصور الرسومية على حدة. تتكون ملفات تعريف EMF من سجلات متغيرة الطول بترتيب زمني يمكن أن تعرض الصورة المخزنة بعد التحليل على أي جهاز إخراج . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/emf) . |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | رسالة البريد الإلكتروني (.eml) تمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook والتطبيقات الأخرى ذات الصلة. يدعم جميع عملاء البريد الإلكتروني تقريبًا تنسيق الملف هذا لتوافقه مع معيار تنسيق رسائل الإنترنت RFC-822. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/eml) . |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | تطبيق Apple Mail Message (.emlx) وتطويره بواسطة Apple. يستخدم تطبيق Apple Mail تنسيق ملف EMLX لتصدير رسائل البريد الإلكتروني . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/emlx) . |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | يمثل ملف Windows Metafile المضغوط المحسن (.emz) صورًا رسومية مضغوطة بواسطة جهاز GZIP بشكل مستقل. تتكون ملفات تعريف EMF من سجلات متغيرة الطول بترتيب زمني يمكن أن تعرض الصورة المخزنة بعد التحليل على أي جهاز إخراج . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/emz) . |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | يصف ملف Encapsulated PostScript (.eps) برنامج لغة Encapsulated PostScript يصف مظهر صفحة واحدة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | ملف الكتاب الإلكتروني المفتوح (.epub) هو تنسيق ملف كتاب إلكتروني يوفر تنسيقًا قياسيًا للنشر الرقمي للناشرين والمستهلكين. أصبح التنسيق شائعًا جدًا حتى الآن لدرجة أنه مدعوم من قبل العديد من برامج القراءة الإلكترونية وتطبيقات البرامج . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/ebook/epub) . |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | برنامج Ruby ERB النصي (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | يمثل Excel 2003 XML (SpreadsheetML) تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | يتم استخدام قالب ODF XML المسطح (.fodg) بواسطة تطبيق رسم Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/fodg) . |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument Presentation (.fodp) يمثل OpenDocument Flat XML Presentation . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/fodp) . |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | جدول بيانات XML مسطح OpenDocument (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | ملف تنسيق التبادل الرسومي (.gif) هو نوع من الصور شديدة الضغط. لكل صورة ، يسمح GIF عادةً بما يصل إلى 8 بت لكل بكسل وما يصل إلى 256 لونًا مسموح به عبر الصورة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/gif) . |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | ملف التعليمات البرمجية المصدر Groovy (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu Zipped File (.gz) هي ملفات مضغوطة تم إنشاؤها باستخدام تطبيق ضغط gzip. يمكن أن يحتوي على عدة ملفات مضغوطة ويستخدم بشكل شائع على أنظمة UNIX و Linux . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/compression/gz) . |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | تم تقديم ملف مضغوط Gnu (.gzip) كأداة مساعدة مجانية لاستبدال برنامج الضغط المستخدم في أنظمة Unix. يمكن فتح هذه الملفات واستخراجها باستخدام العديد من التطبيقات مثل WinZip المتوفر على كل من Windows و MacOS. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/compression/gz) . |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C / C ++ / Objective-C Header File (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | ملف شفرة مصدر Haml (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | ملف رأس C ++ (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | ملف لغة ترميز النص التشعبي (.htm) هو امتداد لصفحات الويب التي تم إنشاؤها للعرض في المستعرضات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/web/html) . |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | ملف لغة توصيف النص التشعبي (.html) هو امتداد لصفحات الويب التي تم إنشاؤها للعرض في المستعرضات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/web/html) . |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | Icon File (.ico) هي أنواع ملفات الصور المستخدمة كأيقونة لتمثيل تطبيق على Microsoft Windows . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/ico) . |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | ملف فئات مؤسسة الصناعة (.ifc) هو تنسيق ملف يحدد المعايير الدولية لاستيراد وتصدير كائنات البناء وخصائصها. يوفر تنسيق الملف هذا إمكانية التشغيل البيني بين تطبيقات البرامج المختلفة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | مواصفات تبادل الرسومات الأولية (IGES) (.igs) |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | دفق كود JPEG 2000 (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000 Code Stream (.j2k) هي صورة يتم ضغطها باستخدام ضغط الموجة بدلاً من ضغط DCT . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/j2k) . |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | ملف شفرة مصدر Java (.java) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000 Core Image File (.jp2) هو نظام ترميز للصور وأحدث معايير ضغط الصور. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jp2) . |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | دفق كود JPEG 2000 (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | صورة JPEG (.jpeg) هي نوع من تنسيق الصورة يتم حفظها باستخدام طريقة الضغط مع فقدان البيانات. الصورة الناتجة ، كنتيجة للضغط ، هي مقايضة بين حجم التخزين وجودة الصورة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | ملف صورة JPEG 2000 (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | صورة JPEG (.jpg) هي نوع من تنسيق الصورة يتم حفظها باستخدام طريقة الضغط مع فقدان البيانات. الصورة الناتجة ، كنتيجة للضغط ، هي مقايضة بين حجم التخزين وجودة الصورة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | ملف صورة JPEG 2000 (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | ملف صورة JPEG 2000 (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | ملف JavaScript (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | ملف JavaScript Object Notation File (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | ورقة أنماط أقل (.less) |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | ملف السجل (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | ملف تنفيذ Objective-C (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | البرنامج النصي Xcode Makefile (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | ملف صندوق بريد البريد الإلكتروني (.mbox) تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/mbox) . |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | ملف التوثيق Markdown (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | أرشيف ويب MHTML (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | ملف HTML MIME (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | ملف التعليمات البرمجية المصدر ML (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | ملف مصدر Objective-C ++ (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket eBook (.mobi) هو أحد أكثر تنسيقات ملفات الكتب الإلكترونية استخدامًا. يعد التنسيق تحسينًا للتنسيق القديم OEB (تنسيق Open Ebook) وقد تم استخدامه كتنسيق خاص لـ Mobipocket Reader . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | ملف Microsoft Project (.mpp) هو ملف بيانات Microsoft Project يقوم بتخزين المعلومات المتعلقة بإدارة المشروع بطريقة متكاملة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/project-management/mpp) . |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft Project Template (.mpt) يحتوي على معلومات أساسية وهيكل إلى جانب إعدادات المستند لإنشاء ملفات .MPP. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/project-management/mpt) . |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | ملف Microsoft Project Exchange (.mpx) هو تنسيق ملف ASCII لنقل معلومات المشروع بين Microsoft Project (MSP) والتطبيقات الأخرى التي تدعم تنسيق ملف MPX مثل Primavera Project Planner و Sciforma و Timerline Precision Estimating . تعرف على المزيد حول هذا تنسيق الملف[هنا](https://wiki.fileformat.com/project-management/mpx) . |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook Mail Message (.msg) هو تنسيق ملف يستخدمه Microsoft Outlook و Exchange لتخزين رسائل البريد الإلكتروني أو جهة الاتصال أو الموعد أو المهام الأخرى. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/msg) . |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | قاعدة بيانات Lotus Notes (.nsf) تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/nsf) . |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | تمثل أرقام Apple Excel مثل تنسيق الملف الثنائي. يمكن إنشاء مثل هذه الملفات عن طريق تطبيق أرقام Apple. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/numbers) . |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D Object File (.obj) هو ملف صور ثلاثي الأبعاد تم تقديمه بواسطة Wavefront Technologies تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/3d/obj/) . |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | ملف رسومي OpenDocument (.odg) يستخدم بواسطة تطبيق رسم Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument Presentation (.odp) يمثل تنسيق ملف العرض التقديمي المستخدم بواسطة OpenOffice.org في معيار OASISOpen . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | جدول بيانات OpenDocument (.ods) يرمز إلى تنسيق OpenDocument Spreadsheet Document الذي يمكن للمستخدم تحريره. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument Text Document (.odt) هو نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة الكلمات التي تعتمد على تنسيق OpenDocument Text File. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [ONE](../../groupdocs.viewer/filetype/one) | تم إنشاء مستند OneNote (.one) بواسطة تطبيق Microsoft OneNote. يتيح لك OneNote جمع المعلومات باستخدام التطبيق كما لو كنت تستخدم لوحة المسودة لتدوين الملاحظات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/note-taking/one) . |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | ملف بيانات Outlook Offline (.ost) يمثل بيانات صندوق بريد المستخدم في وضع عدم الاتصال على الجهاز المحلي عند التسجيل مع Exchange Server باستخدام Microsoft Outlook. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/ost) . |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | قالب رسومي OpenDocument (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | قالب العرض التقديمي OpenDocument (.otp) يمثل ملفات قالب العرض التقديمي التي تم إنشاؤها بواسطة تطبيقات بتنسيق OASIS OpenDocument القياسي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | قالب جدول بيانات OpenDocument (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | قالب مستند OpenDocument (.ott) يمثل مستندات نموذجية تم إنشاؤها بواسطة التطبيقات وفقًا للتنسيق القياسي OpenDocument الخاص بـ OASIS. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | ملف OpenXPS (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | مستند لغة أوامر الطابعة (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | ملف تنسيق المستند المحمول (.pdf) هو نوع من المستندات التي أنشأتها Adobe في التسعينيات. كان الغرض من تنسيق الملف هذا هو تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى بتنسيق مستقل عن برامج التطبيقات والأجهزة وكذلك نظام التشغيل. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | ملف التعليمات البرمجية المصدر PHP (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | نصوص Perl (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT (HPGL) (.plt) هو ملف رسام يعتمد على المتجهات مقدم من شركة Autodesk، Inc. ويحتوي على معلومات لملف CAD معين. تتطلب تفاصيل التخطيط الدقة والدقة في الإنتاج ، ويضمن استخدام ملف PLT ذلك حيث تتم طباعة جميع الصور باستخدام خطوط بدلاً من النقاط. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/plt) . |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | Portable Network Graphic (.png) هو نوع من تنسيق ملف الصورة النقطية الذي يستخدم ضغط بدون فقدان. تم إنشاء تنسيق الملف هذا كبديل لتنسيق تبادل الرسومات (GIF) وليس له قيود على حقوق النشر . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | قالب PowerPoint (.pot) يمثل ملفات قوالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | قالب العرض التقديمي لـ PowerPoint Open XML مع تمكين ماكرو (.potm) عبارة عن ملفات قالب Microsoft PowerPoint مع دعم لوحدات الماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو إصدار أحدث وتحتوي على الإعدادات الافتراضية التي يمكن استخدامها لإنشاء المزيد من ملفات العروض التقديمية . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) يمثل العروض التقديمية لقالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | يتم إنشاء عرض شرائح PowerPoint (.pps) باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يتم دعم قراءة ملف PPS وإنشائه بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) يمثل تنسيق ملف عرض الشرائح الذي تم تمكينه بماكرو والذي تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | يتم إنشاء ملفات PowerPoint Open XML Slide Show (.ppsx) باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث لغرض عرض الشرائح . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint Presentation (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح لعرضها على هيئة SlideShow. تحدد تنسيق الملف الثنائي المستخدم بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML Macro-Enable Presentation عبارة عن ملفات عروض تقديمية تم تمكين الماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) هي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس الإصدار السابق من تنسيق ملف العرض التقديمي PPT الذي كان ثنائيًا ، يعتمد تنسيق PPTX على تنسيق ملف العرض التقديمي XML المفتوح لبرنامج Microsoft PowerPoint. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | ملف خصائص Java (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | ملف PostScript (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | ملف البرنامج النصي PowerShell (.ps1) تنسيق ملف لملفات Windows PowerShell Cmdlet . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/ps1) . |
| static readonly [PSB](../../groupdocs.viewer/filetype/psb) | تنسيق Photoshop Large Document (.psb) يمثل تنسيق مستند Photoshop الكبير المستخدم لتصميم الرسومات وتطويرها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/psb) . |
| static readonly [PSD](../../groupdocs.viewer/filetype/psd) | يمثل Adobe Photoshop Document (.psd) تنسيق ملف Adobe Photoshop الأصلي المستخدم في تصميم الرسومات وتطويرها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/psd) . |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | بيان وحدة البرنامج النصي PowerShell (.psd1) تنسيق ملف للنصوص البرمجية لبيان وحدة PowerShell . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/psd1) . |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | وحدة البرنامج النصي PowerShell (.psm1) تنسيق ملف لبرامج نصية لوحدة PowerShell . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/psm1) . |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | ملف مخزن المعلومات الشخصية في Outlook (.pst) يمثل ملفات التخزين الشخصية لـ Outlook (تسمى أيضًا جدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/pst) . |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | نص بايثون (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive (.rar) هي ملفات مضغوطة تم إنشاؤها باستخدام طريقة ضغط RAR (WINRAR). تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/compression/rar) . |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | كود مصدر روبي (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | reStructuredText File (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | يمثل ملف Rich Text Format (.rtf) طريقة لترميز النص والرسومات المنسقة للاستخدام داخل التطبيقات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | ملف StyleSheets رائع نحويًا (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala Source Code File (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | ملف التعليمات البرمجية المصدر للنظام (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | ملف البرنامج النصي العام (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z، .7zip) هو أرشيفي مجاني مفتوح المصدر بضغط LZMA و LZMA2 . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://docs.fileformat.com/compression/7z/) . |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash Shell Script (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | ملف كود مصدر ML القياسي (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | ملف بيانات لغة الاستعلام المنظم (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | ملف الطباعة الحجرية المجسمة (.stl) هو تنسيق ملف قابل للتبديل يمثل هندسة السطح ثلاثية الأبعاد. يجد تنسيق الملف استخدامه في عدة مجالات مثل النماذج الأولية السريعة والطباعة ثلاثية الأبعاد والتصنيع بمساعدة الكمبيوتر . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/cad/stl) . |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | Scalable Vector Graphics File (.svg) هو ملف Scalar Vector Graphics يستخدم تنسيقًا نصيًا يستند إلى XML لوصف مظهر الصورة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | Scalable Vector Graphics File (.svgz) هو ملف Scalar Vector Graphics يستخدم تنسيق نص يعتمد على XML ، مضغوط بواسطة GZIP لوصف مظهر الصورة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/svgz) . |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | جدول بيانات StarOffice Calc (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | أرشيف ملفات Unix الموحدة (.tar) عبارة عن أرشيفات تم إنشاؤها باستخدام أداة تستند إلى Unix لتجميع ملف واحد أو أكثر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/compression/tar) . |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | أرشيف ملفات Unix الموحدة (.tgz ، .tar.gz) عبارة عن أرشيفات تم إنشاؤها باستخدام أداة تستند إلى Unix لتجميع ملف واحد أو أكثر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/tgz) . |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | أرشيف ملفات Unix الموحدة (.txz ، .tar.xz) عبارة عن أرشيفات تم إنشاؤها باستخدام أداة مساعدة تستند إلى Unix لتجميع ملف واحد أو أكثر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/txz) . |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | وثيقة مصدر LaTeX (.tex) هي لغة تتكون من ميزات البرمجة والترميز المستخدمة في طباعة المستندات. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/tex) . |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | يستخدم Truevision TGA (محول Truevision Advanced Raster - TARGA) لتخزين الصور الرقمية النقطية التي طورتها TRUEVISION. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/tga) . |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | أرشيف ملفات Unix الموحدة (.tgz ، .tar.gz) عبارة عن أرشيفات تم إنشاؤها باستخدام أداة تستند إلى Unix لتجميع ملف واحد أو أكثر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/tgz) . |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | ملف الصور ذي العلامات (.tif) يمثل الصور النقطية المخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار تنسيق الملف هذا. إنه قادر على وصف بيانات الصورة ذات المستوى الثنائي ، والرمادي ، واللون الملون ، وبيانات الصور كاملة الألوان في العديد من مساحات الألوان. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | تنسيق ملف الصورة ذي العلامات (.tiff) يمثل الصور النقطية المخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار تنسيق الملف هذا. إنه قادر على وصف بيانات الصورة ذات المستوى الثنائي ، والرمادي ، واللون الملون ، وبيانات الصور كاملة الألوان في العديد من مساحات الألوان. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | يمثل ملف القيم المفصولة بعلامات جدولة (.tsv) بيانات مفصولة بعلامات تبويب بتنسيق نص عادي. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | ملف نصي عادي (.txt) يمثل مستندًا نصيًا يحتوي على نص عادي في شكل أسطر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | أرشيف ملفات Unix الموحدة (.txz ، .tar.xz) عبارة عن أرشيفات تم إنشاؤها باستخدام أداة مساعدة تستند إلى Unix لتجميع ملف واحد أو أكثر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/txz) . |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | يمثل نوع ملف غير معروف. |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | ملف عنصر مشروع Visual Basic (.vb) هو ملف تعليمات برمجية مصدر تم إنشاؤه بلغة Visual Basic تم إنشاؤه بواسطة Microsoft لتطوير تطبيقات .NET . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/programming/vb) . |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | ملف vCard (.vcf) هو تنسيق ملف رقمي لتخزين معلومات جهات الاتصال. يستخدم التنسيق على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشائعة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/vcf) . |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | يمثل رسم ويب Visio (.vdw) تنسيق ملف يحدد التدفقات والمخازن المطلوبة لتقديم رسم ويب. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/web/vdw) . |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | يمثل ملف Visio Drawing XML (.vdx) أي رسم أو مخطط تم إنشاؤه في Microsoft Visio ، ولكن تم حفظه بتنسيق XML بامتداد .VDX. يتم إنشاء ملف Visio للرسم XML في برنامج Visio ، الذي تم تطويره بواسطة Microsoft . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vdx) . |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | ملف إعدادات Vim (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | ملف رسم Visio (.vsd) عبارة عن رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والترابط بينها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vsd) . |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | رسم Visio ممكّن بماكرو (.vsdm) عبارة عن ملفات رسم تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم وحدات الماكرو. ملفات VSDM هي رسومات OPC / XML تشبه VSDX ، ولكنها توفر أيضًا القدرة على تشغيل وحدات الماكرو عند فتح الملف. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | يمثل Visio Drawing (.vsdx) تنسيق ملف Microsoft Visio المقدم من Microsoft Office 2013 وما بعده. تم تطويره ليحل محل تنسيق الملف الثنائي ، .VSD ، الذي تدعمه الإصدارات السابقة من Microsoft Visio . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | ملف Visio Stencil File (.vss) عبارة عن ملفات استنسل تم إنشاؤها باستخدام Microsoft Visio 2007 والإصدارات الأقدم. توفر ملفات الاستنسل كائنات رسومية يمكن تضمينها في رسم .VSD Visio . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vss) . |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | ملف الاستنسل الممكّن بماكرو Visio (.vssm) هي ملفات Microsoft Visio Stencil التي تدعم توفير الدعم لوحدات الماكرو. يسمح ملف VSSM عند فتحه بتشغيل وحدات الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في رسم تخطيطي . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vssm) . |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | ملف استنسل Visio (.vssx) يرسم قوالب استنسل تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما فوق. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال والموصلات والمخططات الانسيابية وتخطيط الشبكة ومخططات UML و تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vssx) . |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio Drawing Template (.vst) عبارة عن ملفات صور متجهة تم إنشاؤها باستخدام Microsoft Visio وتعمل كقالب لإنشاء المزيد من الملفات. ملفات القوالب هذه بتنسيق ملف ثنائي وتحتوي على التخطيط والإعدادات الافتراضية المستخدمة لإنشاء رسومات Visio الجديدة . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vst) . |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | قالب الرسم الممكّن بماكرو Visio (.vstm) عبارة عن ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio التي تدعم وحدات الماكرو. بخلاف ملفات VSDX ، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل وحدات الماكرو التي تم تطويرها في التعليمات البرمجية لـ Visual Basic for Applications (VBA). تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vstm) . |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | قالب رسم Visio (.vstx) عبارة عن ملفات قالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. توفر ملفات VSTX هذه نقطة بداية لإنشاء رسومات Visio ، المحفوظة كملفات .VSDX ، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vstx) . |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | يشير ملف Visio Stencil XML (.vsx) إلى قوالب استنسل تتكون من رسومات وأشكال تُستخدم لإنشاء الرسوم التخطيطية في Microsoft Visio. يتم حفظ ملفات VSX بتنسيق ملف XML وتم دعمها حتى Visio 2013. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vsx) . |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio Template XML File (.vtx) هو قالب رسم Microsoft Visio يتم حفظه على قرص بتنسيق ملف XML. يهدف القالب إلى توفير ملف بالإعدادات الأساسية التي يمكن استخدامها لإنشاء ملفات Visio متعددة بنفس الإعدادات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vtx) . |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP Image (.webp) هو تنسيق ملف صورة ويب نقطية حديث يعتمد على ضغط بدون فقد أو فقدان البيانات. إنه يوفر نفس جودة الصورة مع تقليل حجم الصورة بشكل كبير. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | يمثل Windows Metafile (.wmf) Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهية وكذلك بصيغة الصور النقطية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | ملف تعريف Windows المضغوط (.wmz) يمثل Microsoft Windows Metafile (WMF) مضغوطًا في أرشيف GZIP - لتخزين بيانات الصور المتجهية وكذلك بصيغة الصور النقطية . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/wmz#compressed_windows_metafile) . |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | الوظيفة الإضافية لـ Microsoft Excel (.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | جدول بيانات Excel (.xls) يمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | يحدد جدول بيانات Excel الثنائي (.xlsb) تنسيق ملف Excel الثنائي ، وهو عبارة عن مجموعة من السجلات والهياكل التي تحدد محتوى مصنف Excel. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) هو نوع من ملفات Spreasheet التي تدعم وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه بواسطة Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | قالب Microsoft Excel (.xlt) عبارة عن ملفات قوالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة بالإضافة إلى فتحها. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | قالب تم تمكين الماكرو لـ Microsoft Excel (.xltm) يمثل الملفات التي تم إنشاؤها بواسطة Microsoft Excel كملفات قوالب ممكّنة بماكرو. تتشابه ملفات XLTM مع XLTX من حيث البنية بخلاف أن أحدثها لا يدعم إنشاء ملفات القوالب باستخدام وحدات الماكرو. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML Spreadsheet Template (xltx) يمثل قالب Microsoft Excel المستند إلى مواصفات تنسيق ملف Office OpenXML. يتم استخدامه لإنشاء ملف قالب قياسي يمكن استخدامه لإنشاء ملفات XLSX التي تعرض نفس الإعدادات المحددة في ملف XLTX . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | ملف XML (.xml) |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | ملف مواصفات ورق XML (.xps) يمثل ملفات تخطيط الصفحة التي تستند إلى مواصفات ورق XML التي أنشأتها Microsoft. تم تطوير هذا التنسيق بواسطة Microsoft كبديل لتنسيق ملف EMF وهو مشابه لتنسيق ملف PDF ، ولكنه يستخدم XML في معلومات التخطيط والمظهر والطباعة لمستند . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/page-description-language/xps) . |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | ملف XZ (.xz) هو أرشيف مضغوط عبارة عن خوارزمية ضغط عالية النسبة تعتمد على خوارزمية LZMA. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://fileinfo.com/extension/xz) . |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | مستند YAML (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | الملف المضغوط (.zip) يمثل أرشيفات يمكنها الاحتفاظ بملف أو مجلد واحد أو أكثر. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/compression/zip) . |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Viewer](../../groupdocs.viewer)
* المجسم [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
