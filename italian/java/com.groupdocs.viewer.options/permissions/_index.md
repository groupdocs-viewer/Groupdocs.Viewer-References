---
title: "Permissions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Definisce i permessi del documento PDF."
type: docs
weight: 24
url: /it/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Definisce i permessi del documento PDF.


La classe Permissions fornisce costanti che rappresentano diverse autorizzazioni
che possono essere applicate a un documento PDF nel componente GroupDocs.Viewer.
Queste autorizzazioni controllano le azioni che possono essere eseguite sul documento PDF,
come la stampa, la copia del testo, la modifica delle annotazioni e altro.


Esempio di utilizzo:

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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | Consenti stampa, modifica ed estrazione dei dati. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | Nega stampa. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | Nega la modifica del contenuto, la compilazione dei moduli, l'aggiunta o la modifica delle annotazioni. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Nega l'estrazione di testo e grafica. |
|
|  | [DENY_ALL](#DENY-ALL) | Nega stampa, modifica ed estrazione dei dati. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Consenti stampa, modifica ed estrazione dei dati.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Nega stampa.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Nega la modifica del contenuto, la compilazione dei moduli, l'aggiunta o la modifica delle annotazioni.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Nega l'estrazione di testo e grafica.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Nega stampa, modifica ed estrazione dei dati.


