---
title: "disable_copy_protection प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "HTML में रेंडर करते समय यह प्रॉपर्टी कंटेंट कॉपी प्रोटेक्शन को निष्क्रिय करती है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

HTML में रेंडर करते समय यह प्रॉपर्टी कंटेंट कॉपी प्रोटेक्शन को निष्क्रिय करती है।

जब PDF फ़ाइलों को HTML में रेंडर किया जाता है और टेक्स्ट व इमेज को कॉपी करने से बचाने के लिए सुरक्षा होती है, तो GroupDocs.Viewer HTML BODY टैग में एक `inert` HTML एट्रिब्यूट जोड़ता है। डिफ़ॉल्ट मान `False` है, जिसका अर्थ है कि `inert` एट्रिब्यूट केवल तब जोड़ा जाता है जब PDF दस्तावेज़ संरक्षित हो।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### साथ में देखें
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
