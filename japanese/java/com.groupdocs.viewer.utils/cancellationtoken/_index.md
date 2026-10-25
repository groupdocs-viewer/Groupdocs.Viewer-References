---
title: "CancellationToken"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "操作がキャンセルされるべきであることを通知します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.viewer.utils/cancellationtoken/
---
**Inheritance:**
java.lang.Object
```
public final class CancellationToken
```

操作がキャンセルされるべきであることを通知します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NONE](#NONE) | 決してキャンセルされないトークンです。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isCancellationRequested()](#isCancellationRequested--) |  |
|  | [throwIfCancellationRequested()](#throwIfCancellationRequested--) | キャンセルが要求された場合、CancellationException をスローします。 |
|
### NONE {#NONE}
```
public static final CancellationToken NONE
```


決してキャンセルされないトークンです。


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


キャンセルが要求された場合、CancellationException をスローします。


