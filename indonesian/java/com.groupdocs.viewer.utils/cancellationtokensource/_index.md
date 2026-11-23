---
title: "CancellationTokenSource"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Memberi sinyal ke  bahwa operasi harus dibatalkan."
type: docs
weight: 11
url: /id/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Memberi sinyal ke [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) bahwa operasi harus dibatalkan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Metode

| Metode | Deskripsi |
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




