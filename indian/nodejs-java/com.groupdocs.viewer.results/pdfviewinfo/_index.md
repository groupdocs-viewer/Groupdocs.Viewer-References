---
title: "PdfViewInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "PDF दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 22
url: /hi/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

PDF दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।

PdfViewInfo इंटरफ़ेस GroupDocs.Viewer घटक में PDF दस्तावेज़ के लिए दृश्य जानकारी तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है। यह प्रिंटिंग की अनुमति जैसी जानकारी और अन्य गुणों को प्राप्त करने के लिए विधियाँ प्रदान करता है।

उदाहरण उपयोग:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | जाँचता है कि दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं। |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं, इसे सेट करता है। |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


जाँचता है कि दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं।

**Returns:**
boolean -  true  यदि प्रिंटिंग की अनुमति है,  false  अन्यथा।
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


दस्तावेज़ की प्रिंटिंग की अनुमति है या नहीं, इसे सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| allowPrinting | boolean | true  प्रिंटिंग की अनुमति देने के लिए,  false  अन्यथा। |

