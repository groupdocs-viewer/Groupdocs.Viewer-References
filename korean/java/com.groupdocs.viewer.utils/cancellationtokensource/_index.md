---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "작업이 취소되어야 함을 알립니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

[CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken)에 작업이 취소되어야 함을 알립니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getToken()](#getToken--) |  |
| [cancel()](#cancel--) |  |
| [isCancellationRequested()](#isCancellationRequested--) |  |
| [close()](#close--) |  |
### CancellationTokenSource() {#CancellationTokenSource--}
```
public CancellationTokenSource()
```


### getToken() {#getToken--}
```
public CancellationToken getToken()
```




**Returns:**
[CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken)
### cancel() {#cancel--}
```
public void cancel()
```




### isCancellationRequested() {#isCancellationRequested--}
```
public boolean isCancellationRequested()
```




**Returns:**
boolean
### close() {#close--}
```
public void close()
```




