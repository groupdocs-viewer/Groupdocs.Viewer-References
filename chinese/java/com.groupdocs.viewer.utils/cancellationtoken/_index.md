---
title: "CancellationToken"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "传播通知，表示应取消操作。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

传播通知，表示应取消操作。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [NONE](#NONE) | 一个永不被取消的令牌。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | 如果已请求取消，则抛出 CancellationException。 |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


一个永不被取消的令牌。


### isCancellationRequested() {#isCancellationRequested--}
```
public boolean isCancellationRequested()
```




**Returns:**
boolean
### throwIfCancellationRequested() {#throwIfCancellationRequested--}
```
public void throwIfCancellationRequested()
```


如果已请求取消，则抛出 CancellationException。


