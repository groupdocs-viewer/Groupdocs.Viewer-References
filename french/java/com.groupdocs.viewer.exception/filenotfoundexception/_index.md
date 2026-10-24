---
title: "FileNotFoundException"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Cette exception est levée lorsqu'un fichier ou un répertoire est introuvable."
type: docs
weight: 11
url: /fr/java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Cette exception est levée lorsqu'un fichier ou un répertoire est introuvable. Elle indique que le fichier ou le répertoire spécifié n'existe pas ou ne peut pas être accédé.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Crée une instance de la classe FileNotFoundException avec le message spécifié. |
|
|  | [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Initialise une nouvelle instance de la classe FileNotFoundException avec un chemin de fichier spécifié. |
|
|  | [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Crée une nouvelle instance de la classe FileNotFoundException avec un message d'erreur spécifié. |
|
|  | [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Instancie une nouvelle instance de la classe FileNotFoundException. |
|
|  | [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Initialise une nouvelle instance de la classe FileNotFoundException avec un message d'erreur spécifié. |
|
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Crée une instance de la classe FileNotFoundException avec le message spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message qui décrit l'erreur. |
|

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Initialise une nouvelle instance de la classe FileNotFoundException avec un chemin de fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | chemin | java.nio.file.Path | Le chemin du fichier qui n'existe pas. |
|

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Crée une nouvelle instance de la classe FileNotFoundException avec un message d'erreur spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | messageTemplate | java.lang.String | Le message qui décrit l'erreur. |
|
|  | paramètres | java.lang.Object[] | Les paramètres qui seront insérés dans le message d'erreur. |
|

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Instancie une nouvelle instance de la classe FileNotFoundException.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | cause | java.lang.Throwable | La cause de l'exception. |
|

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Initialise une nouvelle instance de la classe FileNotFoundException avec un message d'erreur spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message qui décrit l'erreur. |
|
|  | throwable | java.lang.Throwable | Le throwable qui a causé l'exception. |
|

