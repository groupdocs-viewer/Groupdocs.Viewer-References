---
title: "Security"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller säkerhetsalternativ för PDF-dokument."
type: docs
weight: 29
url: /sv/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Tillhandahåller säkerhetsalternativ för PDF-dokument.


Security-klassen kapslar in olika inställningar och alternativ som kan användas för att tillämpa säkerhetsåtgärder
till ett PDF-dokument i GroupDocs.Viewer-komponenten. Dessa alternativ inkluderar lösenordsskydd,
behörigheter och mer.
För detaljer, se [dokumentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


Exempel på användning:

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


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Security()](#Security--) | Initierar en ny instans av |
Security
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Hämtar lösenordet som krävs för att öppna PDF-dokumentet. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Ställer in lösenordet som krävs för att öppna PDF-dokumentet. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Hämtar lösenordet som krävs för att ändra behörighetsinställningar. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Ställer in lösenordet som krävs för att ändra behörighetsinställningar. |
|
|  | [getPermissions()](#getPermissions--) | Hämtar PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | Ställer in PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion. |
|
### Security() {#Security--}
```
public Security()
```


Initierar en ny instans av
Security
klassen.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Hämtar lösenordet som krävs för att öppna PDF-dokumentet.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - dokumentets öppningslösenord.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Ställer in lösenordet som krävs för att öppna PDF-dokumentet.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Dokumentets öppningslösenord. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Hämtar lösenordet som krävs för att ändra behörighetsinställningar.


Genom att använda ett behörighetslösenord kan du begränsa utskrift, ändring och dataextraktion.
Använd ett behörighetslösenord för att begränsa utskrift, ändring och dataextraktion. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - behörighetslösenordet.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Ställer in lösenordet som krävs för att ändra behörighetsinställningar.


Genom att använda ett behörighetslösenord kan du begränsa utskrift, ändring och dataextraktion.
Använd ett behörighetslösenord för att begränsa utskrift, ändring och dataextraktion. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Behörighetslösenordet. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Hämtar PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - PDF-dokumentets behörigheter.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Ställer in PDF-dokumentets behörigheter såsom utskrift, ändring och dataextraktion.


För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | PDF-dokumentets behörigheter. |
|

