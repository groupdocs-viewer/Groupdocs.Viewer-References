---
title: "GetViewInfo"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "व्यू और दस्तावेज़-विशिष्ट जानकारी के बारे में जानकारी लौटाता है।"
type: docs
weight: 60
url: /hi/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

व्यू और दस्तावेज़-विशिष्ट जानकारी के बारे में जानकारी लौटाता है।

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | ViewInfoOptions | व्यू जानकारी विकल्प। |

### वापसी मान

व्यू और दस्तावेज़-विशिष्ट जानकारी के बारे में जानकारी।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *options* null हो तो फेंका जाता है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### संबंधित देखें

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

व्यू और दस्तावेज़-विशिष्ट जानकारी के बारे में जानकारी लौटाता है।

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | ViewInfoOptions | व्यू जानकारी विकल्प। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### वापसी मान

व्यू और दस्तावेज़-विशिष्ट जानकारी के बारे में जानकारी।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *options* null हो तो फेंका जाता है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### संबंधित देखें

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
