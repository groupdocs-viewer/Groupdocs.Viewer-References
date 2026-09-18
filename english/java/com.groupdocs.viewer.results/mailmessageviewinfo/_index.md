---
title: MailMessageViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: 
type: docs
weight: 20
url: /java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Methods

| Method | Description |
| --- | --- |
| [getSent()](#getSent--) | Returns original "Sent" datetime of the email message.
 |
| [getSubject()](#getSubject--) | Returns a "Subject" line.
 |
| [getFrom()](#getFrom--) | Returns a "From" email address of the email message as a string.
 |
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Returns original "Sent" datetime of the email message.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Returns a "Subject" line.


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Returns a "From" email address of the email message as a string.


**Returns:**
java.lang.String
