---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示包含 TrueType 字体的文件夹。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

表示包含 TrueType 字体的文件夹。

FolderFontSource 类用于指定包含 TrueType 字体的文件夹位置。它允许 GroupDocs.Viewer API 访问指定文件夹中存储的字体，以用于文档渲染。

示例用法：

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | 初始化 FolderFontSource 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | 确定两个 FolderFontSource 对象是否相同。 |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | 确定两个 FolderFontSource 对象是否不相同。 |
| [getFolderPath()](#getFolderPath--) | 获取包含 TrueType 字体的文件夹路径。 |
| [getSearchOption()](#getSearchOption--) | 获取搜索选项，指定是仅搜索当前文件夹，还是搜索当前文件夹及所有子文件夹。 |
| [isRecursive()](#isRecursive--) | 检查是否递归搜索字体。 |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | 确定当前 FolderFontSource 是否与指定的 FolderFontSource 对象相同。 |
| [equals(Object o)](#equals-java.lang.Object-) | 确定当前 FolderFontSource 是否与指定的对象相同。 |
| [hashCode()](#hashCode--) | 返回当前 FolderFontSource 对象的哈希码。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


初始化 FolderFontSource 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folderPath | java.lang.String | 包含 TrueType 字体的文件夹路径。 |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | 指定是搜索当前文件夹，还是搜索当前文件夹及所有子文件夹。 |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


确定两个 FolderFontSource 对象是否相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 左侧 FolderFontSource 对象。 |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 右侧 FolderFontSource 对象。 |

**Returns:**
布尔值 - 如果两个 FolderFontSource 对象相同则为 true；否则为 false。
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


确定两个 FolderFontSource 对象是否不相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 左侧 FolderFontSource 对象。 |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 右侧 FolderFontSource 对象。 |

**Returns:**
布尔值 - 如果两个 FolderFontSource 对象不相同则为 true；否则为 false。
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


获取包含 TrueType 字体的文件夹路径。

**Returns:**
java.lang.String - 包含 TrueType 字体的文件夹路径。
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


获取搜索选项，指定是仅搜索当前文件夹，还是搜索当前文件夹及所有子文件夹。

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


检查是否递归搜索字体。

**Returns:**
boolean -  true  如果递归搜索字体，则为 true；否则为 false。
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


确定当前 FolderFontSource 是否与指定的 FolderFontSource 对象相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | 用于与当前  FolderFontSource  对象比较的对象。 |

**Returns:**
boolean -  true  如果两个  FolderFontSource  对象相同；否则为 false
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


确定当前 FolderFontSource 是否与指定的对象相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 用于与当前  FolderFontSource  对象比较的对象。 |

**Returns:**
boolean -  true  如果  obj  参数的类型是  FolderFontSource  并且与当前  FolderFontSource  对象相同；否则为 false
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回当前 FolderFontSource 对象的哈希码。

**Returns:**
int - 当前  FolderFontSource  对象的哈希码。
### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 表示当前对象的字符串。
