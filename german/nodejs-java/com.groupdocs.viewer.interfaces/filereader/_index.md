---
title: "FileReader"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Deklariert eine Schnittstelle zum Lesen eines Dateistreams."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Deklariert eine Schnittstelle zum Lesen eines Dateistreams.

Das FileReader‑Interface stellt eine Methode zum Lesen eines Dateistreams bereit. Es wird verwendet, um auf den Inhalt einer Datei sequenziell zuzugreifen und ihn zu lesen. Implementierungen dieses Interfaces sollten die erforderlichen Vorgänge zum Lesen von Daten aus einer Datei durchführen.

Beispielhafte Verwendung:

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
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [read()](#read--) | Gibt einen InputStream zurück, der einen lesbaren Stream für die Datei darstellt. |
| [close()](#close--) | Entsorgt das Objekt und gibt alle damit verbundenen Systemressourcen frei. |
### read() {#read--}
```
public abstract InputStream read()
```


Gibt einen InputStream zurück, der einen lesbaren Stream für die Datei darstellt.

**Returns:**
java.io.InputStream - der lesbare InputStream.
### close() {#close--}
```
public abstract void close()
```


Entsorgt das Objekt und gibt alle damit verbundenen Systemressourcen frei.

