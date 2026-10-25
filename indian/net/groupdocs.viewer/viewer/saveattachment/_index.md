---
title: "SaveAttachment"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "संलग्न फ़ाइल को गंतव्य स्ट्रीम में सहेजता है।"
type: docs
weight: 70
url: /hi/net/groupdocs.viewer/viewer/saveattachment/
---

## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

अटैचमेंट फ़ाइल को *destination* स्ट्रीम में सहेजता है।

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| attachment | Attachment | संलग्न फ़ाइल। |
| destination | Stream | लिखने योग्य स्ट्रीम। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *attachment* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *destination* null हो तो फेंका जाता है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | जब attachment नहीं मिल पाती है तो फेंका जाता है। |

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

## SaveAttachment(Attachment, Stream) {#saveattachment}

अटैचमेंट फ़ाइल को *destination* स्ट्रीम में सहेजता है।

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| attachment | Attachment | संलग्न फ़ाइल। |
| destination | Stream | लिखने योग्य स्ट्रीम। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *attachment* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *destination* null हो तो फेंका जाता है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | जब attachment नहीं मिल पाती है तो फेंका जाता है। |

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
