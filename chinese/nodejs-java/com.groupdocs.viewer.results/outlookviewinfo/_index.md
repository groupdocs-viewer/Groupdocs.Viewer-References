---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示 Outlook 数据文件的视图信息。"
type: docs
weight: 20
url: /zh/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

表示 Outlook 数据文件的视图信息。

OutlookViewInfo 接口定义了在 GroupDocs.Viewer 组件中访问和操作 Outlook 数据文件视图信息的契约。它提供了检索诸如文件夹列表等信息的方法以及其他属性。

示例用法：

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFolders()](#getFolders--) | 检索 Outlook 数据文件中包含的文件夹列表。 |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | 设置 Outlook 数据文件中包含的文件夹列表。 |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


检索 Outlook 数据文件中包含的文件夹列表。

**Returns:**
java.util.List<java.lang.String> - 文件夹列表。
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


设置 Outlook 数据文件中包含的文件夹列表。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 列表 | java.util.List<java.lang.String> | 文件夹列表。 |

