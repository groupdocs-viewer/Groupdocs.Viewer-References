---
title: "get_page_key मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "पेज फ़ाइल का प्रतिनिधित्व करने वाले कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

पेज फ़ाइल का प्रतिनिधित्व करने वाले कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है।

```python
def get_page_key(cls, page_number, extension):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_number | `int` | पृष्ठ की संख्या। |
| extension | `str` | फ़ाइलनाम प्रत्यय (जिसमें अवधि "." शामिल है) जैसे ".doc"। |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `extension` None या खाली हो। |

### साथ में देखें
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
