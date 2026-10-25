---
title: "com.groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "이 패키지는 렌더링 과정에서 사용되는 글꼴을 관리하기 위한 클래스와 열거형을 제공합니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.viewer.fonts/
---

이 패키지는 렌더링 과정에서 사용되는 글꼴을 관리하기 위한 클래스와 열거형을 제공합니다.

이 패키지의 주요 클래스와 인터페이스는 다음과 같습니다:

* [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
* [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
* [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.


GroupDocs.Viewer에서 글꼴 작업에 대한 자세한 내용은 다음을 참조하십시오.
[GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## 클래스

| 클래스 | 설명 |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | TrueType 글꼴을 포함하는 폴더를 나타냅니다. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | UsedFontInfo 클래스에 존재할 수 있는 모든 글꼴 형식을 나타냅니다. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | TrueType 글꼴을 찾기 위한 소스 작업 메서드를 제공합니다. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | 문서에서 사용되는 글꼴의 4가지 가능한 스타일을 나타냅니다: Regular, Bold, Italic, 또는 Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Viewer 인스턴스로 로드된 PDF 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Viewer 인스턴스로 로드된 프레젠테이션 문서에서 사용되는 글꼴의 메타데이터와 바이너리 데이터를 캡슐화합니다. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Viewer 인스턴스로 로드된 스프레드시트 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Viewer 인스턴스로 로드된 워드 프로세싱 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | GroupDocs.Viewer를 통해 워드 프로세싱 문서에서 사용된 대체 글꼴 하나의 메타데이터와 바이너리 데이터를 캡슐화합니다. |

## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | 글꼴 소스를 위한 마커 인터페이스입니다. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | PDF, WordProcessing, Spreadsheet, Presentation 문서 형식에서 추출할 수 있는 모든 글꼴을 위한 공통 인터페이스입니다. |

## 열거형

| 열거형 | 설명 |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | 현재 폴더만 검색할지, 현재 폴더와 모든 하위 폴더를 검색할지 지정합니다. |
