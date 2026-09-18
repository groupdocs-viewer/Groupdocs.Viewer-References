---
title: CancellationToken
second_title: GroupDocs.Viewer for Java API Reference
description: Propagates notification that an operation should be canceled.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Propagates notification that an operation should be canceled.

## Fields

| Field | Description |
| --- | --- |
| [NONE](#NONE) | A token that is never canceled.
 |
## Methods

| Method | Description |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
| [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Throws CancellationException if cancellation has been requested.
 |
### NONE {#NONE}
```
public static final CancellationToken NONE
```


A token that is never canceled.


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


Throws CancellationException if cancellation has been requested.


