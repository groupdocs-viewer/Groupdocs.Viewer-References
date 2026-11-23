---
title: "FontStyles"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示文档中使用的字体的四种可能样式：Regular、Bold、Italic 或 Bold Italic。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

表示文档中使用的四种可能的字体样式：Regular、Bold、Italic 或 Bold Italic。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | 从粗体/斜体标志创建一个 FontStyles 实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [toString(int style)](#toString-int-) | 将样式值转换为人类可读的字符串。 |
| [getName()](#getName--) | 返回此字体样式的可读名称。 |
| [isBold()](#isBold--) | 如果设置了粗体位，则返回 true。 |
| [isItalic()](#isItalic--) | 如果设置了斜体位，则返回 true。 |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | 并集 (C\# 运算符 +) |
| [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | 差集 (C\# 运算符 -) |
| [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | 将字体样式名称解析为 FontStyles。 |
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


从粗体/斜体标志创建一个 FontStyles 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isBold | boolean |  |
| isItalic | boolean |  |

### Regular {#Regular}
```
public static final int Regular
```


### Bold {#Bold}
```
public static final int Bold
```


### Italic {#Italic}
```
public static final int Italic
```


### BoldItalic {#BoldItalic}
```
public static final int BoldItalic
```


### REGULAR {#REGULAR}
```
public static final FontStyles REGULAR
```


### BOLD {#BOLD}
```
public static final FontStyles BOLD
```


### ITALIC {#ITALIC}
```
public static final FontStyles ITALIC
```


### BOLD_ITALIC {#BOLD-ITALIC}
```
public static final FontStyles BOLD_ITALIC
```


### toString(int style) {#toString-int-}
```
public static String toString(int style)
```


将样式值转换为人类可读的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 样式 | int | 字体样式值 |

**Returns:**
java.lang.String - 字体样式的字符串表示
### getName() {#getName--}
```
public String getName()
```


返回此字体样式的可读名称。

**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


如果设置了粗体位，则返回 true。

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


如果设置了斜体位，则返回 true。

**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### combine(FontStyles first, FontStyles second) {#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles combine(FontStyles first, FontStyles second)
```


并集 (C\# 运算符 +)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 第一个 | com.groupdocs.viewer.fonts.FontStyles |  |
| 第二个 | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


差集 (C\# 运算符 -)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 被减数 | com.groupdocs.viewer.fonts.FontStyles |  |
| 减数 | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


将字体样式名称解析为 FontStyles。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 样式 | java.lang.String |  |
| 已解析 | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - 成功时为 true，失败时为 false。
