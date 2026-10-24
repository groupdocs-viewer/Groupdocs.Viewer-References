---
title: "Permissions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mendefinisikan izin dokumen PDF."
type: docs
weight: 24
url: /id/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Mendefinisikan izin dokumen PDF.


Kelas Permissions menyediakan konstanta yang mewakili berbagai izin
yang dapat diterapkan pada dokumen PDF dalam komponen GroupDocs.Viewer.
Izin-izin ini mengontrol tindakan yang dapat dilakukan pada dokumen PDF,
seperti mencetak, menyalin teks, memodifikasi anotasi, dan lainnya.


Contoh penggunaan:

````

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | Izinkan pencetakan, modifikasi, dan ekstraksi data. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | Tolak pencetakan. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | Tolak modifikasi konten, mengisi formulir, menambah atau memodifikasi anotasi. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Tolak ekstraksi teks dan grafik. |
|
|  | [DENY_ALL](#DENY-ALL) | Tolak pencetakan, modifikasi, dan ekstraksi data. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Izinkan pencetakan, modifikasi, dan ekstraksi data.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Tolak pencetakan.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Tolak modifikasi konten, mengisi formulir, menambah atau memodifikasi anotasi.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Tolak ekstraksi teks dan grafik.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Tolak pencetakan, modifikasi, dan ekstraksi data.


