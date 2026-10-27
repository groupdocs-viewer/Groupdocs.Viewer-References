---
title: "Security"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt beveiligingsopties voor PDF-documenten."
type: docs
weight: 29
url: /nl/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Biedt beveiligingsopties voor PDF-documenten.

De Security‑klasse omvat verschillende instellingen en opties die kunnen worden gebruikt om beveiligingsmaatregelen toe te passen op een PDF‑document in de GroupDocs.Viewer‑component. Deze opties omvatten wachtwoordbeveiliging, permissies en meer. Voor details, zie de [documentation][].

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Security()](#Security--) | Initialiseert een nieuw exemplaar van de  Security  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Haalt het wachtwoord op dat nodig is om het PDF‑document te openen. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Stelt het wachtwoord in dat nodig is om het PDF‑document te openen. |
| [getPermissionsPassword()](#getPermissionsPassword--) | Haalt het wachtwoord op dat nodig is om permissie‑instellingen te wijzigen. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Stelt het wachtwoord in dat nodig is om permissie‑instellingen te wijzigen. |
| [getPermissions()](#getPermissions--) | Haalt de PDF-documentrechten op, zoals afdrukken, wijzigen en gegevensextractie. |
| [setPermissions(int value)](#setPermissions-int-) | Stelt de PDF-documentrechten in, zoals afdrukken, wijzigen en gegevensextractie. |
### Security() {#Security--}
```
public Security()
```


Initialiseert een nieuw exemplaar van de  Security  klasse.

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Haalt het wachtwoord op dat nodig is om het PDF‑document te openen.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - het wachtwoord voor het openen van het document.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Stelt het wachtwoord in dat nodig is om het PDF‑document te openen.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | Het wachtwoord voor het openen van het document. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Haalt het wachtwoord op dat nodig is om permissie‑instellingen te wijzigen.

Met een permissiewachtwoord kun je afdrukken, wijzigen en gegevensextractie beperken. Gebruik een permissiewachtwoord om afdrukken, wijzigen en gegevensextractie te beperken. Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - het permissiewachtwoord.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Stelt het wachtwoord in dat nodig is om permissie‑instellingen te wijzigen.

Met een permissiewachtwoord kun je afdrukken, wijzigen en gegevensextractie beperken. Gebruik een permissiewachtwoord om afdrukken, wijzigen en gegevensextractie te beperken. Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | Het permissiewachtwoord. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Haalt de PDF-documentrechten op, zoals afdrukken, wijzigen en gegevensextractie.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - de PDF-documentrechten.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Stelt de PDF-documentrechten in, zoals afdrukken, wijzigen en gegevensextractie.

Voor een codevoorbeeld, zie de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | De PDF-documentrechten. |

