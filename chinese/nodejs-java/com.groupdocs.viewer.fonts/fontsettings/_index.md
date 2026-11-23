---
title: "FontSettings"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供用于查找 TrueType 字体来源的方法。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

提供用于查找 TrueType 字体来源的方法。

FontSettings 类用于指定和管理用于定位 TrueType 字体的来源。它提供了向 GroupDocs.Viewer API 添加和重置字体来源的方法。

示例用法：

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | 设置在渲染文档时查找 TrueType 字体的来源。 |
| [resetFontSources()](#resetFontSources--) | 重置之前已设置的字体来源。 |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


设置在渲染文档时查找 TrueType 字体的来源。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | 要设置的字体来源。 |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


重置之前已设置的字体来源。

