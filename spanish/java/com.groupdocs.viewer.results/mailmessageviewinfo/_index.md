---
title: "MailMessageViewInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: 
type: docs
weight: 20
url: /es/java/com.groupdocs.viewer.results/mailmessageviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface MailMessageViewInfo extends ViewInfo
```
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSent()](#getSent--) | Devuelve la fecha y hora original de "Enviado" del mensaje de correo electrónico. |
|
|  | [getSubject()](#getSubject--) | Devuelve una línea de "Asunto". |
|
|  | [getFrom()](#getFrom--) | Devuelve la dirección de correo "De" del mensaje de correo electrónico como una cadena. |
|
### getSent() {#getSent--}
```
public abstract Date getSent()
```


Devuelve la fecha y hora original de "Enviado" del mensaje de correo electrónico.


**Returns:**
java.util.Date
### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Devuelve una línea de "Asunto".


**Returns:**
java.lang.String
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```


Devuelve la dirección de correo "De" del mensaje de correo electrónico como una cadena.


**Returns:**
java.lang.String
