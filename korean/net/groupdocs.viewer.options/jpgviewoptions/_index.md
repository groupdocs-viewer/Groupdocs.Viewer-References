---
title: JpgViewOptions
second_title: .NET API 참조용 GroupDocs.Viewer
description: 문서를 JPG 형식으로 렌더링하는 옵션을 제공합니다.
type: docs
weight: 360
url: /ko/net/groupdocs.viewer.options/jpgviewoptions/
---
## JpgViewOptions class

문서를 JPG 형식으로 렌더링하는 옵션을 제공합니다.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | 의 새 인스턴스를 초기화합니다.[`JpgViewOptions`](../jpgviewoptions) 클래스. |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | 의 새 인스턴스를 초기화합니다.[`JpgViewOptions`](../jpgviewoptions) 클래스. |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | 의 새 인스턴스를 초기화합니다.[`JpgViewOptions`](../jpgviewoptions) 클래스. |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | 의 새 인스턴스를 초기화합니다.[`JpgViewOptions`](../jpgviewoptions) 클래스. |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | 의 새 인스턴스를 초기화합니다.[`JpgViewOptions`](../jpgviewoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | 아카이브 파일 보기 옵션입니다. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 도면 보기 옵션입니다. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | 문서에 사용된 특정 글꼴을 찾을 수 없을 때 사용할 기본 글꼴입니다. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 이메일 메시지 보기 옵션입니다. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | 텍스트 추출을 활성화합니다. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | 출력 이미지의 높이(픽셀 단위). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | 메일 저장소 데이터 파일 보기 옵션. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | 출력 이미지의 최대 높이(픽셀 단위). |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | 출력 이미지의 최대 너비(픽셀 단위). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | MS Outlook 데이터 파일 보기 옵션입니다. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF 문서 보기 옵션입니다. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | 프레젠테이션 처리 문서 보기 옵션입니다. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | 프로젝트 관리 파일 보기 옵션입니다. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | 출력 이미지의 품질; 유효한 값은 1에서 100 사이입니다. 기본값은 90입니다. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | 주석 렌더링을 활성화합니다. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 숨겨진 페이지의 렌더링을 활성화합니다. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 렌더링 노트를 활성화합니다. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | 스프레드시트 파일 보기 옵션. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | 페이지 옵션으로 분할 텍스트 파일. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | 문서를 처리하는 Visio 파일 보기 옵션. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 각 페이지에 적용된 텍스트 워터마크입니다. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | 이 렌더링 옵션을 사용하면 웹 문서를 렌더링할 때 출력 HTML/PDF/PNG/JPEG의 모양을 사용자 정의할 수 있습니다. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | 출력 이미지의 너비(픽셀 단위). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | 이 렌더링 옵션을 사용하면 Word 문서를 렌더링할 때 출력 HTML/PDF/PNG/JPEG의 모양을 사용자 지정할 수 있습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | 페이지에 시계 방향 회전을 적용합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | 페이지 회전입니다. |

### 또한보십시오

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* 네임스페이스 [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* 집회 [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
