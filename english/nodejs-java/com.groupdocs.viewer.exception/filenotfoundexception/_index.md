---
title: FileNotFoundException
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: This exception is thrown when a file or directory is not found.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

This exception is thrown when a file or directory is not found. It indicates that the specified file or directory does not exist or cannot be accessed.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Creates an instance of the FileNotFoundException class with the specified message. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Initializes a new instance of the FileNotFoundException class with a specified file path. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Creates a new instance of the FileNotFoundException class with a specified error message. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Instantiates a new instance of the FileNotFoundException class. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the FileNotFoundException class with a specified error message. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Creates an instance of the FileNotFoundException class with the specified message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Initializes a new instance of the FileNotFoundException class with a specified file path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.nio.file.Path | The path of the file that does not exist. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Creates a new instance of the FileNotFoundException class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageTemplate | java.lang.String | The message that describes the error. |
| params | java.lang.Object[] | The parameters that will be set into the error message. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Instantiates a new instance of the FileNotFoundException class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cause | java.lang.Throwable | The cause of the exception. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Initializes a new instance of the FileNotFoundException class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error. |
| throwable | java.lang.Throwable | The throwable that caused the exception. |

