---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Word क्लास की नई इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

[`Word`](/viewer/python-net/groupdocs.viewer.results/word/) का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

[`Word`](/viewer/python-net/groupdocs.viewer.results/word/) का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| word | `str` | शब्द। |
| x | `float` | पृष्ठ लेआउट में सबसे बाएँ उच्चतम बिंदु का X निर्देशांक जहाँ वह आयत शुरू होती है जिसमें word शामिल है। |
| y | `float` | पृष्ठ लेआउट में सबसे बाएँ उच्चतम बिंदु का Y निर्देशांक जहाँ वह आयत शुरू होती है जिसमें word शामिल है। |
| width | `float` | जिस आयत में शब्द शामिल है, उसकी चौड़ाई। |
| height | `float` | जिस आयत में शब्द शामिल है, उसकी ऊँचाई। |
| characters | `List[Character]` | शब्द में शामिल अक्षर। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `characters` null हो। |

### साथ में देखें
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
