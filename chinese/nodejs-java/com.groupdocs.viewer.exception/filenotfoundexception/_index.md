---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "此异常在未找到文件或目录时抛出。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

当未找到文件或目录时会抛出此异常。它表示指定的文件或目录不存在或无法访问。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | 使用指定的消息创建 FileNotFoundException 类的实例。 |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | 使用指定的文件路径初始化 FileNotFoundException 类的新实例。 |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | 使用指定的错误消息创建 FileNotFoundException 类的新实例。 |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | 实例化 FileNotFoundException 类的新实例。 |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | 使用指定的错误消息初始化 FileNotFoundException 类的新实例。 |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


使用指定的消息创建 FileNotFoundException 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 描述错误的消息。 |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


使用指定的文件路径初始化 FileNotFoundException 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.nio.file.Path | 不存在的文件的路径。 |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


使用指定的错误消息创建 FileNotFoundException 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| messageTemplate | java.lang.String | 描述错误的消息。 |
| 参数 | java.lang.Object[] | 将设置到错误消息中的参数。 |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


实例化 FileNotFoundException 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 原因 | java.lang.Throwable | 异常的原因。 |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


使用指定的错误消息初始化 FileNotFoundException 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 描述错误的消息。 |
| Throwable | java.lang.Throwable | 导致异常的 Throwable。 |

