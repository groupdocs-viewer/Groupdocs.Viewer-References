---
title: "LoadOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "파일을 열 때 사용되는 옵션을 제공합니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

파일을 열 때 사용되는 옵션을 제공합니다.


LoadOptions 클래스는 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다
파일이 GroupDocs.Viewer 구성 요소에서 어떻게 열리고 로드되어야 하는지를 지정합니다.
자세한 내용은 이 [page](../https://docs.groupdocs.com/viewer/java/loading/) 및 해당 하위 페이지를 참조하십시오.


사용 예시:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | 새 인스턴스를 초기화합니다. |
LoadOptions
클래스.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | 새 인스턴스를 초기화합니다. |
LoadOptions
클래스.
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | 활성화되면 GroupDocs.Viewer는 PDF 문서의 구조적 손상을 복구하려고 시도합니다. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | 활성화되면 GroupDocs.Viewer는 PDF 문서의 구조적 손상을 복구하려고 시도합니다. |
|
|  | [getFileType()](#getFileType--) | 열 파일의 유형을 가져옵니다. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | 열 파일의 유형을 설정합니다. |
|
|  | [getPassword()](#getPassword--) | 암호화된 파일을 열기 위한 비밀번호를 가져옵니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 암호화된 파일을 열기 위한 비밀번호를 설정합니다. |
|
|  | [getCharset()](#getCharset--) | 텍스트 기반 파일이나 이메일 메시지를 열 때 사용되는 문자 집합은 다음과 같습니다 |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
및 [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | 텍스트 기반 파일이나 이메일 메시지를 열 때 사용되는 문자 집합은 다음과 같습니다 |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
및 [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | 이 옵션은 [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), 및 [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) 파일의 문자 집합 감지를 활성화합니다. |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | 이 옵션은 [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), 및 [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) 파일의 문자 집합 감지를 활성화합니다. |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | 외부 리소스를 로드하기 위한 제한 시간을 가져옵니다. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | 그래픽과 같은 외부 리소스를 로드하기 위한 제한 시간을 설정합니다. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | java.net.URL을 사용하여 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 연결 제한 시간을 가져옵니다. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | java.net.URL을 사용하여 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 연결 제한 시간을 설정합니다. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | java.net.URL을 사용하여 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 읽기 제한 시간을 가져옵니다. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | java.net.URL을 사용하여 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 읽기 제한 시간을 설정합니다. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | 아카이브 추출 프로세스를 제어하기 위한 보안 옵션을 가져옵니다. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | 아카이브 추출 프로세스를 제어하기 위한 보안 옵션을 설정합니다. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | true로 설정하면 이미지와 같은 모든 외부 리소스는 #getWhitelistedResources().getWhitelistedResources()를 제외하고 로드되지 않습니다. |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | true로 설정하면 이미지와 같은 모든 외부 리소스는 #getWhitelistedResources().getWhitelistedResources()를 제외하고 로드되지 않습니다. |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | #isSkipExternalResources().isSkipExternalResources()가 `true`로 설정될 때 로드되어야 하는 외부 리소스에 해당하는 URL 조각 목록입니다. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | 외부 리소스를 로드해야 할 URL 조각 목록을 설정합니다. #isSkipExternalResources().isSkipExternalResources() 가 `true` 로 설정된 경우. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


새 인스턴스를 초기화합니다.
LoadOptions
클래스.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/)을 참조하십시오.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


새 인스턴스를 초기화합니다.
LoadOptions
클래스.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | 열 파일의 유형입니다. |
|

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


활성화되면 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도합니다. 기본값은 false입니다.


이 기능은 PDF 문서의 다음 문제들을 해결합니다:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


활성화되면 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도합니다. 기본값은 false입니다.


이 기능은 PDF 문서의 다음 문제들을 해결합니다:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


열 파일의 유형을 가져옵니다.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/)을 참조하십시오.


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


열 파일의 유형을 설정합니다.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


암호화된 파일을 열기 위한 비밀번호를 가져옵니다.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/)을 참조하십시오.


**Returns:**
java.lang.String - 파일을 열기 위한 비밀번호입니다.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


암호화된 파일을 열기 위한 비밀번호를 설정합니다.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 파일을 열기 위한 비밀번호입니다. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


텍스트 기반 파일이나 이메일 메시지를 열 때 사용되는 문자 집합은 다음과 같습니다
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
및 [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
기본값은 java.nio.charset.StandardCharsets#UTF_8.UTF_8입니다. 코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/)을 참조하십시오.

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // 문자 집합을 설정합니다

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


텍스트 기반 파일이나 이메일 메시지를 열 때 사용되는 문자 집합은 다음과 같습니다
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
및 [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
기본값은 java.nio.charset.StandardCharsets#UTF_8.UTF_8입니다. 코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/)을 참조하십시오.

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // 문자 집합을 설정합니다

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


이 옵션은 [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), 및 [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) 파일의 문자 집합 감지를 활성화합니다. 문자 집합을 감지할 수 없는 경우 기본 [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--)이 사용됩니다.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


인코딩을 감지할 수 없는 경우 기본값이 사용됩니다. 코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/)을 참조하십시오.

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // 인코딩 감지를 활성화합니다

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


이 옵션은 [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), 및 [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) 파일의 문자 집합 감지를 활성화합니다. 문자 집합을 감지할 수 없는 경우 기본 [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--)이 사용됩니다.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


인코딩을 감지할 수 없는 경우 기본값이 사용됩니다. 코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/)을 참조하십시오.

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // 인코딩 감지를 활성화합니다

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


외부 리소스를 로드하기 위한 제한 시간을 가져옵니다.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


기본값은 30초입니다. 코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents)를 참조하십시오.

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // 리소스 로딩 제한 시간을 5초로 설정합니다

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


그래픽과 같은 외부 리소스를 로드하기 위한 제한 시간을 설정합니다.


***Note:** The default value is 30 seconds.*


이 옵션은 외부 리소스를 포함하는 워드 프로세싱 문서에서 지원됩니다.
기본값은 30초입니다. 코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | 로드 시간 초과, 밀리초. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


java.net.URL을 사용하여 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 연결 제한 시간을 가져옵니다.


***Note:** The default value is 5 seconds.*


**Returns:**
int - 연결 시간 초과.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


java.net.URL을 사용하여 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 연결 제한 시간을 설정합니다.


***Note:** The default value is 5 seconds.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | urlConnectTimeout | int | 연결 시간 초과. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


java.net.URL을 사용하여 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 읽기 제한 시간을 가져옵니다.


***Note:** The default value is 30 seconds.*


**Returns:**
int - 읽기 시간 초과.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


java.net.URL을 사용하여 문서를 로드하기 위해 [Viewer](../../com.groupdocs.viewer/viewer)를 생성할 때 읽기 제한 시간을 설정합니다.


***Note:** The default value is 30 seconds.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | urlReadTimeout | int | 읽기 시간 초과. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


아카이브 추출 프로세스를 제어하기 위한 보안 옵션을 가져옵니다.


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
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | 아카이브 추출 프로세스를 구성하기 위한 옵션 객체. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


true로 설정하면 이미지와 같은 모든 외부 리소스는 #getWhitelistedResources().getWhitelistedResources()를 제외하고 로드되지 않습니다.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // 외부 리소스 로드를 건너뛰기

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


true로 설정하면 이미지와 같은 모든 외부 리소스는 #getWhitelistedResources().getWhitelistedResources()를 제외하고 로드되지 않습니다.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // 외부 리소스 로드를 건너뛰기

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | skipExternalResources | boolean | 외부 리소스 로드를 활성화하거나 비활성화하는 플래그. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


#isSkipExternalResources().isSkipExternalResources()가 `true`로 설정될 때 로드되어야 하는 외부 리소스에 해당하는 URL 조각 목록입니다.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // 외부 리소스 로드를 건너뛰기
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // 리소스 URL에 'avatars.githubusercontent.com' 조각이 포함된 외부 리소스 로드 활성화
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


외부 리소스를 로드해야 할 URL 조각 목록을 설정합니다. #isSkipExternalResources().isSkipExternalResources() 가 `true` 로 설정된 경우.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // 외부 리소스 로드를 건너뛰기
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // 리소스 URL에 'avatars.githubusercontent.com' 조각이 포함된 외부 리소스 로드 활성화
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | 로드해야 하는 외부 리소스에 해당하는 URL 조각 목록. |
|

