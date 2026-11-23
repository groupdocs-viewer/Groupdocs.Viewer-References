---
title: "CancellationToken"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "ينشر إشعارًا بأن العملية يجب إلغاؤها."
type: docs
weight: 10
url: /ar/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

ينشر إشعارًا بأن العملية يجب إلغاؤها.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [NONE](#NONE) | رمز لا يتم إلغاؤه أبدًا. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | يرمي استثناء CancellationException إذا تم طلب الإلغاء. |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


رمز لا يتم إلغاؤه أبدًا.


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


يرمي استثناء CancellationException إذا تم طلب الإلغاء.


