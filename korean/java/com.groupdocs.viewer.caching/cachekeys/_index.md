---
title: "CacheKeys"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "캐시 항목에 대한 고유 식별자를 검색하는 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

캐시 항목에 대한 고유 식별자를 검색하는 메서드를 제공합니다.


이 클래스는 문서 경로, 렌더링 옵션, 리소스 이름과 같은 다양한 매개변수를 기반으로 캐시 키를 생성할 수 있게 해줍니다.
이러한 캐시 키는 효율적인 문서 렌더링을 위해 캐시된 데이터를 저장하고 검색하는 데 사용할 수 있습니다.


사용 예시:

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | 컬렉션인 [Attachment](../../com.groupdocs.viewer.results/attachment) 객체들을 나타내는 캐시 항목의 고유 식별자를 반환합니다. |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | 첨부 파일을 나타내는 캐시 항목의 고유 식별자를 검색합니다. |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 객체를 나타내는 캐시 항목의 고유 식별자를 검색합니다. |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 객체를 나타내는 캐시 항목의 고유 식별자를 검색합니다. |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | 파일을 나타내는 캐시 항목의 고유 식별자를 검색합니다. |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | 페이지 파일을 나타내는 캐시 항목의 고유 식별자를 검색합니다. |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | [Resource](../../com.groupdocs.viewer.results/resource) 객체를 나타내는 캐시 항목의 고유 식별자를 반환합니다. |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | [Resource](../../com.groupdocs.viewer.results/resource) 객체를 나타내는 캐시 항목을 검색하기 위한 필터 문자열을 반환합니다. |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


컬렉션인 [Attachment](../../com.groupdocs.viewer.results/attachment) 객체들을 나타내는 캐시 항목의 고유 식별자를 반환합니다.


**Returns:**
java.lang.String - 첨부 파일 캐시 항목의 고유 식별자.

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


첨부 파일을 나타내는 캐시 항목의 고유 식별자를 검색합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | attachmentId | java.lang.String | 첨부 파일의 고유 식별자(단일 파일 컨텍스트 내). |
|

**Returns:**
java.lang.String - 첨부 파일 캐시 항목의 고유 식별자.

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 객체를 나타내는 캐시 항목의 고유 식별자를 검색합니다.


**Returns:**
java.lang.String - 캐시 항목의 고유 식별자.

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 객체를 나타내는 캐시 항목의 고유 식별자를 검색합니다.


**Returns:**
java.lang.String - [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 객체를 나타내는 캐시 항목의 고유 식별자.

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


파일을 나타내는 캐시 항목의 고유 식별자를 검색합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | extension | java.lang.String | 파일 이름 접미사(마침표 "." 포함) 예: ".doc". |
|

**Returns:**
java.lang.String - 파일을 나타내는 캐시 항목의 고유 식별자.

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


페이지 파일을 나타내는 캐시 항목의 고유 식별자를 검색합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageNumber | int | 페이지 번호. |
|
|  | extension | java.lang.String | 파일 이름 접미사(마침표 "." 포함) 예: ".doc". |
|

**Returns:**
java.lang.String - 페이지 파일을 나타내는 캐시 항목의 고유 식별자.

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


[Resource](../../com.groupdocs.viewer.results/resource) 객체를 나타내는 캐시 항목의 고유 식별자를 반환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageNumber | int | 페이지 번호. |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML 리소스. |
|

**Returns:**
java.lang.String - 캐시 항목의 고유 식별자.

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


[Resource](../../com.groupdocs.viewer.results/resource) 객체를 나타내는 캐시 항목을 검색하기 위한 필터 문자열을 반환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageNumber | int | 페이지 번호. |
|

**Returns:**
java.lang.String - 캐시 항목을 검색하기 위한 필터 문자열.

