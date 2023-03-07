---
title: Permissions
second_title: .NET API संदर्भ के लिए GroupDocs.Viewer
description: पडएफ दस्तवेज़ अनुमतयं क परभषत करत है
type: docs
weight: 430
url: /hi/net/groupdocs.viewer.options/permissions/
---
## Permissions enumeration

पीडीएफ दस्तावेज़ अनुमतियों को परिभाषित करता है।

```csharp
[Flags]
public enum Permissions
```

### मान

| नाम | कीमत | विवरण |
| --- | --- | --- |
| AllowAll | `0` | मुद्रण, संशोधन और डेटा निष्कर्षण की अनुमति दें। |
| DenyPrinting | `1` | प्रिंटिंग अस्वीकार करें |
| DenyModification | `2` | सामग्री को संशोधित करने, फॉर्म भरने, एनोटेशन जोड़ने या संशोधित करने से इनकार करें। |
| DenyDataExtraction | `4` | पाठ और ग्राफिक्स निष्कर्षण से इनकार करें। |
| DenyAll | `7` | मुद्रण, संशोधन और डेटा निष्कर्षण से इनकार करें। |

### यह सभी देखें

* नाम स्थान [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* सभा [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->