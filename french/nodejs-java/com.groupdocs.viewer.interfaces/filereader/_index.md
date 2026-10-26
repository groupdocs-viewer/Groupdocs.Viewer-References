---
title: "FileReader"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Déclare une interface pour lire un flux de fichier."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Déclare une interface pour lire un flux de fichier.

L'interface FileReader fournit une méthode pour lire un flux de fichier. Elle est utilisée pour accéder et lire le contenu d'un fichier de manière séquentielle. Les implémentations de cette interface doivent gérer les opérations nécessaires pour lire les données d'un fichier.

Exemple d'utilisation :

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
## Méthodes

| Méthode | Description |
| --- | --- |
| [read()](#read--) | Renvoie un InputStream qui représente un flux lisible pour le fichier. |
| [close()](#close--) | Libère l'objet et libère toutes les ressources système associées. |
### read() {#read--}
```
public abstract InputStream read()
```


Renvoie un InputStream qui représente un flux lisible pour le fichier.

**Returns:**
java.io.InputStream - le flux lisible InputStream.
### close() {#close--}
```
public abstract void close()
```


Libère l'objet et libère toutes les ressources système associées.

