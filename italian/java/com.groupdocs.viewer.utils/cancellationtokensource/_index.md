---
title: "CancellationTokenSource"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Segnala a  che un'operazione dovrebbe essere annullata."
type: docs
weight: 11
url: /it/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Segnala a [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) che un'operazione dovrebbe essere annullata.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Metodi

| Metodo | Descrizione |
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




