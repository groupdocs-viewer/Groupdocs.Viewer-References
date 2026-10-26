---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Diese Ausnahme wird ausgelöst, wenn eine Datei oder ein Verzeichnis nicht gefunden wird."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Diese Ausnahme wird ausgelöst, wenn eine Datei oder ein Verzeichnis nicht gefunden wird. Sie zeigt an, dass die angegebene Datei oder das Verzeichnis nicht existiert oder nicht zugänglich ist.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Erstellt eine Instanz der Klasse FileNotFoundException mit der angegebenen Meldung. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Initialisiert eine neue Instanz der Klasse FileNotFoundException mit einem angegebenen Dateipfad. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Erstellt eine neue Instanz der Klasse FileNotFoundException mit einer angegebenen Fehlermeldung. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Instanziiert eine neue Instanz der Klasse FileNotFoundException. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Initialisiert eine neue Instanz der Klasse FileNotFoundException mit einer angegebenen Fehlermeldung. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Erstellt eine Instanz der Klasse FileNotFoundException mit der angegebenen Meldung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Nachricht, die den Fehler beschreibt. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Initialisiert eine neue Instanz der Klasse FileNotFoundException mit einem angegebenen Dateipfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.nio.file.Path | Der Pfad der Datei, die nicht existiert. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Erstellt eine neue Instanz der Klasse FileNotFoundException mit einer angegebenen Fehlermeldung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| messageTemplate | java.lang.String | Die Nachricht, die den Fehler beschreibt. |
| params | java.lang.Object[] | Die Parameter, die in die Fehlermeldung eingesetzt werden. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Instanziiert eine neue Instanz der Klasse FileNotFoundException.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ursache | java.lang.Throwable | Die Ursache der Ausnahme. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Initialisiert eine neue Instanz der Klasse FileNotFoundException mit einer angegebenen Fehlermeldung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nachricht | java.lang.String | Die Nachricht, die den Fehler beschreibt. |
| throwable | java.lang.Throwable | Das Throwable, das die Ausnahme verursacht hat. |

