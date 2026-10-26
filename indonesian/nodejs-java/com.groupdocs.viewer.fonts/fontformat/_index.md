---
title: "FontFormat"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili semua format font yang mungkin ada dalam kelas UsedFontInfo."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Mewakili semua format font, yang mungkin ada dalam kelas UsedFontInfo.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Unknown](#Unknown) | Format font tidak diketahui atau tidak valid. |
| [TrueType](#TrueType) | Format font TrueType (TTF). |
| [OpenType](#OpenType) | Format font OpenType (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | Format font TrueType Collection (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Format font Embedded OpenType (EOT). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [toString(int format)](#toString-int-) | Mengonversi nilai format menjadi string yang dapat dibaca manusia. |
### Unknown {#Unknown}
```
public static final int Unknown
```


Format font tidak diketahui atau tidak valid.

### TrueType {#TrueType}
```
public static final int TrueType
```


Format font TrueType (TTF).

### OpenType {#OpenType}
```
public static final int OpenType
```


Format font OpenType (OTF).

### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


Format font TrueType Collection (TTC).

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Format font Embedded OpenType (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Mengonversi nilai format menjadi string yang dapat dibaca manusia.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | int | nilai format font |

**Returns:**
java.lang.String - representasi string dari format font
