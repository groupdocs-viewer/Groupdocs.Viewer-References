---
title: "CancellationToken"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Propagereert een melding dat een bewerking geannuleerd moet worden."
type: docs
weight: 10
url: /nl/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Propagereert een melding dat een bewerking geannuleerd moet worden.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [NONE](#NONE) | Een token dat nooit wordt geannuleerd. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Gooit CancellationException als annulering is aangevraagd. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Een token dat nooit wordt geannuleerd.


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


Gooit CancellationException als annulering is aangevraagd.


