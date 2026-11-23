---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for .NET API 참조"
description: "문서를 HTML 형식으로 렌더링하기 위한 옵션을 포함합니다. 자세한 내용은 topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ 및 그 하위 항목을 참조하십시오."
type: docs
weight: 320
url: /ko/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

문서를 HTML 형식으로 렌더링하기 위한 옵션을 포함합니다. 자세한 내용은 [주제](https://docs.groupdocs.com/viewer/net/rendering-to-html/)와 그 하위 항목을 참조하십시오.

```csharp
public class HtmlViewOptions : ViewOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | 아카이브 파일 보기 옵션입니다. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 도면 보기 옵션입니다. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | 문서의 기본 글꼴을 설정합니다. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 이메일 메시지 보기 옵션입니다. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | HTML 문서에 폰트를 추가하는 것을 비활성화합니다. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | HTML 문서에서 제외할 폰트 이름 목록입니다. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | 인쇄용 출력 HTML 최적화를 활성화합니다. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | 출력 이미지의 높이(픽셀 단위)입니다. 이 속성은 단일 이미지를 HTML로 변환할 때만 사용할 수 있습니다. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | 출력 이미지의 최대 높이(픽셀 단위)입니다. 이 속성은 단일 이미지를 HTML로 변환할 때만 사용할 수 있습니다. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | 출력 이미지의 최대 너비(픽셀 단위)입니다. 이 속성는 단일 이미지를 HTML로 변환할 때만 사용할 수 있습니다. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | 출력 이미지의 너비(픽셀 단위)입니다. 이 속성은 단일 이미지를 HTML로 변환할 때만 사용할 수 있습니다. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | 메일 저장 데이터 파일 보기 옵션입니다. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | HTML 콘텐츠 및 HTML 리소스 최소화를 활성화합니다. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook 데이터 파일 보기 옵션입니다. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF 문서 보기 옵션입니다. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | 프레젠테이션 파일 보기 옵션입니다. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | 프로젝트 관리 파일 보기 옵션입니다. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` 로 설정하면 주석 렌더링을 비활성화합니다. 기본값은 `false`이며, 모든 주석이 표시됩니다. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | 스크립트를 포함한 입력 문서를 렌더링할 때 결과 HTML 문서의 링크에서 JavaScript 소스 코드를 제거하도록 허용합니다. 기본값은 활성화(`true`)되어 있습니다. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 숨겨진 페이지 렌더링을 활성화합니다. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 일부 형식에 대해 노트와 주석 렌더링을 활성화합니다. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | 반응형 렌더링을 활성화합니다. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | 전체 문서를 하나의 HTML 파일로 렌더링하도록 활성화합니다. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | 스프레드시트 파일 보기 옵션입니다. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | 텍스트 파일 보기 옵션입니다. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio 파일 보기 옵션입니다. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 각 페이지에 적용될 텍스트 워터마크입니다. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | 웹 파일 보기 옵션입니다. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | 워드 프로세싱 파일 보기 옵션입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | `[`HtmlViewOptions`](../htmlviewoptions)` 클래스의 인스턴스를 초기화합니다. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | 로드된 WordProcessing 문서에 페이지 번호를 강제로 적용할지 여부와 적용한다면 페이지 번호를 배치할 위치를 제어합니다. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | 로드된 WordProcessing 문서에 페이지 번호를 강제로 적용할지 여부와 적용한다면 페이지 번호를 배치할 위치를 제어합니다. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | `[`HtmlViewOptions`](../htmlviewoptions)` 클래스의 인스턴스를 초기화합니다. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | 로드된 WordProcessing 문서에 페이지 번호를 강제로 적용할지 여부와 적용한다면 페이지 번호를 배치할 위치를 제어합니다. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | `[`HtmlViewOptions`](../htmlviewoptions)` 클래스의 인스턴스를 초기화합니다. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | 로드된 WordProcessing 문서를 그대로 유지합니다. 기본값. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | 로드된 WordProcessing 문서를 그대로 유지합니다. 기본값. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | `[`HtmlViewOptions`](../htmlviewoptions)` 클래스의 인스턴스를 초기화합니다. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | 로드된 WordProcessing 문서를 그대로 유지합니다. 기본값. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | 페이지에 시계 방향 회전을 적용합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | 페이지 회전입니다. |

### 또 보기

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
