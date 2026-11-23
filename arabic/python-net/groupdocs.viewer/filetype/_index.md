---
title: "فئة FileType"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل نوع ملف ويوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل GroupDocs.Viewer."
type: docs
url: /ar/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

يمثل نوع ملف ويوفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل GroupDocs.Viewer.

يعرض نوع FileType الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | ينشئ مثيلاً جديداً من [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | ينشئ مثيلاً جديداً من FileType. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | يكشف عن ترميز ملفات النص TXT و TSV و CSV حسب المسار. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | يحاول الكشف عن ترميز ملفات النص (TXT، TSV، CSV) من تدفق. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | يحدد ما إذا كان [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) الحالي هو نفسه الـ [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) المحدد. |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | يحدد ما إذا كان [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) الحالي هو نفسه الكائن المحدد. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | يربط امتداد الملف بنوع الملف. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | يستخرج امتداد الملف ويربطه بنوع الملف. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | يربط نوع وسائط الملف بـ [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (مثال: 'application/pdf' يربط بـ [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | يكشف عن نوع الملف بقراءة توقيع الملف. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | يكشف عن نوع الملف بقراءة توقيع الملف. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | يكشف عن نوع الملف بقراءة توقيع الملف. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | يكشف عن نوع الملف بقراءة توقيع الملف. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | يعيد رمز التجزئة للكائن الحالي [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | يسترجع أنواع الملفات المدعومة. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | يعيد سلسلة نصية تمثل الكائن الحالي. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | لاحقة اسم الملف (بما في ذلك النقطة \".\") مثال: \".doc\". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | اسم نوع الملف مثال: \"Microsoft Word Document\". |

### الحقول
| حقل | الوصف |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | يمثل نوع ملف غير معروف. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | ملف مضغوط (.zip) يمثل أرشيفًا يمكنه احتواء ملف واحد أو أكثر أو أدلة. تعرف على المزيد حول هذا التنسيق هنا. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | أرشيف ملفات يونكس الموحد (.tar) هو أرشيف تم إنشاؤه بأداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق هنا. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | ملف XZ (.xz) هو أرشيف مضغوط باستخدام خوارزمية ضغط عالية النسبة تعتمد على خوارزمية LZMA. تعرف على المزيد حول هذا التنسيق هنا. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | أرشيف ملفات يونكس الموحد (.txz، .tar.xz) هو أرشيف تم إنشاؤه بأداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق هنا. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | أرشيف ملفات يونكس الموحد (.txz، .tar.xz) هو أرشيف تم إنشاؤه بأداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق هنا. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | أرشيف ملفات يونكس الموحد (.tgz، .tar.gz) هو أرشيف تم إنشاؤه بأداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق هنا. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | أرشيف ملفات يونكس الموحد (.tgz، .tar.gz) هو أرشيف تم إنشاؤه بأداة تعتمد على يونكس لجمع ملف واحد أو أكثر. تعرف على المزيد حول هذا التنسيق هنا. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | ملف مضغوط Bzip2 (.bz2) هو ملفات مضغوطة تم إنشاؤها باستخدام طريقة ضغط BZIP2 المفتوحة المصدر، غالبًا على نظام يونكس أو لينكس. تعرف على المزيد حول هذا التنسيق هنا. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) هي ملفات مضغوطة تم إنشاؤها باستخدام طريقة ضغط RAR (WINRAR). تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) هي ملفات مضغوطة تم إنشاؤها باستخدام تطبيق ضغط gzip. يمكن أن تحتوي على ملفات مضغوطة متعددة وتُستخدم عادةً على أنظمة UNIX وLinux. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) تم تقديمه كأداة مجانية لاستبدال برنامج Compress المستخدم في أنظمة Unix. يمكن فتح مثل هذه الملفات واستخراجها باستخدام عدة تطبيقات مثل WinZip المتوفر على كل من Windows وMacOS. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) هو برنامج أرشفة مفتوح المصدر ومجاني يدعم ضغط LZMA وLZMA2. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio هو أداة أرشفة ملفات عامة وتنسيق الملف المرتبط بها. يتم تثبيتها أساسًا على أنظمة تشغيل الحواسيب الشبيهة بـ Unix. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ملف ZST هو ملف مضغوط يتم إنشاؤه باستخدام خوارزمية ضغط Zstandard (zstd). هو ملف مضغوط يُنتج بضغط غير فقدان للبيانات بواسطة الخوارزمية. يمكن استخدام ملفات ZST لضغط أنواع مختلفة من الملفات مثل قواعد البيانات، أنظمة الملفات، الشبكات، والألعاب. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | ملفات TZST (.tar.zst, .tzst) هي أرشيفات Zstandard (ZST)، والتي تحتوي داخليًا على أرشيف ملفات Unix موحد (Tar)، تم إنشاؤه باستخدام أداة تعتمد على Unix لجمع ملف واحد أو أكثر. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | ملفات TZST (.tar.zst, .tzst) هي أرشيفات Zstandard (ZST)، والتي تحتوي داخليًا على أرشيف ملفات Unix موحد (Tar)، تم إنشاؤه باستخدام أداة تعتمد على Unix لجمع ملف واحد أو أكثر. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | صورة قرص بصري ISO هي ملف صورة قرص أرشيف غير مضغوط يمثل محتويات البيانات الكاملة على قرص بصري مثل CD أو DVD، بناءً على معيار ISO-9660. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA أو LZH هي أداة ضغط مجانية وتنسيق ملف مرتبط بها. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (أو CAB) هو تنسيق ملف أرشيف لنظام Microsoft Windows. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | ملف Drawing Exchange Format (.dxf) هو تمثيل بيانات مُوسَّم لملف رسم AutoCAD. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | ملف قاعدة بيانات رسومات AutoCAD (.dwg) يمثل ملفات ثنائية مملوكة تُستخدم لاحتواء بيانات التصميم ثنائية وثلاثية الأبعاد. مثل DXF، التي هي ملفات ASCII، يمثل DWG تنسيق الملف الثنائي لرسومات CAD (التصميم بمساعدة الحاسوب). تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | قالب رسم AutoCAD (.dwt) هو ملف قالب رسم AutoCAD يُستخدم كنقطة انطلاق لإنشاء رسومات يمكن حفظها كملفات DWG. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | ملف Stereolithography (.stl) هو تنسيق ملف قابل للتبادل يمثل هندسة سطح ثلاثية الأبعاد. يُستخدم هذا التنسيق في عدة مجالات مثل النمذجة السريعة، الطباعة ثلاثية الأبعاد، والتصنيع بمساعدة الحاسوب. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | ملف Industry Foundation Classes (.ifc) هو تنسيق ملف يضع معايير دولية لاستيراد وتصدير كائنات المباني وخصائصها. يوفر هذا التنسيق قابلية التفاعل بين تطبيقات البرمجيات المختلفة. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | ملف Design Web Format (.dwf) يمثل رسومات 2D/3D بصيغة مضغوطة للعرض أو المراجعة أو طباعة ملفات التصميم. يحتوي على رسومات ونص كجزء من بيانات التصميم ويقلل من حجم الملف بفضل صيغته المضغوطة. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | ملف Autodesk FBX Interchange (FilmBoX) (.fbx) يمثل تنسيق نموذج ثلاثي الأبعاد. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | ملف Design Web Format XPS (.dwfx) يمثل رسومات 2D/3D كوثيقة XPS بصيغة مضغوطة للعرض أو المراجعة أو طباعة ملفات التصميم. يحتوي على رسومات ونص كجزء من بيانات التصميم ويقلل من حجم الملف بفضل صيغته المضغوطة. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | ملف MicroStation Design (.dgn) هي رسومات تم إنشاؤها ودعمها بواسطة تطبيقات CAD مثل MicroStation وIntergraph Interactive Graphics Design System. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) هو ملف رسام متجه تم تقديمه من قبل Autodesk, Inc. ويحتوي على معلومات لملف CAD معين. تتطلب تفاصيل الرسم دقة وإتقان في الإنتاج، واستخدام ملف PLT يضمن ذلك حيث يتم طباعة جميع الصور باستخدام خطوط بدلاً من النقاط. تعرف على المزيد حول هذا التنسيق هنا. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | ملف تنسيق شائع تعرف على المزيد حول هذا التنسيق هنا. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) هو ملف صورة ثلاثية الأبعاد تم تقديمه من قبل Wavefront Technologies. تعرف على المزيد حول هذا التنسيق هنا. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) هي رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والاتصالات بينها. تعرف على المزيد حول هذا التنسيق هنا. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) يمثل تنسيق ملف Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. تم تطويره لاستبدال تنسيق الملف الثنائي .VSD، الذي كان مدعومًا في الإصدارات السابقة من Microsoft Visio. تعرف على المزيد حول هذا التنسيق هنا. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio 2007 والإصدارات السابقة. توفر ملفات القوالب كائنات رسم يمكن تضمينها في رسم Visio بامتداد .VSD. تعرف على المزيد حول هذا التنسيق هنا. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) هي قوالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. يمكن فتح تنسيق ملف VSSX باستخدام Visio 2013 وما فوق. تُعرف ملفات Visio بتمثيل مجموعة متنوعة من عناصر الرسم مثل مجموعة الأشكال، الموصلات، المخططات الانسيابية، تخطيط الشبكة، مخططات UML. تعرف على المزيد حول هذا التنسيق هنا. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) هي ملفات رسم تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم الماكرو. ملفات VSDM هي رسومات OPC/XML مشابهة لـ VSDX، ولكنها توفر أيضًا القدرة على تشغيل الماكرو عند فتح الملف. تعرف على المزيد حول هذا التنسيق هنا. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) هي ملفات صورة متجهة تم إنشاؤها باستخدام Microsoft Visio وتعمل كقالب لإنشاء ملفات أخرى. هذه الملفات القالبية بتنسيق ملف ثنائي وتحتوي على التخطيط والإعدادات الافتراضية المستخدمة لإنشاء رسومات Visio جديدة. تعرف على المزيد حول هذا التنسيق هنا. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) هي ملفات قالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. توفر ملفات VSTX نقطة انطلاق لإنشاء رسومات Visio، تُحفظ كملفات .VSDX، مع التخطيط والإعدادات الافتراضية. تعرف على المزيد حول هذا التنسيق هنا. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) هي ملفات قالب تم إنشاؤها باستخدام Microsoft Visio وتدعم الماكرو. على عكس ملفات VSDX، يمكن للملفات التي تم إنشاؤها من قوالب VSTM تشغيل الماكرو المطور بلغة Visual Basic for Applications (VBA). تعرف على المزيد حول هذا التنسيق هنا. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) هي ملفات قوالب Microsoft Visio التي تدعم الماكرو. عند فتح ملف VSSM يسمح بتشغيل الماكرو لتحقيق التنسيق المطلوب ووضع الأشكال في المخطط. تعرف على المزيد حول هذا التنسيق هنا. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) تشير إلى القوالب التي تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. تُحفظ ملفات VSX بتنسيق XML وكان الدعم متاحًا حتى Visio 2013. تعرف على المزيد حول هذا التنسيق هنا. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) هو قالب رسم Microsoft Visio يُحفظ على القرص بتنسيق XML. يهدف القالب إلى توفير ملف بإعدادات أساسية يمكن استخدامها لإنشاء ملفات Visio متعددة بنفس الإعدادات. تعرف على المزيد حول هذا التنسيق هنا. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) يمثل تنسيق ملف يحدد التدفقات والتخزينات المطلوبة لعرض رسم ويب. تعرف على المزيد حول هذا التنسيق هنا. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) يمثل أي رسم أو مخطط تم إنشاؤه في Microsoft Visio، لكنه يُحفظ بتنسيق XML بامتداد .VDX. يتم إنشاء ملف رسم Visio XML في برنامج Visio الذي طورته Microsoft. تعرف على المزيد حول هذا التنسيق هنا. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | ملف Open eBook (.epub) هو تنسيق ملف كتاب إلكتروني يوفر تنسيق نشر رقمي قياسي للناشرين والمستهلكين. أصبح هذا التنسيق شائعًا إلى حد أنه مدعوم من قبل العديد من القارئات الإلكترونية وتطبيقات البرمجيات. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | ملف Mobipocket eBook (.mobi) هو أحد أكثر تنسيقات ملفات الكتب الإلكترونية استخدامًا. هذا التنسيق هو تحسين لتنسيق OEB (Open Ebook Format) القديم وكان يُستخدم كتنسيق مملوك لبرنامج Mobipocket Reader. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | كتاب Amazon Kindle Format 8 (KF8) هو تنسيق ملف رقمي تم تطويره لأجهزة Amazon Kindle. هذا التنسيق هو تحسين لملفات AZW القديمة ويُستخدم على أجهزة Kindle Fire فقط مع توافق رجعي مع تنسيق الملف الأصلي أي MOBI و AZW. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | رسالة بريد Outlook (.msg) هي تنسيق ملف يستخدمه Microsoft Outlook وExchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | رسالة البريد الإلكتروني (.eml) تمثل رسائل البريد التي تم حفظها باستخدام Outlook وتطبيقات أخرى ذات صلة. تدعم تقريبًا جميع عملاء البريد هذا التنسيق لامتثاله لمعيار RFC-822 لتنسيق رسائل الإنترنت. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | قاعدة بيانات Lotus Notes (.nsf) تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | ملف صندوق بريد البريد الإلكتروني (.mbox) تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | رسالة بريد Apple Mail (.emlx) تم تنفيذها وتطويرها من قبل Apple. يستخدم تطبيق Apple Mail تنسيق ملف EMLX لتصدير الرسائل الإلكترونية. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | ملف تخزين المعلومات الشخصية لـ Outlook (.pst) يمثل ملفات تخزين شخصية لـ Outlook (تُسمى أيضًا جدول التخزين الشخصي) التي تخزن مجموعة متنوعة من معلومات المستخدم. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | ملف بيانات Outlook غير المتصل (.ost) يمثل بيانات صندوق بريد المستخدم في وضع غير متصل على الجهاز المحلي عند التسجيل في خادم Exchange باستخدام Microsoft Outlook. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | ملف الصورة الموسومة (.tif) يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. يمكنه وصف بيانات الصورة ذات المستوى الثنائي، التدرج الرمادي، ألوان اللوحة، والألوان الكاملة في عدة فضاءات لونية. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | تنسيق ملف الصورة الموسومة (.tiff) يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. يمكنه وصف بيانات الصورة ذات المستوى الثنائي، التدرج الرمادي، ألوان اللوحة، والألوان الكاملة في عدة فضاءات لونية. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | صورة JPEG (.jpg) هي نوع من تنسيقات الصور يتم حفظها باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، تمثل موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | صورة JPEG (.jpeg) هي نوع من تنسيقات الصور يتم حفظها باستخدام طريقة الضغط الفاقد. الصورة الناتجة، نتيجة الضغط، تمثل موازنة بين حجم التخزين وجودة الصورة. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | تنسيق تبادل ملفات JPEG (.jfif) هو صورة تم تطويرها لتبادل سريع بين المنصات. يستخدم هذا التنسيق ضغط JPEG. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | صورة شبكة محمولة (.png) هي نوع من تنسيقات ملفات الصور النقطية يستخدم ضغطًا غير فقدان. تم إنشاء هذا التنسيق كبديل لتنسيق تبادل الرسومات (GIF) ولا يحمل قيود حقوق طبع ونشر. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | ملف تنسيق تبادل الرسومات (.gif) هو نوع من الصور ذات ضغط عالي. عادةً يسمح GIF لكل صورة بما يصل إلى 8 بتات لكل بكسل وإلى 256 لونًا عبر الصورة بأكملها. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | صورة شبكة محمولة متحركة (.apng) هي امتداد لتنسيق PNG يدعم الرسوم المتحركة. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | ملف صورة بتنسيق Bitmap (.bmp) يُستخدم لتخزين الصور الرقمية النقطية. هذه الصور مستقلة عن محول الرسومات وتُسمى أيضًا ملف بتنسيق bitmap غير معتمد على الجهاز (DIB). تعرف على المزيد حول هذا التنسيق هنا. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | يُستخدم Truevision TGA (Truevision Advanced Raster Adapter - TARGA) لتخزين الصور الرقمية النقطية التي طورتها TRUEVISION. تعرف على المزيد حول هذا التنسيق هنا. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | ملف الأيقونة (.ico) هو نوع من ملفات الصورة يُستخدم كأيقونة لتمثيل تطبيق على نظام Microsoft Windows. تعرف على المزيد حول هذا التنسيق هنا. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | ملف صورة JPEG 2000 Core (.jp2) هو نظام ترميز للصور ومعيار ضغط صور متقدم. تعرف على المزيد حول هذا التنسيق هنا. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | ملف صورة JPEG 2000 (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | ملف صورة JPEG 2000 (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | ملف صورة JPEG 2000 (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | تدفق شفرة JPEG 2000 (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | تدفق شفرة JPEG 2000 (.j2k) هو صورة مضغوطة باستخدام ضغط الموجة بدلاً من ضغط DCT. تعرف على المزيد حول هذا التنسيق هنا. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | تدفق شفرة JPEG 2000 (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | ملف Bitmap غير معتمد على الجهاز (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | ملف Windows Metafile (.wmf) يمثل Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهية وكذلك بصيغة bitmap. تعرف على المزيد حول هذا التنسيق هنا. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | ملف Windows Metafile المضغوط (.wmz) يمثل Microsoft Windows Metafile (WMF) مضغوطًا باستخدام أرشيف GZIP لتخزين بيانات الصور المتجهية وكذلك بصيغة bitmap. تعرف على المزيد حول هذا التنسيق هنا. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | ملف Enhanced Windows Metafile (.emf) يمثل الصور الرسومية بشكل غير معتمد على الجهاز. تتألف ملفات EMF من سجلات ذات طول متغير بترتيب زمني يمكنها عرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. تعرف على المزيد حول هذا التنسيق هنا. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | ملف Enhanced Windows Metafile المضغوط (.emz) يمثل الصور الرسومية غير المعتمدة على الجهاز ومضغوطة بواسطة GZIP. تتألف ملفات EMF من سجلات ذات طول متغير بترتيب زمني يمكنها عرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. تعرف على المزيد حول هذا التنسيق هنا. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | صورة WebP (.webp) هي تنسيق ملف صورة نقطية حديث للويب يعتمد على الضغط غير الفاقد والفاقد. توفر نفس جودة الصورة مع تقليل حجم الصورة بشكل كبير. تعرف على المزيد حول هذا التنسيق هنا. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | مواصفة Digital Negative (.dng) هي تنسيق صورة للكاميرا الرقمية يُستخدم لتخزين الملفات الخام. تم تطويره بواسطة Adobe في سبتمبر 2004. تم تطويره أساسًا للتصوير الرقمي. تعرف على المزيد حول هذا التنسيق هنا. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | رسمة CorelDraw Vector Graphic (.cdr) هي ملف صورة رسم متجه يتم إنشاؤه أصلاً باستخدام CorelDRAW لتخزين الصورة الرقمية المشفرة والمضغوطة. يحتوي هذا الملف على نصوص، خطوط، أشكال، صور، ألوان وتأثيرات لتمثيل المتجه لمحتوى الصورة. تعرف على المزيد حول هذا التنسيق هنا. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) هو ملف صورة رسم قد يحتوي على رسومات متجهة وكذلك رسومات bitmap. تعرف على المزيد حول هذا التنسيق هنا. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | صورة DjVu (.djvu) هي تنسيق ملف رسومي مخصص للمستندات والكتب الممسوحة ضوئيًا خاصةً تلك التي تحتوي على مزيج من النصوص، الرسومات، الصور والفوتوغرافات. تعرف على المزيد حول هذا التنسيق هنا. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | ملف Computer Graphics Metafile (.cgm) هو تنسيق ملف ميتا مجاني، مستقل عن المنصة، ومعيار دولي لتخزين وتبادل الرسومات المتجهة (2D)، الرسومات النقطية، والنص. يستخدم CGM نهجًا موجهًا للكائنات والعديد من الدوال لإنتاج الصور. تعرف على المزيد حول هذا التنسيق هنا. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | مستند Printer Command Language (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | مستند Adobe Photoshop (.psd) يمثل تنسيق الملف الأصلي لبرنامج Adobe Photoshop المستخدم لتصميم وتطوير الرسومات. تعرف على المزيد حول هذا التنسيق هنا. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | تنسيق Photoshop Large Document (.psb) يمثل تنسيق المستند الكبير لبرنامج Photoshop المستخدم لتصميم وتطوير الرسومات. تعرف على المزيد حول هذا التنسيق هنا. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | صورة DICOM (.dcm) تمثل صورة رقمية تخزن المعلومات الطبية للمرضى مثل صور الرنين المغناطيسي (MRI)، والمسح الضوئي (CT) وصور الموجات فوق الصوتية. تعرف على المزيد حول هذا التنسيق هنا. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | ملف PostScript (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | ملف Encapsulated PostScript (.eps) يصف برنامج لغة Encapsulated PostScript يوضح مظهر صفحة واحدة. تعرف على المزيد حول هذا التنسيق هنا. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | ملف OpenDocument Graphic (.odg) يُستخدم بواسطة تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول هذا التنسيق هنا. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | قالب Flat XML ODF (.fodg) يُستخدم بواسطة تطبيق Draw في Apache OpenOffice لتخزين عناصر الرسم كصورة متجهة. تعرف على المزيد حول هذا التنسيق هنا. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | ملف Scalable Vector Graphics (.svg) هو ملف رسومات متجهة قابلة للتوسع يستخدم تنسيق نص مبني على XML لوصف مظهر الصورة. تعرف على المزيد حول هذا التنسيق هنا. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | ملف Scalable Vector Graphics (.svgz) هو ملف رسومات متجهة قابلة للتوسع يستخدم تنسيق نص مبني على XML، مضغوط بواسطة GZIP لوصف مظهر الصورة. تعرف على المزيد حول هذا التنسيق هنا. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | قالب OpenDocument Graphic (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | ملف Hypertext Markup Language (.htm) هو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات. تعرف على المزيد حول هذا التنسيق هنا. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | ملف Hypertext Markup Language (.html) هو الامتداد لصفحات الويب التي تُنشأ للعرض في المتصفحات. تعرف على المزيد حول هذا التنسيق هنا. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | أرشيف ويب MHTML (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | ملف MIME HTML (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | ملف XML (.xml). يحتوي GroupDocs.Viewer على معالج خاص لمعالجة ملفات XML، راجع الوثائق. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | مستند OneNote (.one) يتم إنشاؤه بواسطة تطبيق Microsoft OneNote. يتيح لك OneNote جمع المعلومات باستخدام التطبيق كما لو كنت تستخدم دفتر ملاحظاتك لتدوين الملاحظات. تعرف على المزيد حول هذا التنسيق هنا. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | ملف Portable Document Format (.pdf) هو نوع من المستندات تم إنشاؤه بواسطة Adobe في تسعينيات القرن الماضي. كان هدف هذا التنسيق تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى في تنسيق مستقل عن برامج التطبيقات، الأجهزة وكذلك نظام التشغيل. تعرف على المزيد حول هذا التنسيق هنا. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | ملف XML Paper Specification (.xps) يمثل ملفات تخطيط الصفحات المستندة إلى مواصفات XML Paper التي أنشأتها Microsoft. تم تطوير هذا التنسيق من قبل Microsoft كبديل لتنسيق ملف EMF وهو مشابه لتنسيق PDF، لكنه يستخدم XML في تخطيط ومظهر ومعلومات الطباعة للمستند. تعرف على المزيد حول هذا التنسيق هنا. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | ملف OpenXPS (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | مستند مصدر LaTeX (.tex) هو لغة تتضمن ميزات برمجة وعلامات، تُستخدم لتنسيق المستندات. تعرف على المزيد حول هذا التنسيق هنا. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | تنسيق Open Fixed-layout Document (OFD) المحدد بالمعيار GB/T 33190-2016 يهدف إلى استبدال PDF في المؤسسات العامة الصينية. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | عرض PowerPoint (.ppt) يمثل ملف PowerPoint يتكون من مجموعة من الشرائح للعرض كعرض شرائح. يحدد تنسيق الملف الثنائي المستخدم من قبل Microsoft PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق هنا. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | عرض PowerPoint Open XML (.pptx) هي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير. على عكس النسخة السابقة من تنسيق ملف العرض PPT الذي كان ثنائيًا، يعتمد تنسيق PPTX على تنسيق ملف عرض PowerPoint المفتوح XML من Microsoft. تعرف على المزيد حول هذا التنسيق هنا. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | عرض شرائح PowerPoint (.pps) يتم إنشاؤه باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يدعم Microsoft PowerPoint 97-2003 قراءة وإنشاء ملفات PPS. تعرف على المزيد حول هذا التنسيق هنا. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | عرض شرائح PowerPoint Open XML (.ppsx) يتم إنشاؤه باستخدام Microsoft PowerPoint 2007 وما فوق لغرض عرض الشرائح. تعرف على المزيد حول هذا التنسيق هنا. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | عرض OpenDocument (.odp) يمثل تنسيق ملف العرض المستخدم من قبل OpenOffice.org في معيار OASISOpen. تعرف على المزيد حول هذا التنسيق هنا. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | عرض OpenDocument (.fodp) يمثل عرض OpenDocument Flat XML. تعرف على المزيد حول هذا التنسيق هنا. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | قالب PowerPoint (.pot) يمثل ملفات قالب Microsoft PowerPoint التي تم إنشاؤها بواسطة إصدارات PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق هنا. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation هي ملفات عرض تمكين الماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. تعرف على المزيد حول هذا التنسيق هنا. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx) يمثل عروض قالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 وما فوق. تعرف على المزيد حول هذا التنسيق هنا. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) هي ملفات قالب Microsoft PowerPoint تدعم الماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو أعلى وتحتوي على إعدادات افتراضية يمكن استخدامها لإنشاء ملفات عرض إضافية. تعرف على المزيد حول هذا التنسيق هنا. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) يمثل تنسيق ملف عرض شرائح مدعوم بالماكرو تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أعلى. تعرف على المزيد حول هذا التنسيق هنا. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp) يمثل ملفات قالب العرض التي تم إنشاؤها بواسطة التطبيقات وفق معيار OASIS OpenDocument. تعرف على المزيد حول هذا التنسيق هنا. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls) يمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج الجداول الأخرى المشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول هذا التنسيق هنا. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) يمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج الجداول الأخرى المشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول هذا التنسيق هنا. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers يمثل تنسيق ملف ثنائي مشابه لـ Excel. يمكن إنشاء مثل هذه الملفات بواسطة تطبيق Apple Numbers. تعرف على المزيد حول هذا التنسيق هنا. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول هذا التنسيق هنا. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) هو نوع من ملفات الجداول التي تدعم الماكرو. تعرف على المزيد حول هذا التنسيق هنا. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. تعرف على المزيد حول هذا التنسيق هنا. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv) يمثل ملفات نصية عادية تحتوي على سجلات بيانات مفصولة بفواصل. تعرف على المزيد حول هذا التنسيق هنا. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv) يمثل بيانات مفصولة بعلامات جدولة في تنسيق نص عادي. تعرف على المزيد حول هذا التنسيق هنا. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) هو تنسيق مستند جدول OpenDocument يمكن تحريره من قبل المستخدم. يتم تخزين البيانات داخل ملف ODF في صفوف وأعمدة. تعرف على المزيد حول هذا التنسيق هنا. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm) يمثل الملفات التي يتم إنشاؤها بواسطة Microsoft Excel كقوالب مدعومة بالماكرو. ملفات XLTM مشابهة لملفات XLTX في البنية باستثناء أن الأخيرة لا تدعم إنشاء قوالب بملفات ماكرو. تعرف على المزيد حول هذا التنسيق هنا. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Template (.xlt) هي ملفات قالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول يأتي كجزء من مجموعة Microsoft Office. دعم Microsoft Office 97-2003 إنشاء ملفات XLT جديدة وكذلك فتحها. تعرف على المزيد حول هذا التنسيق هنا. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Spreadsheet Template (.xltx) يمثل قالب Microsoft Excel المستند إلى مواصفات تنسيق ملف Office OpenXML. يُستخدم لإنشاء ملف قالب قياسي يمكن استخدامه لتوليد ملفات XLSX التي تتبع نفس الإعدادات المحددة في ملف XLTX. تعرف على المزيد حول هذا التنسيق هنا. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | ملف Microsoft Project (.mpp) هو ملف بيانات Microsoft Project يخزن المعلومات المتعلقة بإدارة المشروع بطريقة متكاملة. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | قالب Microsoft Project (.mpt) يحتوي على معلومات أساسية وبنية بالإضافة إلى إعدادات المستند لإنشاء ملفات .MPP. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | ملف Microsoft Project Exchange (.mpx) هو تنسيق ملف ASCII لنقل معلومات المشروع بين Microsoft Project (MSP) وتطبيقات أخرى تدعم تنسيق MPX مثل Primavera Project Planner وSciforma وTimerline Precision Estimating. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ملف ActionScript (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ملف ActionScript (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | ملف شفرة المصدر بلغة التجميع (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | ملف دفعة DOS (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | ملف شفرة المصدر C/C++ (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | ملف شفرة المصدر C++ (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | ملف CMake (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | ملف شفرة المصدر C++ (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | ملف شفرة المصدر C# (.cs) هو ملف شفرة مصدر للغة البرمجة C#. تم تقديمه من قبل Microsoft للاستخدام مع إطار عمل .NET. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | ملف عنصر مشروع Visual Basic (.vb) هو ملف شفرة مصدر تم إنشاؤه بلغة Visual Basic من قبل Microsoft لتطوير تطبيقات .NET. تعرف على المزيد حول تنسيق الملف هذا هنا. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | ملف Cascading Style Sheet (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | ملف شفرة المصدر C++ (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | ملف تصحيح (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | ملف سكريبت Ruby ERB (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | ملف شفرة المصدر Groovy (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | ملف رأس C/C++/Objective-C (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | ملف شفرة المصدر Haml (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | ملف رأس C++ (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | ملف شفرة المصدر Java (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | ملف JavaScript (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | ملف JavaScript Object Notation (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | ملف LESS Style Sheet (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | ملف سجل (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | ملف تنفيذ Objective-C (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | سكريبت Makefile Xcode (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | ملف توثيق Markdown (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ملف كود مصدر ML (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | ملف مصدر Objective-C++ (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | ملف كود مصدر PHP (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | سكريبت Perl (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | ملف خصائص Java (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | سكريبت Python (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | كود مصدر Ruby (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | ملف reStructuredText (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | ملف Syntactically Awesome StyleSheets (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | ملف كود مصدر Scala (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | ملف كود مصدر Scheme (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | ملف سكريبت عام (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | سكريبت Bash Shell (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | ملف كود مصدر Standard ML (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | ملف بيانات Structured Query Language (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | ملف إعدادات Vim (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | مستند YAML (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | مستند Microsoft Word (.doc) يمثل المستندات التي تم إنشاؤها بواسطة Microsoft Word أو غيرها من مستندات معالجة النصوص بصيغة ملف ثنائي. تعرف على المزيد حول هذا التنسيق هنا. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | مستند Microsoft Word Open XML (.docx) هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه منذ 2007 مع إصدار Microsoft Office 2007، وتم تغيير بنية هذا التنسيق الجديد من ثنائي بسيط إلى مزيج من ملفات XML وملفات ثنائية. تعرف على المزيد حول هذا التنسيق هنا. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | ملف Microsoft Compiled HTML Help (.chm) هو تنسيق معروف لمستندات HELP (توثيق لتطبيق ما). تعرف على المزيد حول هذا التنسيق هنا. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | مستند Word Open XML Macro-Enabled (.docm) هو مستندات Microsoft Word 2007 أو أحدث تم إنشاؤها مع القدرة على تشغيل الماكرو. تعرف على المزيد حول هذا التنسيق هنا. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | قالب مستند Word (.dot) هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتوفير إعدادات مسبقة الصياغة لإنشاء ملفات DOC أو DOCX إضافية. تعرف على المزيد حول هذا التنسيق هنا. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مُنسقة مسبقًا لتوليد ملفات DOCX إضافية. تعرف على المزيد حول هذا التنسيق هنا. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) تمثّل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أحدث. تعرف على المزيد حول هذا التنسيق هنا. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) تمثّل طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. تعرف على المزيد حول هذا التنسيق هنا. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) تمثّل مستند نصي يحتوي على نص عادي على شكل أسطر. تعرف على المزيد حول هذا التنسيق هنا. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة النصوص والتي تعتمد على تنسيق ملف OpenDocument Text. تعرف على المزيد حول هذا التنسيق هنا. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) تمثّل مستندات قالب يتم إنشاؤها بواسطة التطبيقات وفقًا لتنسيق معيار OpenDocument الخاص بـ OASIS. تعرف على المزيد حول هذا التنسيق هنا. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) هو تنسيق ملف رقمي لتخزين معلومات الاتصال. يُستخدم هذا التنسيق على نطاق واسع لتبادل البيانات بين تطبيقات تبادل المعلومات الشائعة. تعرف على المزيد حول هذا التنسيق هنا. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) هو تنسيق ملف للرسومات في Adobe Illustrator. تعرف على المزيد حول هذا التنسيق هنا. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) هو تنسيق ملف لسكربتات وحدات PowerShell. تعرف على المزيد حول هذا التنسيق هنا. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) هو تنسيق ملف لملفات Cmdlet في Windows PowerShell. تعرف على المزيد حول هذا التنسيق هنا. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) هو تنسيق ملف لسكربتات بيان وحدة PowerShell. تعرف على المزيد حول هذا التنسيق هنا. |

### مثال

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# حدد نوع الملف (مثل Markdown) عند تحميل المستند
load_options = LoadOptions(FileType.MD)

# تحويل المستند إلى PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
