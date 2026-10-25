---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Bir işlemin iptal edilmesi gerektiğini bir  nesnesine bildirir."
type: docs
weight: 11
url: /tr/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Bir işlemin iptal edilmesi gerektiğini bir [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) nesnesine bildirir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Yöntemler

| Yöntem | Açıklama |
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




