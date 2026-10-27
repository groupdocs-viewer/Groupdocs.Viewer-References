---
title: "Döndürme"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Sayfa döndürmesini saat yönünde derece cinsinden içerir."
type: docs
weight: 45
url: /tr/nodejs-java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Sayfa dönüşünü derece cinsinden (saat yönünde) içerir.

Rotation enum'ı, GroupDocs.Viewer bileşenindeki bir sayfa için farklı döndürme açılarını temsil eder. Sayfayı çeşitli belge görüntüleme veya dönüştürme senaryolarında render etmek için döndürme açısını belirtmek amacıyla kullanılabilecek önceden tanımlanmış bir dizi döndürme seçeneği sağlar.

Örnek kullanım:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Açıklama |
| --- | --- |
| [ON_90_DEGREE](#ON-90-DEGREE) | 90 derecelik sayfa döndürmesi. |
| [ON_180_DEGREE](#ON-180-DEGREE) | 180 derecelik sayfa döndürmesi. |
| [ON_270_DEGREE](#ON-270-DEGREE) | 270 derecelik sayfa döndürmesi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


90 derecelik sayfa döndürmesi. Bu döndürme, sayfanın saat yönünde 90 derece döndürülmesini temsil eder.

### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


180 derecelik sayfa döndürmesi. Bu döndürme, sayfanın saat yönünde 180 derece döndürülmesini temsil eder.

### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


270 derecelik sayfa döndürmesi. Bu döndürme, sayfanın saat yönünde 270 derece döndürülmesini temsil eder.

### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
