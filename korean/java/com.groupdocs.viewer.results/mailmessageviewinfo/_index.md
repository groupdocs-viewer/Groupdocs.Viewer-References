---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: 
type: docs
weight: 20
url: /ko/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSent()](#getSent--) | 이메일 메시지의 원본 "Sent" 날짜 및 시간을 반환합니다. |
|
|  | [getSubject()](#getSubject--) | "Subject" 라인을 반환합니다. |
|
|  | [getFrom()](#getFrom--) | 이메일 메시지의 "From" 이메일 주소를 문자열로 반환합니다. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


이메일 메시지의 원본 "Sent" 날짜 및 시간을 반환합니다.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


"Subject" 라인을 반환합니다.


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


이메일 메시지의 "From" 이메일 주소를 문자열로 반환합니다.


**Returns:**
java.lang.String
