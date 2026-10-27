---
title: "MailStorageOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones para renderizar archivos de datos de Mail storage Lotus Notes MBox."
type: docs
weight: 19
url: /es/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Proporciona opciones para renderizar archivos de datos de almacenamiento de correo (Lotus Notes, MBox).

La clase MailStorageOptions encapsula varios ajustes y parámetros que pueden usarse para controlar el renderizado de archivos de datos de almacenamiento de correo (como Lotus Notes o MBox) en el componente GroupDocs.Viewer.

Para obtener más detalles, consulte la [documentación][].

Ejemplo de uso:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | Obtiene las palabras clave usadas para filtrar mensajes. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Establece las palabras clave usadas para filtrar mensajes. |
| [getAddressFilter()](#getAddressFilter--) | Obtiene la dirección de correo electrónico usada para filtrar mensajes por remitente o destinatario. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Establece la dirección de correo electrónico usada para filtrar mensajes por remitente o destinatario. |
| [getMaxItems()](#getMaxItems--) | Obtiene el número máximo de mensajes o elementos a renderizar. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Establece el número máximo de mensajes o elementos a renderizar. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Obtiene las palabras clave usadas para filtrar mensajes.

Utilice esta propiedad para renderizar todos los mensajes que contengan texto específico en el asunto o cuerpo. Para un ejemplo de código, vea la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - las palabras clave usadas para filtrar mensajes.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Establece las palabras clave usadas para filtrar mensajes.

Utilice esta propiedad para renderizar todos los mensajes que contengan texto específico en el asunto o cuerpo. Para un ejemplo de código, vea la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textFilter | java.lang.String | Las palabras clave usadas para filtrar mensajes. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Obtiene la dirección de correo electrónico usada para filtrar mensajes por remitente o destinatario.

Utilice esta propiedad para renderizar todos los mensajes que contengan texto específico en la dirección del remitente o del destinatario. Para un ejemplo de código, vea la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - la dirección de correo electrónico usada para filtrar mensajes.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Establece la dirección de correo electrónico usada para filtrar mensajes por remitente o destinatario.

Utilice esta propiedad para renderizar todos los mensajes que contengan texto específico en la dirección del remitente o del destinatario. Para un ejemplo de código, vea la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| addressFilter | java.lang.String | La dirección de correo electrónico utilizada para filtrar los mensajes. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Obtiene el número máximo de mensajes o elementos a renderizar.

Los archivos de datos de Lotus Notes pueden ser grandes, y recuperar todos los mensajes puede llevar tiempo significativo. Esta configuración limita el número máximo de mensajes o elementos que se renderizan.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int - el número máximo de mensajes o elementos a renderizar.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Establece el número máximo de mensajes o elementos a renderizar.

Los archivos de datos de Lotus Notes pueden ser grandes, y recuperar todos los mensajes puede llevar tiempo significativo. Esta configuración limita el número máximo de mensajes o elementos que se renderizan.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxItems | int | El número máximo de mensajes o elementos a renderizar. |

