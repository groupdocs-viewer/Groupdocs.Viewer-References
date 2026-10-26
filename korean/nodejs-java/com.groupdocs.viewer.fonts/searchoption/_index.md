---
title: "SearchOption"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "현재 폴더만 검색할지, 현재 폴더와 모든 하위 폴더를 검색할지를 지정합니다."
type: docs
weight: 21
url: /ko/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

현재 폴더만 검색할지, 현재 폴더와 모든 하위 폴더를 검색할지를 지정합니다.

SearchOption 열거형은 GroupDocs.Viewer API에서 글꼴 검색 작업의 범위를 지정하는 데 사용됩니다.

예시 사용법:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## 필드

| 필드 | 설명 |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | 검색에 현재 폴더만 포함합니다. |
| [ALL_FOLDERS](#ALL-FOLDERS) | 검색에 현재 폴더와 모든 하위 폴더를 포함합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


검색에 현재 폴더만 포함합니다.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


검색에 현재 폴더와 모든 하위 폴더를 포함합니다.

### values() {#values--}
```
public static SearchOption[] values()
```




**Returns:**
com.groupdocs.viewer.fonts.SearchOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SearchOption valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
