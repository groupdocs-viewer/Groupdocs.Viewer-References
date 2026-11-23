---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Detta undantag kastas när en fil eller katalog inte hittas."
type: docs
weight: 11
url: /sv/java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Detta undantag kastas när en fil eller katalog inte hittas. Det indikerar att den angivna filen eller katalogen inte finns eller inte kan nås.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Skapar en instans av klassen FileNotFoundException med det specificerade meddelandet. |
|
|  | [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Initierar en ny instans av klassen FileNotFoundException med en specificerad filsökväg. |
|
|  | [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Skapar en ny instans av klassen FileNotFoundException med ett specificerat felmeddelande. |
|
|  | [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Instansierar en ny instans av klassen FileNotFoundException. |
|
|  | [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Initierar en ny instans av klassen FileNotFoundException med ett specificerat felmeddelande. |
|
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Skapar en instans av klassen FileNotFoundException med det specificerade meddelandet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Meddelandet som beskriver felet. |
|

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Initierar en ny instans av klassen FileNotFoundException med en specificerad filsökväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | sökväg | java.nio.file.Path | Sökvägen till filen som inte finns. |
|

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Skapar en ny instans av klassen FileNotFoundException med ett specificerat felmeddelande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | messageTemplate | java.lang.String | Meddelandet som beskriver felet. |
|
|  | parametrar | java.lang.Object[] | Parametrarna som kommer att sättas in i felmeddelandet. |
|

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Instansierar en ny instans av klassen FileNotFoundException.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | orsak | java.lang.Throwable | Orsaken till undantaget. |
|

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Initierar en ny instans av klassen FileNotFoundException med ett specificerat felmeddelande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Meddelandet som beskriver felet. |
|
|  | kastbar | java.lang.Throwable | Det kastbara objektet som orsakade undantaget. |
|

