---
title: "CancellationTokenSource"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Сигналы к  о том, что операция должна быть отменена."
type: docs
weight: 11
url: /ru/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Сигналы к [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) о том, что операция должна быть отменена.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Методы

| Метод | Описание |
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




