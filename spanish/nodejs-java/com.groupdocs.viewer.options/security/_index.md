---
title: "Security"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones de seguridad para documentos PDF."
type: docs
weight: 29
url: /es/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Proporciona opciones de seguridad para documentos PDF.

La clase Security encapsula varios ajustes y opciones que pueden usarse para aplicar medidas de seguridad a un documento PDF en el componente GroupDocs.Viewer. Estas opciones incluyen protección con contraseña, permisos y más. Para obtener más detalles, consulte la [documentation][].

Ejemplo de uso:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Security()](#Security--) | Inicializa una nueva instancia de la  Security  clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Obtiene la contraseña requerida para abrir el documento PDF. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Establece la contraseña requerida para abrir el documento PDF. |
| [getPermissionsPassword()](#getPermissionsPassword--) | Obtiene la contraseña requerida para cambiar la configuración de permisos. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Establece la contraseña requerida para cambiar la configuración de permisos. |
| [getPermissions()](#getPermissions--) | Obtiene los permisos del documento PDF, como imprimir, modificar y extraer datos. |
| [setPermissions(int value)](#setPermissions-int-) | Establece los permisos del documento PDF, como imprimir, modificar y extraer datos. |
### Security() {#Security--}
```
public Security()
```


Inicializa una nueva instancia de la  Security  clase.

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Obtiene la contraseña requerida para abrir el documento PDF.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - la contraseña de apertura del documento.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Establece la contraseña requerida para abrir el documento PDF.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | La contraseña de apertura del documento. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Obtiene la contraseña requerida para cambiar la configuración de permisos.

Usando una contraseña de permisos, puede restringir la impresión, la modificación y la extracción de datos. Use una contraseña de permisos para restringir la impresión, la modificación y la extracción de datos. Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - la contraseña de permisos.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Establece la contraseña requerida para cambiar la configuración de permisos.

Usando una contraseña de permisos, puede restringir la impresión, la modificación y la extracción de datos. Use una contraseña de permisos para restringir la impresión, la modificación y la extracción de datos. Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | La contraseña de permisos. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Obtiene los permisos del documento PDF, como imprimir, modificar y extraer datos.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - los permisos del documento PDF.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Establece los permisos del documento PDF, como imprimir, modificar y extraer datos.

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | Los permisos del documento PDF. |

