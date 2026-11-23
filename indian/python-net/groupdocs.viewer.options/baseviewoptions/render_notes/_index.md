---
title: "render_notes प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी कुछ फ़ॉर्मेट्स के लिए नोट्स और एनोटेशन के रेंडरिंग को सक्षम करती है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

यह प्रॉपर्टी कुछ फ़ॉर्मेट्स के लिए नोट्स और एनोटेशन के रेंडरिंग को सक्षम करती है।

कुछ फ़ॉर्मेट, जैसे प्रेज़ेंटेशन या Microsoft प्रोजेक्ट फ़ाइलें, नोट्स शामिल कर सकते हैं। साथ ही, PDF फ़ाइलों में पॉप‑अप एनोटेशन (बैलून संकेत) हो सकते हैं जो डिफ़ॉल्ट रूप से छिपे होते हैं और केवल तब PDF व्यूअर में दिखाई देते हैं जब माउस कर्सर को उन पर ले जाया जाता है। डिफ़ॉल्ट रूप से, GroupDocs.Viewer ऐसे नोट्स और एनोटेशन को रेंडर नहीं करता (`False`)। इसे करने के लिए, इस प्रॉपर्टी को `True` सेट करें।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### साथ में देखें
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
