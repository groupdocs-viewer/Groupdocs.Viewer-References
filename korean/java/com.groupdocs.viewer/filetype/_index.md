---
title: "FileType"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "파일 유형을 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

파일 유형을 나타냅니다. GroupDocs.Viewer 구성 요소에서 지원하는 모든 파일 유형 목록을 얻기 위한 메서드를 제공합니다.


FileType 열거형은 GroupDocs.Viewer 구성 요소에서 지원하는 다양한 파일 유형을 나타내는 상수를 제공합니다.
이 열거형의 메서드를 사용하여 지원되는 모든 파일 유형 목록을 얻거나 특정 파일 유형이 지원되는지 확인할 수 있습니다.


사용 예시:

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


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [UNKNOWN](#UNKNOWN) | 알 수 없는 파일 유형을 나타냅니다. |
|
|  | [ZIP](#ZIP) | 하나 이상의 파일이나 디렉터리를 포함할 수 있는 압축 파일(.zip)을 나타냅니다. |
|
|  | [TAR](#TAR) | 하나 이상의 파일을 수집하기 위해 만든 통합 Unix 파일 아카이브(.tar)를 나타냅니다. |
|
|  | [XZ](#XZ) | LZMA 알고리즘을 기반으로 한 고비율 압축 알고리즘으로 압축된 XZ 파일(.xz)을 나타냅니다. |
|
|  | [TXZ](#TXZ) | 하나 이상의 파일을 수집하기 위해 생성된 통합 Unix 파일 아카이브(.txz, .tar.xz)를 나타냅니다. |
|
|  | [TARXZ](#TARXZ) | 하나 이상의 파일을 수집하기 위해 생성된 통합 Unix 파일 아카이브(.txz, .tar.xz)를 나타냅니다. |
|
|  | [TGZ](#TGZ) | 하나 이상의 파일을 수집하기 위해 생성된 통합 Unix 파일 아카이브(.tgz, .tar.gz)를 나타냅니다. |
|
|  | [TARGZ](#TARGZ) | 하나 이상의 파일을 수집하기 위해 생성된 통합 Unix 파일 아카이브(.tgz, .tar.gz)를 나타냅니다. |
|
|  | [BZ_2](#BZ-2) | BZIP2 오픈소스 압축 방식을 사용하여 생성된 Bzip2 압축 파일(.bz2)을 나타냅니다. |
|
|  | [RAR](#RAR) | RAR (WINRAR 버전 4) 압축 방식을 사용하여 생성된 Roshal Archive(.rar) 압축 파일을 나타냅니다. |
|
|  | [GZ](#GZ) | gzip 압축 애플리케이션으로 생성된 Gnu Zipped File(.gz) 압축 파일을 나타냅니다. |
|
|  | [GZIP](#GZIP) | Unix 시스템에서 사용되는 Compress 프로그램을 대체하기 위해 도입된 무료 유틸리티인 Gnu Zipped File(.gzip) 압축 파일을 나타냅니다. |
|
|  | [SEVEN_ZIP](#SEVEN-ZIP) | LZMA 및 LZMA2 압축을 지원하는 무료 오픈소스 압축 프로그램인 7Zip(.7z, .7zip) 파일을 나타냅니다. |
|
|  | [CPIO](#CPIO) | Cpio는 일반 파일 아카이버 유틸리티 및 해당 파일 형식입니다. |
|
|  | [ZSTANDARD](#ZSTANDARD) | Zstandard(zstd) 압축 알고리즘으로 생성된 압축 파일인 ZST 파일입니다. |
|
|  | [TZST](#TZST) | TZST 파일(.tar.zst, .tzst)은 Zstandard 아카이브(ZST)이며, 내부에 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 통합 Unix 파일 아카이브(Tar)를 포함합니다. |
|
|  | [TAR_ZST](#TAR-ZST) | TZST 파일(.tar.zst, .tzst)은 Zstandard 아카이브(ZST)이며, 내부에 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 통합 Unix 파일 아카이브(Tar)를 포함합니다. |
|
|  | [ISO](#ISO) | ISO 광디스크 이미지는 CD 또는 DVD와 같은 광디스크의 전체 데이터를 나타내는 압축되지 않은 아카이브 디스크 이미지 파일이며, ISO-9660 표준을 기반으로 합니다. |
|
|  | [LHA](#LHA) | LHA 또는 LZH는 무료 압축 유틸리티 및 해당 파일 형식입니다. |
|
|  | [CAB](#CAB) | Cabinet(또는 CAB)은 Microsoft Windows용 아카이브 파일 형식입니다. |
|
|  | [DXF](#DXF) | AutoCAD 도면 파일의 태그된 데이터 표현인 Drawing Exchange Format File(.dxf)을 나타냅니다. |
|
|  | [DWG](#DWG) | AutoCAD Drawing Database File(.dwg)은 2D 및 3D 설계 데이터를 포함하는 데 사용되는 독점 바이너리 파일을 나타냅니다. |
|
|  | [DWT](#DWT) | DWG 파일로 저장할 수 있는 도면을 만들기 위한 시작 파일인 AutoCAD Drawing Template(.dwt) 파일을 나타냅니다. |
|
|  | [STL](#STL) | 3차원 표면 기하학을 나타내는 교환 가능한 파일 형식인 Stereolithography File(.stl)을 나타냅니다. |
|
|  | [IFC](#IFC) | 건축 객체 및 속성의 수입·수출을 위한 국제 표준을 설정하는 파일 형식인 Industry Foundation Classes File(.ifc)을 나타냅니다. |
|
|  | [DWF](#DWF) | 2D/3D 도면을 보기, 검토 또는 인쇄하기 위한 압축 파일 형식인 Design Web Format File(.dwf)을 나타냅니다. |
|
|  | [FBX](#FBX) | 3D 모델 형식인 Autodesk FBX Interchange File(FilmBoX)(.fbx)을 나타냅니다. |
|
|  | [DWFX](#DWFX) | 2D/3D 도면을 XPS 문서로 보기, 검토 또는 인쇄하기 위한 압축 형식인 Design Web Format File XPS(.dwfx)를 나타냅니다. |
|
|  | [DGN](#DGN) | MicroStation 및 Intergraph Interactive Graphics Design System과 같은 CAD 애플리케이션에서 생성 및 지원되는 도면인 MicroStation Design File(.dgn)을 나타냅니다. |
|
|  | [PLT](#PLT) | Autodesk, Inc.에서 도입한 벡터 기반 플로터 파일인 PLT(HPGL) File(.plt)을 나타냅니다. |
|
|  | [CF2](#CF2) | Common File Format File(.cf2)을 나타냅니다. |
|
|  | [OBJ](#OBJ) | Wavefront Technologies에서 도입한 3D 이미지 파일인 Wavefront 3D Object File(.obj)을 나타냅니다. |
|
|  | [HPG](#HPG) | PLT (HPGL) 파일 (.hpg)을 나타냅니다. |
|
|  | [IGS](#IGS) | 초기 그래픽 교환 사양 (IGES) 파일 (.igs)을 나타냅니다. |
|
|  | [VSD](#VSD) | Visio 도면 파일 (.vsd)을 나타내며, 이는 Microsoft Visio 애플리케이션으로 만든 다양한 그래픽 객체와 그 상호 연결을 나타내는 도면입니다. |
|
|  | [VSDX](#VSDX) | Visio 도면 파일 (.vsdx)을 나타내며, 이는 Microsoft Office 2013 이후부터 도입된 Microsoft Visio 파일 형식입니다. |
|
|  | [VSS](#VSS) | Visio 스텐실 파일 (.vss)을 나타내며, 이는 Microsoft Visio 2007 이전 버전으로 만든 스텐실 파일입니다. |
|
|  | [VSSX](#VSSX) | Visio 스텐실 파일 (.vssx)을 나타내며, 이는 Microsoft Visio 2013 이후 버전으로 만든 도면 스텐실입니다. |
|
|  | [VSDM](#VSDM) | Visio 매크로 사용 가능 도면 (.vsdm)을 나타내며, 이는 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 도면 파일입니다. |
|
|  | [VST](#VST) | Visio 도면 템플릿 (.vst)을 나타내며, 이는 Microsoft Visio로 만든 벡터 이미지 파일입니다. |
|
|  | [VSTX](#VSTX) | Visio 도면 템플릿 (.vstx)을 나타내며, 이는 Microsoft Visio 2013 이후 버전으로 만든 도면 템플릿 파일입니다. |
|
|  | [VSTM](#VSTM) | Visio 매크로 사용 가능 도면 템플릿 (.vstm)을 나타내며, 이는 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. |
|
|  | [VSSM](#VSSM) | Visio 매크로 사용 가능 스텐실 파일 (.vssm)을 나타내며, 이는 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. |
|
|  | [VSX](#VSX) | Visio 스텐실 XML 파일 (.vsx)을 나타내며, 이는 Microsoft Visio에서 다이어그램을 만들 때 사용되는 도면 및 도형으로 구성된 스텐실을 의미합니다. |
|
|  | [VTX](#VTX) | Visio 템플릿 XML 파일 (.vtx)을 나타내며, 이는 XML 파일 형식으로 디스크에 저장된 Microsoft Visio 도면 템플릿입니다. |
|
|  | [VDW](#VDW) | Visio 웹 도면 (.vdw)을 나타내며, 이는 웹 도면을 렌더링하는 데 필요한 스트림 및 스토리지를 지정합니다. |
|
|  | [VDX](#VDX) | Visio 도면 XML 파일 (.vdx)을 나타내며, 이는 Microsoft Visio에서 만든 모든 도면 또는 차트를 .VDX 확장자를 가진 XML 형식으로 저장한 것을 의미합니다. |
|
|  | [EPUB](#EPUB) | Open eBook 파일 (.epub)을 나타내며, 이는 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. |
|
|  | [MOBI](#MOBI) | Mobipocket 전자책 (.mobi)을 나타내며, 이는 가장 널리 사용되는 전자책 파일 형식 중 하나입니다. |
|
|  | [AZW_3](#AZW-3) | Amazon Kindle Format 8 (KF8) 전자책은 Amazon Kindle 기기를 위해 개발된 디지털 파일 형식입니다. |
|
|  | [MSG](#MSG) | Outlook 메일 메시지 (.msg)를 나타내며, 이는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용하는 파일 형식입니다. |
|
|  | [EML](#EML) | 이메일 메시지 (.eml)를 나타내며, 이는 Outlook 및 기타 관련 애플리케이션을 사용해 저장된 이메일 메시지를 의미합니다. |
|
|  | [EMLX](#EMLX) | Apple 메일 메시지 (.emlx)를 나타내며, 이는 Apple에서 구현 및 개발한 것입니다. |
|
|  | [PST](#PST) | Outlook 개인 정보 저장 파일 (.pst)를 나타내며, 이는 다양한 사용자 정보를 저장하는 Outlook 개인 저장 파일(또는 Personal Storage Table)입니다. |
|
|  | [OST](#OST) | Outlook 오프라인 데이터 파일 (.ost)를 나타내며, 이는 Microsoft Outlook을 사용해 Exchange Server에 등록할 때 로컬 머신에서 오프라인 모드로 사용자의 사서함 데이터를 저장합니다. |
|
|  | [TIF](#TIF) | 태그된 이미지 파일 (.tif)을 나타내며, 이는 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 의미합니다. |
|
|  | [TIFF](#TIFF) | 태그된 이미지 파일 형식 (.tiff)을 나타내며, 이는 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 의미합니다. |
|
|  | [JPG](#JPG) | JPEG 이미지 (.jpg)를 나타내며, 손실 압축 방식을 사용하여 저장되는 이미지 형식의 일종입니다. |
|
|  | [JPEG](#JPEG) | JPEG 이미지 (.jpeg)를 나타내며, 손실 압축 방식을 사용하여 저장되는 이미지 형식의 일종입니다. |
|
|  | [JFIF](#JFIF) | JPEG 파일 교환 형식 (.jfif)은 플랫폼 간 빠른 교환을 위해 개발된 이미지입니다. |
|
|  | [PNG](#PNG) | Portable Network Graphic (.png)를 나타내며, 무손실 압축을 사용하는 래스터 이미지 파일 형식의 일종입니다. |
|
|  | [GIF](#GIF) | Graphical Interchange Format 파일 (.gif)을 나타내며, 고도로 압축된 이미지의 일종입니다. |
|
|  | [APNG](#APNG) | Animated Portable Network Graphic (.apng)를 나타내며, 애니메이션을 지원하는 PNG 형식의 확장입니다. |
|
|  | [BMP](#BMP) | Bitmap 이미지 파일 (.bmp)를 나타내며, 비트맵 디지털 이미지를 저장하는 데 사용됩니다. |
|
|  | [ICO](#ICO) | Icon 파일 (.ico)를 나타내며, Microsoft Windows에서 애플리케이션을 나타내는 아이콘으로 사용되는 이미지 파일 형식입니다. |
|
|  | [TGA](#TGA) | Truevision TGA (TARGA) 파일을 나타내며, TRUEVISION에서 개발한 비트맵 디지털 이미지를 저장하는 데 사용됩니다. |
|
|  | [JP_2](#JP-2) | JPEG 2000 Core Image 파일 (.jp2)를 나타내며, 이미지 코딩 시스템 및 최첨단 이미지 압축 표준입니다. |
|
|  | [JPF](#JPF) | JPEG 2000 이미지 파일 (.jpf)를 나타냅니다. |
|
|  | [JPX](#JPX) | JPEG 2000 이미지 파일 (.jpx)를 나타냅니다. |
|
|  | [JPM](#JPM) | JPEG 2000 이미지 파일 (.jpm)를 나타냅니다. |
|
|  | [J2C](#J2C) | JPEG 2000 코드 InputStream (.j2c)를 나타냅니다. |
|
|  | [J2K](#J2K) | JPEG 2000 코드 스트림 (.j2k)를 나타내며, DCT 압축 대신 웨이브릿 압축을 사용한 이미지입니다. |
|
|  | [JPC](#JPC) | JPEG 2000 코드 스트림 (.jpc)를 나타냅니다. |
|
|  | [JLS](#JLS) | JPEG-LS (JLS) 파일 (.jls)를 나타냅니다. |
|
|  | [DIB](#DIB) | Device Independent Bitmap 파일 (.dib)를 나타냅니다. |
|
|  | [WMF](#WMF) | Windows Metafile (.wmf)를 나타내며, 벡터와 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows Metafile (WMF)을 의미합니다. |
|
|  | [WMZ](#WMZ) | Compressed Windows Metafile (.wmz)를 나타내며, 벡터와 비트맵 형식 이미지 데이터를 저장하기 위해 GZIP 아카이브로 압축된 Microsoft Windows Metafile (WMF)을 의미합니다. |
|
|  | [EMF](#EMF) | Enhanced Windows Metafile (.emf)를 나타내며, 장치에 독립적인 그래픽 이미지를 의미합니다. |
|
|  | [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz)를 나타내며, GZIP으로 압축된 장치 독립적인 그래픽 이미지를 의미합니다. |
|
|  | [WEBP](#WEBP) | WebP 이미지 (.webp)를 나타내며, 무손실 및 손실 압축을 기반으로 하는 현대적인 래스터 웹 이미지 파일 형식입니다. |
|
|  | [DNG](#DNG) | Digital Negative Specification (.dng)를 나타내며, RAW 파일 저장에 사용되는 디지털 카메라 이미지 형식입니다. |
|
|  | [CDR](#CDR) | CorelDraw Vector Graphic Drawing (.cdr)를 나타내며, 디지털 인코딩 및 압축된 이미지를 저장하기 위해 CorelDRAW로 기본 생성된 벡터 드로잉 이미지 파일입니다. |
|
|  | [CMX](#CMX) | Corel Exchange (.cmx)를 나타내며, 이는 벡터 그래픽과 비트맵 그래픽을 모두 포함할 수 있는 그림 이미지 파일입니다. |
|
|  | [DJVU](#DJVU) | DjVu Image (.djvu)를 나타내며, 이는 스캔한 문서와 책을 위해 설계된 그래픽 파일 형식으로, 특히 텍스트, 그림, 이미지 및 사진이 결합된 경우에 사용됩니다. |
|
|  | [CGM](#CGM) | Computer Graphics Metafile (.cgm)를 나타내며, 이는 벡터 그래픽(2D), 래스터 그래픽 및 텍스트를 저장하고 교환하기 위한 무료이며 플랫폼에 독립적인 국제 표준 메타파일 형식입니다. |
|
|  | [PCL](#PCL) | Printer Command Language Document (.pcl)를 나타냅니다. |
|
|  | [PSD](#PSD) | Adobe Photoshop Document (.psd)를 나타내며, 이는 그래픽 디자인 및 개발에 사용되는 Adobe Photoshop의 기본 파일 형식입니다. |
|
|  | [PSB](#PSB) | Photoshop Large Document Format (.psb)를 나타내며, 이는 Adobe Photoshop에서 그래픽 디자인 및 개발에 사용됩니다. |
|
|  | [DCM](#DCM) | DICOM Image (.dcm)를 나타내며, 이는 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지를 의미합니다. |
|
|  | [PS](#PS) | PostScript File (.ps)를 나타냅니다. |
|
|  | [EPS](#EPS) | Encapsulated PostScript File (.eps)를 나타내며, 이는 단일 페이지의 외관을 정의하는 Encapsulated PostScript 언어 프로그램을 설명합니다. |
|
|  | [ODG](#ODG) | OpenDocument Graphic File (.odg)를 나타내며, 이는 Apache OpenOffice의 Draw 애플리케이션에서 그림 요소를 벡터 이미지로 저장하는 데 사용됩니다. |
|
|  | [FODG](#FODG) | Flat XML ODF Template (.fodg)를 나타내며, 이는 Apache OpenOffice의 Draw 애플리케이션에서 그림 요소를 벡터 이미지로 저장하는 데 사용됩니다. |
|
|  | [SVG](#SVG) | Scalable Vector Graphics File (.svg)를 나타내며, 이는 이미지의 외관을 설명하기 위해 XML 기반 텍스트 형식을 사용하는 Scalable Vector Graphics 파일입니다. |
|
|  | [SVGZ](#SVGZ) | Compressed Scalable Vector Graphics File (.svgz)를 나타내며, 이는 XML 기반 텍스트 형식을 사용하고 GZIP으로 압축된 Scalable Vector Graphics 파일로 이미지의 외관을 설명합니다. |
|
|  | [OTG](#OTG) | OpenDocument Graphic Template (.otg)를 나타냅니다. |
|
|  | [HTM](#HTM) | Hypertext Markup Language File (.htm)를 나타내며, 이는 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. |
|
|  | [HTML](#HTML) | Hypertext Markup Language File (.html)를 나타내며, 이는 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. |
|
|  | [MHT](#MHT) | MHTML Web Archive (.mht)를 나타냅니다. |
|
|  | [NSF](#NSF) | Lotus Notes Database (.nsf)를 나타냅니다. |
|
|  | [MBOX](#MBOX) | Email Mailbox File (.mbox)를 나타냅니다. |
|
|  | [MHTML](#MHTML) | MIME HTML File (.mhtml)를 나타냅니다. |
|
|  | [XML](#XML) | XML File (.xml)를 나타냅니다. |
|
|  | [ONE](#ONE) | Microsoft OneNote 애플리케이션에서 만든 OneNote Document (.one)를 나타냅니다. |
|
|  | [PDF](#PDF) | Portable Document Format File (.pdf)를 나타내며, 이는 1990년대에 Adobe가 만든 문서 유형입니다. |
|
|  | [XPS](#XPS) | XML Paper Specification File (.xps)를 나타내며, 이는 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 의미합니다. |
|
|  | [OXPS](#OXPS) | OpenXPS File (.oxps)를 나타냅니다. |
|
|  | [TEX](#TEX) | LaTeX 소스 문서(.tex)를 나타내며, 이는 문서를 조판하는 데 사용되는 프로그래밍과 마크업 기능을 모두 포함하는 언어입니다. |
|
|  | [OFD](#OFD) | GB/T 33190-2016에서 정의된 오픈 고정 레이아웃 문서(OFD) 형식은 중국 공공 기관에서 PDF를 대체하는 것을 목표로 합니다. |
|
|  | [PPT](#PPT) | PowerPoint 프레젠테이션(.ppt)을 나타내며, 이는 슬라이드 모음으로 구성되어 슬라이드쇼로 표시되는 PowerPoint 파일을 의미합니다. |
|
|  | [PPTX](#PPTX) | PowerPoint Open XML 프레젠테이션(.pptx)을 나타내며, 이는 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. |
|
|  | [PPS](#PPS) | PowerPoint 슬라이드 쇼(.pps)를 나타내며, 이는 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용해 생성됩니다. |
|
|  | [PPSX](#PPSX) | PowerPoint Open XML 슬라이드 쇼(.ppsx) 파일을 나타내며, 이는 Microsoft PowerPoint 2007 이상을 사용해 슬라이드 쇼 용도로 생성됩니다. |
|
|  | [ODP](#ODP) | OpenDocument 프레젠테이션(.odp)을 나타내며, 이는 OASIS Open 표준에서 OpenOffice.org가 사용하는 프레젠테이션 파일 형식입니다. |
|
|  | [FODP](#FODP) | OpenDocument 프레젠테이션(.fodp)을 나타내며, 이는 OpenDocument 플랫 XML 프레젠테이션을 의미합니다. |
|
|  | [POT](#POT) | PowerPoint 템플릿(.pot)을 나타내며, 이는 PowerPoint 97-2003 버전으로 만든 Microsoft PowerPoint 템플릿 파일을 의미합니다. |
|
|  | [PPTM](#PPTM) | PowerPoint Open XML 매크로 사용 프레젠테이션(.pptm)을 나타내며, 이는 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 사용 프레젠테이션 파일입니다. |
|
|  | [POTX](#POTX) | PowerPoint Open XML 프레젠테이션 템플릿(.potx)을 나타내며, 이는 Microsoft PowerPoint 2007 이상으로 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 의미합니다. |
|
|  | [POTM](#POTM) | PowerPoint Open XML 매크로 사용 프레젠테이션 템플릿(.potm)을 나타내며, 이는 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. |
|
|  | [PPSM](#PPSM) | PowerPoint Open XML 매크로 사용 슬라이드(.ppsm)를 나타내며, 이는 Microsoft PowerPoint 2007 이상으로 만든 매크로 사용 슬라이드 쇼 파일 형식입니다. |
|
|  | [OTP](#OTP) | OpenDocument 프레젠테이션 템플릿(.otp)을 나타내며, 이는 OASIS OpenDocument 표준 형식의 애플리케이션으로 만든 프레젠테이션 템플릿 파일을 의미합니다. |
|
|  | [XLS](#XLS) | Excel 스프레드시트(.xls)를 나타내며, 이는 Excel 바이너리 파일 형식을 의미합니다. |
|
|  | [EXCEL_2003_XML](#EXCEL-2003-XML) | Excel 2003 XML(SpreadsheetML)(.xml)을 나타내며, 이는 Excel 바이너리 파일 형식을 의미합니다. |
|
|  | [NUMBERS](#NUMBERS) | Apple Numbers(.numbers)를 나타내며, 이는 Excel과 유사한 바이너리 파일 형식을 의미합니다. |
|
|  | [XLSX](#XLSX) | Microsoft Excel Open XML 스프레드시트(.xlsx)를 나타내며, 이는 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 Microsoft Excel 문서의 잘 알려진 형식입니다. |
|
|  | [XLSM](#XLSM) | Excel Open XML 매크로 사용 스프레드시트(.xlsm)를 나타내며, 이는 매크로를 지원하는 스프레드시트 파일 유형입니다. |
|
|  | [XLSB](#XLSB) | Excel 바이너리 스프레드시트(.xlsb)를 나타내며, 이는 Excel 바이너리 파일 형식을 지정합니다. |
|
|  | [CSV](#CSV) | 콤마 구분 값 파일(.csv)을 나타내며, 이는 쉼표로 구분된 값으로 데이터 레코드를 포함하는 일반 텍스트 파일을 의미합니다. |
|
|  | [TSV](#TSV) | 탭 구분 값 파일(.tsv)을 나타내며, 이는 탭으로 구분된 데이터를 일반 텍스트 형식으로 포함합니다. |
|
|  | [ODS](#ODS) | OpenDocument 스프레드시트(.ods)를 나타내며, 이는 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 의미합니다. |
|
|  | [FODS](#FODS) | OpenDocument 플랫 XML 스프레드시트(.fods)를 나타냅니다. |
|
|  | [OTS](#OTS) | OpenDocument 스프레드시트 템플릿(.ots)를 나타냅니다. |
|
|  | [XLAM](#XLAM) | Microsoft Excel 추가 기능(.xlam)을 나타냅니다. |
|
|  | [XLTM](#XLTM) | Microsoft Excel 매크로 사용 템플릿(.xltm)을 나타내며, 이는 Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 의미합니다. |
|
|  | [XLT](#XLT) | Microsoft Excel 템플릿(.xlt)을 나타내며, 이는 Microsoft Office 제품군에 포함된 스프레드시트 애플리케이션인 Microsoft Excel로 만든 템플릿 파일입니다. |
|
|  | [XLTX](#XLTX) | Excel Open XML 스프레드시트 템플릿(.xltx)을 나타내며, 이는 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 의미합니다. |
|
|  | [SXC](#SXC) | StarOffice Calc 스프레드시트(.sxc)를 나타냅니다. |
|
|  | [MPP](#MPP) | Microsoft Project 파일(.mpp)을 나타내며, 이는 프로젝트 관리와 관련된 정보를 통합 방식으로 저장하는 Microsoft Project 데이터 파일입니다. |
|
|  | [MPT](#MPT) | Microsoft Project 템플릿(.mpt)을 나타내며, 이는 .MPP 파일을 만들기 위한 기본 정보와 구조 및 문서 설정을 포함합니다. |
|
|  | [MPX](#MPX) | Microsoft Project Exchange 파일(.mpx)을 나타내며, 이는 Microsoft Project(MSP)와 MPX 파일 형식을 지원하는 Primavera Project Planner, Sciforma, Timerline Precision Estimating과 같은 다른 애플리케이션 간에 프로젝트 정보를 전송하기 위한 ASCII 파일 형식입니다. |
|
|  | [AS](#AS) | ActionScript 파일(.as)을 나타냅니다. |
|
|  | [AS_3](#AS-3) | ActionScript 파일(.as3)을 나타냅니다. |
|
|  | [ASM](#ASM) | 어셈블리 언어 소스 코드 파일(.asm)을 나타냅니다. |
|
|  | [BAT](#BAT) | DOS 배치 파일(.bat)을 나타냅니다. |
|
|  | [C](#C) | C/C++ 소스 코드 파일(.c)을 나타냅니다. |
|
|  | [CC](#CC) | C++ 소스 코드 파일(.cc)을 나타냅니다. |
|
|  | [CMAKE](#CMAKE) | CMake 파일(.cmake)을 나타냅니다. |
|
|  | [CPP](#CPP) | C++ 소스 코드 파일(.cpp)을 나타냅니다. |
|
|  | [CS](#CS) | C# 소스 코드 파일(.cs)을 나타내며, 이는 C# 프로그래밍 언어용 소스 코드 파일입니다. |
|
|  | [VB](#VB) | Visual Basic 프로젝트 항목 파일(.vb)을 나타내며, 이는 Visual Basic 언어로 만든 소스 코드 파일입니다. |
|
|  | [CSS](#CSS) | Cascading Style Sheet(.css) 파일을 나타냅니다. |
|
|  | [CXX](#CXX) | C++ 소스 코드 파일(.cxx)을 나타냅니다. |
|
|  | [DIFF](#DIFF) | 패치 파일(.diff)을 나타냅니다. |
|
|  | [ERB](#ERB) | Ruby ERB 스크립트(.erb)를 나타냅니다. |
|
|  | [GROOVY](#GROOVY) | Groovy 소스 코드 파일(.groovy)을 나타냅니다. |
|
|  | [H](#H) | C/C++/Objective-C 헤더 파일(.h)을 나타냅니다. |
|
|  | [HAML](#HAML) | Haml 소스 코드 파일(.haml)을 나타냅니다. |
|
|  | [HH](#HH) | C++ 헤더 파일 (.hh)을 나타냅니다. |
|
|  | [JAVA](#JAVA) | Java 소스 코드 파일 (.java)을 나타냅니다. |
|
|  | [JS](#JS) | JavaScript 파일 (.js)을 나타냅니다. |
|
|  | [JSON](#JSON) | JavaScript 객체 표기법 파일 (.json)을 나타냅니다. |
|
|  | [LESS](#LESS) | LESS 스타일 시트 (.less) 파일을 나타냅니다. |
|
|  | [LOG](#LOG) | 로그 파일 (.log)을 나타냅니다. |
|
|  | [M](#M) | Objective-C 구현 파일 (.m)을 나타냅니다. |
|
|  | [MAKE](#MAKE) | Xcode 메이크파일 스크립트 (.make)를 나타냅니다. |
|
|  | [MD](#MD) | Markdown 문서 파일 (.md)을 나타냅니다. |
|
|  | [ML](#ML) | ML 소스 코드 파일 (.ml)을 나타냅니다. |
|
|  | [MM](#MM) | Objective-C++ 소스 파일 (.mm)을 나타냅니다. |
|
|  | [PHP](#PHP) | PHP 소스 코드 파일 (.php)을 나타냅니다. |
|
|  | [PL](#PL) | Perl 스크립트 (.pl)를 나타냅니다. |
|
|  | [PROPERTIES](#PROPERTIES) | Java 속성 파일 (.properties)을 나타냅니다. |
|
|  | [PY](#PY) | Python 스크립트 (.py)를 나타냅니다. |
|
|  | [RB](#RB) | Ruby 소스 코드 (.rb) 파일을 나타냅니다. |
|
|  | [RST](#RST) | reStructuredText 파일 (.rst)을 나타냅니다. |
|
|  | [SASS](#SASS) | Syntactically Awesome StyleSheets 파일 (.sass)을 나타냅니다. |
|
|  | [SCALA](#SCALA) | Scala 소스 코드 파일 (.scala)을 나타냅니다. |
|
|  | [SCM](#SCM) | Scheme 소스 코드 파일 (.scm)을 나타냅니다. |
|
|  | [SCRIPT](#SCRIPT) | 일반 스크립트 파일 (.script)을 나타냅니다. |
|
|  | [SH](#SH) | Bash 셸 스크립트 (.sh)를 나타냅니다. |
|
|  | [SML](#SML) | Standard ML 소스 코드 파일 (.sml)을 나타냅니다. |
|
|  | [SQL](#SQL) | Structured Query Language 데이터 파일 (.sql)을 나타냅니다. |
|
|  | [VIM](#VIM) | Vim 설정 파일 (.vim)을 나타냅니다. |
|
|  | [YAML](#YAML) | YAML 문서 (.yaml)를 나타냅니다. |
|
|  | [DOC](#DOC) | Microsoft Word 문서 (.doc) 파일을 나타냅니다. |
|
|  | [DOCX](#DOCX) | Microsoft Word Open XML 문서 (.docx) 파일을 나타냅니다. |
|
|  | [CHM](#CHM) | Microsoft 컴파일된 HTML 도움말 파일 (.chm)을 나타냅니다. |
|
|  | [DOCM](#DOCM) | Word Open XML 매크로 사용 문서 (.docm) 파일을 나타냅니다. |
|
|  | [DOT](#DOT) | Word 문서 템플릿 (.dot) 파일을 나타냅니다. |
|
|  | [DOTX](#DOTX) | Word Open XML 문서 템플릿 (.dotx) 파일을 나타냅니다. |
|
|  | [DOTM](#DOTM) | Word Open XML 매크로 사용 문서 템플릿 (.dotm) 파일을 나타냅니다. |
|
|  | [RTF](#RTF) | Rich Text Format 파일 (.rtf)을 나타냅니다. |
|
|  | [TXT](#TXT) | 일반 텍스트 파일 (.txt)을 나타냅니다. |
|
|  | [ODT](#ODT) | OpenDocument 텍스트 문서 (.odt)를 나타냅니다. |
|
|  | [OTT](#OTT) | OpenDocument 문서 템플릿 (.ott)을 나타냅니다. |
|
|  | [VCF](#VCF) | vCard 파일 (.vcf)을 나타내며, 이는 연락처 정보를 저장하기 위한 디지털 파일 형식입니다. |
|
|  | [AI](#AI) | Adobe Illustrator 파일 (.ai)을 나타내며, 이는 Adobe Illustrator 그림을 위한 파일 형식입니다. |
|
|  | [PSM1](#PSM1) | PowerShell 스크립트 모듈 파일 (.psm1)을 나타냅니다. |
|
|  | [PS1](#PS1) | PowerShell 스크립트 파일 (.ps1)을 나타냅니다. |
|
|  | [PSD1](#PSD1) | PowerShell 스크립트 모듈 매니페스트 파일 (.psd1)을 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | 파일 확장자를 파일 유형에 매핑합니다. |
|
|  | [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | 파일 이름 또는 파일 경로에서 파일 확장자를 추출하고 이를 파일 유형에 매핑합니다. |
|
|  | [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | 파일 미디어 유형을 파일 유형에 매핑합니다. |
|
|  | [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 파일 서명을 읽어 파일 유형을 감지합니다. |
|
|  | [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | 파일 서명을 읽어 파일 유형을 감지합니다. |
|
|  | [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | 파일 서명을 읽어 파일 유형을 감지합니다. |
|
|  | [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | 파일 서명을 읽어 파일 유형을 감지합니다. |
|
|  | [getSupportedFileTypes()](#getSupportedFileTypes--) | 지원되는 파일 유형을 검색합니다. |
|
|  | [detectCharset(String filePath)](#detectCharset-java.lang.String-) | 경로를 통해 텍스트 [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), 및 [CSV](../../com.groupdocs.viewer/filetype#CSV) 파일의 문자 집합을 감지하려 시도합니다. |
|
|  | [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | 스트림을 통해 텍스트 [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), 및 [CSV](../../com.groupdocs.viewer/filetype#CSV) 파일의 문자 집합을 감지하려 시도합니다. |
|
|  | [getFileFormat()](#getFileFormat--) | 파일 형식의 이름을 가져옵니다. 예: "Microsoft Word Document". |
|
|  | [getExtension()](#getExtension--) | 파일 확장자 접미사(마침표 "." 포함)를 가져옵니다. 예: ".doc". |
|
|  | [toString()](#toString--) | 현재 객체의 문자열 표현을 반환합니다. |
|
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


알 수 없는 파일 유형을 나타냅니다.


### ZIP {#ZIP}
```
public static final FileType ZIP
```


하나 이상의 파일이나 디렉터리를 포함할 수 있는 압축 파일(.zip)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/compression/zip)를 클릭하세요.


### TAR {#TAR}
```
public static final FileType TAR
```


하나 이상의 파일을 수집하기 위해 만든 통합 Unix 파일 아카이브(.tar)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/compression/tar)를 클릭하세요.


### XZ {#XZ}
```
public static final FileType XZ
```


LZMA 알고리즘을 기반으로 한 고비율 압축 알고리즘으로 압축된 XZ 파일(.xz)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/xz)를 클릭하세요.


### TXZ {#TXZ}
```
public static final FileType TXZ
```


하나 이상의 파일을 수집하기 위해 생성된 통합 Unix 파일 아카이브(.txz, .tar.xz)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/txz)를 클릭하세요.


### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


하나 이상의 파일을 수집하기 위해 생성된 통합 Unix 파일 아카이브(.txz, .tar.xz)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/txz)를 클릭하세요.


### TGZ {#TGZ}
```
public static final FileType TGZ
```


하나 이상의 파일을 수집하기 위해 생성된 통합 Unix 파일 아카이브(.tgz, .tar.gz)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/tgz)를 클릭하세요.


### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


하나 이상의 파일을 수집하기 위해 생성된 통합 Unix 파일 아카이브(.tgz, .tar.gz)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/tgz)를 클릭하세요.


### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


BZIP2 오픈소스 압축 방식을 사용하여 생성된 Bzip2 압축 파일(.bz2)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/compression/bz2)를 클릭하세요.


### RAR {#RAR}
```
public static final FileType RAR
```


RAR (WINRAR 버전 4) 압축 방식을 사용하여 생성된 Roshal Archive(.rar) 압축 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/compression/rar)). 클릭하세요.


### GZ {#GZ}
```
public static final FileType GZ
```


gzip 압축 애플리케이션으로 생성된 Gnu Zipped File(.gz) 압축 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/compression/gz)를 클릭하세요.


### GZIP {#GZIP}
```
public static final FileType GZIP
```


Unix 시스템에서 사용되는 Compress 프로그램을 대체하기 위해 도입된 무료 유틸리티인 Gnu Zipped File(.gzip) 압축 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/compression/gz)를 클릭하세요.


### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


LZMA 및 LZMA2 압축을 지원하는 무료 오픈소스 압축 프로그램인 7Zip(.7z, .7zip) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/compression/7z/))를 클릭하세요.


### CPIO {#CPIO}
```
public static final FileType CPIO
```


Cpio는 일반 파일 아카이버 유틸리티 및 관련 파일 형식입니다. 주로 Unix와 유사한 컴퓨터 운영 체제에 설치됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/compression/cpio)를 클릭하세요.


### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


ZST 파일은 Zstandard(zstd) 압축 알고리즘으로 생성된 압축 파일입니다. 손실 없는 압축으로 만들어진 파일이며, 데이터베이스, 파일 시스템, 네트워크, 게임 등 다양한 유형의 파일을 압축하는 데 사용할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/compression/zst/))를 클릭하세요.


### TZST {#TZST}
```
public static final FileType TZST
```


TZST 파일(.tar.zst, .tzst)은 Zstandard 아카이브(ZST)이며, 내부에 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 통합 Unix 파일 아카이브(Tar)를 포함합니다.


### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


TZST 파일(.tar.zst, .tzst)은 Zstandard 아카이브(ZST)이며, 내부에 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 통합 Unix 파일 아카이브(Tar)를 포함합니다.


### ISO {#ISO}
```
public static final FileType ISO
```


ISO 광디스크 이미지는 CD 또는 DVD와 같은 광디스크의 전체 데이터를 나타내는 압축되지 않은 아카이브 디스크 이미지 파일이며, ISO-9660 표준을 기반으로 합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/compression/iso/))를 클릭하세요.


### LHA {#LHA}
```
public static final FileType LHA
```


LHA 또는 LZH는 무료 압축 유틸리티 및 해당 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/compression/lzh/))를 클릭하세요.


### CAB {#CAB}
```
public static final FileType CAB
```


Cabinet(또는 CAB)은 Microsoft Windows용 아카이브 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://en.wikipedia.org/wiki/Cabinet_(file_format)))를 클릭하세요.


### DXF {#DXF}
```
public static final FileType DXF
```


AutoCAD 도면 파일의 태그된 데이터 표현인 Drawing Exchange Format File(.dxf)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/dxf))를 클릭하세요.


### DWG {#DWG}
```
public static final FileType DWG
```


AutoCAD Drawing Database File(.dwg)은 2D 및 3D 설계 데이터를 포함하는 데 사용되는 독점 바이너리 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/dwg))를 클릭하세요.


### DWT {#DWT}
```
public static final FileType DWT
```


DWG 파일로 저장할 수 있는 도면을 만들기 위한 시작 파일인 AutoCAD Drawing Template(.dwt) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/dwt))를 클릭하세요.


### STL {#STL}
```
public static final FileType STL
```


Stereolithography 파일(.stl)을 나타내며, 3차원 표면 기하학을 표현하는 교환 가능한 파일 형식입니다. 빠른 프로토타이핑, 3D 프린팅 및 컴퓨터 지원 제조에 일반적으로 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/stl))를 클릭하세요.


### IFC {#IFC}
```
public static final FileType IFC
```


Industry Foundation Classes 파일(.ifc)을 나타내며, 건축 객체와 그 속성을 가져오고 내보내기 위한 국제 표준을 정의하는 파일 형식입니다. 다양한 소프트웨어 애플리케이션 간의 상호 운용성을 가능하게 합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/ifc))를 클릭하세요.


### DWF {#DWF}
```
public static final FileType DWF
```


Design Web Format 파일(.dwf)을 나타내며, 2D/3D 도면을 보기, 검토 또는 인쇄하기 위한 압축 파일 형식입니다. 디자인 데이터의 일부로 그래픽과 텍스트를 포함하고 압축으로 파일 크기를 줄입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/dwf))를 클릭하세요.


### FBX {#FBX}
```
public static final FileType FBX
```


3D 모델 형식인 Autodesk FBX Interchange File(FilmBoX)(.fbx)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/fbx)를 클릭하십시오.


### DWFX {#DWFX}
```
public static final FileType DWFX
```


Design Web Format 파일 XPS(.dwfx)를 나타내며, 2D/3D 도면을 XPS 문서로 보기, 검토 또는 인쇄하기 위한 압축 형식입니다. 디자인 데이터의 일부로 그래픽과 텍스트를 포함하고 압축으로 인해 파일 크기가 감소합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/dwfx)를 클릭하십시오.


### DGN {#DGN}
```
public static final FileType DGN
```


MicroStation 및 Intergraph Interactive Graphics Design System과 같은 CAD 애플리케이션에서 생성 및 지원되는 도면인 MicroStation Design File(.dgn)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/dgn)를 클릭하십시오.


### PLT {#PLT}
```
public static final FileType PLT
```


PLT(HPGL) 파일(.plt)을 나타내며, Autodesk, Inc.에서 도입한 벡터 기반 플로터 파일입니다. 특정 CAD 파일에 대한 정보를 포함하고, 모든 이미지를 점이 아닌 선으로 인쇄하여 생산 시 정확성과 정밀성을 보장합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/cad/plt)를 클릭하십시오.


### CF2 {#CF2}
```
public static final FileType CF2
```


Common File Format File(.cf2)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/cf2)를 클릭하십시오.


### OBJ {#OBJ}
```
public static final FileType OBJ
```


Wavefront Technologies에서 도입한 3D 이미지 파일인 Wavefront 3D Object File(.obj)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/3d/obj/)를 클릭하십시오.


### HPG {#HPG}
```
public static final FileType HPG
```


PLT (HPGL) 파일 (.hpg)을 나타냅니다.
HP Graphics Language(HPGL)에서 플로터 파일에 사용되는 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/hpg)를 클릭하십시오.


### IGS {#IGS}
```
public static final FileType IGS
```


초기 그래픽 교환 사양 (IGES) 파일 (.igs)을 나타냅니다.


### VSD {#VSD}
```
public static final FileType VSD
```


Visio 도면 파일 (.vsd)을 나타내며, 이는 Microsoft Visio 애플리케이션으로 만든 다양한 그래픽 객체와 그 상호 연결을 나타내는 도면입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vsd)를 클릭하십시오.


### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing 파일(.vsdx)을 나타내며, Microsoft Office 2013 이후부터 도입된 Microsoft Visio 파일 형식입니다. 이전 버전의 Microsoft Visio에서 지원하던 바이너리 파일 형식(.VSD)을 대체했습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vsdx)를 클릭하십시오.


### VSS {#VSS}
```
public static final FileType VSS
```


Visio Stencil 파일(.vss)을 나타내며, Microsoft Visio 2007 및 이전 버전으로 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 도면에 포함될 수 있는 그리기 객체를 제공합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vss)를 클릭하십시오.


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio Stencil 파일(.vssx)을 나타내며, Microsoft Visio 2013 이상에서 만든 드로잉 스텐실입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 도형, 연결선, 순서도, 네트워크 레이아웃, UML 다이어그램 등 다양한 그리기 요소를 나타내는 것으로 알려져 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vssx)를 클릭하십시오.


### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio 매크로 사용 가능 드로잉(.vsdm)을 나타내며, 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 드로잉 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 드로잉이지만, 파일이 열릴 때 매크로를 실행할 수 있는 기능도 제공합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vsdm)를 클릭하십시오.


### VST {#VST}
```
public static final FileType VST
```


Visio Drawing 템플릿(.vst)을 나타내며, Microsoft Visio로 만든 벡터 이미지 파일입니다. 추가 파일을 만들기 위한 템플릿으로 작동하며, 새로운 Visio 도면을 만들 때 사용되는 기본 레이아웃 및 설정을 포함합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vst)를 클릭하십시오.


### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing 템플릿(.vstx)을 나타내며, Microsoft Visio 2013 이상에서 만든 드로잉 템플릿 파일입니다. 이러한 VSTX 파일은 .VSDX 파일로 저장되는 Visio 도면을 만들기 위한 시작점을 제공하며, 기본 레이아웃 및 설정을 포함합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vstx)를 클릭하십시오.


### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio 매크로 사용 가능 드로잉 템플릿(.vstm)을 나타내며, 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSTM 템플릿에서 만든 파일은 Visual Basic for Applications(VBA) 코드로 개발된 매크로를 실행할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vstm)). 클릭하십시오.


### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio 매크로 지원 스텐실 파일(.vssm)을 나타내며, 이는 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 도형의 원하는 서식 및 배치를 달성할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vssm)를 클릭하십시오.


### VSX {#VSX}
```
public static final FileType VSX
```


Visio 스텐실 XML 파일(.vsx)을 나타내며, 이는 Microsoft Visio에서 다이어그램을 만들 때 사용되는 도면 및 도형으로 구성된 스텐실을 의미합니다. VSX 파일은 XML 파일 형식으로 저장되며 Visio 2013까지 지원되었습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vsx)를 클릭하십시오.


### VTX {#VTX}
```
public static final FileType VTX
```


Visio 템플릿 XML 파일(.vtx)을 나타내며, 이는 XML 파일 형식으로 디스크에 저장된 Microsoft Visio 도면 템플릿입니다. 템플릿은 동일한 설정으로 여러 Visio 파일을 만들기 위한 기본 설정을 제공합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vtx)를 클릭하십시오.


### VDW {#VDW}
```
public static final FileType VDW
```


Visio 웹 도면 (.vdw)을 나타내며, 이는 웹 도면을 렌더링하는 데 필요한 스트림 및 스토리지를 지정합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/web/vdw)를 클릭하십시오.


### VDX {#VDX}
```
public static final FileType VDX
```


Visio 도면 XML 파일(.vdx)을 나타내며, 이는 Microsoft Visio에서 만든 도면이나 차트를 .VDX 확장자를 가진 XML 형식으로 저장한 것입니다. Visio 도면 XML 파일은 Microsoft에서 개발한 Visio 소프트웨어에서 생성됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/vdx)를 클릭하십시오.


### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook 파일(.epub)을 나타내며, 이는 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 많은 전자책 리더와 소프트웨어 애플리케이션에서 지원됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/ebook/epub)).


### MOBI {#MOBI}
```
public static final FileType MOBI
```


Mobipocket 전자책(.mobi)을 나타내며, 이는 가장 널리 사용되는 전자책 파일 형식 중 하나입니다. 이 형식은 기존 OEB(Open Ebook Format) 형식을 개선한 것이며 Mobipocket Reader용 독점 형식으로 사용되었습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/ebook/mobi)).


### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Amazon Kindle Format 8(KF8) 전자책은 Amazon Kindle 기기를 위해 개발된 디지털 파일 형식입니다. 이 형식은 이전 AZW 파일을 개선한 것이며 Kindle Fire 기기에서만 사용되며, 이전 파일 형식인 MOBI와 AZW와의 하위 호환성을 제공합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/ebook/azw3)).


### MSG {#MSG}
```
public static final FileType MSG
```


Outlook 메일 메시지 (.msg)를 나타내며, 이는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용하는 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/email/msg)).


### EML {#EML}
```
public static final FileType EML
```


E-Mail 메시지(.eml)를 나타내며, 이는 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 의미합니다. RFC-822 인터넷 메시지 형식 표준을 준수하기 때문에 거의 모든 이메일 클라이언트가 이 파일 형식을 지원합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/email/eml)).


### EMLX {#EMLX}
```
public static final FileType EMLX
```


Apple Mail 메시지(.emlx)를 나타내며, 이는 Apple에서 구현 및 개발한 것입니다. Apple Mail 애플리케이션은 이메일 내보내기를 위해 EMLX 파일 형식을 사용합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/email/emlx)).


### PST {#PST}
```
public static final FileType PST
```


Outlook 개인 정보 저장 파일 (.pst)를 나타내며, 이는 다양한 사용자 정보를 저장하는 Outlook 개인 저장 파일(또는 Personal Storage Table)입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/email/pst)).


### OST {#OST}
```
public static final FileType OST
```


Outlook 오프라인 데이터 파일 (.ost)를 나타내며, 이는 Microsoft Outlook을 사용해 Exchange Server에 등록할 때 로컬 머신에서 오프라인 모드로 사용자의 사서함 데이터를 저장합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/email/ost)).


### TIF {#TIF}
```
public static final FileType TIF
```


Tagged Image File(.tif)을 나타내며, 이는 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 의미합니다. 이 형식은 이진, 그레이스케일, 팔레트 색상 및 여러 색 공간의 풀 컬러 이미지 데이터를 설명할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/tiff)).


### TIFF {#TIFF}
```
public static final FileType TIFF
```


Tagged Image File Format(.tiff)을 나타내며, 이는 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 의미합니다. 이 형식은 이진, 그레이스케일, 팔레트 색상 및 여러 색 공간의 풀 컬러 이미지 데이터를 설명할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/tiff)).


### JPG {#JPG}
```
public static final FileType JPG
```


JPEG 이미지(.jpg)를 나타내며, 손실 압축 방식을 사용하여 저장되는 이미지 형식의 일종입니다. 압축 결과로 생성된 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/jpeg).


### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG 이미지(.jpeg)를 나타내며, 손실 압축 방식을 사용하여 저장되는 이미지 형식의 일종입니다. 압축 결과로 생성된 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/jpeg).


### JFIF {#JFIF}
```
public static final FileType JFIF
```


JPEG 파일 교환 형식(.jfif)은 플랫폼 간 빠른 교환을 위해 개발된 이미지입니다. 이 형식은 JPEG 압축을 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/jfif).


### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic(.png)를 나타내며, 무손실 압축을 사용하는 래스터 이미지 파일 형식의 일종입니다. 이 파일 형식은 Graphics Interchange Format(GIF)을 대체하기 위해 만들어졌으며 저작권 제한이 없습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/png).


### GIF {#GIF}
```
public static final FileType GIF
```


Graphical Interchange Format 파일(.gif)을 나타내며, 고도로 압축된 이미지 형식입니다. 각 이미지에 대해 GIF는 일반적으로 픽셀당 최대 8비트를 허용하고, 전체 이미지에서 최대 256색을 사용할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/gif).


### APNG {#APNG}
```
public static final FileType APNG
```


Animated Portable Network Graphic (.apng)를 나타내며, 애니메이션을 지원하는 PNG 형식의 확장입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/apng).


### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap 이미지 파일(.bmp)를 나타내며, 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이러한 이미지는 그래픽 어댑터와 독립적이며, 디바이스 독립 비트맵(DIB) 파일 형식이라고도 합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/bmp).


### ICO {#ICO}
```
public static final FileType ICO
```


Icon 파일 (.ico)를 나타내며, Microsoft Windows에서 애플리케이션을 나타내는 아이콘으로 사용되는 이미지 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/ico).


### TGA {#TGA}
```
public static final FileType TGA
```


Truevision TGA (TARGA) 파일을 나타내며, TRUEVISION에서 개발한 비트맵 디지털 이미지를 저장하는 데 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/tga).


### JP_2 {#JP-2}
```
public static final FileType JP_2
```


JPEG 2000 Core Image 파일 (.jp2)를 나타내며, 이미지 코딩 시스템 및 최첨단 이미지 압축 표준입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/jp2).


### JPF {#JPF}
```
public static final FileType JPF
```


JPEG 2000 이미지 파일 (.jpf)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/image/jpf).


### JPX {#JPX}
```
public static final FileType JPX
```


JPEG 2000 이미지 파일 (.jpx)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/jpx).


### JPM {#JPM}
```
public static final FileType JPM
```


JPEG 2000 이미지 파일 (.jpm)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/jpm).


### J2C {#J2C}
```
public static final FileType J2C
```


JPEG 2000 코드 InputStream (.j2c)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/j2c).


### J2K {#J2K}
```
public static final FileType J2K
```


JPEG 2000 코드 스트림 (.j2k)를 나타내며, DCT 압축 대신 웨이브릿 압축을 사용한 이미지입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/j2k).


### JPC {#JPC}
```
public static final FileType JPC
```


JPEG 2000 코드 스트림 (.jpc)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/jpc).


### JLS {#JLS}
```
public static final FileType JLS
```


JPEG-LS (JLS) 파일 (.jls)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/jls).


### DIB {#DIB}
```
public static final FileType DIB
```


Device Independent Bitmap 파일 (.dib)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/dib).


### WMF {#WMF}
```
public static final FileType WMF
```


Windows Metafile (.wmf)를 나타내며, 벡터와 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows Metafile (WMF)을 의미합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/wmf).


### WMZ {#WMZ}
```
public static final FileType WMZ
```


Compressed Windows Metafile (.wmz)를 나타내며, 벡터와 비트맵 형식 이미지 데이터를 저장하기 위해 GZIP 아카이브로 압축된 Microsoft Windows Metafile (WMF)을 의미합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/wmz#compressed_windows_metafile).


### EMF {#EMF}
```
public static final FileType EMF
```


Enhanced Windows Metafile(.emf)을 나타내며, 그래픽 이미지를 디바이스 독립적으로 표현합니다. EMF 메타파일은 순차적인 가변 길이 레코드로 구성되어 있어, 어떤 출력 장치에서도 파싱 후 저장된 이미지를 렌더링할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/emf).


### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows 압축 향상 메타파일(.emz)을 나타내며, GZIP으로 장치 독립적으로 압축된 그래픽 이미지를 나타냅니다. EMF 메타파일은 순차적인 가변 길이 레코드로 구성되어 파싱 후 모든 출력 장치에서 저장된 이미지를 렌더링할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/emz).


### WEBP {#WEBP}
```
public static final FileType WEBP
```


WebP 이미지(.webp)를 나타내며, 손실 및 무손실 압축을 기반으로 하는 최신 래스터 웹 이미지 파일 형식입니다. 동일한 이미지 품질을 제공하면서 이미지 크기를 크게 줄입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/webp).


### DNG {#DNG}
```
public static final FileType DNG
```


디지털 네거티브 사양(.dng)을 나타내며, 원시 파일 저장에 사용되는 디지털 카메라 이미지 형식입니다. 2004년 9월 Adobe에서 개발했으며 주로 디지털 사진 촬영에 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/dng).


### CDR {#CDR}
```
public static final FileType CDR
```


CorelDraw 벡터 그래픽 드로잉(.cdr)을 나타내며, CorelDRAW로 기본 생성된 벡터 이미지 파일로 디지털 인코딩 및 압축된 이미지를 저장합니다. CDR 드로잉 파일에는 텍스트, 선, 도형, 이미지, 색상 및 효과가 포함되어 이미지 내용을 벡터 방식으로 표현합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/cdr).


### CMX {#CMX}
```
public static final FileType CMX
```


Corel Exchange (.cmx)를 나타내며, 이는 벡터 그래픽과 비트맵 그래픽을 모두 포함할 수 있는 그림 이미지 파일입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/cmx).


### DJVU {#DJVU}
```
public static final FileType DJVU
```


DjVu Image (.djvu)를 나타내며, 이는 스캔한 문서와 책을 위해 설계된 그래픽 파일 형식으로, 특히 텍스트, 그림, 이미지 및 사진이 결합된 경우에 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/djvu).


### CGM {#CGM}
```
public static final FileType CGM
```


Computer Graphics Metafile(.cgm)을 나타내며, 벡터 그래픽(2D), 래스터 그래픽 및 텍스트를 저장하고 교환하기 위한 무료, 플랫폼 독립적인 국제 표준 메타파일 형식입니다. CGM은 객체 지향 방식을 사용하며 이미지 제작을 위한 다양한 기능을 제공합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/page-description-language/cgm).


### PCL {#PCL}
```
public static final FileType PCL
```


Printer Command Language Document (.pcl)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/page-description-language/pcl).


### PSD {#PSD}
```
public static final FileType PSD
```


Adobe Photoshop Document (.psd)를 나타내며, 이는 그래픽 디자인 및 개발에 사용되는 Adobe Photoshop의 기본 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/psd).


### PSB {#PSB}
```
public static final FileType PSB
```


Photoshop Large Document Format (.psb)를 나타내며, 이는 Adobe Photoshop에서 그래픽 디자인 및 개발에 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/psb).


### DCM {#DCM}
```
public static final FileType DCM
```


DICOM Image (.dcm)를 나타내며, 이는 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지를 의미합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/dcm).


### PS {#PS}
```
public static final FileType PS
```


PostScript File (.ps)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/page-description-language/ps).


### EPS {#EPS}
```
public static final FileType EPS
```


Encapsulated PostScript File (.eps)를 나타내며, 이는 단일 페이지의 외관을 정의하는 Encapsulated PostScript 언어 프로그램을 설명합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/page-description-language/eps).


### ODG {#ODG}
```
public static final FileType ODG
```


OpenDocument Graphic File (.odg)를 나타내며, 이는 Apache OpenOffice의 Draw 애플리케이션에서 그림 요소를 벡터 이미지로 저장하는 데 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/odg).


### FODG {#FODG}
```
public static final FileType FODG
```


Flat XML ODF Template (.fodg)를 나타내며, 이는 Apache OpenOffice의 Draw 애플리케이션에서 그림 요소를 벡터 이미지로 저장하는 데 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/image/fodg).


### SVG {#SVG}
```
public static final FileType SVG
```


Scalable Vector Graphics File (.svg)를 나타내며, 이는 이미지의 외관을 설명하기 위해 XML 기반 텍스트 형식을 사용하는 Scalable Vector Graphics 파일입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/page-description-language/svg).


### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Compressed Scalable Vector Graphics File (.svgz)를 나타내며, 이는 XML 기반 텍스트 형식을 사용하고 GZIP으로 압축된 Scalable Vector Graphics 파일로 이미지의 외관을 설명합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/svgz).


### OTG {#OTG}
```
public static final FileType OTG
```


OpenDocument Graphic Template (.otg)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/image/otg).


### HTM {#HTM}
```
public static final FileType HTM
```


Hypertext Markup Language File (.htm)를 나타내며, 이는 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/web/html).


### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html)를 나타내며, 이는 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/web/html).


### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/web/mht)를 클릭하십시오.


### NSF {#NSF}
```
public static final FileType NSF
```


Lotus Notes Database (.nsf)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/nsf)를 클릭하십시오.


### MBOX {#MBOX}
```
public static final FileType MBOX
```


Email Mailbox File (.mbox)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/mbox)를 클릭하십시오.


### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/web/mhtml)를 클릭하십시오.


### XML {#XML}
```
public static final FileType XML
```


XML File (.xml)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/web/xml)를 클릭하십시오.


### ONE {#ONE}
```
public static final FileType ONE
```


Microsoft OneNote 애플리케이션에서 만든 OneNote 문서(.one)를 나타냅니다. OneNote를 사용하면 초안 패드처럼 메모를 작성하면서 정보를 수집할 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/note-taking/one)를 클릭하십시오.


### PDF {#PDF}
```
public static final FileType PDF
```


Adobe가 1990년대에 만든 Portable Document Format 파일(.pdf)을 나타냅니다. 이 파일 형식의 목적은 애플리케이션 소프트웨어, 하드웨어 및 운영 체제와 무관하게 문서 및 기타 참고 자료를 표현하기 위한 표준을 도입하는 것이었습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/view/pdf)를 클릭하십시오.


### XPS {#XPS}
```
public static final FileType XPS
```


Microsoft에서 만든 XML Paper Specification 파일(.xps)을 나타냅니다. 이 파일은 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 의미합니다. 이 형식은 Microsoft가 EMF 파일 형식을 대체하기 위해 개발했으며 PDF 파일 형식과 유사하지만 문서의 레이아웃, 외관 및 인쇄 정보를 XML로 사용합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/page-description-language/xps)를 클릭하십시오.


### OXPS {#OXPS}
```
public static final FileType OXPS
```


OpenXPS File (.oxps)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/page-description-language/oxps)를 클릭하십시오.


### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX 소스 문서(.tex)를 나타내며, 이는 문서를 조판하는 데 사용되는 프로그래밍과 마크업 기능을 모두 포함하는 언어입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/page-description-language/tex)). 클릭하십시오.


### OFD {#OFD}
```
public static final FileType OFD
```


GB/T 33190-2016에서 정의된 오픈 고정 레이아웃 문서(OFD) 형식은 중국 공공 기관에서 PDF를 대체하는 것을 목표로 합니다.


### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint 프레젠테이션(.ppt)을 나타냅니다. 이는 슬라이드 모음으로 구성된 PowerPoint 파일로, 슬라이드쇼로 표시됩니다. Microsoft PowerPoint 97-2003에서 사용되는 바이너리 파일 형식을 지정합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/ppt)). 클릭하십시오.


### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML 프레젠테이션(.pptx)을 나타냅니다. 이는 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전의 바이너리 PPT 형식과 달리 PPTX 형식은 Microsoft PowerPoint Open XML 프레젠테이션 파일 형식을 기반으로 합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/pptx)). 클릭하십시오.


### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint 슬라이드 쇼(.pps)를 나타냅니다. 이는 Microsoft PowerPoint를 사용하여 슬라이드 쇼용으로 만든 파일이며, PPS 파일의 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/pps)). 클릭하십시오.


### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML 슬라이드 쇼(.ppsx) 파일을 나타내며, 이는 Microsoft PowerPoint 2007 이상을 사용해 슬라이드 쇼 용도로 생성됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/ppsx)). 클릭하십시오.


### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument 프레젠테이션(.odp)을 나타내며, 이는 OASIS Open 표준에서 OpenOffice.org가 사용하는 프레젠테이션 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/odp)). 클릭하십시오.


### FODP {#FODP}
```
public static final FileType FODP
```


OpenDocument 프레젠테이션(.fodp)을 나타내며, 이는 OpenDocument 플랫 XML 프레젠테이션을 의미합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/fodp)). 클릭하십시오.


### POT {#POT}
```
public static final FileType POT
```


PowerPoint 템플릿(.pot)을 나타내며, 이는 PowerPoint 97-2003 버전으로 만든 Microsoft PowerPoint 템플릿 파일을 의미합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/pot)). 클릭하십시오.


### PPTM {#PPTM}
```
public static final FileType PPTM
```


PowerPoint Open XML 매크로 사용 프레젠테이션(.pptm)을 나타내며, 이는 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 사용 프레젠테이션 파일입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/pptm)). 클릭하십시오.


### POTX {#POTX}
```
public static final FileType POTX
```


PowerPoint Open XML 프레젠테이션 템플릿(.potx)을 나타내며, 이는 Microsoft PowerPoint 2007 이상으로 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 의미합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/potx)). 클릭하십시오.


### POTM {#POTM}
```
public static final FileType POTM
```


PowerPoint Open XML 매크로 사용 프레젠테이션 템플릿 (.potm)을 나타내며, 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며, 추가 프레젠테이션 파일을 만드는 데 사용할 수 있는 기본 설정을 포함합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/potm)를 클릭하십시오.


### PPSM {#PPSM}
```
public static final FileType PPSM
```


PowerPoint Open XML 매크로 사용 슬라이드(.ppsm)를 나타내며, 이는 Microsoft PowerPoint 2007 이상으로 만든 매크로 사용 슬라이드 쇼 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/ppsm)를 클릭하십시오.


### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument 프레젠테이션 템플릿(.otp)을 나타내며, 이는 OASIS OpenDocument 표준 형식의 애플리케이션으로 만든 프레젠테이션 템플릿 파일을 의미합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/presentation/otp)를 클릭하십시오.


### XLS {#XLS}
```
public static final FileType XLS
```


Excel 스프레드시트 (.xls)를 나타내며, Excel 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 만들 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/xls)를 클릭하십시오.


### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Excel 2003 XML (SpreadsheetML) (.xml)를 나타내며, Excel 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 만들 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/xls)를 클릭하십시오.


### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Apple Numbers (.numbers)를 나타내며, Excel과 유사한 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Apple Numbers 애플리케이션으로 만들 수 있습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/numbers)를 클릭하십시오.


### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML 스프레드시트(.xlsx)를 나타내며, 이는 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 Microsoft Excel 문서의 잘 알려진 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/xlsx)를 클릭하십시오.


### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML 매크로 사용 스프레드시트(.xlsm)를 나타내며, 이는 매크로를 지원하는 스프레드시트 파일 유형입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/xlsm)를 클릭하십시오.


### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel 바이너리 스프레드시트 (.xlsb)를 나타내며, Excel 바이너리 파일 형식을 지정합니다. 이는 Excel 워크북 내용을 지정하는 레코드와 구조의 모음입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/xlsb)를 클릭하십시오.


### CSV {#CSV}
```
public static final FileType CSV
```


콤마 구분 값 파일(.csv)을 나타내며, 이는 쉼표로 구분된 값으로 데이터 레코드를 포함하는 일반 텍스트 파일을 의미합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/csv)를 클릭하십시오.


### TSV {#TSV}
```
public static final FileType TSV
```


탭 구분 값 파일(.tsv)을 나타내며, 이는 탭으로 구분된 데이터를 일반 텍스트 형식으로 포함합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/tsv)를 클릭하십시오.


### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument 스프레드시트 (.ods)를 나타내며, 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 의미합니다. 데이터는 ODF 파일 내에 행과 열로 저장됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/ods)를 클릭하십시오.


### FODS {#FODS}
```
public static final FileType FODS
```


OpenDocument 플랫 XML 스프레드시트(.fods)를 나타냅니다.
이는 OpenOffice와 LibreOffice에서 사용하는 XML 기반 스프레드시트 문서 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/fods)).


### OTS {#OTS}
```
public static final FileType OTS
```


OpenDocument 스프레드시트 템플릿(.ots)를 나타냅니다.
이는 OpenOffice와 LibreOffice에서 스프레드시트용으로 사용하는 템플릿 문서 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/ots)).


### XLAM {#XLAM}
```
public static final FileType XLAM
```


Microsoft Excel 추가 기능(.xlam)을 나타냅니다.
이는 Microsoft Excel에서 사용자 정의 기능이 있는 추가 기능을 만들기 위해 사용하는 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/xlam)).


### XLTM {#XLTM}
```
public static final FileType XLTM
```


Microsoft Excel 매크로 사용 템플릿 (.xltm)을 나타내며, Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 의미합니다. XLTM 파일은 구조가 XLTX와 유사하지만 후자는 매크로가 포함된 템플릿 파일을 지원하지 않습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/xltm)).


### XLT {#XLT}
```
public static final FileType XLT
```


Microsoft Excel 템플릿(.xlt)을 나타내며, 이는 Microsoft Excel로 만든 템플릿 파일이며, Microsoft Office 제품군에 포함된 스프레드시트 애플리케이션입니다. Microsoft Office 97-2003은 새로운 XLT 파일을 만들고 열 수 있었습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/xlt).


### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML 스프레드시트 템플릿(.xltx)을 나타내며, 이는 Office OpenXML 파일 형식 사양을 기반으로 한 Microsoft Excel 템플릿입니다. XLTX 파일에 지정된 동일한 설정으로 XLSX 파일을 생성하는 데 사용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/xltx).


### SXC {#SXC}
```
public static final FileType SXC
```


StarOffice Calc 스프레드시트(.sxc)를 나타냅니다.
StarOffice Calc으로 만든 스프레드시트 문서이며, 스프레드시트 프로그램입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/spreadsheet/sxc).


### MPP {#MPP}
```
public static final FileType MPP
```


Microsoft Project 파일(.mpp)을 나타내며, 이는 프로젝트 관리와 관련된 정보를 통합 방식으로 저장하는 Microsoft Project 데이터 파일입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/project-management/mpp).


### MPT {#MPT}
```
public static final FileType MPT
```


Microsoft Project 템플릿(.mpt)을 나타내며, 이는 .MPP 파일을 만들기 위한 기본 정보와 구조 및 문서 설정을 포함합니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/project-management/mpt).


### MPX {#MPX}
```
public static final FileType MPX
```


Microsoft Project Exchange 파일(.mpx)을 나타내며, 이는 Microsoft Project(MSP)와 MPX 파일 형식을 지원하는 Primavera Project Planner, Sciforma, Timerline Precision Estimating과 같은 다른 애플리케이션 간에 프로젝트 정보를 전송하기 위한 ASCII 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/project-management/mpx).


### AS {#AS}
```
public static final FileType AS
```


ActionScript 파일(.as)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/as).


### AS_3 {#AS-3}
```
public static final FileType AS_3
```


ActionScript 파일(.as3)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://datatypes.net/open-as3-files).


### ASM {#ASM}
```
public static final FileType ASM
```


어셈블리 언어 소스 코드 파일(.asm)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/cad/asm).


### BAT {#BAT}
```
public static final FileType BAT
```


DOS 배치 파일(.bat)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/executable/bat).


### C {#C}
```
public static final FileType C
```


C/C++ 소스 코드 파일(.c)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/c).


### CC {#CC}
```
public static final FileType CC
```


C++ 소스 코드 파일(.cc)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/cc).


### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


CMake 파일(.cmake)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/cmake).


### CPP {#CPP}
```
public static final FileType CPP
```


C++ 소스 코드 파일(.cpp)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/cpp).


### CS {#CS}
```
public static final FileType CS
```


C# 소스 코드 파일(.cs)을 나타내며, C# 프로그래밍 언어용 소스 코드 파일입니다. .NET Framework와 함께 사용하도록 Microsoft에서 도입했습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/cs).


### VB {#VB}
```
public static final FileType VB
```


Visual Basic 프로젝트 항목 파일(.vb)을 나타내며, Visual Basic 언어로 만든 소스 코드 파일입니다. .NET 애플리케이션 개발을 위해 Microsoft에서 만들었습니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/vb).


### CSS {#CSS}
```
public static final FileType CSS
```


Cascading Style Sheet(.css) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/web/css).


### CXX {#CXX}
```
public static final FileType CXX
```


C++ 소스 코드 파일(.cxx)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/cxx).


### DIFF {#DIFF}
```
public static final FileType DIFF
```


패치 파일(.diff)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/diff).


### ERB {#ERB}
```
public static final FileType ERB
```


Ruby ERB 스크립트(.erb)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/erb).


### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Groovy 소스 코드 파일(.groovy)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/groovy).


### H {#H}
```
public static final FileType H
```


C/C++/Objective-C 헤더 파일(.h)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/h).


### HAML {#HAML}
```
public static final FileType HAML
```


Haml 소스 코드 파일(.haml)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/haml).


### HH {#HH}
```
public static final FileType HH
```


C++ 헤더 파일 (.hh)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/hh).


### JAVA {#JAVA}
```
public static final FileType JAVA
```


Java 소스 코드 파일 (.java)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/java).


### JS {#JS}
```
public static final FileType JS
```


JavaScript 파일 (.js)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/web/js).


### JSON {#JSON}
```
public static final FileType JSON
```


JavaScript 객체 표기법 파일 (.json)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/web/json).


### LESS {#LESS}
```
public static final FileType LESS
```


LESS 스타일 시트 (.less) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/web/less).


### LOG {#LOG}
```
public static final FileType LOG
```


로그 파일 (.log)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/database/log).


### M {#M}
```
public static final FileType M
```


Objective-C 구현 파일 (.m)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/m).


### MAKE {#MAKE}
```
public static final FileType MAKE
```


Xcode 메이크파일 스크립트 (.make)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/make).


### MD {#MD}
```
public static final FileType MD
```


Markdown 문서 파일 (.md)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/word-processing/md).


### ML {#ML}
```
public static final FileType ML
```


ML 소스 코드 파일 (.ml)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/ml).


### MM {#MM}
```
public static final FileType MM
```


Objective-C++ 소스 파일 (.mm)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/mm).


### PHP {#PHP}
```
public static final FileType PHP
```


PHP 소스 코드 파일 (.php)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/programming/php).


### PL {#PL}
```
public static final FileType PL
```


Perl 스크립트 (.pl)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/pl).


### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Java 속성 파일 (.properties)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/properties).


### PY {#PY}
```
public static final FileType PY
```


Python 스크립트 (.py)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/py).


### RB {#RB}
```
public static final FileType RB
```


Ruby 소스 코드 (.rb) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/rb).


### RST {#RST}
```
public static final FileType RST
```


reStructuredText 파일 (.rst)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/rst).


### SASS {#SASS}
```
public static final FileType SASS
```


Syntactically Awesome StyleSheets 파일 (.sass)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/web/sass).


### SCALA {#SCALA}
```
public static final FileType SCALA
```


Scala 소스 코드 파일 (.scala)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/scala).


### SCM {#SCM}
```
public static final FileType SCM
```


Scheme 소스 코드 파일 (.scm)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/scm).


### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


일반 스크립트 파일 (.script)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/script).


### SH {#SH}
```
public static final FileType SH
```


Bash 셸 스크립트 (.sh)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/cs/programming/sh).


### SML {#SML}
```
public static final FileType SML
```


Standard ML 소스 코드 파일 (.sml)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/sml).


### SQL {#SQL}
```
public static final FileType SQL
```


Structured Query Language 데이터 파일 (.sql)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/database/sql).


### VIM {#VIM}
```
public static final FileType VIM
```


Vim 설정 파일 (.vim)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/vim).


### YAML {#YAML}
```
public static final FileType YAML
```


YAML 문서 (.yaml)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/programming/yaml).


### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word 문서 (.doc) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/doc).


### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML 문서 (.docx) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/docx).


### CHM {#CHM}
```
public static final FileType CHM
```


Microsoft 컴파일된 HTML 도움말 파일 (.chm)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/web/chm).


### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML 매크로 사용 문서 (.docm) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/docm).


### DOT {#DOT}
```
public static final FileType DOT
```


Word 문서 템플릿 (.dot) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/dot).


### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML 문서 템플릿 (.dotx) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/dotx).


### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML 매크로 사용 문서 템플릿 (.dotm) 파일을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/dotm).


### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format 파일 (.rtf)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/rtf).


### TXT {#TXT}
```
public static final FileType TXT
```


일반 텍스트 파일 (.txt)을 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/txt).


### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument 텍스트 문서 (.odt)를 나타냅니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/odt).


### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument 문서 템플릿 (.ott)을 나타냅니다.
이 문서는 OASIS의 OpenDocument 표준 형식에 따라 생성된 템플릿 문서입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/word-processing/ott).


### VCF {#VCF}
```
public static final FileType VCF
```


vCard 파일 (.vcf)을 나타내며, 이는 연락처 정보를 저장하기 위한 디지털 파일 형식입니다.
이는 인기 있는 정보 교환 애플리케이션 간에 데이터 교환을 위해 널리 사용됩니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://wiki.fileformat.com/email/vcf).


### AI {#AI}
```
public static final FileType AI
```


Adobe Illustrator 파일 (.ai)을 나타내며, 이는 Adobe Illustrator 그림을 위한 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://docs.fileformat.com/image/ai).


### PSM1 {#PSM1}
```
public static final FileType PSM1
```


PowerShell 스크립트 모듈 파일 (.psm1)을 나타냅니다.
이것은 PowerShell 모듈 스크립트용 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/psm1).


### PS1 {#PS1}
```
public static final FileType PS1
```


PowerShell 스크립트 파일 (.ps1)을 나타냅니다.
이것은 Windows PowerShell Cmdlet 파일용 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/ps1).


### PSD1 {#PSD1}
```
public static final FileType PSD1
```


PowerShell 스크립트 모듈 매니페스트 파일 (.psd1)을 나타냅니다.
이것은 PowerShell 모듈 매니페스트 스크립트용 파일 형식입니다.
이 파일 형식에 대해 자세히 알아보려면 [여기](../https://fileinfo.com/extension/psd1).


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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


파일 확장자를 파일 유형에 매핑합니다.


이 메서드는 파일 확장자를 입력받으며, 마침표 "."가 있거나 없어도 되며, 지원되는 경우 해당 파일 유형을 반환합니다.
파일 유형이 지원되지 않으면 기본 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 파일 유형을 반환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | extension | java.lang.String | 마침표 "."가 있거나 없는 파일 확장자입니다. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


파일 이름 또는 파일 경로에서 파일 확장자를 추출하고 이를 파일 유형에 매핑합니다.


파일 유형이 지원되는 경우, 메서드는 해당
FileType
,
그렇지 않으면 기본 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 파일 유형을 반환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 파일 이름 또는 파일 경로입니다. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


파일 미디어 유형을 파일 유형에 매핑합니다. 예를 들어, 'application/pdf'는 [PDF](../../com.groupdocs.viewer/filetype#PDF) 로 매핑됩니다.


이 메서드는 파일 미디어 유형을 입력으로 받아 해당
FileType
. 미디어 유형이
지원되는 경우, 메서드는 해당 파일 유형을 반환합니다. 미디어 유형이 지원되지 않으면 기본
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | mediaType | java.lang.String | 파일 미디어 유형, 예: 'application/pdf'. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


파일 서명을 읽어 파일 유형을 감지합니다.


이 메서드는 파일을 나타내는 입력 스트림을 받아 파일 서명을 분석하여 파일 유형을 감지하려고 시도합니다. 해당
파일 서명은 파일 시작 부분에 있는 고유한 바이트 시퀀스로, 파일 유형을 나타냅니다. 메서드는
입력 스트림에서 파일 서명을 읽고 지원되는 파일 유형의 알려진 파일 서명과 비교합니다.
일치하는 항목이 발견되면 메서드는 해당 파일 유형을 반환합니다. 일치하는 항목이 없으면 기본
[UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 파일을 나타내는 입력 스트림입니다. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


파일 서명을 읽어 파일 유형을 감지합니다.


이 메서드는 파일 시작 부분에 있는 고유한 바이트 시퀀스인 파일 서명을 분석하여
파일 유형을 결정합니다. 제공된 입력 스트림에서 파일 서명을 읽고 알려진 파일 서명과 비교합니다.
지원되는 파일 유형 중 하나와 비교합니다. 일치하는 항목이 발견되면 메서드는 해당 파일 유형을 반환합니다. 일치하는 항목이 없으면
기본 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 파일 유형을 반환합니다.


파일이 암호화되어 있고 열기 위해 비밀번호가 필요하면, 비밀번호는 이 메서드에 매개변수로 제공되어야 합니다
메서드. 비밀번호는 파일을 복호화하고 파일 유형을 결정하기 위해 서명을 분석하는 데 사용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 파일을 나타내는 입력 스트림입니다. |
|
|  | 비밀번호 | java.lang.String | 파일을 열기 위한 비밀번호. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


파일 서명을 읽어 파일 유형을 감지합니다.


이 메서드는 파일 시작 부분에 있는 고유한 바이트 시퀀스인 파일 서명을 분석하여
파일 유형을 결정합니다. 제공된 입력 스트림에서 파일 서명을 읽고 알려진 파일 서명과 비교합니다.
지원되는 파일 유형 중 하나와 비교합니다. 일치하는 항목이 발견되면 메서드는 해당 파일 유형을 반환합니다. 일치하는 항목이 없으면
기본 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 파일 유형을 반환합니다.


파일 유형 감지 과정에서 관련 정보나 오류를 기록하기 위해 로거를 제공할 수 있습니다. 로거
ILogger 인터페이스를 구현해야 합니다. 로거가 제공되지 않으면, 감지 과정은 어떤
로그 출력도 생성하지 않습니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 파일을 나타내는 입력 스트림입니다. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | 정보 또는 오류를 기록하기 위한 로거. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


파일 서명을 읽어 파일 유형을 감지합니다.


이 메서드는 파일 시작 부분에 있는 고유한 바이트 시퀀스인 파일 서명을 분석하여
파일 유형을 결정합니다. 제공된 입력 스트림에서 파일 서명을 읽고 알려진 파일 서명과 비교합니다.
지원되는 파일 유형 중 하나와 비교합니다. 일치하는 항목이 발견되면 메서드는 해당 파일 유형을 반환합니다. 일치하는 항목이 없으면
기본 [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) 파일 유형을 반환합니다.


파일이 암호화되었거나 보호된 경우 비밀번호를 제공할 수 있습니다. 비밀번호는 파일을 열기 전에 사용됩니다
파일 서명을 분석합니다. 파일에 비밀번호가 필요하지 않으면, 이 매개변수를 null로 설정할 수 있습니다.


파일 유형 감지 과정에서 관련 정보나 오류를 기록하기 위해 로거를 제공할 수 있습니다. 로거
ILogger 인터페이스를 구현해야 합니다. 로거가 제공되지 않으면, 감지 과정은 어떤
로그 출력도 생성하지 않습니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 파일을 나타내는 입력 스트림입니다. |
|
|  | 비밀번호 | java.lang.String | 파일을 열기 위한 비밀번호. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | 정보 또는 오류를 기록하기 위한 로거. |
|

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype#UNKNOWN) file type.

### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


지원되는 파일 유형을 검색합니다.


이 메서드는 시스템이 지원하는 모든 파일 유형의 시퀀스를 반환합니다. 파일 유형은 다양한
문서 형식들을 나타내며, 시스템에서 처리하거나 인식할 수 있습니다.
***Learn more**
* Learn more about the supported document formats: [Full list of supported file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/)*


**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - 지원되는 파일 유형의 시퀀스.

### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


경로를 통해 텍스트 [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), 및 [CSV](../../com.groupdocs.viewer/filetype#CSV) 파일의 문자 집합을 감지하려 시도합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 파일 이름 또는 파일 경로입니다. |
|

**Returns:**
java.nio.charset.Charset - 파일 문자 집합을 감지하지 못했을 때 Charset 또는 null.

**Example:**


Charset charset = FileType.detectCharset("message.txt");
     

### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


스트림을 통해 텍스트 [TXT](../../com.groupdocs.viewer/filetype#TXT), [TSV](../../com.groupdocs.viewer/filetype#TSV), 및 [CSV](../../com.groupdocs.viewer/filetype#CSV) 파일의 문자 집합을 감지하려 시도합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | stream | java.io.InputStream | 파일 스트림. |
|

**Returns:**
java.nio.charset.Charset - 파일 문자 집합을 감지하지 못했을 때 Charset 또는 null.

**Example:**


InputStream stream = new FileInputStream("message.txt");
Charset charset = FileType.detectCharset(stream);
     

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


파일 형식의 이름을 가져옵니다. 예: "Microsoft Word Document".


**Returns:**
java.lang.String - 파일 형식의 이름.

### getExtension() {#getExtension--}
```
public final String getExtension()
```


파일 확장자 접미사(마침표 "." 포함)를 가져옵니다. 예: ".doc".


**Returns:**
java.lang.String - 파일 확장자 접미사.

### toString() {#toString--}
```
public String toString()
```


현재 객체의 문자열 표현을 반환합니다.


**Returns:**
java.lang.String - 현재 객체의 문자열 표현입니다.

