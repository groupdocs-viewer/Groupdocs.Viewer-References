---
title: "FileName"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bir arşivdeki dosyanın adını temsil eder."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Bir arşivdeki dosyanın adını temsil eder.

FileName sınıfı, bir dosyanın yol veya dizin bilgisi olmadan adını kapsüller. Dosya adıyla ilgili bilgileri manipüle etmek ve almak için yöntemler sağlar.

Örnek kullanım:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | FileName sınıfının yeni bir örneğini başlatır. |
## Fields

| Field | Açıklama |
| --- | --- |
| [EMPTY](#EMPTY) | Boş bir dosya adını temsil eder. |
| [SOURCE](#SOURCE) | Kaynak dosyanın adını temsil eder. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | Geçerli nesnenin string temsilini döndürür. |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


FileName sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Dosyanın adı. |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Boş bir dosya adını temsil eder.

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Kaynak dosyanın adını temsil eder.

### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Geçerli nesnenin string temsilini döndürür.

**Returns:**
java.lang.String - geçerli nesnenin string temsili.
