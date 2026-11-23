---
title: "ViewOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "रेंडरिंग विकल्पों को शामिल करता है।"
type: docs
weight: 590
url: /hi/net/groupdocs.viewer.options/viewoptions/
---

## ViewOptions class

रेंडरिंग विकल्पों को शामिल करता है।

```csharp
public abstract class ViewOptions : BaseViewOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | आर्काइव फ़ाइलों के दृश्य विकल्प। |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD ड्राइंग के दृश्य विकल्प। |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट सेट करता है। |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | ईमेल संदेशों के दृश्य विकल्प। |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | मेल स्टोरेज डेटा फ़ाइलों के दृश्य विकल्प। |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook डेटा फ़ाइलों के दृश्य विकल्प। |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF दस्तावेज़ के दृश्य विकल्प। |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | प्रेजेंटेशन फ़ाइलों के दृश्य विकल्प। |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | प्रोजेक्ट मैनेजमेंट फ़ाइलों के दृश्य विकल्प। |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | जब `true` पर सेट किया जाता है तो टिप्पणी रेंडरिंग को निष्क्रिय करता है। डिफ़ॉल्ट रूप से यह `false` है — सभी टिप्पणियाँ प्रदर्शित होती हैं। |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | छिपे पृष्ठों की रेंडरिंग को सक्षम करता है। |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | कुछ फ़ॉर्मैट्स के लिए नोट्स और एनोटेशन की रेंडरिंग को सक्षम करता है। |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | स्प्रेडशीट फ़ाइलों के दृश्य विकल्प। |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | टेक्स्ट फ़ाइलों के दृश्य विकल्प। |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio फ़ाइलों के दृश्य विकल्प। |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | प्रत्येक पृष्ठ पर लागू किया जाने वाला टेक्स्ट वॉटरमार्क। |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | वेब फ़ाइलों के दृश्य विकल्प। |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | वर्ड प्रोसेसिंग फ़ाइलों के दृश्य विकल्प। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | एक पृष्ठ पर घड़ी की दिशा में घुमाव लागू करता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | पृष्ठ घुमाव। |

### संबंधित देखें

* class [BaseViewOptions](../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
