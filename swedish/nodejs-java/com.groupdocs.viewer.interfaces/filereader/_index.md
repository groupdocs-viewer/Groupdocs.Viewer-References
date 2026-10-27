---
title: "FileReader"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Deklarerar ett gränssnitt för att läsa en filström."
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Deklarerar ett gränssnitt för att läsa en filström.

FileReader-gränssnittet tillhandahåller en metod för att läsa en filström. Det används för att komma åt och läsa innehållet i en fil på ett sekventiellt sätt. Implementationer av detta gränssnitt bör hantera de nödvändiga operationerna för att läsa data från en fil.

Exempel på användning:

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [read()](#read--) | Returnerar en InputStream som representerar en läsbar ström för filen. |
| [close()](#close--) | Frigör objektet och släpper alla systemresurser som är associerade med det. |
### read() {#read--}
```
public abstract InputStream read()
```


Returnerar en InputStream som representerar en läsbar ström för filen.

**Returns:**
java.io.InputStream - den läsbara InputStream-strömmen.
### close() {#close--}
```
public abstract void close()
```


Frigör objektet och släpper alla systemresurser som är associerade med det.

