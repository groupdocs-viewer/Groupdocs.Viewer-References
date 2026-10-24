---
title: "CancellationToken"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Διαδίδει ειδοποίηση ότι μια λειτουργία πρέπει να ακυρωθεί."
type: docs
weight: 10
url: /el/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Διαδίδει ειδοποίηση ότι μια λειτουργία πρέπει να ακυρωθεί.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [NONE](#NONE) | Ένα διακριτικό που δεν ακυρώνεται ποτέ. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Ρίχνει CancellationException εάν έχει ζητηθεί ακύρωση. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Ένα διακριτικό που δεν ακυρώνεται ποτέ.


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


Ρίχνει CancellationException εάν έχει ζητηθεί ακύρωση.


