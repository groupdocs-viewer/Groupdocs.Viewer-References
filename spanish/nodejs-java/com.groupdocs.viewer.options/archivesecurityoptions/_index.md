---
title: "ArchiveSecurityOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Clase que puede usarse para limitar el proceso de extracción de archivos."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Clase que puede usarse para limitar el proceso de extracción de archivos.

La clase ArchiveSecurityOptions proporciona una forma de limitar la extracción de archivos y aplicar ciertas restricciones.

Ejemplo de uso:

```

 ArchiveSecurityOptions securityOptions = new ArchiveSecurityOptions();
 securityOptions.setMaxAllowedEntryNameLength(255);
 securityOptions.setMaxAllowedEntrySize(10737418240L);
 securityOptions.setMaxAllowedEntriesCount(1000);
 securityOptions.setMaxAllowedEntryCompressionRatio(100);

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setArchiveSecurityOptions(securityOptions);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** Not each archive type supports all options.*
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Esta opción especifica la longitud máxima que puede tener el nombre de una entrada de archivo. |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Establece la longitud máxima permitida para los nombres de entradas de archivo. |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Obtiene el tamaño máximo permitido para las entradas de archivo. |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Establece el tamaño máximo permitido para las entradas de archivo. |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Obtiene la cantidad máxima permitida de entradas en un archivo. |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Establece la cantidad máxima permitida de entradas en un archivo. |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Especifica la relación de compresión máxima permitida para extraer entradas de archivo. |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Especifica la relación de compresión máxima permitida para extraer entradas de archivo. |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Esta opción especifica la longitud máxima que puede tener el nombre de una entrada de archivo. Si el nombre de una entrada supera este límite, provocará un error.

***Note:** The default value for this option is 255.*

**Returns:**
int - la longitud máxima permitida para los nombres de entradas de archivo.
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Establece la longitud máxima permitida para los nombres de entradas del archivo. La longitud máxima permitida especifica el límite para la longitud de un nombre de entrada del archivo. Si la longitud de un nombre de entrada supera este límite, provocará un error.

***Note:** The default value for the maximum allowed entry name length is 255.*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | La longitud máxima del nombre de entrada del archivo que se establecerá. |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Obtiene el tamaño máximo permitido para las entradas del archivo. El tamaño máximo permitido de la entrada especifica el límite para el tamaño de una entrada del archivo. Si el tamaño de una entrada supera este límite, resultará en un error.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Returns:**
long - el tamaño máximo de la entrada del archivo.
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Establece el tamaño máximo permitido para las entradas del archivo. El tamaño máximo permitido de la entrada especifica el límite para el tamaño de una entrada del archivo. Si el tamaño de una entrada supera este límite, resultará en un error.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxAllowedEntrySize | long | El tamaño máximo de la entrada del archivo. |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Obtiene el recuento máximo permitido de entradas en un archivo. El recuento máximo permitido de entradas especifica el límite para el número de entradas que un archivo puede contener. Si un archivo contiene más entradas que este límite, no podrá extraerse.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Returns:**
long - el recuento máximo de entradas en un archivo.
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Establece el recuento máximo permitido de entradas en un archivo. El recuento máximo permitido de entradas especifica el límite para el número de entradas que un archivo puede contener. Si un archivo contiene más entradas que este límite, no podrá extraerse.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxAllowedEntriesCount | long | El recuento máximo de entradas en un archivo. |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Especifica la relación de compresión máxima permitida para extraer entradas de archivo.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Returns:**
double - la relación de compresión máxima permitida para las entradas del archivo.
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Especifica la relación de compresión máxima permitida para extraer entradas de archivo.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | La relación de compresión máxima permitida para las entradas del archivo. |

