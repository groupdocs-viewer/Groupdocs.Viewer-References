---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示 Lotus Notes 数据库存储的视图信息。"
type: docs
weight: 19
url: /zh/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

表示 Lotus Notes 数据库存储的视图信息。

LotusNotesViewInfo 接口定义了在 GroupDocs.Viewer 组件中访问和操作 Lotus Notes 数据库存储视图信息的契约。它提供了检索诸如笔记计数等信息的方法以及其他属性。

示例用法：

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | 检索存储中的笔记计数。 |
| [setNotesCount(int count)](#setNotesCount-int-) | 设置存储中的笔记计数。 |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


检索存储中的笔记计数。

**Returns:**
int - 存储中的笔记计数。
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


设置存储中的笔记计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| count | int | 存储中的笔记计数。 |

