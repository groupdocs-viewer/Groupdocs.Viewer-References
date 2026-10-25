---
title: "CancellationToken"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Bir işlemin iptal edilmesi gerektiğine dair bildirimi yayar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Bir işlemin iptal edilmesi gerektiğine dair bildirimi yayar.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [NONE](#NONE) | Asla iptal edilmeyen bir token. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | İptal talep edilmişse CancellationException fırlatır. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Asla iptal edilmeyen bir token.


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


İptal talep edilmişse CancellationException fırlatır.


