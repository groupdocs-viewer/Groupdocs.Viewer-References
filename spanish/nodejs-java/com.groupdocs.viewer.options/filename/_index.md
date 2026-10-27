---
title: "FileName"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa el nombre de un archivo en un archivo comprimido."
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Representa el nombre de un archivo en un archivo comprimido.

La clase FileName encapsula el nombre de un archivo sin ninguna información de ruta o directorio. Proporciona métodos para manipular y obtener información sobre el nombre del archivo.

Ejemplo de uso:

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | Inicializa una nueva instancia de la clase  FileName . |
## Fields

| Field | Descripción |
| --- | --- |
| [EMPTY](#EMPTY) | Representa un nombre de archivo vacío. |
| [SOURCE](#SOURCE) | Representa el nombre del archivo fuente. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | Devuelve una representación en forma de cadena del objeto actual. |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Inicializa una nueva instancia de la clase  FileName .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | java.lang.String | El nombre del archivo. |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Representa un nombre de archivo vacío.

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Representa el nombre del archivo fuente.

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


Devuelve una representación en forma de cadena del objeto actual.

**Returns:**
java.lang.String - una representación en forma de cadena del objeto actual.
