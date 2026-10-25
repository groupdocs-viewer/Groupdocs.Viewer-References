---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: 
type: docs
weight: 20
url: /tr/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSent()](#getSent--) | E-posta mesajının orijinal "Gönderildi" tarih ve saatini döndürür. |
|
|  | [getSubject()](#getSubject--) | Bir "Konu" satırını döndürür. |
|
|  | [getFrom()](#getFrom--) | E-posta mesajının "From" adresini bir dize olarak döndürür. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


E-posta mesajının orijinal "Gönderildi" tarih ve saatini döndürür.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Bir "Konu" satırını döndürür.


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


E-posta mesajının "From" adresini bir dize olarak döndürür.


**Returns:**
java.lang.String
