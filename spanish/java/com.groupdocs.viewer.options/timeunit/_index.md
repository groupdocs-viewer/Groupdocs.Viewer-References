---
title: "TimeUnit"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Unidad de tiempo de la duración del proyecto."
type: docs
weight: 47
url: /es/java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Unidad de tiempo de la duración del proyecto.


El enum TimeUnit representa diferentes unidades de tiempo para especificar la duración de un proyecto en el componente GroupDocs.Viewer.
Proporciona un conjunto de unidades de tiempo predefinidas que pueden usarse para representar y calcular la duración de un proyecto,
como días, meses, etc.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


Ejemplo de uso:

````

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | La escala de tiempo desconocida. |
|
|  | [DAYS](#DAYS) | Escala de tiempo en días. |
|
|  | [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Escala de tiempo de terceras partes del mes. |
|
|  | [MONTHS](#MONTHS) | Escala de tiempo de meses. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


La escala de tiempo desconocida.
Esta unidad de tiempo representa una escala de tiempo desconocida o no especificada.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Escala de tiempo en días.
Esta unidad de tiempo representa un intervalo de un día.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Escala de tiempo de terceras partes del mes.
Esta unidad de tiempo representa un intervalo de un tercio del mes.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Escala de tiempo de meses.
Esta unidad de tiempo representa un intervalo de un mes.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


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
