---
title: "WrapImagesInSvg"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "आउटपुट क्वालिटी सुधारने के लिए आउटपुट HTML दस्तावेज़ में प्रत्येक इमेज को SVG टैग में रैप करने को सक्षम करता है।"
type: docs
weight: 110
url: /hi/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

आउटपुट क्वालिटी सुधारने के लिए आउटपुट HTML दस्तावेज़ में प्रत्येक इमेज को SVG टैग में रैप करने को सक्षम करता है।

```csharp
public bool WrapImagesInSvg { get; set; }
```

### टिप्पणियाँ

डिफ़ॉल्ट रूप से, PDF और पेज लेआउट फ़ाइलों को HTML में रेंडर करते समय सभी छवियों को एक PNG छवि के रूप में रेंडर किया जाता है। रेंडर की गई PNG छवि आउटपुट HTML दस्तावेज़ की पृष्ठभूमि के रूप में उपयोग की जाती है।

यह विकल्प [PDF और पेज लेआउट फ़ाइल स्वरूपों](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) को HTML में एम्बेडेड और बाहरी संसाधनों के साथ रेंडर करते समय उपलब्ध है। यह प्रत्येक छवि को आउटपुट HTML दस्तावेज़ में SVG टैग में लपेटने को सक्षम करता है। डिफ़ॉल्ट मान `false` है।

कोड उदाहरण के लिए, [दस्तावेज़ीकरण](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files) देखें।

### संबंधित देखें

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
