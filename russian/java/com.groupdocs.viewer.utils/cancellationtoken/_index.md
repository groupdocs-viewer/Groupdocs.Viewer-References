---
title: "CancellationToken"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Распространяет уведомление о том, что операция должна быть отменена."
type: docs
weight: 10
url: /ru/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

Распространяет уведомление о том, что операция должна быть отменена.

## Поля

| Поле | Описание |
| --- | --- |
|  | [NONE](#NONE) | Токен, который никогда не отменяется. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | Выбрасывает CancellationException, если была запрошена отмена. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


Токен, который никогда не отменяется.


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


Выбрасывает CancellationException, если была запрошена отмена.


