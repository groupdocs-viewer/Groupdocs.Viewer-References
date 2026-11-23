---
title: "DisableFontLicenseVerifications"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए किसी भी लाइसेंस प्रतिबंध को अक्षम करता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए किसी भी लाइसेंस प्रतिबंध को अक्षम करता है।

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### टिप्पणियाँ

फ़ॉन्ट के साथ कई ऑपरेशन तब निष्पादित नहीं किए जा सकते यदि वे इस फ़ॉन्ट के लाइसेंस द्वारा प्रतिबंधित हों। उदाहरण के लिए, कुछ फ़ॉन्ट को PDF दस्तावेज़ में एम्बेड नहीं किया जा सकता यदि लाइसेंस नियम एम्बेडिंग को निष्क्रिय कर देते हैं। यह विकल्प आपको इन नियमों की सत्यापन को छोड़ने की अनुमति देता है।

इस फ़्लैग का उपयोग करते समय सावधान रहें। जब इसे सेट किया जाता है, तो इसका अर्थ है कि फ़्लैग सेट करने वाला व्यक्ति संभावित लाइसेंस/कानून उल्लंघनों की पूरी ज़िम्मेदारी स्वयं लेता है। इसलिए यह उसका अपना जोखिम है। यह दृढ़ता से अनुशंसा की जाती है कि आप इस फ़्लैग का उपयोग केवल तभी करें जब आपको पूरी तरह यकीन हो कि आप कॉपीराइट कानून का उल्लंघन नहीं कर रहे हैं। डिफ़ॉल्ट मान `false` है।

कोड उदाहरण के लिए, देखें [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).

### संबंधित देखें

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
