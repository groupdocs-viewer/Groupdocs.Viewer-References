---
title: "CancellationToken"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Übermittelt die Benachrichtigung, dass ein Vorgang abgebrochen werden sollte."
type: docs
weight: 10
url: /de/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Übermittelt die Benachrichtigung, dass ein Vorgang abgebrochen werden sollte.

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [NONE](#NONE) | Ein Token, das niemals abgebrochen wird. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Wirft CancellationException, wenn ein Abbruch angefordert wurde. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Ein Token, das niemals abgebrochen wird.


### isCancellationRequested() {#isCancellationRequested--}
```
public boolean isCancellationRequested()
```




**Returns:**
boolesch
### throwIfCancellationRequested() {#throwIfCancellationRequested--}
```
public void throwIfCancellationRequested()
```


Wirft CancellationException, wenn ein Abbruch angefordert wurde.


