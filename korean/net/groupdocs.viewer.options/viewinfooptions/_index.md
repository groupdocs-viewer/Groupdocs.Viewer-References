---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for .NET API 참조"
description: "뷰에 대한 정보를 검색하기 위한 옵션을 포함합니다."
type: docs
weight: 580
url: /ko/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

뷰에 대한 정보를 검색하기 위한 옵션을 포함합니다.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | 아카이브 파일 보기 옵션입니다. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 도면 보기 옵션입니다. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | 문서의 기본 글꼴을 설정합니다. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 이메일 메시지 보기 옵션입니다. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | 이메일 메시지 필드를 나타냅니다(예: From, To, Subject 등). 자세한 내용은 문서 https//docs.groupdocs.com/viewer/net/renderemailmessages/renamefieldsinthemessageheader 를 참조하십시오. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | 출력 이미지의 높이(픽셀 단위, PNG/JPG 렌더링 전용)입니다. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | 메일 저장 데이터 파일 보기 옵션입니다. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | 출력 이미지의 최대 높이를 설정합니다(픽셀 단위, PNG/JPG 렌더링 전용). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | 출력 이미지의 최대 너비를 설정합니다(픽셀 단위, PNG/JPG 렌더링 전용). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook 데이터 파일 보기 옵션입니다. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF 문서 보기 옵션입니다. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | 프레젠테이션 파일 보기 옵션입니다. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | 프로젝트 관리 파일 보기 옵션입니다. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` 로 설정하면 주석 렌더링을 비활성화합니다. 기본값은 `false`이며, 모든 주석이 표시됩니다. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 숨겨진 페이지 렌더링을 활성화합니다. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 일부 형식에 대해 노트와 주석 렌더링을 활성화합니다. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | 스프레드시트 파일 보기 옵션입니다. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | 텍스트 파일 보기 옵션입니다. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio 파일 보기 옵션입니다. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | 웹 파일 보기 옵션입니다. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | 출력 이미지의 너비(픽셀 단위, PNG/JPG 렌더링 전용)입니다. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | 워드 프로세싱 파일 보기 옵션입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | HTML로 렌더링할 때 뷰 정보를 가져오기 위해 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | HTML로 렌더링할 때 뷰 정보를 가져오기 위해 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | JPG로 렌더링할 때 뷰 정보를 가져오기 위해 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | JPG로 렌더링할 때 뷰 정보를 가져오기 위해 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | PDF로 렌더링할 때 뷰 정보를 가져오기 위해 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | PNG로 렌더링할 때 뷰 정보를 가져오기 위해 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | PNG로 렌더링할 때 뷰 정보를 가져오기 위해 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | `[`HtmlViewOptions`](../htmlviewoptions)` 객체를 기반으로 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | `[`JpgViewOptions`](../jpgviewoptions)` 객체를 기반으로 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | `[`PdfViewOptions`](../pdfviewoptions)` 객체를 기반으로 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | `[`PngViewOptions`](../pngviewoptions)` 객체를 기반으로 [`ViewInfoOptions`](../viewinfooptions) 클래스의 인스턴스를 초기화합니다. |

### 또 보기

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
