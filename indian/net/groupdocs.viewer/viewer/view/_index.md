---
title: View
second_title: .NET API संदर्भ के लिए GroupDocs.Viewer
description: सभ दस्तवेज़ पृष्ठं क दृश्य बनत है
type: docs
weight: 70
url: /hi/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

सभी दस्तावेज़ पृष्ठों का दृश्य बनाता है।

```csharp
public void View(ViewOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | ViewOptions | दृश्य विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*options* शून्य है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | दस्तावेज़ खोलने के लिए पासवर्ड की आवश्यकता होने पर फेंक दिया गया। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | निर्दिष्ट किया गया पासवर्ड गलत होने पर फेंक दिया गया। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | अटैचमेंट नहीं मिलने पर फेंक दिया। |

### टिप्पणियों

**और अधिक जानें**

* देखने के विभिन्न विकल्पों के बारे में अधिक जानकारी के लिए इस गाइड का अनुसरण करें: [GroupDocs.Viewer का उपयोग करके दस्तावेज़ देखने के आउटपुट को कैसे अनुकूलित करें](https://docs.groupdocs.com/display/viewernet/Viewing)

### यह सभी देखें

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

सभी दस्तावेज़ पृष्ठों का दृश्य बनाता है।

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | ViewOptions | दृश्य विकल्प। |
| cancellationToken | CancellationToken | रद्दीकरण टोकन वर्तमान दृश्य प्रक्रिया को रद्द करने का अनुरोध भेजने के लिए। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*options* शून्य है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | दस्तावेज़ खोलने के लिए पासवर्ड की आवश्यकता होने पर फेंक दिया गया। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | निर्दिष्ट किया गया पासवर्ड गलत होने पर फेंक दिया गया। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | अटैचमेंट नहीं मिलने पर फेंक दिया। |

### टिप्पणियों

**और अधिक जानें**

* देखने के विभिन्न विकल्पों के बारे में अधिक जानकारी के लिए इस गाइड का अनुसरण करें: [GroupDocs.Viewer का उपयोग करके दस्तावेज़ देखने के आउटपुट को कैसे अनुकूलित करें](https://docs.groupdocs.com/display/viewernet/Viewing)

### यह सभी देखें

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

विशिष्ट दस्तावेज़ पृष्ठों का दृश्य बनाता है।

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | ViewOptions | दृश्य विकल्प। |
| pageNumbers | Int32[] | देखने के लिए पेज नंबर। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*options* शून्य है। |
| ArgumentNullException | कब फेंका*pageNumbers* शून्य है। |
| ArgumentException | कब फेंका*pageNumbers* खाली है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | दस्तावेज़ खोलने के लिए पासवर्ड की आवश्यकता होने पर फेंक दिया गया। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | निर्दिष्ट किया गया पासवर्ड गलत होने पर फेंक दिया गया। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | अटैचमेंट नहीं मिलने पर फेंक दिया। |

### टिप्पणियों

**और अधिक जानें**

* देखने के विभिन्न विकल्पों के बारे में अधिक जानकारी के लिए इस गाइड का अनुसरण करें: [GroupDocs.Viewer का उपयोग करके दस्तावेज़ देखने के आउटपुट को कैसे अनुकूलित करें](https://docs.groupdocs.com/display/viewernet/Viewing)

### यह सभी देखें

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

विशिष्ट दस्तावेज़ पृष्ठों का दृश्य बनाता है।

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | ViewOptions | दृश्य विकल्प। |
| pageNumbers | CancellationToken | देखने के लिए पेज नंबर। |
| cancellationToken | Int32[] | रद्दीकरण टोकन प्रसंस्करण रद्द करने के लिए। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*options* शून्य है। |
| ArgumentNullException | कब फेंका*pageNumbers* शून्य है। |
| ArgumentException | कब फेंका*pageNumbers* खाली है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | दस्तावेज़ खोलने के लिए पासवर्ड की आवश्यकता होने पर फेंक दिया गया। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | निर्दिष्ट किया गया पासवर्ड गलत होने पर फेंक दिया गया। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | अटैचमेंट नहीं मिलने पर फेंक दिया। |

### टिप्पणियों

**और अधिक जानें**

* देखने के विभिन्न विकल्पों के बारे में अधिक जानकारी के लिए इस गाइड का अनुसरण करें: [GroupDocs.Viewer का उपयोग करके दस्तावेज़ देखने के आउटपुट को कैसे अनुकूलित करें](https://docs.groupdocs.com/display/viewernet/Viewing)

### यह सभी देखें

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
