---
title: "get_file_key मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "फ़ाइल का प्रतिनिधित्व करने वाले कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

फ़ाइल का प्रतिनिधित्व करने वाले कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है।

```python
def get_file_key(cls, extension):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| extension | `str` | फ़ाइलनाम प्रत्यय (जिसमें अवधि "." शामिल है) जैसे ".doc"। |

**Returns:** str: Unique identifier for the cache entry that represents file.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `extension` None है या खाली है। |

### साथ में देखें
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
