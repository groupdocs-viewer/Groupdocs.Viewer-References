---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer för Java API-referens"
description: 
type: docs
weight: 20
url: /sv/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSent()](#getSent--) | Returnerar det ursprungliga "Sent" datum- och tidsvärdet för e-postmeddelandet. |
|
|  | [getSubject()](#getSubject--) | Returnerar en "Subject"-rad. |
|
|  | [getFrom()](#getFrom--) | Returnerar en "From" e-postadress för e-postmeddelandet som en sträng. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Returnerar det ursprungliga "Sent" datum- och tidsvärdet för e-postmeddelandet.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Returnerar en "Subject"-rad.


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Returnerar en "From" e-postadress för e-postmeddelandet som en sträng.


**Returns:**
java.lang.String
