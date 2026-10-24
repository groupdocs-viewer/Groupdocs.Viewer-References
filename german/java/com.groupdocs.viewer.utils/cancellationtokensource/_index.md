---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Signalisiert einem  dass ein Vorgang abgebrochen werden soll."
type: docs
weight: 11
url: /de/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Signalisiert einem [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken), dass ein Vorgang abgebrochen werden soll.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Methoden

| Methode | Beschreibung |
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
boolesch
### close() {#close--}
```
public void close()
```




