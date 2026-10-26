---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Questa eccezione viene sollevata quando un file o una directory non viene trovato."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Questa eccezione viene sollevata quando un file o una directory non viene trovato. Indica che il file o la directory specificati non esistono o non possono essere accessi.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Crea un'istanza della classe FileNotFoundException con il messaggio specificato. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Inizializza una nuova istanza della classe FileNotFoundException con un percorso file specificato. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Crea una nuova istanza della classe FileNotFoundException con un messaggio di errore specificato. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Istanzia una nuova istanza della classe FileNotFoundException. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Inizializza una nuova istanza della classe FileNotFoundException con un messaggio di errore specificato. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Crea un'istanza della classe FileNotFoundException con il messaggio specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio che descrive l'errore. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Inizializza una nuova istanza della classe FileNotFoundException con un percorso file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.nio.file.Path | Il percorso del file che non esiste. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Crea una nuova istanza della classe FileNotFoundException con un messaggio di errore specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageTemplate | java.lang.String | Il messaggio che descrive l'errore. |
| params | java.lang.Object[] | I parametri che verranno inseriti nel messaggio di errore. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Istanzia una nuova istanza della classe FileNotFoundException.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| causa | java.lang.Throwable | La causa dell'eccezione. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Inizializza una nuova istanza della classe FileNotFoundException con un messaggio di errore specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messaggio | java.lang.String | Il messaggio che descrive l'errore. |
| Throwable | java.lang.Throwable | Il Throwable che ha causato l'eccezione. |

