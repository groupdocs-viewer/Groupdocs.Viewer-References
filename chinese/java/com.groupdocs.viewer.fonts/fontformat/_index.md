---
title: "字体格式"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示 UsedFontInfo 类中可能出现的所有字体格式。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

表示所有可能出现在 UsedFontInfo 类中的字体格式。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Unknown](#Unknown) | 未知或无效的字体格式。 |
|
|  | [TrueType](#TrueType) | TrueType 字体格式（TTF）。 |
|
|  | [OpenType](#OpenType) | OpenType 字体格式（OTF）。 |
|
|  | [TrueTypeCollection](#TrueTypeCollection) | TrueType Collection 字体格式（TTC）。 |
|
|  | [EmbeddedOpenType](#EmbeddedOpenType) | 嵌入式 OpenType 字体格式（EOT）。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [toString(int format)](#toString-int-) | 将格式值转换为人类可读的字符串。 |
|
### Unknown {#Unknown}
```
public static final int Unknown
```


未知或无效的字体格式。


### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType 字体格式（TTF）。


### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType 字体格式（OTF）。


### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType Collection 字体格式（TTC）。


### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


嵌入式 OpenType 字体格式（EOT）。


### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


将格式值转换为人类可读的字符串。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 格式 | int | 字体格式值 |
|

**Returns:**
java.lang.String - 字体格式的字符串表示

