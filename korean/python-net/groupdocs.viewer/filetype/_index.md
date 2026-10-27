---
title: "FileType 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일 유형을 나타내며 GroupDocs.Viewer에서 지원하는 모든 파일 유형 목록을 가져오는 메서드를 제공합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

파일 유형을 나타내며 GroupDocs.Viewer에서 지원하는 모든 파일 유형 목록을 가져오는 메서드를 제공합니다.

FileType 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | 새 인스턴스를 초기화합니다 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | 새 FileType 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | 경로를 통해 텍스트 TXT, TSV 및 CSV 파일의 인코딩을 감지합니다. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | 스트림에서 텍스트 파일(TXT, TSV, CSV)의 인코딩을 감지하려 시도합니다. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | 현재 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)가 지정된 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)와 동일한지 확인합니다. |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | 현재 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)가 지정된 객체와 동일한지 확인합니다. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | 파일 확장자를 파일 유형에 매핑합니다. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | 파일 확장자를 추출하고 파일 유형에 매핑합니다. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | 파일 미디어 유형을 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)에 매핑합니다(예: 'application/pdf'는 [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)에 매핑됩니다). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | 파일 서명을 읽어 파일 유형을 감지합니다. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | 파일 서명을 읽어 파일 유형을 감지합니다. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | 파일 서명을 읽어 파일 유형을 감지합니다. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | 파일 서명을 읽어 파일 유형을 감지합니다. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | 현재 [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) 객체의 해시 코드를 반환합니다. |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | 지원되는 파일 유형을 검색합니다. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | 파일 이름 접미사(마침표 \".\" 포함) 예: \".doc\". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | 파일 유형 이름 예: \"Microsoft Word Document\". |

### 필드
| 필드 | 설명 |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | 알 수 없는 파일 유형을 나타냅니다. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | 압축 파일(.zip)은 하나 이상의 파일 또는 디렉터리를 포함할 수 있는 아카이브를 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | 통합 유닉스 파일 아카이브(.tar)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | XZ 파일(.xz)은 LZMA 알고리즘을 기반으로 한 고비율 압축 알고리즘으로 압축된 아카이브입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | 통합 유닉스 파일 아카이브(.txz, .tar.xz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | 통합 유닉스 파일 아카이브(.txz, .tar.xz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | 통합 유닉스 파일 아카이브(.tgz, .tar.gz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | 통합 유닉스 파일 아카이브(.tgz, .tar.gz)는 하나 이상의 파일을 수집하기 위해 Unix 기반 유틸리티로 생성된 아카이브입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Bzip2 압축 파일(.bz2)은 주로 UNIX 또는 Linux 시스템에서 BZIP2 오픈 소스 압축 방식을 사용하여 생성된 압축 파일입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Roshal ARchive (.rar)는 RAR (WINRAR) 압축 방식을 사용하여 생성된 압축 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Gnu Zipped File (.gz)는 gzip 압축 응용 프로그램으로 만든 압축 파일입니다. 여러 압축 파일을 포함할 수 있으며 UNIX 및 Linux 시스템에서 일반적으로 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Gnu Zipped File (.gzip)는 Unix 시스템에서 사용되던 Compress 프로그램을 대체하기 위해 도입된 무료 유틸리티입니다. 이러한 파일은 Windows와 MacOS 모두에서 사용할 수 있는 WinZip과 같은 여러 응용 프로그램으로 열고 추출할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | 7Zip (.7z, .7zip)는 LZMA 및 LZMA2 압축을 지원하는 무료 오픈 소스 압축 프로그램입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Cpio는 일반 파일 압축 유틸리티 및 관련 파일 형식이며, 주로 Unix와 유사한 운영 체제에 설치됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | ZST 파일은 Zstandard (zstd) 압축 알고리즘으로 생성된 압축 파일입니다. 이 알고리즘은 무손실 압축을 사용하여 데이터베이스, 파일 시스템, 네트워크, 게임 등 다양한 유형의 파일을 압축하는 데 사용할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | TZST 파일(.tar.zst, .tzst)은 Zstandard 아카이브(ZST)이며, 내부에 Consolidated Unix File Archive (Tar)를 포함하고 Unix 기반 유틸리티로 하나 이상의 파일을 수집하여 생성됩니다. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | TZST 파일(.tar.zst, .tzst)은 Zstandard 아카이브(ZST)이며, 내부에 Consolidated Unix File Archive (Tar)를 포함하고 Unix 기반 유틸리티로 하나 이상의 파일을 수집하여 생성됩니다. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | ISO 광디스크 이미지 파일은 CD 또는 DVD와 같은 광디스크 전체 데이터를 나타내는 비압축 아카이브 디스크 이미지 파일이며, ISO-9660 표준을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | LHA 또는 LZH는 무료 압축 유틸리티 및 관련 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Cabinet(또는 CAB)은 Microsoft Windows용 아카이브 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Drawing Exchange Format File (.dxf)는 AutoCAD 도면 파일의 태그된 데이터 표현입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | AutoCAD Drawing Database File (.dwg)는 2D 및 3D 설계 데이터를 포함하는 독점 바이너리 파일을 나타냅니다. ASCII 파일인 DXF와 달리, DWG는 CAD(Computer Aided Design) 도면을 위한 바이너리 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | AutoCAD Drawing Template (.dwt)는 DWG 파일로 저장할 수 있는 도면을 만들기 위한 시작 템플릿인 AutoCAD 도면 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Stereolithography File (.stl)는 3차원 표면 기하학을 나타내는 교환 가능한 파일 형식입니다. 이 파일 형식은 빠른 프로토타이핑, 3D 프린팅 및 컴퓨터 지원 제조와 같은 여러 분야에서 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Industry Foundation Classes File (.ifc)는 건물 객체와 그 속성을 가져오고 내보내기 위한 국제 표준을 설정하는 파일 형식이며, 다양한 소프트웨어 애플리케이션 간 상호 운용성을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Design Web Format File (.dwf)는 2D/3D 도면을 압축 형식으로 제공하여 디자인 파일을 보기, 검토 또는 인쇄할 수 있게 합니다. 이 파일은 그래픽과 텍스트를 디자인 데이터의 일부로 포함하며, 압축 형식 덕분에 파일 크기가 감소합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Autodesk FBX Interchange File (FilmBoX) (.fbx)는 3D 모델 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Design Web Format File XPS (.dwfx)는 XPS 문서 형식으로 압축된 2D/3D 도면을 제공하여 디자인 파일을 보기, 검토 또는 인쇄할 수 있게 합니다. 이 파일은 그래픽과 텍스트를 디자인 데이터의 일부로 포함하며, 압축 형식 덕분에 파일 크기가 감소합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | MicroStation Design File (.dgn)은 MicroStation 및 Intergraph Interactive Graphics Design System과 같은 CAD 애플리케이션에서 생성 및 지원되는 도면 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | PLT (HPGL) (.plt)는 Autodesk, Inc.에서 도입한 벡터 기반 플로터 파일이며 특정 CAD 파일에 대한 정보를 포함합니다. 플로팅 세부 사항은 생산에서 정확성과 정밀성을 요구하며, PLT 파일은 모든 이미지를 점이 아닌 선으로 인쇄하기 때문에 이를 보장합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Common File Format File 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Wavefront 3D Object File (.obj)는 Wavefront Technologies에서 도입한 3D 이미지 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Visio Drawing File (.vsd)는 Microsoft Visio 애플리케이션으로 만든 도면으로, 다양한 그래픽 객체와 이들 간의 연결을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Visio Drawing (.vsdx)은 Microsoft Office 2013부터 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이는 이전 버전의 Microsoft Visio에서 지원되는 이진 파일 형식인 .VSD를 대체하기 위해 개발되었습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Visio Stencil File(.vss)은 Microsoft Visio 2007 및 이전 버전으로 만든 스텐실 파일입니다. 스텐실 파일은 .VSD Visio 도면에 포함될 수 있는 그리기 객체를 제공합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Visio Stencil File (.vssx)은 Microsoft Visio 2013 이상에서 만든 드로잉 스텐실 파일입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 도형 컬렉션, 연결선, 흐름도, 네트워크 레이아웃, UML 다이어그램 등 다양한 그리기 요소를 표현하는 것으로 알려져 있습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Visio Macro-Enabled Drawing (.vsdm)은 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 드로잉 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 드로잉이지만, 파일이 열릴 때 매크로를 실행할 수 있는 기능도 제공합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Visio Drawing Template (.vst)은 Microsoft Visio로 만든 벡터 이미지 파일이며, 이후 파일을 만들기 위한 템플릿 역할을 합니다. 이러한 템플릿 파일은 이진 파일 형식이며, 새로운 Visio 도면을 만들 때 사용되는 기본 레이아웃과 설정을 포함합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Visio Drawing Template (.vstx)은 Microsoft Visio 2013 이상에서 만든 드로잉 템플릿 파일입니다. 이러한 VSTX 파일은 기본 레이아웃과 설정을 갖춘 .VSDX 파일로 저장되는 Visio 도면을 만들기 위한 시작점을 제공합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Visio Macro-Enabled Drawing Template (.vstm)은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSDX 파일과 달리 VSTM 템플릿에서 만든 파일은 Visual Basic for Applications (VBA) 코드로 개발된 매크로를 실행할 수 있습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Visio Macro-Enabled Stencil File (.vssm)은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 원하는 형식 지정 및 도형 배치를 할 수 있습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Visio Stencil XML File (.vsx)은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 드로잉 및 도형으로 구성된 스텐실을 의미합니다. VSX 파일은 XML 파일 형식으로 저장되며 Visio 2013까지 지원되었습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Visio Template XML File (.vtx)은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 드로잉 템플릿입니다. 이 템플릿은 동일한 설정을 가진 여러 Visio 파일을 만들 때 사용할 수 있는 기본 설정이 포함된 파일을 제공하도록 설계되었습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Visio Web Drawing (.vdw)은 웹 드로잉을 렌더링하는 데 필요한 스트림 및 저장소를 지정하는 파일 형식을 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Visio Drawing XML File (.vdx)은 Microsoft Visio에서 만든 모든 드로잉이나 차트를 나타내며, XML 형식으로 저장되어 .VDX 확장자를 가집니다. Visio 드로잉 XML 파일은 Microsoft에서 개발한 Visio 소프트웨어에서 생성됩니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Open eBook File (.epub)은 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 현재 매우 일반화되어 많은 전자책 리더와 소프트웨어 애플리케이션에서 지원됩니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Mobipocket eBook (.mobi)은 가장 널리 사용되는 전자책 파일 형식 중 하나입니다. 이 형식은 기존 OEB(Open Ebook Format) 형식을 개선한 것이며, Mobipocket Reader의 독점 형식으로 사용되었습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Amazon Kindle Format 8 (KF8) 전자책은 Amazon Kindle 기기를 위해 개발된 디지털 파일 형식입니다. 이 형식은 이전 AZW 파일을 개선한 것이며, Kindle Fire 기기에서만 사용되며 이전 파일 형식인 MOBI와 AZW와의 하위 호환성을 제공합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Outlook Mail Message (.msg)는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용하는 파일 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | E-Mail Message (.eml)은 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 나타냅니다. 거의 모든 이메일 클라이언트가 RFC-822 인터넷 메시지 형식 표준을 준수하기 때문에 이 파일 형식을 지원합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Apple Mail Message (.emlx)는 Apple에서 구현 및 개발한 것입니다. Apple Mail 애플리케이션은 이메일을 내보낼 때 EMLX 파일 형식을 사용합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Outlook Personal Information Store File (.pst)는 다양한 사용자 정보를 저장하는 Outlook 개인 저장 파일(또는 Personal Storage Table)입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Outlook Offline Data File (.ost)는 Microsoft Outlook을 사용하여 Exchange Server에 등록할 때 로컬 컴퓨터에서 오프라인 모드로 사용자 메일함 데이터를 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Tagged Image File (.tif)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하도록 설계된 래스터 이미지 파일을 나타냅니다. 이 형식은 이진, 그레이스케일, 팔레트 색상 및 전체 색상 이미지 데이터를 여러 색 공간에서 표현할 수 있습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Tagged Image File Format (.tiff)은 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하도록 설계된 래스터 이미지 파일을 나타냅니다. 이 형식은 이진, 그레이스케일, 팔레트 색상 및 전체 색상 이미지 데이터를 여러 색 공간에서 표현할 수 있습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | JPEG 이미지 (.jpg)는 손실 압축 방식을 사용하여 저장되는 이미지 형식의 한 종류입니다. 압축 결과로 생성되는 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | JPEG 이미지 (.jpeg)는 손실 압축 방식을 사용하여 저장되는 이미지 형식의 한 종류입니다. 압축 결과로 생성되는 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | JPEG 파일 교환 형식 (.jfif)은 플랫폼 간 빠른 교환을 위해 개발된 이미지입니다. 이 형식은 JPEG 압축을 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Portable Network Graphic (.png)는 무손실 압축을 사용하는 래스터 이미지 파일 형식의 한 종류입니다. 이 파일 형식은 Graphics Interchange Format (GIF)을 대체하기 위해 만들어졌으며 저작권 제한이 없습니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Graphical Interchange Format 파일 (.gif)은 고도로 압축된 이미지 형식입니다. GIF는 일반적으로 픽셀당 최대 8비트, 전체 이미지에 최대 256색을 허용합니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Animated Portable Network Graphic (.apng)는 애니메이션을 지원하는 PNG 형식의 확장입니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Bitmap 이미지 파일 (.bmp)은 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이러한 이미지는 그래픽 어댑터와 무관하며 디바이스 독립 비트맵 (Device Independent Bitmap, DIB) 파일 형식이라고도 합니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Truevision TGA (Truevision Advanced Raster Adapter - TARGA)는 TRUEVISION에서 개발한 비트맵 디지털 이미지를 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Icon 파일 (.ico)은 Microsoft Windows에서 애플리케이션을 나타내는 아이콘으로 사용되는 이미지 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | JPEG 2000 Core Image 파일 (.jp2)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | JPEG 2000 이미지 파일 (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | JPEG 2000 이미지 파일 (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | JPEG 2000 이미지 파일 (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | JPEG 2000 코드 스트림 (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | JPEG 2000 코드 스트림 (.j2k)은 DCT 압축 대신 웨이브렛 압축을 사용하여 압축된 이미지입니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | JPEG 2000 코드 스트림 (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Device Independent Bitmap 파일 (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Windows Metafile (.wmf)은 벡터와 비트맵 형식 이미지 데이터를 저장하기 위한 Microsoft Windows Metafile (WMF)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Compressed Windows Metafile (.wmz)은 벡터와 비트맵 형식 이미지 데이터를 저장하기 위해 GZIP 압축된 Microsoft Windows Metafile (WMF)을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Enhanced Windows Metafile (.emf)은 디바이스 독립적으로 그래픽 이미지를 나타냅니다. EMF 메타파일은 순차적인 가변 길이 레코드로 구성되어 있어, 어떤 출력 장치에서도 파싱 후 저장된 이미지를 렌더링할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Enhanced Windows Metafile compressed (.emz)은 GZIP으로 압축된 디바이스 독립 그래픽 이미지를 나타냅니다. EMF 메타파일은 순차적인 가변 길이 레코드로 구성되어 있어, 어떤 출력 장치에서도 파싱 후 저장된 이미지를 렌더링할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | WebP 이미지 (.webp)는 무손실 및 손실 압축을 기반으로 하는 최신 래스터 웹 이미지 파일 형식입니다. 이미지 품질을 유지하면서 이미지 크기를 크게 줄여줍니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Digital Negative Specification (.dng)은 RAW 파일 저장에 사용되는 디지털 카메라 이미지 형식입니다. 2004년 9월 Adobe에서 개발되었습니다. 기본적으로 디지털 사진 촬영을 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | CorelDraw Vector Graphic Drawing (.cdr)은 CorelDRAW에서 기본적으로 생성되어 디지털 이미지를 인코딩 및 압축하여 저장하는 벡터 드로잉 이미지 파일입니다. 이러한 드로잉 파일은 텍스트, 선, 도형, 이미지, 색상 및 효과를 포함하여 이미지 내용을 벡터 형태로 표현합니다. 이 파일 형식에 대해 자세히 알아보려면 여기. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Corel Exchange (.cmx)는 벡터 그래픽과 비트맵 그래픽을 모두 포함할 수 있는 그림 이미지 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | DjVu Image (.djvu)는 텍스트, 도면, 이미지 및 사진이 결합된 스캔 문서와 책을 위해 설계된 그래픽 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Computer Graphics Metafile (.cgm)는 벡터 그래픽(2D), 래스터 그래픽 및 텍스트를 저장하고 교환하기 위한 무료이며 플랫폼에 독립적인 국제 표준 메타파일 형식입니다. CGM은 객체 지향 접근 방식과 이미지 제작을 위한 다양한 기능을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Printer Command Language 문서 (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Adobe Photoshop Document (.psd)는 그래픽 디자인 및 개발에 사용되는 Adobe Photoshop 고유의 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Photoshop Large Document Format (.psb)는 그래픽 디자인 및 개발에 사용되는 Photoshop Large Document Format을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | DICOM Image (.dcm)는 MRI, CT 스캔 및 초음파 이미지와 같은 환자의 의료 정보를 저장하는 디지털 이미지를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | PostScript 파일 (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Encapsulated PostScript File (.eps)는 단일 페이지의 모양을 설명하는 Encapsulated PostScript 언어 프로그램을 설명합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | OpenDocument Graphic File (.odg)는 Apache OpenOffice의 Draw 애플리케이션에서 그림 요소를 벡터 이미지로 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Flat XML ODF Template (.fodg)는 Apache OpenOffice의 Draw 애플리케이션에서 그림 요소를 벡터 이미지로 저장하는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Scalable Vector Graphics File (.svg)는 이미지의 모양을 설명하기 위해 XML 기반 텍스트 형식을 사용하는 Scalable Vector Graphics 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Scalable Vector Graphics File (.svgz)는 이미지의 모양을 설명하기 위해 XML 기반 텍스트 형식을 사용하고 GZIP으로 압축된 Scalable Vector Graphics 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | OpenDocument Graphic 템플릿 (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Hypertext Markup Language File (.htm)는 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Hypertext Markup Language File (.html)는 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | MHTML 웹 아카이브 (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | MIME HTML 파일 (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | XML 파일 (.xml). GroupDocs.Viewer는 XML 파일을 처리하기 위한 특수 프로세서를 제공하며, 문서를 참조하십시오. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | OneNote Document (.one)는 Microsoft OneNote 애플리케이션에 의해 생성됩니다. OneNote를 사용하면 초안 패드로 메모를 하는 것처럼 애플리케이션을 이용해 정보를 수집할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Portable Document Format File (.pdf)는 1990년대 Adobe에서 만든 문서 유형입니다. 이 파일 형식의 목적은 애플리케이션 소프트웨어, 하드웨어 및 운영 체제와 무관하게 문서와 기타 참고 자료를 표현하기 위한 표준을 도입하는 것이었습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | XML Paper Specification File (.xps)는 Microsoft에서 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다. 이 형식은 EMF 파일 형식을 대체하기 위해 Microsoft에서 개발되었으며 PDF 파일 형식과 유사하지만 문서의 레이아웃, 외관 및 인쇄 정보를 XML로 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | OpenXPS 파일 (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | LaTeX Source Document (.tex)는 프로그래밍 및 마크업 기능을 포함하는 언어로, 문서 조판에 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | GB/T 33190-2016에 정의된 Open Fixed-layout Document (OFD) 형식은 중국 공공 기관에서 PDF를 대체하는 것을 목표로 합니다. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | PowerPoint Presentation (.ppt)는 슬라이드 쇼로 표시하기 위해 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 바이너리 파일 형식을 지정합니다. 자세한 내용은 여기에서 확인하세요. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | PowerPoint Open XML Presentation (.pptx)는 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전의 바이너리 PPT 프레젠테이션 파일 형식과 달리, PPTX 형식은 Microsoft PowerPoint 오픈 XML 프레젠테이션 파일 형식을 기반으로 합니다. 자세한 내용은 여기에서 확인하세요. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | PowerPoint Slide Show (.pps)는 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용하여 생성됩니다. PPS 파일의 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 자세한 내용은 여기에서 확인하세요. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | PowerPoint Open XML Slide Show (.ppsx) 파일은 슬라이드 쇼 용도로 Microsoft PowerPoint 2007 이상을 사용하여 생성됩니다. 자세한 내용는 여기에서 확인하세요. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | OpenDocument Presentation (.odp)는 OASIS Open 표준에서 OpenOffice.org가 사용하는 프레젠테이션 파일 형식을 나타냅니다. 자세한 내용은 여기에서 확인하세요. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | OpenDocument Presentation (.fodp)는 OpenDocument Flat XML 프레젠테이션을 나타냅니다. 자세한 내용은 여기에서 확인하세요. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | PowerPoint Template (.pot)는 PowerPoint 97-2003 버전으로 만든 Microsoft PowerPoint 템플릿 파일을 나타냅니다. 자세한 내용은 여기에서 확인하세요. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | PowerPoint Open XML Macro-Enabled Presentation은 Microsoft PowerPoint 2007 이상 버전으로 만든 매크로 사용 가능 프레젠테이션 파일입니다. 자세한 내용은 여기에서 확인하세요. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | PowerPoint Open XML Presentation Template (.potx)는 Microsoft PowerPoint 2007 이상으로 만든 Microsoft PowerPoint 템플릿 프레젠테이션을 나타냅니다. 자세한 내용은 여기에서 확인하세요. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm)는 매크로를 지원하는 Microsoft PowerPoint 템플릿 파일입니다. POTM 파일은 PowerPoint 2007 이상으로 생성되며 추가 프레젠테이션 파일을 만들 때 사용할 수 있는 기본 설정을 포함합니다. 자세한 내용은 여기에서 확인하세요. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | PowerPoint Open XML Macro-Enabled Slide (.ppsm)는 Microsoft PowerPoint 2007 이상으로 만든 매크로 사용 가능 슬라이드 쇼 파일 형식을 나타냅니다. 자세한 내용은 여기에서 확인하세요. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | OpenDocument Presentation Template (.otp)는 OASIS OpenDocument 표준 형식으로 애플리케이션에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. 자세한 내용은 여기에서 확인하세요. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Excel Spreadsheet (.xls)는 Excel 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성될 수 있습니다. 자세한 내용은 여기에서 확인하세요. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Excel 2003 XML (SpreadsheetML)은 Excel 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성될 수 있습니다. 자세한 내용은 여기에서 확인하세요. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Apple numbers는 Excel과 유사한 바이너리 파일 형식을 나타냅니다. 이러한 파일은 Apple numbers 애플리케이션으로 생성될 수 있습니다. 자세한 내용은 여기에서 확인하세요. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Microsoft Excel Open XML Spreadsheet (.xlsx)는 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 Microsoft Excel 문서의 잘 알려진 형식입니다. 자세한 내용은 여기에서 확인하세요. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm)는 매크로를 지원하는 스프레드시트 파일 유형입니다. 자세한 내용은 여기에서 확인하세요. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Excel Binary Spreadsheet (.xlsb)는 Excel 바이너리 파일 형식을 지정하며, 이는 Excel 워크북 내용을 정의하는 레코드와 구조의 집합입니다. 자세한 내용은 여기에서 확인하세요. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Comma Separated Values File (.csv)는 쉼표로 구분된 값으로 데이터 레코드를 포함하는 일반 텍스트 파일을 나타냅니다. 자세한 내용은 여기에서 확인하세요. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Tab Separated Values File (.tsv)는 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. 자세한 내용은 여기에서 확인하세요. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | OpenDocument Spreadsheet (.ods)는 사용자가 편집할 수 있는 OpenDocument 스프레드시트 문서 형식을 의미합니다. 데이터는 ODF 파일 내부에 행과 열로 저장됩니다. 자세한 내용은 여기에서 확인하세요. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Microsoft Excel Macro-Enabled Template (.xltm)는 Microsoft Excel에서 매크로 사용 가능 템플릿 파일로 생성되는 파일을 나타냅니다. XLTM 파일은 구조적으로 XLTX와 유사하지만, 후자는 매크로가 포함된 템플릿 파일 생성을 지원하지 않습니다. 자세한 내용은 여기에서 확인하세요. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Microsoft Excel 템플릿(.xlt)은 Microsoft Excel로 만든 템플릿 파일이며, Microsoft Excel은 Microsoft Office 제품군의 일부인 스프레드시트 응용 프로그램입니다. Microsoft Office 97-2003은 새로운 XLT 파일을 만들고 열 수 있었습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Excel Open XML 스프레드시트 템플릿(.xltx)은 Office OpenXML 파일 형식 사양을 기반으로 하는 Microsoft Excel 템플릿을 나타냅니다. 이는 XLTX 파일에 지정된 동일한 설정을 가진 XLSX 파일을 생성하는 데 사용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc 스프레드시트(.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Microsoft Project 파일(.mpp)은 프로젝트 관리와 관련된 정보를 통합된 방식으로 저장하는 Microsoft Project 데이터 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Microsoft Project 템플릿(.mpt)에는 .MPP 파일을 만들기 위한 기본 정보와 구조, 문서 설정이 포함되어 있습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Microsoft Project Exchange 파일(.mpx)은 Microsoft Project(MSP)와 Primavera Project Planner, Sciforma, Timerline Precision Estimating 등 MPX 파일 형식을 지원하는 다른 애플리케이션 간에 프로젝트 정보를 전송하기 위한 ASCII 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | ActionScript 파일(.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | ActionScript 파일(.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | 어셈블리 언어 소스 코드 파일(.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | DOS 배치 파일(.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | C/C++ 소스 코드 파일(.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | C++ 소스 코드 파일(.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | CMake 파일(.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | C++ 소스 코드 파일(.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | C# 소스 코드 파일(.cs)은 C# 프로그래밍 언어용 소스 코드 파일입니다. Microsoft가 .NET Framework와 함께 사용하도록 도입했습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Visual Basic 프로젝트 항목 파일(.vb)은 Microsoft가 .NET 애플리케이션 개발을 위해 만든 Visual Basic 언어로 작성된 소스 코드 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하십시오. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | 계단식 스타일 시트(.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | C++ 소스 코드 파일(.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | 패치 파일(.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Ruby ERB 스크립트(.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Groovy 소스 코드 파일(.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | C/C++/Objective-C 헤더 파일(.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Haml 소스 코드 파일(.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | C++ 헤더 파일(.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Java 소스 코드 파일(.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | JavaScript 파일(.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | JavaScript 객체 표기법 파일 (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | LESS 스타일 시트 (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | 로그 파일 (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Objective-C 구현 파일 (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Xcode 메이크파일 스크립트 (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Markdown 문서 파일 (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | ML 소스 코드 파일 (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Objective-C++ 소스 파일 (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | PHP 소스 코드 파일 (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Perl 스크립트 (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Java 속성 파일 (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Python 스크립트 (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Ruby 소스 코드 (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | reStructuredText 파일 (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Syntactically Awesome StyleSheets 파일 (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Scala 소스 코드 파일 (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Scheme 소스 코드 파일 (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | 일반 스크립트 파일 (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Bash 셸 스크립트 (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Standard ML 소스 코드 파일 (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | 구조적 질의 언어 데이터 파일 (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Vim 설정 파일 (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | YAML 문서 (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word 문서 (.doc)는 Microsoft Word 또는 기타 워드 프로세서에서 생성된 문서를 바이너리 파일 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML 문서 (.docx)는 Microsoft Word 문서에 널리 알려진 형식입니다. 2007년 Microsoft Office 2007이 출시되면서 도입된 이 새로운 문서 형식은 기존의 순수 바이너리 방식에서 XML과 바이너리 파일의 조합으로 구조가 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help File (.chm)은 일부 애플리케이션에 대한 문서(HELP) 문서에 널리 알려진 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML Macro-Enabled Document (.docm)은 매크로 실행 기능이 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word Document Template (.dot)은 추가 DOC 또는 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Word Open XML Document Template (.dotx)은 추가 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Word Open XML Macro-Enabled Document Template (.dotm)은 Microsoft Word 2007 이상으로 만든 템플릿 파일을 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Rich Text Format File (.rtf)은 애플리케이션 내에서 사용하기 위한 서식 있는 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Plain Text File (.txt)은 줄 형태의 순수 텍스트를 포함하는 텍스트 문서를 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | OpenDocument Text Document (.odt)은 OpenDocument Text File 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | OpenDocument Document Template (.ott)은 OASIS의 OpenDocument 표준 형식을 준수하는 애플리케이션에서 생성한 템플릿 문서를 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | vCard File (.vcf)은 연락처 정보를 저장하기 위한 디지털 파일 형식입니다. 이 형식은 인기 있는 정보 교환 애플리케이션 간 데이터 교환에 널리 사용됩니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Adobe Illustrator (.ai)는 Adobe Illustrator 그림을 위한 파일 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | PowerShell script module (.psm1)은 PowerShell 모듈 스크립트를 위한 파일 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | PowerShell script file (.ps1)은 Windows PowerShell Cmdlet 파일을 위한 파일 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | PowerShell script module manifest (.psd1)은 PowerShell 모듈 매니페스트 스크립트를 위한 파일 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |

### 예시

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# 문서를 로드할 때 파일 유형(예: Markdown)을 지정하십시오.
load_options = LoadOptions(FileType.MD)

# 문서를 PDF로 렌더링합니다.
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### 참고
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
