---
title: "Security क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "PDF दस्तावेज़ सुरक्षा विकल्प।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

PDF दस्तावेज़ सुरक्षा विकल्प।

विवरण के लिए, दस्तावेज़ देखें।

Security प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) क्लास का एक उदाहरण प्रारंभ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड। |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | PDF दस्तावेज़ की अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण। |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
`Security` का उपयोग करने वाले कार्य गाइड:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
