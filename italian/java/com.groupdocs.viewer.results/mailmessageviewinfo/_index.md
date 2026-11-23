---
title: "MailMessageViewInfo"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: 
type: docs
weight: 20
url: /it/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSent()](#getSent--) | Restituisce la data e ora originale "Sent" del messaggio email. |
|
|  | [getSubject()](#getSubject--) | Restituisce una riga "Subject". |
|
|  | [getFrom()](#getFrom--) | Restituisce l'indirizzo email "From" del messaggio email come stringa. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Restituisce la data e ora originale "Sent" del messaggio email.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Restituisce una riga "Subject".


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Restituisce l'indirizzo email "From" del messaggio email come stringa.


**Returns:**
java.lang.String
