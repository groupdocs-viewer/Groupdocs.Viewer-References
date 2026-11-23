---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供用于渲染邮件存储 Lotus Notes MBox 数据文件的选项。"
type: docs
weight: 19
url: /zh/java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

提供用于渲染邮件存储（Lotus Notes，MBox）数据文件的选项。


MailStorageOptions 类封装了可用于的各种设置和参数。
控制在 GroupDocs.Viewer 组件中渲染邮件存储数据文件（如 Lotus Notes 或 MBox）。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options)。


示例用法：

````

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getTextFilter()](#getTextFilter--) | 获取用于过滤消息的关键字。 |
|
|  | [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | 设置用于过滤消息的关键字。 |
|
|  | [getAddressFilter()](#getAddressFilter--) | 获取用于按发送者或收件人过滤消息的电子邮件地址。 |
|
|  | [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | 设置用于按发送者或收件人过滤消息的电子邮件地址。 |
|
|  | [getMaxItems()](#getMaxItems--) | 获取要渲染的消息或项目的最大数量。 |
|
|  | [setMaxItems(int maxItems)](#setMaxItems-int-) | 设置要渲染的消息或项目的最大数量。 |
|
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


获取用于过滤消息的关键字。


使用此属性渲染主题或正文中包含特定文本的所有消息。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages)。


**Returns:**
java.lang.String - 用于过滤消息的关键字。

### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


设置用于过滤消息的关键字。


使用此属性渲染主题或正文中包含特定文本的所有消息。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | textFilter | java.lang.String | 用于过滤消息的关键字。 |
|

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


获取用于按发送者或收件人过滤消息的电子邮件地址。


使用此属性渲染发送者\u2019s 或收件人\u2019s 地址中包含特定文本的所有消息。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages)。


**Returns:**
java.lang.String - 用于过滤消息的电子邮件地址。

### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


设置用于按发送者或收件人过滤消息的电子邮件地址。


使用此属性渲染发送者\u2019s 或收件人\u2019s 地址中包含特定文本的所有消息。有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | addressFilter | java.lang.String | 用于过滤消息的电子邮件地址。 |
|

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


获取要渲染的消息或项目的最大数量。


Lotus Notes 数据文件可能很大，检索所有消息可能需要相当长的时间。
此设置限制渲染的消息或项目的最大数量。


***Note:** The default value is 0, which means all messages will be rendered.*
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render)。


**Returns:**
int - 要渲染的消息或项目的最大数量。

### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


设置要渲染的消息或项目的最大数量。


Lotus Notes 数据文件可能很大，检索所有消息可能需要相当长的时间。
此设置限制渲染的消息或项目的最大数量。


***Note:** The default value is 0, which means all messages will be rendered.*
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxItems | int | 要渲染的消息或项目的最大数量。 |
|

