---
title: "horizontal_resolution प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "जनरेट किए गए इमेजों के लिए डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

उत्पन्न छवियों के लिए डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन। यह विकल्प केवल वर्ड प्रोसेसिंग दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है।

डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान 72 DPI है; अधिकतम संभव मान 600 DPI है। यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं के बाहर है, तो निकटतम सीमा (न्यूनतम या अधिकतम) लागू की जाएगी।

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### साथ में देखें
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
