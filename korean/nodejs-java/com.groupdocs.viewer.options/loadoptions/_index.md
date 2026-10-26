---
title: "LoadOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "파일을 열 때 사용되는 옵션을 제공합니다."
type: docs
weight: 18
url: /ko/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

파일을 열 때 사용되는 옵션을 제공합니다.

LoadOptions 클래스는 파일을 GroupDocs.Viewer 구성 요소에서 어떻게 열고 로드할지 지정하는 데 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다. 자세한 내용은 이 [page][] 및 하위 항목을 참조하십시오.

예시 사용법:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/loading/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | 활성화하면 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도합니다. |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | 활성화하면 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도합니다. |
| [getFileType()](#getFileType--) | 열 파일의 유형을 가져옵니다. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | 열 파일의 유형을 설정합니다. |
| [getPassword()](#getPassword--) | 암호화된 파일을 열기 위한 비밀번호를 가져옵니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 암호화된 파일을 열기 위한 비밀번호를 설정합니다. |
| [getCharset()](#getCharset--) | 텍스트 기반 파일이나 [FileType.CSV](../../com.groupdocs.viewer/filetype\\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\\#TXT), [FileType.MSG](../../com.groupdocs.viewer/filetype\\#MSG)와 같은 이메일 메시지를 열 때 사용되는 문자 집합입니다. |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | 텍스트 기반 파일이나 [FileType.CSV](../../com.groupdocs.viewer/filetype\\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\\#TXT), [FileType.MSG](../../com.groupdocs.viewer/filetype\\#MSG)와 같은 이메일 메시지를 열 때 사용되는 문자 집합입니다. |
| [isDetectCharset()](#isDetectCharset--) | 이 옵션은 [FileType.TXT](../../com.groupdocs.viewer/filetype\\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\\#TSV), [FileType.CSV](../../com.groupdocs.viewer/filetype\\#CSV) 파일의 문자 집합 감지를 활성화합니다. |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | 이 옵션은 [FileType.TXT](../../com.groupdocs.viewer/filetype\\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\\#TSV), [FileType.CSV](../../com.groupdocs.viewer/filetype\\#CSV) 파일의 문자 집합 감지를 활성화합니다. |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | 외부 리소스를 로드하는 시간 제한을 가져옵니다. |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | 그래픽과 같은 외부 리소스를 로드하는 시간 제한을 설정합니다. |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | java.net.URL을 사용해 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 연결 시간 제한을 가져옵니다. |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | java.net.URL을 사용해 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 연결 시간 제한을 설정합니다. |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | java.net.URL을 사용해 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 읽기 시간 제한을 가져옵니다. |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | java.net.URL을 사용해 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 읽기 시간 제한을 설정합니다. |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | 아카이브 추출 프로세스를 제어하는 보안 옵션을 가져옵니다. |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | 아카이브 추출 프로세스를 제어하기 위한 보안 옵션을 설정합니다. |
| [isSkipExternalResources()](#isSkipExternalResources--) | true 로 설정하면, \#getWhitelistedResources().getWhitelistedResources() 를 제외한 이미지와 같은 모든 외부 리소스가 로드되지 않습니다. |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | true 로 설정하면, \#getWhitelistedResources().getWhitelistedResources() 를 제외한 이미지와 같은 모든 외부 리소스가 로드되지 않습니다. |
| [getWhitelistedResources()](#getWhitelistedResources--) | \#isSkipExternalResources().isSkipExternalResources() 가 `true` 로 설정될 때 로드되어야 하는 외부 리소스에 해당하는 URL 조각 목록입니다. |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | \#isSkipExternalResources().isSkipExternalResources() 가 `true` 로 설정될 때 로드되어야 하는 외부 리소스에 해당하는 URL 조각 목록을 설정합니다. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


LoadOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 열 파일의 유형입니다. |

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### _tryRepair {#-tryRepair}
```
public boolean _tryRepair
```


### isTryRepair() {#isTryRepair--}
```
public boolean isTryRepair()
```


활성화되면 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도합니다. 기본값은 false 입니다.

이 기능은 PDF 문서에서 다음 문제들을 해결합니다:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


활성화되면 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도합니다. 기본값은 false 입니다.

이 기능은 PDF 문서에서 다음 문제들을 해결합니다:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


열 파일의 유형을 가져옵니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


열 파일의 유형을 설정합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


암호화된 파일을 열기 위한 비밀번호를 가져옵니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String - 파일을 여는 비밀번호입니다.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


암호화된 파일을 열기 위한 비밀번호를 설정합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 파일을 여는 비밀번호입니다. |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


텍스트 기반 파일이나 [FileType.CSV](../../com.groupdocs.viewer/filetype\\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\\#TXT), [FileType.MSG](../../com.groupdocs.viewer/filetype\\#MSG)와 같은 이메일 메시지를 열 때 사용되는 문자 집합입니다.

기본값은 java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8 입니다. 코드 예제는 [documentation][]을 참조하십시오.

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


텍스트 기반 파일이나 [FileType.CSV](../../com.groupdocs.viewer/filetype\\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\\#TXT), [FileType.MSG](../../com.groupdocs.viewer/filetype\\#MSG)와 같은 이메일 메시지를 열 때 사용되는 문자 집합입니다.

기본값은 java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8 입니다. 코드 예제는 [documentation][]을 참조하십시오.

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


이 옵션은 [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), 및 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) 파일의 문자 집합 감지를 활성화합니다. 문자 집합을 감지할 수 없는 경우 기본 [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--)이 사용됩니다.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

인코딩을 감지할 수 없으면 기본값이 사용됩니다. 코드 예제는 [documentation][]을 참조하십시오.

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


이 옵션은 [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV), 및 [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) 파일의 문자 집합 감지를 활성화합니다. 문자 집합을 감지할 수 없는 경우 기본 [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--)이 사용됩니다.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

인코딩을 감지할 수 없으면 기본값이 사용됩니다. 코드 예제는 [documentation][]을 참조하십시오.

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


외부 리소스를 로드하는 시간 제한을 가져옵니다.

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

기본값은 30초입니다. 코드 예제는 [documentation][]을 참조하십시오.

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setResourceLoadingTimeout(5000); // Set resource loading timeout to 5 seconds

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


그래픽과 같은 외부 리소스를 로드하는 시간 제한을 설정합니다.

***Note:** The default value is 30 seconds.*

이 옵션은 외부 리소스를 포함하는 워드 프로세싱 문서에서 지원됩니다. 기본값은 30초입니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resourceLoadingTimeout | int | 로드 제한 시간(밀리초)입니다. |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


java.net.URL을 사용해 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 연결 시간 제한을 가져옵니다.

***Note:** The default value is 5 seconds.*

**Returns:**
int - 연결 제한 시간입니다.
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


java.net.URL을 사용해 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 연결 시간 제한을 설정합니다.

***Note:** The default value is 5 seconds.*

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| urlConnectTimeout | int | 연결 제한 시간입니다. |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


java.net.URL을 사용해 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 읽기 시간 제한을 가져옵니다.

***Note:** The default value is 30 seconds.*

**Returns:**
int - 읽기 제한 시간입니다.
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


java.net.URL을 사용해 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 읽기 시간 제한을 설정합니다.

***Note:** The default value is 30 seconds.*

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| urlReadTimeout | int | 읽기 제한 시간. |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


아카이브 추출 프로세스를 제어하는 보안 옵션을 가져옵니다.

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - 아카이브 추출 프로세스를 구성하기 위한 옵션 객체.
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


아카이브 추출 프로세스를 제어하기 위한 보안 옵션을 설정합니다.

***Note:** Not each archive type supports all options.*

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | 아카이브 추출 프로세스를 구성하기 위한 옵션 객체. |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


true 로 설정하면, \#getWhitelistedResources().getWhitelistedResources() 를 제외한 이미지와 같은 모든 외부 리소스가 로드되지 않습니다.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


true 로 설정하면, \#getWhitelistedResources().getWhitelistedResources() 를 제외한 이미지와 같은 모든 외부 리소스가 로드되지 않습니다.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| skipExternalResources | boolean | 외부 리소스 로드를 활성화하거나 비활성화하는 플래그. |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


\#isSkipExternalResources().isSkipExternalResources() 가 `true` 로 설정될 때 로드되어야 하는 외부 리소스에 해당하는 URL 조각 목록입니다.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


\#isSkipExternalResources().isSkipExternalResources() 가 `true` 로 설정될 때 로드되어야 하는 외부 리소스에 해당하는 URL 조각 목록을 설정합니다.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | 로드해야 하는 외부 리소스에 해당하는 URL 조각 목록. |

