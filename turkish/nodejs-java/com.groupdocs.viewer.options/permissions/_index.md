---
title: "Permissions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "PDF belge izinlerini tanımlar."
type: docs
weight: 24
url: /tr/nodejs-java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

PDF belge izinlerini tanımlar.

Permissions sınıfı, GroupDocs.Viewer bileşeninde bir PDF belgesine uygulanabilecek farklı izinleri temsil eden sabitler sağlar. Bu izinler, PDF belgesi üzerinde yapılabilecek işlemleri, örneğin yazdırma, metin kopyalama, ek açıklamaları değiştirme ve daha fazlasını kontrol eder.

Örnek kullanım:

```

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Fields

| Field | Açıklama |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Yazdırma, değiştirme ve veri çıkarımına izin ver. |
| [DENY_PRINTING](#DENY-PRINTING) | Yazdırmayı reddet. |
| [DENY_MODIFICATION](#DENY-MODIFICATION) | İçerik değişikliğini, form doldurmayı, ek açıklama eklemeyi veya değiştirmeyi reddet. |
| [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Metin ve grafik çıkarımını reddet. |
| [DENY_ALL](#DENY-ALL) | Yazdırma, değiştirme ve veri çıkarımını reddet. |
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Yazdırma, değiştirme ve veri çıkarımına izin ver.

### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Yazdırmayı reddet.

### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


İçerik değişikliğini, form doldurmayı, ek açıklama eklemeyi veya değiştirmeyi reddet.

### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Metin ve grafik çıkarımını reddet.

### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Yazdırma, değiştirme ve veri çıkarımını reddet.

