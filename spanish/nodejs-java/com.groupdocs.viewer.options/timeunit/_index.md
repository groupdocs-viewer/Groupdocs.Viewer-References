---
title: "TimeUnit"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Unidad de tiempo de la duración del proyecto."
type: docs
weight: 47
url: /es/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Unidad de tiempo de la duración del proyecto.

El enum TimeUnit representa diferentes unidades de tiempo para especificar la duración de un proyecto en el componente GroupDocs.Viewer. Proporciona un conjunto de unidades de tiempo predefinidas que pueden usarse para representar y calcular la duración de un proyecto, como días, meses, etc. Para más detalles, consulte la [documentación][].

Ejemplo de uso:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## Fields

| Field | Descripción |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | La escala de tiempo desconocida. |
| [DAYS](#DAYS) | Escala de tiempo en días. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Escala de tiempo en tercios de mes. |
| [MONTHS](#MONTHS) | Escala de tiempo en meses. |
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


La escala de tiempo desconocida. Esta unidad de tiempo representa una escala de tiempo desconocida o no especificada.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Escala de tiempo en días. Esta unidad de tiempo representa un intervalo de un día.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Escala de tiempo en tercios de mes. Esta unidad de tiempo representa un intervalo de un tercio del mes.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Escala de tiempo en meses. Esta unidad de tiempo representa un intervalo de un mes.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
