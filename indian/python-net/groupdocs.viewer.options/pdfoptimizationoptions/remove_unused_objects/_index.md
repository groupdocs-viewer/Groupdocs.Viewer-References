---
title: "remove_unused_objects प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी PDF फ़ाइल से अप्रयुक्त (अनाथ) ऑब्जेक्ट्स को हटाती है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

यह प्रॉपर्टी PDF फ़ाइल से अप्रयुक्त (अनाथ) ऑब्जेक्ट्स को हटाती है।

ये ऑब्जेक्ट्स PDF दस्तावेज़ में रखे गए हैं लेकिन किसी भी पृष्ठ के रिसोर्स डिक्शनरी से संदर्भित नहीं होते और इसलिए बिल्कुल भी उपयोग नहीं होते। इस प्रॉपर्टी को सक्रिय करने (`True`) से आउटपुट PDF दस्तावेज़ का आकार घटेगा। डिफ़ॉल्ट रूप से यह अक्षम (`False`) है।

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### साथ में देखें
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
