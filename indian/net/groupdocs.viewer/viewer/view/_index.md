---
title: "View"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "सभी दस्तावेज़ पृष्ठों का व्यू बनाता है।"
type: docs
weight: 90
url: /hi/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

सभी दस्तावेज़ पृष्ठों का व्यू बनाता है।

```csharp
public void View(ViewOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | ViewOptions | व्यू विकल्प। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *options* null हो तो फेंका जाता है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | जब attachment नहीं मिल पाती है तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### संबंधित देखें

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

सभी दस्तावेज़ पृष्ठों का व्यू बनाता है।

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | ViewOptions | व्यू विकल्प। |
| cancellationToken | CancellationToken | वर्तमान व्यू प्रक्रिया को रद्द करने के लिए अनुरोध भेजने हेतु कैंसलेशन टोकन। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *options* null हो तो फेंका जाता है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | जब attachment नहीं मिल पाती है तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### संबंधित देखें

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है।

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | ViewOptions | व्यू विकल्प। |
| pageNumbers | Int32[] | देखने के लिए पृष्ठ संख्याएँ। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *options* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *pageNumbers* null हो तो फेंका जाता है। |
| ArgumentException | जब *pageNumbers* खाली हो तो फेंका जाता है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | जब attachment नहीं मिल पाती है तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### संबंधित देखें

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

विशिष्ट दस्तावेज़ पृष्ठों का व्यू बनाता है।

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | ViewOptions | व्यू विकल्प। |
| pageNumbers | CancellationToken | देखने के लिए पृष्ठ संख्याएँ। |
| cancellationToken | Int32[] | प्रसंस्करण को रद्द करने के लिए कैंसलेशन टोकन। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *options* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *pageNumbers* null हो तो फेंका जाता है। |
| ArgumentException | जब *pageNumbers* खाली हो तो फेंका जाता है। |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक हो तो फेंका जाता है। |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | जब निर्दिष्ट पासवर्ड गलत हो तो फेंका जाता है। |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | जब attachment नहीं मिल पाती है तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### संबंधित देखें

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
