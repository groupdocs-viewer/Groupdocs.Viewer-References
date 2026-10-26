---
title: "FileName"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta il nome di un file in un archivio."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Rappresenta il nome di un file in un archivio.

La classe FileName incapsula il nome di un file senza alcuna informazione di percorso o directory. Fornisce metodi per manipolare e recuperare informazioni sul nome del file.

Esempio di utilizzo:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | Inizializza una nuova istanza della  classe FileName. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [EMPTY](#EMPTY) | Rappresenta un nome file vuoto. |
| [SOURCE](#SOURCE) | Rappresenta il nome del file di origine. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa dell'oggetto corrente. |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Inizializza una nuova istanza della  classe FileName.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | java.lang.String | Il nome del file. |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Rappresenta un nome file vuoto.

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Rappresenta il nome del file di origine.

### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa dell'oggetto corrente.

**Returns:**
java.lang.String - una rappresentazione stringa dell'oggetto corrente.
