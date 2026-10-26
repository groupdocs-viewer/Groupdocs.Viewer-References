---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili informasi tampilan untuk dokumen PDF."
type: docs
weight: 22
url: /id/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Mewakili informasi tampilan untuk dokumen PDF.

Antarmuka PdfViewInfo mendefinisikan kontrak untuk mengakses dan memanipulasi informasi tampilan untuk dokumen PDF dalam komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengambil informasi seperti mengizinkan pencetakan, dan properti lainnya.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | Memeriksa apakah pencetakan dokumen diizinkan. |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Mengatur apakah pencetakan dokumen diizinkan. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Memeriksa apakah pencetakan dokumen diizinkan.

**Returns:**
boolean -  true  jika pencetakan diizinkan,  false  jika tidak.
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Mengatur apakah pencetakan dokumen diizinkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowPrinting | boolean | true  untuk mengizinkan pencetakan,  false  jika tidak. |

