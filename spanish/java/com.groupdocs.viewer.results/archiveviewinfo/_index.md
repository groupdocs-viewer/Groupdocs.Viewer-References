---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa información de vista para un archivo comprimido."
type: docs
weight: 11
url: /es/java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Representa información de vista para un archivo comprimido.


La interfaz ArchiveViewInfo define el contrato para obtener información de vista específica de un archivo de archivo
en el componente GroupDocs.Viewer. Proporciona métodos para acceder a detalles como el recuento de páginas, dimensiones y opciones de renderizado
específicos de archivos de archivo.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFolders()](#getFolders--) | Recupera la lista de carpetas contenidas en el archivo de archivo. |
|
|  | [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Establece la lista de carpetas contenidas en el archivo de archivo. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Recupera la lista de carpetas contenidas en el archivo de archivo.


**Returns:**
java.util.List<java.lang.String> - la lista de carpetas.

### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Establece la lista de carpetas contenidas en el archivo de archivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | carpetas | java.util.List<java.lang.String> | la lista de carpetas. |
|

