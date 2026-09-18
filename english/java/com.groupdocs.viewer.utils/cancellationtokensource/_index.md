---
title: CancellationTokenSource
second_title: GroupDocs.Viewer for Java API Reference
description: Signals to a  that an operation should be canceled.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Signals to a [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) that an operation should be canceled.

## Constructors

| Constructor | Description |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Methods

| Method | Description |
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




