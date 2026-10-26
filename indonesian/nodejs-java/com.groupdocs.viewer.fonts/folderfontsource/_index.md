---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili folder yang berisi font TrueType."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Mewakili folder yang berisi font TrueType.

Kelas FolderFontSource digunakan untuk menentukan lokasi folder yang berisi font TrueType. Ini memungkinkan API GroupDocs.Viewer mengakses font yang disimpan di folder yang ditentukan untuk keperluan rendering dokumen.

Contoh penggunaan:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Menginisialisasi instance baru dari kelas  FolderFontSource . |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Menentukan apakah dua objek  FolderFontSource  sama. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Menentukan apakah dua objek  FolderFontSource  tidak sama. |
| [getFolderPath()](#getFolderPath--) | Mendapatkan jalur ke folder yang berisi font TrueType. |
| [getSearchOption()](#getSearchOption--) | Mendapatkan opsi pencarian yang menentukan apakah mencari di folder saat ini, atau folder saat ini dan semua subfolder. |
| [isRecursive()](#isRecursive--) | Memeriksa apakah font akan dicari secara rekursif. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Menentukan apakah  FolderFontSource  saat ini sama dengan objek  FolderFontSource  yang ditentukan. |
| [equals(Object o)](#equals-java.lang.Object-) | Menentukan apakah  FolderFontSource  saat ini sama dengan objek yang ditentukan. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk objek  FolderFontSource  saat ini. |
| [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Menginisialisasi instance baru dari kelas  FolderFontSource .

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| folderPath | java.lang.String | Jalur ke folder yang berisi font TrueType. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Menentukan apakah mencari di folder saat ini, atau folder saat ini dan semua subfolder. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Menentukan apakah dua objek  FolderFontSource  sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Objek  FolderFontSource  kiri. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Objek  FolderFontSource  kanan. |

**Returns:**
boolean -  true  jika kedua objek  FolderFontSource  sama; jika tidak,  false .
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Menentukan apakah dua objek  FolderFontSource  tidak sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Objek  FolderFontSource  kiri. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Objek  FolderFontSource  kanan. |

**Returns:**
boolean -  true  jika kedua objek  FolderFontSource  tidak sama; jika tidak,  false .
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Mendapatkan jalur ke folder yang berisi font TrueType.

**Returns:**
java.lang.String - jalur ke folder yang berisi font TrueType.
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Mendapatkan opsi pencarian yang menentukan apakah mencari di folder saat ini, atau folder saat ini dan semua subfolder.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Memeriksa apakah font akan dicari secara rekursif.

**Returns:**
boolean -  true  jika font akan dicari secara rekursif,  false  jika tidak.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Menentukan apakah  FolderFontSource  saat ini sama dengan objek  FolderFontSource  yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Objek untuk dibandingkan dengan objek  FolderFontSource  saat ini. |

**Returns:**
boolean -  true  jika kedua objek  FolderFontSource  sama; jika tidak,  false
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Menentukan apakah  FolderFontSource  saat ini sama dengan objek yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| o | java.lang.Object | Objek untuk dibandingkan dengan objek  FolderFontSource  saat ini. |

**Returns:**
boolean -  true  jika parameter  obj  bertipe  FolderFontSource  dan sama dengan objek  FolderFontSource  saat ini; jika tidak,  false
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk objek  FolderFontSource  saat ini.

**Returns:**
int - kode hash untuk objek  FolderFontSource  saat ini.
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang mewakili objek saat ini.

**Returns:**
java.lang.String - string yang mewakili objek saat ini.
