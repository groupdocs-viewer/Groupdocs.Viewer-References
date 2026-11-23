---
title: "get_attachment_key मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "ऐटेचमेंट फ़ाइल का प्रतिनिधित्व करने वाले कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

ऐटेचमेंट फ़ाइल का प्रतिनिधित्व करने वाले कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है।

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| attachment_id | `str` | एकल फ़ाइल के संदर्भ में अनन्य पहचानकर्ता अटैचमेंट का। |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `attachment_id` जब null या खाली हो तो फेंका जाता है। |

### साथ में देखें
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
