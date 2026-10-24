---
title: "Permissions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Definiert PDF‑Dokumentenberechtigungen."
type: docs
weight: 24
url: /de/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Definiert PDF‑Dokumentenberechtigungen.


Die Permissions‑Klasse stellt Konstanten bereit, die verschiedene Berechtigungen darstellen
die auf ein PDF-Dokument in der GroupDocs.Viewer‑Komponente angewendet werden können.
Diese Berechtigungen steuern die Aktionen, die am PDF-Dokument ausgeführt werden können,
wie Drucken, Text kopieren, Anmerkungen ändern und mehr.


Beispielverwendung:

````

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | Drucken, Änderungen und Datenextraktion erlauben. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | Drucken verweigern. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | Inhaltsänderungen, Ausfüllen von Formularen, Hinzufügen oder Ändern von Anmerkungen verweigern. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Text- und Grafikaus extraction verweigern. |
|
|  | [DENY_ALL](#DENY-ALL) | Drucken, Änderungen und Datenextraktion verweigern. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Drucken, Änderungen und Datenextraktion erlauben.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Drucken verweigern.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Inhaltsänderungen, Ausfüllen von Formularen, Hinzufügen oder Ändern von Anmerkungen verweigern.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Text- und Grafikaus extraction verweigern.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Drucken, Änderungen und Datenextraktion verweigern.


