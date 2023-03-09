---
title: HtmlViewOptions
second_title: .NET API 참조용 GroupDocs.Viewer
description: 문서를 HTML 형식으로 렌더링하기 위한 옵션을 제공합니다.
type: docs
weight: 330
url: /ko/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

문서를 HTML 형식으로 렌더링하기 위한 옵션을 제공합니다.

```csharp
public class HtmlViewOptions : ViewOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | 아카이브 파일 보기 옵션입니다. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 도면 보기 옵션입니다. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | 문서에 사용된 특정 글꼴을 찾을 수 없을 때 사용할 기본 글꼴입니다. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 이메일 메시지 보기 옵션입니다. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | 활성화되면 HTML 문서에 글꼴을 추가할 수 없습니다. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | HTML 문서에서 제외할 글꼴 이름 목록입니다. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | 인쇄를 위해 출력 HTML을 최적화할지 여부를 나타냅니다. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | 출력 이미지의 높이(픽셀)입니다. (단일 이미지를 HTML로만 변환하는 경우) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | 출력 이미지의 최대 높이(픽셀 단위). (단일 이미지를 HTML로만 변환하는 경우) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | 출력 이미지의 최대 너비(픽셀 단위). (단일 이미지를 HTML로만 변환하는 경우) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | 출력 이미지의 너비(픽셀)입니다. (단일 이미지를 HTML로만 변환하는 경우) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | 메일 저장소 데이터 파일 보기 옵션. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | HTML 콘텐츠 및 HTML 리소스 축소를 활성화합니다. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | MS Outlook 데이터 파일 보기 옵션입니다. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF 문서 보기 옵션입니다. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | 프레젠테이션 처리 문서 보기 옵션입니다. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | 프로젝트 관리 파일 보기 옵션입니다. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | 주석 렌더링을 활성화합니다. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 숨겨진 페이지의 렌더링을 활성화합니다. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 렌더링 노트를 활성화합니다. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | 반응형 렌더링을 활성화합니다. 반응형 웹 페이지는 화면 크기가 다른 장치에서 잘 렌더링됩니다. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | 전체 문서를 하나의 HTML 파일로 렌더링할 수 있습니다. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | 스프레드시트 파일 보기 옵션. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | 페이지 옵션으로 분할 텍스트 파일. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | 문서를 처리하는 Visio 파일 보기 옵션. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 각 페이지에 적용된 텍스트 워터마크입니다. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | 이 렌더링 옵션을 사용하면 웹 문서를 렌더링할 때 출력 HTML/PDF/PNG/JPEG의 모양을 사용자 정의할 수 있습니다. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | 이 렌더링 옵션을 사용하면 Word 문서를 렌더링할 때 출력 HTML/PDF/PNG/JPEG의 모양을 사용자 지정할 수 있습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 클래스. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 리소스가 포함된 HTML로 렌더링하기 위한 클래스입니다. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 리소스가 포함된 HTML로 렌더링하기 위한 클래스입니다. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 클래스. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 리소스가 포함된 HTML로 렌더링하기 위한 클래스입니다. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 클래스. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 클래스. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | 의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | 페이지에 시계 방향 회전을 적용합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | 페이지 회전입니다. |

### 또한보십시오

* class [ViewOptions](../viewoptions)
* 네임스페이스 [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* 집회 [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
