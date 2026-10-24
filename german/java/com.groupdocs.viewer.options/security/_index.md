---
title: "Security"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt PDF‑Dokumentensicherheitsoptionen bereit."
type: docs
weight: 29
url: /de/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Stellt PDF‑Dokumentensicherheitsoptionen bereit.


Die Security‑Klasse kapselt verschiedene Einstellungen und Optionen, die verwendet werden können, um Sicherheitsmaßnahmen anzuwenden
auf ein PDF‑Dokument in der GroupDocs.Viewer‑Komponente. Diese Optionen umfassen Passwortschutz,
Berechtigungen und mehr.
Weitere Details finden Sie in der [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


Beispielverwendung:

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

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
|  | [Security()](#Security--) | Initialisiert eine neue Instanz von |
Security
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Ermittelt das Passwort, das zum Öffnen des PDF-Dokuments erforderlich ist. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Legt das Passwort fest, das zum Öffnen des PDF-Dokuments erforderlich ist. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Ermittelt das Passwort, das zum Ändern der Berechtigungseinstellungen erforderlich ist. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Legt das Passwort fest, das zum Ändern der Berechtigungseinstellungen erforderlich ist. |
|
|  | [getPermissions()](#getPermissions--) | Ermittelt die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | Legt die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion fest. |
|
### Security() {#Security--}
```
public Security()
```


Initialisiert eine neue Instanz von
Security
Klasse.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Ermittelt das Passwort, das zum Öffnen des PDF-Dokuments erforderlich ist.


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - das Dokument‑Öffnungspasswort.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Legt das Passwort fest, das zum Öffnen des PDF-Dokuments erforderlich ist.


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Das Dokument‑Öffnungspasswort. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Ermittelt das Passwort, das zum Ändern der Berechtigungseinstellungen erforderlich ist.


Mit einem Berechtigungspasswort können Sie das Drucken, Ändern und die Datenextraktion einschränken.
Verwenden Sie ein Berechtigungspasswort, um das Drucken, Ändern und die Datenextraktion einzuschränken. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - das Berechtigungspasswort.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Legt das Passwort fest, das zum Ändern der Berechtigungseinstellungen erforderlich ist.


Mit einem Berechtigungspasswort können Sie das Drucken, Ändern und die Datenextraktion einschränken.
Verwenden Sie ein Berechtigungspasswort, um das Drucken, Ändern und die Datenextraktion einzuschränken. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Das Berechtigungspasswort. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Ermittelt die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion.


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - die PDF-Dokumentberechtigungen.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Legt die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion fest.


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Die PDF-Dokumentberechtigungen. |
|

