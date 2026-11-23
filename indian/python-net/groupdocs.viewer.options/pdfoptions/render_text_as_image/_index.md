---
title: "render_text_as_image प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह विकल्प PDF फ़ाइलों में टेक्स्ट को HTML आउटपुट में इमेज के रूप में रेंडर करने को सक्षम करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 2090
---


## render_text_as_image property

यह विकल्प PDF फ़ाइलों में टेक्स्ट को HTML आउटपुट में इमेज के रूप में रेंडर करने को सक्षम करता है।

जब यह विकल्प True पर सेट किया जाता है, तो GroupDocs.Viewer HTML आउटपुट में टेक्स्ट को इमेज के रूप में रेंडर करता है। इससे टेक्स्ट चयन योग्य नहीं रहता और कैरेक्टर रेंडरिंग में सुधार होता है, जिससे HTML में PDF जैसा रूप मिलता है। डिफ़ॉल्ट मान False है।

यह विकल्प HTML में रेंडर करने के लिए उपलब्ध है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

### Definition:
```python
@property
def render_text_as_image(self):
    ...
@render_text_as_image.setter
def render_text_as_image(self, value):
    ...
```

### साथ में देखें
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
