---
title: "MailMessageViewInfo"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: 
type: docs
weight: 20
url: /ru/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Методы

| Метод | Описание |
| --- | --- |
|  | [getSent()](#getSent--) | Возвращает оригинальную дату и время \"Sent\" сообщения электронной почты. |
|
|  | [getSubject()](#getSubject--) | Возвращает строку \"Subject\". |
|
|  | [getFrom()](#getFrom--) | Возвращает адрес электронной почты \"From\" сообщения в виде строки. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Возвращает оригинальную дату и время \"Sent\" сообщения электронной почты.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Возвращает строку \"Subject\".


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Возвращает адрес электронной почты \"From\" сообщения в виде строки.


**Returns:**
java.lang.String
