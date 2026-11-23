---
title: "CancellationToken"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Diffuse une notification indiquant qu'une opération doit être annulée."
type: docs
weight: 10
url: /fr/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Diffuse une notification indiquant qu'une opération doit être annulée.

## Champs

| Champ | Description |
| --- | --- |
|  | [NONE](#NONE) | Un jeton qui n'est jamais annulé. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Lance CancellationException si une annulation a été demandée. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Un jeton qui n'est jamais annulé.


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


Lance CancellationException si une annulation a été demandée.


