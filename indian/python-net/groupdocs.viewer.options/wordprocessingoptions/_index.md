---
title: "WordProcessingOptions क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Word दस्तावेज़ों को रेंडर करने के विकल्प शामिल करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Word दस्तावेज़ों को रेंडर करने के विकल्प शामिल करता है।

विवरण के लिए, https://docs.groupdocs.com/viewer/net/render-word-documents/ पर दस्तावेज़ देखें।

WordProcessingOptions टाइप निम्नलिखित सदस्य प्रदर्शित करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | वर्ड प्रोसेसिंग दस्तावेज़ों को रेंडर करने के विकल्पों को प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | इन विकल्पों की पूरी गहरी प्रति बनाता है और लौटाता है। |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | निर्धारित करता है कि निर्दिष्ट [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) इंस्टेंस इस इंस्टेंस के बराबर है या नहीं। |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | पृष्ठ का निचला मार्जिन। |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | विकल्प अरबी, हिब्रू, भारतीय लैटिन-आधारित, या सायरिलिक-आधारित लिपियों को रेंडर करते समय करनिंग और अन्य OpenType सुविधाओं को सक्षम करता है। |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | उत्पन्न छवियों के लिए डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन। यह विकल्प केवल वर्ड प्रोसेसिंग दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है। |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | पृष्ठ का बायाँ मार्जिन। |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | लोड किए गए वर्ड प्रोसेसिंग दस्तावेज़ के पृष्ठ क्रमांक स्थान, जो पृष्ठ क्रमांक को जबरन लागू कर सकता है; डिफ़ॉल्ट रूप से यह `WordsPageNumberLocation.not_apply` है, जिससे दस्तावेज़ अपरिवर्तित रहता है। |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | आउटपुट पृष्ठ का आकार। |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | यह प्रॉपर्टी ट्रैक किए गए परिवर्तन (संशोधन) के रेंडरिंग को सक्षम करती है। |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | पृष्ठ का दायाँ मार्जिन। |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | पृष्ठ का शीर्ष मार्जिन पॉइंट्स में। |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | विकल्प HTML या PDF रेंडरिंग के लिए True सेट होने पर सामग्री तालिका से नेविगेशन को अक्षम करता है। |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | यह प्रॉपर्टी निर्धारित करती है कि वर्ड प्रोसेसिंग दस्तावेज़ को HTML, PDF, PNG, या JPEG फ़ॉर्मेट में सहेजने से पहले कुछ प्रकार के फ़ील्ड अपडेट किए जाएँ या नहीं। डिफ़ॉल्ट रूप से यह True है, जिसका अर्थ है फ़ील्ड अपडेट होते हैं। |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | उत्पन्न छवियों के लिए डॉट्स प्रति इंच में लंबवत रेज़ोल्यूशन, जो केवल वर्ड प्रोसेसिंग दस्तावेज़ों को PNG या JPEG फ़ॉर्मेट में रेंडर करते समय उपयोग किया जाता है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
