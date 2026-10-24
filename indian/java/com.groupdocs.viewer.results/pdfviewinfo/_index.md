---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "PDF दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 24
url: /hi/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

PDF दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।


PdfViewInfo इंटरफ़ेस व्यू जानकारी तक पहुँचने और उसे संशोधित करने के लिए अनुबंध को परिभाषित करता है।
GroupDocs.Viewer घटक में PDF दस्तावेज़ के लिए। यह जानकारी प्राप्त करने के लिए मेथड्स प्रदान करता है।
जैसे प्रिंटिंग की अनुमति देना, और अन्य प्रॉपर्टीज़।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## Methods

| Method | विवरण |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | जाँचता है कि दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं। |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं सेट करता है। |
|
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


जाँचता है कि दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं।


**Returns:**
boolean - यदि प्रिंटिंग की अनुमति है तो true, अन्यथा false।

### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | allowPrinting | boolean | प्रिंटिंग की अनुमति के लिए true, अन्यथा false। |
|

