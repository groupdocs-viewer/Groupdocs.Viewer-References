---
title: "EmailOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar mensajes de correo electrónico."
type: docs
weight: 14
url: /es/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Proporciona opciones para renderizar mensajes de correo electrónico.


La clase EmailOptions encapsula varios ajustes y parámetros que pueden usarse
para controlar la renderización de mensajes de correo electrónico en el componente GroupDocs.Viewer.


Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


Ejemplo de uso:

````

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | Inicializa una nueva instancia de la |
EmailOptions
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | Obtiene el formato de hora para los valores de fecha y hora. |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Obtiene el formato de hora para los valores de fecha y hora. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Obtiene la diferencia horaria para el mensaje. |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Obtiene los minutos de diferencia horaria para el mensaje. |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Obtiene la diferencia horaria para el mensaje. |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Obtiene el desplazamiento en minutos de la zona horaria para el mensaje. |
|
|  | [getPageSize()](#getPageSize--) | Obtiene el tamaño de la página de salida. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Obtiene el tamaño de la página de salida. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Recupera la asignación entre los campos del mensaje de correo electrónico y sus representaciones de texto. |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Establece la asignación entre los campos del mensaje de correo electrónico y sus representaciones de texto. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Sobrescribe el método equals() de la clase Object. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | Sobrescribe el método toString() de la clase Object. |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Inicializa una nueva instancia de la
EmailOptions
clase.
Este constructor se usa para crear una nueva instancia de la
EmailOptions
clase con configuraciones predeterminadas.


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Obtiene el formato de hora para los valores de fecha y hora.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Si el formato de hora no está configurado, se usará el formato del sistema actual.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.lang.String - el formato de hora para valores de fecha y hora.

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Obtiene el formato de hora para los valores de fecha y hora.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Si el formato de hora no está configurado, se usará el formato del sistema actual.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | El formato de hora para valores de fecha y hora. |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Obtiene la diferencia horaria para el mensaje.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.util.TimeZone - el desplazamiento de la zona horaria.

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Obtiene los minutos de diferencia horaria para el mensaje.
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
int - el desplazamiento de la zona horaria.

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Obtiene la diferencia horaria para el mensaje.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | El desplazamiento de la zona horaria. |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Obtiene el desplazamiento en minutos de la zona horaria para el mensaje.
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | offsetMinutes | int | El desplazamiento de la zona horaria. |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Obtiene el tamaño de la página de salida.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Obtiene el tamaño de la página de salida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | El tamaño de la página. |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Recupera la asignación entre los campos del mensaje de correo electrónico y sus representaciones de texto.


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - la asignación entre los campos del mensaje de correo electrónico y sus representaciones de texto.

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Establece la asignación entre los campos del mensaje de correo electrónico y sus representaciones de texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | La asignación entre los campos del mensaje de correo electrónico y sus representaciones de texto. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Sobrescribe el método equals() de la clase Object.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | o | java.lang.Object | El objeto con el que comparar. |
|

**Returns:**
boolean - true si los objetos son iguales, false de lo contrario.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcula el valor del código hash para este objeto. El código hash se basa en
el estado interno del objeto y se utiliza en estructuras de datos basadas en hash
como mapas hash y conjuntos hash.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - el valor del código hash para este objeto.

### toString() {#toString--}
```
public String toString()
```


Sobrescribe el método toString() de la clase Object.


**Returns:**
java.lang.String - una representación en cadena del objeto.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Devuelve una representación en cadena de este objeto.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | estilo | org.apache.commons.lang3.builder.ToStringStyle | El ToStringStyle a usar para generar la representación en cadena. |
|

**Returns:**
java.lang.String - una representación en cadena de este objeto usando el ToStringStyle especificado.

