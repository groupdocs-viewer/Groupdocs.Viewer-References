---
title: "disable_font_license_verifications प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए यह प्रॉपर्टी किसी भी लाइसेंस प्रतिबंध को निष्क्रिय करती है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

वर्तमान XPS/OXPS दस्तावेज़ में सभी फ़ॉन्ट्स के लिए यह प्रॉपर्टी किसी भी लाइसेंस प्रतिबंध को निष्क्रिय करती है।

फ़ॉन्ट के लाइसेंस द्वारा प्रतिबंधित होने पर कई फ़ॉन्ट संचालन नहीं किए जा सकते। उदाहरण के लिए, यदि लाइसेंस नियम उस फ़ॉन्ट के लिए एम्बेडिंग को निष्क्रिय करते हैं तो कुछ फ़ॉन्ट को PDF दस्तावेज़ में एम्बेड नहीं किया जा सकता। यह विकल्प आपको इन नियमों की सत्यापन को छोड़ने की अनुमति देता है।

इस फ़्लैग का उपयोग करते समय सावधान रहें। जब इसे सेट किया जाता है, तो इसका अर्थ है कि इस फ़्लैग को सेट करने वाला व्यक्ति संभावित लाइसेंस या कानूनी उल्लंघनों की पूरी ज़िम्मेदारी लेता है। यह दृढ़ता से अनुशंसा की जाती है कि आप इस फ़्लैग का उपयोग केवल तभी करें जब आपको पूरी तरह यकीन हो कि आप कॉपीराइट कानून का उल्लंघन नहीं कर रहे हैं। डिफ़ॉल्ट मान `False` है।

कोड उदाहरण के लिए, दस्तावेज़ देखें https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### साथ में देखें
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
