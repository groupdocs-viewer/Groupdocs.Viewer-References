---
title: "is_search_term_reg_ex प्रॉपर्टी"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह प्रॉपर्टी दर्शाती है कि खोज शब्द को नियमित अभिव्यक्ति के रूप में या साधारण पाठ के रूप में माना जाना चाहिए।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

यह प्रॉपर्टी दर्शाती है कि खोज शब्द को नियमित अभिव्यक्ति के रूप में या साधारण टेक्स्ट के रूप में माना जाना चाहिए। डिफ़ॉल्ट False है — इसे साधारण टेक्स्ट के रूप में मानें।

यदि True हो, तो [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) को .NET Regex पैटर्न के रूप में व्याख्यायित किया जाता है।

यदि False हो, तो [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) को दस्तावेज़ में साधारण पाठ के रूप में खोजा जाता है।

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### साथ में देखें
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
