---
title: "max_items_in_folder प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या।

Outlook डेटा फ़ाइलें बड़ी हो सकती हैं और सभी संदेश प्राप्त करने में काफी समय लग सकता है। यह प्रॉपर्टी रेंडर किए जाने वाले संदेशों या आइटमों की अधिकतम संख्या को सीमित करती है। डिफ़ॉल्ट मान `50` है। सभी संदेश रेंडर करने के लिए, मान को `0` सेट करें।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### साथ में देखें
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
