---
title: "FileReader"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Dichiara un'interfaccia per la lettura di uno stream di file."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Dichiara un'interfaccia per la lettura di uno stream di file.

L'interfaccia FileReader fornisce un metodo per leggere un flusso di file. Viene utilizzata per accedere e leggere il contenuto di un file in modo sequenziale. Le implementazioni di questa interfaccia dovrebbero gestire le operazioni necessarie per leggere i dati da un file.

Esempio di utilizzo:

```

 FileReader fileReader = new FileReader() {
     @Override
     public InputStream read() {
         // Create document stream
     }

     @Override
     public void close() {
         // Close the stream
     }
 };
 try (Viewer viewer = new Viewer(fileReader, new ViewerSettings())){
     // Process document
 }
 
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [read()](#read--) | Restituisce un InputStream che rappresenta un flusso leggibile per il file. |
| [close()](#close--) | Elimina l'oggetto e rilascia tutte le risorse di sistema ad esso associate. |
### read() {#read--}
```
public abstract InputStream read()
```


Restituisce un InputStream che rappresenta un flusso leggibile per il file.

**Returns:**
java.io.InputStream - il flusso leggibile InputStream.
### close() {#close--}
```
public abstract void close()
```


Elimina l'oggetto e rilascia tutte le risorse di sistema ad esso associate.

