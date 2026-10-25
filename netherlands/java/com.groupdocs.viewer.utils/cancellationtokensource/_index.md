---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Geeft een signaal aan een  dat een bewerking geannuleerd moet worden."
type: docs
weight: 11
url: /nl/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Geeft een signaal aan een [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) dat een bewerking geannuleerd moet worden.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Methoden

| Methode | Beschrijving |
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




