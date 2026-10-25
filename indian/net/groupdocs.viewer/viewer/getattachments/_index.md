---
title: "GetAttachments"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "दस्तावेज़ में सम्मिलित अटैचमेंट्स को लौटाता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.viewer/viewer/getattachments/
---

## GetAttachments() {#getattachments}

दस्तावेज़ में सम्मिलित अटैचमेंट्स को लौटाता है।

```csharp
public IList<Attachment> GetAttachments()
```

### वापसी मान

दस्तावेज़ में शामिल संलग्नक।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### संबंधित देखें

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetAttachments(CancellationToken) {#getattachments_1}

दस्तावेज़ में सम्मिलित अटैचमेंट्स को लौटाता है।

```csharp
public IList<Attachment> GetAttachments(CancellationToken cancellationToken)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### वापसी मान

दस्तावेज़ में शामिल संलग्नक।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### संबंधित देखें

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
