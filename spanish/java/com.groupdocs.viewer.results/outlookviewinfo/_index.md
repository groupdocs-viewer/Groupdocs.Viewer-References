---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa información de vista para un archivo de datos de Outlook."
type: docs
weight: 22
url: /es/java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Representa información de vista para un archivo de datos de Outlook.


La interfaz OutlookViewInfo define el contrato para acceder y manipular la información de vista
para un archivo de datos de Outlook en el componente GroupDocs.Viewer. Proporciona métodos para obtener información
como una lista de carpetas y otras propiedades.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is OutlookViewInfoImpl.*

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFolders()](#getFolders--) | Recupera la lista de carpetas contenidas en el archivo de datos de Outlook. |
|
|  | [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Establece la lista de carpetas contenidas en el archivo de datos de Outlook. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Recupera la lista de carpetas contenidas en el archivo de datos de Outlook.


**Returns:**
java.util.List<java.lang.String> - la lista de carpetas.

### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Establece la lista de carpetas contenidas en el archivo de datos de Outlook.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | lista | java.util.List<java.lang.String> | la lista de carpetas. |
|

