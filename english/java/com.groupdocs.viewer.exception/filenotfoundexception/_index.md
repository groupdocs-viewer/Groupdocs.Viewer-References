---
title: FileNotFoundException
second_title: GroupDocs.Viewer for Java API Reference
description: Represents the the exception that throws when file or directory was not found.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Represents the the exception that throws when file or directory was not found.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Initializes a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class with a specified error message. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Initializes a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class with a specified error message. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Initializes a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class with a specified error message. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Instantiates a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Initializes a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class with a specified error message. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Initializes a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message that describes the error. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Initializes a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.nio.file.Path | The path of file that does not exist |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Initializes a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageTemplate | java.lang.String | The message that describes the error. |
| params | java.lang.Object[] | The params which will be set into error message. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Instantiates a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cause | java.lang.Throwable | the cause |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Initializes a new instance of the [FileNotFoundException](../../com.groupdocs.viewer.exception/filenotfoundexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The message. |
| throwable | java.lang.Throwable | The throwable. |

