---
title: "wrap_images_in_svg प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी आउटपुट HTML दस्तावेज़ में प्रत्येक इमेज को SVG टैग में रैप करके आउटपुट क्वालिटी सुधारती है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

यह प्रॉपर्टी आउटपुट HTML दस्तावेज़ में प्रत्येक इमेज को SVG टैग में रैप करके आउटपुट क्वालिटी सुधारती है।

डिफ़ॉल्ट रूप से, जब PDF और Page Layout फ़ाइलों को HTML में रेंडर किया जाता है, सभी इमेज एक ही PNG इमेज के रूप में रेंडर होते हैं। रेंडर किया गया PNG इमेज आउटपुट HTML दस्तावेज़ की पृष्ठभूमि के रूप में उपयोग किया जाता है।

यह विकल्प PDF और Page Layout फ़ाइल फ़ॉर्मेट को एम्बेडेड और एक्सटर्नल संसाधनों के साथ HTML में रेंडर करने पर उपलब्ध है। यह आउटपुट HTML दस्तावेज़ में प्रत्येक इमेज को SVG टैग में रैप करने को सक्षम करता है। डिफ़ॉल्ट मान False है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### साथ में देखें
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
