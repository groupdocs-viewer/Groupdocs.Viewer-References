---
title: "PasswordRequiredException"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "此异常在加载文档需要密码时抛出。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.viewer.exception/passwordrequiredexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class PasswordRequiredException extends GroupDocsViewerException
```

当加载文档需要密码时会抛出此异常。当尝试在未提供有效密码的情况下加载或打开已加密或受密码保护的文档时，通常会出现此异常。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PasswordRequiredException()](#PasswordRequiredException--) | 初始化 PasswordRequiredException 类的新实例。 |
| [PasswordRequiredException(String message)](#PasswordRequiredException-java.lang.String-) | 使用自定义异常消息初始化 PasswordRequiredException 类的新实例。 |
| [PasswordRequiredException(String message, Throwable throwable)](#PasswordRequiredException-java.lang.String-java.lang.Throwable-) | 使用指定的错误消息初始化 PasswordRequiredException 类的新实例。 |
### PasswordRequiredException() {#PasswordRequiredException--}
```
public PasswordRequiredException()
```


初始化 PasswordRequiredException 类的新实例。

### PasswordRequiredException(String message) {#PasswordRequiredException-java.lang.String-}
```
public PasswordRequiredException(String message)
```


使用自定义异常消息初始化 PasswordRequiredException 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String |  |

### PasswordRequiredException(String message, Throwable throwable) {#PasswordRequiredException-java.lang.String-java.lang.Throwable-}
```
public PasswordRequiredException(String message, Throwable throwable)
```


使用指定的错误消息初始化 PasswordRequiredException 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 该消息。 |
| Throwable | java.lang.Throwable | 该 Throwable。 |

