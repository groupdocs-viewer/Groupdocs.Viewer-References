---
title: "CancellationToken"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "작업이 취소되어야 함을 알리는 알림을 전파합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

작업이 취소되어야 함을 알리는 알림을 전파합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [NONE](#NONE) | 절대로 취소되지 않는 토큰입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | 취소가 요청된 경우 CancellationException을 발생시킵니다. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


절대로 취소되지 않는 토큰입니다.


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


취소가 요청된 경우 CancellationException을 발생시킵니다.


