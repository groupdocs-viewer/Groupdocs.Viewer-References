---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "एक  को संकेत देता है कि एक ऑपरेशन रद्द किया जाना चाहिए।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

एक [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) को संकेत देता है कि एक ऑपरेशन रद्द किया जाना चाहिए।

## Constructors

| Constructor | विवरण |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Methods

| Method | विवरण |
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




