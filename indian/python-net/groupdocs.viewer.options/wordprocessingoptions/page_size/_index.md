---
title: "page_size प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "आउटपुट पृष्ठ का आकार।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

आउटपुट पृष्ठ का आकार।

डिफ़ॉल्ट मान `PageSize.Unspecified` है, जिसका अर्थ है कि पेज सेटिंग्स (Page Setup) में निर्धारित पेज आकार उपयोग किया जाता है।

HTM और HTML फ़ाइलों को रेंडर करते समय डिफ़ॉल्ट पेज आकार Letter 792 x 612 पॉइंट्स पर सेट किया जाता है।

परिणामस्वरूप, कुछ सामग्री पेज फ्रेम में फिट नहीं हो सकती।

सामग्री को फिट करने के लिए बड़ा पेज आकार सेट करें, जैसे `PageSize.A3`।

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### साथ में देखें
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
