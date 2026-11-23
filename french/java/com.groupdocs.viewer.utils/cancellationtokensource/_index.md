---
title: "CancellationTokenSource"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Signale à un  que l'opération doit être annulée."
type: docs
weight: 11
url: /fr/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Signale à un [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) que l'opération doit être annulée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Méthodes

| Méthode | Description |
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




