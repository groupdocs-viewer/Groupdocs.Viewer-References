---
title: "Sicurezza"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Fornisce opzioni di sicurezza per i documenti PDF."
type: docs
weight: 29
url: /it/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Fornisce opzioni di sicurezza per i documenti PDF.


La classe Security incapsula varie impostazioni e opzioni che possono essere utilizzate per applicare misure di sicurezza
a un documento PDF nel componente GroupDocs.Viewer. Queste opzioni includono la protezione con password,
permessi e altro.
Per ulteriori dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


Esempio di utilizzo:

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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Security()](#Security--) | Inizializza una nuova istanza di |
Sicurezza
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Ottiene la password necessaria per aprire il documento PDF. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Imposta la password necessaria per aprire il documento PDF. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Ottiene la password necessaria per modificare le impostazioni dei permessi. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Imposta la password necessaria per modificare le impostazioni dei permessi. |
|
|  | [getPermissions()](#getPermissions--) | Ottiene i permessi del documento PDF, come stampa, modifica e estrazione dei dati. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | Imposta i permessi del documento PDF, come stampa, modifica e estrazione dei dati. |
|
### Security() {#Security--}
```
public Security()
```


Inizializza una nuova istanza di
Sicurezza
classe.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Ottiene la password necessaria per aprire il documento PDF.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - la password di apertura del documento.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Imposta la password necessaria per aprire il documento PDF.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La password di apertura del documento. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Ottiene la password necessaria per modificare le impostazioni dei permessi.


Utilizzando una password per i permessi, è possibile limitare la stampa, la modifica e l'estrazione dei dati.
Usa una password per i permessi per limitare la stampa, la modifica e l'estrazione dei dati. Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - la password dei permessi.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Imposta la password necessaria per modificare le impostazioni dei permessi.


Utilizzando una password per i permessi, è possibile limitare la stampa, la modifica e l'estrazione dei dati.
Usa una password per i permessi per limitare la stampa, la modifica e l'estrazione dei dati. Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La password dei permessi. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Ottiene i permessi del documento PDF, come stampa, modifica e estrazione dei dati.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - i permessi del documento PDF.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Imposta i permessi del documento PDF, come stampa, modifica e estrazione dei dati.


Per un esempio di codice, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | I permessi del documento PDF. |
|

