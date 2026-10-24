---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer for Java API 参考"
description: 
type: docs
weight: 20
url: /zh/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSent()](#getSent--) | 返回电子邮件消息的原始 "Sent" 日期时间。 |
|
|  | [getSubject()](#getSubject--) | 返回 "Subject" 行。 |
|
|  | [getFrom()](#getFrom--) | 返回电子邮件消息的 "From" 电子邮件地址，作为字符串。 |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


返回电子邮件消息的原始 "Sent" 日期时间。


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


返回 "Subject" 行。


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


返回电子邮件消息的 "From" 电子邮件地址，作为字符串。


**Returns:**
java.lang.String
