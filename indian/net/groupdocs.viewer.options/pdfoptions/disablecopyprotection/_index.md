---
title: "DisableCopyProtection"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "HTML में रेंडर करते समय सामग्री कॉपी सुरक्षा को बंद करता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

HTML में रेंडर करते समय सामग्री कॉपी सुरक्षा को बंद करता है।

```csharp
public bool DisableCopyProtection { get; set; }
```

### टिप्पणियाँ

जब PDF फ़ाइलों को HTML में रेंडर किया जाता है और टेक्स्ट व छवियों की कॉपी से सुरक्षा होती है, तो GroupDocs.Viewer HTML BODY टैग में एक 'inert' HTML एट्रिब्यूट जोड़ता है। इस विकल्प का डिफ़ॉल्ट मान `false` है, जो दर्शाता है कि 'intent' HTML एट्रिब्यूट केवल तब जोड़ा जाता है जब PDF दस्तावेज़ संरक्षित हो।

कोड उदाहरण के लिए, देखें [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).

### संबंधित देखें

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
