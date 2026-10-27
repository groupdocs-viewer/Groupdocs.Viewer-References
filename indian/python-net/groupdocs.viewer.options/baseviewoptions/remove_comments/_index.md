---
title: "remove_comments प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "जब यह प्रॉपर्टी True पर सेट की जाती है, तो यह टिप्पणी रेंडरिंग को निष्क्रिय कर देती है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

जब यह True पर सेट हो तो यह प्रॉपर्टी टिप्पणी रेंडरिंग को अक्षम करती है। डिफ़ॉल्ट रूप से यह False है, इसलिए सभी टिप्पणियां प्रदर्शित होती हैं।

PDF और WordProcessing जैसे कुछ दस्तावेज़ फ़ॉर्मेट में टिप्पणी हो सकती हैं। डिफ़ॉल्ट रूप से GroupDocs.Viewer उन्हें रेंडर करता है। जब यह विकल्प True पर सेट किया जाता है, तो टिप्पणियों को परिणामी दस्तावेज़ से बाहर रखा जा सकता है।

यह विकल्प पुरानी `RenderComments` प्रॉपर्टी को बदलता है।

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### साथ में देखें
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
