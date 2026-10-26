---
title: "PathUtils"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "La classe PathUtils fornisce metodi di utilità per lavorare con i percorsi dei file."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

La classe PathUtils fornisce metodi di utilità per lavorare con i percorsi dei file.

La classe PathUtils contiene metodi statici che consentono di eseguire varie operazioni sui percorsi dei file nel componente GroupDocs.Viewer.

Esempio di utilizzo:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Combina le parti del percorso usando il separatore. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Ottiene il nome del file. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Combina le parti del percorso usando il separatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| params | java.lang.String[] | le parti del percorso |

**Returns:**
java.lang.String - il percorso risultante
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Ottiene il nome del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | il percorso |

**Returns:**
java.lang.String - il nome del file
