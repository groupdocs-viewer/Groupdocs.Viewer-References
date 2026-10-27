---
title: "Permissions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Define permisos de documentos PDF."
type: docs
weight: 24
url: /es/nodejs-java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Define permisos de documentos PDF.

La clase Permissions proporciona constantes que representan diferentes permisos que pueden aplicarse a un documento PDF en el componente GroupDocs.Viewer. Estos permisos controlan las acciones que pueden realizarse sobre el documento PDF, como imprimir, copiar texto, modificar anotaciones y más.

Ejemplo de uso:

```

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Fields

| Field | Descripción |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Permitir impresión, modificación y extracción de datos. |
| [DENY_PRINTING](#DENY-PRINTING) | Denegar impresión. |
| [DENY_MODIFICATION](#DENY-MODIFICATION) | Denegar la modificación de contenido, rellenar formularios, agregar o modificar anotaciones. |
| [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Denegar la extracción de texto y gráficos. |
| [DENY_ALL](#DENY-ALL) | Denegar impresión, modificación y extracción de datos. |
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Permitir impresión, modificación y extracción de datos.

### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Denegar impresión.

### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Denegar la modificación de contenido, rellenar formularios, agregar o modificar anotaciones.

### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Denegar la extracción de texto y gráficos.

### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Denegar impresión, modificación y extracción de datos.

