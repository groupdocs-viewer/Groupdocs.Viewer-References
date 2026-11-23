---
title: "PdfOptimizationOptions क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "आउटपुट PDF फ़ाइल पर लागू करने के लिए PDF अनुकूलन विकल्पों को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

आउटपुट PDF फ़ाइल पर लागू करने के लिए PDF अनुकूलन विकल्पों को दर्शाता है।

विवरण और कोड नमूनों के लिए, दस्तावेज़ पृष्ठ देखें।

PdfOptimizationOptions प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | MaxResolution विकल्प के डिफ़ॉल्ट मान को 300 और ImageQuality विकल्प को 100 पर प्रारंभ करता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | यह प्रॉपर्टी आउटपुट PDF फ़ाइल में छवियों को संपीड़ित करने को सक्षम करती है। |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | यह प्रॉपर्टी आउटपुट PDF फ़ाइल को ग्रेस्केल में बदलने को सक्षम करती है। |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | आउटपुट PDF फ़ाइल में छवि गुणवत्ता, प्रतिशत के रूप में व्यक्त। |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | यह प्रॉपर्टी वेब ब्राउज़र के साथ ऑनलाइन देखने के लिए आउटपुट PDF फ़ाइल का अनुकूलन सक्षम करती है। |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | आउटपुट PDF फ़ाइल में अधिकतम रिज़ॉल्यूशन। |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | यह प्रॉपर्टी PDF फ़ाइलों में स्प्रेडशीट्स के अनुकूलन को सक्षम करती है। |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | यह प्रॉपर्टी आउटपुट PDF फ़ाइल से एनोटेशन हटाने को सक्षम करती है। |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | यह प्रॉपर्टी PDF फ़ाइल से फ़ॉर्म फ़ील्ड हटाने को सक्षम करती है। |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | यह प्रॉपर्टी PDF फ़ाइल से अप्रयुक्त (अनाथ) ऑब्जेक्ट्स को हटाती है। |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | यह प्रॉपर्टी PDF फ़ाइल से उन अप्रयुक्त (अनाथ) स्ट्रीम्स को हटाती है जो पेज रिसोर्स डिक्शनरी में संदर्भित हैं लेकिन पेज सामग्री में कभी उपयोग नहीं होते। डिफ़ॉल्ट रूप से अक्षम (`False`); इसे `True` पर सेट करने से आउटपुट PDF का आकार घटता है। |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | यह प्रॉपर्टी आउटपुट PDF फ़ाइल में अधिकतम रिज़ॉल्यूशन सेट करने को सक्षम करती है। |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | यह प्रॉपर्टी आउटपुट PDF फ़ाइल में फ़ॉन्ट्स को उपसमुच्चय बनाती है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # तेज़ वेब प्रीव्यू के लिए लीनियराइज़ेशन सक्षम करें
        view_options.pdf_optimization_options.lineriaze = True
        # आकार कम करने के लिए एनोटेशन और फ़ॉर्म फ़ील्ड हटाएँ
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
