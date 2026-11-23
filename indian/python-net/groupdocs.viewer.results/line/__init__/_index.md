---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Line क्लास की नई इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

[`Line`](/viewer/python-net/groupdocs.viewer.results/line/) का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

[`Line`](/viewer/python-net/groupdocs.viewer.results/line/) क्लास का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| line | `str` | रेखा। |
| x | `float` | पृष्ठ लेआउट में सबसे बाएँ उच्चतम बिंदु का X निर्देशांक जहाँ वह आयत शुरू होती है जिसमें line शामिल है। |
| y | `float` | पृष्ठ लेआउट में सबसे बाएँ उच्चतम बिंदु का Y निर्देशांक जहाँ वह आयत शुरू होती है जिसमें line शामिल है। |
| width | `float` | जिस आयत में line शामिल है, उसकी चौड़ाई (पिक्सेल में)। |
| height | `float` | जिस आयत में line शामिल है, उसकी ऊँचाई (पिक्सेल में)। |
| words | `List[Word]` | लाइन में शामिल शब्द। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `line` जब null या खाली हो, या `words` जब null हो, तो उत्पन्न होता है। |

### साथ में देखें
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
