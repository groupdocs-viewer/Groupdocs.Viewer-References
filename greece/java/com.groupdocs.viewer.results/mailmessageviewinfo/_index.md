---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer για Java API Reference"
description: 
type: docs
weight: 20
url: /el/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getSent()](#getSent--) | Επιστρέφει την αρχική ημερομηνία/ώρα "Sent" του μηνύματος ηλεκτρονικού ταχυδρομείου. |
|
|  | [getSubject()](#getSubject--) | Επιστρέφει μια γραμμή "Subject". |
|
|  | [getFrom()](#getFrom--) | Επιστρέφει τη διεύθυνση ηλεκτρονικού ταχυδρομείου "From" του μηνύματος ως συμβολοσειρά. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Επιστρέφει την αρχική ημερομηνία/ώρα "Sent" του μηνύματος ηλεκτρονικού ταχυδρομείου.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Επιστρέφει μια γραμμή "Subject".


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Επιστρέφει τη διεύθυνση ηλεκτρονικού ταχυδρομείου "From" του μηνύματος ως συμβολοσειρά.


**Returns:**
java.lang.String
