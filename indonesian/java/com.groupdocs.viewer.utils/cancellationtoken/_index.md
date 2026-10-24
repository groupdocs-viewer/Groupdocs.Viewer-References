---
title: "CancellationToken"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyebarkan notifikasi bahwa operasi harus dibatalkan."
type: docs
weight: 10
url: /id/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Menyebarkan notifikasi bahwa operasi harus dibatalkan.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [NONE](#NONE) | Token yang tidak pernah dibatalkan. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Melempar CancellationException jika pembatalan telah diminta. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Token yang tidak pernah dibatalkan.


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


Melempar CancellationException jika pembatalan telah diminta.


