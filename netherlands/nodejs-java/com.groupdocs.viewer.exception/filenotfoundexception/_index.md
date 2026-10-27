---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Deze uitzondering wordt gegooid wanneer een bestand of map niet wordt gevonden."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Deze uitzondering wordt gegooid wanneer een bestand of map niet wordt gevonden. Het geeft aan dat het opgegeven bestand of de opgegeven map niet bestaat of niet toegankelijk is.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Maakt een instantie van de FileNotFoundException‑klasse met het opgegeven bericht. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Initialiseert een nieuwe instantie van de FileNotFoundException‑klasse met een opgegeven bestandspad. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Maakt een nieuwe instantie van de FileNotFoundException‑klasse met een opgegeven foutbericht. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Instantieert een nieuwe instantie van de FileNotFoundException‑klasse. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Initialiseert een nieuwe instantie van de FileNotFoundException‑klasse met een opgegeven foutbericht. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Maakt een instantie van de FileNotFoundException‑klasse met het opgegeven bericht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het bericht dat de fout beschrijft. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Initialiseert een nieuwe instantie van de FileNotFoundException‑klasse met een opgegeven bestandspad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.nio.file.Path | Het pad van het bestand dat niet bestaat. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Maakt een nieuwe instantie van de FileNotFoundException‑klasse met een opgegeven foutbericht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| messageTemplate | java.lang.String | Het bericht dat de fout beschrijft. |
| params | java.lang.Object[] | De parameters die in het foutbericht worden geplaatst. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Instantieert een nieuwe instantie van de FileNotFoundException‑klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oorzaak | java.lang.Throwable | De oorzaak van de uitzondering. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Initialiseert een nieuwe instantie van de FileNotFoundException‑klasse met een opgegeven foutbericht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het bericht dat de fout beschrijft. |
| throwable | java.lang.Throwable | De throwable die de uitzondering veroorzaakte. |

