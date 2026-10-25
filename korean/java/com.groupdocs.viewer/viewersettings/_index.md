---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer 구성 요소의 동작을 사용자 지정하기 위한 설정을 정의합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Viewer 구성 요소의 동작을 사용자 지정하기 위한 설정을 정의합니다.


ViewerSettings 클래스는 문서 렌더링 과정에서 GroupDocs.Viewer 구성 요소의 동작을 사용자 지정할 수 있는 옵션 및 속성을 제공합니다.
이 클래스를 사용하여 로거, 사용자 정의 캐시 구현 등 다양한 설정을 지정할 수 있습니다.


사용 예시:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | 새 인스턴스를 초기화합니다. |
ViewerSettings
클래스.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | 새 인스턴스를 초기화합니다. |
ViewerSettings
클래스.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | 새 인스턴스를 초기화합니다. |
ViewerSettings
클래스.
|
|  | [ViewerSettings()](#ViewerSettings--) | 새 인스턴스를 초기화합니다. |
ViewerSettings
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getLogger()](#getLogger--) | 로깅에 사용되는 로거 구현(오류, 경고, 추적)을 가져옵니다. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | 로깅에 사용되는 로거 구현(오류, 경고, 추적)을 설정합니다. |
|
|  | [getCache()](#getCache--) | 렌더링 결과를 저장하는 데 사용되는 캐시 구현을 가져옵니다. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | 렌더링 결과를 저장하는 데 사용되는 캐시 구현을 설정합니다. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


새 인스턴스를 초기화합니다.
ViewerSettings
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | 캐시입니다. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | 로거입니다. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


새 인스턴스를 초기화합니다.
ViewerSettings
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | 로거입니다. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


새 인스턴스를 초기화합니다.
ViewerSettings
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | 캐시입니다. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


새 인스턴스를 초기화합니다.
ViewerSettings
클래스.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


로깅에 사용되는 로거 구현(오류, 경고, 추적)을 가져옵니다.


**Returns:**
com.groupdocs.foundation.logging.ILogger - 로거 구현입니다.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


로깅에 사용되는 로거 구현(오류, 경고, 추적)을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | 설정할 로거 구현입니다. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


렌더링 결과를 저장하는 데 사용되는 캐시 구현을 가져옵니다.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


렌더링 결과를 저장하는 데 사용되는 캐시 구현을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | 캐시 구현. |
|

