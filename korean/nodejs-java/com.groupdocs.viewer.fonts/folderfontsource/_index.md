---
title: "FolderFontSource"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "TrueType 글꼴을 포함하는 폴더를 나타냅니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

TrueType 글꼴을 포함하는 폴더를 나타냅니다.

FolderFontSource 클래스는 TrueType 글꼴이 포함된 폴더 위치를 지정하는 데 사용됩니다. 지정된 폴더에 저장된 글꼴에 대한 문서 렌더링을 위해 GroupDocs.Viewer API가 접근할 수 있도록 합니다.

예시 사용법:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | FolderFontSource 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | 두 FolderFontSource 객체가 동일한지 확인합니다. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | 두 FolderFontSource 객체가 동일하지 않은지 확인합니다. |
| [getFolderPath()](#getFolderPath--) | TrueType 글꼴이 포함된 폴더의 경로를 가져옵니다. |
| [getSearchOption()](#getSearchOption--) | 현재 폴더만 검색할지, 현재 폴더와 모든 하위 폴더를 검색할지를 지정하는 검색 옵션을 가져옵니다. |
| [isRecursive()](#isRecursive--) | 글꼴을 재귀적으로 검색할지 확인합니다. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | 현재 FolderFontSource가 지정된 FolderFontSource 객체와 동일한지 확인합니다. |
| [equals(Object o)](#equals-java.lang.Object-) | 현재 FolderFontSource가 지정된 객체와 동일한지 확인합니다. |
| [hashCode()](#hashCode--) | 현재 FolderFontSource 객체의 해시 코드를 반환합니다. |
| [toString()](#toString--) | 현재 객체를 나타내는 문자열을 반환합니다. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


FolderFontSource 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| folderPath | java.lang.String | TrueType 글꼴이 포함된 폴더의 경로. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | 현재 폴더만 검색할지, 현재 폴더와 모든 하위 폴더를 검색할지를 지정합니다. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


두 FolderFontSource 객체가 동일한지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 왼쪽 FolderFontSource 객체. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 오른쪽 FolderFontSource 객체. |

**Returns:**
boolean - 두 FolderFontSource 객체가 동일하면 true; 그렇지 않으면 false.
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


두 FolderFontSource 객체가 동일하지 않은지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 왼쪽 FolderFontSource 객체. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 오른쪽 FolderFontSource 객체. |

**Returns:**
boolean - 두 FolderFontSource 객체가 동일하지 않으면 true; 그렇지 않으면 false.
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


TrueType 글꼴이 포함된 폴더의 경로를 가져옵니다.

**Returns:**
java.lang.String - TrueType 글꼴이 포함된 폴더의 경로.
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


현재 폴더만 검색할지, 현재 폴더와 모든 하위 폴더를 검색할지를 지정하는 검색 옵션을 가져옵니다.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


글꼴을 재귀적으로 검색할지 확인합니다.

**Returns:**
boolean - 글꼴을 재귀적으로 검색할 경우 true, 그렇지 않으면 false.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


현재 FolderFontSource가 지정된 FolderFontSource 객체와 동일한지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 현재 FolderFontSource 객체와 비교할 객체. |

**Returns:**
boolean - 두 FolderFontSource 객체가 동일하면 true, 그렇지 않으면 false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


현재 FolderFontSource가 지정된 객체와 동일한지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| o | java.lang.Object | 현재 FolderFontSource 객체와 비교할 객체. |

**Returns:**
boolean - obj 매개변수가 FolderFontSource 타입이며 현재 FolderFontSource 객체와 동일하면 true, 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


현재 FolderFontSource 객체의 해시 코드를 반환합니다.

**Returns:**
int - 현재 FolderFontSource 객체의 해시 코드.
### toString() {#toString--}
```
public String toString()
```


현재 객체를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 현재 객체를 나타내는 문자열.
