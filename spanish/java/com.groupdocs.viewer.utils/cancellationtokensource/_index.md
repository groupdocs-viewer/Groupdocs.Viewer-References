---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Señala a un  que una operación debe cancelarse."
type: docs
weight: 11
url: /es/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Señala a un [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) que una operación debe cancelarse.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Métodos

| Método | Descripción |
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




