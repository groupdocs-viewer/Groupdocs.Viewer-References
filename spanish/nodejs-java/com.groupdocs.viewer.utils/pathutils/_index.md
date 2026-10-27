---
title: "PathUtils"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "La clase PathUtils proporciona métodos de utilidad para trabajar con rutas de archivo."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

La clase PathUtils proporciona métodos de utilidad para trabajar con rutas de archivo.

La clase PathUtils contiene métodos estáticos que le permiten realizar varias operaciones sobre rutas de archivo en el componente GroupDocs.Viewer.

Ejemplo de uso:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Métodos

| Método | Descripción |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Combina partes de rutas usando el separador. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Obtiene el nombre del archivo. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Combina partes de rutas usando el separador.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parámetros | java.lang.String[] | las partes de las rutas |

**Returns:**
java.lang.String - la ruta resultante
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Obtiene el nombre del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | la ruta |

**Returns:**
java.lang.String - el nombre del archivo
