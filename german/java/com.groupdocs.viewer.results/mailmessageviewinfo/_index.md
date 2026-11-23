---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: 
type: docs
weight: 20
url: /de/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSent()](#getSent--) | Gibt das ursprüngliche "Gesendet"‑Datum‑Uhrzeit der E‑Mail‑Nachricht zurück. |
|
|  | [getSubject()](#getSubject--) | Gibt eine "Subject"-Zeile zurück. |
|
|  | [getFrom()](#getFrom--) | Gibt die "From"-E-Mail-Adresse der E-Mail-Nachricht als Zeichenkette zurück. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Gibt das ursprüngliche "Gesendet"‑Datum‑Uhrzeit der E‑Mail‑Nachricht zurück.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Gibt eine "Subject"-Zeile zurück.


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Gibt die "From"-E-Mail-Adresse der E-Mail-Nachricht als Zeichenkette zurück.


**Returns:**
java.lang.String
