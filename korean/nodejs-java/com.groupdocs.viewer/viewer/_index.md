---
title: "Viewer"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "문서 렌더링 프로세스를 제어하는 주요 클래스를 나타냅니다."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

문서 렌더링 프로세스를 제어하는 주요 클래스를 나타냅니다.

Viewer 클래스는 GroupDocs.Viewer 구성 요소를 사용하여 문서를 렌더링하기 위한 진입점입니다. 다양한 소스에서 문서를 로드하고, 렌더링 프로세스를 맞춤 설정하며, 다양한 형식으로 렌더링된 출력을 가져오는 메서드와 옵션을 제공합니다.

예시 사용법:

```

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(URL url)](#Viewer-java.net.URL-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(String filePath)](#Viewer-java.lang.String-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
| [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | 뷰와 문서에 대한 특정 정보를 반환합니다. |
| [getAttachments()](#getAttachments--) | 문서에 포함된 첨부 파일을 반환합니다. |
| [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | 첨부 파일을 대상 스트림에 저장합니다. |
| [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | 전체 문서 페이지의 뷰를 생성합니다. |
| [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | 특정 문서 페이지의 뷰를 생성합니다. |
| [getAllFonts()](#getAllFonts--) | 로드된 문서에서 사용된 모든 글꼴을 반환합니다. 여기에는 문서 자체에 포함된 글꼴과 OS에 설치되어 문서에서 사용되는 시스템 글꼴이 포함됩니다. |
| [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | 제공된 옵션에 따라 로드된 문서에서 텍스트 검색을 수행하고 일치 항목을 (찾은 경우) 강조 표시합니다. |
| [getFileInfo()](#getFileInfo--) | 파일 유형 및 파일이 암호화되었는지 여부를 나타내는 플래그와 같은 파일 정보를 반환합니다. |
| [close()](#close--) | 파일 스트림과 관리되는 내부 리소스를 해제합니다. |
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

GroupDocs.Viewer에서 지원하는 파일 유형에 대한 자세한 내용: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStream | java.io.InputStream | 읽을 수 있는 스트림을 반환하는 메서드. |

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStream | java.io.InputStream | 파일 스트림입니다. |
| leaveOpen | boolean | Viewer 객체가 해제된 후 스트림을 열어 두려면 true; 그렇지 않으면 false. |

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStream | java.io.InputStream | 읽을 수 있는 스트림. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStream | java.io.InputStream | 파일 스트림입니다. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |
| leaveOpen | boolean | Viewer 객체가 해제된 후 스트림을 열어 두려면 true; 그렇지 않으면 false. |

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStream | java.io.InputStream | 파일 스트림입니다. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStream | java.io.InputStream | 파일 스트림입니다. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |
| leaveOpen | boolean | Viewer 객체가 해제된 후 스트림을 열어 두려면 true; 그렇지 않으면 false. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStream | java.io.InputStream | 파일 스트림입니다. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStream | java.io.InputStream | 파일 스트림입니다. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |
| leaveOpen | boolean | Viewer 객체가 해제된 후 스트림을 열어 두려면 true; 그렇지 않으면 false. |

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

GroupDocs.Viewer에서 지원하는 파일 유형에 대한 자세한 내용: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.net.URL | Viewer에 로드되어야 하는 파일의 URL. |

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.net.URL | Viewer에 로드되어야 하는 파일의 URL. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.net.URL | Viewer에 로드되어야 하는 파일의 URL. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.net.URL | Viewer에 로드되어야 하는 파일의 URL. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

이 생성자를 사용하면 지정된 [ViewerSettings](../../com.groupdocs.viewer/viewersettings)를 사용하여 [FileReader](../../com.groupdocs.viewer.interfaces/filereader)에서 문서를 보기 위한 Viewer 객체를 생성할 수 있습니다.

 **Learn more**

 *  To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer][]
 *  To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Viewer에 로드될 문서를 포함하는 [FileReader](../../com.groupdocs.viewer.interfaces/filereader). |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer에 적용될 [ViewerSettings](../../com.groupdocs.viewer/viewersettings). |

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

GroupDocs.Viewer를 사용하여 문서를 로드하고 보는 기능을 제공합니다.

**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | 파일 리더. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 로드 옵션. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more:**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 렌더링할 파일의 경로. |

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.nio.file.Path | 렌더링할 파일의 경로. |

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 렌더링할 파일의 경로. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view a document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.nio.file.Path | 렌더링할 파일의 경로. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 렌더링할 파일의 경로. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.nio.file.Path | 렌더링할 파일의 경로. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view documents with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 렌더링할 파일의 경로. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer 클래스의 새 인스턴스를 초기화합니다.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view documents with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.nio.file.Path | 렌더링할 파일의 경로. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | 문서 로드 옵션. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer 설정. |

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


뷰와 문서에 대한 특정 정보를 반환합니다.

 **Learn more:**

 *  Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer][]


[How to get file information using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+file+information

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | 뷰 정보 옵션. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.
### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


문서에 포함된 첨부 파일을 반환합니다.

 **Learn more:**

 *  Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get a list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - 문서에 포함된 첨부 파일.
### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


첨부 파일을 대상 스트림에 저장합니다.

 **Learn more:**

 *  Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get a list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | 첨부 파일. |
| 대상 | java.io.OutputStream | 쓰기 가능한 스트림입니다. |

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


전체 문서 페이지의 뷰를 생성합니다.

 **Learn more**

 *  Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 보기 옵션입니다. |

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


특정 문서 페이지의 뷰를 생성합니다.

 **Learn more**

 *  Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | 보기 옵션입니다. |
| pageNumbers | int[] | 볼 페이지 번호입니다. |

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


로드된 문서에서 사용된 모든 글꼴을 반환합니다. 여기에는 문서 자체에 포함된 글꼴과 OS에 설치되어 문서에서 사용되는 시스템 글꼴이 포함됩니다.

자세한 내용은 [ documentation][documentation]을(를) 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - null이 아닌 목록으로, 이 문서에 로드된 모든 글꼴이며, 이 [Viewer](../../com.groupdocs.viewer/viewer) 인스턴스에 사용됩니다.
### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


제공된 옵션에 따라 로드된 문서에서 텍스트 검색을 수행하고 일치 항목을 (찾은 경우) 강조 표시합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | com.groupdocs.viewer.options.SearchHighlightOptions | 검색 및 강조 옵션으로, 검색할 텍스트 구문을 포함합니다. null일 수 없습니다. |

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


파일 유형 및 파일이 암호화되었는지 여부를 나타내는 플래그와 같은 파일 정보를 반환합니다.

**Learn more:**

 *  Learn more about how to check if a file is encrypted: [How to check if a file is encrypted][]


[How to check if a file is encrypted]: https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.
### close() {#close--}
```
public final void close()
```


파일 스트림과 관리되는 내부 리소스를 해제합니다.

