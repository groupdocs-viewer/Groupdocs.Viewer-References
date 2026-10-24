---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "向一个  发出操作应被取消的信号。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

向一个 [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) 发出操作应被取消的信号。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## 方法

| 方法 | 描述 |
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




