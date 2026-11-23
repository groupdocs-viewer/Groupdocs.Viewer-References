---
title: "CancellationToken"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Propaga la notifica che un'operazione dovrebbe essere annullata."
type: docs
weight: 10
url: /it/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Propaga la notifica che un'operazione dovrebbe essere annullata.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [NONE](#NONE) | Un token che non viene mai annullato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Lancia CancellationException se è stata richiesta l'annullamento. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Un token che non viene mai annullato.


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


Lancia CancellationException se è stata richiesta l'annullamento.


