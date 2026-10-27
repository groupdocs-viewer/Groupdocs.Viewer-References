---
title: "ProjectManagementOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones para renderizar archivos de gestión de proyectos."
type: docs
weight: 27
url: /es/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Proporciona opciones para renderizar archivos de gestión de proyectos.

La clase ProjectManagementOptions encapsula varios ajustes y parámetros que pueden usarse para controlar la renderización de archivos de gestión de proyectos (como Microsoft Project o similares) en el componente GroupDocs.Viewer. Para obtener más detalles, consulte la [documentación][].

Ejemplo de uso:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | Inicializa una nueva instancia de la clase  ProjectManagementOptions  . |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPageSize()](#getPageSize--) | Obtiene el tamaño de página de salida. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Establece el tamaño de página de salida. |
| [getTimeUnit()](#getTimeUnit--) | Obtiene la unidad de tiempo. |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Obtiene la unidad de tiempo. |
| [getStartDate()](#getStartDate--) | Obtiene la fecha de inicio de la vista de diagrama de Gantt que se incluirá en la salida. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Establece la fecha de inicio de la vista de diagrama de Gantt que se incluirá en la salida. |
| [getEndDate()](#getEndDate--) | Obtiene la fecha de finalización de la vista de diagrama de Gantt que se incluirá en la salida. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Establece la fecha de finalización de la vista de diagrama de Gantt que se incluirá en la salida. |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Inicializa una nueva instancia de la clase  ProjectManagementOptions  .

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Obtiene el tamaño de página de salida.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Establece el tamaño de página de salida.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | El tamaño de página de salida. |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Obtiene la unidad de tiempo.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Obtiene la unidad de tiempo.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | La unidad de tiempo. |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Obtiene la fecha de inicio de la vista de diagrama de Gantt que se incluirá en la salida.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - la fecha de inicio de la vista de diagrama de Gantt.
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Establece la fecha de inicio de la vista de diagrama de Gantt que se incluirá en la salida.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date | La fecha de inicio de la vista de diagrama de Gantt. |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Obtiene la fecha de finalización de la vista de diagrama de Gantt que se incluirá en la salida.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - la fecha de finalización de la vista de diagrama de Gantt.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Establece la fecha de finalización de la vista de diagrama de Gantt que se incluirá en la salida.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date | La fecha de finalización de la vista de diagrama de Gantt. |

