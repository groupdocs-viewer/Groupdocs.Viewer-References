---
title: "ProjectManagementViewInfo"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa información de vista para un documento de MS Project."
type: docs
weight: 23
url: /es/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Representa información de vista para un documento de MS Project.

La interfaz ProjectManagementViewInfo define el contrato para acceder y manipular la información de vista de un documento MS Project en el componente GroupDocs.Viewer. Proporciona métodos para obtener información como las fechas de inicio y fin, y otras propiedades.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Métodos

| Método | Descripción |
| --- | --- |
| [getStartDate()](#getStartDate--) | Obtiene la fecha y hora en que el proyecto comenzó. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Establece la fecha y hora de inicio del proyecto. |
| [getEndDate()](#getEndDate--) | Obtiene la fecha y hora en que se debe completar el proyecto. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Establece la fecha y hora de finalización del proyecto. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Obtiene la fecha y hora en que el proyecto comenzó.

**Returns:**
java.util.Date - la fecha y hora de inicio del proyecto.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Establece la fecha y hora de inicio del proyecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startDate | java.util.Date | la nueva fecha y hora de inicio a establecer. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Obtiene la fecha y hora en que se debe completar el proyecto.

**Returns:**
java.util.Date - la fecha y hora de finalización del proyecto.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Establece la fecha y hora de finalización del proyecto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| endDate | java.util.Date | la nueva fecha y hora de finalización a establecer. |

