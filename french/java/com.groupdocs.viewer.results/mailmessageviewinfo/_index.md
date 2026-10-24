---
title: "MailMessageViewInfo"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: 
type: docs
weight: 20
url: /fr/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSent()](#getSent--) | Renvoie la date et l'heure d'origine "Sent" du message électronique. |
|
|  | [getSubject()](#getSubject--) | Renvoie une ligne "Subject". |
|
|  | [getFrom()](#getFrom--) | Renvoie une adresse e‑mail "From" du message électronique sous forme de chaîne. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Renvoie la date et l'heure d'origine "Sent" du message électronique.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Renvoie une ligne "Subject".


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Renvoie une adresse e‑mail "From" du message électronique sous forme de chaîne.


**Returns:**
java.lang.String
