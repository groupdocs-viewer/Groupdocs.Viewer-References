---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bu istisna, bir dosya veya dizin bulunamadığında fırlatılır."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Bu istisna, bir dosya veya dizin bulunamadığında fırlatılır. Belirtilen dosya veya dizinin mevcut olmadığını veya erişilemediğini gösterir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Belirtilen mesajla FileNotFoundException sınıfının bir örneğini oluşturur. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Belirtilen dosya yolu ile FileNotFoundException sınıfının yeni bir örneğini başlatır. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Belirtilen hata mesajı ile FileNotFoundException sınıfının yeni bir örneğini oluşturur. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | FileNotFoundException sınıfının yeni bir örneğini oluşturur. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Belirtilen hata mesajı ile FileNotFoundException sınıfının yeni bir örneğini başlatır. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Belirtilen mesajla FileNotFoundException sınıfının bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hatayı açıklayan mesaj. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Belirtilen dosya yolu ile FileNotFoundException sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.nio.file.Path | Var olmayan dosyanın yolu. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Belirtilen hata mesajı ile FileNotFoundException sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| messageTemplate | java.lang.String | Hatayı açıklayan mesaj. |
| parametreler | java.lang.Object[] | Hata mesajına yerleştirilecek parametreler. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


FileNotFoundException sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| neden | java.lang.Throwable | İstisnanın nedeni. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Belirtilen hata mesajı ile FileNotFoundException sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesaj | java.lang.String | Hatayı açıklayan mesaj. |
| fırlatılabilir | java.lang.Throwable | İstisnaya neden olan fırlatılabilir. |

