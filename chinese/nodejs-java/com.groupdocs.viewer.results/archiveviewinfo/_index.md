---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示归档文件的视图信息。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

表示归档文件的视图信息。

ArchiveViewInfo 接口定义了在 GroupDocs.Viewer 组件中检索特定归档文件的视图信息的契约。它提供了访问诸如页数、尺寸以及归档文件特定渲染选项等详细信息的方法。

示例用法：

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFolders()](#getFolders--) | 检索归档文件中包含的文件夹列表。 |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | 设置归档文件中包含的文件夹列表。 |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


检索归档文件中包含的文件夹列表。

**Returns:**
java.util.List<java.lang.String> - 文件夹列表。
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


设置归档文件中包含的文件夹列表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件夹 | java.util.List<java.lang.String> | 文件夹列表。 |

