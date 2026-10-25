---
title: "Permissions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Definierar PDF-dokumentbehörigheter."
type: docs
weight: 24
url: /sv/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Definierar PDF-dokumentbehörigheter.


Permissions‑klassen tillhandahåller konstanter som representerar olika behörigheter
som kan tillämpas på ett PDF‑dokument i GroupDocs.Viewer‑komponenten.
Dessa behörigheter styr de åtgärder som kan utföras på PDF‑dokumentet,
såsom utskrift, kopiering av text, modifiering av annotationer och mer.


Exempel på användning:

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


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | Tillåt utskrift, modifiering och dataextraktion. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | Neka utskrift. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | Neka innehållsmodifiering, ifyllning av formulär, samt tillägg eller modifiering av annotationer. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Neka extraktion av text och grafik. |
|
|  | [DENY_ALL](#DENY-ALL) | Neka utskrift, modifiering och dataextraktion. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Tillåt utskrift, modifiering och dataextraktion.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Neka utskrift.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Neka innehållsmodifiering, ifyllning av formulär, samt tillägg eller modifiering av annotationer.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Neka extraktion av text och grafik.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Neka utskrift, modifiering och dataextraktion.


