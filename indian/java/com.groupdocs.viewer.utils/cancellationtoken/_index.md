---
title: "CancellationToken"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "ऑपरेशन को रद्द किया जाना चाहिए, इसकी सूचना प्रसारित करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

ऑपरेशन को रद्द किया जाना चाहिए, इसकी सूचना प्रसारित करता है।

## Fields

| Field | विवरण |
| --- | --- |
|  | [NONE](#NONE) | एक टोकन जो कभी रद्द नहीं होता। |
|
## Methods

| Method | विवरण |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | यदि रद्दीकरण का अनुरोध किया गया हो तो CancellationException फेंकता है। |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


एक टोकन जो कभी रद्द नहीं होता।


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


यदि रद्दीकरण का अनुरोध किया गया हो तो CancellationException फेंकता है।


