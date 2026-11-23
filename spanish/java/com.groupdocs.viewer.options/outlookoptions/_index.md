---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar archivos de datos de Outlook."
type: docs
weight: 20
url: /es/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Proporciona opciones para renderizar archivos de datos de Outlook.


La clase OutlookOptions encapsula varios ajustes y parámetros que pueden ser utilizados
para controlar el renderizado de archivos de datos de Outlook (como archivos PST u OST) en el componente GroupDocs.Viewer.


Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Ejemplo de uso:

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFolder()](#getFolder--) | Obtiene el nombre de la carpeta a renderizar. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Establece el nombre de la carpeta a renderizar. |
|
|  | [getTextFilter()](#getTextFilter--) | Obtiene las palabras clave utilizadas para filtrar mensajes. |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Obtiene las palabras clave utilizadas para filtrar mensajes. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Obtiene la dirección de correo electrónico utilizada para filtrar mensajes por remitente o destinatario. |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Establece la dirección de correo electrónico utilizada para filtrar mensajes por remitente o destinatario. |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Obtiene el número máximo de mensajes o elementos que pueden renderizarse desde una carpeta. |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Establece el número máximo de mensajes o elementos que pueden renderizarse desde una carpeta. |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Obtiene el nombre de la carpeta a renderizar.
El nombre de la carpeta (p. ej., Bandeja de entrada, Elementos enviados o Elementos eliminados) a renderizar.


Al renderizar un archivo de datos de Outlook, GroupDocs.Viewer renderiza los mensajes de todas las carpetas contenidas en el archivo (incluidas las carpetas anidadas). Use esta propiedad para renderizar elementos de una carpeta específica.
Para un ejemplo de código, consulte esta [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Returns:**
java.lang.String - el nombre de la carpeta a renderizar.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Establece el nombre de la carpeta a renderizar.
El nombre de la carpeta (p. ej., Bandeja de entrada, Elementos enviados o Elementos eliminados) a renderizar.


Al renderizar un archivo de datos de Outlook, GroupDocs.Viewer renderiza los mensajes de todas las carpetas contenidas en el archivo (incluidas las carpetas anidadas). Use esta propiedad para renderizar elementos de una carpeta específica.
Para un ejemplo de código, consulte esta [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre de la carpeta a renderizar. |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Obtiene las palabras clave utilizadas para filtrar mensajes.


Use esta propiedad para renderizar todos los mensajes que contengan texto específico en el asunto o el cuerpo. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - las palabras clave.

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Obtiene las palabras clave utilizadas para filtrar mensajes.


Use esta propiedad para renderizar todos los mensajes que contengan texto específico en el asunto o el cuerpo. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | Las palabras clave. |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Obtiene la dirección de correo electrónico utilizada para filtrar mensajes por remitente o destinatario.


Use esta propiedad para renderizar todos los mensajes que contengan texto específico en la dirección del remitente\\ufffds o del destinatario\\ufffds. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - la dirección de correo electrónico utilizada para filtrar los mensajes.

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Establece la dirección de correo electrónico utilizada para filtrar mensajes por remitente o destinatario.


Use esta propiedad para renderizar todos los mensajes que contengan texto específico en la dirección del remitente\\ufffds o del destinatario\\ufffds. Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La dirección de correo electrónico utilizada para filtrar los mensajes. |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Obtiene el número máximo de mensajes o elementos que pueden renderizarse desde una carpeta.


Los archivos de datos de Outlook pueden ser grandes y recuperar todos los mensajes puede llevar tiempo significativo.
Esta configuración limita el número máximo de mensajes o elementos (como contactos y tareas) que se renderizan.
El valor predeterminado es 50. Establezca el valor en 0 para renderizar todos los mensajes.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Returns:**
int - el número máximo de mensajes o elementos que pueden renderizarse desde una carpeta.

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Establece el número máximo de mensajes o elementos que pueden renderizarse desde una carpeta.


Los archivos de datos de Outlook pueden ser grandes y recuperar todos los mensajes puede llevar tiempo significativo.
Esta configuración limita el número máximo de mensajes o elementos (como contactos y tareas) que se renderizan.
El valor predeterminado es 50. Establezca el valor en 0 para renderizar todos los mensajes.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El número máximo de mensajes o elementos que pueden renderizarse desde una carpeta. |
|

