---
title: "CancellationTokenSource"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Σήματα σε ένα  ότι μια λειτουργία πρέπει να ακυρωθεί."
type: docs
weight: 11
url: /el/java/com.groupdocs.viewer.utils/cancellationtokensource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public final class CancellationTokenSource implements AutoCloseable
```

Σήματα σε ένα [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) ότι μια λειτουργία πρέπει να ακυρωθεί.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CancellationTokenSource()](#CancellationTokenSource--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
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




