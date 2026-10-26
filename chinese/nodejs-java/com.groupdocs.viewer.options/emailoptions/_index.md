---
title: "EmailOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供用于渲染电子邮件消息的选项。"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

提供用于渲染电子邮件消息的选项。

EmailOptions 类封装了各种设置和参数，可用于控制 GroupDocs.Viewer 组件中电子邮件消息的渲染。

有关详细信息，请参阅[文档][].

示例用法：

```

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | 初始化 EmailOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | 获取日期和时间值的时间格式。 |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | 获取日期和时间值的时间格式。 |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | 获取消息的时区偏移量。 |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | 获取消息的时区分钟偏移量。 |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | 获取消息的时区偏移量。 |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | 获取消息的时区偏移分钟。 |
| [getPageSize()](#getPageSize--) | 获取输出页面的大小。 |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 获取输出页面的大小。 |
| [getFieldTextMap()](#getFieldTextMap--) | 检索电子邮件消息字段与其文本表示之间的映射。 |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | 设置电子邮件消息字段与其文本表示之间的映射。 |
| [equals(Object o)](#equals-java.lang.Object-) | 重写 Object 类的 equals() 方法。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | 重写 Object 类的 toString() 方法。 |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


初始化 EmailOptions 类的新实例。此构造函数用于使用默认设置创建 EmailOptions 类的新实例。

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


获取日期和时间值的时间格式。

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.lang.String - 日期和时间值的时间格式。
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


获取日期和时间值的时间格式。

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | 日期和时间值的时间格式。 |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


获取消息的时区偏移量。

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.util.TimeZone - 时区偏移量。
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


获取消息的时区分钟偏移量。

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
int - 时区偏移量。
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


获取消息的时区偏移量。

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | 时区偏移量。 |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


获取消息的时区偏移分钟。

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| offsetMinutes | int | 时区偏移量。 |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


获取输出页面的大小。

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


获取输出页面的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 页面大小。 |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


检索电子邮件消息字段与其文本表示之间的映射。

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - 电子邮件消息字段与其文本表示之间的映射。
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


设置电子邮件消息字段与其文本表示之间的映射。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | 电子邮件消息字段与其文本表示之间的映射。 |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


重写 Object 类的 equals() 方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 要比较的对象。 |

**Returns:**
boolean - 如果对象相等则为 true，否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


计算此对象的哈希码值。哈希码基于对象的内部状态，并用于哈希映射和哈希集合等基于哈希的数据结构。

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - 此对象的哈希码值。
### toString() {#toString--}
```
public String toString()
```


重写 Object 类的 toString() 方法。

**Returns:**
java.lang.String - 对象的字符串表示形式。
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


返回此对象的字符串表示形式。

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 样式 | org.apache.commons.lang3.builder.ToStringStyle | 用于生成字符串表示的 ToStringStyle。 |

**Returns:**
java.lang.String - 使用指定的 ToStringStyle 对此对象进行字符串表示。
