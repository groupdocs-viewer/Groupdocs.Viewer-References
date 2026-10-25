---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: 
type: docs
weight: 20
url: /ja/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSent()](#getSent--) | メールメッセージの元の "Sent" 日時を返します。 |
|
|  | [getSubject()](#getSubject--) | "Subject" 行を返します。 |
|
|  | [getFrom()](#getFrom--) | メールメッセージの "From" アドレスを文字列として返します。 |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


メールメッセージの元の "Sent" 日時を返します。


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


"Subject" 行を返します。


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


メールメッセージの "From" アドレスを文字列として返します。


**Returns:**
java.lang.String
