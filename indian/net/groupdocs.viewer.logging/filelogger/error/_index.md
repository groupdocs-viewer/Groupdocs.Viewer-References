---
title: "त्रुटि"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "कंसोल में एक त्रुटि संदेश लिखता है। त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं की जानकारी प्रदान करते हैं।"
type: docs
weight: 20
url: /hi/net/groupdocs.viewer.logging/filelogger/error/
---

## FileLogger.Error method

कंसोल में एक त्रुटि संदेश लिखता है। त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं की जानकारी प्रदान करते हैं।

```csharp
public void Error(string message, Exception exception)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | String | त्रुटि संदेश। |
| एक्सेप्शन | अपवाद | अपवाद। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *message* शून्य हो तो फेंका जाता है। |
| ArgumentNullException | जब *exception* शून्य हो तो फेंका जाता है। |

### संबंधित देखें

* class [FileLogger](../../filelogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
