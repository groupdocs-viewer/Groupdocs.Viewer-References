---
title: "PathUtils"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "PathUtils sınıfı, dosya yolları ile çalışmak için yardımcı yöntemler sağlar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

PathUtils sınıfı, dosya yolları ile çalışmak için yardımcı yöntemler sağlar.

PathUtils sınıfı, GroupDocs.Viewer bileşenindeki dosya yolları üzerinde çeşitli işlemler yapmanıza olanak tanıyan statik yöntemler içerir.

Örnek kullanım:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Ayırıcı kullanarak yol bölümlerini birleştir. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Dosya adını alır. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Ayırıcı kullanarak yol bölümlerini birleştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parametreler | java.lang.String[] | yol bölümleri |

**Returns:**
java.lang.String - sonuç yolu
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Dosya adını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | yol |

**Returns:**
java.lang.String - dosya adı
