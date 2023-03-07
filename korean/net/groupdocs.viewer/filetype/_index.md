---
title: FileType
second_title: .NET API 참조용 GroupDocs.Viewer
description: 파일 형식을 나타냅니다. 에서 지원하는 모든 파일 형식 목록을 얻을 수 있는 방법을 제공합니다.GroupDocs.Viewer .
type: docs
weight: 70
url: /ko/net/groupdocs.viewer/filetype/
---
## FileType class

파일 형식을 나타냅니다. 에서 지원하는 모든 파일 형식 목록을 얻을 수 있는 방법을 제공합니다.**GroupDocs.Viewer** .

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FileType](filetype#constructor)() | 의 새 인스턴스를 초기화합니다.[`FileType`](../filetype) 클래스. |
| [FileType](filetype#constructor_1)(string, string) | 의 새 인스턴스를 초기화합니다.[`FileType`](../filetype) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.viewer/filetype/extension) { get; set; } | 파일 이름 접미사(마침표 "." 포함) 예: ".doc". |
| [FileFormat](../../groupdocs.viewer/filetype/fileformat) { get; set; } | 파일 유형 이름 예: "Microsoft Word 문서". |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.viewer/filetype/fromextension)(string) | 파일 확장자를 파일 유형에 매핑합니다. |
| static [FromFilePath](../../groupdocs.viewer/filetype/fromfilepath)(string) | 파일 확장자를 추출하고 파일 유형에 매핑합니다. |
| static [FromMediaType](../../groupdocs.viewer/filetype/frommediatype)(string) | 파일 미디어 유형을 파일 유형에 매핑합니다. 예를 들어 'application/pdf'가 매핑됩니다.[`PDF`](./pdf) . |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream)(Stream) | 파일 서명을 읽어 파일 형식을 감지합니다. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_1)(Stream, ILogger) | 파일 서명을 읽어 파일 형식을 감지합니다. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_2)(Stream, string) | 파일 서명을 읽어 파일 형식을 감지합니다. |
| static [FromStream](../../groupdocs.viewer/filetype/fromstream#fromstream_3)(Stream, string, ILogger) | 파일 서명을 읽어 파일 형식을 감지합니다. |
| [Equals](../../groupdocs.viewer/filetype/equals#equals)(FileType) | 현재 여부를 결정합니다.[`FileType`](../filetype) 지정된 것과 동일합니다[`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.viewer/filetype/equals#equals_1)(object) | 현재 여부를 결정합니다.[`FileType`](../filetype) 지정된 개체와 동일합니다. |
| override [GetHashCode](../../groupdocs.viewer/filetype/gethashcode)() | 현재 해시 코드를 반환합니다.[`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.viewer/filetype/tostring)() | 현재 개체를 나타내는 문자열을 반환합니다. |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding)(Stream) | 텍스트 감지 시도[`TXT`](./txt) ,[`TSV`](./tsv) , 그리고[`CSV`](./csv) stream. 로 파일 인코딩 |
| static [DetectEncoding](../../groupdocs.viewer/filetype/detectencoding#detectencoding_1)(string) | 텍스트 감지 시도[`TXT`](./txt) ,[`TSV`](./tsv) , 그리고[`CSV`](./csv)path. 로 파일 인코딩 |
| static [GetSupportedFileTypes](../../groupdocs.viewer/filetype/getsupportedfiletypes)() | 지원되는 파일 유형 검색 |
| [operator ==](../../groupdocs.viewer/filetype/op_equality) | 여부를 결정합니다.[`FileType`](../filetype) 객체는 동일합니다. |
| [operator !=](../../groupdocs.viewer/filetype/op_inequality) | 여부를 결정합니다.[`FileType`](../filetype) 개체가 동일하지 않습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [AI](../../groupdocs.viewer/filetype/ai) | Adobe Illustrator(.ai)는 Adobe Illustrator 그림용 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/ai#adobe_illustrator_file) . |
| static readonly [APNG](../../groupdocs.viewer/filetype/apng) | 애니메이션 휴대용 네트워크 그래픽(.apng)은 애니메이션을 지원하는 PNG 형식의 확장입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/apng) . |
| static readonly [AS](../../groupdocs.viewer/filetype/as) | 액션스크립트 파일(.as) |
| static readonly [AS3](../../groupdocs.viewer/filetype/as3) | 액션스크립트 파일(.as) |
| static readonly [ASM](../../groupdocs.viewer/filetype/asm) | 어셈블리 언어 소스 코드 파일(.asm) |
| static readonly [BAT](../../groupdocs.viewer/filetype/bat) | DOS 배치 파일(.bat) |
| static readonly [BMP](../../groupdocs.viewer/filetype/bmp) | 비트맵 이미지 파일(.bmp)은 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이러한 이미지는 그래픽 어댑터와 독립적이며 DIB(장치 독립적 비트맵) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/bmp) . |
| static readonly [BZ2](../../groupdocs.viewer/filetype/bz2) | Bzip2 압축 파일(.bz2)은 주로 UNIX 또는 Linux 시스템에서 BZIP2 오픈 소스 압축 방법을 사용하여 생성된 압축 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/compression/bz2) . |
| static readonly [C](../../groupdocs.viewer/filetype/c) | C/C++ 소스 코드 파일(.c) |
| static readonly [CC](../../groupdocs.viewer/filetype/cc) | C++ 소스 코드 파일(.cc) |
| static readonly [CDR](../../groupdocs.viewer/filetype/cdr) | CorelDraw Vector Graphic Drawing(.cdr)은 디지털 이미지를 인코딩하고 압축하기 위해 CorelDRAW로 기본적으로 생성되는 벡터 드로잉 이미지 파일입니다. 이러한 도면 파일에는 이미지 내용의 벡터 표현을 위한 텍스트, 선, 모양, 이미지, 색상 및 효과가 포함되어 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/cdr) . |
| static readonly [CF2](../../groupdocs.viewer/filetype/cf2) | 공통 파일 형식 File 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/cf2) . |
| static readonly [CGM](../../groupdocs.viewer/filetype/cgm) | 컴퓨터 그래픽 메타파일(.cgm)은 벡터 그래픽(2D), 래스터 그래픽 및 텍스트를 저장하고 교환하기 위한 무료 플랫폼 독립적 국제 표준 메타파일 형식입니다. CGM은 이미지 생성을 위해 객체 지향 접근 방식과 많은 기능 제공을 사용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/cgm) . |
| static readonly [CHM](../../groupdocs.viewer/filetype/chm) | Microsoft Compiled HTML Help File(.chm)은 HELP(일부 응용 프로그램에 대한 문서) 문서의 잘 알려진 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/web/chm/) . |
| static readonly [CMAKE](../../groupdocs.viewer/filetype/cmake) | CMake 파일(.cmake) |
| static readonly [CMX](../../groupdocs.viewer/filetype/cmx) | Corel Exchange(.cmx)는 벡터 그래픽과 비트맵 그래픽을 포함할 수 있는 드로잉 이미지 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/cmx) . |
| static readonly [CPIO](../../groupdocs.viewer/filetype/cpio) | Cpio는 일반 파일 아카이버 유틸리티 및 관련 파일 형식입니다. 주로 Unix 계열 컴퓨터 운영 체제에 설치됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/compression/cpio) . |
| static readonly [CPP](../../groupdocs.viewer/filetype/cpp) | C++ 소스 코드 파일(.cpp) |
| static readonly [CS](../../groupdocs.viewer/filetype/cs) | C# 소스 코드 파일(.cs)은 C# 프로그래밍 언어용 소스 코드 파일입니다. .NET Framework와 함께 사용하기 위해 Microsoft에서 도입했습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/programming/cs) . |
| static readonly [CSS](../../groupdocs.viewer/filetype/css) | 캐스케이딩 스타일시트(.css) |
| static readonly [CSV](../../groupdocs.viewer/filetype/csv) | 쉼표로 구분된 값 파일(.csv)은 쉼표로 구분된 값이 있는 데이터 레코드가 포함된 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [CXX](../../groupdocs.viewer/filetype/cxx) | C++ 소스 코드 파일(.cxx) |
| static readonly [DCM](../../groupdocs.viewer/filetype/dcm) | DICOM 이미지(.dcm)는 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/dcm) . |
| static readonly [DGN](../../groupdocs.viewer/filetype/dgn) | MicroStation 디자인 파일(.dgn)은 MicroStation 및 Intergraph Interactive Graphics Design System과 같은 CAD 응용 프로그램에서 생성하고 지원하는 도면입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [DIB](../../groupdocs.viewer/filetype/dib) | 장치 독립적 비트맵 파일(.dib) |
| static readonly [DIFF](../../groupdocs.viewer/filetype/diff) | 패치 파일(.diff) |
| static readonly [DJVU](../../groupdocs.viewer/filetype/djvu) | DjVu 이미지(.djvu)는 특히 텍스트, 그림, 이미지 및 사진의 조합을 포함하는 스캔 문서 및 책을 위한 그래픽 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/djvu) . |
| static readonly [DNG](../../groupdocs.viewer/filetype/dng) | 디지털 네거티브 사양(.dng)은 Raw 파일 저장에 사용되는 디지털 카메라 이미지 형식입니다. 2004년 9월 Adobe에서 개발했습니다. 기본적으로 디지털 사진용으로 개발되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/dng) . |
| static readonly [DOC](../../groupdocs.viewer/filetype/doc) | Microsoft Word 문서(.doc)는 Microsoft Word 또는 기타 워드 프로세싱 문서에서 생성된 이진 파일 형식의 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [DOCM](../../groupdocs.viewer/filetype/docm) | Word Open XML 매크로 사용 문서(.docm)는 매크로를 실행할 수 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [DOCX](../../groupdocs.viewer/filetype/docx) | Microsoft Word Open XML 문서(.docx)는 Microsoft Word 문서의 잘 알려진 형식입니다. 2007년부터 Microsoft Office 2007 출시와 함께 도입된 이 새로운 문서 형식의 구조는 일반 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [DOT](../../groupdocs.viewer/filetype/dot) | Word 문서 템플릿(.dot)은 Microsoft Word에서 추가 DOC 또는 DOCX 파일 생성을 위한 사전 형식 설정을 갖도록 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [DOTM](../../groupdocs.viewer/filetype/dotm) | Word Open XML 매크로 사용 문서 템플릿(.dotm)은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [DOTX](../../groupdocs.viewer/filetype/dotx) | Word Open XML 문서 템플릿(.dotx)은 Microsoft Word에서 추가 DOCX 파일 생성을 위한 미리 서식이 지정된 설정을 갖도록 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [DWF](../../groupdocs.viewer/filetype/dwf) | 디자인 웹 형식 파일(.dwf)은 디자인 파일 보기, 검토 또는 인쇄를 위한 압축 형식의 2D/3D 도면을 나타냅니다. 디자인 데이터의 일부로 그래픽과 텍스트가 포함되어 있으며 압축 형식으로 인해 파일 크기가 줄어듭니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [DWFX](../../groupdocs.viewer/filetype/dwfx) | 디자인 웹 형식 파일 XPS(.dwfx)는 디자인 파일 보기, 검토 또는 인쇄를 위한 압축 형식의 XPS 문서로 2D/3D 도면을 나타냅니다. 디자인 데이터의 일부로 그래픽과 텍스트가 포함되어 있으며 압축 형식으로 인해 파일 크기가 줄어듭니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/dwfx) . |
| static readonly [DWG](../../groupdocs.viewer/filetype/dwg) | AutoCAD 도면 데이터베이스 파일(.dwg)은 2D 및 3D 설계 데이터를 포함하는 데 사용되는 독점 바이너리 파일을 나타냅니다. ASCII 파일인 DXF와 마찬가지로 DWG는 CAD(Computer Aided Design) 도면의 이진 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [DWT](../../groupdocs.viewer/filetype/dwt) | AutoCAD 드로잉 템플릿(.dwt)은 DWG 파일로 저장할 수 있는 드로잉을 만들기 위한 스타터로 사용되는 AutoCAD 드로잉 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [DXF](../../groupdocs.viewer/filetype/dxf) | 도면 교환 형식 파일(.dxf)은 AutoCAD 도면 파일의 태그가 지정된 데이터 표현입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [EMF](../../groupdocs.viewer/filetype/emf) | 향상된 Windows 메타파일(.emf)은 그래픽 이미지를 장치 독립적으로 나타냅니다. EMF의 메타파일은 모든 출력 장치에서 구문 분석한 후 저장된 이미지를 렌더링할 수 있는 시간순의 가변 길이 레코드로 구성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/emf) . |
| static readonly [EML](../../groupdocs.viewer/filetype/eml) | 전자 메일 메시지(.eml)는 Outlook 및 기타 관련 응용 프로그램을 사용하여 저장된 전자 메일 메시지를 나타냅니다. 거의 모든 이메일 클라이언트는 RFC-822 인터넷 메시지 형식 표준을 준수하기 위해 이 파일 형식을 지원합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/eml) . |
| static readonly [EMLX](../../groupdocs.viewer/filetype/emlx) | Apple Mail Message(.emlx)는 Apple에서 구현하고 개발합니다. Apple Mail 애플리케이션은 이메일을 내보내기 위해 EMLX 파일 형식을 사용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/emlx) . |
| static readonly [EMZ](../../groupdocs.viewer/filetype/emz) | 향상된 Windows 메타파일 압축(.emz)은 GZIP에 의해 장치 독립적으로 압축된 그래픽 이미지를 나타냅니다. EMF의 메타파일은 모든 출력 장치에서 구문 분석한 후 저장된 이미지를 렌더링할 수 있는 시간순의 가변 길이 레코드로 구성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/emz) . |
| static readonly [EPS](../../groupdocs.viewer/filetype/eps) | 캡슐화된 포스트스크립트 파일(.eps)은 단일 페이지의 모양을 설명하는 캡슐화된 포스트스크립트 언어 프로그램을 설명합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/eps) . |
| static readonly [EPUB](../../groupdocs.viewer/filetype/epub) | Open eBook File(.epub)은 발행인과 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 현재 매우 일반적이어서 많은 e-reader 및 소프트웨어 응용 프로그램에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/ebook/epub) . |
| static readonly [ERB](../../groupdocs.viewer/filetype/erb) | 루비 ERB 스크립트(.erb) |
| static readonly [Excel2003XML](../../groupdocs.viewer/filetype/excel2003xml) | Excel 2003 XML(SpreadsheetML)은 Excel 이진 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 기타 유사한 스프레드시트 프로그램으로 만들 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [FBX](../../groupdocs.viewer/filetype/fbx) | Autodesk FBX 교환 파일(FilmBoX)(.fbx)은 3D 모델 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/fbx) . |
| static readonly [FODG](../../groupdocs.viewer/filetype/fodg) | 플랫 XML ODF 템플릿(.fodg)은 Apache OpenOffice의 그리기 응용 프로그램에서 그리기 요소를 벡터 이미지로 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/fodg) . |
| static readonly [FODP](../../groupdocs.viewer/filetype/fodp) | OpenDocument 프레젠테이션(.fodp)은 OpenDocument 플랫 XML 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/fodp) . |
| static readonly [FODS](../../groupdocs.viewer/filetype/fods) | OpenDocument 플랫 XML 스프레드시트(.fods) |
| static readonly [GIF](../../groupdocs.viewer/filetype/gif) | Graphical Interchange Format File(.gif)은 고도로 압축된 이미지 유형입니다. 각 이미지 GIF는 일반적으로 픽셀당 최대 8비트를 허용하고 이미지 전체에 최대 256색을 허용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/gif) . |
| static readonly [GROOVY](../../groupdocs.viewer/filetype/groovy) | Groovy 소스 코드 파일(.groovy) |
| static readonly [GZ](../../groupdocs.viewer/filetype/gz) | Gnu 압축 파일(.gz)은 gzip 압축 응용 프로그램으로 만든 압축 파일입니다. 여러 압축 파일을 포함할 수 있으며 UNIX 및 Linux 시스템에서 일반적으로 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/compression/gz) . |
| static readonly [GZIP](../../groupdocs.viewer/filetype/gzip) | Gnu 압축 파일(.gzip)은 Unix 시스템에서 사용되는 Compress 프로그램을 대체하기 위한 무료 유틸리티로 도입되었습니다. 이러한 파일은 Windows와 MacOS 모두에서 사용할 수 있는 WinZip과 같은 여러 응용 프로그램으로 열고 추출할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/compression/gz) . |
| static readonly [H](../../groupdocs.viewer/filetype/h) | C/C++/Objective-C 헤더 파일(.h) |
| static readonly [HAML](../../groupdocs.viewer/filetype/haml) | Haml 소스 코드 파일(.haml) |
| static readonly [HH](../../groupdocs.viewer/filetype/hh) | C++ 헤더 파일(.hh) |
| static readonly [HPG](../../groupdocs.viewer/filetype/hpg) | PLT(HPGL)(.hpg) |
| static readonly [HTM](../../groupdocs.viewer/filetype/htm) | Hypertext Markup Language 파일(.htm)은 브라우저에 표시하기 위해 만든 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/web/html) . |
| static readonly [HTML](../../groupdocs.viewer/filetype/html) | Hypertext Markup Language 파일(.html)은 브라우저에 표시하기 위해 만든 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/web/html) . |
| static readonly [ICO](../../groupdocs.viewer/filetype/ico) | 아이콘 파일(.ico)은 Microsoft Windows에서 애플리케이션을 나타내는 아이콘으로 사용되는 이미지 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/ico) . |
| static readonly [IFC](../../groupdocs.viewer/filetype/ifc) | Industry Foundation Classes 파일(.ifc)은 건물 객체 및 해당 속성을 가져오고 내보내는 국제 표준을 설정하는 파일 형식입니다. 이 파일 형식은 서로 다른 소프트웨어 응용 프로그램 간의 상호 운용성을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [IGS](../../groupdocs.viewer/filetype/igs) | 초기 그래픽 교환 사양(IGES)(.igs) |
| static readonly [J2C](../../groupdocs.viewer/filetype/j2c) | JPEG 2000 코드 스트림(.j2c) |
| static readonly [J2K](../../groupdocs.viewer/filetype/j2k) | JPEG 2000 Code Stream(.j2k)은 DCT 압축 대신 웨이블릿 압축을 사용하여 압축한 이미지입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/j2k) . |
| static readonly [JAVA](../../groupdocs.viewer/filetype/java) | Java 소스 코드 파일(.java) |
| static readonly [JLS](../../groupdocs.viewer/filetype/jls) | JPEG-LS(JLS)(.jls) |
| static readonly [JP2](../../groupdocs.viewer/filetype/jp2) | JPEG 2000 Core Image File(.jp2)은 이미지 코딩 시스템이자 최신 이미지 압축 표준입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/jp2) . |
| static readonly [JPC](../../groupdocs.viewer/filetype/jpc) | JPEG 2000 코드 스트림(.jpc) |
| static readonly [JPEG](../../groupdocs.viewer/filetype/jpeg) | JPEG 이미지(.jpeg)는 손실 압축 방식을 사용하여 저장되는 일종의 이미지 형식입니다. 압축 결과 출력 이미지는 저장소 크기와 이미지 품질 간의 절충안입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPF](../../groupdocs.viewer/filetype/jpf) | JPEG 2000 이미지 파일(.jpf) |
| static readonly [JPG](../../groupdocs.viewer/filetype/jpg) | JPEG 이미지(.jpg)는 손실 압축 방식을 사용하여 저장되는 일종의 이미지 형식입니다. 압축 결과 출력 이미지는 저장소 크기와 이미지 품질 간의 절충안입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/jpeg) . |
| static readonly [JPM](../../groupdocs.viewer/filetype/jpm) | JPEG 2000 이미지 파일(.jpm) |
| static readonly [JPX](../../groupdocs.viewer/filetype/jpx) | JPEG 2000 이미지 파일(.jpx) |
| static readonly [JS](../../groupdocs.viewer/filetype/js) | JavaScript 파일(.js) |
| static readonly [JSON](../../groupdocs.viewer/filetype/json) | JavaScript 개체 표기 파일(.json) |
| static readonly [LESS](../../groupdocs.viewer/filetype/less) | LESS 스타일 시트(.less) |
| static readonly [LOG](../../groupdocs.viewer/filetype/log) | 로그 파일(.log) |
| static readonly [M](../../groupdocs.viewer/filetype/m) | Objective-C 구현 파일(.m) |
| static readonly [MAKE](../../groupdocs.viewer/filetype/make) | Xcode Makefile 스크립트(.make) |
| static readonly [MBOX](../../groupdocs.viewer/filetype/mbox) | 이메일 사서함 파일(.mbox) 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/mbox) . |
| static readonly [MD](../../groupdocs.viewer/filetype/md) | 마크다운 문서 파일(.md) |
| static readonly [MHT](../../groupdocs.viewer/filetype/mht) | MHTML 웹 아카이브(.mht) |
| static readonly [MHTML](../../groupdocs.viewer/filetype/mhtml) | MIME HTML 파일(.mhtml) |
| static readonly [ML](../../groupdocs.viewer/filetype/ml) | ML 소스 코드 파일(.ml) |
| static readonly [MM](../../groupdocs.viewer/filetype/mm) | Objective-C++ 소스 파일(.mm) |
| static readonly [MOBI](../../groupdocs.viewer/filetype/mobi) | Mobipocket eBook(.mobi)은 가장 널리 사용되는 전자책 파일 형식 중 하나입니다. 이 형식은 이전 OEB(Open Ebook Format) 형식을 개선한 것으로 Mobipocket Reader의 독점 형식으로 사용되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/ebook/mobi) . |
| static readonly [MPP](../../groupdocs.viewer/filetype/mpp) | Microsoft Project File(.mpp)은 프로젝트 관리와 관련된 정보를 통합적으로 저장하는 Microsoft Project 데이터 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/project-management/mpp) . |
| static readonly [MPT](../../groupdocs.viewer/filetype/mpt) | Microsoft 프로젝트 템플릿(.mpt)에는 .MPP 파일을 만들기 위한 문서 설정과 함께 기본 정보 및 구조가 포함되어 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/project-management/mpt) . |
| static readonly [MPX](../../groupdocs.viewer/filetype/mpx) | Microsoft Project Exchange 파일(.mpx)은 Microsoft Project(MSP)와 Primavera Project Planner, Sciforma 및 Timerline Precision Estimating과 같은 MPX 파일 형식을 지원하는 다른 응용 프로그램 간에 프로젝트 정보를 전송하기 위한 ASCII 파일 형식입니다. 자세히 알아보기 이 파일 형식[여기](https://wiki.fileformat.com/project-management/mpx) . |
| static readonly [MSG](../../groupdocs.viewer/filetype/msg) | Outlook 메일 메시지(.msg)는 Microsoft Outlook 및 Exchange에서 전자 메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용하는 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/msg) . |
| static readonly [NSF](../../groupdocs.viewer/filetype/nsf) | Lotus Notes 데이터베이스(.nsf) 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/nsf) . |
| static readonly [NUMBERS](../../groupdocs.viewer/filetype/numbers) | Apple 숫자는 이진 파일 형식과 같은 Excel을 나타냅니다. 이러한 파일은 Apple 번호 응용 프로그램에서 만들 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/numbers) . |
| static readonly [OBJ](../../groupdocs.viewer/filetype/obj) | Wavefront 3D 개체 파일(.obj)은 Wavefront Technologies 에서 도입한 3D 이미지 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/3d/obj/) . |
| static readonly [ODG](../../groupdocs.viewer/filetype/odg) | OpenDocument 그래픽 파일(.odg)은 Apache OpenOffice의 Draw 응용 프로그램에서 드로잉 요소를 벡터 이미지로 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/odg) . |
| static readonly [ODP](../../groupdocs.viewer/filetype/odp) | OpenDocument 프레젠테이션(.odp)은 OASISOpen 표준에서 OpenOffice.org에서 사용하는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [ODS](../../groupdocs.viewer/filetype/ods) | OpenDocument 스프레드시트(.ods)는 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 나타냅니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [ODT](../../groupdocs.viewer/filetype/odt) | OpenDocument 텍스트 문서(.odt)는 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 응용 프로그램으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [ONE](../../groupdocs.viewer/filetype/one) | OneNote 문서(.one)는 Microsoft OneNote 응용 프로그램에서 생성됩니다. OneNote를 사용하면 메모를 작성하기 위해 드래프트 패드를 사용하는 것처럼 응용 프로그램을 사용하여 정보를 수집할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/note-taking/one) . |
| static readonly [OST](../../groupdocs.viewer/filetype/ost) | Outlook 오프라인 데이터 파일(.ost)은 Microsoft Outlook을 사용하여 Exchange Server에 등록할 때 로컬 컴퓨터에서 오프라인 모드로 있는 사용자 사서함 데이터를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/ost) . |
| static readonly [OTG](../../groupdocs.viewer/filetype/otg) | OpenDocument 그래픽 템플릿(.otg) |
| static readonly [OTP](../../groupdocs.viewer/filetype/otp) | OpenDocument 프레젠테이션 템플릿(.otp)은 OASIS OpenDocument 표준 형식의 응용 프로그램에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [OTS](../../groupdocs.viewer/filetype/ots) | OpenDocument 스프레드시트 템플릿(.ots) |
| static readonly [OTT](../../groupdocs.viewer/filetype/ott) | OpenDocument 문서 템플릿(.ott)은 OASIS의 OpenDocument 표준 형식을 준수하는 응용 프로그램에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [OXPS](../../groupdocs.viewer/filetype/oxps) | OpenXPS 파일(.oxps) |
| static readonly [PCL](../../groupdocs.viewer/filetype/pcl) | 프린터 명령 언어 문서(.pcl) |
| static readonly [PDF](../../groupdocs.viewer/filetype/pdf) | Portable Document Format File(.pdf)은 Adobe에서 1990년대에 만든 문서 유형입니다. 이 파일 형식의 목적은 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식으로 문서 및 기타 참조 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/view/pdf) . |
| static readonly [PHP](../../groupdocs.viewer/filetype/php) | PHP 소스 코드 파일(.php) |
| static readonly [PL](../../groupdocs.viewer/filetype/pl) | Perl 스크립트(.pl) |
| static readonly [PLT](../../groupdocs.viewer/filetype/plt) | PLT(HPGL)(.plt)는 Autodesk, Inc.에서 소개한 벡터 기반 플로터 파일로 특정 CAD 파일에 대한 정보가 포함되어 있습니다. 플로팅 디테일은 제작상 정확성과 정밀도가 요구되며 PLT 파일을 사용하면 모든 이미지가 점 대신 선을 사용하여 인쇄되므로 이를 보장합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/plt) . |
| static readonly [PNG](../../groupdocs.viewer/filetype/png) | Portable Network Graphic(.png)은 무손실 압축을 사용하는 일종의 래스터 이미지 파일 형식입니다. 이 파일 형식은 GIF(Graphics Interchange Format)를 대체하기 위해 만들어졌으며 저작권 제한이 없습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/png) . |
| static readonly [POT](../../groupdocs.viewer/filetype/pot) | PowerPoint 템플릿(.pot)은 PowerPoint 97-2003 버전에서 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [POTM](../../groupdocs.viewer/filetype/potm) | PowerPoint Open XML 매크로 사용 프레젠테이션 템플릿(.potm)은 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상에서 생성되며 추가 프레젠테이션 파일을 생성하는 데 사용할 수 있는 기본 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [POTX](../../groupdocs.viewer/filetype/potx) | PowerPoint Open XML 프레젠테이션 템플릿(.potx)은 Microsoft PowerPoint 2007 이상에서 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [PPS](../../groupdocs.viewer/filetype/pps) | PowerPoint 슬라이드 쇼(.pps)는 슬라이드 쇼 목적으로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [PPSM](../../groupdocs.viewer/filetype/ppsm) | PowerPoint Open XML 매크로 사용 슬라이드(.ppsm)는 Microsoft PowerPoint 2007 이상에서 만든 매크로 사용 슬라이드 쇼 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [PPSX](../../groupdocs.viewer/filetype/ppsx) | PowerPoint Open XML 슬라이드 쇼(.ppsx) 파일은 슬라이드 쇼 목적으로 Microsoft PowerPoint 2007 이상을 사용하여 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [PPT](../../groupdocs.viewer/filetype/ppt) | PowerPoint 프레젠테이션(.ppt)은 슬라이드 쇼로 표시하기 위한 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. Microsoft PowerPoint 97-2003에서 사용하는 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [PPTM](../../groupdocs.viewer/filetype/pptm) | PowerPoint Open XML 매크로 사용 프레젠테이션은 Microsoft PowerPoint 2007 이상 버전에서 만든 매크로 사용 프레젠테이션 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [PPTX](../../groupdocs.viewer/filetype/pptx) | PowerPoint Open XML 프레젠테이션(.pptx)은 널리 사용되는 Microsoft PowerPoint 응용 프로그램으로 만든 프레젠테이션 파일입니다. 프레젠테이션 파일 형식 PPT의 이전 버전인 바이너리와 달리 PPTX 형식은 Microsoft PowerPoint 개방형 XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [PROPERTIES](../../groupdocs.viewer/filetype/properties) | Java 속성 파일(.properties) |
| static readonly [PS](../../groupdocs.viewer/filetype/ps) | 포스트스크립트 파일(.ps) |
| static readonly [PS1](../../groupdocs.viewer/filetype/ps1) | PowerShell 스크립트 파일(.ps1) Windows PowerShell Cmdlet 파일용 파일 형식. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/ps1) . |
| static readonly [PSB](../../groupdocs.viewer/filetype/psb) | Photoshop 대용량 문서 형식(.psb)은 그래픽 디자인 및 개발에 사용되는 Photoshop 대용량 문서 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/psb) . |
| static readonly [PSD](../../groupdocs.viewer/filetype/psd) | Adobe Photoshop 문서(.psd)는 그래픽 디자인 및 개발에 사용되는 Adobe Photoshop의 기본 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/psd) . |
| static readonly [PSD1](../../groupdocs.viewer/filetype/psd1) | PowerShell 스크립트 모듈 매니페스트(.psd1) PowerShell 모듈 매니페스트 스크립트용 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/psd1) . |
| static readonly [PSM1](../../groupdocs.viewer/filetype/psm1) | PowerShell 스크립트 모듈(.psm1) PowerShell 모듈 스크립트용 파일 형식. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/psm1) . |
| static readonly [PST](../../groupdocs.viewer/filetype/pst) | Outlook 개인 정보 저장소 파일(.pst)은 다양한 사용자 정보를 저장하는 Outlook 개인 저장소 파일(개인 저장소 테이블이라고도 함)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/pst) . |
| static readonly [PY](../../groupdocs.viewer/filetype/py) | 파이썬 스크립트(.py) |
| static readonly [RAR](../../groupdocs.viewer/filetype/rar) | Roshal ARchive(.rar)는 RAR(WINRAR) 압축 방법을 사용하여 생성된 압축 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/compression/rar) . |
| static readonly [RB](../../groupdocs.viewer/filetype/rb) | Ruby 소스 코드(.rb) |
| static readonly [RST](../../groupdocs.viewer/filetype/rst) | reStructuredText 파일(.rst) |
| static readonly [RTF](../../groupdocs.viewer/filetype/rtf) | 리치 텍스트 형식 파일(.rtf)은 응용 프로그램 내에서 사용하기 위해 형식이 지정된 텍스트 및 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [SASS](../../groupdocs.viewer/filetype/sass) | 구문적으로 멋진 StyleSheets 파일(.sass) |
| static readonly [SCALA](../../groupdocs.viewer/filetype/scala) | Scala 소스 코드 파일(.scala) |
| static readonly [SCM](../../groupdocs.viewer/filetype/scm) | 스키마 소스 코드 파일(.scm) |
| static readonly [SCRIPT](../../groupdocs.viewer/filetype/script) | 일반 스크립트 파일(.script) |
| static readonly [SevenZip](../../groupdocs.viewer/filetype/sevenzip) | 7Zip(.7z, .7zip)은 LZMA 및 LZMA2 압축을 사용하는 무료 오픈 소스 아카이버입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/compression/7z/) . |
| static readonly [SH](../../groupdocs.viewer/filetype/sh) | Bash 셸 스크립트(.sh) |
| static readonly [SML](../../groupdocs.viewer/filetype/sml) | 표준 ML 소스 코드 파일(.sml) |
| static readonly [SQL](../../groupdocs.viewer/filetype/sql) | 구조적 쿼리 언어 데이터 파일(.sql) |
| static readonly [STL](../../groupdocs.viewer/filetype/stl) | 스테레오리소그래피 파일(.stl)은 3차원 표면 형상을 나타내는 교환 가능한 파일 형식입니다. 파일 형식은 신속한 프로토타이핑, 3D 인쇄 및 컴퓨터 지원 제조와 같은 여러 분야에서 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/cad/stl) . |
| static readonly [SVG](../../groupdocs.viewer/filetype/svg) | 확장 가능한 벡터 그래픽 파일(.svg)은 이미지 모양을 설명하기 위해 XML 기반 텍스트 형식을 사용하는 스칼라 벡터 그래픽 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/svg) . |
| static readonly [SVGZ](../../groupdocs.viewer/filetype/svgz) | 확장 가능한 벡터 그래픽 파일(.svgz)은 XML 기반 텍스트 형식을 사용하는 스칼라 벡터 그래픽 파일이며 이미지 모양을 설명하기 위해 GZIP으로 압축됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/svgz) . |
| static readonly [SXC](../../groupdocs.viewer/filetype/sxc) | StarOffice Calc 스프레드시트(.sxc) |
| static readonly [TAR](../../groupdocs.viewer/filetype/tar) | Consolidated Unix File Archive(.tar)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/compression/tar) . |
| static readonly [TARGZ](../../groupdocs.viewer/filetype/targz) | Consolidated Unix File Archive(.tgz, .tar.gz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/tgz) . |
| static readonly [TARXZ](../../groupdocs.viewer/filetype/tarxz) | Consolidated Unix File Archive(.txz, .tar.xz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/txz) . |
| static readonly [TEX](../../groupdocs.viewer/filetype/tex) | LaTeX 소스 문서(.tex)는 문서 조판에 사용되는 마크업 기능과 프로그래밍으로 구성된 언어입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/tex) . |
| static readonly [TGA](../../groupdocs.viewer/filetype/tga) | Truevision TGA(Truevision Advanced Raster Adapter - TARGA)는 TRUEVISION에서 개발한 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/tga) . |
| static readonly [TGZ](../../groupdocs.viewer/filetype/tgz) | Consolidated Unix File Archive(.tgz, .tar.gz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/tgz) . |
| static readonly [TIF](../../groupdocs.viewer/filetype/tif) | 태그가 지정된 이미지 파일(.tif)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 여러 색 공간에서 이중 수준, 회색조, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TIFF](../../groupdocs.viewer/filetype/tiff) | Tagged Image File Format(.tiff)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 여러 색 공간에서 이중 수준, 회색조, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/tiff) . |
| static readonly [TSV](../../groupdocs.viewer/filetype/tsv) | 탭으로 구분된 값 파일(.tsv)은 일반 텍스트 형식의 탭으로 구분된 데이터를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [TXT](../../groupdocs.viewer/filetype/txt) | 일반 텍스트 파일(.txt)은 일반 텍스트를 줄 형태로 포함하는 텍스트 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [TXZ](../../groupdocs.viewer/filetype/txz) | Consolidated Unix File Archive(.txz, .tar.xz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/txz) . |
| static readonly [Unknown](../../groupdocs.viewer/filetype/unknown) | 알 수 없는 파일 형식을 나타냅니다. |
| static readonly [VB](../../groupdocs.viewer/filetype/vb) | Visual Basic 프로젝트 항목 파일(.vb)은 Microsoft에서 .NET 응용 프로그램 개발을 위해 만든 Visual Basic 언어로 만든 소스 코드 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/programming/vb) . |
| static readonly [VCF](../../groupdocs.viewer/filetype/vcf) | vCard 파일(.vcf)은 연락처 정보를 저장하기 위한 디지털 파일 형식입니다. 이 형식은 널리 사용되는 정보 교환 응용 프로그램 간의 데이터 교환에 널리 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/email/vcf) . |
| static readonly [VDW](../../groupdocs.viewer/filetype/vdw) | Visio 웹 드로잉(.vdw)은 웹 드로잉을 렌더링하는 데 필요한 스트림과 저장소를 지정하는 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/web/vdw) . |
| static readonly [VDX](../../groupdocs.viewer/filetype/vdx) | Visio 드로잉 XML 파일(.vdx)은 Microsoft Visio에서 생성되었지만 확장자가 .VDX인 XML 형식으로 저장된 모든 드로잉 또는 차트를 나타냅니다. Visio 드로잉 XML 파일은 Microsoft에서 개발한 Visio 소프트웨어에서 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vdx) . |
| static readonly [VIM](../../groupdocs.viewer/filetype/vim) | Vim 설정 파일(.vim) |
| static readonly [VSD](../../groupdocs.viewer/filetype/vsd) | Visio 드로잉 파일(.vsd)은 Microsoft Visio 응용 프로그램으로 만든 드로잉으로 다양한 그래픽 개체와 이들 사이의 상호 연결을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vsd) . |
| static readonly [VSDM](../../groupdocs.viewer/filetype/vsdm) | Visio Macro-Enabled Drawing(.vsdm)은 매크로를 지원하는 Microsoft Visio 응용 프로그램으로 만든 드로잉 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 도면이지만 파일을 열 때 매크로를 실행할 수 있는 기능도 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [VSDX](../../groupdocs.viewer/filetype/vsdx) | Visio Drawing(.vsdx)은 Microsoft Office 2013부터 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이전 버전의 Microsoft Visio에서 지원하는 이진 파일 형식인 .VSD를 대체하기 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [VSS](../../groupdocs.viewer/filetype/vss) | Visio 스텐실 파일(.vss)은 Microsoft Visio 2007 및 이전 버전에서 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 드로잉에 포함될 수 있는 드로잉 개체를 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vss) . |
| static readonly [VSSM](../../groupdocs.viewer/filetype/vssm) | Visio 매크로 사용 스텐실 파일(.vssm)은 매크로 지원을 제공하는 Microsoft Visio 스텐실 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 모양의 원하는 서식 및 배치를 얻을 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vssm) . |
| static readonly [VSSX](../../groupdocs.viewer/filetype/vssx) | Visio 스텐실 파일(.vssx)은 Microsoft Visio 2013 이상에서 만든 드로잉 스텐실입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 셰이프 컬렉션, 커넥터, 순서도, 네트워크 레이아웃, UML 다이어그램, 와 같은 다양한 드로잉 요소를 표현하는 것으로 알려져 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vssx) . |
| static readonly [VST](../../groupdocs.viewer/filetype/vst) | Visio 드로잉 템플릿(.vst)은 Microsoft Visio로 만든 벡터 이미지 파일이며 추가 파일을 만들기 위한 템플릿 역할을 합니다. 이러한 템플릿 파일은 이진 파일 형식이며 새 Visio 드로잉 생성에 사용되는 기본 레이아웃 및 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vst) . |
| static readonly [VSTM](../../groupdocs.viewer/filetype/vstm) | Visio 매크로 사용 드로잉 템플릿(.vstm)은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSDX 파일과 달리 VSTM 템플릿에서 만든 파일은 VBA(Visual Basic for Applications) 코드로 개발된 매크로를 실행할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vstm) . |
| static readonly [VSTX](../../groupdocs.viewer/filetype/vstx) | Visio 드로잉 템플릿(.vstx)은 Microsoft Visio 2013 이상에서 만든 드로잉 템플릿 파일입니다. 이러한 VSTX 파일은 기본 레이아웃 및 설정과 함께 .VSDX 파일로 저장된 Visio 드로잉을 만들기 위한 시작점을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vstx) . |
| static readonly [VSX](../../groupdocs.viewer/filetype/vsx) | Visio 스텐실 XML 파일(.vsx)은 Microsoft Visio에서 다이어그램을 만드는 데 사용되는 드로잉 및 도형으로 구성된 스텐실을 나타냅니다. VSX 파일은 XML 파일 형식으로 저장되며 Visio 2013까지 지원되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vsx) . |
| static readonly [VTX](../../groupdocs.viewer/filetype/vtx) | Visio 템플릿 XML 파일(.vtx)은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 드로잉 템플릿입니다. 템플릿은 동일한 설정의 여러 Visio 파일을 만드는 데 사용할 수 있는 기본 설정이 있는 파일을 제공하는 것을 목표로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/vtx) . |
| static readonly [WEBP](../../groupdocs.viewer/filetype/webp) | WebP 이미지(.webp)는 무손실 및 손실 압축을 기반으로 하는 최신 래스터 웹 이미지 파일 형식입니다. 이미지 크기를 상당히 줄이면서 동일한 이미지 품질을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/webp) . |
| static readonly [WMF](../../groupdocs.viewer/filetype/wmf) | Windows 메타파일(.wmf)은 벡터 및 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows 메타파일(WMF)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/image/wmf) . |
| static readonly [WMZ](../../groupdocs.viewer/filetype/wmz) | 압축 Windows 메타파일(.wmz)은 벡터 및 비트맵 형식 이미지 데이터를 저장하기 위해 GZIP 아카이브로 압축된 Microsoft Windows 메타파일(WMF)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/wmz#compressed_windows_metafile) . |
| static readonly [XLAM](../../groupdocs.viewer/filetype/xlam) | Microsoft Excel 추가 기능(.xlam) |
| static readonly [XLS](../../groupdocs.viewer/filetype/xls) | Excel 스프레드시트(.xls)는 Excel 이진 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 기타 유사한 스프레드시트 프로그램으로 만들 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [XLSB](../../groupdocs.viewer/filetype/xlsb) | Excel 이진 스프레드시트(.xlsb)는 Excel 통합 문서 콘텐츠를 지정하는 레코드 및 구조의 모음인 Excel 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [XLSM](../../groupdocs.viewer/filetype/xlsm) | Excel Open XML 매크로 사용 스프레드시트(.xlsm)는 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [XLSX](../../groupdocs.viewer/filetype/xlsx) | Microsoft Excel Open XML 스프레드시트(.xlsx)는 Microsoft Office 2007 릴리스와 함께 Microsoft에서 도입한 잘 알려진 Microsoft Excel 문서 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [XLT](../../groupdocs.viewer/filetype/xlt) | Microsoft Excel 템플릿(.xlt)은 Microsoft Office 제품군의 일부로 제공되는 스프레드시트 응용 프로그램인 Microsoft Excel로 만든 템플릿 파일입니다. Microsoft Office 97-2003은 새 XLT 파일 생성 및 열기를 지원했습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [XLTM](../../groupdocs.viewer/filetype/xltm) | Microsoft Excel 매크로 사용 템플릿(.xltm)은 Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 나타냅니다. XLTM 파일은 XLTX가 매크로로 템플릿 파일 생성을 지원하지 않는다는 점을 제외하면 구조상 XLTX와 유사합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [XLTX](../../groupdocs.viewer/filetype/xltx) | Excel Open XML 스프레드시트 템플릿(.xltx)은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 나타냅니다. XLTX 파일에 지정된 것과 동일한 설정을 나타내는 XLSX 파일을 생성하는 데 활용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [XML](../../groupdocs.viewer/filetype/xml) | XML 파일(.xml) |
| static readonly [XPS](../../groupdocs.viewer/filetype/xps) | XML Paper 사양 파일(.xps)은 Microsoft에서 만든 XML Paper 사양을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다. 이 형식은 Microsoft에서 EMF 파일 형식을 대체하기 위해 개발했으며 PDF 파일 형식과 유사하지만 문서의 레이아웃, 모양 및 인쇄 정보에 XML을 사용합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/page-description-language/xps) . |
| static readonly [XZ](../../groupdocs.viewer/filetype/xz) | XZ 파일(.xz)은 LZMA 알고리즘 기반의 고비율 압축 알고리즘으로 압축된 아카이브입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/xz) . |
| static readonly [YAML](../../groupdocs.viewer/filetype/yaml) | YAML 문서(.yaml) |
| static readonly [ZIP](../../groupdocs.viewer/filetype/zip) | 압축 파일(.zip)은 하나 이상의 파일 또는 디렉토리를 보유할 수 있는 아카이브를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://wiki.fileformat.com/compression/zip) . |

### 또한보십시오

* 네임스페이스 [GroupDocs.Viewer](../../groupdocs.viewer)
* 집회 [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
