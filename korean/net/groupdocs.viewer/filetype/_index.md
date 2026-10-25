---
title: "FileType"
second_title: "GroupDocs.Viewer for .NET API 참조"
description: "파일 유형을 나타냅니다. GroupDocs.Viewer에서 지원하는 모든 파일 유형 목록을 얻기 위한 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.viewer/filetype/
---

## FileType class

파일 유형을 나타냅니다. **GroupDocs.Viewer**에서 지원하는 모든 파일 유형 목록을 얻는 메서드를 제공합니다.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FileType](filetype#constructor)() | [`FileType`](../filetype) 클래스의 새 인스턴스를 초기화합니다. |
| [FileType](filetype#constructor_1)(string, string) | [`FileType`](../filetype) 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; set; } | 파일 이름 접미사(마침표 "." 포함) 예: ".doc". |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; set; } | 파일 유형 이름 예: "Microsoft Word Document". |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | 파일 확장자를 파일 유형에 매핑합니다. |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | 파일 확장자를 추출하고 파일 유형에 매핑합니다. |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | 파일 미디어 유형을 파일 유형에 매핑합니다. 예: 'application/pdf'는 [`PDF`](./pdf)로 매핑됩니다. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | 파일 서명을 읽어 파일 유형을 감지합니다. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | 파일 서명을 읽어 파일 유형을 감지합니다. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | 파일 서명을 읽어 파일 유형을 감지합니다. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | 파일 서명을 읽어 파일 유형을 감지합니다. |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | 현재 [`FileType`](../filetype)이 지정된 [`FileType`](../filetype) 객체와 동일한지 확인합니다. |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | 현재 [`FileType`](../filetype)이 지정된 객체와 동일한지 확인합니다. |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | 현재 [`FileType`](../filetype) 객체의 해시 코드를 반환합니다. |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | 현재 객체를 나타내는 문자열을 반환합니다. |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding)(Stream) | 스트림을 통해 텍스트 [`TXT`](./txt), [`TSV`](./tsv), 및 [`CSV`](./csv) 파일 인코딩을 감지하려 시도합니다. |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding_1)(string) | 경로를 통해 텍스트 [`TXT`](./txt), [`TSV`](./tsv), 및 [`CSV`](./csv) 파일 인코딩을 감지하려 시도합니다. |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | 지원되는 파일 유형을 가져옵니다 |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | 두 [`FileType`](../filetype) 객체가 동일한지 확인합니다. |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | 두 [`FileType`](../filetype) 객체가 동일하지 않은지 확인합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | Animated Portable Network Graphic (.apng)은 애니메이션을 지원하는 PNG 형식의 확장입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/apng)를 클릭하세요. |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | ActionScript 파일 (.as) |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | ActionScript 파일 (.as) |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | 어셈블리 언어 소스 코드 파일 (.asm) |
| static readonly [AZW3](../../groupdocs.viewer/filetype/azw3) | Amazon Kindle Format 8 (KF8) 전자책은 Amazon Kindle 기기를 위해 개발된 디지털 파일 형식입니다. 이 형식은 기존 AZW 파일을 개선한 것이며 Kindle Fire 기기에서만 사용되며, 이전 파일 형식인 MOBI와 AZW와의 하위 호환성을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/ebook/azw3)를 클릭하세요. |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | DOS 배치 파일 (.bat) |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | Bitmap 이미지 파일 (.bmp)은 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이러한 이미지는 그래픽 어댑터와 무관하며 디바이스 독립 비트맵(DIB) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/bmp)를 클릭하세요. |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | Bzip2 압축 파일 (.bz2)은 주로 UNIX 또는 Linux 시스템에서 BZIP2 오픈 소스 압축 방식을 사용해 생성된 압축 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/compression/bz2)를 클릭하세요. |
| static readonly [C](../../groupdocs.viewer/filetype/c) | C/C++ 소스 코드 파일 (.c) |
| static readonly [Cab](../../groupdocs.viewer/filetype/cab) | Cabinet(CAB)은 Microsoft Windows용 아카이브 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://en.wikipedia.org/wiki/Cabinet_(file_format))를 클릭하세요. |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | C++ 소스 코드 파일 (.cc) |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw 벡터 그래픽 드로잉 (.cdr)은 CorelDRAW에서 기본적으로 생성되는 벡터 이미지 파일로, 디지털 이미지를 인코딩 및 압축하여 저장합니다. 이러한 드로잉 파일에는 텍스트, 선, 도형, 이미지, 색상 및 효과가 포함되어 이미지 내용을 벡터 형태로 표현합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/cdr)를 클릭하세요. |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | Common File Format 파일에 대해 자세히 알아보려면 [여기](https://fileinfo.com/extension/cf2)를 클릭하세요. |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | Computer Graphics Metafile (.cgm)은 벡터 그래픽(2D), 래스터 그래픽 및 텍스트를 저장하고 교환하기 위한 무료이며 플랫폼에 독립적인 국제 표준 메타파일 형식입니다. CGM은 객체 지향 접근 방식과 이미지 제작을 위한 다양한 기능을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/page-description-language/cgm)를 클릭하세요. |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft Compiled HTML Help 파일 (.chm)은 HELP(일부 애플리케이션에 대한 문서) 문서에 널리 사용되는 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://docs.fileformat.com/web/chm/)를 클릭하세요. |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | CMake 파일 (.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange (.cmx)는 벡터 그래픽과 비트맵 그래픽을 모두 포함할 수 있는 도면 이미지 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/cmx). |
| static readonly [CPIO](../../groupdocs.viewer/filetype/cpio) | Cpio는 일반 파일 압축 유틸리티 및 관련 파일 형식입니다. 주로 Unix와 유사한 컴퓨터 운영 체제에 설치됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/compression/cpio). |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | C++ 소스 코드 파일 (.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C# 소스 코드 파일 (.cs)은 C# 프로그래밍 언어용 소스 코드 파일입니다. Microsoft가 .NET Framework와 함께 사용하도록 도입했습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/programming/cs). |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | 계단식 스타일 시트 (.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | Comma Separated Values 파일 (.csv)은 쉼표로 구분된 값으로 데이터 레코드를 포함하는 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | C++ 소스 코드 파일 (.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | DICOM 이미지 (.dcm)는 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/dcm). |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | MicroStation 디자인 파일 (.dgn)은 MicroStation 및 Intergraph Interactive Graphics Design System과 같은 CAD 애플리케이션에서 생성되고 지원되는 도면입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/cad/dgn). |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | 디바이스 독립 비트맵 파일 (.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | 패치 파일 (.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu 이미지 (.djvu)는 특히 텍스트, 도면, 이미지 및 사진이 결합된 스캔 문서와 책을 위한 그래픽 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/djvu). |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | Digital Negative 사양 (.dng)은 원시 파일 저장에 사용되는 디지털 카메라 이미지 형식입니다. 2004년 9월 Adobe에서 개발되었습니다. 기본적으로 디지털 사진 촬영을 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/dng). |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | Microsoft Word 문서 (.doc)는 Microsoft Word 또는 기타 워드 프로세서에서 생성된 문서를 바이너리 파일 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | Word Open XML 매크로 사용 문서 (.docm)는 매크로 실행 기능이 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML 문서 (.docx)는 Microsoft Word 문서에 널리 알려진 형식입니다. 2007년 Microsoft Office 2007 출시와 함께 도입되었으며, 이 새로운 문서 형식의 구조는 기존의 순수 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | Word 문서 템플릿 (.dot)은 Microsoft Word에서 생성한 템플릿 파일로, 이후 DOC 또는 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | Word Open XML 매크로 사용 문서 템플릿 (.dotm)은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML 문서 템플릿 (.dotx)은 Microsoft Word에서 생성한 템플릿 파일로, 이후 DOCX 파일을 생성하기 위한 사전 서식 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | Design Web Format 파일 (.dwf)은 보기, 검토 또는 인쇄용 디자인 파일을 위한 압축 형식의 2D/3D 도면을 나타냅니다. 디자인 데이터의 일부로 그래픽과 텍스트를 포함하며, 압축 형식으로 인해 파일 크기가 감소합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/cad/dwf). |
| static readonly [DWFX](../../groupdocs.viewer/filetype/dwfx) | Design Web Format 파일 XPS (.dwfx)는 보기, 검토 또는 인쇄용 디자인 파일을 위한 압축 형식의 XPS 문서로 2D/3D 도면을 나타냅니다. 디자인 데이터의 일부로 그래픽과 텍스트를 포함하며, 압축 형식으로 인해 파일 크기가 감소합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/cad/dwfx). |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | AutoCAD 도면 데이터베이스 파일 (.dwg)은 2D 및 3D 디자인 데이터를 포함하는 독점 바이너리 파일을 나타냅니다. ASCII 파일인 DXF와 달리, DWG는 CAD(Computer Aided Design) 도면을 위한 바이너리 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/cad/dwg). |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | AutoCAD 도면 템플릿 (.dwt)은 DWG 파일로 저장할 수 있는 도면을 만들기 위한 시작점으로 사용되는 AutoCAD 도면 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/cad/dwt). |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | Drawing Exchange Format 파일 (.dxf)은 AutoCAD 도면 파일의 태그된 데이터 표현입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/cad/dxf). |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | Enhanced Windows Metafile (.emf)은 그래픽 이미지를 장치에 독립적으로 나타냅니다. EMF 메타파일은 순차적인 가변 길이 레코드로 구성되어 있으며, 파싱 후 모든 출력 장치에서 저장된 이미지를 렌더링할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/emf)에서 확인하세요. |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | E-Mail Message (.eml)은 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 나타냅니다. 거의 모든 이메일 클라이언트가 RFC-822 인터넷 메시지 형식 표준을 준수하기 때문에 이 파일 형식을 지원합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/email/eml)에서 확인하세요. |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | Apple Mail Message (.emlx)는 Apple에서 구현 및 개발되었습니다. Apple Mail 애플리케이션은 이메일을 내보내기 위해 EMLX 파일 형식을 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/email/emlx)에서 확인하세요. |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | Enhanced Windows Metafile compressed (.emz)은 GZIP으로 압축된 장치에 독립적인 그래픽 이미지를 나타냅니다. EMF 메타파일은 순차적인 가변 길이 레코드로 구성되어 있으며, 파싱 후 모든 출력 장치에서 저장된 이미지를 렌더링할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/emz)에서 확인하세요. |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | Encapsulated PostScript File (.eps)은 단일 페이지의 모습을 설명하는 Encapsulated PostScript 언어 프로그램을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/page-description-language/eps)에서 확인하세요. |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | Open eBook File (.epub)은 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 현재 매우 보편화되어 많은 전자책 리더와 소프트웨어 애플리케이션에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/ebook/epub)에서 확인하세요. |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | Ruby ERB 스크립트 (.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML (SpreadsheetML)은 Excel 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xls)에서 확인하세요. |
| static readonly [FBX](../../groupdocs.viewer/filetype/fbx) | Autodesk FBX Interchange File (FilmBoX) (.fbx)은 3D 모델 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/cad/fbx)에서 확인하세요. |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | Flat XML ODF Template (.fodg)은 Apache OpenOffice의 Draw 애플리케이션에서 벡터 이미지로 그리기 요소를 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/fodg)에서 확인하세요. |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument Presentation (.fodp)은 OpenDocument Flat XML 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/fodp)에서 확인하세요. |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | OpenDocument Flat XML 스프레드시트 (.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | Graphical Interchange Format File (.gif)은 고도로 압축된 이미지 유형입니다. 각 GIF 이미지에서는 일반적으로 픽셀당 최대 8비트, 전체 이미지에서 최대 256색을 허용합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/gif)에서 확인하세요. |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | Groovy 소스 코드 파일 (.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu Zipped File (.gz)은 gzip 압축 애플리케이션으로 생성된 압축 파일입니다. 여러 압축 파일을 포함할 수 있으며 UNIX 및 Linux 시스템에서 일반적으로 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/compression/gz)에서 확인하세요. |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | Gnu Zipped File (.gzip)은 Unix 시스템에서 사용되던 Compress 프로그램을 대체하기 위해 도입된 무료 유틸리티입니다. 이러한 파일은 Windows와 macOS 모두에서 사용할 수 있는 WinZip과 같은 여러 애플리케이션으로 열고 압축을 풀 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/compression/gz)에서 확인하세요. |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C/C++/Objective-C 헤더 파일 (.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | Haml 소스 코드 파일 (.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | C++ 헤더 파일 (.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT (HPGL) (.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | Hypertext Markup Language File (.htm)은 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/web/html)에서 확인하세요. |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | Hypertext Markup Language File (.html)은 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/web/html)에서 확인하세요. |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | Icon File (.ico)은 Microsoft Windows에서 애플리케이션을 나타내는 아이콘으로 사용되는 이미지 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/ico)에서 확인하세요. |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | Industry Foundation Classes File (.ifc)은 건물 객체와 그 속성을 가져오고 내보내기 위한 국제 표준을 설정하는 파일 형식입니다. 이 파일 형식은 다양한 소프트웨어 애플리케이션 간의 상호 운용성을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/cad/ifc)에서 확인하세요. |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | 초기 그래픽 교환 사양 (IGES) (.igs) |
| static readonly [Iso](../../groupdocs.viewer/filetype/iso) | ISO optical disc image는 CD 또는 DVD와 같은 광 디스크의 전체 데이터를 나타내는 압축되지 않은 아카이브 디스크 이미지 파일이며, ISO-9660 표준을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/compression/iso/). |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | JPEG 2000 코드 스트림 (.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000 코드 스트림 (.j2k)은 DCT 압축 대신 웨이브릿 압축을 사용하여 압축된 이미지입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/j2k). |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | Java 소스 코드 파일 (.java) |
| static readonly [JFIF](../../groupdocs.viewer/filetype/jfif) | JPEG 파일 교환 형식 (.jfif)은 플랫폼 간 빠른 교환을 위해 개발된 이미지입니다. 이 형식은 JPEG 압축을 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jfif). |
| static readonly [JLS](../../groupdocs.viewer/filetype/jls) | JPEG-LS (JLS) (.jls) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000 코어 이미지 파일 (.jp2)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jp2). |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | JPEG 2000 코드 스트림 (.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | JPEG 이미지 (.jpeg)는 손실 압축 방식을 사용하여 저장되는 이미지 형식입니다. 압축 결과로 생성된 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | JPEG 2000 이미지 파일 (.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | JPEG 이미지 (.jpg)는 손실 압축 방식을 사용하여 저장되는 이미지 형식입니다. 압축 결과로 생성된 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/jpeg). |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | JPEG 2000 이미지 파일 (.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | JPEG 2000 이미지 파일 (.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | JavaScript 파일 (.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | JavaScript 객체 표기법 파일 (.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | LESS 스타일 시트 (.less) |
| static readonly [Lha](../../groupdocs.viewer/filetype/lha) | LHA 또는 LZH는 무료 압축 유틸리티 및 관련 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/compression/lzh/). |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | 로그 파일 (.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | Objective-C 구현 파일 (.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | Xcode 메이크파일 스크립트 (.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | 이메일 메일함 파일 (.mbox) 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/mbox). |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | Markdown 문서 파일 (.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | MHTML 웹 아카이브 (.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | MIME HTML 파일 (.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | ML 소스 코드 파일 (.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | Objective-C++ 소스 파일 (.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket eBook (.mobi)는 가장 널리 사용되는 전자책 파일 형식 중 하나입니다. 이 형식은 기존 OEB(Open Ebook Format) 형식을 개선한 것이며 Mobipocket Reader의 독점 형식으로 사용되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/ebook/mobi). |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | Microsoft Project 파일 (.mpp)은 프로젝트 관리와 관련된 정보를 통합적으로 저장하는 Microsoft Project 데이터 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft Project 템플릿 (.mpt)에는 .MPP 파일을 만들기 위한 기본 정보와 구조, 문서 설정이 포함되어 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | Microsoft Project Exchange 파일 (.mpx)은 Microsoft Project(MSP)와 Primavera Project Planner, Sciforma, Timerline Precision Estimating 등 MPX 파일 형식을 지원하는 다른 애플리케이션 간에 프로젝트 정보를 전송하기 위한 ASCII 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook 메일 메시지 (.msg)는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용되는 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/email/msg). |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | Lotus Notes 데이터베이스 (.nsf) 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/nsf). |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple numbers는 Excel과 유사한 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Apple numbers 애플리케이션으로 만들 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/numbers). |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D 객체 파일 (.obj)은 Wavefront Technologies에서 도입한 3D 이미지 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/3d/obj/). |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | OpenDocument 그래픽 파일 (.odg)은 Apache OpenOffice의 Draw 애플리케이션에서 벡터 이미지로 그림 요소를 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/odg). |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument 프레젠테이션 (.odp)은 OpenOffice.org에서 OASISOpen 표준으로 사용되는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | OpenDocument 스프레드시트 (.ods)는 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 의미합니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument 텍스트 문서 (.odt)는 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [OFD](../../groupdocs.viewer/filetype/ofd) | GB/T 33190-2016에 정의된 Open Fixed-layout Document (OFD) 형식은 중국 공공 기관에서 PDF를 대체하는 것을 목표로 합니다. |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | Outlook 오프라인 데이터 파일 (.ost)은 Microsoft Outlook을 사용하여 Exchange Server에 등록할 때 로컬 컴퓨터에서 오프라인 모드로 사용자의 메일함 데이터를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/email/ost). |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | OpenDocument 그래픽 템플릿 (.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | OpenDocument 프레젠테이션 템플릿 (.otp)은 OASIS OpenDocument 표준 형식으로 애플리케이션에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/presentation/otp). |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | OpenDocument 스프레드시트 템플릿 (.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | OpenDocument 문서 템플릿 (.ott)은 OASIS의 OpenDocument 표준 형식을 준수하여 애플리케이션에서 생성한 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | OpenXPS 파일 (.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | Printer Command Language 문서 (.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | Portable Document Format 파일 (.pdf)은 1990년대 Adobe에서 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 무관하게 문서 및 기타 참고 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/view/pdf). |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | PHP 소스 코드 파일 (.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | Perl 스크립트 (.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT (HPGL) (.plt)는 Autodesk, Inc.에서 도입한 벡터 기반 플로터 파일이며 특정 CAD 파일에 대한 정보를 포함합니다. 플로팅 세부 사항은 생산에서 정확성과 정밀성을 요구하며, PLT 파일을 사용하면 모든 이미지를 점이 아닌 선으로 인쇄하므로 이를 보장합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/cad/plt). |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | Portable Network Graphic (.png)은 무손실 압축을 사용하는 래스터 이미지 파일 형식의 일종입니다. 이 파일 형식은 Graphics Interchange Format (GIF)을 대체하기 위해 만들어졌으며 저작권 제한이 없습니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/image/png)에서 확인하십시오. |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | PowerPoint Template (.pot)은 PowerPoint 97-2003 버전에서 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pot)에서 확인하십시오. |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm)은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며 추가 프레젠테이션 파일을 만들 때 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/potm)에서 확인하십시오. |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML Presentation Template (.potx)은 Microsoft PowerPoint 2007 이상에서 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/potx)에서 확인하십시오. |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | PowerPoint Slide Show (.pps)은 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일의 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pps)에서 확인하십시오. |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm)은 Microsoft PowerPoint 2007 이상에서 만든 매크로 지원 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppsm)에서 확인하십시오. |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint 2007 이상을 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppsx)에서 확인하십시오. |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint Presentation (.ppt)은 슬라이드 쇼로 표시하기 위한 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 바이너리 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/ppt)에서 확인하십시오. |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation은 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 지원 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pptm)에서 확인하십시오. |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML Presentation (.pptx)은 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전 버전인 바이너리 PPT와 달리 PPTX 형식은 Microsoft PowerPoint Open XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/presentation/pptx)에서 확인하십시오. |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | Java Properties 파일 (.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | PostScript 파일 (.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | PowerShell script 파일 (.ps1)은 Windows PowerShell Cmdlet 파일을 위한 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://fileinfo.com/extension/ps1)에서 확인하십시오. |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | PowerShell script 모듈 매니페스트 (.psd1)는 PowerShell 모듈 매니페스트 스크립트를 위한 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://fileinfo.com/extension/psd1)에서 확인하십시오. |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | PowerShell script 모듈 (.psm1)은 PowerShell 모듈 스크립트를 위한 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://fileinfo.com/extension/psm1)에서 확인하십시오. |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | Outlook Personal Information Store 파일 (.pst)은 다양한 사용자 정보를 저장하는 Outlook Personal Storage Files(또는 Personal Storage Table이라고도 함)를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/email/pst)에서 확인하십시오. |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | Python 스크립트 (.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive (.rar)는 RAR (WINRAR) 압축 방식을 사용하여 생성된 압축 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/compression/rar)에서 확인하십시오. |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | Ruby 소스 코드 (.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | reStructuredText 파일 (.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | Rich Text Format 파일 (.rtf)은 애플리케이션 내에서 사용하기 위해 서식이 지정된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [여기](https://wiki.fileformat.com/word-processing/rtf)에서 확인하십시오. |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | Syntactically Awesome StyleSheets 파일 (.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala 소스 코드 파일 (.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | Scheme 소스 코드 파일 (.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | Generic 스크립트 파일 (.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip (.7z, .7zip)는 LZMA 및 LZMA2 압축을 지원하는 무료 오픈 소스 압축 프로그램입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/compression/7z/). |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash 셸 스크립트 (.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | Standard ML 소스 코드 파일 (.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | 구조적 질의 언어 데이터 파일 (.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | Stereolithography 파일 (.stl)은 3차원 표면 기하학을 나타내는 교환 가능한 파일 형식입니다. 이 파일 형식은 빠른 프로토타이핑, 3D 프린팅 및 컴퓨터 지원 제조와 같은 여러 분야에서 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/cad/stl). |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | Scalable Vector Graphics 파일 (.svg)은 이미지의 모습을 설명하기 위해 XML 기반 텍스트 형식을 사용하는 벡터 그래픽 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/page-description-language/svg). |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | Scalable Vector Graphics 파일 (.svgz)은 XML 기반 텍스트 형식을 사용하고 GZIP으로 압축하여 이미지의 모습을 설명하는 벡터 그래픽 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/svgz). |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | StarOffice Calc 스프레드시트 (.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | Consolidated Unix 파일 아카이브 (.tar)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/compression/tar). |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | Consolidated Unix 파일 아카이브 (.tgz, .tar.gz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/tgz). |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | Consolidated Unix 파일 아카이브 (.txz, .tar.xz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/txz). |
| static readonly [TarZst](../../groupdocs.viewer/filetype/tarzst) | TZST 파일 (.tar.zst, .tzst)은 Zstandard 아카이브(ZST)이며, 내부에 Consolidated Unix 파일 아카이브(Tar)를 포함하고 있습니다. 이는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성됩니다. |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | LaTeX 소스 문서 (.tex)는 프로그래밍 및 마크업 기능을 포함하는 언어로, 문서 조판에 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/page-description-language/tex). |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA(Truevision Advanced Raster Adapter - TARGA)는 TRUEVISION에서 개발한 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/tga). |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | Consolidated Unix 파일 아카이브 (.tgz, .tar.gz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/tgz). |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | Tagged Image File (.tif)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용되는 래스터 이미지를 나타냅니다. 이 형식은 이진, 그레이스케일, 팔레트 색상 및 풀 컬러 이미지 데이터를 여러 색상 공간에서 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/tiff). |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | Tagged Image File Format (.tiff)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용되는 래스터 이미지를 나타냅니다. 이 형식은 이진, 그레이스케일, 팔레트 색상 및 풀 컬러 이미지 데이터를 여러 색상 공간에서 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/tiff). |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | Tab Separated Values 파일 (.tsv)은 탭으로 구분된 데이터를 평문 텍스트 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | Plain Text 파일 (.txt)은 줄 형태의 순수 텍스트를 포함하는 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | Consolidated Unix 파일 아카이브 (.txz, .tar.xz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/txz). |
| static readonly [Tzst](../../groupdocs.viewer/filetype/tzst) | TZST 파일 (.tar.zst, .tzst)은 Zstandard 아카이브(ZST)이며, 내부에 Consolidated Unix 파일 아카이브(Tar)를 포함하고 있습니다. 이는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성됩니다. |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | 알 수 없는 파일 유형을 나타냅니다. |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | Visual Basic 프로젝트 항목 파일 (.vb)은 Microsoft가 .NET 애플리케이션 개발을 위해 만든 Visual Basic 언어로 작성된 소스 코드 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/programming/vb). |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | vCard 파일 (.vcf)은 연락처 정보를 저장하는 디지털 파일 형식입니다. 이 형식은 인기 있는 정보 교환 애플리케이션 간 데이터 교환에 널리 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/email/vcf). |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | Visio Web Drawing (.vdw)은 웹 드로잉을 렌더링하는 데 필요한 스트림 및 스토리지를 지정하는 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/web/vdw). |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | Visio Drawing XML 파일 (.vdx)은 Microsoft Visio에서 만든 모든 도면이나 차트를 나타내며, XML 형식으로 저장되어 .VDX 확장자를 가집니다. Visio Drawing XML 파일은 Microsoft가 개발한 Visio 소프트웨어에서 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vdx). |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | Vim 설정 파일 (.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | Visio Drawing 파일 (.vsd)은 Microsoft Visio 애플리케이션으로 만든 도면으로, 다양한 그래픽 객체와 이들 간의 연결을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vsd). |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | Visio 매크로 사용 가능 도면(.vsdm)은 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 도면 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 도면이며, 파일을 열 때 매크로를 실행할 수 있는 기능도 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | Visio 도면(.vsdx)은 Microsoft Office 2013 이후에 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이는 이전 버전 Microsoft Visio에서 지원하던 이진 파일 형식 .VSD를 대체하기 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | Visio 스텐실 파일(.vss)은 Microsoft Visio 2007 및 이전 버전으로 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 도면에 포함될 수 있는 그리기 객체를 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vss). |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | Visio 매크로 사용 가능 스텐실 파일(.vssm)은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 원하는 형식 지정 및 도형 배치를 할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | Visio 스텐실 파일(.vssx)은 Microsoft Visio 2013 이상으로 만든 드로잉 스텐실입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 도형 컬렉션, 연결선, 흐름도, 네트워크 레이아웃, UML 다이어그램 등 다양한 그리기 요소를 표현하는 것으로 알려져 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio 도면 템플릿(.vst)은 Microsoft Visio로 만든 벡터 이미지 파일이며, 이후 파일을 만들기 위한 템플릿 역할을 합니다. 이러한 템플릿 파일은 이진 파일 형식이며 새로운 Visio 도면을 만들 때 사용되는 기본 레이아웃과 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vst). |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | Visio 매크로 사용 가능 도면 템플릿(.vstm)은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSDX 파일과 달리 VSTM 템플릿으로 만든 파일은 Visual Basic for Applications(VBA) 코드로 개발된 매크로를 실행할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | Visio 도면 템플릿(.vstx)은 Microsoft Visio 2013 이상으로 만든 드로잉 템플릿 파일입니다. 이러한 VSTX 파일은 기본 레이아웃과 설정을 갖춘 .VSDX 파일로 저장되는 Visio 도면을 만들기 위한 시작점을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | Visio 스텐실 XML 파일(.vsx)은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 도면 및 도형으로 구성된 스텐실을 의미합니다. VSX 파일은 XML 파일 형식으로 저장되며 Visio 2013까지 지원되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio 템플릿 XML 파일(.vtx)은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 도면 템플릿입니다. 이 템플릿은 동일한 설정을 가진 여러 Visio 파일을 만들 때 사용할 수 있는 기본 설정 파일을 제공하는 것을 목표로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/vtx). |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP 이미지(.webp)는 무손실 및 손실 압축을 기반으로 하는 최신 래스터 웹 이미지 파일 형식입니다. 이미지 품질은 동일하면서도 이미지 크기를 크게 줄여줍니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/webp). |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | Windows 메타파일(.wmf)은 벡터와 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows Metafile(WMF)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/image/wmf). |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | 압축된 Windows 메타파일(.wmz)은 GZIP 아카이브로 압축된 Microsoft Windows Metafile(WMF)로, 벡터와 비트맵 형식 이미지 데이터를 저장합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/wmz#compressed_windows_metafile). |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | Microsoft Excel 추가 기능(.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | Excel 스프레드시트(.xls)는 Excel 이진 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 만들 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel 이진 스프레드시트(.xlsb)는 Excel 이진 파일 형식을 지정하며, 이는 Excel 워크북 내용을 정의하는 레코드와 구조의 모음입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML 매크로 사용 가능 스프레드시트(.xlsm)는 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML 스프레드시트(.xlsx)는 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 잘 알려진 Microsoft Excel 문서 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel 템플릿(.xlt)은 Microsoft Office 제품군에 포함된 스프레드시트 애플리케이션인 Microsoft Excel로 만든 템플릿 파일입니다. Microsoft Office 97-2003은 새로운 XLT 파일을 만들고 열 수 있었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel 매크로 사용 가능 템플릿(.xltm)은 Microsoft Excel에서 매크로 사용 가능 템플릿 파일로 생성되는 파일을 나타냅니다. XLTM 파일은 구조면에서 XLTX와 유사하지만, XLTX는 매크로가 포함된 템플릿 파일 생성을 지원하지 않습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx)는 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 나타냅니다. 이 템플릿은 XLTX 파일에 지정된 동일한 설정을 가진 XLSX 파일을 생성하는 데 사용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/spreadsheet/xltx). |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML File (.xml). GroupDocs.Viewer는 XML 파일을 처리하기 위한 특수 프로세서를 제공합니다. 자세한 내용은 [documentation](https://docs.groupdocs.com/viewer/net/render-xml-documents/)을 참조하세요. |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML Paper Specification File (.xps)는 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다. 이 형식은 Microsoft가 EMF 파일 형식을 대체하기 위해 개발했으며 PDF 파일 형식과 유사하지만 문서의 레이아웃, 외관 및 인쇄 정보를 XML로 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/page-description-language/xps). |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ file (.xz)는 LZMA 알고리즘을 기반으로 하는 고비율 압축 알고리즘으로 압축된 아카이브 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://fileinfo.com/extension/xz). |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | YAML 문서 (.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | Zipped File (.zip)는 하나 이상의 파일이나 디렉터리를 포함할 수 있는 아카이브를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://wiki.fileformat.com/compression/zip). |
| static readonly [Zstandard](../../groupdocs.viewer/filetype/zstandard) | ZST file은 Zstandard(zstd) 압축 알고리즘으로 생성된 압축 파일입니다. 이 알고리즘은 무손실 압축을 사용하여 파일을 압축합니다. ZST 파일은 데이터베이스, 파일 시스템, 네트워크, 게임 등 다양한 유형의 파일을 압축하는 데 사용할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here](https://docs.fileformat.com/compression/zst/). |

### 또 보기

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
