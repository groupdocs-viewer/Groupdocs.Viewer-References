---
title: PngViewOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Viewer
description: दस्तवेज़ं क पएनज प्ररूप में प्रस्तुत करने के लए वकल्प प्रदन करत है
type: docs
weight: 440
url: /hi/net/groupdocs.viewer.options/pngviewoptions/
---
## PngViewOptions class

दस्तावेज़ों को पीएनजी प्रारूप में प्रस्तुत करने के लिए विकल्प प्रदान करता है।

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | का नया उदाहरण शुरू करता है[`PngViewOptions`](../pngviewoptions) वर्ग. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | का नया उदाहरण शुरू करता है[`PngViewOptions`](../pngviewoptions) वर्ग. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | का नया उदाहरण शुरू करता है[`PngViewOptions`](../pngviewoptions) वर्ग. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | का नया उदाहरण शुरू करता है[`PngViewOptions`](../pngviewoptions) वर्ग. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | का नया उदाहरण शुरू करता है[`PngViewOptions`](../pngviewoptions) वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | संग्रह फ़ाइलें विकल्प देखें। |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | सीएडी आरेखण दृश्य विकल्प। |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | डिफ़ॉल्ट फ़ॉन्ट का उपयोग तब किया जाता है जब दस्तावेज़ में उपयोग किया गया विशेष फ़ॉन्ट नहीं मिल पाता है। |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | ईमेल संदेश विकल्प देखें। |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | पाठ निष्कर्षण सक्षम करता है। |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | पिक्सल में आउटपुट छवि की ऊंचाई। |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | मेल संग्रहण डेटा फ़ाइलें दृश्य विकल्प. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | पिक्सल में आउटपुट इमेज की अधिकतम ऊंचाई. |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | पिक्सल में आउटपुट छवि की अधिकतम चौड़ाई। |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | एमएस आउटलुक डेटा फ़ाइलें विकल्प देखें। |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | पीडीएफ दस्तावेज़ विकल्प देखें। |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | प्रस्तुति प्रसंस्करण दस्तावेज़ विकल्प देखें। |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | परियोजना प्रबंधन फ़ाइलें विकल्प देखें। |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | टिप्पणियां प्रस्तुत करना सक्षम करता है. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | छिपे हुए पेजों की रेंडरिंग सक्षम करता है. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | नोट्स प्रस्तुत करना सक्षम करता है। |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | स्प्रैडशीट फ़ाइलें देखने के विकल्प. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | पाठ फ़ाइलें पेज विकल्पों में विभाजित हो रही हैं। |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | दस्तावेज़ों को संसाधित करने वाली Visio फ़ाइलें विकल्प देखें। |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | टेक्स्ट वॉटरमार्क प्रत्येक पृष्ठ पर लागू होता है। |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | यह रेंडरिंग विकल्प आपको वेब दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG के स्वरूप को अनुकूलित करने में सक्षम बनाता है। |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | पिक्सल में आउटपुट छवि की चौड़ाई। |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | यह रेंडरिंग विकल्प आपको Word दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG के स्वरूप को अनुकूलित करने में सक्षम बनाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | पृष्ठ पर दक्षिणावर्त घुमाव लागू करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | पेज रोटेशन. |

### यह सभी देखें

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* सभा [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
