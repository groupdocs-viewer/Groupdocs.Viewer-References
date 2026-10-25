---
title: "FileType"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل GroupDocs.Viewer."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer/filetype/
---

## FileType class

يمثل نوع الملف. يوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل **GroupDocs.Viewer**.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FileType](filetype#constructor)() | ينشئ نسخة جديدة من الفئة [`FileType`](../filetype). |
| [FileType](filetype#constructor_1)(string, string) | ينشئ نسخة جديدة من الفئة [`FileType`](../filetype). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; set; } | لاحقة اسم الملف (بما في ذلك النقطة ".") مثال: ".doc". |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; set; } | اسم نوع الملف مثال: "Microsoft Word Document". |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | يربط امتداد الملف بنوع الملف. |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | يستخرج امتداد الملف ويطابقه مع نوع الملف. |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | يُطابق نوع وسائط الملف مع نوع الملف، على سبيل المثال 'application/pdf' سيُطابق إلى [`PDF`](./pdf). |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | يكتشف نوع الملف بقراءة توقيع الملف. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | يكتشف نوع الملف بقراءة توقيع الملف. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | يكتشف نوع الملف بقراءة توقيع الملف. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | يكتشف نوع الملف بقراءة توقيع الملف. |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | يحدد ما إذا كان [`FileType`](../filetype) الحالي هو نفسه كائن [`FileType`](../filetype) المحدد. |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | يحدد ما إذا كان [`FileType`](../filetype) الحالي هو نفسه الكائن المحدد. |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | يعيد رمز التجزئة (hash code) للكائن [`FileType`](../filetype) الحالي. |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | يعيد سلسلة تمثل الكائن الحالي. |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding)(Stream) | يحاول اكتشاف ترميز ملفات النص [`TXT`](./txt)، [`TSV`](./tsv)، و[`CSV`](./csv) عبر التدفق. |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding_1)(string) | يحاول اكتشاف ترميز ملفات النص [`TXT`](./txt)، [`TSV`](./tsv)، و[`CSV`](./csv) عبر المسار. |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | يسترجع أنواع الملفات المدعومة |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | يحدد ما إذا كان كائني [`FileType`](../filetype) متطابقين. |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | يحدد ما إذا كان كائني [`FileType`](../filetype) غير متطابقين. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | Animated Portable Network Graphic (.apng) هو امتداد لتنسيق PNG يدعم الرسوم المتحركة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/apng). |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | ملف ActionScript (.as) |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | ملف ActionScript (.as) |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | ملف شفرة مصدر لغة التجميع (.asm) |
| static readonly [AZW3](../../groupdocs.viewer/filetype/azw3) | Amazon Kindle Format 8 (KF8) هو تنسيق ملف إلكتروني تم تطويره لأجهزة Amazon Kindle. هذا التنسيق يُحسّن ملفات AZW القديمة ويُستخدم على أجهزة Kindle Fire فقط مع توافق رجعي مع تنسيقات الملفات الأصلية مثل MOBI وAZW. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/ebook/azw3). |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | ملف دفعة DOS (.bat) |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | ملف صورة Bitmap (.bmp) يُستخدم لتخزين الصور الرقمية النقطية. هذه الصور مستقلة عن محول الرسومات وتُعرف أيضًا بتنسيق bitmap المستقل عن الجهاز (DIB). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/bmp). |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | ملف مضغوط Bzip2 (.bz2) هو ملف مضغوط يُنشأ باستخدام طريقة الضغط المفتوحة المصدر BZIP2، غالبًا على أنظمة UNIX أو Linux. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/compression/bz2). |
| static readonly [C](../../groupdocs.viewer/filetype/c) | ملف شفرة مصدر C/C++ (.c) |
| static readonly [Cab](../../groupdocs.viewer/filetype/cab) | Cabinet (أو CAB) هو تنسيق ملف أرشيف لنظام Microsoft Windows. تعرف على المزيد حول هذا التنسيق [هنا](https://en.wikipedia.org/wiki/Cabinet_(file_format)). |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | ملف شفرة مصدر C++ (.cc) |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw Vector Graphic Drawing (.cdr) هو ملف رسم صورة متجهة يُنشأ أصلاً باستخدام CorelDRAW لتخزين الصورة الرقمية المشفرة والمضغوطة. يحتوي هذا الملف على نصوص، خطوط، أشكال، صور، ألوان وتأثيرات لتمثيل محتوى الصورة بشكل متجهي. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/cdr). |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | ملف Common File Format. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/cf2). |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | Computer Graphics Metafile (.cgm) هو تنسيق ملف ميتا مجاني، مستقل عن المنصة، ومعيار دولي لتخزين وتبادل الرسومات المتجهة (2D)، الرسومات النقطية، والنص. يستخدم CGM نهجًا كائنيًا والعديد من الدوال لإنتاج الصور. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/cgm). |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft Compiled HTML Help File (.chm) هو تنسيق معروف لمستندات HELP (وثائق لتطبيق ما). تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/web/chm/). |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | ملف CMake (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx) هو ملف صورة رسم قد يحتوي على رسومات متجهة وكذلك رسومات نقطية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/cmx). |
| static readonly [CPIO](../../groupdocs.viewer/filetype/cpio) | Cpio هو أداة أرشفة ملفات عامة وتنسيق الملف المرتبط بها. يتم تثبيتها أساسًا على أنظمة تشغيل الحواسيب الشبيهة بـ Unix. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/compression/cpio). |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | ملف كود مصدر C++ (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | ملف كود مصدر C# (.cs) هو ملف كود مصدر للغة البرمجة C#. تم تقديمه من قبل Microsoft للاستخدام مع إطار عمل .NET. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/programming/cs). |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | ورقة الأنماط المتتالية (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | ملف القيم المفصولة بفواصل (.csv) يمثل ملفات نصية عادية تحتوي على سجلات بيانات بقيم مفصولة بفواصل. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | ملف كود مصدر C++ (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | صورة DICOM (.dcm) تمثل صورة رقمية تخزن معلومات طبية للمرضى مثل صور الرنين المغناطيسي (MRI)، والمسح المقطعي (CT) وصور الموجات فوق الصوتية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/dcm). |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | ملف تصميم MicroStation (.dgn) هو رسومات تم إنشاؤها ودعمها من قبل تطبيقات CAD مثل MicroStation و Intergraph Interactive Graphics Design System. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dgn). |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | ملف Bitmap مستقل عن الجهاز (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | ملف تصحيح (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | صورة DjVu (.djvu) هو تنسيق ملف رسومي مخصص للمستندات والكتب الممسوحة ضوئيًا خاصة تلك التي تحتوي على مزيج من النصوص والرسومات والصور والفوتوغرافات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/djvu). |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | مواصفة Digital Negative (.dng) هي تنسيق صورة كاميرا رقمية يُستخدم لتخزين الملفات الخام. تم تطويره من قبل Adobe في سبتمبر 2004. تم تطويره أساسًا للتصوير الفوتوغرافي الرقمي. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/dng). |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | مستند Microsoft Word (.doc) يمثل مستندات تم إنشاؤها بواسطة Microsoft Word أو برامج معالجة النصوص الأخرى بصيغة ملف ثنائي. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | مستند Word Open XML مع تمكين الماكرو (.docm) هو مستند تم إنشاؤه بواسطة Microsoft Word 2007 أو أحدث مع القدرة على تشغيل الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | مستند Microsoft Word Open XML (.docx) هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه منذ 2007 مع إصدار Microsoft Office 2007، وتم تغيير بنية هذا التنسيق الجديد من ثنائي بسيط إلى مزيج من ملفات XML وملفات ثنائية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | قالب مستند Word (.dot) هو ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة الصياغة لإنشاء مستندات DOC أو DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | قالب مستند Word Open XML مع تمكين الماكرو (.dotm) يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أحدث. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | قالب مستند Word Open XML (.dotx) هو ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة الصياغة لإنشاء ملفات DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | ملف Design Web Format (.dwf) يمثل رسومات ثنائية/ثلاثية الأبعاد بصيغة مضغوطة للعرض أو المراجعة أو طباعة ملفات التصميم. يحتوي على رسومات ونص كجزء من بيانات التصميم ويقلل حجم الملف بفضل صيغته المضغوطة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dwf). |
| static readonly [DWFX](../../groupdocs.viewer/filetype/dwfx) | ملف تنسيق الويب للتصميم XPS (.dwfx) يمثل رسومات ثنائية/ثلاثية الأبعاد كوثيقة XPS بصيغة مضغوطة للعرض أو المراجعة أو طباعة ملفات التصميم. يحتوي على رسومات ونص كجزء من بيانات التصميم ويقلل حجم الملف بفضل صيغته المضغوطة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dwfx). |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | ملف قاعدة بيانات رسومات AutoCAD (.dwg) يمثل ملفات ثنائية مملوكة تُستخدم لاحتواء بيانات التصميم ثنائية وثلاثية الأبعاد. مثل DXF، التي هي ملفات ASCII، يمثل DWG صيغة الملف الثنائي لرسومات CAD (التصميم بمساعدة الحاسوب). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dwg). |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | قالب رسومات AutoCAD (.dwt) هو ملف قالب رسومات AutoCAD يُستخدم كنقطة انطلاق لإنشاء رسومات يمكن حفظها كملفات DWG. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dwt). |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | ملف تنسيق تبادل الرسومات (.dxf) هو تمثيل بيانات مُعلمة لملف رسومات AutoCAD. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/dxf). |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | ملف Windows Metafile المحسن (.emf) يمثل صورًا رسومية مستقلة عن الجهاز. تتألف ملفات الميتا من EMF من سجلات ذات طول متغير بترتيب زمني يمكنها عرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/emf). |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | رسالة البريد الإلكتروني (.eml) تمثل رسائل البريد المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. تدعم تقريبًا جميع عملاء البريد هذا التنسيق لامتثاله لمعيار RFC-822 لتنسيق رسائل الإنترنت. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/eml). |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | رسالة Apple Mail (.emlx) تم تنفيذها وتطويرها من قبل Apple. يستخدم تطبيق Apple Mail تنسيق ملف EMLX لتصدير الرسائل الإلكترونية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/emlx). |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | ملف Windows Metafile المحسن المضغوط (.emz) يمثل صورًا رسومية مستقلة عن الجهاز ومضغوطة بواسطة GZIP. تتألف ملفات الميتا من EMF من سجلات ذات طول متغير بترتيب زمني يمكنها عرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/emz). |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | ملف Encapsulated PostScript (.eps) يصف برنامج لغة Encapsulated PostScript الذي يحدد مظهر صفحة واحدة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/eps). |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | ملف Open eBook (.epub) هو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. أصبح هذا التنسيق شائعًا إلى حد أنه مدعوم من قبل العديد من القارئات الإلكترونية وتطبيقات البرمجيات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/ebook/epub). |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | سكريبت Ruby ERB (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML (SpreadsheetML) يمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج جداول بيانات مشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [FBX](../../groupdocs.viewer/filetype/fbx) | ملف تبادل Autodesk FBX (FilmBoX) (.fbx) يمثل تنسيق نموذج ثلاثي الأبعاد. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/fbx). |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | قالب Flat XML ODF (.fodg) يُستخدم بواسطة تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/fodg). |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | عرض OpenDocument (.fodp) يمثل عرض OpenDocument Flat XML. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/fodp). |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | جدول بيانات OpenDocument Flat XML (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | ملف تنسيق التبادل الرسومي (.gif) هو نوع من الصور المضغوطة بشكل كبير. لكل صورة GIF عادةً تسمح بما يصل إلى 8 بت لكل بكسل وتسمح بما يصل إلى 256 لونًا عبر الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/gif). |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | ملف كود المصدر Groovy (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | ملفات Gnu Zipped (.gz) هي ملفات مضغوطة تم إنشاؤها باستخدام تطبيق ضغط gzip. يمكن أن تحتوي على ملفات مضغوطة متعددة وتُستخدم عادةً على أنظمة UNIX و Linux. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/compression/gz). |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | تم تقديم ملف Gnu Zipped (.gzip) كأداة مجانية لاستبدال برنامج Compress المستخدم في أنظمة Unix. يمكن فتح هذه الملفات واستخراجها باستخدام عدة تطبيقات مثل WinZip المتوفر على كل من Windows و MacOS. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/compression/gz). |
| static readonly [H](../../groupdocs.viewer/filetype/h) | ملف رأس C/C++/Objective-C (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | ملف شفرة المصدر Haml (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | ملف رأس C++ (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | ملف PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | ملف Hypertext Markup Language (.htm) هو الامتداد لصفحات الويب التي تم إنشاؤها للعرض في المتصفحات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/web/html). |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | ملف Hypertext Markup Language (.html) هو الامتداد لصفحات الويب التي تم إنشاؤها للعرض في المتصفحات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/web/html). |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | ملف الأيقونة (.ico) هو نوع من ملفات الصور يُستخدم كأيقونة لتمثيل تطبيق على نظام Microsoft Windows. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/ico). |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | ملف Industry Foundation Classes (.ifc) هو تنسيق ملف يضع معايير دولية لاستيراد وتصدير كائنات المباني وخصائصها. يوفر هذا التنسيق قابلية التفاعل بين تطبيقات البرمجيات المختلفة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/ifc). |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | مواصفة تبادل الرسومات الأولية (IGES) (.igs) |
| static readonly [Iso](../../groupdocs.viewer/filetype/iso) | صورة قرص بصري ISO هي ملف صورة قرص أرشيف غير مضغوط يمثل محتويات البيانات الكاملة على قرص بصري مثل CD أو DVD، استنادًا إلى معيار ISO-9660. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/iso/). |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | تدفق شفرة JPEG 2000 (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | تدفق شفرة JPEG 2000 (.j2k) هو صورة مضغوطة باستخدام ضغط الموجة بدلاً من ضغط DCT. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/j2k). |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | ملف شفرة المصدر Java (.java) |
| static readonly [JFIF](../../groupdocs.viewer/filetype/jfif) | تنسيق تبادل ملفات JPEG (.jfif) هو صورة تم تطويرها لتبادل سريع بين المنصات. يستخدم هذا التنسيق ضغط JPEG. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jfif). |
| static readonly [JLS](../../groupdocs.viewer/filetype/jls) | JPEG-LS (JLS) (.jls) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | ملف صورة JPEG 2000 Core (.jp2) هو نظام ترميز صور ومعيار ضغط صور متطور. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jp2). |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | تدفق شفرة JPEG 2000 (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | صورة JPEG (.jpeg) هي نوع من تنسيقات الصور يتم حفظها باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، تمثل موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | ملف صورة JPEG 2000 (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | صورة JPEG (.jpg) هي نوع من تنسيقات الصور يتم حفظها باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، تمثل موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | ملف صورة JPEG 2000 (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | ملف صورة JPEG 2000 (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | ملف JavaScript (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | ملف جافا سكريبت لتنسيق الكائنات (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | ورقة أنماط LESS (.less) |
| static readonly [Lha](../../groupdocs.viewer/filetype/lha) | LHA أو LZH هو أداة ضغط مجانية وتنسيق ملف مرتبط. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/lzh/). |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | ملف سجل (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | ملف تنفيذ Objective-C (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | نص Makefile لـ Xcode (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | ملف صندوق بريد البريد الإلكتروني (.mbox) تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/mbox). |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | ملف توثيق Markdown (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | أرشيف ويب MHTML (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | ملف MIME HTML (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | ملف شفرة مصدر ML (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | ملف مصدر Objective-C++ (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | ملف eBook من Mobipocket (.mobi) هو أحد أكثر تنسيقات الكتب الإلكترونية استخدامًا. التنسيق هو تحسين لتنسيق OEB (Open Ebook Format) القديم وكان يُستخدم كتنسيق مملوك لبرنامج قراءة Mobipocket. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/ebook/mobi). |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | ملف Microsoft Project (.mpp) هو ملف بيانات Microsoft Project يخزن المعلومات المتعلقة بإدارة المشاريع بطريقة متكاملة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | قالب Microsoft Project (.mpt) يحتوي على معلومات أساسية وبنية بالإضافة إلى إعدادات المستند لإنشاء ملفات .MPP. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | ملف Microsoft Project Exchange (.mpx) هو تنسيق ملف ASCII لنقل معلومات المشروع بين Microsoft Project (MSP) وتطبيقات أخرى تدعم تنسيق MPX مثل Primavera Project Planner و Sciforma و Timerline Precision Estimating. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | رسالة بريد Outlook (.msg) هي تنسيق ملف يستخدمه Microsoft Outlook و Exchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/msg). |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | قاعدة بيانات Lotus Notes (.nsf) تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/nsf). |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple Numbers يمثل تنسيق ملف ثنائي مشابه لـ Excel. يمكن إنشاء مثل هذه الملفات بواسطة تطبيق Apple Numbers. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/numbers). |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | ملف كائن 3D من Wavefront (.obj) هو ملف صورة ثلاثية الأبعاد قدمته Wavefront Technologies. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/3d/obj/). |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | ملف رسومي OpenDocument (.odg) يُستخدم بواسطة تطبيق Draw من Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/odg). |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | عرض OpenDocument (.odp) يمثل تنسيق ملف عرض يُستخدم بواسطة OpenOffice.org في معيار OASISOpen. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | جدول بيانات OpenDocument (.ods) هو تنسيق مستند جدول بيانات OpenDocument يمكن تحريره من قبل المستخدم. تُخزن البيانات داخل ملف ODF في صفوف وأعمدة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | مستند نص OpenDocument (.odt) هو نوع من المستندات التي تُنشأ باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف نص OpenDocument. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [OFD](../../groupdocs.viewer/filetype/ofd) | تنسيق المستند الثابت التخطيط (OFD) المحدد بواسطة GB/T 33190-2016 يهدف إلى استبدال PDF في المؤسسات العامة الصينية |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | ملف بيانات أوفلاين لأوتلوك (.ost) يمثل بيانات صندوق بريد المستخدم في وضع عدم الاتصال على الجهاز المحلي عند التسجيل مع خادم Exchange باستخدام Microsoft Outlook. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/ost). |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | قالب رسومي OpenDocument (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | قالب عرض OpenDocument (.otp) يمثل ملفات قوالب العروض التي تُنشئها التطبيقات وفق تنسيق معيار OASIS OpenDocument. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/otp). |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | قالب جدول بيانات OpenDocument (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | قالب مستند OpenDocument (.ott) يمثل مستندات القوالب التي تُنشئها التطبيقات وفق تنسيق معيار OASIS OpenDocument. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | ملف OpenXPS (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | مستند لغة أوامر الطابعة (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | ملف تنسيق المستندات القابل للنقل (.pdf) هو نوع من المستندات أنشأته شركة Adobe في تسعينيات القرن الماضي. كان هدف هذا التنسيق تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى في صيغة مستقلة عن برامج التطبيقات والأجهزة وكذلك نظام التشغيل. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/view/pdf). |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | ملف شفرة مصدر PHP (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | سكريبت Perl (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | ملف PLT (HPGL) (.plt) هو ملف رسام يعتمد على المتجهات تم تقديمه من قبل Autodesk, Inc. ويحتوي على معلومات لملف CAD معين. تتطلب تفاصيل الرسم دقة وتحديد في الإنتاج، واستخدام ملف PLT يضمن ذلك لأن جميع الصور تُطبع باستخدام خطوط بدلاً من النقاط. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/plt). |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | ملف Portable Network Graphic (.png) هو نوع من تنسيقات الصور النقطية التي تستخدم ضغطًا غير فقدان للبيانات. تم إنشاء هذا التنسيق كبديل لتنسيق Graphics Interchange Format (GIF) ولا يحتوي على قيود حقوق نشر. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/png). |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | قالب PowerPoint (.pot) يمثل ملفات قوالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pot). |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | قالب عرض PowerPoint Open XML المدعم بالماكرو (.potm) هو ملفات قوالب Microsoft PowerPoint التي تدعم الماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو أحدث وتحتوي على إعدادات افتراضية يمكن استخدامها لإنشاء ملفات عرض إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/potm). |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | قالب عرض PowerPoint Open XML (.potx) يمثل عروض قوالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/potx). |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | عرض شرائح PowerPoint (.pps) يتم إنشاؤه باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يدعم Microsoft PowerPoint 97-2003 قراءة وإنشاء ملفات PPS. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | شريحة PowerPoint Open XML المدعومة بالماكرو (.ppsm) تمثل تنسيق ملف عرض شرائح مدعوم بالماكرو تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أحدث. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | ملفات عرض شرائح PowerPoint Open XML (.ppsx) يتم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق لغرض عرض الشرائح. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | عرض PowerPoint (.ppt) يمثل ملف PowerPoint يتألف من مجموعة من الشرائح للعرض كعرض شرائح. يحدد تنسيق الملف الثنائي المستخدم من قبل Microsoft PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | عرض PowerPoint Open XML المدعم بالماكرو هو ملفات عرض مدعومة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) هي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس النسخة السابقة من تنسيق ملف العرض PPT الذي كان ثنائيًا، يعتمد تنسيق PPTX على تنسيق ملف عرض Microsoft PowerPoint المفتوح XML. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pptx). |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | ملف خصائص جافا (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | ملف PostScript (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | ملف سكريبت PowerShell (.ps1) هو تنسيق ملف لملفات Cmdlet الخاصة بـ Windows PowerShell. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/ps1). |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | ملف بيان وحدة سكريبت PowerShell (.psd1) هو تنسيق ملف لسكريبتات بيان وحدة PowerShell. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/psd1). |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | ملف وحدة سكريبت PowerShell (.psm1) هو تنسيق ملف لسكريبتات وحدة PowerShell. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/psm1). |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | ملف تخزين المعلومات الشخصية لـ Outlook (.pst) يمثل ملفات تخزين Outlook الشخصية (المعروفة أيضًا باسم جدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/pst). |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | سكريبت بايثون (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | ملف أرشيف روسال (.rar) هو ملفات مضغوطة تم إنشاؤها باستخدام طريقة ضغط RAR (WINRAR). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/compression/rar). |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | كود مصدر روبي (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | ملف reStructuredText (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | ملف تنسيق النص الغني (.rtf) يمثل طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | ملف Syntactically Awesome StyleSheets (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | ملف كود مصدر سكالا (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | ملف كود مصدر Scheme (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | ملف سكريبت عام (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z, .7zip) هو أداة أرشفة مفتوحة المصدر مجانية تستخدم ضغط LZMA و LZMA2. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/7z/). |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | سكريبت Bash Shell (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | ملف كود مصدر Standard ML (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | ملف بيانات Structured Query Language (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | ملف Stereolithography (.stl) هو تنسيق ملف قابل للتبادل يمثل هندسة سطح ثلاثية الأبعاد. يُستخدم هذا التنسيق في عدة مجالات مثل النمذجة السريعة، الطباعة ثلاثية الأبعاد، والتصنيع بمساعدة الحاسوب. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/cad/stl). |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | ملف Scalable Vector Graphics (.svg) هو ملف رسومات متجهية قابلة للتوسع يستخدم تنسيق نصي قائم على XML لوصف مظهر الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | ملف Scalable Vector Graphics (.svgz) هو ملف رسومات متجهية قابلة للتوسع يستخدم تنسيق نصي قائم على XML، مضغوط بـ GZIP لوصف مظهر الصورة. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/svgz). |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | جدول بيانات StarOffice Calc (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | ملف أرشيف Unix الموحد (.tar) هو أرشيفات تم إنشاؤها باستخدام أداة تعتمد على Unix لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/compression/tar). |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | أرشيفات ملف يونكس الموحد (.tgz, .tar.gz) هي أرشيفات تم إنشاؤها باستخدام أداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/tgz). |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | أرشيفات ملف يونكس الموحد (.txz, .tar.xz) هي أرشيفات تم إنشاؤها باستخدام أداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/txz). |
| static readonly [TarZst](../../groupdocs.viewer/filetype/tarzst) | ملفات TZST (.tar.zst, .tzst) هي أرشيفات Zstandard (ZST)، والتي تحتوي داخليًا على أرشيف ملف يونكس موحد (Tar)، تم إنشاؤه باستخدام أداة تعتمد على يونكس لجمع ملف واحد أو أكثر. |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | مستند مصدر LaTeX (.tex) هو لغة تتضمن ميزات برمجة وكذلك ميزات توصيف، تُستخدم لتنسيق المستندات. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/tex). |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA (محول الراستر المتقدم من Truevision - TARGA) يُستخدم لتخزين الصور الرقمية النقطية التي طورتها TRUEVISION. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/tga). |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | أرشيفات ملف يونكس الموحد (.tgz, .tar.gz) هي أرشيفات تم إنشاؤها باستخدام أداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/tgz). |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | ملف الصورة الموسومة (.tif) يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. وهو قادر على وصف بيانات الصورة ذات المستوى الثنائي، وتدرج الرمادي، وألوان لوحة الألوان، والصورة ذات الألوان الكاملة في عدة فضاءات لونية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/tiff). |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | ملف الصورة الموسومة (.tiff) يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. وهو قادر على وصف بيانات الصورة ذات المستوى الثنائي، وتدرج الرمادي، وألوان لوحة الألوان، والصورة ذات الألوان الكاملة في عدة فضاءات لونية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/tiff). |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | ملف القيم المفصولة بالجدولة (.tsv) يمثل بيانات مفصولة بعلامات جدولة في تنسيق نص عادي. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | ملف النص العادي (.txt) يمثل مستند نص يحتوي على نص عادي على شكل أسطر. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | أرشيفات ملف يونكس الموحد (.txz, .tar.xz) هي أرشيفات تم إنشاؤها باستخدام أداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/txz). |
| static readonly [Tzst](../../groupdocs.viewer/filetype/tzst) | ملفات TZST (.tar.zst, .tzst) هي أرشيفات Zstandard (ZST)، والتي تحتوي داخليًا على أرشيف ملف يونكس موحد (Tar)، تم إنشاؤه باستخدام أداة تعتمد على يونكس لجمع ملف واحد أو أكثر. |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | يمثل نوع ملف غير معروف. |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | ملف عنصر مشروع Visual Basic (.vb) هو ملف كود مصدر تم إنشاؤه بلغة Visual Basic التي طورتها Microsoft لتطوير تطبيقات .NET. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/programming/vb). |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | ملف vCard (.vcf) هو تنسيق ملف رقمي لتخزين معلومات الاتصال. يُستخدم هذا التنسيق على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشائعة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/vcf). |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | رسمة Visio على الويب (.vdw) تمثل تنسيق ملف يحدد التدفقات والتخزينات المطلوبة لتصوير رسم ويب. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/web/vdw). |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | ملف Visio Drawing XML (.vdx) يمثل أي رسم أو مخطط تم إنشاؤه في Microsoft Visio، لكنه محفوظ بتنسيق XML يحمل امتداد .VDX. يتم إنشاء ملف Visio Drawing XML في برنامج Visio، الذي طورته Microsoft. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vdx). |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | ملف إعدادات Vim (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | ملف رسم Visio (.vsd) هو رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والاتصالات بينها. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsd). |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | ملف رسم Visio مع تمكين الماكرو (.vsdm) هو ملفات رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio وتدعم الماكرو. ملفات VSDM هي رسومات OPC/XML تشبه VSDX، لكنها توفر أيضًا القدرة على تشغيل الماكرو عند فتح الملف. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | يمثل Visio Drawing (.vsdx) تنسيق ملف Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. تم تطويره لاستبدال تنسيق الملف الثنائي .VSD، الذي تدعمه الإصدارات السابقة من Microsoft Visio. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | ملفات Visio Stencil File(.vss) هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio 2007 والإصدارات السابقة. توفر ملفات القوالب كائنات رسم يمكن تضمينها في رسم Visio بامتداد .VSD. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vss). |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | ملف Visio Macro-Enabled Stencil (.vssm) هو ملف قوالب Microsoft Visio يدعم الماكرو. عند فتح ملف VSSM يتيح تشغيل الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في المخطط. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | ملف Visio Stencil (.vssx) هو قالب رسم تم إنشاؤه باستخدام Microsoft Visio 2013 وما فوق. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما فوق. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال، الموصلات، المخططات الانسيابية، تخطيط الشبكات، مخططات UML. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | قالب Visio Drawing (.vst) هو ملف صورة متجهة تم إنشاؤه باستخدام Microsoft Visio ويعمل كقالب لإنشاء ملفات أخرى. هذه القوالب بتنسيق ملف ثنائي وتحتوي على التخطيط والإعدادات الافتراضية المستخدمة لإنشاء رسومات Visio جديدة. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vst). |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | قالب Visio Macro-Enabled Drawing (.vstm) هو ملفات قالب تم إنشاؤها باستخدام Microsoft Visio وتدعم الماكرو. على عكس ملفات VSDX، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل الماكرو المطور بلغة Visual Basic for Applications (VBA). تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | قالب Visio Drawing (.vstx) هو ملفات قالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. توفر ملفات VSTX نقطة انطلاق لإنشاء رسومات Visio، تُحفظ كملفات .VSDX، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | ملف Visio Stencil XML (.vsx) يشير إلى القوالب التي تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. تُحفظ ملفات VSX بتنسيق XML وكان الدعم متاحًا حتى Visio 2013. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | ملف Visio Template XML (.vtx) هو قالب رسم Microsoft Visio يُحفظ على القرص بتنسيق XML. يهدف القالب إلى توفير ملف بإعدادات أساسية يمكن استخدامها لإنشاء عدة ملفات Visio بنفس الإعدادات. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/vtx). |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | صورة WebP (.webp) هي تنسيق ملف صورة نقطية حديث للويب يعتمد على ضغط غير فقدان للبيانات وضغط فقدان للبيانات. توفر نفس جودة الصورة مع تقليل حجم الصورة بشكل كبير. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/webp). |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | ملف Windows Metafile (.wmf) يمثل Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهة وكذلك بصيغة bitmap. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/image/wmf). |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | ملف Compressed Windows Metafile (.wmz) يمثل Microsoft Windows Metafile (WMF) مضغوطًا باستخدام أرشيف GZIP - لتخزين بيانات الصور المتجهة وكذلك بصيغة bitmap. تعرف على المزيد حول تنسيق الملف هذا [here](https://fileinfo.com/extension/wmz#compressed_windows_metafile). |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | ملحق Microsoft Excel (.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | تمثل Excel Spreadsheet (.xls) تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج جداول بيانات مشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا [here](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى مصنف Excel. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) هو نوع من ملفات جداول البيانات التي تدعم الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel Template (.xlt) هي ملفات قالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول بيانات يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة وكذلك فتحها. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel Macro-Enabled Template (.xltm) يمثل ملفات يتم إنشاؤها بواسطة Microsoft Excel كقوالب تمكين الماكرو. ملفات XLTM مشابهة لملفات XLTX في البنية باستثناء أن الأخيرة لا تدعم إنشاء قوالب مع ماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx) يمثل قالب Microsoft Excel المستند إلى مواصفات تنسيق ملف Office OpenXML. يُستخدم لإنشاء ملف قالب قياسي يمكن استخدامه لتوليد ملفات XLSX التي تعرض نفس الإعدادات المحددة في ملف XLTX. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/spreadsheet/xltx). |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML File (.xml). يحتوي GroupDocs.Viewer على معالج خاص للتعامل مع ملفات XML، راجع [الوثائق](https://docs.groupdocs.com/viewer/net/render-xml-documents/). |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML Paper Specification File (.xps) يمثل ملفات تخطيط الصفحات المستندة إلى مواصفات XML Paper التي أنشأتها Microsoft. تم تطوير هذا التنسيق من قبل Microsoft كبديل لتنسيق ملف EMF وهو مشابه لتنسيق PDF، لكنه يستخدم XML في تخطيط ومظهر ومعلومات الطباعة للمستند. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/page-description-language/xps). |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ file (.xz) هو أرشيف مضغوط يستخدم خوارزمية ضغط عالية النسبة تعتمد على خوارزمية LZMA. تعرف على المزيد حول هذا التنسيق [هنا](https://fileinfo.com/extension/xz). |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | مستند YAML (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | Zipped File (.zip) يمثل أرشيفات يمكنها احتواء ملف أو أكثر أو أدلة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/compression/zip). |
| static readonly [Zstandard](../../groupdocs.viewer/filetype/zstandard) | ZST file هو ملف مضغوط يتم إنشاؤه باستخدام خوارزمية الضغط Zstandard (zstd). هو ملف مضغوط يتم إنشاؤه بضغط غير فقداني بواسطة الخوارزمية. يمكن استخدام ملفات ZST لضغط أنواع مختلفة من الملفات مثل قواعد البيانات، أنظمة الملفات، الشبكات، والألعاب. تعرف على المزيد حول هذا التنسيق [هنا](https://docs.fileformat.com/compression/zst/). |

### انظر أيضًا

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
