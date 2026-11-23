---
title: "Beveiliging"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Biedt PDF‑documentbeveiligingsopties."
type: docs
weight: 29
url: /nl/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Biedt PDF‑documentbeveiligingsopties.


De Security-klasse omvat verschillende instellingen en opties die kunnen worden gebruikt om beveiligingsmaatregelen toe te passen
aan een PDF-document in de GroupDocs.Viewer-component. Deze opties omvatten wachtwoordbeveiliging,
machtigingen, en meer.
Zie voor details de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Security()](#Security--) | Initialiseert een nieuw exemplaar van de |
Beveiliging
klasse.
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Haalt het wachtwoord op dat nodig is om het PDF-document te openen. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Stelt het wachtwoord in dat nodig is om het PDF-document te openen. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Haalt het wachtwoord op dat nodig is om machtigingsinstellingen te wijzigen. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Stelt het wachtwoord in dat nodig is om machtigingsinstellingen te wijzigen. |
|
|  | [getPermissions()](#getPermissions--) | Haalt de PDF-documentmachtigingen op, zoals afdrukken, wijzigen en gegevensextractie. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | Stelt de PDF-documentmachtigingen in, zoals afdrukken, wijzigen en gegevensextractie. |
|
### Security() {#Security--}
```
public Security()
```


Initialiseert een nieuw exemplaar van de
Beveiliging
klasse.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Haalt het wachtwoord op dat nodig is om het PDF-document te openen.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - het wachtwoord om het document te openen.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Stelt het wachtwoord in dat nodig is om het PDF-document te openen.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het wachtwoord om het document te openen. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Haalt het wachtwoord op dat nodig is om machtigingsinstellingen te wijzigen.


Met een machtigingswachtwoord kun je afdrukken, wijzigen en gegevensextractie beperken.
Gebruik een machtigingswachtwoord om afdrukken, wijzigen en gegevensextractie te beperken. Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - het machtigingswachtwoord.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Stelt het wachtwoord in dat nodig is om machtigingsinstellingen te wijzigen.


Met een machtigingswachtwoord kun je afdrukken, wijzigen en gegevensextractie beperken.
Gebruik een machtigingswachtwoord om afdrukken, wijzigen en gegevensextractie te beperken. Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | Het machtigingswachtwoord. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Haalt de PDF-documentmachtigingen op, zoals afdrukken, wijzigen en gegevensextractie.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - de PDF-documentmachtigingen.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Stelt de PDF-documentmachtigingen in, zoals afdrukken, wijzigen en gegevensextractie.


Voor een codevoorbeeld, zie de [documentatie](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De PDF-documentmachtigingen. |
|

