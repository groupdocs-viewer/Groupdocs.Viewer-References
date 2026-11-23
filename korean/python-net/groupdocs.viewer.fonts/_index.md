---
title: "groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "글꼴 로드 및 대체 구성."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


글꼴 로드 및 대체 구성.

### 클래스
| 클래스 | 설명 |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | TrueType 글꼴을 포함하는 폴더를 나타냅니다. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | TrueType 글꼴을 찾기 위해 소스와 작업하는 메서드를 제공합니다. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | 문서에서 사용되는 글꼴의 4가지 가능한 스타일을 나타냅니다: Regular, Bold, Italic, 또는 Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | PDF, WordProcessing, Spreadsheet, Presentation 등 지원되는 모든 문서 형식군에서 추출할 수 있는 모든 글꼴에 대한 공통 인터페이스를 나타냅니다. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드된 PDF 글꼴의 메타데이터와 바이너리 데이터를 캡슐화합니다. 이 글꼴은 문서에 포함될 수 있거나 GroupDocs.Viewer가 실행되는 운영 체제에 설치될 수 있습니다. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드된 Presentation 문서의 글꼴에 대한 메타정보와 바이너리 데이터를 나타냅니다. 이 글꼴은 문서 내용에 사용되며 문서에 포함될 수 있거나 뷰어가 실행되는 운영 체제에 설치될 수 있습니다. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드된 스프레드시트 문서의 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다. 스프레드시트 문서는 글꼴을 포함할 수 없으므로, [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) 로 반환된 글꼴은 뷰어가 실행되는 운영 체제에 설치됩니다. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드된 WordProcessing 문서의 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다. |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | 로드된 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스 문서에서 원래 사용되지 않았지만 대상 머신에서 찾을 수 없는 경우 대체 글꼴로 사용되는 WordProcessing 문서의 한 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다. 대체 글꼴은 WordProcessing 형식군에만 존재합니다. |

### 열거형
| 열거형 | 설명 |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | 글꼴 소스를 위한 마커 인터페이스를 나타냅니다. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
