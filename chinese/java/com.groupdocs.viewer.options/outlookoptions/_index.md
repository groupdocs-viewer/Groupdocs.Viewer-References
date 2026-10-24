---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供用于渲染 Outlook 数据文件的选项。"
type: docs
weight: 20
url: /zh/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

提供用于渲染 Outlook 数据文件的选项。


OutlookOptions 类封装了可用于的各种设置和参数
以控制在 GroupDocs.Viewer 组件中渲染 Outlook 数据文件（如 PST 或 OST 文件）。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options)。


示例用法：

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFolder()](#getFolder--) | 获取要渲染的文件夹名称。 |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | 设置要渲染的文件夹名称。 |
|
|  | [getTextFilter()](#getTextFilter--) | 获取用于过滤消息的关键字。 |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | 获取用于过滤消息的关键字。 |
|
|  | [getAddressFilter()](#getAddressFilter--) | 获取用于按发送者或收件人过滤消息的电子邮件地址。 |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | 设置用于按发送者或收件人过滤消息的电子邮件地址。 |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | 获取可以从单个文件夹渲染的消息或项目的最大数量。 |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | 设置可以从单个文件夹渲染的消息或项目的最大数量。 |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


获取要渲染的文件夹名称。
要渲染的文件夹名称（例如，收件箱、已发送邮件或已删除项目）。


在渲染 Outlook 数据文件时，GroupDocs.Viewer 会渲染文件中包含的所有文件夹的消息（包括嵌套文件夹）。使用此属性可渲染特定文件夹中的项目。
代码示例请参见此[文档](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder)。


**Returns:**
java.lang.String - 要渲染的文件夹名称。

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


设置要渲染的文件夹名称。
要渲染的文件夹名称（例如，收件箱、已发送邮件或已删除项目）。


在渲染 Outlook 数据文件时，GroupDocs.Viewer 会渲染文件中包含的所有文件夹的消息（包括嵌套文件夹）。使用此属性可渲染特定文件夹中的项目。
代码示例请参见此[文档](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 要渲染的文件夹名称。 |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


获取用于过滤消息的关键字。


使用此属性渲染所有主题或正文中包含特定文本的消息。代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages)。


**Returns:**
java.lang.String - 关键字。

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


获取用于过滤消息的关键字。


使用此属性渲染所有主题或正文中包含特定文本的消息。代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 关键字。 |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


获取用于按发送者或收件人过滤消息的电子邮件地址。


使用此属性渲染所有发件人\ufffd或收件人\ufffd地址中包含特定文本的消息。代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages)。


**Returns:**
java.lang.String - 用于过滤消息的电子邮件地址。

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


设置用于按发送者或收件人过滤消息的电子邮件地址。


使用此属性渲染所有发件人\ufffd或收件人\ufffd地址中包含特定文本的消息。代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 用于过滤消息的电子邮件地址。 |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


获取可以从单个文件夹渲染的消息或项目的最大数量。


Outlook 数据文件可能很大，检索所有消息可能需要相当长的时间。
此设置限制渲染的消息或项目（如联系人和任务）的最大数量。
默认值为 50。将该值设为 0 可渲染所有消息。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render)。


**Returns:**
int - 可以从单个文件夹渲染的消息或项目的最大数量。

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


设置可以从单个文件夹渲染的消息或项目的最大数量。


Outlook 数据文件可能很大，检索所有消息可能需要相当长的时间。
此设置限制渲染的消息或项目（如联系人和任务）的最大数量。
默认值为 50。将该值设为 0 可渲染所有消息。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 可以从单个文件夹渲染的消息或项目的最大数量。 |
|

