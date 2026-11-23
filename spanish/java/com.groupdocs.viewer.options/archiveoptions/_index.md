---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar archivos de archivo."
type: docs
weight: 10
url: /es/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Proporciona opciones para renderizar archivos de archivo.


El
ArchiveOptions
La clase representa un conjunto de opciones que pueden usarse para configurar la renderización de archivos de archivo en el módulo de visualización.
Le permite personalizar varios aspectos del proceso de renderización, como la cantidad de elementos en cada página, entre otros.


Ejemplo de uso:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
La clase proporciona una variedad de opciones de personalización para la renderización de archivos de archivo.
Puede configurar estas opciones según sus requisitos específicos para lograr la salida deseada.*

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | Crea una nueva instancia de la clase ArchiveOptions con la configuración predeterminada. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFolder()](#getFolder--) | Obtiene la carpeta dentro del archivo que se utilizará para la renderización. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Establece la carpeta dentro del archivo que se utilizará para la renderización. |
|
|  | [getFileName()](#getFileName--) | Obtiene el nombre de archivo que se mostrará en el encabezado. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Establece el nombre de archivo que se mostrará en el encabezado. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Crea una nueva instancia de la clase ArchiveOptions con la configuración predeterminada.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Obtiene la carpeta dentro del archivo que se utilizará para la renderización.


Por defecto, GroupDocs.Viewer renderiza los elementos de todas las carpetas contenidas en el archivo. Para renderizar elementos de una carpeta específica, establezca esta propiedad.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder).


**Returns:**
java.lang.String - la carpeta a renderizar.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Establece la carpeta dentro del archivo que se utilizará para la renderización.


Por defecto, GroupDocs.Viewer renderiza los elementos de todas las carpetas contenidas en el archivo. Para renderizar elementos de una carpeta específica, establezca esta propiedad.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La carpeta a renderizar. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Obtiene el nombre de archivo que se mostrará en el encabezado.


Por defecto, GroupDocs.Viewer muestra el nombre del archivo de archivo en el encabezado de cada página. Para cambiar u ocultar este nombre, establezca esta propiedad.
Para obtener más información y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Establece el nombre de archivo que se mostrará en el encabezado.


Por defecto, GroupDocs.Viewer muestra el nombre del archivo de archivo en el encabezado de cada página. Para cambiar u ocultar este nombre, establezca esta propiedad.
Para obtener más información y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | El nombre de archivo que se mostrará. |
|

