---
title: "fixed_layout प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "फ़िक्स्ड लेआउट विकल्प PDF और EPUB दस्तावेज़ों को फ़िक्स्ड लेआउट के साथ HTML में रेंडर करने को सक्षम करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

फ़िक्स्ड लेआउट विकल्प PDF और EPUB दस्तावेज़ों को फ़िक्स्ड लेआउट के साथ HTML में रेंडर करने को सक्षम करता है।

PDF और EPUB दस्तावेज़ प्रारंभ में एक स्थिर लेआउट के साथ HTML में रेंडर किए जाते हैं ताकि स्रोत दस्तावेज़ की उपस्थिति बनी रहे। यह स्थिर लेआउट का अर्थ है कि सभी HTML तत्वों की एक निर्धारित आकार वाले कंटेनर में सटीक स्थितियाँ होती हैं। ब्राउज़र विंडो का आकार बदलने से दस्तावेज़ में तत्वों की स्थिति और आकार प्रभावित नहीं होते।

यह विकल्प केवल HTML में रेंडर करने पर उपलब्ध है। डिफ़ॉल्ट मान `True` है। फ्लुइड लेआउट के साथ रेंडर करने के लिए, इस प्रॉपर्टी को `False` सेट करें।

फ्लुइड लेआउट में रेंडर करते समय, छवियों को छोड़ दिया जाता है। टेक्स्ट सामग्री वाले PDF दस्तावेज़ को रेंडर करते समय फ्लुइड लेआउट का उपयोग करें।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### साथ में देखें
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
