---
title: "IsSearchTermRegEx"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि खोज शब्द को नियमित अभिव्यक्ति के रूप में या साधारण पाठ के रूप में माना जाना चाहिए। डिफ़ॉल्ट रूप से false है, अर्थात साधारण पाठ के रूप में माना जाता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.viewer.options/searchhighlightoptions/issearchtermregex/
---

## SearchHighlightOptions.IsSearchTermRegEx property

एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि खोज शब्द को नियमित अभिव्यक्ति के रूप में या टेक्स्ट लिटरल के रूप में माना जाना चाहिए। डिफ़ॉल्ट `false` है — इसे टेक्स्ट लिटरल के रूप में मानें।

```csharp
public bool IsSearchTermRegEx { get; set; }
```

### टिप्पणियाँ

यदि `true` है, तो [`SearchTerm`](../searchterm) को .NET Regex पैटर्न के रूप में व्याख्यायित किया जाता है।

यदि `false` है, तो दस्तावेज़ में [`SearchTerm`](../searchterm) को साधारण पाठ के रूप में खोजा जाता है।

### संबंधित देखें

* class [SearchHighlightOptions](../../searchhighlightoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
