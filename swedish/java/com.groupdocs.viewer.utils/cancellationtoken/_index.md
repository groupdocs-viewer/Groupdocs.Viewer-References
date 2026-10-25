---
title: "CancellationToken"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Sprider en avisering om att en operation bör avbrytas."
type: docs
weight: 10
url: /sv/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Sprider en avisering om att en operation bör avbrytas.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [NONE](#NONE) | En token som aldrig avbryts. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Kastar CancellationException om avbrott har begärts. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


En token som aldrig avbryts.


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


Kastar CancellationException om avbrott har begärts.


