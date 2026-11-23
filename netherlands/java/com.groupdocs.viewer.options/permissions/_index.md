---
title: "Machtigingen"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Definieert PDF‑documentrechten."
type: docs
weight: 24
url: /nl/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Definieert PDF‑documentrechten.


De Permissions-klasse biedt constanten die verschillende machtigingen vertegenwoordigen.
die kunnen worden toegepast op een PDF-document in de GroupDocs.Viewer-component.
Deze machtigingen bepalen de acties die op het PDF-document kunnen worden uitgevoerd,
zoals afdrukken, tekst kopiëren, annotaties wijzigen en meer.


Voorbeeldgebruik:

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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | Sta afdrukken, wijziging en gegevensextractie toe. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | Weiger afdrukken. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | Weiger inhoudsaanpassing, formulieren invullen, annotaties toevoegen of wijzigen. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Weiger tekst- en grafiekextractie. |
|
|  | [DENY_ALL](#DENY-ALL) | Weiger afdrukken, wijziging en gegevensextractie. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Sta afdrukken, wijziging en gegevensextractie toe.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Weiger afdrukken.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Weiger inhoudsaanpassing, formulieren invullen, annotaties toevoegen of wijzigen.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Weiger tekst- en grafiekextractie.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Weiger afdrukken, wijziging en gegevensextractie.


