---
title: "CancellationToken"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Propaga una notificación de que una operación debe cancelarse."
type: docs
weight: 10
url: /es/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Propaga una notificación de que una operación debe cancelarse.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [NONE](#NONE) | Un token que nunca se cancela. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Lanza CancellationException si se ha solicitado la cancelación. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Un token que nunca se cancela.


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


Lanza CancellationException si se ha solicitado la cancelación.


