---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل معلومات العرض لمستند PDF."
type: docs
weight: 24
url: /ar/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

يمثل معلومات العرض لمستند PDF.


واجهة PdfViewInfo تحدد العقد للوصول إلى معلومات العرض ومعالجتها.
لمستند PDF في مكوّن GroupDocs.Viewer. توفر طرقًا لاسترجاع المعلومات.
مثل السماح بالطباعة، وغيرها من الخصائص.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | يتحقق مما إذا كان طباعة المستند مسموحًا بها. |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | يضبط ما إذا كان طباعة المستند مسموحًا بها. |
|
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


يتحقق مما إذا كان طباعة المستند مسموحًا بها.


**Returns:**
منطقية -  true  إذا كان الطباعة مسموحًا بها،  false  غير ذلك.

### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


يضبط ما إذا كان طباعة المستند مسموحًا بها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | allowPrinting | boolean | true  للسماح بالطباعة،  false  غير ذلك. |
|

