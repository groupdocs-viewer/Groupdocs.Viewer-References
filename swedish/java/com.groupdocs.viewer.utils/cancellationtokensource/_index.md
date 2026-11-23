---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Signaliserar till en  att en operation bör avbrytas."
type: docs
weight: 11
url: /sv/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Signaliserar till en [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) att en operation bör avbrytas.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Metoder

| Metod | Beskrivning |
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




