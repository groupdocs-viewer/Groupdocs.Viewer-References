---
title: "Clase FileType"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa un tipo de archivo y proporciona métodos para obtener la lista de todos los tipos de archivo compatibles con GroupDocs.Viewer."
type: docs
url: /es/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Representa un tipo de archivo y proporciona métodos para obtener la lista de todos los tipos de archivo compatibles con GroupDocs.Viewer.

El tipo FileType expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Inicializa una nueva instancia de [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Inicializa una nueva instancia de FileType. |

### Métodos
| Método | Descripción |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Detecta la codificación de archivos de texto TXT, TSV y CSV por ruta. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Intenta detectar la codificación de archivos de texto (TXT, TSV, CSV) desde un flujo. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Determina si el [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) actual es el mismo que el [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) especificado. |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Determina si el [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) actual es el mismo que el objeto especificado. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Mapea la extensión de archivo al tipo de archivo. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Extrae la extensión del archivo y la asigna a un tipo de archivo. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Mapea un tipo de medio de archivo a un [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (p.ej., 'application/pdf' se asigna a [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Detecta el tipo de archivo leyendo la firma del archivo. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Detecta el tipo de archivo leyendo la firma del archivo. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Detecta el tipo de archivo leyendo la firma del archivo. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Detecta el tipo de archivo leyendo la firma del archivo. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Devuelve el código hash del objeto [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) actual. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Recupera los tipos de archivo compatibles. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Devuelve una cadena que representa el objeto actual. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | El sufijo del nombre de archivo (incluyendo el punto ".") p.ej. ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | El nombre del tipo de archivo p.ej. "Microsoft Word Document". |

### Campos
| Campo | Descripción |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Representa un tipo de archivo desconocido. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Archivo comprimido (.zip) representa archivos que pueden contener uno o más archivos o directorios. Obtén más información sobre este formato de archivo aquí. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Archivo consolidado Unix (.tar) son archivos creados con una utilidad basada en Unix para recopilar uno o más archivos. Obtén más información sobre este formato de archivo aquí. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | Archivo XZ (.xz) es un archivo comprimido con un algoritmo de compresión de alta relación basado en el algoritmo LZMA. Obtén más información sobre este formato de archivo aquí. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Archivo consolidado Unix (.txz, .tar.xz) son archivos creados con una utilidad basada en Unix para recopilar uno o más archivos. Obtén más información sobre este formato de archivo aquí. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Archivo consolidado Unix (.txz, .tar.xz) son archivos creados con una utilidad basada en Unix para recopilar uno o más archivos. Obtén más información sobre este formato de archivo aquí. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Archivo consolidado Unix (.tgz, .tar.gz) son archivos creados con una utilidad basada en Unix para recopilar uno o más archivos. Obtén más información sobre este formato de archivo aquí. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Archivo consolidado Unix (.tgz, .tar.gz) son archivos creados con una utilidad basada en Unix para recopilar uno o más archivos. Obtén más información sobre este formato de archivo aquí. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Archivo comprimido Bzip2 (.bz2) son archivos comprimidos generados usando el método de compresión de código abierto BZIP2, mayormente en sistemas UNIX o Linux. Obtén más información sobre este formato de archivo aquí. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar) son archivos comprimidos generados usando el método de compresión RAR (WINRAR). Obtén más información sobre este formato de archivo aquí. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz) son archivos comprimidos creados con la aplicación de compresión gzip. Puede contener varios archivos comprimidos y se usa comúnmente en sistemas UNIX y Linux. Obtén más información sobre este formato de archivo aquí. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip) se introdujo como una utilidad gratuita para reemplazar el programa Compress usado en sistemas Unix. Estos archivos pueden abrirse y extraerse con varias aplicaciones, como WinZip, que está disponible tanto para Windows como para MacOS. Obtén más información sobre este formato de archivo aquí. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip) es un archivador de código abierto gratuito con compresión LZMA y LZMA2. Obtén más información sobre este formato de archivo aquí. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio es una utilidad de archivado de archivos general y su formato de archivo asociado. Se instala principalmente en sistemas operativos de computadora tipo Unix. Obtén más información sobre este formato de archivo aquí. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | El archivo ZST es un archivo comprimido que se genera con el algoritmo de compresión Zstandard (zstd). Es un archivo comprimido creado con compresión sin pérdida mediante el algoritmo. Los archivos ZST pueden usarse para comprimir diferentes tipos de archivos, como bases de datos, sistemas de archivos, redes y juegos. Obtén más información sobre este formato de archivo aquí. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | Los archivos TZST (.tar.zst, .tzst) son archivos Zstandard (ZST), que internamente contienen un Archivo Consolidado de Archivos Unix (Tar), creado con una utilidad basada en Unix para recopilar uno o más archivos. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | Los archivos TZST (.tar.zst, .tzst) son archivos Zstandard (ZST), que internamente contienen un Archivo Consolidado de Archivos Unix (Tar), creado con una utilidad basada en Unix para recopilar uno o más archivos. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | La imagen de disco óptico ISO es un archivo de imagen de disco de archivo sin comprimir que representa el contenido de todos los datos en un disco óptico como CD o DVD, basado en el estándar ISO-9660. Obtén más información sobre este formato de archivo aquí. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA o LZH es una utilidad de compresión freeware y su formato de archivo asociado. Obtén más información sobre este formato de archivo aquí. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet (o CAB) es un formato de archivo de archivo para Microsoft Windows. Obtén más información sobre este formato de archivo aquí. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf) es una representación de datos etiquetados de un archivo de dibujo AutoCAD. Obtén más información sobre este formato de archivo aquí. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg) representa archivos binarios propietarios utilizados para contener datos de diseño 2D y 3D. Al igual que DXF, que son archivos ASCII, DWG representa el formato de archivo binario para dibujos CAD (Computer Aided Design). Obtén más información sobre este formato de archivo aquí. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt) es un archivo de plantilla de dibujo AutoCAD que se usa como punto de partida para crear dibujos que pueden guardarse como archivos DWG. Obtén más información sobre este formato de archivo aquí. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl) es un formato de archivo intercambiable que representa la geometría de superficie tridimensional. El formato de archivo se utiliza en varios campos como el prototipado rápido, la impresión 3D y la fabricación asistida por computadora. Obtén más información sobre este formato de archivo aquí. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc) es un formato de archivo que establece normas internacionales para importar y exportar objetos de construcción y sus propiedades. Este formato de archivo proporciona interoperabilidad entre diferentes aplicaciones de software. Obtén más información sobre este formato de archivo aquí. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format File (.dwf) representa dibujos 2D/3D en formato comprimido para ver, revisar o imprimir archivos de diseño. Contiene gráficos y texto como parte de los datos de diseño y reduce el tamaño del archivo gracias a su formato comprimido. Obtén más información sobre este formato de archivo aquí. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx) representa un formato de modelo 3D. Obtén más información sobre este formato de archivo aquí. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx) representa dibujos 2D/3D como documento XPS en formato comprimido para ver, revisar o imprimir archivos de diseño. Contiene gráficos y texto como parte de los datos de diseño y reduce el tamaño del archivo gracias a su formato comprimido. Obtén más información sobre este formato de archivo aquí. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn) son dibujos creados y compatibles con aplicaciones CAD como MicroStation e Intergraph Interactive Graphics Design System. Obtén más información sobre este formato de archivo aquí. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt) es un archivo de trazador vectorial introducido por Autodesk, Inc. y contiene información para un determinado archivo CAD. Los detalles de trazado requieren precisión y exactitud en la producción, y el uso del archivo PLT garantiza esto ya que todas las imágenes se imprimen usando líneas en lugar de puntos. Obtenga más información sobre este formato de archivo aquí. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Archivo de formato común Obtenga más información sobre este formato de archivo aquí. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj) es un archivo de imagen 3D introducido por Wavefront Technologies. Obtenga más información sobre este formato de archivo aquí. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd) son dibujos creados con la aplicación Microsoft Visio para representar una variedad de objetos gráficos y la interconexión entre ellos. Obtenga más información sobre este formato de archivo aquí. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx) representa el formato de archivo de Microsoft Visio introducido a partir de Microsoft Office 2013. Fue desarrollado para reemplazar el formato de archivo binario, .VSD, que es compatible con versiones anteriores de Microsoft Visio. Obtenga más información sobre este formato de archivo aquí. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss) son archivos de plantilla creados con Microsoft Visio 2007 y versiones anteriores. Los archivos de plantilla proporcionan objetos de dibujo que pueden incluirse en un dibujo Visio .VSD. Obtenga más información sobre este formato de archivo aquí. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx) son plantillas de dibujo creadas con Microsoft Visio 2013 y versiones posteriores. El formato de archivo VSSX puede abrirse con Visio 2013 y versiones posteriores. Los archivos Visio son conocidos por representar una variedad de elementos de dibujo como colecciones de formas, conectores, diagramas de flujo, diseños de red, diagramas UML. Obtenga más información sobre este formato de archivo aquí. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm) son archivos de dibujo creados con la aplicación Microsoft Visio que admite macros. Los archivos VSDM son dibujos OPC/XML similares a VSDX, pero también ofrecen la capacidad de ejecutar macros cuando se abre el archivo. Obtenga más información sobre este formato de archivo aquí. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst) son archivos de imagen vectorial creados con Microsoft Visio y actúan como plantilla para crear más archivos. Estos archivos de plantilla están en formato binario y contienen el diseño y la configuración predeterminados que se utilizan para crear nuevos dibujos Visio. Obtenga más información sobre este formato de archivo aquí. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx) son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y versiones posteriores. Estos archivos VSTX proporcionan un punto de partida para crear dibujos Visio, guardados como archivos .VSDX, con diseño y configuraciones predeterminados. Obtenga más información sobre este formato de archivo aquí. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm) son archivos de plantilla creados con Microsoft Visio que admiten macros. A diferencia de los archivos VSDX, los archivos creados a partir de plantillas VSTM pueden ejecutar macros desarrolladas en código Visual Basic for Applications (VBA). Obtenga más información sobre este formato de archivo aquí. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm) son archivos de plantilla de Microsoft Visio que admiten macros. Un archivo VSSM, al abrirse, permite ejecutar las macros para lograr el formato y la ubicación deseados de las formas en un diagrama. Obtenga más información sobre este formato de archivo aquí. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx) se refiere a plantillas que consisten en dibujos y formas utilizados para crear diagramas en Microsoft Visio. Los archivos VSX se guardan en formato XML y fueron compatibles hasta Visio 2013. Obtenga más información sobre este formato de archivo aquí. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx) es una plantilla de dibujo de Microsoft Visio que se guarda en disco en formato XML. La plantilla está diseñada para proporcionar un archivo con configuraciones básicas que pueden usarse para crear múltiples archivos Visio con los mismos ajustes. Obtenga más información sobre este formato de archivo aquí. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw) representa el formato de archivo que especifica los flujos y almacenamientos necesarios para renderizar un dibujo web. Obtenga más información sobre este formato de archivo aquí. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx) representa cualquier dibujo o gráfico creado en Microsoft Visio, pero guardado en formato XML con extensión .VDX. Un archivo XML de dibujo Visio se crea en el software Visio, desarrollado por Microsoft. Obtenga más información sobre este formato de archivo aquí. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | El archivo Open eBook (.epub) es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. El formato se ha vuelto tan común que es compatible con muchos lectores electrónicos y aplicaciones de software. Obtenga más información sobre este formato de archivo aquí. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | El eBook Mobipocket (.mobi) es uno de los formatos de archivo de libro electrónico más utilizados. El formato es una mejora del antiguo formato OEB (Open Ebook Format) y se utilizó como formato propietario para Mobipocket Reader. Obtenga más información sobre este formato de archivo aquí. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | El ebook Amazon Kindle Format 8 (KF8) es el formato de archivo digital desarrollado para dispositivos Amazon Kindle. El formato es una mejora de los archivos AZW más antiguos y se usa en dispositivos Kindle Fire solo con compatibilidad retroactiva con los formatos de archivo ancestrales, es decir, MOBI y AZW. Obtenga más información sobre este formato de archivo aquí. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg) es un formato de archivo utilizado por Microsoft Outlook y Exchange para almacenar mensajes de correo electrónico, contactos, citas u otras tareas. Obtenga más información sobre este formato de archivo aquí. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E-Mail Message (.eml) representa mensajes de correo electrónico guardados usando Outlook y otras aplicaciones relevantes. Casi todos los clientes de correo electrónico admiten este formato de archivo por su cumplimiento con el estándar RFC-822 Internet Message Format. Obtenga más información sobre este formato de archivo aquí. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) Obtenga más información sobre este formato de archivo aquí. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) Obtenga más información sobre este formato de archivo aquí. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx) es implementado y desarrollado por Apple. La aplicación Apple Mail utiliza el formato de archivo EMLX para exportar los correos electrónicos. Obtenga más información sobre este formato de archivo aquí. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst) representa los archivos de almacenamiento personal de Outlook (también llamados Personal Storage Table) que guardan una variedad de información del usuario. Obtenga más información sobre este formato de archivo aquí. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost) representa los datos del buzón del usuario en modo offline en la máquina local tras el registro con Exchange Server usando Microsoft Outlook. Obtenga más información sobre este formato de archivo aquí. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif) representa imágenes rasterizadas destinadas al uso en una variedad de dispositivos que cumplen con este estándar de formato de archivo. Es capaz de describir datos de imagen binaria, en escala de grises, con paleta de colores y a todo color en varios espacios de color. Obtenga más información sobre este formato de archivo aquí. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff) representa imágenes rasterizadas destinadas al uso en una variedad de dispositivos que cumplen con este estándar de formato de archivo. Es capaz de describir datos de imagen binaria, en escala de grises, con paleta de colores y a todo color en varios espacios de color. Obtenga más información sobre este formato de archivo aquí. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG Image (.jpg) es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen resultante, como consecuencia de la compresión, es un compromiso entre el tamaño de almacenamiento y la calidad de la imagen. Obtenga más información sobre este formato de archivo aquí. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG Image (.jpeg) es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen resultante, como consecuencia de la compresión, es un compromiso entre el tamaño de almacenamiento y la calidad de la imagen. Obtenga más información sobre este formato de archivo aquí. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG File Interchange Format (.jfif) es una imagen que se desarrolló para el intercambio rápido entre plataformas. Este formato utiliza compresión JPEG. Obtenga más información sobre este formato de archivo aquí. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png) es un tipo de formato de archivo de imagen rasterizada que utiliza compresión sin pérdida. Este formato de archivo se creó como reemplazo del Graphics Interchange Format (GIF) y no tiene limitaciones de derechos de autor. Obtenga más información sobre este formato de archivo aquí. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format File (.gif) es un tipo de imagen altamente comprimida. Para cada imagen GIF típicamente permite hasta 8 bits por píxel y se permiten hasta 256 colores en toda la imagen. Obtenga más información sobre este formato de archivo aquí. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng) es una extensión del formato PNG que soporta animación. Obtenga más información sobre este formato de archivo aquí. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | El archivo de imagen Bitmap (.bmp) se utiliza para almacenar imágenes digitales bitmap. Estas imágenes son independientes del adaptador gráfico y también se denominan formato de archivo bitmap independiente del dispositivo (DIB). Obtenga más información sobre este formato de archivo aquí. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA) se utiliza para almacenar imágenes digitales bitmap desarrolladas por TRUEVISION. Obtenga más información sobre este formato de archivo aquí. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Los archivos de icono (.ico) son tipos de archivos de imagen utilizados como icono para la representación de una aplicación en Microsoft Windows. Obtenga más información sobre este formato de archivo aquí. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image File (.jp2) es un sistema de codificación de imágenes y un estándar de compresión de imágenes de última generación. Obtenga más información sobre este formato de archivo aquí. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | Archivo de imagen JPEG 2000 (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | Archivo de imagen JPEG 2000 (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | Archivo de imagen JPEG 2000 (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | Secuencia de código JPEG 2000 (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 Code Stream (.j2k) es una imagen que se comprime utilizando compresión por ondículas en lugar de compresión DCT. Obtenga más información sobre este formato de archivo aquí. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | Secuencia de código JPEG 2000 (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Archivo bitmap independiente del dispositivo (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf) representa el Metarchivo de Microsoft Windows (WMF) para almacenar datos de imágenes en formato vectorial y bitmap. Obtenga más información sobre este formato de archivo aquí. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz) representa el Metarchivo de Microsoft Windows (WMF) comprimido en archivo GZIP, para almacenar datos de imágenes en formato vectorial y bitmap. Obtenga más información sobre este formato de archivo aquí. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf) representa imágenes gráficas de forma independiente del dispositivo. Los metarchivos EMF constan de registros de longitud variable en orden cronológico que pueden renderizar la imagen almacenada después de analizarse en cualquier dispositivo de salida. Obtenga más información sobre este formato de archivo aquí. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz) representa imágenes gráficas de forma independiente del dispositivo comprimidas con GZIP. Los metarchivos EMF constan de registros de longitud variable en orden cronológico que pueden renderizar la imagen almacenada después de analizarse en cualquier dispositivo de salida. Obtenga más información sobre este formato de archivo aquí. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP Image (.webp) es un formato de archivo de imagen raster web moderno que se basa en compresión sin pérdida y con pérdida. Proporciona la misma calidad de imagen mientras reduce considerablemente el tamaño de la imagen. Obtenga más información sobre este formato de archivo aquí. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng) es un formato de imagen de cámara digital utilizado para el almacenamiento de archivos RAW. Fue desarrollado por Adobe en septiembre de 2004. Básicamente se creó para la fotografía digital. Obtenga más información sobre este formato de archivo aquí. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr) es un archivo de imagen de dibujo vectorial que se crea de forma nativa con CorelDRAW para almacenar imágenes digitales codificadas y comprimidas. Este tipo de archivo de dibujo contiene texto, líneas, formas, imágenes, colores y efectos para la representación vectorial del contenido de la imagen. Obtenga más información sobre este formato de archivo aquí. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx) es un archivo de imagen de dibujo que puede contener gráficos vectoriales así como gráficos bitmap. Obtenga más información sobre este formato de archivo aquí. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu) es un formato de archivo gráfico destinado a documentos escaneados y libros, especialmente aquellos que contienen una combinación de texto, dibujos, imágenes y fotografías. Obtenga más información sobre este formato de archivo aquí. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm) es un formato de metarchivo gratuito, independiente de la plataforma y estándar internacional para almacenar e intercambiar gráficos vectoriales (2D), gráficos raster y texto. CGM utiliza un enfoque orientado a objetos y muchas funciones para la producción de imágenes. Obtenga más información sobre este formato de archivo aquí. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Documento Printer Command Language (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd) representa el formato de archivo nativo de Adobe Photoshop utilizado para el diseño y desarrollo gráfico. Obtenga más información sobre este formato de archivo aquí. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb) representa el formato de documento grande de Photoshop utilizado para el diseño y desarrollo gráfico. Obtenga más información sobre este formato de archivo aquí. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | La imagen DICOM (.dcm) representa una imagen digital que almacena información médica de los pacientes, como resonancias magnéticas, tomografías computarizadas e imágenes de ultrasonido. Obtenga más información sobre este formato de archivo aquí. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | Archivo PostScript (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | El archivo Encapsulated PostScript (.eps) describe un programa del lenguaje Encapsulated PostScript que define la apariencia de una sola página. Obtenga más información sobre este formato de archivo aquí. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | El archivo OpenDocument Graphic (.odg) es utilizado por la aplicación Draw de Apache OpenOffice para almacenar elementos de dibujo como una imagen vectorial. Obtenga más información sobre este formato de archivo aquí. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | La plantilla Flat XML ODF (.fodg) es utilizada por la aplicación Draw de Apache OpenOffice para almacenar elementos de dibujo como una imagen vectorial. Obtenga más información sobre este formato de archivo aquí. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | El archivo Scalable Vector Graphics (.svg) es un archivo de gráficos vectoriales escalables que utiliza un formato de texto basado en XML para describir la apariencia de una imagen. Obtenga más información sobre este formato de archivo aquí. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | El archivo Scalable Vector Graphics (.svgz) es un archivo de gráficos vectoriales escalables que utiliza un formato de texto basado en XML, comprimido con GZIP, para describir la apariencia de una imagen. Obtenga más información sobre este formato de archivo aquí. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | Plantilla OpenDocument Graphic (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | El archivo Hypertext Markup Language (.htm) es la extensión para páginas web creadas para mostrarse en navegadores. Obtenga más información sobre este formato de archivo aquí. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | El archivo Hypertext Markup Language (.html) es la extensión para páginas web creadas para mostrarse en navegadores. Obtenga más información sobre este formato de archivo aquí. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | Archivo MHTML Web Archive (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | Archivo MIME HTML (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | Archivo XML (.xml). GroupDocs.Viewer tiene un procesador especial para manejar los archivos XML, consulte la documentación. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | El documento OneNote (.one) es creado por la aplicación Microsoft OneNote. OneNote le permite recopilar información usando la aplicación como si estuviera usando su cuaderno de borradores para tomar notas. Obtenga más información sobre este formato de archivo aquí. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | El archivo Portable Document Format (.pdf) es un tipo de documento creado por Adobe en la década de 1990. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otros materiales de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Obtenga más información sobre este formato de archivo aquí. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | El archivo XML Paper Specification (.xps) representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Este formato fue desarrollado por Microsoft como reemplazo del formato de archivo EMF y es similar al formato PDF, pero utiliza XML en el diseño, apariencia e información de impresión de un documento. Obtenga más información sobre este formato de archivo aquí. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | Archivo OpenXPS (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | El documento fuente LaTeX (.tex) es un lenguaje que comprende características de programación y de marcado, utilizado para componer documentos. Obtenga más información sobre este formato de archivo aquí. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | El formato Open Fixed-layout Document (OFD) definido por GB/T 33190-2016 tiene como objetivo reemplazar al PDF en instituciones públicas chinas. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | La presentación PowerPoint (.ppt) representa un archivo PowerPoint que consiste en una colección de diapositivas para mostrarse como presentación. Especifica el formato de archivo binario utilizado por Microsoft PowerPoint 97-2003. Obtenga más información sobre este formato de archivo aquí. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | Las presentaciones PowerPoint Open XML (.pptx) son archivos de presentación creados con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de presentación Open XML de Microsoft PowerPoint. Obtenga más información sobre este formato de archivo aquí. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | La presentación de diapositivas PowerPoint (.pps) se crea usando Microsoft PowerPoint con fines de presentación. La lectura y creación de archivos PPS es compatible con Microsoft PowerPoint 97-2003. Obtenga más información sobre este formato de archivo aquí. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | Los archivos de presentación de diapositivas PowerPoint Open XML (.ppsx) se crean usando Microsoft PowerPoint 2007 y versiones posteriores con fines de presentación. Obtenga más información sobre este formato de archivo aquí. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | La presentación OpenDocument (.odp) representa el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. Obtenga más información sobre este formato de archivo aquí. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | La presentación OpenDocument (.fodp) representa la presentación OpenDocument Flat XML. Obtenga más información sobre este formato de archivo aquí. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint Template (.pot) representa archivos de plantilla de Microsoft PowerPoint creados por versiones de PowerPoint 97-2003. Obtenga más información sobre este formato de archivo aquí. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation son archivos de presentación con macros que se crean con Microsoft PowerPoint 2007 o versiones superiores. Obtenga más información sobre este formato de archivo aquí. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx) representa presentaciones de plantilla de Microsoft PowerPoint que se crean con Microsoft PowerPoint 2007 y posteriores. Obtenga más información sobre este formato de archivo aquí. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) son archivos de plantilla de Microsoft PowerPoint con soporte para macros. Los archivos POTM se crean con PowerPoint 2007 o posterior y contienen configuraciones predeterminadas que pueden usarse para crear más archivos de presentación. Obtenga más información sobre este formato de archivo aquí. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) representa el formato de archivo de presentación de diapositivas con macros creado con Microsoft PowerPoint 2007 o superior. Obtenga más información sobre este formato de archivo aquí. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp) representa archivos de plantilla de presentación creados por aplicaciones en el formato estándar OASIS OpenDocument. Obtenga más información sobre este formato de archivo aquí. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls) representa el formato binario de Excel. Estos archivos pueden ser creados por Microsoft Excel así como por otros programas de hoja de cálculo similares, como OpenOffice Calc o Apple Numbers. Obtenga más información sobre este formato de archivo aquí. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML) representa el formato binario de Excel. Estos archivos pueden ser creados por Microsoft Excel así como por otros programas de hoja de cálculo similares, como OpenOffice Calc o Apple Numbers. Obtenga más información sobre este formato de archivo aquí. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple Numbers representa un formato binario similar a Excel. Estos archivos pueden ser creados por la aplicación Apple Numbers. Obtenga más información sobre este formato de archivo aquí. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx) es un formato bien conocido para documentos de Microsoft Excel que fue introducido por Microsoft con el lanzamiento de Microsoft Office 2007. Obtenga más información sobre este formato de archivo aquí. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) es un tipo de archivo de hoja de cálculo que admite macros. Obtenga más información sobre este formato de archivo aquí. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb) especifica el formato binario de Excel, que es una colección de registros y estructuras que definen el contenido de un libro de Excel. Obtenga más información sobre este formato de archivo aquí. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv) representa archivos de texto plano que contienen registros de datos con valores separados por comas. Obtenga más información sobre este formato de archivo aquí. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv) representa datos separados por tabulaciones en formato de texto plano. Obtenga más información sobre este formato de archivo aquí. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods) corresponde al formato de documento de hoja de cálculo OpenDocument que es editable por el usuario. Los datos se almacenan dentro del archivo ODF en filas y columnas. Obtenga más información sobre este formato de archivo aquí. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm) representa archivos que son generados por Microsoft Excel como plantillas con macros. Los archivos XLTM son similares a XLTX en estructura, salvo que este último no admite crear plantillas con macros. Obtenga más información sobre este formato de archivo aquí. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel Template (.xlt) son archivos de plantilla creados con Microsoft Excel, que es una aplicación de hoja de cálculo incluida en la suite Microsoft Office. Microsoft Office 97-2003 permitía crear nuevos archivos XLT así como abrirlos. Obtenga más información sobre este formato de archivo aquí. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML Spreadsheet Template (.xltx) representa una plantilla de Microsoft Excel basada en las especificaciones del formato de archivo Office OpenXML. Se utiliza para crear un archivo de plantilla estándar que puede emplearse para generar archivos XLSX que presenten la misma configuración especificada en el archivo XLTX. Obtenga más información sobre este formato de archivo aquí. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project File (.mpp) es un archivo de datos de Microsoft Project que almacena información relacionada con la gestión de proyectos de manera integrada. Obtenga más información sobre este formato de archivo aquí. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project Template (.mpt) contiene información básica y estructura junto con la configuración de documentos para crear archivos .MPP. Obtenga más información sobre este formato de archivo aquí. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange file (.mpx) es un formato de archivo ASCII para la transferencia de información de proyectos entre Microsoft Project (MSP) y otras aplicaciones que admiten el formato de archivo MPX, como Primavera Project Planner, Sciforma y Timerline Precision Estimating. Obtenga más información sobre este formato de archivo aquí. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | Archivo ActionScript (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | Archivo ActionScript (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Archivo de código fuente en lenguaje ensamblador (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | Archivo por lotes DOS (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | Archivo de código fuente C/C++ (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | Archivo de código fuente C++ (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | Archivo CMake (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | Archivo de código fuente C++ (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C# Source Code File (.cs) es un archivo de código fuente para el lenguaje de programación C#. Introducido por Microsoft para su uso con el .NET Framework. Obtenga más información sobre este formato de archivo aquí. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic Project Item File (.vb) es un archivo de código fuente creado en el lenguaje Visual Basic que fue desarrollado por Microsoft para la creación de aplicaciones .NET. Obtenga más información sobre este formato de archivo aquí. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Hoja de estilo en cascada (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | Archivo de código fuente C++ (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | Archivo de parche (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Script Ruby ERB (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Archivo de código fuente Groovy (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | Archivo de encabezado C/C++/Objective-C (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Archivo de código fuente Haml (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | Archivo de encabezado C++ (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Archivo de código fuente Java (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | Archivo JavaScript (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | Archivo de notación de objetos JavaScript (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | Hoja de estilo LESS (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | Archivo de registro (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Archivo de implementación Objective-C (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Script Makefile de Xcode (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Archivo de documentación Markdown (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | Archivo de código fuente ML (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Archivo fuente Objective-C++ (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | Archivo de código fuente PHP (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Script Perl (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Archivo de propiedades Java (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Script Python (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Archivo de código fuente Ruby (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | Archivo reStructuredText (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Archivo Syntactically Awesome StyleSheets (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Archivo de código fuente Scala (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Archivo de código fuente Scheme (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | Archivo de script genérico (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Script de shell Bash (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Archivo de código fuente Standard ML (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Archivo de datos Structured Query Language (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Archivo de configuración Vim (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | Documento YAML (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word Document (.doc) representa documentos generados por Microsoft Word u otros documentos de procesamiento de texto en formato binario. Obtenga más información sobre este formato de archivo aquí. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML Document (.docx) es un formato muy conocido para documentos de Microsoft Word. Introducido a partir de 2007 con la publicación de Microsoft Office 2007, la estructura de este nuevo formato de documento cambió de binario simple a una combinación de archivos XML y binarios. Obtenga más información sobre este formato de archivo aquí. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help File (.chm) es un formato muy conocido para documentos HELP (documentación de alguna aplicación). Obtenga más información sobre este formato de archivo aquí. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML Macro-Enabled Document (.docm) es un documento generado por Microsoft Word 2007 o versiones posteriores con la capacidad de ejecutar macros. Obtenga más información sobre este formato de archivo aquí. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word Document Template (.dot) son archivos de plantilla creados por Microsoft Word para disponer de configuraciones preformateadas para la generación de futuros archivos DOC o DOCX. Obtenga más información sobre este formato de archivo aquí. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx) son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOCX. Obtén más información sobre este formato de archivo aquí. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm) representa un archivo de plantilla creado con Microsoft Word 2007 o superior. Obtén más información sobre este formato de archivo aquí. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf) representa un método de codificación de texto formateado y gráficos para su uso en aplicaciones. Obtén más información sobre este formato de archivo aquí. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt) representa un documento de texto que contiene texto plano en forma de líneas. Obtén más información sobre este formato de archivo aquí. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt) es un tipo de documento creado con aplicaciones de procesamiento de texto que se basan en el formato OpenDocument Text File. Obtén más información sobre este formato de archivo aquí. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott) representa documentos de plantilla generados por aplicaciones que cumplen con el formato estándar OpenDocument de OASIS. Obtén más información sobre este formato de archivo aquí. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf) es un formato de archivo digital para almacenar información de contactos. El formato se utiliza ampliamente para el intercambio de datos entre aplicaciones populares de intercambio de información. Obtén más información sobre este formato de archivo aquí. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai) es un formato de archivo para dibujos de Adobe Illustrator. Obtén más información sobre este formato de archivo aquí. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1) es un formato de archivo para scripts de módulos de PowerShell. Obtén más información sobre este formato de archivo aquí. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1) es un formato de archivo para archivos Cmdlet de Windows PowerShell. Obtén más información sobre este formato de archivo aquí. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1) es un formato de archivo para scripts de manifiesto de módulos de PowerShell. Obtén más información sobre este formato de archivo aquí. |

### Ejemplo

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Especifica el tipo de archivo (p. ej., Markdown) al cargar el documento
load_options = LoadOptions(FileType.MD)

# Renderiza el documento a PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Ver también
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
