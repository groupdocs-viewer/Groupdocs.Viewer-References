---
title: "Security"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Optionen für die Sicherheit von PDF-Dokumenten bereit."
type: docs
weight: 29
url: /de/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Stellt Optionen für die Sicherheit von PDF-Dokumenten bereit.

Die Security‑Klasse kapselt verschiedene Einstellungen und Optionen, die verwendet werden können, um Sicherheitsmaßnahmen auf ein PDF‑Dokument in der GroupDocs.Viewer‑Komponente anzuwenden. Diese Optionen umfassen Passwortschutz, Berechtigungen und mehr. Für Details siehe die [Dokumentation][].

Beispielhafte Verwendung:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Security()](#Security--) | Initialisiert eine neue Instanz der  Security  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Liest das Passwort, das zum Öffnen des PDF‑Dokuments erforderlich ist. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Setzt das Passwort, das zum Öffnen des PDF‑Dokuments erforderlich ist. |
| [getPermissionsPassword()](#getPermissionsPassword--) | Liest das Passwort, das zum Ändern der Berechtigungseinstellungen erforderlich ist. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Setzt das Passwort, das zum Ändern der Berechtigungseinstellungen erforderlich ist. |
| [getPermissions()](#getPermissions--) | Ermittelt die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion. |
| [setPermissions(int value)](#setPermissions-int-) | Legt die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion fest. |
### Security() {#Security--}
```
public Security()
```


Initialisiert eine neue Instanz der  Security  Klasse.

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Liest das Passwort, das zum Öffnen des PDF‑Dokuments erforderlich ist.

Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String – das Dokument-Öffnungspasswort.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Setzt das Passwort, das zum Öffnen des PDF‑Dokuments erforderlich ist.

Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | Das Dokument-Öffnungspasswort. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Liest das Passwort, das zum Ändern der Berechtigungseinstellungen erforderlich ist.

Mit einem Berechtigungspasswort können Sie das Drucken, Ändern und die Datenextraktion einschränken. Verwenden Sie ein Berechtigungspasswort, um das Drucken, Ändern und die Datenextraktion einzuschränken. Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String – das Berechtigungspasswort.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Setzt das Passwort, das zum Ändern der Berechtigungseinstellungen erforderlich ist.

Mit einem Berechtigungspasswort können Sie das Drucken, Ändern und die Datenextraktion einschränken. Verwenden Sie ein Berechtigungspasswort, um das Drucken, Ändern und die Datenextraktion einzuschränken. Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String | Das Berechtigungspasswort. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Ermittelt die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion.

Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int – die PDF-Dokumentberechtigungen.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Legt die PDF-Dokumentberechtigungen wie Drucken, Ändern und Datenextraktion fest.

Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int | Die PDF-Dokumentberechtigungen. |

