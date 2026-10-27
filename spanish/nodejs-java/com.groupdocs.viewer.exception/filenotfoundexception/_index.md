---
title: "FileNotFoundException"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Esta excepción se lanza cuando no se encuentra un archivo o directorio."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Esta excepción se lanza cuando no se encuentra un archivo o directorio. Indica que el archivo o directorio especificado no existe o no se puede acceder.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Crea una instancia de la clase FileNotFoundException con el mensaje especificado. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Inicializa una nueva instancia de la clase FileNotFoundException con una ruta de archivo especificada. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Crea una nueva instancia de la clase FileNotFoundException con un mensaje de error especificado. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Instancia una nueva instancia de la clase FileNotFoundException. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Inicializa una nueva instancia de la clase FileNotFoundException con un mensaje de error especificado. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Crea una instancia de la clase FileNotFoundException con el mensaje especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje que describe el error. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Inicializa una nueva instancia de la clase FileNotFoundException con una ruta de archivo especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.nio.file.Path | La ruta del archivo que no existe. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Crea una nueva instancia de la clase FileNotFoundException con un mensaje de error especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| messageTemplate | java.lang.String | El mensaje que describe el error. |
| parámetros | java.lang.Object[] | Los parámetros que se establecerán en el mensaje de error. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Instancia una nueva instancia de la clase FileNotFoundException.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| causa | java.lang.Throwable | La causa de la excepción. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Inicializa una nueva instancia de la clase FileNotFoundException con un mensaje de error especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje que describe el error. |
| throwable | java.lang.Throwable | El throwable que causó la excepción. |

