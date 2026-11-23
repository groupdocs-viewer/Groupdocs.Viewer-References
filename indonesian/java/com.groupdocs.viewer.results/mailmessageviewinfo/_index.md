---
title: "MailMessageViewInfo"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: 
type: docs
weight: 20
url: /id/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSent()](#getSent--) | Mengembalikan tanggal dan waktu "Sent" asli dari pesan email. |
|
|  | [getSubject()](#getSubject--) | Mengembalikan baris "Subject". |
|
|  | [getFrom()](#getFrom--) | Mengembalikan alamat email "From" dari pesan email sebagai string. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Mengembalikan tanggal dan waktu "Sent" asli dari pesan email.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Mengembalikan baris "Subject".


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Mengembalikan alamat email "From" dari pesan email sebagai string.


**Returns:**
java.lang.String
