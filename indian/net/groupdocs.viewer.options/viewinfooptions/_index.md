---
title: ViewInfoOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Viewer
description: दृश्य के बरे में जनकर प्रप्त करने के लए उपयग कए जने वले वकल्प प्रदन करत है
type: docs
weight: 570
url: /hi/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

दृश्य के बारे में जानकारी प्राप्त करने के लिए उपयोग किए जाने वाले विकल्प प्रदान करता है।

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | संग्रह फ़ाइलें विकल्प देखें। |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | सीएडी आरेखण दृश्य विकल्प। |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | डिफ़ॉल्ट फ़ॉन्ट का उपयोग तब किया जाता है जब दस्तावेज़ में उपयोग किया गया विशेष फ़ॉन्ट नहीं मिल पाता है। |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | ईमेल संदेश विकल्प देखें। |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | इंगित करता है कि पाठ निष्कर्षण सक्षम है। |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | छवि ऊंचाई (केवल पीएनजी/जेपीजी को प्रस्तुत करने के लिए) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | मेल संग्रहण डेटा फ़ाइलें दृश्य विकल्प. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | आउटपुट छवि की अधिकतम ऊंचाई (केवल पीएनजी/जेपीजी को प्रस्तुत करने के लिए) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | आउटपुट छवि की अधिकतम चौड़ाई (केवल पीएनजी/जेपीजी को प्रस्तुत करने के लिए) |
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
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | यह रेंडरिंग विकल्प आपको वेब दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG के स्वरूप को अनुकूलित करने में सक्षम बनाता है। |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | इमेज की चौड़ाई (सिर्फ़ PNG/JPG में रेंडर करने के लिए) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | यह रेंडरिंग विकल्प आपको Word दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG के स्वरूप को अनुकूलित करने में सक्षम बनाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) HTML. में रेंडर करते समय दृश्य के बारे में जानकारी प्राप्त करने के लिए वर्ग |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) HTML. में रेंडर करते समय दृश्य के बारे में जानकारी प्राप्त करने के लिए वर्ग |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) JPG. में रेंडर करते समय दृश्य के बारे में जानकारी प्राप्त करने के लिए वर्ग |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) JPG. में रेंडर करते समय दृश्य के बारे में जानकारी प्राप्त करने के लिए वर्ग |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) PNG. में रेंडर करते समय देखने के बारे में जानकारी प्राप्त करने के लिए क्लास |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) PNG. में रेंडर करते समय देखने के बारे में जानकारी प्राप्त करने के लिए क्लास |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) वर्ग पर आधारित है[`HtmlViewOptions`](../htmlviewoptions) वस्तु. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) वर्ग पर आधारित है[`JpgViewOptions`](../jpgviewoptions) वस्तु. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | का नया उदाहरण शुरू करता है[`ViewInfoOptions`](../viewinfooptions) वर्ग पर आधारित है[`PngViewOptions`](../pngviewoptions) वस्तु. |

### यह सभी देखें

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* सभा [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
