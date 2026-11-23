---
title: "FileReader"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Declara una interfaz para leer un flujo de archivo."
type: docs
weight: 14
url: /es/java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Declara una interfaz para leer un flujo de archivo.


La interfaz FileReader proporciona un método para leer un flujo de archivo. Se utiliza para acceder y leer el contenido
de un archivo de forma secuencial. Las implementaciones de esta interfaz deben manejar las operaciones necesarias para leer datos de un archivo.


Ejemplo de uso:

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


## Métodos

| Método | Descripción |
| --- | --- |
|  | [read()](#read--) | Devuelve un InputStream que representa un flujo legible para el archivo. |
|
|  | [close()](#close--) | Elimina el objeto y libera los recursos del sistema asociados a él. |
|
### read() {#read--}
```
public abstract InputStream read()
```


Devuelve un InputStream que representa un flujo legible para el archivo.


**Returns:**
java.io.InputStream - el flujo legible InputStream.

### close() {#close--}
```
public abstract void close()
```


Elimina el objeto y libera los recursos del sistema asociados a él.


