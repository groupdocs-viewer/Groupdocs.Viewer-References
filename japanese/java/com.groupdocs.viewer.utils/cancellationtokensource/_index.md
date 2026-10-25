---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "操作をキャンセルすべきであることを  にシグナルします。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

操作をキャンセルすべきであることを [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) にシグナルします。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## メソッド

| メソッド | 説明 |
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




