---
title: "KnownColors"
second_title: "GroupDocs.Viewer for Java API 参考"
description: 
type: docs
weight: 10
url: /zh/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | 尝试通过字符串名称查找颜色。 |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | 尝试通过其 RGB 值查找颜色名称。 |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


尝试通过字符串名称查找颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 关键字 | java.lang.String | 颜色名称。 |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | 找到的颜色的结果容器，若失败则为 CssLevel1.Black。 |
|

**Returns:**
布尔值 - 若成功通过名称找到颜色则为 True，否则为 false。

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


尝试通过其 RGB 值查找颜色名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | 颜色实例。 |
|
|  | 名称 | java.lang.String[] | 找到的颜色名称的结果容器，若失败则为 null。 |
|

**Returns:**
布尔值 - 若成功为给定颜色找到名称则为 True，否则为 false。

