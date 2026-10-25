---
title: "FileReader"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Declareert een interface voor het lezen van een bestandsstream."
type: docs
weight: 14
url: /nl/java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Declareert een interface voor het lezen van een bestandsstream.


De FileReader-interface biedt een methode voor het lezen van een bestandsstroom. Het wordt gebruikt voor het openen en lezen van de inhoud
van een bestand op een sequentiële manier. Implementaties van deze interface moeten de noodzakelijke bewerkingen uitvoeren om gegevens uit een bestand te lezen.


Voorbeeldgebruik:

````

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
 
````


## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [read()](#read--) | Retourneert een InputStream die een leesbare stroom voor het bestand vertegenwoordigt. |
|
|  | [close()](#close--) | Verwijdert het object en geeft alle bijbehorende systeembronnen vrij. |
|
### read() {#read--}
```
public abstract InputStream read()
```


Retourneert een InputStream die een leesbare stroom voor het bestand vertegenwoordigt.


**Returns:**
java.io.InputStream - de leesbare InputStream-stroom.

### close() {#close--}
```
public abstract void close()
```


Verwijdert het object en geeft alle bijbehorende systeembronnen vrij.


