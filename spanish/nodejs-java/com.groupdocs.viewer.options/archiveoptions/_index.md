---
title: "ArchiveOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones para renderizar archivos de archivo."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Proporciona opciones para renderizar archivos de archivo.

La  clase ArchiveOptions  representa un conjunto de opciones que pueden usarse para configurar el renderizado de archivos de archivo en el módulo de visualización. Permite personalizar varios aspectos del proceso de renderizado, como la cantidad de elementos por página y similares.

Ejemplo de uso:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | Crea una nueva instancia de la clase ArchiveOptions con la configuración predeterminada. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFolder()](#getFolder--) | Obtiene la carpeta dentro del archivo que se utilizará para el renderizado. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Establece la carpeta dentro del archivo que se utilizará para la renderización. |
| [getFileName()](#getFileName--) | Obtiene el nombre de archivo que se mostrará en el encabezado. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Establece el nombre de archivo que se mostrará en el encabezado. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Crea una nueva instancia de la clase ArchiveOptions con la configuración predeterminada.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


Obtiene la carpeta dentro del archivo que se utilizará para el renderizado.

Por defecto, GroupDocs.Viewer renderiza elementos de todas las carpetas contenidas en el archivo. Para renderizar elementos de una carpeta específica, establezca esta propiedad. Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - la carpeta que se renderizará.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Establece la carpeta dentro del archivo que se utilizará para la renderización.

Por defecto, GroupDocs.Viewer renderiza elementos de todas las carpetas contenidas en el archivo. Para renderizar elementos de una carpeta específica, establezca esta propiedad. Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | La carpeta que se renderizará. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Obtiene el nombre de archivo que se mostrará en el encabezado.

Por defecto, GroupDocs.Viewer muestra el nombre del archivo del archivo en el encabezado de cada página. Para cambiar o ocultar este nombre, establezca esta propiedad. Para más información y un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Establece el nombre de archivo que se mostrará en el encabezado.

Por defecto, GroupDocs.Viewer muestra el nombre del archivo del archivo en el encabezado de cada página. Para cambiar o ocultar este nombre, establezca esta propiedad. Para más información y un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | El nombre de archivo que se mostrará. |

