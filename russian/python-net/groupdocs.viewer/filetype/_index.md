---
title: "Класс FileType"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет тип файла и предоставляет методы для получения списка всех типов файлов, поддерживаемых GroupDocs.Viewer."
type: docs
url: /ru/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Представляет тип файла и предоставляет методы для получения списка всех типов файлов, поддерживаемых GroupDocs.Viewer.

Тип FileType раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Инициализирует новый экземпляр [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Инициализирует новый экземпляр FileType. |

### Методы
| Метод | Описание |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Определяет кодировку текстовых файлов TXT, TSV и CSV по пути. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Пытается определить кодировку текстовых файлов (TXT, TSV, CSV) из потока. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Определяет, является ли текущий [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) тем же, что указанный [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Определяет, является ли текущий [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) тем же, что указанный объект. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Отображает расширение файла в тип файла. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Извлекает расширение файла и отображает его в тип файла. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Отображает тип медиа файла в [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (например, 'application/pdf' отображается в [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Определяет тип файла, читая сигнатуру файла. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Определяет тип файла, читая сигнатуру файла. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Определяет тип файла, читая сигнатуру файла. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Определяет тип файла, читая сигнатуру файла. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Возвращает хеш-код для текущего объекта [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Получает поддерживаемые типы файлов. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Возвращает строку, представляющую текущий объект. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Суффикс имени файла (включая точку ".") например ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | Имя типа файла, например "Microsoft Word Document". |

### Поля
| Поле | Описание |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Представляет неизвестный тип файла. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Сжатый файл (.zip) представляет архивы, которые могут содержать один или несколько файлов или каталогов. Узнайте больше об этом формате файла здесь. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Объединённый Unix-архив (.tar) — это архивы, созданные с помощью утилиты Unix для сбора одного или нескольких файлов. Узнайте больше об этом формате файла здесь. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | Файл XZ (.xz) — это архив, сжатый алгоритмом высокой степени сжатия, основанным на алгоритме LZMA. Узнайте больше об этом формате файла здесь. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Объединённый Unix-архив (.txz, .tar.xz) — это архивы, созданные с помощью утилиты Unix для сбора одного или нескольких файлов. Узнайте больше об этом формате файла здесь. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Объединённый Unix-архив (.txz, .tar.xz) — это архивы, созданные с помощью утилиты Unix для сбора одного или нескольких файлов. Узнайте больше об этом формате файла здесь. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Объединённый Unix-архив (.tgz, .tar.gz) — это архивы, созданные с помощью утилиты Unix для сбора одного или нескольких файлов. Узнайте больше об этом формате файла здесь. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Объединённый Unix-архив (.tgz, .tar.gz) — это архивы, созданные с помощью утилиты Unix для сбора одного или нескольких файлов. Узнайте больше об этом формате файла здесь. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Сжатый файл Bzip2 (.bz2) — это сжатые файлы, созданные с использованием открытого метода сжатия BZIP2, в основном в системах UNIX или Linux. Узнайте больше об этом формате файла здесь. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) — это сжатые файлы, создаваемые с использованием метода сжатия RAR (WINRAR). Узнайте больше о этом формате файла здесь. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) — это сжатые файлы, созданные с помощью приложения gzip. Они могут содержать несколько сжатых файлов и обычно используются в системах UNIX и Linux. Узнайте больше о этом формате файла здесь. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) был представлен как бесплатная утилита, заменяющая программу Compress, используемую в Unix‑системах. Такие файлы можно открыть и извлечь с помощью различных приложений, например WinZip, доступного как для Windows, так и для macOS. Узнайте больше о этом формате файла здесь. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) — это бесплатный архиватор с открытым исходным кодом, использующий сжатие LZMA и LZMA2. Узнайте больше о этом формате файла здесь. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio — это универсальная утилита архивирования файлов и связанный с ней формат. Она в основном устанавливается в Unix‑подобных операционных системах. Узнайте больше о этом формате файла здесь. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST‑файл — это сжатый файл, созданный с помощью алгоритма сжатия Zstandard (zstd). Это сжатый файл, полученный без потерь благодаря этому алгоритму. ZST‑файлы могут использоваться для сжатия различных типов файлов, таких как базы данных, файловые системы, сети и игры. Узнайте больше о этом формате файла здесь. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST‑файлы (.tar.zst, .tzst) представляют собой архивы Zstandard (ZST), которые внутри содержат объединённый Unix‑архив (Tar), созданный с помощью Unix‑утилиты для сбора одного или нескольких файлов. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST‑файлы (.tar.zst, .tzst) представляют собой архивы Zstandard (ZST), которые внутри содержат объединённый Unix‑архив (Tar), созданный с помощью Unix‑утилиты для сбора одного или нескольких файлов. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO‑образ оптического диска — это не сжатый образ диска‑архива, представляющий содержимое всех данных на оптическом диске, таком как CD или DVD, основанный на стандарте ISO‑9660. Узнайте больше о этом формате файла здесь. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA или LZH — это бесплатная утилита сжатия и связанный с ней формат файлов. Узнайте больше о этом формате файла здесь. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (или CAB) — это формат архивных файлов для Microsoft Windows. Узнайте больше о этом формате файла здесь. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) — это тегированное представление данных файла чертежа AutoCAD. Узнайте больше о этом формате файла здесь. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) представляет собой проприетарные бинарные файлы, используемые для хранения 2‑D и 3‑D данных дизайна. Как и DXF, который является ASCII‑файлом, DWG представляет бинарный формат файлов для чертежей CAD (Computer Aided Design). Узнайте больше о этом формате файла здесь. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt) — это шаблон чертежа AutoCAD, используемый в качестве отправной точки для создания чертежей, которые могут быть сохранены как DWG‑файлы. Узнайте больше о этом формате файла здесь. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl) — это взаимозаменяемый формат файлов, представляющий трехмерную поверхность. Этот формат используется в различных областях, таких как быстрое прототипирование, 3D‑печать и компьютерное производство. Узнайте больше о этом формате файла здесь. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc) — это формат файлов, устанавливающий международные стандарты импорта и экспорта строительных объектов и их свойств. Этот формат обеспечивает совместимость между различными программными приложениями. Узнайте больше о этом формате файла здесь. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format File (.dwf) представляет 2‑D/3‑D чертеж в сжатом формате для просмотра, рецензирования или печати файлов дизайна. Он содержит графику и текст как часть данных дизайна и уменьшает размер файла благодаря сжатому формату. Узнайте больше о этом формате файла здесь. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) представляет формат 3‑D модели. Узнайте больше о этом формате файла здесь. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) представляет 2‑D/3‑D чертеж в виде XPS‑документа в сжатом формате для просмотра, рецензирования или печати файлов дизайна. Он содержит графику и текст как часть данных дизайна и уменьшает размер файла благодаря сжатому формату. Узнайте больше о этом формате файла здесь. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) — это чертежи, создаваемые и поддерживаемые CAD‑приложениями, такими как MicroStation и Intergraph Interactive Graphics Design System. Узнайте больше о этом формате файла здесь. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) — это векторный файл плоттера, представленный компанией Autodesk, Inc., и содержащий информацию для определённого CAD‑файла. Детали построения требуют точности и аккуратности в производстве, а использование файла PLT гарантирует это, поскольку все изображения печатаются линиями, а не точками. Узнайте больше о этом формате файла здесь. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Общий файловый формат Файл. Узнайте больше о этом формате файла здесь. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) — это 3D‑файл изображения, представленный компанией Wavefront Technologies. Узнайте больше о этом формате файла здесь. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) — это чертежи, созданные с помощью приложения Microsoft Visio для представления разнообразных графических объектов и их взаимосвязей. Узнайте больше о этом формате файла здесь. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) представляет файловый формат Microsoft Visio, представленный, начиная с Microsoft Office 2013. Он был разработан для замены бинарного формата .VSD, поддерживаемого более ранними версиями Microsoft Visio. Узнайте больше о этом формате файла здесь. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File (.vss) — это файлы шаблонов, созданные в Microsoft Visio 2007 и более ранних версиях. Файлы шаблонов предоставляют объекты чертежа, которые могут быть включены в чертёж Visio формата .VSD. Узнайте больше о этом формате файла здесь. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) — это шаблоны чертежей, созданные в Microsoft Visio 2013 и более новых версиях. Формат файла VSSX можно открыть в Visio 2013 и выше. Файлы Visio известны представлением разнообразных элементов чертежа, таких как набор фигур, соединителей, блок‑схем, сетевых схем, UML‑диаграмм. Узнайте больше о этом формате файла здесь. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) — это файлы чертежей, созданные в приложении Microsoft Visio с поддержкой макросов. Файлы VSDM являются OPC/XML‑чертежами, похожими на VSDX, но также предоставляют возможность выполнять макросы при открытии файла. Узнайте больше о этом формате файла здесь. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) — это векторные файлы изображений, созданные в Microsoft Visio и служащие шаблонами для создания последующих файлов. Эти шаблонные файлы находятся в бинарном формате и содержат макет и настройки по умолчанию, используемые при создании новых чертежей Visio. Узнайте больше о этом формате файла здесь. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) — это файлы шаблонов чертежей, созданные в Microsoft Visio 2013 и более новых версиях. Эти файлы VSTX предоставляют отправную точку для создания чертежей Visio, сохраняемых как файлы .VSDX, с макетом и настройками по умолчанию. Узнайте больше о этом формате файла здесь. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) — это шаблонные файлы, созданные в Microsoft Visio с поддержкой макросов. В отличие от файлов VSDX, файлы, созданные из шаблонов VSTM, могут выполнять макросы, разработанные на языке Visual Basic for Applications (VBA). Узнайте больше о этом формате файла здесь. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) — это файлы шаблонов Microsoft Visio, поддерживающие макросы. При открытии файла VSSM можно выполнять макросы для достижения требуемого форматирования и размещения фигур в диаграмме. Узнайте больше о этом формате файла здесь. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) относится к шаблонам, состоящим из чертежей и фигур, используемых для создания диаграмм в Microsoft Visio. Файлы VSX сохраняются в формате XML и поддерживались до Visio 2013. Узнайте больше о этом формате файла здесь. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) — это шаблон чертежа Microsoft Visio, сохраняемый на диск в формате XML. Шаблон предназначен для предоставления файла с базовыми настройками, которые можно использовать для создания нескольких файлов Visio с одинаковыми параметрами. Узнайте больше о этом формате файла здесь. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) представляет файловый формат, определяющий потоки и хранилища, необходимые для отображения веб‑чертежа. Узнайте больше о этом формате файла здесь. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) представляет любой чертеж или схему, созданные в Microsoft Visio, но сохранённые в формате XML с расширением .VDX. Файл XML‑чертежа Visio создаётся в программном обеспечении Visio, разработанном Microsoft. Узнайте больше о этом формате файла здесь. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub) — это формат электронных книг, который предоставляет стандартный цифровой формат публикаций для издателей и потребителей. Формат стал настолько распространённым, что его поддерживают многие электронные читалки и программные приложения. Узнайте больше об этом формате файла здесь. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi) — один из наиболее широко используемых форматов файлов электронных книг. Этот формат является улучшением старого формата OEB (Open Ebook Format) и использовался как проприетарный формат для Mobipocket Reader. Узнайте больше об этом формате файла здесь. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) ebook — цифровой файловый формат, разработанный для устройств Amazon Kindle. Этот формат является улучшением более старых файлов AZW и используется на устройствах Kindle Fire только с обратной совместимостью с предшествующими форматами, то есть MOBI и AZW. Узнайте больше об этом формате файла здесь. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) — файловый формат, используемый Microsoft Outlook и Exchange для хранения электронных сообщений, контактов, встреч или других задач. Узнайте больше об этом формате файла здесь. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E-Mail Message (.eml) представляет собой электронные сообщения, сохранённые с помощью Outlook и других соответствующих приложений. Практически все почтовые клиенты поддерживают этот формат файла благодаря его соответствию стандарту RFC‑822 Internet Message Format. Узнайте больше об этом формате файла здесь. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) Узнайте больше об этом формате файла здесь. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) Узнайте больше об этом формате файла здесь. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx) реализован и разработан компанией Apple. Приложение Apple Mail использует формат файлов EMLX для экспорта электронных писем. Узнайте больше об этом формате файла здесь. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst) представляет собой файлы Outlook Personal Storage (также называемые Personal Storage Table), которые хранят разнообразную пользовательскую информацию. Узнайте больше об этом формате файла здесь. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost) представляет данные почтового ящика пользователя в автономном режиме на локальном компьютере после регистрации на сервере Exchange с использованием Microsoft Outlook. Узнайте больше об этом формате файла здесь. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файлов. Он способен описывать двухуровневые, градации серого, палитровые и полноцветные данные изображений в нескольких цветовых пространствах. Узнайте больше об этом формате файла здесь. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) представляет растровые изображения, предназначенные для использования на различных устройствах, соответствующих этому стандарту формата файлов. Он способен описывать двухуровневые, градации серого, палитровые и полноцветные данные изображений в нескольких цветовых пространствах. Узнайте больше об этом формате файла здесь. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG Image (.jpg) — тип графического формата, сохраняемый с помощью метода сжатия с потерями. Получаемое изображение в результате сжатия представляет собой компромисс между размером файла и качеством изображения. Узнайте больше об этом формате файла здесь. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG Image (.jpeg) — тип графического формата, сохраняемый с помощью метода сжатия с потерями. Получаемое изображение в результате сжатия представляет собой компромисс между размером файла и качеством изображения. Узнайте больше об этом формате файла здесь. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif) — изображение, разработанное для быстрой передачи между платформами. Этот формат использует JPEG‑сжатие. Узнайте больше об этом формате файла здесь. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png) — тип растрового графического формата, использующий без потерь сжатие. Этот формат был создан как замена Graphics Interchange Format (GIF) и не имеет ограничений по авторским правам. Узнайте больше об этом формате файла здесь. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format File (.gif) — тип сильно сжатого изображения. Для каждого изображения GIF обычно допускает до 8 бит на пиксель и до 256 цветов по всему изображению. Узнайте больше об этом формате файла здесь. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng) — расширение формата PNG, поддерживающее анимацию. Узнайте больше об этом формате файла здесь. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Файл растрового изображения (.bmp) используется для хранения цифровых растровых изображений. Эти изображения независимы от графического адаптера и также называются форматом файла device independent bitmap (DIB). Узнайте больше об этом формате файла здесь. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) используется для хранения цифровых растровых изображений, разработанных компанией TRUEVISION. Узнайте больше об этом формате файла здесь. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Файлы значков (.ico) — типы файлов изображений, используемые в качестве иконок для представления приложения в Microsoft Windows. Узнайте больше об этом формате файла здесь. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image File (.jp2) — система кодирования изображений и современный стандарт сжатия изображений. Узнайте больше об этом формате файла здесь. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | Файл изображения JPEG 2000 (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | Файл изображения JPEG 2000 (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | Файл изображения JPEG 2000 (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | Поток кода JPEG 2000 (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | Поток кода JPEG 2000 (.j2k) — изображение, сжатое с использованием вейвлетного сжатия вместо DCT‑сжатия. Узнайте больше об этом формате файла здесь. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | Поток кода JPEG 2000 (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | Формат JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Файл Device Independent Bitmap (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) представляет Microsoft Windows Metafile (WMF) для хранения данных векторных и растровых изображений. Узнайте больше об этом формате файла здесь. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) представляет Microsoft Windows Metafile (WMF), сжатый в архиве GZIP, для хранения данных векторных и растровых изображений. Узнайте больше об этом формате файла здесь. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) представляет графические изображения независимо от устройства. Метафайлы EMF состоят из переменной длины записей в хронологическом порядке, которые могут отобразить сохранённое изображение после разбора на любом выводном устройстве. Узнайте больше об этом формате файла здесь. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz) представляет графические изображения, независимо от устройства, сжатые с помощью GZIP. Метафайлы EMF состоят из переменной длины записей в хронологическом порядке, которые могут отобразить сохранённое изображение после разбора на любом выводном устройстве. Узнайте больше об этом формате файла здесь. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp) — современный растровый веб‑формат изображения, основанный на без потерь и с потерями сжатии. Он обеспечивает такое же качество изображения при значительном уменьшении его размера. Узнайте больше об этом формате файла здесь. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng) — формат изображения цифровой камеры, используемый для хранения RAW‑файлов. Он был разработан компанией Adobe в сентябре 2004 года. По сути, он создан для цифровой фотографии. Узнайте больше об этом формате файла здесь. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) — векторный файл рисунка, изначально созданный в CorelDRAW для хранения цифрового изображения в закодированном и сжатом виде. Такой файл рисунка содержит текст, линии, формы, изображения, цвета и эффекты для векторного представления содержимого изображения. Узнайте больше об этом формате файла здесь. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) — файл рисунка, который может содержать как векторную, так и растровую графику. Узнайте больше об этом формате файла здесь. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) — графический формат файлов, предназначенный для отсканированных документов и книг, особенно тех, которые содержат комбинацию текста, рисунков, изображений и фотографий. Узнайте больше об этом формате файла здесь. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) — бесплатный, независимый от платформы, международный стандартный формат метафайла для хранения и обмена векторной графикой (2D), растровой графикой и текстом. CGM использует объектно‑ориентированный подход и множество функциональных возможностей для создания изображений. Узнайте больше об этом формате файла здесь. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Документ Printer Command Language (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) представляет собственный формат файла Adobe Photoshop, используемый для разработки и создания графики. Узнайте больше об этом формате файла здесь. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) представляет формат Photoshop Large Document, используемый для разработки и создания графики. Узнайте больше об этом формате файла здесь. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | Изображение DICOM (.dcm) представляет собой цифровое изображение, которое хранит медицинскую информацию о пациентах, такую как МРТ, КТ‑сканы и ультразвуковые изображения. Узнайте больше о этом формате файла здесь. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | Файл PostScript (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Файл Encapsulated PostScript (.eps) описывает программу языка Encapsulated PostScript, которая определяет внешний вид одной страницы. Узнайте больше о этом формате файла здесь. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | Файл OpenDocument Graphic (.odg) используется приложением Draw из Apache OpenOffice для хранения элементов рисунка в виде векторного изображения. Узнайте больше о этом формате файла здесь. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Шаблон Flat XML ODF (.fodg) используется приложением Draw из Apache OpenOffice для хранения элементов рисунка в виде векторного изображения. Узнайте больше о этом формате файла здесь. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Файл Scalable Vector Graphics (.svg) — это файл Scalable Vector Graphics, который использует основанный на XML текстовый формат для описания внешнего вида изображения. Узнайте больше о этом формате файла здесь. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Файл Scalable Vector Graphics (.svgz) — это файл Scalable Vector Graphics, который использует основанный на XML текстовый формат, сжатый с помощью GZIP, для описания внешнего вида изображения. Узнайте больше о этом формате файла здесь. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | Шаблон OpenDocument Graphic (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Файл Hypertext Markup Language (.htm) — это расширение для веб‑страниц, созданных для отображения в браузерах. Узнайте больше о этом формате файла здесь. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Файл Hypertext Markup Language (.html) — это расширение для веб‑страниц, созданных для отображения в браузерах. Узнайте больше о этом формате файла здесь. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | Веб‑архив MHTML (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | Файл MIME HTML (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | Файл XML (.xml). GroupDocs.Viewer имеет специальный процессор для обработки файлов XML, см. документацию. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | Документ OneNote (.one) создаётся приложением Microsoft OneNote. OneNote позволяет собирать информацию, используя приложение, как если бы вы использовали черновик для записи заметок. Узнайте больше о этом формате файла здесь. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Файл Portable Document Format (.pdf) — это тип документа, созданный Adobe в 1990‑х годах. Цель этого формата файла заключалась в введении стандарта представления документов и других справочных материалов в формате, независимом от прикладного программного обеспечения, аппаратного обеспечения и операционной системы. Узнайте больше о этом формате файла здесь. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | Файл XML Paper Specification (.xps) представляет файлы разметки страниц, основанные на XML Paper Specification, созданной Microsoft. Этот формат был разработан Microsoft как замена формата EMF и похож на формат PDF, но использует XML для описания разметки, внешнего вида и печатной информации документа. Узнайте больше о этом формате файла здесь. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | Файл OpenXPS (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | Исходный документ LaTeX (.tex) — это язык, включающий программные и разметочные возможности, используемый для наборa документов. Узнайте больше о этом формате файла здесь. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Формат Open Fixed-layout Document (OFD), определённый GB/T 33190-2016, направлен на замену PDF в китайских государственных учреждениях. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | Презентация PowerPoint (.ppt) представляет файл PowerPoint, содержащий набор слайдов для отображения в виде слайд‑шоу. Он определяет бинарный формат файла, используемый Microsoft PowerPoint 97‑2003. Узнайте больше о этом формате файла здесь. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | Презентация PowerPoint Open XML (.pptx) — это файлы презентаций, созданные популярным приложением Microsoft PowerPoint. В отличие от предыдущей версии формата PPT, который был бинарным, формат PPTX основан на открытом XML‑формате презентаций Microsoft PowerPoint. Узнайте больше о этом формате файла здесь. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | Слайд‑шоу PowerPoint (.pps) создаётся с помощью Microsoft PowerPoint для целей показа слайдов. Чтение и создание файлов PPS поддерживается Microsoft PowerPoint 97‑2003. Узнайте больше о этом формате файла здесь. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | Слайд‑шоу PowerPoint Open XML (.ppsx) создаётся с помощью Microsoft PowerPoint 2007 и более новых версий для целей показа слайдов. Узнайте больше о этом формате файла здесь. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | Презентация OpenDocument (.odp) представляет формат файлов презентаций, используемый OpenOffice.org в стандарте OASISOpen. Узнайте больше о этом формате файла здесь. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | Презентация OpenDocument (.fodp) представляет собой OpenDocument Flat XML Presentation. Узнайте больше о этом формате файла здесь. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint Template (.pot) представляет файлы шаблонов Microsoft PowerPoint, созданные в версиях PowerPoint 97‑2003. Узнайте больше об этом формате файла здесь. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation — это файлы презентаций с поддержкой макросов, созданные в Microsoft PowerPoint 2007 или более новых версиях. Узнайте больше об этом формате файла здесь. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx) представляет шаблоны презентаций Microsoft PowerPoint, созданные в Microsoft PowerPoint 2007 и новее. Узнайте больше об этом формате файла здесь. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) — это файлы шаблонов Microsoft PowerPoint с поддержкой макросов. Файлы POTM создаются в PowerPoint 2007 или новее и содержат настройки по умолчанию, которые можно использовать для создания дальнейших файлов презентаций. Узнайте больше об этом формате файла здесь. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) представляет формат файлов слайд‑шоу с поддержкой макросов, созданный в Microsoft PowerPoint 2007 или новее. Узнайте больше об этом формате файла здесь. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp) представляет файлы шаблонов презентаций, созданные приложениями в стандарте OASIS OpenDocument. Узнайте больше об этом формате файла здесь. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls) представляет двоичный формат файлов Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла здесь. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) представляет двоичный формат файлов Excel. Такие файлы могут быть созданы Microsoft Excel, а также другими аналогичными программами для работы с таблицами, такими как OpenOffice Calc или Apple Numbers. Узнайте больше об этом формате файла здесь. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers представляет двоичный формат файлов, похожий на Excel. Такие файлы могут быть созданы приложением Apple Numbers. Узнайте больше об этом формате файла здесь. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) — это известный формат документов Microsoft Excel, представленный Microsoft в выпуске Microsoft Office 2007. Узнайте больше об этом формате файла здесь. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) — это тип файлов электронных таблиц, поддерживающих макросы. Узнайте больше об этом формате файла здесь. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) определяет двоичный формат файлов Excel, который представляет собой набор записей и структур, описывающих содержимое рабочей книги Excel. Узнайте больше об этом формате файла здесь. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv) представляет текстовые файлы, содержащие записи данных со значениями, разделёнными запятыми. Узнайте больше об этом формате файла здесь. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv) представляет данные, разделённые табуляциями, в текстовом формате. Узнайте больше об этом формате файла здесь. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) обозначает формат документа OpenDocument Spreadsheet, который может редактироваться пользователем. Данные хранятся в файле ODF в виде строк и столбцов. Узнайте больше об этом формате файла здесь. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm) представляет файлы, генерируемые Microsoft Excel как шаблоны с поддержкой макросов. Файлы XLTM похожи на XLTX по структуре, за исключением того, что последние не поддерживают создание шаблонов с макросами. Узнайте больше об этом формате файла здесь. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Template (.xlt) — это файлы шаблонов, созданные в Microsoft Excel, который является приложением для работы с электронными таблицами и входит в состав пакета Microsoft Office. Microsoft Office 97‑2003 поддерживал создание новых файлов XLT, а также их открытие. Узнайте больше об этом формате файла здесь. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Spreadsheet Template (.xltx) представляет шаблоны Microsoft Excel, основанные на спецификациях формата Office OpenXML. Он используется для создания стандартного файла шаблона, который может быть использован для генерации файлов XLSX с теми же настройками, указанными в файле XLTX. Узнайте больше об этом формате файла здесь. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Файл Microsoft Project (.mpp) — это файл данных Microsoft Project, который хранит информацию, связанную с управлением проектами, в интегрированном виде. Узнайте больше о этом формате файла здесь. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Шаблон Microsoft Project (.mpt) содержит базовую информацию и структуру, а также настройки документа для создания файлов .MPP. Узнайте больше о этом формате файла здесь. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Файл Microsoft Project Exchange (.mpx) — это формат ASCII‑файла для передачи информации о проектах между Microsoft Project (MSP) и другими приложениями, поддерживающими формат MPX, такими как Primavera Project Planner, Sciforma и Timerline Precision Estimating. Узнайте больше о этом формате файла здесь. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | Файл ActionScript (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | Файл ActionScript (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Файл исходного кода на ассемблере (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | Пакетный файл DOS (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | Файл исходного кода C/C++ (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | Файл исходного кода C++ (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | Файл CMake (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | Файл исходного кода C++ (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | Файл исходного кода C# (.cs) — это файл исходного кода для языка программирования C#. Был введён Microsoft для использования с .NET Framework. Узнайте больше о этом формате файла здесь. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Файл элемента проекта Visual Basic (.vb) — это файл исходного кода, созданный на языке Visual Basic, разработанный Microsoft для разработки приложений .NET. Узнайте больше о этом формате файла здесь. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Файл каскадных таблиц стилей (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | Файл исходного кода C++ (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | Файл патча (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Скрипт Ruby ERB (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Файл исходного кода Groovy (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | Файл заголовка C/C++/Objective-C (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Файл исходного кода Haml (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | Файл заголовка C++ (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Файл исходного кода Java (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | Файл JavaScript (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | Файл JavaScript Object Notation (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | Файл таблицы стилей LESS (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | Файл журнала (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Файл реализации Objective-C (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Скрипт Makefile Xcode (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Файл документации Markdown (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | Файл исходного кода ML (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Файл исходного кода Objective-C++ (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | Файл исходного кода PHP (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Скрипт Perl (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Файл свойств Java (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Скрипт Python (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Файл исходного кода Ruby (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | Файл reStructuredText (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Файл Syntactically Awesome StyleSheets (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Файл исходного кода Scala (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Файл исходного кода Scheme (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | Файл общего скрипта (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Скрипт оболочки Bash (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Файл исходного кода Standard ML (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Файл данных Structured Query Language (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Файл настроек Vim (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | Документ YAML (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Документ Microsoft Word (.doc) представляет документы, созданные Microsoft Word или другими текстовыми процессорами, в бинарном файловом формате. Узнайте больше о этом формате файла здесь. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Документ Microsoft Word Open XML (.docx) — известный формат документов Microsoft Word. Появился в 2007 году с выпуском Microsoft Office 2007, структура этого нового формата документа была изменена с обычного бинарного на комбинацию XML и бинарных файлов. Узнайте больше о этом формате файла здесь. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Скомпилированный файл справки Microsoft HTML Help (.chm) — известный формат для HELP (документация к некоторому приложению) документов. Узнайте больше о этом формате файла здесь. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Документ Word Open XML с поддержкой макросов (.docm) — документ, созданный Microsoft Word 2007 или более поздних версий, с возможностью выполнения макросов. Узнайте больше о этом формате файла здесь. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Шаблон документа Word (.dot) — это файлы шаблонов, созданные Microsoft Word, содержащие предварительно отформатированные настройки для создания последующих файлов DOC или DOCX. Узнайте больше о этом формате файла здесь. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) — это шаблонные файлы, созданные Microsoft Word, содержащие предварительно отформатированные настройки для создания дальнейших файлов DOCX. Узнайте больше о этом формате файла здесь. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) представляет шаблонный файл, созданный в Microsoft Word 2007 или более новой версии. Узнайте больше о этом формате файла здесь. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) представляет метод кодирования форматированного текста и графики для использования в приложениях. Узнайте больше о этом формате файла здесь. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) представляет текстовый документ, содержащий обычный текст в виде строк. Узнайте больше о этом формате файла здесь. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) — это тип документов, создаваемых с помощью текстовых процессоров, основанных на формате OpenDocument Text File. Узнайте больше о этом формате файла здесь. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) представляет шаблонные документы, генерируемые приложениями в соответствии со стандартным форматом OASIS OpenDocument. Узнайте больше о этом формате файла здесь. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) — это цифровой формат файла для хранения контактной информации. Формат широко используется для обмена данными между популярными приложениями обмена информацией. Узнайте больше о этом формате файла здесь. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) — это формат файла для рисунков Adobe Illustrator. Узнайте больше о этом формате файла здесь. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) — это формат файла для скриптов модулей PowerShell. Узнайте больше о этом формате файла здесь. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) — это формат файла для файлов Cmdlet Windows PowerShell. Узнайте больше о этом формате файла здесь. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) — это формат файла для скриптов манифеста модуля PowerShell. Узнайте больше о этом формате файла здесь. |

### Пример

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Укажите тип файла (например, Markdown) при загрузке документа
load_options = LoadOptions(FileType.MD)

# Преобразовать документ в PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
