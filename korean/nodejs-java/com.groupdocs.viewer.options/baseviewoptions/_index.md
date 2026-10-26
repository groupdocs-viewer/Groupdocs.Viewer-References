---
title: "BaseViewOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "기본 렌더링 옵션을 포함합니다."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

기본 렌더링 옵션을 포함합니다.

BaseViewOptions 클래스는 GroupDocs.Viewer에서 렌더링 옵션의 기본 역할을 합니다. 특정 문서 형식을 렌더링할 때 출력 HTML, PDF, PNG 및 JPEG 파일의 렌더링 동작을 사용자 정의할 수 있습니다.

***Note:** For internal usage.*
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextOptions()](#getTextOptions--) | 텍스트 파일을 페이지로 분할하는 옵션을 가져옵니다. |
| [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | 텍스트 파일을 페이지로 분할하는 옵션을 설정합니다. |
| [isRenderComments()](#isRenderComments--) | 주석 렌더링을 활성화합니다. |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | 주석 렌더링을 활성화합니다. |
| [isRemoveComments()](#isRemoveComments--) | true 로 설정하면 주석 렌더링을 비활성화합니다. |
| [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | true 로 설정하면 주석 렌더링을 비활성화합니다. |
| [isRenderNotes()](#isRenderNotes--) | 노트 렌더링을 활성화합니다. |
| [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | 노트 렌더링을 활성화합니다. |
| [isRenderHiddenPages()](#isRenderHiddenPages--) | 숨겨진 페이지 렌더링을 활성화합니다. |
| [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | 숨겨진 페이지 렌더링을 활성화합니다. |
| [getDefaultFontName()](#getDefaultFontName--) | 문서에서 사용된 특정 폰트를 찾을 수 없을 때 사용할 기본 폰트입니다. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | 문서에서 사용된 특정 폰트를 찾을 수 없을 때 사용할 기본 폰트입니다. |
| [getArchiveOptions()](#getArchiveOptions--) | 아카이브 파일 보기 옵션을 가져옵니다. |
| [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | 아카이브 파일 보기 옵션을 설정합니다. |
| [getCadOptions()](#getCadOptions--) | CAD 도면 보기 옵션을 가져옵니다. |
| [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | CAD 도면 보기 옵션을 설정합니다. |
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
| [getEmailOptions()](#getEmailOptions--) | 이메일 메시지 보기 옵션을 가져옵니다. |
| [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | 이메일 메시지 보기 옵션을 설정합니다. |
| [getOutlookOptions()](#getOutlookOptions--) | MS Outlook 데이터 파일 보기 옵션을 가져옵니다. |
| [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | MS Outlook 데이터 파일 보기 옵션을 설정합니다. |
| [getPdfOptions()](#getPdfOptions--) | PDF 문서 보기 옵션을 검색합니다. |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | PDF 문서 보기 옵션을 검색합니다. |
| [getMailStorageOptions()](#getMailStorageOptions--) | Lotus Notes 저장 데이터 파일 보기 옵션을 검색합니다. |
| [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Lotus Notes 저장 데이터 파일 보기 옵션을 설정합니다. |
| [getProjectManagementOptions()](#getProjectManagementOptions--) | 프로젝트 관리 파일 보기 옵션을 검색합니다. |
| [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | 프로젝트 관리 파일 보기 옵션을 설정합니다. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | 스프레드시트 파일 보기 옵션을 검색합니다. |
| [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | 스프레드시트 파일 보기 옵션을 설정합니다. |
| [getWordProcessingOptions()](#getWordProcessingOptions--) | 워드 프로세싱 파일 보기 옵션. |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | 워드 프로세싱 파일 보기 옵션. |
| [getVisioRenderingOptions()](#getVisioRenderingOptions--) | 문서를 볼 때 Visio 파일을 처리하기 위한 렌더링 옵션을 검색합니다. |
| [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | 문서를 볼 때 Visio 파일을 처리하기 위한 렌더링 옵션을 설정합니다. |
| [getPresentationOptions()](#getPresentationOptions--) | 프레젠테이션 문서 처리를 위한 보기 옵션을 검색합니다. |
| [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | 프레젠테이션 문서 처리를 위한 보기 옵션을 설정합니다. |
| [getWebDocumentOptions()](#getWebDocumentOptions--) | Web 문서를 렌더링할 때 출력 HTML/PDF/PNG/JPEG의 모양을 사용자 정의할 수 있는 렌더링 옵션을 가져옵니다. |
| [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Web 문서를 렌더링할 때 출력 HTML/PDF/PNG/JPEG의 모양을 사용자 정의할 수 있는 렌더링 옵션을 설정합니다. |
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


텍스트 파일을 페이지로 분할하는 옵션을 가져옵니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


텍스트 파일을 페이지로 분할하는 옵션을 설정합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | 텍스트 파일 분할 옵션. |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


주석 렌더링을 활성화합니다.

기본적으로 GroupDocs.Viewer는 주석을 렌더링하지 않습니다. 이를 수행하려면 이 속성을 true로 설정하십시오. 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Returns:**
boolean -  true  주석을 렌더링해야 하면,  false  그렇지 않으면.
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


주석 렌더링을 활성화합니다.

기본적으로 GroupDocs.Viewer는 주석을 렌더링하지 않습니다. 이를 수행하려면 이 속성을 true로 설정하십시오. 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  주석을 렌더링해야 하면,  false  그렇지 않으면. |

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


true로 설정하면 주석 렌더링을 비활성화합니다. 기본값은 false — 모든 주석이 표시됩니다.

PDF 및 WordProcessing과 같은 일부 문서 형식에는 주석이 포함될 수 있습니다. 기본적으로 GroupDocs.Viewer는 이를 렌더링합니다. 이 옵션을 true로 설정하면 결과 문서에서 주석이 제외될 수 있습니다. 이 옵션은 오래된 'RenderComments' 속성을 대체합니다.

**Returns:**
boolean -  true  주석을 렌더링해야 하면,  false  그렇지 않으면.
### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


true로 설정하면 주석 렌더링을 비활성화합니다. 기본값은 false — 모든 주석이 표시됩니다.

PDF 및 WordProcessing과 같은 일부 문서 형식에는 주석이 포함될 수 있습니다. 기본적으로 GroupDocs.Viewer는 이를 렌더링합니다. 이 옵션을 true로 설정하면 결과 문서에서 주석이 제외될 수 있습니다. 이 옵션은 오래된 'RenderComments' 속성을 대체합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  주석을 렌더링해야 하면,  false  그렇지 않으면. |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


노트 렌더링을 활성화합니다.

프레젠테이션이나 Microsoft 프로젝트 파일과 같은 일부 파일에는 메모가 포함될 수 있습니다. 기본적으로 GroupDocs.Viewer는 메모를 렌더링하지 않습니다. 이를 수행하려면 이 속성을 true로 설정하십시오. 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes

**Returns:**
boolean -  true  메모를 렌더링해야 하면,  false  그렇지 않으면.
### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


노트 렌더링을 활성화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  메모를 렌더링해야 하면,  false  그렇지 않으면. |

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


숨겨진 페이지 렌더링을 활성화합니다.

프레젠테이션이나 스프레드시트와 같은 일부 파일에는 숨겨진 페이지가 포함될 수 있습니다. 기본적으로 GroupDocs.Viewer는 이러한 페이지를 렌더링하지 않습니다. 이를 수행하려면 이 속성을 true로 설정하십시오. 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Returns:**
boolean - 숨겨진 페이지를 렌더링해야 하면 true, 그렇지 않으면 false.
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


숨겨진 페이지 렌더링을 활성화합니다.

프레젠테이션이나 스프레드시트와 같은 일부 파일에는 숨겨진 페이지가 포함될 수 있습니다. 기본적으로 GroupDocs.Viewer는 이러한 페이지를 렌더링하지 않습니다. 이를 수행하려면 이 속성을 true로 설정하십시오. 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | 숨겨진 페이지를 렌더링해야 하면 true, 그렇지 않으면 false. |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


문서에서 사용된 특정 폰트를 찾을 수 없을 때 사용할 기본 폰트입니다.

이 속성을 사용하여 문서의 기본 글꼴을 설정합니다. GroupDocs.Viewer는 설치되지 않은 글꼴 대신 렌더링 중에 이 글꼴을 사용합니다. 코드 예제는 [문서][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Returns:**
java.lang.String - 기본 글꼴의 이름.
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


문서에서 사용된 특정 폰트를 찾을 수 없을 때 사용할 기본 폰트입니다.

이 속성을 사용하여 문서의 기본 글꼴을 설정합니다. GroupDocs.Viewer는 설치되지 않은 글꼴 대신 렌더링 중에 이 글꼴을 사용합니다. 코드 예제는 [문서][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 기본 글꼴의 이름. |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


아카이브 파일 보기 옵션을 가져옵니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


아카이브 파일 보기 옵션을 설정합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | 아카이브 파일 보기 옵션. |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


CAD 도면 보기 옵션을 가져옵니다.

자세한 정보와 코드 예제는 [HTML, PDF 및 이미지 파일로 CAD 도면 및 모델 렌더링][Render CAD drawings and models as HTML_ PDF_ and image files] 및 [CAD 파일에 대한 렌더링 옵션 지정][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


CAD 도면 보기 옵션을 설정합니다.

자세한 정보와 코드 예제는 [HTML, PDF 및 이미지 파일로 CAD 도면 및 모델 렌더링][Render CAD drawings and models as HTML_ PDF_ and image files] 및 [CAD 파일에 대한 렌더링 옵션 지정][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | CAD 도면 보기 옵션. |

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


이메일 메시지 보기 옵션을 가져옵니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


이메일 메시지 보기 옵션을 설정합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | 이메일 메시지 보기 옵션. |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


MS Outlook 데이터 파일 보기 옵션을 가져옵니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


MS Outlook 데이터 파일 보기 옵션을 설정합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | 설정할 MS Outlook 데이터 파일 보기 옵션. |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


PDF 문서 보기 옵션을 검색합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


PDF 문서 보기 옵션을 검색합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | PDF 문서 보기 옵션. |

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Lotus Notes 저장 데이터 파일 보기 옵션을 검색합니다.

**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.
### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Lotus Notes 저장 데이터 파일 보기 옵션을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Lotus Notes 저장 데이터 파일 보기 옵션. |

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


프로젝트 관리 파일 보기 옵션을 검색합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


프로젝트 관리 파일 보기 옵션을 설정합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | 설정할 프로젝트 관리 파일 보기 옵션. |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


스프레드시트 파일 보기 옵션을 검색합니다.

자세한 정보와 코드 예제는 [HTML, PDF 및 이미지 파일로 Excel 및 Apple Numbers 스프레드시트 렌더링][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [워크시트를 페이지로 분할][], 및 [스프레드시트 렌더링 옵션 지정][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


스프레드시트 파일 보기 옵션을 설정합니다.

자세한 정보와 코드 예제는 [HTML, PDF 및 이미지 파일로 Excel 및 Apple Numbers 스프레드시트 렌더링][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [워크시트를 페이지로 분할][], 및 [스프레드시트 렌더링 옵션 지정][].


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | 스프레드시트 파일 보기 옵션. |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


워드 프로세싱 파일 보기 옵션.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


워드 프로세싱 파일 보기 옵션.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Word 문서를 렌더링하기 위한 Word 처리 옵션. |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


문서를 볼 때 Visio 파일을 처리하기 위한 렌더링 옵션을 검색합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


문서를 볼 때 Visio 파일을 처리하기 위한 렌더링 옵션을 설정합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Visio 파일을 처리하기 위한 Visio 렌더링 옵션. |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


프레젠테이션 문서 처리를 위한 보기 옵션을 검색합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Returns:**
com.groupdocs.viewer.options.PresentationOptions - 프레젠테이션 문서를 처리하기 위한 프레젠테이션 보기 옵션.
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


프레젠테이션 문서 처리를 위한 보기 옵션을 설정합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions | 프레젠테이션 문서를 처리하기 위한 프레젠테이션 보기 옵션. |

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Web 문서를 렌더링할 때 출력 HTML/PDF/PNG/JPEG의 모양을 사용자 정의할 수 있는 렌더링 옵션을 가져옵니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - 렌더링 옵션을 사용자 정의하기 위한 WebDocumentOptions 객체.
### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Web 문서를 렌더링할 때 출력 HTML/PDF/PNG/JPEG의 모양을 사용자 정의할 수 있는 렌더링 옵션을 설정합니다.

자세한 정보와 코드 예제는 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | 렌더링 옵션을 사용자 정의하기 위한 WebDocumentOptions 객체. |

