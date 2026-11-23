---
title: "render_header_footer_placeholders प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी स्लाइड के हेडर और फुटर में प्लेसहोल्डर के रेंडरिंग को सक्षम करती है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

यह प्रॉपर्टी स्लाइड के हेडर और फुटर में प्लेसहोल्डर के रेंडरिंग को सक्षम करती है।

यह डिफ़ॉल्ट रूप से निष्क्रिय है (`False`)। यह विकल्प प्रेजेंटेशन के सभी चार रेंडरिंग मोड्स पर लागू होता है: HTML, PDF, PNG, और JPEG। यह तब लागू नहीं होता जब प्रेजेंटेशन को शुद्ध HTML/CSS मार्कअप में रेंडर किया जाता है, जैसे कि [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/) का उपयोग करके।

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### साथ में देखें
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
