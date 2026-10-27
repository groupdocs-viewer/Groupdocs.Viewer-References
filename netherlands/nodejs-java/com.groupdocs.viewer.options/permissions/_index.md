---
title: "Permissions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Definieert PDF-documentpermissies."
type: docs
weight: 24
url: /nl/nodejs-java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Definieert PDF-documentpermissies.

De Permissions‑klasse biedt constanten die verschillende rechten vertegenwoordigen die kunnen worden toegepast op een PDF‑document in de GroupDocs.Viewer‑component. Deze rechten regelen de acties die op het PDF‑document kunnen worden uitgevoerd, zoals afdrukken, tekst kopiëren, annotaties wijzigen en meer.

Voorbeeldgebruik:

```

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Afdrukken, wijzigen en gegevensextractie toestaan. |
| [DENY_PRINTING](#DENY-PRINTING) | Afdrukken weigeren. |
| [DENY_MODIFICATION](#DENY-MODIFICATION) | Wijzigen van inhoud, invullen van formulieren, toevoegen of wijzigen van annotaties weigeren. |
| [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Tekst- en grafiekextractie weigeren. |
| [DENY_ALL](#DENY-ALL) | Afdrukken, wijzigen en gegevensextractie weigeren. |
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Afdrukken, wijzigen en gegevensextractie toestaan.

### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Afdrukken weigeren.

### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Wijzigen van inhoud, invullen van formulieren, toevoegen of wijzigen van annotaties weigeren.

### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Tekst- en grafiekextractie weigeren.

### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Afdrukken, wijzigen en gegevensextractie weigeren.

