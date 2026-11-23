---
title: "FileCache"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "로컬 디스크 캐시를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

로컬 디스크 캐시를 나타냅니다.


FileCache 클래스는 GroupDocs.Viewer 구성 요소에서 로컬 디스크 캐시를 나타냅니다.
효율적인 문서 렌더링을 위해 디스크에 캐시된 데이터를 저장하고 검색하는 기능을 제공합니다.


사용 예시:

````

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
````


FileCache를 사용하려면 이 클래스의 인스턴스를 생성하고 ViewerSettings 객체에 전달해야 합니다.
그런 다음 Viewer 객체는 문서를 렌더링하는 동안 캐싱 목적으로 FileCache를 사용합니다.


***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer.
Cache 인터페이스를 구현하여 자체 사용자 정의 캐시를 구현할 수도 있습니다.*

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | 새 인스턴스를 생성합니다 |
FileCache
클래스.
|
|  | [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | 새 인스턴스를 생성합니다 |
FileCache
클래스.
|
|  | [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | 새 인스턴스를 생성합니다 |
FileCache
클래스.
|
|  | [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | 새 인스턴스를 생성합니다 |
FileCache
클래스.
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCachePath()](#getCachePath--) | 캐시 폴더에 대한 상대 경로나 절대 경로를 가져옵니다. |
|
|  | [getCacheSubFolder()](#getCacheSubFolder--) | 캐시 경로에 추가할 하위 폴더. |
|
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | 데이터를 로컬 디스크에 직렬화합니다. |
|
|  | [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | 해당 키와 연결된 데이터가 있으면 역직렬화합니다. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | 파일 이름에 필터가 포함된 모든 파일 이름을 반환합니다. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


새 인스턴스를 생성합니다
FileCache
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | cachePath | java.lang.String | 문서 캐시가 저장될 상대 경로나 절대 경로. |
|

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


새 인스턴스를 생성합니다
FileCache
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | 문서 캐시가 저장될 상대 경로나 절대 경로. |
|

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


새 인스턴스를 생성합니다
FileCache
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | cachePath | java.lang.String | 문서 캐시가 저장될 상대 경로나 절대 경로. |
|
|  | cacheSubFolder | java.lang.String | cachePath에 추가할 하위 폴더입니다. |
|

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


새 인스턴스를 생성합니다
FileCache
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | 문서 캐시가 저장될 상대 경로나 절대 경로. |
|
|  | cacheSubFolder | java.lang.String | cachePath에 추가할 하위 폴더입니다. |
|

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


캐시 폴더에 대한 상대 경로나 절대 경로를 가져옵니다.


**Returns:**
java.lang.String - 캐시 폴더 경로.

### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


캐시 경로에 추가할 하위 폴더.


**Returns:**
java.lang.String - 추가할 하위 폴더.

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


데이터를 로컬 디스크에 직렬화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 키 | java.lang.String | 캐시 항목에 대한 고유 식별자입니다. |
|
|  | 값 | java.lang.Object | 직렬화할 객체입니다. |
|

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


해당 키와 연결된 데이터가 있으면 역직렬화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 키 | java.lang.String | 요청된 항목을 식별하는 키입니다. |
|
|  | clazz | java.lang.Class<T> | 예상 값의 클래스입니다. |
|

**Returns:**
T - 찾은 값 또는 null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


파일 이름에 필터가 포함된 모든 파일 이름을 반환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 필터 | java.lang.String | 사용할 필터입니다. |
|

**Returns:**
java.util.List<java.lang.String> - 파일 이름에 필터가 포함된 파일명들.

