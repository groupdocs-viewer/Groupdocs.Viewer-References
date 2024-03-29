---
title: Encoding
second_title: .NET API संदर्भ के लिए GroupDocs.Viewer
description: टेक्स्टआधरत फ़इलें य ईमेल संदेश जैसे खलते समय उपयग क जने वल एन्कडंगCSVgroupdocs.viewer/filetype/csv  TXTgroupdocs.viewer/filetype/txt  औरMSGgroupdocs.viewer/filetype/msg . डफ़ल्ट मन हैUTF8 .
type: docs
weight: 30
url: /hi/net/groupdocs.viewer.options/loadoptions/encoding/
---
## LoadOptions.Encoding property

टेक्स्ट-आधारित फ़ाइलें या ईमेल संदेश जैसे खोलते समय उपयोग की जाने वाली एन्कोडिंग[`CSV`](../../../groupdocs.viewer/filetype/csv) , [`TXT`](../../../groupdocs.viewer/filetype/txt) , और[`MSG`](../../../groupdocs.viewer/filetype/msg) . डिफ़ॉल्ट मान हैUTF8 .

```csharp
public Encoding Encoding { get; set; }
```

### टिप्पणियों

**और अधिक जानें**

* [Excel और Apple Numbers स्प्रेडशीट को HTML, PDF और छवि फ़ाइलों के रूप में प्रस्तुत करें](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/)
* [टेक्स्ट दस्तावेज़ों को HTML, PDF और छवि फ़ाइलों के रूप में प्रस्तुत करें](https://docs.groupdocs.com/viewer/net/render-text-files)
* [ईमेल संदेशों को HTML, PDF, PNG और JPEG फ़ाइलों के रूप में रेंडर करें](https://docs.groupdocs.com/viewer/net/render-email-messages/)

### उदाहरण

उदाहरण इस विकल्प के सामान्य उपयोग को प्रदर्शित करता है।

```csharp
LoadOptions loadOptions = new LoadOptions();
loadOptions.Encoding = Encoding.ASCII; // एन्कोडिंग सेट करें

using (Viewer viewer = new Viewer("message.txt", loadOptions))
{
    HtmlViewOptions viewOptions = 
        HtmlViewOptions.ForEmbeddedResources();

    viewer.View(viewOptions);
}
```

### यह सभी देखें

* class [LoadOptions](../../loadoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../loadoptions)
* सभा [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
