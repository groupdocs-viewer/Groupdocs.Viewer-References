---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: 
type: docs
weight: 20
url: /ar/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSent()](#getSent--) | يعيد تاريخ ووقت "الإرسال" الأصلي لرسالة البريد الإلكتروني. |
|
|  | [getSubject()](#getSubject--) | يعيد سطر "الموضوع". |
|
|  | [getFrom()](#getFrom--) | يعيد عنوان البريد الإلكتروني "من" لرسالة البريد الإلكتروني كسلسلة. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


يعيد تاريخ ووقت "الإرسال" الأصلي لرسالة البريد الإلكتروني.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


يعيد سطر "الموضوع".


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


يعيد عنوان البريد الإلكتروني "من" لرسالة البريد الإلكتروني كسلسلة.


**Returns:**
java.lang.String
