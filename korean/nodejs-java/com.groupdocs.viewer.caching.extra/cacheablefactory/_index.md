---
title: "CacheableFactory"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "이 클래스는 사용자 정의를 돕습니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

이 클래스는 [Cache](../../com.groupdocs.viewer.caching/cache)를 사용자 정의하는 데 도움이 됩니다.

직렬화를 위한 사용자 정의 모델은 이 클래스의 메서드를 재정의하여 내장된 모델 대신 반환하도록 구현할 수 있습니다. 이를 위해 CacheableFactory를 확장하고 새 사용자 정의 팩토리 인스턴스를 [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-) 메서드에 전달하여 활성화합니다.

예시 사용법:

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

캐시 사용자 정의에 대한 자세한 내용, 가이드 및 예제는 [GroupDocs.Viewer documentation][].을 참조하십시오.


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInstance()](#getInstance--) | 캐시 가능한 객체를 생성하는 데 사용할 수 있는 CacheableFactory 인스턴스를 가져옵니다. |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | 사용할 CacheableFactory 인스턴스를 설정합니다. |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | 지정된 파일 유형 및 페이지에 대한 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 인터페이스 구현을 생성합니다. |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | 지정된 파일 유형, 페이지 및 노트 수에 대한 [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) 인터페이스 구현을 생성합니다. |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | 지정된 파일 유형, 페이지 및 폴더에 대한 [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) 인터페이스 구현을 생성합니다. |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | 지정된 문자, 위치 및 차원에 대한 [Character](../../com.groupdocs.viewer.results/character) 인터페이스 구현을 생성합니다. |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | 지정된 파일 유형에 대한 [FileInfo](../../com.groupdocs.viewer.results/fileinfo) 인터페이스 구현을 생성합니다. |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | 지정된 이름 및 가시성을 가진 [Layer](../../com.groupdocs.viewer.results/layer) 인터페이스 구현을 생성합니다. |
| [newLayer(String name)](#newLayer-java.lang.String-) | 지정된 이름을 가진 [Layer](../../com.groupdocs.viewer.results/layer) 인터페이스 구현을 생성합니다. |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | 지정된 이름, 너비 및 높이를 가진 [Layout](../../com.groupdocs.viewer.results/layout) 인터페이스 구현을 생성합니다. |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | 지정된 라인, 위치, 차원 및 단어를 가진 [Line](../../com.groupdocs.viewer.results/line) 인터페이스 구현을 생성합니다. |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | [Attachment](../../com.groupdocs.viewer.results/attachment) 인터페이스 구현을 생성합니다. |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) 인터페이스 구현을 생성합니다. |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) 인터페이스 구현을 생성합니다. |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) 인터페이스 구현을 생성합니다. |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | 지정된 파일 유형, 페이지 목록 및 폴더 목록을 기반으로 하는 [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) 인터페이스 구현을 생성합니다. |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | 지정된 번호와 가시성을 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스 구현을 생성합니다. |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | 지정된 번호, 이름 및 가시성을 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스 구현을 생성합니다. |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | 지정된 번호, 이름, 가시성, 너비 및 높이를 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스 구현을 생성합니다. |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | 지정된 번호, 가시성, 너비 및 높이를 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스의 구현을 생성합니다. |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | 지정된 번호, 이름, 가시성, 너비, 높이 및 라인을 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스의 구현을 생성합니다. |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | 지정된 번호, 가시성, 너비, 높이 및 라인을 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스의 구현을 생성합니다. |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | 지정된 파일 유형, 페이지 및 인쇄 허용 플래그를 가진 [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) 인터페이스의 구현을 생성합니다. |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | 지정된 파일 유형, 페이지, 레이어 및 레이아웃을 가진 [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) 인터페이스의 구현을 생성합니다. |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | 지정된 파일 유형, 페이지, 시작 날짜 및 종료 날짜를 가진 [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) 인터페이스의 구현을 생성합니다. |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | 지정된 값, 좌표 및 차원을 가진 [TextElement](../../com.groupdocs.viewer.results/textelement) 인터페이스의 구현을 생성합니다. |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | 지정된 파일 유형, 페이지 및 노트 수를 가진 MboxViewInfo 인터페이스의 구현을 생성합니다. |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | 지정된 단어, 좌표, 차원 및 문자를 가진 [Word](../../com.groupdocs.viewer.results/word) 인터페이스의 구현을 생성합니다. |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


캐시 가능한 객체를 생성하는 데 사용할 수 있는 CacheableFactory 인스턴스를 가져옵니다.

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


사용할  CacheableFactory  인스턴스를 설정합니다. 이는 캐시 가능한 팩토리의 사용자 정의 구현을 허용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | 설정할  CacheableFactory  인스턴스입니다. |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


지정된 파일 유형 및 페이지에 대한 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | 문서 페이지를 나타내는 페이지 목록입니다. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


지정된 파일 유형, 페이지 및 노트 수에 대한 [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | 문서 페이지를 나타내는 페이지 목록입니다. |
| notesCount | int | 문서에 포함된 Lotus Notes의 개수입니다. |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


지정된 파일 유형, 페이지 및 폴더에 대한 [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | 문서 페이지를 나타내는 페이지 목록입니다. |
| folders | java.util.List<java.lang.String> | 아카이브에 있는 폴더 목록입니다. |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


지정된 문자, 위치 및 차원에 대한 [Character](../../com.groupdocs.viewer.results/character) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| character | char | 문자입니다. |
| x | double | 문자 위치의 x 좌표입니다. |
| y | double | 문자 위치의 y 좌표입니다. |
| width | double | 문자의 너비. |
| height | double | 문자의 높이. |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


지정된 파일 유형에 대한 [FileInfo](../../com.groupdocs.viewer.results/fileinfo) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


지정된 이름 및 가시성을 가진 [Layer](../../com.groupdocs.viewer.results/layer) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 레이어의 이름. |
| 보임 | boolean | 레이어의 가시성. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


지정된 이름을 가진 [Layer](../../com.groupdocs.viewer.results/layer) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 레이어의 이름. |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


지정된 이름, 너비 및 높이를 가진 [Layout](../../com.groupdocs.viewer.results/layout) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 레이아웃의 이름. |
| width | double | 레이아웃의 너비. |
| height | double | 레이아웃의 높이. |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


지정된 라인, 위치, 차원 및 단어를 가진 [Line](../../com.groupdocs.viewer.results/line) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 라인 | java.lang.String | 라인 내용. |
| x | double | 라인을 포함하는 사각형의 왼쪽 위 점의 X 좌표. |
| y | double | 라인을 포함하는 사각형의 왼쪽 위 점의 Y 좌표. |
| width | double | 라인을 포함하는 사각형의 너비(픽셀 단위). |
| height | double | 라인을 포함하는 사각형의 높이(픽셀 단위). |
| 단어 | java.util.List<com.groupdocs.viewer.results.Word> | 라인에 포함된 단어. |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 첨부 파일의 이름. |
| filePath | java.lang.String | 첨부 파일의 상대 경로, 예: \"folder/file.docx\". 파일이 아카이브 루트, 이메일 메시지 또는 데이터 파일에 위치한 경우 파일 이름을 지정하십시오. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| id | java.lang.String | 첨부 파일의 ID. |
| fileName | java.lang.String | 첨부 파일의 이름. |
| filePath | java.lang.String | 첨부 파일의 상대 경로, 예: \"folder/file.docx\". 파일이 아카이브 루트, 이메일 메시지 또는 데이터 파일에 위치한 경우 파일 이름을 지정하십시오. |
| 크기 | long | 첨부 파일의 크기. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| id | java.lang.String | 첨부 파일의 ID. |
| fileName | java.lang.String | 첨부 파일의 이름. |
| filePath | java.nio.file.Path | 첨부 파일의 상대 경로나 절대 경로. |
| 크기 | long | 첨부 파일의 크기. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


다음 [Attachment](../../com.groupdocs.viewer.results/attachment) 인터페이스의 구현을 생성합니다. 첨부 파일은 문서 또는 이메일 메시지에 첨부된 파일을 나타냅니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| id | java.lang.String | 첨부 파일의 ID. |
| fileName | java.lang.String | 첨부 파일의 이름. |
| filePath | java.lang.String | 첨부 파일의 상대 경로나 절대 경로입니다. 파일이 아카이브 루트, 이메일 메시지 또는 데이터 파일에 위치한 경우 폴더 내 파일 경로나 파일 이름 자체가 될 수 있습니다. |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 첨부 파일의 유형입니다. |
| 크기 | long | 첨부 파일의 크기. |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


지정된 파일 유형, 페이지 목록 및 폴더 목록을 기반으로 하는 [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | 페이지 목록입니다. |
| folders | java.util.List<java.lang.String> | 폴더 목록입니다. |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


지정된 번호와 가시성을 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 숫자 | int | 페이지 번호입니다. |
| 보임 | boolean | 가시성 플래그입니다. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


지정된 번호, 이름 및 가시성을 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 숫자 | int | 페이지 번호입니다. |
| 이름 | java.lang.String | 페이지 이름입니다. |
| 보임 | boolean | 가시성 플래그입니다. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


지정된 번호, 이름, 가시성, 너비 및 높이를 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 숫자 | int | 페이지 번호입니다. |
| 이름 | java.lang.String | 페이지 이름입니다. |
| 보임 | boolean | 가시성 플래그입니다. |
| width | int | 페이지의 너비입니다. |
| height | int | 페이지의 높이입니다. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


지정된 번호, 가시성, 너비 및 높이를 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 숫자 | int | 페이지 번호입니다. |
| 보임 | boolean | 가시성 플래그입니다. |
| width | int | 페이지의 너비입니다. |
| height | int | 페이지의 높이입니다. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


지정된 번호, 이름, 가시성, 너비, 높이 및 라인을 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 숫자 | int | 페이지 번호입니다. |
| 이름 | java.lang.String | 페이지 이름입니다. |
| 보임 | boolean | 가시성 플래그입니다. |
| width | int | 페이지의 너비입니다. |
| height | int | 페이지의 높이입니다. |
| 라인 | java.util.List<com.groupdocs.viewer.results.Line> | 페이지에 포함된 라인입니다. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


지정된 번호, 가시성, 너비, 높이 및 라인을 가진 페이지를 나타내는 [Page](../../com.groupdocs.viewer.results/page) 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 숫자 | int | 페이지 번호입니다. |
| 보임 | boolean | 가시성 플래그입니다. |
| width | int | 페이지의 너비입니다. |
| height | int | 페이지의 높이입니다. |
| 라인 | java.util.List<com.groupdocs.viewer.results.Line> | 페이지에 포함된 라인입니다. |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


지정된 파일 유형, 페이지 및 인쇄 허용 플래그를 가진 [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | 페이지 목록입니다. |
| printingAllowed | boolean | 인쇄가 허용되는지 여부를 나타내는 플래그입니다. |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


지정된 파일 유형, 페이지, 레이어 및 레이아웃을 가진 [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | 페이지 목록입니다. |
| 레이어 | java.util.List<com.groupdocs.viewer.results.Layer> | 레이어 목록입니다. |
| 레이아웃 | java.util.List<com.groupdocs.viewer.results.Layout> | 레이아웃 목록입니다. |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


지정된 파일 유형, 페이지, 시작 날짜 및 종료 날짜를 가진 [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형입니다. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | 페이지 목록입니다. |
| startDate | java.util.Date | 시작 날짜입니다. |
| endDate | java.util.Date | 종료 날짜입니다. |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


지정된 값, 좌표 및 차원을 가진 [TextElement](../../com.groupdocs.viewer.results/textelement) 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | T | 값. |
| x | double | X 좌표. |
| y | double | Y 좌표. |
| width | double | 너비. |
| height | double | 높이. |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


지정된 파일 유형, 페이지 및 노트 수를 가진 MboxViewInfo 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | 파일 유형. |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | 볼 페이지 목록. |
| notesCount | int | Lotus 데이터베이스 저장 파일에 포함된 노트 수. |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - MboxViewInfo 구현의 새 인스턴스.
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


지정된 단어, 좌표, 차원 및 문자를 가진 [Word](../../com.groupdocs.viewer.results/word) 인터페이스의 구현을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 단어 | java.lang.String | 단어. |
| x | double | 단어를 포함하는 사각형이 시작되는 페이지 레이아웃의 가장 왼쪽 상단 점의 X 좌표. |
| y | double | 단어를 포함하는 사각형이 시작되는 페이지 레이아웃의 가장 왼쪽 상단 점의 Y 좌표. |
| width | double | 단어를 포함하는 사각형의 너비(픽셀 단위). |
| height | double | 단어를 포함하는 사각형의 높이(픽셀 단위). |
| 문자 | java.util.List<com.groupdocs.viewer.results.Character> | 단어에 포함된 문자. |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
