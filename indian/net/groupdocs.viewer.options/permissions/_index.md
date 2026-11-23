---
title: "अनुमतियाँ"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "PDF दस्तावेज़ अनुमतियों को परिभाषित करता है।"
type: docs
weight: 430
url: /hi/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

PDF दस्तावेज़ अनुमतियों को परिभाषित करता है।

```csharp
[Flags]
public enum Permissions
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| AllowAll | `0` | प्रिंटिंग, संशोधन और डेटा निष्कर्षण की अनुमति दें। |
| DenyPrinting | `1` | प्रिंटिंग को अस्वीकार करें। |
| DenyModification | `2` | सामग्री संशोधन, फ़ॉर्म भरना, एनोटेशन जोड़ना या संशोधित करना अस्वीकार करें। |
| DenyDataExtraction | `4` | टेक्स्ट और ग्राफ़िक्स निष्कर्षण को अस्वीकार करें। |
| DenyAll | `7` | प्रिंटिंग, सामग्री संशोधन और डेटा निष्कर्षण को अस्वीकार करें। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
